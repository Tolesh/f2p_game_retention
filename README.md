# Mobile Game Analytics — Retention, A/B, Event KPIs

Мини-кейс по аналитике F2P-игры: считаю **retention** по дням от регистрации, оцениваю **A/B** промо-офферы и формирую набор **метрик для тематических ивентов**.

## Как запустить

```bash

docker compose up -d

# затем открыть Jupyter: http://localhost:8888/lab?token=jlab

## Короткий README внутри папки проекта
```bash

mkdir -p notebooks/03-karpov-v1

cat > notebooks/03-karpov-v1/00_README.md <<'MD'

# 03 — karpov v1 (mobile game analytics)

**Цель:** посчитать retention, оценить A/B офферов, предложить KPI для ивента.  

**Данные:** в `data/` рядом с ноутбуками (в git не попадают).  

**Запуск:** открыть ноутбуки по порядку в Jupyter.

