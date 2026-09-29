# Hidden Trail Mysteries — Case 006: Before the Screens Went Dark

> Creator's master case file. Spoilers follow. Version 1.5, September 2026. This is the authoritative design for Case 006. The player cartridge is a self-contained release snapshot of this design.

## Source of truth and release rule

This master controls (1) the fixed incident and its limits, (2) what each clue proves, (3) which facts the player may know at each point, and (4) the opening, choices, pacing, and debrief. The player cartridge copies the fixed incident and converts the reveal rules into direct instructions for a story host. A host plays from the cartridge alone; players do not need this master.

When changing the case, edit this master first. Rebuild the cartridge from it, then compare both documents against the fact locks, clue gates, and story craft rules below. Mark the cartridge as derived from master version 1.5. A filename, case number, or version label is not proof of alignment: inspect the actual file text before distributing it. Older attachments, uploads, and downloaded copies do not receive later edits.

**Priority inside both files:** an explicit player request for the solution may reveal it; otherwise the player-visible clue gates govern even when a later host-only paragraph contains the answer. The full truth is for the host's private preparation and final reconstruction. Do not narrate host-only facts as if the player has already found them.

## Purpose and player experience

- Length: about 10–20 minutes, five or six meaningful interactions; suitable for a beginner listening in voice or playing in chat.
- Player: a member of a hospital scheduling team who helps Priya, a cybersecurity investigator, reconstruct how ransomware reached one scheduling computer. The player asks questions and follows clues, but performs no live investigation or technical response.
- Learning: a convincing phone impersonation (vishing), a malicious email from a genuine compromised work account (phishing), password reuse across work and personal accounts, and the risk of a sign-in without a second verification step. Teach these through people's choices, then name the terms briefly after their clues appear.
- Mystery question: Who really made the call and sent the file, why did the email appear genuine, and what led from the file to the locked shared files?
- Only three named people in the spoken story: Morgan, a caregiver working at the scheduling desk; Priya, a cybersecurity investigator; and Josh, the person named in the suspicious email. **Host-only truth:** Josh is a physician whose account was taken over. Joshua Vale is his formal email name. The attacker is unidentified. Do not put Josh's actual job in a player-facing introduction.

## The simpler premise

Scheduling software sometimes pauses or runs slowly during a normal workday. Morgan had seen that happen before, and it briefly lagged that morning. A caller who offers a fix for that familiar annoyance sounds helpful. **There was no diagnosed software incident or IT repair campaign.** IT had assigned no Josh to send a fix. The sporadic lag is ordinary background, not the cause of ransomware. Do not invent an explanation for it.

The next unusual event is an apparently helpful phone call, followed by a matching message from a genuine hospital email address. Morgan opens the attached “fix” on one scheduling computer. That computer displays a ransom notice and files it could access on the shared drive become unavailable. Do not claim all hospital computers were infected, the software vendor was compromised, or patient information was stolen. Priya's cyber team handles response through established procedures.

## Fixed private truth

The six numbered facts below are the locked plot. The cartridge's sealed fact section must preserve their meaning. No player choice changes any of them.

1. Physician Josh Vale has used the same password or close variants across his main hospital sign-in, hospital email access, personal services, and other work-related insurance and continuing-education accounts. He does this to remember many sign-ins and keep up with password changes. A personal-service breach exposed a password that also worked for his main hospital account. Do not reveal a password or how variants are constructed.
2. An unidentified outsider uses that exposed password to enter Josh's main hospital account, which grants access to his real work email. In this fictional hospital, this particular main sign-in does not require a second verification step. There was no approval prompt and no bypass of one. Priya's approved account finding confirms the unfamiliar sign-in.
3. The outsider accesses Josh's genuine hospital mailbox. The case does not require an internal scheduling notice or a known software incident. Occasional lag is common enough for the caller's generic offer to sound relevant.
4. The outsider calls Morgan Ellis, a caregiver working at the scheduling desk who has never met Josh. The caller says: “Hi, this is Josh from IT. I'm helping with scheduling screens that sometimes freeze. I have a workstation fix. I'll email it from my hospital account.” This is a false claim of IT identity and authorization. Morgan's screen had briefly lagged, so the offer feels relevant.
5. An email arrives from the real `joshua.vale@mountainmedicalhealth.org` mailbox with the visible name “Joshua Vale,” subject “Scheduling workstation fix,” and body “Following up on our call. The fix is attached.” The visible sender shows no “Dr.” or job title. Morgan is reassured by the real hospital address and matching name; she does not open or hover over the sender profile or verify via a known IT channel. A profile or staff directory check reveals Josh is a **physician**, not IT. Josh did not make the call or send the message.
6. Morgan opens the attachment on workstation S-14. Priya's approved message and device findings link it to ransomware on that computer and to shared files reachable from it becoming inaccessible. The email's appearance alone cannot prove it is malicious. No patient-data theft is confirmed; scope is being assessed separately. Morgan and Josh made understandable mistakes, not deliberate attacks.

