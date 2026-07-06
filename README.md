# AI Mystery Prompt Project

## Project Goal

This project is a personal library of clean, fair-play, fixed-case detective mystery prompts designed to be used with ChatGPT or other AI chat tools.

The goal is to create mystery cases that people can copy, paste, upload, or attach to an AI chat session and then play as an interactive detective RPG.

Each mystery is designed to be:

- Clean and suitable for a G-rated to PG audience
- Fair-play and solvable through deduction
- Internally consistent
- Fixed in advance, so the culprit and solution do not change during play
- Free of inappropriate, graphic, horror, occult, magical, spiritistic, or supernatural content
- Easy for social media users to access and try

The project is intended to support regular social media content, especially short-form posts and videos that invite users to solve a mystery by copying or downloading a prompt.

---

## Core Concept

There are two main types of mystery prompts:

1. **Customizable Mystery Generator Prompt**
   - Lets the user choose story details such as time period, setting, style, tone, suspect count, and difficulty.
   - The AI creates a new mystery after interviewing the user.

2. **Fixed-Case Mystery Prompt**
   - The case is already designed in advance.
   - The victim, suspects, culprit, motive, method, clues, red herrings, timeline, and final solution are locked.
   - The player may only choose limited gameplay settings such as difficulty level, hint level, and tone.
   - This format is best for social media because everyone can play the same case and compare theories.

This README focuses on the **fixed-case mystery workflow**.

---

## Fixed-Case Mystery Goals

Each fixed mystery should function like a reusable mini detective game.

A good fixed mystery should include:

- A clear title
- A spoiler-free teaser
- A defined time period and setting
- A victim
- A closed suspect list
- A locked culprit
- A locked motive
- A locked method
- A full true timeline
- A public or misleading timeline
- Fair clues
- Red herrings that can be resolved
- Suspect secrets
- Alibi contradictions
- Physical evidence
- Witness statements
- A clue logic map
- A satisfying final reveal

The AI must not change the case after gameplay begins.

---

## Clean Content and Guardrail Goals

All cases should stay clean, safe, and morally appropriate.

Mysteries should avoid:

- Graphic violence
- Explicit gore
- Sexual content
- Sexual motives
- Torture
- Cruelty to children or animals
- Horror themes
- Occult themes
- Demons
- Ghosts
- Magic
- Sorcery
- Curses
- Spiritistic topics, rituals, objects, or explanations
- Supernatural explanations
- Revenge fantasy framing
- Cynical or nihilistic endings
- Player actions that encourage harm, threats, abuse, theft, coercion, blackmail, or immoral behavior

Acceptable player actions include:

- Observing
- Questioning
- Inspecting
- Searching permitted areas
- Reviewing evidence
- Comparing statements
- Comparing timelines
- Taking notes
- Interviewing witnesses
- Making deductions
- Asking for hints
- Making a formal accusation

---

## Recommended Folder Structure

Suggested private working structure:

```text
mystery-prompts/
├── README.md
├── templates/
│   ├── fixed-case-prompt-template.md
│   ├── customizable-case-template.md
│   └── case-description-template.md
├── cases/
│   ├── case-001-title/
│   │   ├── case-001-title-master.md
│   │   ├── case-001-title-copy-paste.txt
│   │   └── case-001-title-social.md
│   ├── case-002-title/
│   │   ├── case-002-title-master.md
│   │   ├── case-002-title-copy-paste.txt
│   │   └── case-002-title-social.md
│   └── case-003-title/
│       ├── case-003-title-master.md
│       ├── case-003-title-copy-paste.txt
│       └── case-003-title-social.md
└── notes/
    ├── case-ideas.md
    ├── difficulty-rules.md
    ├── content-guardrails.md
    └── posting-workflow.md
```

---

## The Three File Outputs for Each Case

Each finished mystery case should have three main files.

---

### 1. Master Case File

Example filename:

```text
case-001-the-clockmakers-last-appointment-master.md
```

Purpose:

The master case file is the full private or working Markdown version of the case.

It includes:

- Case metadata
- Locked case facts
- Victim details
- Culprit details
- Motive
- Method
- True timeline
- Public or false timeline
- Suspect roster
- Locations
- Evidence
- Witness statements
- Red herrings
- Clue logic map
- Opening scene instructions
- Gameplay rules
- Hint rules
- Accusation rules
- Final reveal instructions

This file is mainly for editing, version control, and maintaining the true structure of the mystery.

It may contain spoilers and should not be posted publicly unless the full locked solution is meant to be included in the playable prompt.

---

### 2. Copy/Paste Public Prompt File

Example filename:

```text
case-001-the-clockmakers-last-appointment-copy-paste.txt
```

