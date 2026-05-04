# Playtest Session 6: The Harrow (in harrow app)

**Date:** 2026-05-01 (Cold Open, Acts) → 2026-05-02 (Bomb scene) → 2026-05-04 (capture)
**Loom:** The Harrow (sci-fi horror)
**Players:** 2 — User playing Archie and Jude; Claude playing Mira Valen and Tomas Reyes
**Tooling:** harrow web app, two isolated browser contexts (one per Claude character) so each character had its own localStorage and player identity

---

## Setup

Four characters at the table:

- **Archie** — The Pilot. Drive: Control. Approach: Direct. Memory: Replay (a navigation error that killed his co-pilot).
- **Jude** — The Doctor. Drive: Family. Approach: Quiet observation. Memory: Cost (someone who trusted her completely).
- **Mira Valen** — The Signals Tech. Drive: Curiosity (TRUTH). Approach: Nervous energy (MOTION). Memory: The last transmission from someone who went dark (DARK).
- **Tomas Reyes** — The Specialist. Drive: Redemption (PENANCE). Approach: Protective (WALL). Memory: Something he saw on a previous contract that nobody believed (WITNESS).

Random ring connections at game start:
- STATIC (Mira → Tomas): "What does Tomas hear when no one's listening?"
- VITAL (Tomas → Jude): "Will you let Jude treat what's wrong with you?"
- WATCH (Jude → Archie): "How long until Archie breaks, and will you be ready?"
- WING (Archie → Mira): "What do you owe Mira at the seat beside yours?"

Anchors / opener at start: GLITCH (Judith inconsistencies), OVERRIDE (manual override), WRECK (Acheron-9 derelict on path) — opener rolled was OVERRIDE.

---

## What Happened (by phase)

### Cold Open

Each character at their station, alone. Archie at the bridge muttering to himself ("Why did the pods open?... Something is not right, Archie. We need to be careful"). Jude in med bay digging into Acheron-9 records, not crew vitals. Mira at comms pulling wake-logs, snooping into network access logs out of nervous energy — caught Jude's database query from med bay. Tomas the last out of his pod, staying to count bodies before the others, then trailing the group at a half-step.

**Honors:**
- Archie: Replay (Memory)
- Jude: Cost
- Mira: MOTION (Nervous energy)
- Tomas: WALL (Protective)

**New threads opened during Cold Open's tail:**
- *"How far will Mira go with access she shouldn't have?"* — 1-ref personal on Mira. Player-authored after Mira's snooping was earned by fiction (she actively pulled network access logs she shouldn't have had).

### Act One — Scene 1: Mira + Jude in Med Bay

Mira walked into med bay using the post-cryo physical as cover. Jude turned around slowly, did not minimize the Acheron-9 record on her screen, made deliberate eye contact and welcomed Mira in. Mira sat for the exam. While Jude wrapped the cuff and pressed the stethoscope, Mira said flatly: "You were looking up the *Acheron-9*." Jude reframed without lying outright: "A ship previously in our route goes offline, and we wake up unexpectedly before we are supposed to reach their last known location. I could not help myself but see what all we know about that ship." Mira clocked the smoothness — too rehearsed for "couldn't help myself." She didn't push. Took the long way back to comms.

**Honors:**
- Mira: TRUTH (Curiosity) for walking in with the timestamp slip in her pocket
- Jude: not clearly clicked (user narrated; mechanical state unclear)

**Mira also clicked HONOR on the snooping thread.** This was mechanically invalid — the snooping thread isn't an established element. Filed as [harrow#5](https://github.com/mostlyfuzz/harrow/issues/5). User said "keep the extra die for great roleplaying effort."

**New thread opened:**
- *"Mira Valen thinks Jude is hiding something — what is it?"* — 2-ref shared, between Mira and Jude. Captures what's now genuinely table-unknown (the *specific* shape of what Jude hides, beyond the family connection that BLOOD already revealed).

**Thread that *didn't* get opened:** "Jude's connection to Acheron-9" — table already knows from BLOOD body that Jude has family there. Threads are for what's unknown to the *table*, not what's unknown to a character.

### Act One — Scene 2: Tomas + Archie at the Bridge

