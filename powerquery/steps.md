## Power Query steps

### Columns created
- ResolutionDays: days between ClosedDate and CreatedDate (null if no ClosedDate)
- SLA_Met: 1 if closed within SLA_Target_Days, 0 if not met, null if not closed

### Notes
- Dataset is synthetic (service requests).