Purpose:

The copy/paste file is the public-facing version that users can download, copy, paste, upload, or attach to ChatGPT.

This should be the easiest version for normal users.

It should:

- Be saved as a plain `.txt` file
- Contain the playable prompt
- Be easy to copy into ChatGPT
- Avoid unnecessary Markdown complexity
- Clearly tell the user where the prompt begins and ends
- Include the fixed mystery prompt instructions
- Include the locked case details only if the AI needs them to run the mystery correctly
- Tell the AI not to reveal the locked case facts to the player

Recommended wrapper:

```text
AI MYSTERY CASE #001: THE CLOCKMAKER'S LAST APPOINTMENT

Copy everything between START PROMPT and END PROMPT into ChatGPT.

[START PROMPT]

...full playable fixed mystery prompt...

[END PROMPT]
```

This is the file that should be placed in Google Drive for public access.

---

### 3. Social Media Description File

Example filename:

```text
case-001-the-clockmakers-last-appointment-social.md
```

Purpose:

The social file contains public-facing promotional material for TikTok and other platforms.

It should include:

- Case title
- Short hook
- One-line teaser
- Spoiler-free synopsis
- TikTok caption options
- On-screen text ideas
- Voiceover script options
- Short and long post descriptions
- Pinned comment ideas
- Call-to-action ideas
- Hashtag sets
- Reveal post template
- Notes on what can and cannot be revealed publicly

This file should not include the culprit, true motive, method, final clue, or solution unless it is specifically a reveal post section.

---

## Public Storage Plan

Final public prompt files are stored in Google Drive as `.txt` files.

The Google Drive version should be:

- Plain text
- Easy to download
- Easy to open on mobile
- Easy to copy and paste
- Publicly accessible through a share link
- Safe to share from social media posts

The public link should point users to the `.txt` copy/paste file, not the private master file.

Recommended public file naming:

```text
AI-Mystery-Case-001-The-Clockmakers-Last-Appointment.txt
AI-Mystery-Case-002-The-Lighthouse-at-Grayhaven-Point.txt
AI-Mystery-Case-003-The-Vanishing-Violinist.txt
```

Suggested Google Drive folder:

```text
AI Mystery Prompts/
├── Case 001 - The Clockmaker's Last Appointment.txt
├── Case 002 - The Lighthouse at Grayhaven Point.txt
├── Case 003 - The Vanishing Violinist.txt
└── Read Me - How To Play.txt
```

---

## How Users Should Use the Public Prompt

User instructions should be simple.

Recommended public instructions:

```text
How to play:

1. Download or open the prompt file.
2. Copy the full prompt.
3. Paste it into ChatGPT.
4. Choose your difficulty.
5. Choose your hint level.
6. Investigate the case.
7. Question suspects, inspect locations, compare clues, and reconstruct the timeline.
8. Make your accusation when ready.
9. Ask for the reveal only after you are done investigating.
```

For social media, the call-to-action can be even shorter:

```text
Copy the prompt from the link in bio.
Paste it into ChatGPT.
Choose your difficulty.
Play detective.
Comment who you accused before asking for the reveal.
```

---

## How to Generate a New Fixed Case Using ChatGPT

Use this workflow when creating a new mystery case.

---

### Step 1: Start With the Fixed-Case Template

Open:

```text
templates/fixed-case-prompt-template.md
```

Copy the template into ChatGPT and ask ChatGPT to help create a new fixed mystery case.

Suggested instruction:

```text
Using this fixed-case mystery template, help me create a new clean, fair-play detective mystery case. Keep it G-rated to PG. No horror, gore, sexual content, magic, occult, supernatural, spiritistic, or morally objectionable themes. The mystery should be fixed, solvable, consistent, and suitable for social media users to copy/paste into ChatGPT.
```

---

### Step 2: Define the Case Design

Choose or ask ChatGPT to suggest:

- Case number
- Title
- Time period
- Setting
- Mystery type
- Tone
- Suspect count
- Difficulty target
- Estimated play length
- Core hook
- Main location
- Investigation style
- Red herring strength
- Clue density

Example:

```text
Create Case #001. Make it a cozy village mystery set in a clockmaker's workshop in the late 1800s. It should have five suspects, a medium difficulty level, and a fair-play clue chain based on timeline contradictions and physical evidence.
```

---

### Step 3: Have ChatGPT Draft the Locked Case

Ask ChatGPT to generate the full case file using the template.

Important instruction:

```text
Before writing the playable opening, fully design the locked case facts: culprit, motive, method, true timeline, false timeline, suspects, clue logic, red herrings, evidence, and final solution. Make sure the case has at least three independent clue paths and does not rely on one fragile clue.
```

---