Tomas's circuit (cryo, quarters, galley, cargo, med bay, comms) ended at the bridge. He stopped two meters behind Archie's chair, watched his shoulders set, the back of his neck. Asked: "Anyone else been up here yet?" Archie, half-smiling: "Just the four of us... You should address me as Lead Archie... will let it pass this time." Tomas listed the count: override from inside, derelict eight hours closer than expected, four people who shouldn't be awake. Then quietly: "I've been on a job that started like this once. Not exactly. But close enough that I notice." Archie deflected: "Remind me Tomas, what is your specialty again?" Tomas: "Derelict response. Salvage and recovery on ships that went dark. Meridian contracts, mostly." Flat delivery. Archie ignored the implication, claimed Tomas onto the team, and made a unilateral call: "no need to wake up anyone else, the four of us will uncover the mystery."

**Honors:**
- Tomas: WALL (making rounds, putting himself between problem and crew) and WITNESS (the unbelieved past leaning into the room without him naming it)
- Archie: Direct (asserting Lead with the half-smile)

**New thread opened:**
- *"Why these four?"* — 0-ref shared. Reframed by the user from "why didn't the other two pods wake" to the sharper haunting question. Connects to OVERRIDE without being redundant: OVERRIDE asks who fired it; this asks who was *chosen* to wake.

### Act One — Scene 3: All Four in the Wardroom

Archie called everyone for ration check. Seating choices said things: Archie head-of-table, Tomas on his left back-to-wall, Mira across from Tomas with view of the door, Jude at Archie's right (closest to him, watching the room before eating). Archie gave a corporate-flavored welcome speech: "punctuality... seize the moment... Meridian motto... GO TEAM." Conspicuously omitted the override question.

Mira asked it for him: "Who do we think pulled the override?" Archie deflected by delegating: "Excellent question, Mira! Actually, I was hoping you would take charge of that question, but I think the #1 priority is our arrival to Acheron-9..." Mira pinned the delegation down by claiming the authorization out loud in front of witnesses: "I'll need access to the override system logs. The authentication chain. The wake-cycle telemetry from all six pods. I assume that's authorized now."

Tomas: "Lead — before we plan the arrival, I should ask. Are we docking, or observing from station-keeping distance?" Jude (per the user, knowing she was lying for crew morale): "Docking should be safe, we have proper protocols to safely enter hostile environments without contaminating our own." Archie: "Docking was exactly what I was thinking. Thank you Jude for confirming my thoughts." He delegated docking-prep to Tomas with "let ME know what you need."

Tomas accepted the delegation and used it to lay out his procedure: buddy system on EVA, hard quarantine on return, twelve hours minimum, no interior doors opened until sensor logs cleared from outside, "if any of those line items become inconvenient, you tell me before we breach, not after." A checklist that read, to anyone listening hard, like the corrected version of someone else's mistake.

