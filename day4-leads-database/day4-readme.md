# Day 4 — Leads Database (portfolio-automation/day4-leads-database)

## Files included
- `leads_table.csv` — 20 dummy lead rows (id, name, email, company, product_interest, lead_source, created_at, notes).
- `screenshot.png` — (you should add a screenshot of the table here after you import it and capture it).
- `README.md` — this file (schema + import + git steps).

## Schema / Columns
- `id` — integer (1..20). If you import into Airtable and want an Auto Number, create a new Autonumber field and drop this column.
- `name` — full name (diverse sample).
- `email` — realistic-looking but synthetic email address.
- `company` — fake company name.
- `product_interest` — example: CRM, AI Assistant, Email Marketing.
- `lead_source` — example: LinkedIn, Cold Email, Referral, Website.
- `created_at` — ISO date (YYYY-MM-DD) in September 2025.
- `notes` — short context for the lead.

## How to import into Airtable (quick)
1. Open Airtable → use the left sidebar **Add a base** → **Import a spreadsheet** → Upload `leads_table.csv`.
2. During import, Airtable will map columns. Set column types if you want:
   - `id` → Number (or delete and create Autonumber field).
   - `email` → Email field type (optional).
   - `created_at` → Date field type (choose ISO format).
   - `notes` → Long text.
3. Finish import. Optional: create a primary field (Name) if not auto-selected.

## How to import into Google Sheets
1. Open Google Sheets → **File → Import → Upload** → select `leads_table.csv`.
2. Choose "Replace current sheet" (or "Insert new sheet") and import. Done.

## How to take a screenshot (Windows)
- Open the sheet in your browser or Airtable.
- Press **Win + Shift + S** (Snip & Sketch) → drag to capture the table → save as `screenshot.png`.
- Place `screenshot.png` into the `day4-leads-database` folder before committing.

## Git: add files to your portfolio-automation repo and push
Assuming your repo is at `C:/Users/bakrs/portfolio-automation` and you've downloaded `leads_table.csv` and `day4-readme.md` to your computer:

```bash
cd C:/Users/bakrs/portfolio-automation
mkdir -p day4-leads-database
# move/copy the downloaded files into the new folder, e.g. via File Explorer or PowerShell:
# Copy-Item -Path "C:\Users\bakrs\Downloads\leads_table.csv" -Destination ".\day4-leads-database\"
# Copy-Item -Path "C:\Users\bakrs\Downloads\day4-readme.md" -Destination ".\day4-leads-database\"

git add day4-leads-database/*
git commit -m "Add day4 leads database: 20 dummy leads + README"
git push origin main
```

## Deliverable checklist
- [ ] `leads_table.csv` (provided)
- [ ] `screenshot.png` (you create after import)
- [ ] `README.md` inside `day4-leads-database` (this file)
- [ ] Repo updated on GitHub under `portfolio-automation/day4-leads-database`

---
If you want, I can also:
- Generate a ready-to-import Airtable CSV that uses an empty `id` column (so Airtable Autonumber is used) — say the word and I'll produce that too.
- Or, I can create a simple PowerShell copy command tailored to your Downloads folder so you can move the files into your local repo automatically.
