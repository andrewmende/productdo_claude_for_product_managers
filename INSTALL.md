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

- **Mac:** Tell the student to run `xcode-select --install` in their Terminal and wait for it to finish, then confirm it worked with `git --version`.
- **Windows:** Tell the student to download and install Git from [https://git-scm.com/download/win](https://git-scm.com/download/win), accepting all default options, then restart their computer and confirm with `git --version`.

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

> "The course files are ready. Now relaunch Claude from the course folder:
>
> **Mac:** In Claude Desktop, go to **File → Open Folder…** and select:
> `/Users/[your-username]/Documents/productdo_claude_for_product_managers`
>
> **Windows:** In Claude Desktop, go to **File → Open Folder…** and select:
> `C:\Users\[your-username]\Documents\productdo_claude_for_product_managers`
>
> Once you've opened that folder, the course will start automatically."

---

### If using Claude CLI (terminal)

Mention that the student needs to type `/exit` to close this session, then run the commands below to navigate to the course folder and launch Claude from there:

**Mac:**
```bash
cd ~/Documents/productdo_claude_for_product_managers
claude
```

**Windows (Command Prompt):**
```
cd %USERPROFILE%\Documents\productdo_claude_for_product_managers
claude
```

**Windows (PowerShell):**
```
cd $env:USERPROFILE\Documents\productdo_claude_for_product_managers
claude
```

---

That's it. Your job here is done once the student knows to relaunch Claude from the new folder.
