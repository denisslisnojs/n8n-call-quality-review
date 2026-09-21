# n8n call quality review

An n8n workflow that reviews sales calls automatically. Each recording is transcribed and scored against a checklist, the results are saved to a table, and every day at 18:00 the manager gets an email summary with an Excel report.

## How it works

1. Upload a call recording (Latvian, Russian or English).
2. The workflow transcribes it (OpenAI) and Claude scores it against 5 criteria: greeting, company introduction, offer, next steps, goodbye.
3. The result is saved to a data table, and an Excel report can be downloaded at any time.
4. Every evening the manager receives the day's summary by email.

## Contents

| File | What it is |
|---|---|
| `Call review — all-in-one.json` | The n8n workflow: call upload and review, Excel download, daily email |
| `HOW TO INSTALL.pdf` | How to import and set up the workflow in n8n (Latvian) |
| `3.uzdevums_INFO.pdf` | Process description, prototype, rollout and measurement plan (Latvian) |
| `zvanu_atskaite_2026-09-13.xlsx` | Sample Excel report |
| `Zvanu ieraksti testam/` | 4 test calls in Latvian, Russian and English |

All test calls and their content are fictional.
