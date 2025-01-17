# SQL code for HR Billing Analysis. 
Ensuring Consistency Between Client Billing and Timesheet Data. 
This SQL script calculates the expected client payments based on timesheet data and consultant charge rates, compares it to the actual client billings, and identifies discrepancies. 

Table Assumptions: 
1. billings: Contains actual client payments
 Columns: client_id, total_billed

 2. timesheets: Tracks consultant hours
 Columns: consultant_id, client_id, hours_logged

 3. charge_rates: Indicates consultant charge rates by position
 Columns: position_id, rate_per_hour
 
4. consultants: Links consultants to their positions
 Columns: consultant_id, position_id