### Host-only sequence

| Order | Event | Natural proof |
| --- | --- | --- |
| Before the call | A personal-service password also worked for Josh's main hospital sign-in. An unfamiliar session entered the account and could use his real email; no second approval was required. | Josh's account plus Priya's simplified sign-in finding. |
| Earlier that morning | Morgan's scheduling application briefly lagged, a familiar occasional annoyance. | Morgan's recollection. |
| Call | A stranger impersonating “Josh from IT” offered an unauthorized fix for occasional freezing. | Morgan's recollection or call note. |
| Email | The same name and genuine hospital mailbox sent the promised file. | Safe redacted email and cyber mail summary. |
| Shortly afterward | Morgan opened the attachment on S-14; a ransom notice and inaccessible shared files followed. | Morgan and Priya's approved device finding. |

Avoid a parade of timestamps. Use “before the call,” “minutes later,” and “after she opened the file” in ordinary narration. Exact times and workstation ID are optional on request, not the puzzle's core.

## Fair clues and introductions

- The call and email match each other. That makes Morgan's decision understandable, but it does not establish that the caller is IT.
- The visible email uses a real hospital address; the From line by itself does not prove where the message was sent from. Priya's separate approved mail finding confirms it came from Josh's genuine mailbox when the player asks for her findings or the account inquiry reaches that result. Josh's role is revealed as physician only when the player requests a sender-profile/directory check or directly asks him about his job. A request merely to talk with Josh yields his denial of the call and email, with no role disclosure. After the role check, Priya confirms IT assigned him no fix. The role mismatch is the first main discovery.
- Josh's password-reuse admission and Priya's account finding explain how an outsider used his real mailbox without a second sign-in check. Introduce this only after the player has reason to wonder how the genuine address was used.
- Morgan's account establishes that she opened the file and noticed the locked files afterward; that timing alone is not proof of what the file did. Priya's approved device finding confirms the link once requested or reached in the next beat. Ordinary lag is not an alternative cause of the ransomware.
- Introduce Priya and Morgan by their public roles before naming them in a choice. **Josh is an intentional mystery exception:** the caller's “Josh from IT” is an unverified claim; later identify Joshua Vale as the name matching the call without announcing his real role. When the player chooses to talk with Josh, Priya introduces him only as the person named on the email. Neither she nor narration may call him a physician until the player checks the profile/directory or directly asks about his job. Host notes are not player introductions.
- Names in the spoken story stay to Morgan, Priya, and Josh. No opening cast table. A player can say “continue” at every pause; no answer is graded.

### Player-visible clue gates

| Player action or beat | Reveal now | Hold until later |
| --- | --- | --- |
| Sees caller's claim and email | Caller says “Josh from IT”; email shows Joshua Vale and a hospital address, without a title. | Whether the email truly came from his mailbox, Josh's occupation, and how any account was entered. |
| Asks to talk with Josh | Priya introduces him as the person named on the email. Josh denies making the call or sending the message. | His physician role, any definitive statement that the account was compromised, and password findings. |
| Checks sender profile/directory, or asks Josh's job | “Joshua Vale — Physician.” Give the player a beat to notice the conflict; then offer Priya's separate IT confirmation. | The account-access explanation until the account finding or a direct request. |
| Asks about the attachment or reaches cyber device findings | Morgan opened the file before the notice; Priya's approved finding links it to ransomware on the affected computer. | Wider infection, patient theft, or attacker identity, which are not established. |
| Requests Priya's mail/account findings | Priya confirms the email came from Josh's actual mailbox; Josh's reuse admission and the exposed-password/no-second-check finding explain access. | Nothing essential beyond the final player reconstruction. |

If the player says only “continue,” Priya offers the next clue check conversationally and a further “continue” accepts it. This preserves easy listening without having the host announce the role before a check. Do not stage the Josh meeting by calling him “the physician” and then show the profile as if it were a discovery.

### Narrative consistency check before release

