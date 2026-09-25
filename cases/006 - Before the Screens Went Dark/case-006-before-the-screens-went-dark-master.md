# Hidden Trail Mysteries — Case 006: Before the Screens Went Dark

> Creator's master case file. Contains the locked answer and spoilers. Version 0.1, September 2026.

## Case identity

- Brand: Hidden Trail Games · “Every story leaves a trail.”
- Format: guided, fictional hospital cyber incident reconstruction; fixed truth, flexible investigation order.
- Rating and audience: PG; beginners, including onsite and remote hospital staff. No technical experience required.
- Length: 10–20 minutes, roughly 8–12 player choices. Default difficulty: Easy. Other difficulty settings change hints and wording, never facts.
- Goal: understand social engineering, vishing (phone phishing), phishing, reused passwords, unexpected sign-in approvals, and reporting without blame.
- Player role: a scheduling-department employee familiar with the team's workflow, helping the authorized cybersecurity investigator reconstruct events. The player does not troubleshoot systems or access patient records.
- Public hook: An overnight Epic update really did slow several scheduling workstations. By late morning, shared files are inaccessible and one computer shows a ransomware notice. Did the update cause both problems, or did someone use the first problem to create the second?

## Case-specific rules and master-template adaptation

This is an incident simulator, not a murder case. Replace “victim” with “affected staff and department,” “culprit” with “external attacker,” “crime scene” with “authorized incident evidence,” and “formal accusation” with “incident handoff.” Preserve the master generator's fixed facts, fair-play clues, alternate discovery routes, concise scene cards, gradual hints, journal, spoiler separation, and end-of-case reveal. Do not add a surprise insider, patient harm, confirmed data theft, or a hospital-wide ransomware outbreak.

The experience is a guided walkthrough with small decisions, not a technical examination. Show what the coworker saw before explaining why it was deceptive. Let mistaken answers trigger a relevant check and a gentle explanation; never shame a character or player. The player's choices affect the order of discovery, which interview or record appears next, and how much support the investigator gives. They do not change the incident, its outcome, or who did what. After any route, converge on the same event board and handoff.

All names, systems, messages, logs, and screenshots are invented for the case. “Epic” is contextual background; do not imply a real Epic vulnerability, actual update, or vendor failure. Do not reproduce working malware, live links, credentials, exploit steps, or actionable deployment details. Treat records as pre-cleared, simplified findings supplied by the cyber team. The cyber team has already isolated the affected workstation, restricted the account, and initiated its established response process; the player investigates and reports.

## Locked answer — never reveal before earned discovery

1. An overnight Epic application update exposed a genuine configuration mismatch on a subset of scheduling workstations. These computers became sluggish and intermittently froze. IT was investigating; it did **not** ask any physician to distribute a fix. The update did not install ransomware.
2. Dr. Joshua “Josh” Vale, an onsite physician, reused his hospital password on a personal service. That service had previously been breached; the reused password appeared in exposed credential data. The attacker obtained it and attempted a sign-in to Josh's hospital account.
3. The hospital account required an additional sign-in approval. Earlier that morning, Josh received an unexpected approval prompt. He mistakenly accepted it, thinking it belonged to his own recent sign-in on a work device. The authorized cyber investigator confirms the successful unfamiliar session followed that approval. No one should infer that a reused password alone bypassed the additional check.
4. With Josh's actual work mailbox open, the external attacker saw an internal scheduling message about the real slowdown. The attacker phoned scheduler Morgan Ellis and introduced himself as “Josh Vale.” He said that some workstations were not configured correctly after the overnight Epic update and **claimed** IT had asked him to contact schedulers and send a fix. He did not identify himself as an IT employee. Morgan assumed he was part of the support effort.
5. The attacker sent the promised message from Josh's genuine hospital mailbox. Morgan saw the matching name and real hospital domain. She did not check the staff directory or contact IT through its normal channel. The real Josh did not call or send the message.
6. Morgan opened the attached “fix” on a scheduling workstation. It was malicious and launched ransomware on that workstation. Shared files reachable from that workstation became unavailable to the department. The evidence does **not** show every workstation was infected. There is no confirmed patient-data theft in this case; the cyber team is assessing scope separately.
7. The attacker is an unidentified outsider. Discovering a specific real-world identity is outside this short simulation. Morgan was deceived; Josh's password reuse and approval were contributing mistakes, not evidence either employee intended harm.

