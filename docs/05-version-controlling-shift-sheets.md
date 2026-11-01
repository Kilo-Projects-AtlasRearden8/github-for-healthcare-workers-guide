# 5. Version-Controlling Shift Sheets

Shift sheets show who is working when. They change constantly — someone calls
out, a shift gets swapped, a new hire starts. This chapter shows how to use
GitHub to keep every version of a shift sheet, see what changed, and go back
if a mistake is made.

You can keep shift sheets as plain text (Markdown) files or as spreadsheet
files (Excel/CSV). This chapter shows both.

## Option A: Shift sheets as plain text files

Plain text files are easiest to read on GitHub and show changes clearly.

### Step 1: Create the shift sheet

1. In your repository (or a new one called `shift-sheets`), click
   **Add file** → **Create new file**.
2. Name it `2026-11-shift-sheet.md`.
3. Write the schedule:

   ```
   # November 2026 Shift Sheet — West Wing

   ## Week of November 2

   | Date | Day shift | Night shift |
   |------|-----------|-------------|
   | Nov 2 | A. Rivera | O. Patel |
   | Nov 3 | S. Chen | J. Okoye |
   | Nov 4 | L. Dubois | M. Torres |

   ## Notes
   - A. Rivera is on vacation Nov 7–9.
   - Float pool covers Nov 5 night shift.
   ```

4. Commit the file.

### Step 2: Update the sheet each week

1. Open the file → click the pencil icon.
2. Make your changes.
3. Commit with a note like "Updated night shift for Nov 5 — float pool."
4. Repeat each week.

Because every commit is saved, you can always see last month's schedule if
you need to check who worked a particular shift.

## Option B: Shift sheets as spreadsheet files

If your team prefers Excel or CSV, you can commit those files too. GitHub will
store them, but it cannot show you exactly which cell changed — it will only
tell you the file changed.

### Step 1: Save your spreadsheet

Save your shift sheet as a CSV file (File → Save As → CSV) so it is a plain
text spreadsheet. Name it `shift-sheet-2026-11.csv`.

### Step 2: Upload it

1. In your repository, click **Add file** → **Upload files**.
2. Drag in your CSV file.
3. Commit the file.

### Step 3: Replace it next time

When the schedule changes, upload the new CSV with the same filename. GitHub
keeps both versions. To see an older version:

1. Click **commits** on the repository page.
2. Click the commit you want.
3. Click the CSV file to download that older version.

## Step 3: Compare versions

1. Go to your repository → **commits**.
2. Click any commit to see what changed.
3. For text files, GitHub highlights added lines in green and removed lines
   in red. This makes it easy to see who was added or removed from a shift.

## Step 4: Fixing a mistake

If someone accidentally deletes a name or changes the wrong date:

1. Open the commit before the mistake.
2. Click **Browse files** → open the shift sheet.
3. Copy the contents.
4. Open the current file → click Edit → paste the old contents back in.
5. Commit with a note like "Restored shift sheet from before Nov 4 error."

## Privacy checklist for shift sheets

Shift sheets contain staff information, which is workplace data — handle it
carefully:

- Keep the shift sheet repository **Private**.
- Invite only teammates who need to see schedules.
- Do not include staff phone numbers, home addresses, or personal contact
  details.
- Do not include reasons for time off (e.g., "maternity leave" or "sick
  leave"). Use blank cells or "off" instead.
- Never include patient names or assignments that link a specific staff
  member to a specific patient. A shift sheet shows *who is working*, not
  *which patients they are caring for*.

If you are unsure whether something belongs in GitHub, ask your manager or
your workplace's privacy officer first.

---
*Produced by Asdale Dynamics, LLC.*
