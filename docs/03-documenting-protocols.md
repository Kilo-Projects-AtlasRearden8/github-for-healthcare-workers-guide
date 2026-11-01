# 3. Documenting Protocols

A protocol is a step-by-step guide for a clinical task — for example, how to
admit a patient, how to respond to a fall, or how to handle a medication
error. This chapter shows how to create a protocol repository, write a
protocol in plain text, save changes, and review the history.

GitHub stores documents as plain text files using a simple format called
Markdown. It looks like normal writing with a few shortcuts for headings and
lists. You do not need to learn programming.

## Step 1: Create a repository for your protocols

1. Sign in to GitHub.
2. Click the **+** icon (top right) → **New repository**.
3. Name it something clear, like `unit-protocols`.
4. Choose **Public** or **Private**. Private means only people you invite can
   see it. For workplace documents, Private is usually the safer choice.
5. Do **not** check any boxes about adding patient or workplace data.
6. Click **Create repository**.

Your repository is now an empty folder on GitHub.

## Step 2: Add your first protocol file

1. On your repository page, click **Add file** → **Create new file**.
2. Name the file with `.md` at the end, for example `fall-response.md`.
   The `.md` tells GitHub it is a Markdown document.
3. Write the protocol in plain English. Example:

   ```
   # Fall Response Protocol

   ## Purpose
   What to do when a patient falls.

   ## When to use
   Any time a patient is found on the floor or reports a fall.

   ## Steps
   1. Stay with the patient. Do not move them unless they are in danger.
   2. Call for help according to your unit's procedure.
   3. Check for injuries: head, hips, wrists, and any pain.
   4. Report the fall to the charge nurse.
   5. Document the fall in the incident reporting system.

   ## Notes
   Never include patient names or room numbers in this file.
   ```

4. Under **Commit changes**, type a short note like "Add fall response
   protocol."
5. Click **Commit changes** twice to confirm.

Your protocol is now saved, with a date, time, and your username attached.

## Step 3: Edit a protocol later

1. Go to the file in your repository.
2. Click the pencil icon (Edit file).
3. Make your changes.
4. Under **Commit changes**, write what changed — for example,
   "Updated step 3 to include wrist check."
5. Click **Commit changes**.

GitHub saves the old version too. You can always go back.

## Step 4: Look at older versions

1. On your repository page, click the **commits** link (it shows a number like
   "3 commits").
2. Click any commit to see what changed in that version.
3. To restore an older version, open that commit, click **Browse files**, open
   the file, and save it again as a new commit.

## Step 5: Invite a teammate (optional)

If you want a coworker to help maintain protocols:

1. Go to your repository → **Settings** → **Collaborators**.
2. Click **Add people** and type their GitHub username.
3. Choose **Read** (can view only) or **Write** (can edit).
4. Your coworker accepts the invitation by email.

Only invite people you trust, and remind them never to add patient
information.

## Privacy checklist for protocols

- No patient names, initials, or nicknames.
- No medical record numbers, dates of birth, or dates of service.
- No room numbers or unit-specific details that could identify a patient.
- No photos of patients or their wristbands.
- If an example is needed, make up a clearly fake patient (e.g., "Patient J.,
  a fictional 65-year-old") and label it as an example.

Protocols describe *how work is done*, not *who a patient is*. Keep it that
way.

---
*Produced by Asdale Dynamics, LLC.*