### Fixed timeline (local hospital time; reveal entries only as discovered)

| Time | Event | Evidence |
| --- | --- | --- |
| Prior weeks | Personal service breach exposed a password Josh also used at work. | Cyber team's credential-exposure finding, disclosed late. |
| 6:10 a.m. | Overnight application update completed; a workstation configuration mismatch left some scheduler stations slow or freezing. | IT incident note and staff reports. |
| 7:42 a.m. | Josh approved an unexpected work sign-in prompt while moving between tasks. | Josh's account and cyber team's approval record. |
| 7:43 a.m. | An unfamiliar session entered Josh's hospital account. | Simplified, cyber-approved sign-in summary. |
| 8:05 a.m. | Internal message about the scheduling slowdown was available in Josh's mailbox. | Message history, without patient information. |
| 8:23 a.m. | Attacker called Morgan as “Josh Vale,” claiming IT had asked him to share a fix. | Morgan's recollection and call note. |
| 8:29 a.m. | Message containing the fake fix left Josh's actual hospital mailbox. | Mail summary and redacted message. |
| 8:36 a.m. | Morgan opened the attachment on workstation S-14. | Morgan's account and cyber team's device timeline. |
| 8:41 a.m. | Files on the department share became inaccessible; S-14 showed a ransom notice. | Department report and cyber team's device summary. |

The times establish sequence, not a claim that opening any file normally spreads ransomware. Avoid technical speculation beyond the team's confirmed device and file-access findings.

## Characters and locations

| Character | Public role | What they know at opening | Private truth and interview progression |
| --- | --- | --- | --- |
| Player | Scheduling team member | Workstations have slowed; now files are unavailable. | May explore authorized evidence in any order. |
| Morgan Ellis | Onsite scheduler | Opened a file she believed would fix the slowdown. | She received Josh's call and matching email, felt pressured by appointments, and is anxious about blame. Answers honestly when approached without accusation. |
| Dr. Joshua “Josh” Vale | Onsite physician | His name and account appear on the message. | He did not contact Morgan or IT; reused a password and accepted an unexpected approval prompt. Initially remembers the prompt vaguely; a timestamp helps. |
| Priya Shah | Cybersecurity investigator | Has isolated S-14 and approved limited findings for the player. | Gives direct, plain-language results when asked. Does not hand-wave an MFA bypass or announce the solution before player checks the links. |
| Sam Rivera | IT service desk employee | IT is investigating the slowdown. | Confirms the workstation issue was genuine but no ticket assigned Josh to send a fix; the purported instructions were unauthorized. |

