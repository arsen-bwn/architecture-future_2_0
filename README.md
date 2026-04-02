# Яндекс Практикум. Проект: кейс «Будущее 2.0»


---

## Навигация по заданиям

| Задание | Содержание | Основные файлы |
|--------|------------|----------------|
| **Task 1** | Целевая архитектура (C4), проблемные места, приоритизация | [Task1/c4-target-architecture.puml](Task1/c4-target-architecture.puml), [Task1/problem-analysis-and-prioritization.md](Task1/problem-analysis-and-prioritization.md) |
| **Task 2** | Домены, DFD, потоки данных, аргументация | [Task2/dfd-data-flows.puml](Task2/dfd-data-flows.puml), [Task2/domain-argumentation.md](Task2/domain-argumentation.md) |
| **Task 3** | Техрадар, роадмап, обоснование изменений | [Task3/tech-radar.md](Task3/tech-radar.md), [Task3/tech-radar.drawio](Task3/tech-radar.drawio), [Task3/roadmap.md](Task3/roadmap.md), [Task3/roadmap.drawio](Task3/roadmap.drawio), [Task3/changes-justification.md](Task3/changes-justification.md) |
| **Task 4** | Terraform (IaaS), диаграмма автоматизации, обоснование | [Task4/main.tf](Task4/main.tf), [Task4/variables.tf](Task4/variables.tf), [Task4/outputs.tf](Task4/outputs.tf), [Task4/terraform.tfvars](Task4/terraform.tfvars), [Task4/deployment-automation.drawio](Task4/deployment-automation.drawio), [Task4/justification.md](Task4/justification.md) |

---

## Task 1 — архитектура и приоритеты

- Диаграмма **C4 (контейнеры)** в PlantUML: [`Task1/c4-target-architecture.puml`](Task1/c4-target-architecture.puml)  
- Анализ проблем, матрица Эйзенхауэра, MoSCoW: [`Task1/problem-analysis-and-prioritization.md`](Task1/problem-analysis-and-prioritization.md)

## Task 2 — домены и DFD

- **DFD** (PlantUML): [`Task2/dfd-data-flows.puml`](Task2/dfd-data-flows.puml)  
- Обоснование доменов и выгод для бизнеса: [`Task2/domain-argumentation.md`](Task2/domain-argumentation.md)

## Task 3 — техрадар и роадмап

- Технический радар (таблица по кольцам): [`Task3/tech-radar.md`](Task3/tech-radar.md)  
- Визуализация радара (draw.io): [`Task3/tech-radar.drawio`](Task3/tech-radar.drawio.png)  
- Роадмап (текст): [`Task3/roadmap.md`](Task3/roadmap.md)  
- Роадмап (draw.io): [`Task3/roadmap.drawio`](Task3/roadmap.drawio.png)  
- Обоснование этапов: [`Task3/changes-justification.md`](Task3/changes-justification.md)

## Task 4 — Terraform и диаграмма развёртывания

- Конфигурация Terraform: [`Task4/main.tf`](Task4/main.tf), [`Task4/variables.tf`](Task4/variables.tf), [`Task4/outputs.tf`](Task4/outputs.tf), [`Task4/terraform.tfvars`](Task4/terraform.tfvars), lock-файл [`.terraform.lock.hcl`](Task4/.terraform.lock.hcl)  
- Подробная **диаграмма автоматизации** (draw.io): [`Task4/deployment-automation.drawio`](Task4/deployment-automation.drawio.png)  
- Упрощённая схема (PNG): [`Task4/diagram.png`](Task4/diagram.png)  
- Обоснование ресурсов и IaC: [`Task4/justification.md`](Task4/justification.md)

Перед `terraform plan` / `apply` задайте `YC_TOKEN` (см. раздел в [`Task4/justification.md`](Task4/justification.md)).