**Honors:**
- Mira: TRUTH (the brave question)
- Tomas: WALL (procedural barrier between Archie's eagerness and crew safety) and PENANCE (laying out exhaustive procedure as the redemption move)
- Archie: Control (reframing Jude's lie as confirmation of his thoughts)
- Jude: Cost (the lie for the team's morale)

**No new thread opened.** Two candidates were considered ("Who at this table actually trusts the others?" and "Will Archie defer to Tomas when protocols slow him down?") — neither felt earned. User flagged that forcing a thread per scene was too tight and proliferation should be measured at the act level. Filed as [harrow#7](https://github.com/mostlyfuzz/harrow/issues/7).

### Bomb Naming

Tension that Act One revealed: nobody trusts anyone, and everyone is acting like they get along, before reaching a possibly extremely dangerous situation. Some back-handed shenanigans coming.

**Bomb opened as a thread:** *"Will the facade hold?"*

(This was a mistake — see Bomb scene below.)

### Act Two — The Bomb: Mira → Tomas in the Corridor

User asked Claude to play one character so the bomb scene would be a real conversation. Claude took Mira (the data-bearer); user took Tomas (the receiver, whose decision becomes the rupture).

**Frame:** Lowest-trust pair was Mira ↔ Jude (mutual, recent), but the move that breaks the facade is *one of them going to a third*. Mira goes to Tomas — the watcher with no agenda yet, no current grudge against her, adjacent via STATIC. She finds him at the end of his last walk before sleep cycle, in the corridor between airlock and wardroom.

Mira holds out her override-investigation printout. The authentication chain is corrupted in places, but one thing survived: a biometric ping inside the ship at the moment of the override that doesn't match any of the four signatures on record. **It matches a name from the Acheron-9 manifest.** Mira: "I think we have a name for who pulled the override. I just don't think they're on this ship. I think they're on the one we're docking with. I didn't know who else."

**Honor:** Mira: DARK (Memory: the last transmission from someone who went dark — she's now the one transmitting from a place of going-dark, naming someone who shouldn't exist).

Tomas's face goes pale staring at the paper.

Mira: "You recognize it." A statement.

**Pull on WITNESS — 2D — rolled 3, 5 → CLEAR.**

**Tomas's narration of the answer:**
> Tomas throws the paper to the floor and presses himself against the corridor wall, cheek to the metal, eyes shut, body straining as if the bulkhead could put more distance between him and the name.
>
> The thing Tomas can't take back is related to this person, **Sars**. Not only is it impossible for them to have opened the pods — they are dead. Tomas has seen them show up in other random missions. Weird glitches, Tomas thought. Now it is impossible to chalk to odd coincidences or glitches.

WITNESS closes (Clarity branches). Mira picks up the printout, folds it once, tucks it inside her uniform against her ribs. Doesn't run it to Archie. The four-person facade became three-and-a-half.

### The Break (no roll, no prevention)

Per the bomb-scene rule, a thread breaks open at scene end, by table declaration, no dice.

**Thread broken: PENANCE (Tomas, Drive: Redemption — *Does the slate ever come clean?*).**

Why PENANCE: Sars *is* the thing Tomas can't take back. The previous-contract trauma he's been carrying is no longer a glitch he could explain away. The redemption arc structurally compromised in the moment of revelation. The break landed where it actually hurt.

**Wound attached: *Denial*. Tier 1 (Scarred). 1d6 manifestation zone: 1–3. Source: Sars.**

Going forward, when Tomas honors or pulls PENANCE, roll 1d6 first. On 1–3 the wound manifests: Tomas refuses to acknowledge or act on what he knows. The slate won't come clean, so push it down.

(First wound name was *Sars* — corrected during playtest. The wound's name should be the *behavior it produces*, not the source. Sars is what wounded the thread; Denial is how the wound shows. Rulebook updated to reflect this distinction.)

### Cleanup mid-bomb

**Retired thread:** *"Will the facade hold?"* — opened as bomb-thread placeholder, but it failed the generativity test. Yes/no answer with no fiction inside the thread itself. The actual rupture landed elsewhere (PENANCE). Mentally retired. Ravel rulebook now has a Thread Shape note about generativity.

---

## Dice State (end of Bomb scene)

- **Mira:** 5 dice (Cold Open MOTION + Scene 1 TRUTH + Scene 1 snooping [extra, kept for roleplay] + Scene 3 TRUTH + Bomb DARK)
- **Tomas:** 4 dice (after spending 2D on the WITNESS pull). Cold Open WALL + Scene 2 WALL + Scene 2 WITNESS + Scene 3 WALL + Scene 3 PENANCE + an extra honor I miscounted — pool reconciliation needed
- **Archie:** tracked by user
- **Jude:** tracked by user

Pool counts off-by-one in places; user agreed to keep extras for roleplay and we're not micro-correcting.

---

## Thread Board (end of Bomb scene)

**Shared / world / connection (active):**
- STATIC (Mira → Tomas)
- VITAL (Tomas → Jude) — never engaged with
- WATCH (Jude → Archie)
- WING (Archie → Mira)
- GLITCH (Judith inconsistencies)
- OVERRIDE (manual override) — partially answered by Mira's investigation; Sars's biometric named
- WRECK (Acheron-9) — looming
- *"Mira thinks Jude is hiding something — what is it?"* (2-ref Mira+Jude)
- *"Why these four?"*

**Yours/peer character threads (active):**
- All loom-given threads (3 per character) — except WITNESS (Tomas's) which is now CLEAR
- Mira's player-authored snooping thread

**Retired:**
- *"Will the facade hold?"*

**Wounded:**
- PENANCE (Tomas, Drive) — Wound: *Denial* (source: Sars). Tier 1 (Scarred). Zone 1–3.

**Closed via Clarity:**
- WITNESS (Tomas, Memory) — answered: *Sars is the dead biometric Tomas has seen across multiple missions, dismissed as glitches, now confirmed real.*

---

## Issues Filed During Session

- [harrow#1](https://github.com/mostlyfuzz/harrow/issues/1) — Hide peer character thread bodies until revealed
- [harrow#2](https://github.com/mostlyfuzz/harrow/issues/2) — Player-opened threads have no theme tag
- [harrow#3](https://github.com/mostlyfuzz/harrow/issues/3) — New-thread input has no character picker
- [harrow#4](https://github.com/mostlyfuzz/harrow/issues/4) — Filter threads by character / scope
- [harrow#5](https://github.com/mostlyfuzz/harrow/issues/5) — Honor button shown on threads that aren't established elements
- [harrow#6](https://github.com/mostlyfuzz/harrow/issues/6) — Disable HONOR button after a thread is honored in the current scene
- [harrow#7](https://github.com/mostlyfuzz/harrow/issues/7) — Soften "open or branch a thread per scene" rule in Act One
- [harrow#8](https://github.com/mostlyfuzz/harrow/issues/8) — No UI to declare a thread Break without rolling
- [harrow#9](https://github.com/mostlyfuzz/harrow/issues/9) — No UI for the wound model on broken character/relationship threads
- [harrow#10](https://github.com/mostlyfuzz/harrow/issues/10) — No UI to retire/collapse/merge threads

---

## Rulebook changes that came out of this session

- **Seasons section** added to RULEBOOK.md (5–6 episodes, Finale as engine-in-reverse, five inversions for the finale).
- **Breaks section rewrite** — split into story / character-relationship lineages; introduced the wound model for character and relationship threads (Tier 1/2/3, 1d6 manifestation zones). Recovery via Clarity reduces tier.
- **Thread authoring note** in Thread Shape: a thread's answer should generate fiction inside the thread itself, not just trigger consequences elsewhere. Cited *Will the facade hold?* as the negative example.
- **The Harrow loom**: added "Records refusing to agree" to the Pressure Palette — gives players a manifestation hook for the loom's forensic-time horror (cryo discrepancy, Pilot's replay, Acheron-9's last transmission).

---

## Open beats heading into Echo

- Mira and Tomas now share the *Sars* secret. They have not told Archie or Jude.
- Acheron-9 is six hours out at end of Bomb scene.
- Jude lied about docking safety; Tomas's checklist quietly corrected her without naming it.
- VITAL is unresolved — Tomas avoiding Jude's exam, Jude knows there are things on his file that aren't there.
- Echo scene needs a second thread to develop alongside the bomb. Pressure visible. Manifestation territory.

---

## Balance observation (mid-Collision pause)

Honor-to-pull ratio was heavily lopsided across Act One and Act Two. Across the table we landed roughly 18+ honors (multiple per character per scene, many earned legitimately by playing established elements through fiction). We landed three pulls total: Tomas's WITNESS (2D, Clear), Archie's EDGE (Clear), and the implicit "no-roll" wound on PENANCE.

That left rough pool counts entering Aftermath at ~4–5 dice per character — a lot of unspent agency.

**Possible reads:**
- The fiction simply didn't call for pulls. Acts 1–2 were establishment-heavy, pressure-visible, manifestation-rich. Resolution moments were rare because the table was building, not resolving. Aftermath is structurally pulls-only and will burn pool fast.
- Or honors are over-generous as currently designed — character threads earn dice too easily relative to the rate at which threads need resolving, leading to inflated pools that flatten the cost of pulls.
- Or pulls feel high-stakes (commit dice, accept potential Break) and players defaulted to honor-and-establish, dodging the resolution risk. If that's a pattern, the dice economy isn't actually creating pressure — it's accumulating capital.

**Worth watching:** Across multiple full-episode playtests, are pools naturally drained by Aftermath, or do players end episodes still rich? If the latter, the economy needs tightening — either fewer honors per scene, or pull-encouragement built into earlier act structure.

Not a rule change yet. A flag for future sessions to track.
