# FAL — Hulling

Single-file HTML dashboard for **FAL — Rice Hulling** (Hulling Side Line-1 & Line-2).

## Features
- Toggle: Last completed day + Month-to-date (live from Google Sheets)
- OEE KPIs (A/P/Q/Overall) vs targets A90/P86/Q97/OEE75, with overall **Out x/y MT**
- Where time is going; OEE by unit; Find-the-bottleneck
- Top downtime + downtime by category (min) — includes FAL's operational curtailments (capacity / less-electricity / unavailable order)
- Opportunity Loss = NPT min ÷ cycle time; Production & OEE trend; Shift Action Board; Shift OEE; Gemba walk

## Data source
`Hulling Production Report` (gid=0) + `Breakdown` (gid=482789258) of the FAL OEE sheet.