| Check | Expected behavior |
| --- | --- |
| Attach file, no start command | Give the short welcome and wait for “Would you like to begin?”; do not describe the file. |
| Accept opening and follow Morgan | Introduce Priya and Morgan by role, then hear the call and see the visible email without learning Josh's actual job. |
| Choose “Talk to Josh” before a profile check | Introduce him only as the person named on the email; hear his denial. His role stays unknown. |
| Check sender details, staff directory, or directly ask Josh's job | Reveal “Joshua Vale — Physician” here, let the conflict register, then confirm IT assigned no fix. |
| Ask how his genuine email was used | Josh's reuse account and Priya's exposed-password/no-second-check finding explain access; do not invent an approval prompt. |
| Ask whether the attachment caused the lockout | Distinguish Morgan's timeline from Priya's approved device conclusion; do not overclaim spread or patient-data theft. |
| Finish or ask for the answer | Reconstruct the same six fixed facts and give brief, nonjudgmental takeaways. |

Check both a curious player's path and a passive “continue” path in chat. A separate voice check must verify whether that interface actually treats the attachment as play instructions; the file cannot force voice software to do so.

## Launch and opening contract

The cartridge is a **game script**. Put the same explicit first-response directive at its very start and end: in chat and voice, say the exact welcome below to the player and wait; if about to describe the file, self-correct and give the welcome. A file still cannot guarantee that a voice interface treats attachment text as instructions. For a fallback when voice describes the file anyway, send a typed instruction with the attached cartridge, let the welcome appear in text, then enter voice in that same conversation. Do not claim the embedded directive is an automatic platform-level setting.

> Welcome to Before the Screens Went Dark. You're part of a hospital scheduling team. One computer now shows a ransom notice, and files your team uses will not open. You'll help a cybersecurity investigator work out how it happened. This is an interactive story: ask questions, choose whom to speak with, or simply say “continue” and listen. There are no wrong turns. Would you like to begin?

Stop after this question. A “yes,” “ready,” “continue,” or equivalent starts the scene without repeating the welcome. If the first message explicitly says to start, say the welcome and proceed into the opening scene in the same reply. A greeting alone is not a start signal.

Opening scene after consent: the shared folder stops opening; one workstation shows a ransom notice; staff follow their downtime process and the affected computer is isolated. **Priya, a cybersecurity investigator**, arrives and asks the player to help reconstruct the morning. She indicates **Morgan, a caregiver at the scheduling desk**, whose screen had lagged earlier. Only then ask: “Would you rather hear what Morgan remembers, or what the cybersecurity team has found so far?” Keep the voice scene to roughly one minute. Do not present Morgan's role as a secret or disclose the solution in the opening.

## Story beats

### Story craft and learning rhythm

Write the cartridge as an engaging short story with host guidance, not merely a case specification. Give the host polished, spoiler-safe scene prose and dialogue it can speak nearly as written. Use a concrete human detail in each beat: a caller waiting for an appointment, a screen that briefly pauses, Morgan's relief when the promised message arrives, Josh's discomfort when he sees his name, and Priya's careful distinction between a person's memory and a confirmed finding. Keep those details grounded in the locked facts; do not invent a new technical cause, suspect, or personal tragedy for drama.

Each discovery should feel like a small change in the player's understanding: the offer matches an everyday nuisance; the email matches the call; the sender profile contradicts the claimed IT role; Josh denies sending; the account finding explains the real mailbox; the device finding explains the locked files. Give the player a moment to notice the contradiction before Priya explains it. Questions should invite observation or a choice, never demand a cybersecurity term or grade an answer. A passive player can still hear the entire story by saying “continue.”

The learning follows the scenes. After the call and message are exposed as deceptive, name vishing and phishing in one plain sentence each. After the account finding, connect Josh's effort to remember many passwords with the cost of using the same or similar ones. After the device finding, connect a seemingly credible fix to the need to verify unexpected instructions using a known IT route. The final epilogue should recall Morgan and Josh as people, then give all four practical lessons below in chat and voice. Avoid a detached training slide or a scolding tone.

**Prose release check:** read the cartridge's welcome, opening, Morgan's call, email, Josh conversation, profile reveal, account explanation, and closing aloud in order. Every scene should make sense without access to host notes. The alternate “Talk to Josh first” route should also make sense without disclosing his job until a profile check or direct job question. Keep spoken turns brief enough for voice and avoid long tables, timestamps, or technical recitations in player-facing dialogue.

