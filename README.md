Кейс по аналитике F2P-игры: считаю **retention** по дням от регистрации, оцениваю **A/B** промо-офферы и формирую **метрики для тематических ивентов**.
##  Как запустить
```bash
docker compose up -d
# затем открыть Jupyter: http://localhost:8888/lab?token=jlab
# 2) Локальный README внутри папки проекта
```bash
cat > notebooks/03-karpov-v1/00_README.md <<'MD'

# 03 — karpov v1 (mobile game analytics)

**Цель:** посчитать retention, оценить A/B офферов, предложить KPI для ивента.  

**Данные:** `data/*.csv` (локально, в git не попадают).  

**Как запускать:** открыть ноутбуки по порядку и положить датасеты в `data/`.

## Ключевые метрики
- **Retention**: D1, D7, D30; когорты по регистрации.  

- **A/B**: CR\_pay, ARPU, ARPPU, uplift; z-test/Bootstrap.  

- **Event**: participation, stage funnel, reward rate, avg progress/day, event ARPU, post-event retention.

