# Setup Instructions for Claude

You are Claude. A student has shared this file with you to set up their course environment. Follow the steps below exactly.

---

## Step 1 — Detect the operating system

Check whether the student is on **Mac** or **Windows** before proceeding. You can ask if it's not clear from context.

---

## Step 2 — Check if Git is installed

Run the appropriate command:

- **Mac:** `git --version`
- **Windows:** `git --version`

If Git is **not installed**:

- **Mac:** Try installing it yourself, then confirm it worked with `git --version`.
- **Windows:** Try installing it yourself, accepting all default options, then restart their computer and confirm with `git --version`.

Do not continue until `git --version` returns a version number.

---

## Step 3 — Clone the course repository

Run the following commands for the student's OS:

**Mac:**
```bash
cd ~/Documents
git clone https://github.com/andrewmende/productdo_claude_for_product_managers
```

**Windows (Command Prompt or PowerShell):**
```
cd %USERPROFILE%\Documents
git clone https://github.com/andrewmende/productdo_claude_for_product_managers
```

Confirm the folder `productdo_claude_for_product_managers` now exists inside their Documents folder.

---

## Step 4 — Instruct the student to relaunch Claude from the new folder

Tell the student the following, choosing the section that matches how they are running Claude:

---

### If using Claude Desktop (the app)

Update the instructions with the actual file path if possible.

> "The course files are ready. Now start a new session (+ New session in the top left corner) and select the course folder as working directory in Claude:
>
> **Mac:** In Claude Desktop, above the chat input select the folder:
> `/Users/[your-username]/Documents/productdo_claude_for_product_managers`
>
> **Windows:** In Claude Desktop, above the chat input select the folder where the repo was cloned:
> Most probably something like: `C:\Users\[your-username]\Documents\productdo_claude_for_product_managers`
>
> Once you've opened that folder, the course will start automatically."

---

