# Data Dictionary

This document describes the fields used in the **Machine Breakdown Analysis Dashboard**.

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| Date | Date | Date on which the machine breakdown occurred. |
| Shift | Text | Production shift during which the breakdown occurred (I, II, III). |
| Equipment Name | Text | Unique machine or equipment identifier. |
| Problem Details | Text | Description of the machine issue or failure. |
| Action Taken | Text | Corrective action performed by the maintenance team. |
| Breakdown Time (Hrs.) | Decimal | Total downtime of the machine in hours. |
| Remark | Text | Additional maintenance remarks or observations (if any). |
| Available Time | Decimal | Total available operating time for the machine (hours). |
| % of Breakdown | Percentage | Percentage of breakdown time relative to available operating time. |
| Availability | Percentage | Machine availability after considering downtime. |