### Step 4: Review for Solvability

After ChatGPT drafts the case, review it carefully.

Check:

- Is the culprit fixed and clear?
- Is the motive clean and appropriate?
- Is the method non-graphic and PG?
- Is the timeline internally consistent?
- Can the player discover the truth fairly?
- Are there at least three independent clues pointing to the solution?
- Can innocent suspects be reasonably cleared?
- Are red herrings explainable?
- Are there alternate ways to discover essential clues?
- Does the case avoid horror, occult, supernatural, sexual, graphic, or morally objectionable content?

Suggested review prompt:

```text
Review this mystery case for consistency, fairness, solvability, clean content, and moral guardrails. Identify any plot holes, weak clues, unfair leaps, inappropriate elements, or places where the AI might accidentally reveal the solution too early. Then suggest fixes.
```

---

### Step 5: Create the Three Output Files

Once the case is approved, create:

1. `case-###-title-master.md`
2. `case-###-title-copy-paste.txt`
3. `case-###-title-social.md`

The master file is for editing and version control.

The copy/paste file is for public Google Drive sharing.

The social file is for TikTok captions, teasers, hashtags, and reveal post planning.

---

### Step 6: Store the Files

Private storage:

- Store the Markdown master file and social file in GitHub.
- Use GitHub to track changes, improvements, versions, and revisions.

Public storage:

- Store the final `.txt` copy/paste prompt in Google Drive.
- Make the Google Drive file publicly accessible through a share link.
- Use that Google Drive link in social media bios, posts, pinned comments, or link pages.

---

## TikTok Posting Workflow

Recommended TikTok workflow:

1. Create a short video teasing the case.
2. Show the case title on screen.
3. Mention that the prompt is fixed and fair-play.
4. Tell users to copy the prompt from the link in bio or pinned comment.
5. Ask them to comment who they accused.
6. Later, post a spoiler warning and reveal video.
7. Use the social file to create captions, hashtags, and pinned comments.

Example TikTok caption:

```text
AI Mystery Case #001: The Clockmaker's Last Appointment

The victim, suspects, clues, and solution are already locked.

Copy the prompt, paste it into ChatGPT, choose your difficulty, and play detective.

Can you solve it before asking for the reveal?

#mysterygame #chatgptprompt #detectivegame #canyousolveit #whodunit #aigame #logicpuzzle
```

---

## Versioning Guidelines

Use simple version numbers:

```text
0.1 = first draft
0.2 = revised draft
0.3 = tested draft
1.0 = public release
1.1 = small fixes after release
2.0 = major rewrite
```

Each case file should include a metadata block near the top.

Example:

```yaml
case_number: "001"
title: "The Clockmaker's Last Appointment"
status: "draft"
version: "0.1"
content_rating: "G-PG"
case_type: "cozy whodunit"
time_period: "late 1800s"
setting: "village clockmaker's workshop"
recommended_difficulty: "medium"
public_file_location: "Google Drive"
```

---

## Case Quality Checklist

Before publishing a case, confirm:

- [ ] The mystery has a fixed culprit.
- [ ] The motive is clean and appropriate.
- [ ] The method is non-graphic and PG.
- [ ] The timeline is consistent.
- [ ] The player can solve the case through fair clues.
- [ ] There are at least three independent clues pointing toward the solution.
- [ ] The culprit's alibi can be challenged fairly.
- [ ] Innocent suspects can be cleared.
- [ ] Red herrings are explainable.
- [ ] Essential clues have alternate discovery paths.
- [ ] The case does not include horror, occult, supernatural, spiritistic, sexual, graphic, or cruel content.
- [ ] Player actions are limited to appropriate detective behavior.
- [ ] The opening scene does not reveal spoilers.
- [ ] The character card does not reveal hidden motives or relationships.
- [ ] The floor plan does not reveal hidden evidence or the solution.
- [ ] The final reveal explains the clue chain clearly.
- [ ] The `.txt` copy/paste file is easy for users to understand.
- [ ] The Google Drive sharing permissions are correct.
- [ ] The TikTok/social description is spoiler-free.

---

## Suggested Hashtag Base

```text
#mysterygame #chatgptprompt #detectivegame #canyousolveit #whodunit #aigame #logicpuzzle #storytok #cozymystery #promptengineering
```

---

## Project Notes

This project is meant to become a repeatable content system.

Each case should be easy to:

- Create
- Test
- Store
- Share
- Copy
- Play
- Reveal
- Reuse

The fixed-case format helps make the mysteries consistent for social media. Everyone plays the same case, but each player can choose a different difficulty or hint level.

The long-term goal is to build a library of clean, fair-play AI mystery cases that people can enjoy, share, and discuss.
