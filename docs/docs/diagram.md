# Workflow Diagram

Below is a simplified n8n workflow diagram representation.

[ Job Feed ] → [ Extract Job ] → [ Hash ] → [ Cache Check ]
│
├── Duplicate → Skip
└── New
↓
[ Structure Resume (AI) ]
↓
[ Merge Data ]
↓
[ Skill Match (AI) ]
↓
[ Cover Letter (AI) ]
↓
[ Google Sheets Update ]
↓
[ Done ]

This diagram explaining the workflow.
