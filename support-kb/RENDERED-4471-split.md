# #4471 · three problems merged as one

owner **support desk** · status **known** · reviewed 2026-10-28

#4471 was marked known as one parser bug. Its 412 unique reports (427 export rows, 15 repeated) hold three separate problems. Each now has its own ticket.

> **Not one issue.** A parser fix will not close the form-hint reports or the one-day-shift reports.

## What was merged

412 reports merged into #4471 · 2 causes (by the desk's cause table)

| cause | reports | tagged as | tenants | seen | |
| --- | --- | --- | --- | --- | --- |
| `parser` | 379 | parser ×356 · hint ×23 | 11 | 2026-04-01 → 2026-10-04 | #4471 |
| `hint` | 33 | hint ×18 · parser ×15 | 3 | 2026-04-17 → 2026-09-22 | not this ticket — no ticket of its own |

5 reports read as a one-day move; filed under `parser` by tenant.

## Tickets

| problem | reports | ticket |
| --- | --- | --- |
| Parser reads day-first dates month first | 374 | [#1](https://github.com/edpittol/mega-s01e03-4471/issues/1) |
| booking-v3 form hint says MM/DD/YYYY to day-first tenants | 33 | [#2](https://github.com/edpittol/mega-s01e03-4471/issues/2) |
| Invites one day off (time-zone or date-boundary suspect) | 5 | [#3](https://github.com/edpittol/mega-s01e03-4471/issues/3) |

374 + 33 + 5 = 412.

## Lessons

- Intake tags are a guess: 15 of the 33 form-hint reports were tagged `parser`.
- Merging on subject hides different causes. Check tenant and channel before you merge.

desk ref **DR-ANTC-N77G**
