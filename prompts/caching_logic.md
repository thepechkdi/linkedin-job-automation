# Hash & Caching Logic Notes

Used to prevent duplicate processing in n8n workflow.

Hash is computed from:
- jobId
- company_name
- position
- posted_date

If hash exists in Google Sheets:
- Skip all AI steps
Else:
- Process the job and update the sheet