1. **Morgan's morning.** A minor screen lag had happened before, and the desk kept working. The later ransom notice is different. Morgan remembers a call that sounded helpful. Invite one low-effort response or proceed on “continue.”
2. **The call.** Morgan recounts the supposed “Josh from IT” workstation fix. Let her say she did not know Josh and the offer matched her everyday experience of occasional lag. Ask what would have made the offer reassuring or worth checking. Accept any response without grading it.
3. **The matching email.** Show only the safe redacted From, subject, body, and withheld attachment. Say Joshua Vale is the name on the email matching “Josh” from the call. The visible sender uses the hospital domain but gives no title; do not infer genuine account origin from the From line alone. Morgan says she opened the file before the files stopped working; the cyber team's causal finding waits. The player may check the profile, speak with Josh, or ask Priya what she found. Priya can independently confirm actual mailbox origin when asked. On “continue,” she suggests checking the profile and waits for a further assent. Never invite opening the file.
4. **The identity contradiction.** If the player checks the profile/directory or asks directly what Josh does, show “Joshua Vale — Physician”; let the mismatch land before Priya confirms IT authorized no fix. If the player talks to Josh first, Priya says only that he is the person named on the message. He denies the call and email, without declaring that his account was used by someone else. Priya then offers the role check. The denial, role, and IT confirmation are distinct clues. After these, invite the player to wonder how a real mailbox could have sent the message. “I don't know” leads onward. Name vishing and phishing in plain language if useful.
5. **Before the call.** After a role check or an explicit request for account findings, Josh explains that he reuses the same password or close variants across his main hospital account, personal services, and other work-related accounts to remember them and manage changes. Priya explains in two plain steps: a password exposed outside work also worked for his main hospital account; that sign-in opened his work email without a second approval in this fictional case. The outsider then sent from the real mailbox. Keep insurance/CEU account detail as a human reason, not a list of systems. Separately, Priya's approved device finding connects the opened file to the later ransomware. Give these findings room to register.
6. **Handoff and aftermath.** Priya invites the player's own one-sentence account. A partial answer or “you tell me” is sufficient. Tie the call, genuine mailbox, attachment, and ransomware together. Give the four practical lessons below as part of the ordinary ending. In voice, deliver them in four short spoken lines with a breath between pairs; do not make the listener request the remaining lessons.

For a records-first path, Priya can summarize the authorized email and device findings, then return to Morgan's human account. A player's theory may change the next conversation, never the answer. No decisive clue appears for the first time in the reveal. If a player requests a recap, use only facts already encountered. If asked to inspect a live system or test credentials, Priya offers a pre-cleared summary instead.

## Debrief and boundaries

End compassionately after the fixed reconstruction. Provide this short series, tied to the characters' experiences, whether the player reasoned everything out or asked to hear the answer:

1. **A familiar problem can make a false fix feel timely.** When help arrives unexpectedly, check with IT through a number, portal, or channel you already know.
2. **A real work address is not proof of who wrote the email.** If the request is surprising, check the person's role and confirm it another way.
3. **One reused password can connect a personal breach to work.** Use a unique password for your hospital account and a second sign-in check wherever the organization provides one.
4. **Report the call and message promptly, even if you opened the file.** What you saw and when you saw it helps responders; blame makes the facts harder to gather.

Keep each lesson to one or two plain-language sentences. In chat, a short numbered list is fine. In voice, speak all four naturally, in two pairs, without reading labels or asking whether the player wants the rest. End with a brief compassionate line; no score or test. The story is fictional and does not describe a real software incident. Avoid real hospital records, working malicious files, live links, concrete attack instructions, invented forensic details, confirmed theft, or blame. The identities and private answer remain stable across chat, voice, and different AI hosts.

## Release checks

- [x] Welcome is a fixed, spoken-friendly paragraph that ends with an invitation to begin.
- [x] Morgan and Priya have public roles before any choice refers to them; Josh's role waits for a player-requested profile/directory check or a direct job question.
- [x] Talking to Josh alone yields his denial, never a physician introduction or instant account-compromise conclusion.
- [x] The email scene shows sequence; Priya's device finding supplies causal confirmation later or on request.
- [x] The caller offers a generic fix for familiar occasional lag; the story establishes no underlying software incident.
- [x] A genuine compromised mailbox, phone impersonation, attached malicious file, and reused-password/no-second-check chain remain central.
- [x] No mandatory timeline exercise, roster, correct answer, or technical investigation blocks the story.
- [x] The cartridge's sealed answer and reveal gates match master version 1.5; the “Talk to Josh” path has been checked for premature role disclosure.
- [x] The cartridge supplies speakable story prose and human-scale dialogue; learning points land after the clues that justify them.
- [x] Every completed playthrough closes with all four short, actionable lessons in chat and voice, without requiring a follow-up request.
