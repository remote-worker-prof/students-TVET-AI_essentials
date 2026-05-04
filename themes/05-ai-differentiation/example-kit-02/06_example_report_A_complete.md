# 06. Обезличенный пример полного результата

---

## Назначение примера
Пример демонстрирует формально корректное заполнение артефактов без привязки к персональным данным.

---

## Пример A1

```text
discipline: <дисциплина>
topic: <узкая тема>
audience: <курс СПО>
learning_goal: <измеримая цель>
pretest_6q: <6 вопросов>
answer_key: <ключ к 6 вопросам>
score: 4/6
assigned_level: standard
```

---

## Пример A2

```text
level: basic
theory: ...
practice_block: ...
checkpoint_test: ...
checkpoint_key: ...
criteria: ...
teacher_notes: ...
```

```text
level: standard
theory: ...
practice_block: ...
checkpoint_test: ...
checkpoint_key: ...
criteria: ...
teacher_notes: ...
```

```text
level: advanced
theory: ...
practice_block: ...
checkpoint_test: ...
checkpoint_key: ...
criteria: ...
teacher_notes: ...
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
| st-101 | <disc> | <topic> | 2 | basic | /materials/basic | 2026-05-01T09:00:00 |
| st-102 | <disc> | <topic> | 4 | standard | /materials/standard | 2026-05-01T09:02:00 |
| st-103 | <disc> | <topic> | 6 | advanced | /materials/advanced | 2026-05-01T09:04:00 |
