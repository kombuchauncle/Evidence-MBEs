# MBE Evidence Question Bank

A study tool for MBE Evidence questions with automatic sync from Google Sheets.

## About

This repository contains:
- `mbe_questions.csv` - Question bank (auto-synced from Google Sheets)
- `mbe-study-tool.html` - Web-based study interface
- Auto-sync workflow (updates CSV from Google Sheets daily)

## Live Study Tool

Access the study tool at: (https://kombuchauncle.github.io/Evidence-MBEs/study-tool.html)

## How It Works

1. Edit questions in Google Sheets
2. GitHub Action automatically syncs changes (runs every 6 hours)
3. Web app always shows latest questions
4. Full version history in GitHub commits

## Question Format

| Column | Description |
|--------|-------------|
| ID | Question number (Q001, Q002, etc.) |
| Question | The question text |
| Scenario | Background facts (optional) |
| Choice_A - D | Answer choices |
| Correct_Answer | A, B, C, or D |
| Explanation | Why the answer is correct |
| Source | In-Class MBE, UWorld, NCBE, etc. |
| Topic | Hearsay, Character Evidence, etc. |

## Adding Questions

1. Open the Google Sheet
2. Add a new row with question details
3. Wait for auto-sync (or trigger manually)
4. Refresh the web app to see new questions

## Manual Sync

To manually trigger a sync:
1. Go to Actions tab
2. Click "Sync from Google Sheets"
3. Click "Run workflow"

---

*Study tool for Santa Clara University School of Law, Class of 2026*
