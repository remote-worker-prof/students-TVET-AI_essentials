# 06. Обезличенный пример полного результата

---

## Назначение примера
Пример демонстрирует формально корректное заполнение артефактов без привязки к персональным данным.  
Используется тот же демонстрационный предметный образец, что и в основном наборе.

---

## Демонстрационный образец
- `discipline`: информатика
- `topic`: ветвление в алгоритмах (`if/else`)
- `audience`: 1 курс СПО
- `learning_goal`: выбор корректной ветви алгоритма по условию

---

## Пример A1

```text
discipline: информатика
topic: ветвление в алгоритмах (if/else)
audience: 1 курс СПО
learning_goal: выбор корректной ветви алгоритма по условию
pretest_6q: 6 вопросов по базовым правилам if/else
answer_key: ключ к 6 вопросам
score: 4/6
assigned_level: standard
```

Пояснение: значение `4/6` соответствует уровню `standard`.

---

## Пример A2

```text
level: basic
theory: базовые правила условного оператора if/else.
practice_block: задачи на определение выполняемой ветви.
checkpoint_test: 3 вопроса на распознавание условий.
checkpoint_key: эталонные ответы к 3 вопросам.
criteria: корректность выбора ветви и терминов.
teacher_notes: опора на простые логические выражения.
```

```text
level: standard
theory: запись условий с порогами и диапазонами.
practice_block: задачи на формулирование и проверку условий.
checkpoint_test: 3 вопроса с кратким обоснованием.
checkpoint_key: критерии проверки логики условия.
criteria: корректность условия и полнота объяснения.
teacher_notes: контроль противоречивых условий.
```

```text
level: advanced
theory: анализ сложных логических условий.
practice_block: исправление дефектных условий и перенос в новую задачу.
checkpoint_test: мини-кейс на анализ и коррекцию.
checkpoint_key: эталон шага анализа и исправления.
criteria: точность анализа и корректность коррекции.
teacher_notes: контроль причинно-следственной логики.
```

---

## Пример A3

```text
flow_steps: Yandex Forms -> Albato -> Google Sheets
field_mapping: discipline/topic/score/assigned_level/material_link
routing_rules(2/4/6): 0-2 basic; 3-4 standard; 5-6 advanced
run_evidence: 3 подтверждения прогонов
result_log: минимум 3 строки
```

### Пример строк журнала

| student_id | discipline | topic | score | assigned_level | material_link | timestamp |
|---|---|---|---|---|---|---|
| st-101 | информатика | ветвление в алгоритмах (if/else) | 2 | basic | /materials/basic | 2026-05-01T09:00:00 |
| st-102 | информатика | ветвление в алгоритмах (if/else) | 4 | standard | /materials/standard | 2026-05-01T09:02:00 |
| st-103 | информатика | ветвление в алгоритмах (if/else) | 6 | advanced | /materials/advanced | 2026-05-01T09:04:00 |
