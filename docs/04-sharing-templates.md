# 4. Sharing Templates

Templates are documents your team reuses over and over — shift report sheets,
orientation checklists, equipment sign-out sheets, and on-call contact lists.
This chapter shows how to create templates, share them with colleagues, and
let people copy them without changing the original.

## Step 1: Create a template repository

1. Sign in to GitHub.
2. Click the **+** icon → **New repository**.
3. Name it something like `unit-templates`.
4. Choose **Private** if the templates contain internal workplace info.
5. Click **Create repository**.

## Step 2: Add a template file

Use the same steps as Chapter 3:

1. Click **Add file** → **Create new file**.
2. Name it, for example `shift-report-template.md`.
3. Write the template with blank sections for filling in:

   ```
   # Shift Report Template

   ## Shift details
   Date: ____________
   Shift: Day / Evening / Night
   Unit: ____________
   Reported by: ____________

   ## Patients
   - Room ____: ____________
   - Room ____: ____________

   ## Tasks to complete
   - [ ] ____________
   - [ ] ____________

   ## Handoff notes
   ____________
   ```

4. Commit the file.

## Step 3: Mark the repository as a template (optional)

GitHub has a "template repository" feature that lets others start a new repo
from yours:

1. Go to your repository → **Settings**.
2. Under **Template repository**, check the box **Template repository**.
3. Anyone with access can now click **Use this template** to make their own
   copy.

If your repository is Private, only people you invite can use it as a
template. That is usually what you want for workplace templates.

## Step 4: Share with teammates

1. Go to **Settings** → **Collaborators**.
2. Add coworkers with **Read** access.
3. Tell them where to find the templates: `github.com/your-username/unit-templates`

## Step 5: How teammates use a template

A teammate can:

1. Open the template file on GitHub.
2. Click the **Copy** button above the file contents.
3. Paste it into a document, an email, or their own GitHub repository.
4. Fill in the blanks for their own shift.

The original template on GitHub stays untouched, so everyone always starts
from the same clean version.

## Updating a template

When you improve a template:

1. Edit the original file in the template repository.
2. Commit the change with a note like "Added medication check section."
3. Teammates who already copied the template will not see the update
   automatically — they copy the new version next time they need it.

## Privacy checklist for templates

- Templates should contain blank fields, not real patient data.
- Do not include actual shift schedules with staff names unless the
  repository is Private and your workplace allows it.
- Do not include phone numbers or contact info for real patients.
- If a template references a real form number (e.g., "Incident Form #104"),
  that is usually fine — it is not patient information.

---
*Produced by Asdale Dynamics, LLC.*
