Day 1 notes
# Day 1 — Notes

## What I did
- Generated the **analyst-starter-pack** in `~/projects/analyst-starter-pack`.
- Verified outputs: `day1_daily_revenue.csv`, `day1_signups_avg7.csv`, and `ecom.sqlite`.
- Practiced terminal basics: `cd`, `ls`, `head`, and how to avoid running files as commands.

## SQL #1 — Daily revenue (last 30 days, completed orders)
- CTE to get latest completed order date → filtered last 30 days.
- `SUM(order_revenue)` grouped by `DATE(order_ts)`.
- Takeaways:
  - Filtering to `status='completed'` avoids negative revenue from refunds.
  - Weekend vs weekday pattern: ____  
  - Max day & value: ____ on ____.

## SQL #2 — 7-day rolling average of signups
- Built daily counts from `customers.signup_date`.
- Rolling average computed without window functions (portable).
- Observations:
  - Typical daily signups range: ____ to ____.
  - Overall trend: ____ (up / down / flat).

## Troubleshooting & learnings
- Sudo password not working → used **no-sudo** path to finish Day 1.
- Keyboard layout confirmed **US**.
- Reminder: at sudo prompts, typing is invisible.

## Files saved today
- `day1_daily_revenue.csv`
- `day1_signups_avg7.csv`
- `day1_notes.md`

## Next steps (Day 2)
- Do SQL Q2, Q3, Q7, Q8; export KPIs for dashboard.
- Start `dashboard_requirements.md` (KPIs, filters, 3 business questions).

