---
layout: default
title: Forum Setup Guide
---

# How to Join the Discussion Forum

This guide will help you get set up to participate in discussions about the FACS Scientist Job Family Matrix.

---

## What You'll Need

- A **GitHub account** (free)
- About **5 minutes** for one-time setup

---

## Step 1: Create a GitHub Account (if you don't have one)

1. Go to [github.com/signup](https://github.com/signup)
2. Enter your email, create a password, and choose a username
3. Verify your email address

> **Tip:** Your GitHub username will be visible when you post, so choose something recognizable to the team (e.g., `jsmith-gne` or `john-smith`).

---

## Step 2: Create a Personal Access Token

This token lets the forum post on your behalf. You only need to do this once.

### 2a. Go to Token Settings

1. Sign in to GitHub
2. Click your profile picture (top right) → **Settings**
3. Scroll down the left sidebar → click **Developer settings** (at the very bottom)
4. Click **Personal access tokens** → **Tokens (classic)**
5. Click **Generate new token** → **Generate new token (classic)**

### 2b. Configure the Token

1. **Note:** Enter something like `FACS Forum Access`
2. **Expiration:** Choose "No expiration" (or set a reminder to renew)
3. **Scopes:** Check only `public_repo` (under "repo" section)

   ![Token scope](https://docs.github.com/assets/cb-43299/mw-1440/images/help/settings/token-scopes.webp)

4. Scroll down and click **Generate token**

### 2c. Copy Your Token

1. **IMPORTANT:** Copy the token now — you won't see it again!
2. It looks like: `ghp_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx`
3. Save it somewhere safe (password manager, secure note, etc.)

---

## Step 3: Sign In to the Forum

1. Go to the **[Discussion Forum](forum)**
2. Click **Sign in with GitHub**
3. Paste your Personal Access Token when prompted
4. Click OK

You're now signed in! Your token is saved in your browser, so you won't need to enter it again on this device.

---

## Using the Forum

### Starting a Discussion

1. Click **New Discussion**
2. Choose a category:
   - **Question** — Ask about the framework
   - **Suggestion** — Propose an improvement
   - **Feedback** — Comment on a specific document
   - **General** — Everything else
3. Write your title and message
4. Click **Post Discussion**

### Mentioning Teammates

Type `@` followed by their GitHub username to notify them:

```
@jsmith What do you think about this approach?
```

The forum will autocomplete usernames as you type.

### Referencing Documents

Type `[[` to link to a document:

```
I have a question about [[promotion-philosophy]]
```

Available documents:
- `[[handover-doc]]` — Handover Document
- `[[facs-scientist-promotion-criteria-summary]]` — Promotion Criteria
- `[[promotion-philosophy]]` — Promotion Philosophy
- `[[project-strategies]]` — Project Strategies
- `[[promotion-project-examples]]` — Project Examples
- `[[matrix-planning-doc]]` — Matrix Planning
- `[[orig-matrix-guidelines]]` — Original Guidelines
- `[[project-challenges]]` — Project Challenges

### Quoting Text

Use `>` at the start of a line to create a quote:

```
> This is a quoted passage from a document

My response to this...
```

### Replying to Discussions

1. Click on any discussion to open it
2. Scroll to the bottom
3. Write your reply
4. Click **Reply**

---

## Troubleshooting

### "Error creating discussion"

- Make sure your token has the `public_repo` scope
- Try generating a new token

### "Error loading discussions"

- Refresh the page
- Check your internet connection

### Forgot your token?

- You can't recover it, but you can create a new one
- Go back to Step 2 and generate a fresh token

### Want to sign out?

- Click **Sign out** in the forum
- Your token is removed from your browser

---

## Questions?

If you run into issues, reach out to the team or [open an issue on GitHub](https://github.com/pawj-gne/facs-scientist-job-family-matrix/issues/new).