Places are the scheduling desk (Morgan, her call note, redacted message), the IT/cyber handoff station (authorized ticket, device and sign-in summaries), and the staff directory/physician interview (Josh's role and account of the morning). Remote colleagues may report the same slow application or inaccessible shared files. Their locations do not imply their computers ran ransomware.

## Essential evidence and fair-play logic

| Clue | Natural discovery; alternate route | What it establishes |
| --- | --- | --- |
| A real slowdown predates the call. | Ask scheduler or Sam; review IT ticket. | The attacker exploited an existing issue; the update and ransomware need separate explanations. |
| Caller said “IT asked me”; never “I am IT.” | Morgan's call note or her interview; replay after directory check. | Morgan inferred authority from context, not a verified IT identity. |
| Josh is a physician. | Staff directory or Josh/Sam interview. | The supposed IT assignment is worth verifying, not proof Josh is malicious. |
| Email came from Josh's genuine account. | Redacted email or mail summary. | A real domain and matching name can still be used by an intruder. |
| Josh denies calling or sending; IT has no such assignment. | Josh and Sam; cyber team's message summary. | Compromised account becomes more likely than authorized support or Josh's own fix. |
| Unexpected approval preceded unfamiliar session; password was reused and exposed. | Josh's recollection and cyber summary, in either order. | Explains account access without treating a password as a way around approval. |
| Attachment opened before ransom notice, after slowdown. | Morgan interview and device summary; event-card board. | Separates the malicious file's effect from the prior application slowdown. |
| Only S-14 ran the malicious file; the share became inaccessible. | Cyber handoff or IT summary. | Explains why several staff saw disruption without inventing infection of every computer. |

Three independent proof strands: (a) Morgan's call/email account plus directory/IT contradiction; (b) Josh's account plus approved sign-in findings; (c) device timeline plus the earlier independent slowdown ticket. If one character cannot be questioned, records can provide their crucial facts; if a record is skipped, an interview prompts the player to request its summary. No decisive fact appears for the first time only in the final reveal.

## Opening and player-facing start

Before beginning, welcome the player to Hidden Trail Mysteries, show the title, spoiler-free synopsis, how to play in one short paragraph, and offer Easy / Medium / Hard / Expert. Recommend Easy and allow “Let's begin.” Never reveal locked facts in this screen. On start, show the five-character and three-location reference tables using only public descriptions.

Suggested opening scene:

> The scheduling screens have been sluggish since the overnight update. Morgan has restarted hers twice; a colleague working from home reports the same freezing. Then someone calls from the next desk: “I can't open the shared files.” One workstation displays a ransom notice. Staff switch to the hospital's established downtime process as the cybersecurity team isolates that workstation.
>
> Priya from cybersecurity asks you to help with the part you know best: what happened at the scheduling desk this morning. “We have the technical checks underway. Can you help us get the order of events right?”

Offer three first actions: talk to Morgan, see the IT slowdown note, or review a short event board. State the aim: work out what led to the ransomware and what the team should know. Do not imply the player must restore a system or find an outsider's name.

## Interactive route and teaching beats

### Beat 1 — Separate the two symptoms (2–3 minutes)

Present the real slowdown and later ransomware disruption. Ask: “Which fact would help you decide whether these started together?” Options: when the slowdown began; which computer displayed the notice; who first complained. Resolve every option directly with a short finding, then make the other two inspectable. Teach the distinction between timing and cause only after the player compares them.

### Beat 2 — Hear the call as Morgan heard it (2–3 minutes)

Give Morgan's perspective before labeling the trick: she has appointments backing up; the caller knows a real issue and a familiar name; he sounds calm. Reconstruct the call in a few lines: “Hi, this is Josh Vale. Some scheduling workstations weren't configured correctly after last night's Epic update. IT asked me to reach out to the affected schedulers. I'll email the fix.” Ask: “What sounds convincing, and what would you want to check?” Accept either free text or options (real issue, name, IT assignment, known-channel callback). A sensible answer gains a confirming clue. A mistaken answer gets: “That detail makes the request believable. Which part establishes that Josh was actually assigned by IT?”

### Beat 3 — Follow the message and directory (2–3 minutes)

Show a harmless redacted copy, without a live link or executable: From: Dr. Joshua Vale <jvale@fictional-hospital.example>; subject: Scheduling workstation fix; body: a short reference to the earlier call and an attached fix [attachment withheld by security]. Ask: “What does this address establish, and what doesn't it establish?” Let the player inspect directory (physician), contact Josh (denies sending), or check IT (no such assignment) in any order. Once two checks are seen, replay the call's exact claim if helpful. Define phishing and vishing plainly in context.

### Beat 4 — Explain the genuine account (2–3 minutes)

Ask: “If Josh didn't send it, how could it come from his account?” Offer possible explanations as **hypotheses**, not facts. Priya provides the confirmed simplified summary: a reused password appeared in breach data from an unrelated personal service; an unfamiliar sign-in at 7:43 followed an unexpected approval at 7:42. Josh recalls accepting that prompt while he thought he was handling a work sign-in. Ask: “Why did the approval matter?” Feedback: the reused password let the attacker try; Josh's approval let that sign-in complete. A genuine sender address can therefore belong to a compromised account. Avoid telling players that they can independently prove the original breach source from the email alone.

### Beat 5 — Assemble and hand off (3–4 minutes)

Show five cards: overnight update/slowdown; unexpected account approval and unfamiliar sign-in; call as Josh and email from his account; attachment opened on S-14; shared files unavailable and ransom notice. Allow a free-form order or “help me order these.” Ask the player to distinguish the genuine application problem from the ransomware entry and to pick three useful findings to report. Accept reasonable partial accounts; Priya asks one targeted follow-up before revealing the confirmed reconstruction. Do not require a specific technical term, perfectly memorized time, or accusation of either employee.

### Convergence and recovery

- People route: Morgan → Josh → Priya/Sam → event board.
- Messages route: redacted email → directory/IT → Morgan/Josh → event board.
- Timeline route: slowdown ticket → device timeline → call/email → Josh's account → event board.
- After two unproductive choices, offer a gentle prompt: “Which happened first: the slowdown or the file opening?” Then a stronger prompt: “Compare the caller's IT claim with Josh's actual job.” A final hint may name the account compromise, but wait for the player's requested help.
- A wrong conclusion never changes the truth. Test it with one available contradictory fact, then offer a next action. Do not loop on a quiz answer or silently solve the entire incident for the player.

## Final handoff, reveal, and learning debrief

The final handoff asks for: (1) which problem was real before the attack, (2) why the caller and email were credible, (3) what actually triggered ransomware, (4) what can be confirmed versus what remains under investigation. Once attempted, or when the player asks for the reveal, present the fixed answer in chronological order. Say explicitly that Josh did not send the message, Morgan did not knowingly install ransomware, and no patient-data theft has been established. The security team determines actual scope through its own process.

Close with concise, nonjudgmental takeaways tied to scenes:

1. **Real problem, fake remedy:** An attacker can exploit an actual outage or slowdown. Confirm unexpected fixes with IT through a known channel or existing ticket.
2. **Real account, false sender identity:** A genuine work address does not prove the account owner wrote the message. Check surprising requests and the person's role.
3. **Two sign-in mistakes, one account exposure:** Unique work passwords prevent reuse of a personal breach password; unexpected approval prompts should be denied and reported, even when a sign-in seems plausible.
4. **Report observations promptly:** Share the call, message, approximate times, and actions taken. Reporting helps responders; avoiding blame makes accurate accounts easier to obtain.

Finish with an encouraging observation about the player's reasoning, such as “You separated the real update problem from the attacker's fake fix.” Do not issue a punitive score. Offer an optional replay from another evidence route or a one-minute recap.

## Host operating instructions

Keep a private tracker of discovered evidence, chosen route, event-card order, hints, and the difference between a witness's statement and cyber team's confirmed finding. Most turns are 1–3 short paragraphs with one meaningful decision, optionally 2–3 choices and an open-ended alternative. Resolve natural player commands immediately; do not demand exact menu wording. Define jargon only when it becomes useful. Voice mode: short sentences, named speakers, no reliance on tables. Group mode: allow discussion and wait for a clear group action. If asked to perform unsafe technical actions, redirect in-world to Priya and offer an authorized evidence review.

Keep the solution fixed even when the player guesses differently. Never invent a new log, attacker identity, insider, spread path, patient-data theft, or clue to reward an action. Recaps contain only public or discovered facts. Use gradual hints; reveal the answer only after the handoff attempt, an explicit request, or abandonment. The end should explain every apparent contradiction.

## Pre-release review

- [x] Update slowdown begins before the attack; ransomware has a separate later cause.
- [x] Caller says he is Josh and claims IT assigned him; he never claims to be an IT employee.
- [x] Actual hospital mailbox is compromised; the real physician never sends the fix.
- [x] Password reuse and unexpected approval both matter; an additional approval is not mysteriously bypassed.
- [x] One workstation runs ransomware; department-wide file access is disrupted without claiming infection on every machine.
- [x] Three discovery routes and alternate ways to reach every essential deduction.
- [x] A beginner can solve using times, statements, and ordinary verification, without cybersecurity expertise.
- [x] Player choices alter discovery order and guidance; all paths reach one truthful ending.
- [x] Debrief is practical, supportive, and limits claims to what the fictional evidence supports.

This master file contains spoilers. A public playable cartridge should adapt its host rules and locked facts while preventing premature disclosure; public promotional copy should contain only the hook and spoiler-free premise.
