# COHERENCE REPORT — LA TRAQUE DE L'ATTENTAT DU MÉTRO 14

> **Prepared by:** Maxime Grenu (review pass, February 2026)  
> **Method:** Complete read of all 35 chapters + half-chapters + TEAM_DOSSIER.md + README.md  
> **Scope:** Character consistency, timeline, geography, plot holes, factual accuracy, structural integrity

---

## 0. EXECUTIVE SUMMARY

The novel has evolved far beyond its original README blueprint — and that evolution is largely brilliant. The story grew from a compact 20-chapter Parisian thriller into a 35-chapter transmediterranean manhunt epic. However, this organic growth left behind a trail of unresolved contradictions. This report catalogs **38 distinct issues**, rated by severity:

- 🔴 **CRITICAL** (breaks story logic entirely, must fix before any submission)
- 🟠 **MAJOR** (reader will notice, significantly weakens the story)
- 🟡 **MINOR** (internal inconsistency, easy to fix in editing pass)
- 🔵 **TECHNICAL** (factual error — weapons, geography, science)

---

## 1. CRITICAL CONTRADICTIONS 🔴

---

### C1 — JÉRÔME: SON vs. HOLIDAY FRIEND

**Location:** Chapter 8 vs. Chapters 18, 35, TEAM_DOSSIER.md  
**Issue:**

- **Chapter 8:** *"He thinks about Jérôme. About the thirty-minute delay. About how much time has passed since **his son** died."*
- **Chapter 18:** *"A friend died in the attack. Jérôme. **A holiday friend.** He was in the metro."*
- **Chapter 35:** *"A friend. **A holiday friend.**"*
- **TEAM_DOSSIER:** *"Motivation: Revenge (Jérôme — **holiday friend**)"*

**Impact:** This is Thomas's entire motivation. Is he hunting his dead son's killers, or a friend's? The moral weight is completely different. Three sources say "friend," one says "son."

**Fix:** Chapter 8 must be corrected to read "holiday friend" to match all other references. The word "son" appears to be a drafting error that was caught and corrected in later chapters but never retroactively fixed in Ch 8.

---

### C2 — DUPLICATE CHAPTER: CHAPTER_07 = CHAPTER_10 (IDENTICAL FILES)

**Location:** `/chapters/CHAPTER_07_LOUVRE.md` and `/chapters/CHAPTER_10_LOUVRE.md`  
**Issue:**  
`CHAPTER_07_LOUVRE.md` has the internal header **"CHAPTER 10: LOUVRE"** and its content is **word-for-word identical** to `CHAPTER_10_LOUVRE.md`. This means:

- Chapter 7 slot is **occupied by a copy of Chapter 10**
- Chapter 7's intended content (presumably a scene between the metro bombing and the massive truck attacks) is **completely missing** from the manuscript
- The novel jumps from Chapter 6.5 (Abdelkrim's recruitment backstory) directly to what is actually Chapter 10

**Fix:** Rename `CHAPTER_07_LOUVRE.md` to something appropriate (e.g., `CHAPTER_07_INVESTIGATION.md`) and write a new Chapter 7 covering the gap between the metro bombing aftermath (Ch 6) and the Louvre truck attack (Ch 10). Chronologically, this chapter should cover Thomas's initial investigation: the forensic results from the wheelchair bomb, the first interviews, and the discovery that the cell is planning a second wave.

---

### C3 — CASUALTY COUNT: 2,391 vs. 3,000

**Location:** Chapter 10 (running total) vs. Chapter 11 (opening)  
**Issue:**

- **Chapter 10:** Running total explicitly tabulated: *"Métro 14: 327 dead. Louvre: 478. Élysée: 341. Eiffel: 289. Bercy Barge: 956. TOTAL: 2,391."*
- **Chapter 11:** *"Three thousand French dead."*
- **Chapter 15 notes:** Confirms "2,391 dead"
- **Chapter 18:** Thomas's motivation cites "2,391 dead"

**Impact:** France's government, Thomas's colleagues, and suburban residents cannot simultaneously cite 2,391 and 3,000. This is a 609-person discrepancy that undermines the authority of both chapters.

**Fix:** Standardize to **2,391** throughout the novel (it's the specific, documented figure). In Chapter 11, change "Three thousand French dead" to "Nearly twenty-four hundred French dead" or simply "2,391 French dead." The round figure "three thousand" was likely an early placeholder that was never updated after the precise count was established.

---

### C4 — THREE CONTRADICTORY EXPLANATIONS FOR HOW THOMAS FINDS TADRART

**Location:** Chapters 30, 33, and 35 notes  
**Issue:** Three separate, mutually exclusive explanations are given for how Thomas locates Yasmine in Tadrart:

1. **Chapter 30:** Thomas traces a hawala money transfer code "TADR" cross-referenced with DGSE databases → points to Tadrart.
2. **Chapter 33:** A deed found in Malik's Zug safe lists the Tadrart property with exact GPS coordinates, naming Malik Benhadj as owner and Hassan Medjahed as secondary authority.
3. **Chapter 35 notes:** *"Hassan Medjahed (cell ideologue, captured in Lyon) broke under DGSE interrogation and revealed Tadrart location."*

**Impact:** All three mechanisms are used but never reconciled. The reader gets three different "aha" moments for the same plot point, which diminishes all of them.

**Fix:** Choose ONE primary mechanism (the deed in the safe is the most dramatic and plot-integrated), and fold the others as corroborating confirmation rather than independent discoveries. Suggested flow: Thomas's team traces the hawala code to a region → the deed in Malik's safe provides the exact coordinates → confirmed by Touareg surveillance on the ground. Hassan Medjahed's interrogation could predate all of this (he breaks but only gives partial intel), establishing that Yasmine went south without knowing exactly where.

---

### C5 — WHO OWNS/ARRANGED THE TADRART REFUGE?

**Location:** Chapter 13 vs. Chapter 33  
**Issue:**

- **Chapter 13:** Yasmine calls *"Hassan Boudjellal. Her cousin. The one who moved money. The one who funded the operation. The one who never left Paris."* He arranges the Tadrart refuge, sends a driver, prepares the house, provides servants.
- **Chapter 33:** Thomas reads a deed from Malik's safe: *"The property belongs to a Cayman Islands trust... The deed names the beneficiary: Malik Benhadj. Secondary authority: Hassan Medjahed."*

Two different people (Hassan Boudjellal in Ch 13; Malik Benhadj in Ch 33) supposedly own the same property. A third person (Hassan Medjahed, the ideologue in custody) is also listed. Hassan Boudjellal is never mentioned again after Ch 13.

**Fix:** Either (a) make Hassan Boudjellal a cover identity for Malik Benhadj (he uses multiple names in financial networks), or (b) make Hassan Boudjellal a genuine separate character who was Malik's front man for the property purchase, explain his connection to Malik, and have him appear in one other scene. Option (a) is simpler and requires fewer new pages.

---

### C6 — THOMAS'S MARSEILLE ARRIVAL: MV AGUSTA vs. FALCON 7X

**Location:** Chapters 11, 16, 27  
**Issue:**

- **Chapter 11:** *"He gets in the MV Agusta and he heads south toward Marseille."* Thomas is described as driving alone on a motorcycle, making a solo decision to pursue Yasmine.
- **Chapter 16:** *"The Falcon 7X lands at Marseille Provence Airport at 7:04 AM. Thomas exits onto the tarmac. A car is waiting. Black Peugeot 607. Government plates. Driver in civilian clothes. DGSE. Professional. 'Commander Dieudegard,' the driver said. 'I'm Beaumont. Your contact in Marseille.'"*
- **Chapter 27:** Thomas is described returning to Marseille after Yasmine has already crossed to Algeria — but there's no motorcycle, no car, no explanation of how he's moving.

**Impact:** The MV Agusta solo ride sets up a rogue-agent-going-off-books vibe that is completely contradicted by an official DGSE reception at the airport with government transport. One suggests Thomas is acting alone; the other suggests DGSE infrastructure was pre-positioned.

**Fix:** Decide which version of Thomas's Marseille arrival is canonical. The Falcon 7X arrival (Ch 16) better fits the rest of the story (he has a full DGSE team, unlimited resources, Director authorization). If keeping the solo MV Agusta ride, he should arrive independently and Beaumont should explain he was pre-positioned independently by the Director. The MV Agusta either arrives separately or is explained as Thomas's personal transport that he left in Marseille after switching to official vehicles.

---

### C7 — HASSAN JR.'S AGE: 21 vs. 32

**Location:** Chapter 11 vs. Chapter 21  
**Issue:**

- **Chapter 11:** *"Hassan Jr... He's young. **Twenty-one.** Operations assistant. He's been with the cell since planning began."*
- **Chapter 21:** Beaumont's surveillance notes: *"**Thirty-two** years old. Operational planner for the cell."*

**Impact:** 21 and 32 are entirely different people. A 21-year-old "operations assistant" vs. a 32-year-old "operational planner" have completely different backstories, credibilities, and narrative functions.

**Fix:** Standardize to **32**. A 32-year-old experienced operational planner is more consistent with someone who can hide in Palermo, maintain operational security, and warrant assassination by DGSE. At 21, he'd be too young and inexperienced for his described role. Update Chapter 11.

---

### C8 — MALIK'S AGE: 41 vs. 55

**Location:** Chapter 6 vs. Chapter 34 notes  
**Issue:**

- **Chapter 6:** *"Malik Benhadj is **forty-one**."*
- **Chapter 34 notes:** *"Malik: **55 years old**, 150 kilos"*

**Fix:** Standardize to **41** (established in-text, Ch 6) or **55** (consistent with the physical description of a heavy, slow-moving, overindulgent financier in Ch 34). A 55-year-old who's been in financial crime for decades is more plausible for the accumulated wealth. Update Chapter 6 accordingly.

---

## 2. MAJOR INCONSISTENCIES 🟠

---

### M1 — SAFE CONTENTS: CHAPTER 24 vs. CHAPTER 32

Both chapters describe the contents of Malik's Zug safe in detail. They contradict each other:

| Item | Chapter 24 | Chapter 32 |
|------|-----------|-----------|
| Gold bars | 12 bars (120 kg) | 24 bars (240 kg) |
| Watches | 15 watches | 27 watches |
| Cash | 1,000,000 CHF | 200,000 CHF |
| Diamonds | ~200 loose stones | 6 leather pouches |

**Context:** Chapter 24 was written to establish Malik's wealth accumulation over months. Chapter 32 was written as an action sequence where the team physically inventories and removes the contents. The two chapters must match.

**Fix:** Write the definitive inventory once (suggested: Ch 32 as the "reality" since it's the action scene), then backfit Ch 24 to use the same numbers. Note that a 5x discrepancy in gold (12 vs. 24 bars) is major — this affects the total value claim of "50 million CHF."

---

### M2 — AMINA ZEROUAL: TARGET ASSIGNMENT vs. ACTUAL ELIMINATION

**Issue:**

- **Chapter 18:** Thomas assigns targets: *"Target three: Amina Zeroual. Tunisia. Tunis. Communications specialist."*  
- **Chapter 23:** DGSE tracks Amina in Tunis — she **escapes** to Bizerte, then Portugal.  
- **Chapter 25:** Amina is **eliminated in Lisbon** (Portugal hotel, disguised as hotel cleaner "Fatima").  
- **Chapter 25 notes:** *"Leila is a name crossed off in another file."* This suggests Leila Hamadi was separately eliminated in Portugal, but **no chapter shows Leila's elimination**.

**Impact:** Target 3 (Amina/Tunisia) and Target 4 (Leila/Portugal) appear to have merged into one kill: Amina dies in Lisbon while Leila disappears from the story. If there were six escapees (Yasmine, Malik, Hassan Jr., Amina, Farid, Leila) and Thomas's team eliminates five of them, Leila's fate must be shown or referenced.

**Fix:** Either add a brief scene showing Leila's elimination (perhaps in Spain, as Amina passes through Barcelona), or explicitly state in Ch 25's narrative that "Leila had already been dealt with" by local police/Portuguese intelligence while Amina ran to Lisbon.

---

### M3 — FARID MESSAOUD AND LEILA HAMADI: UNDECLARED CELL MEMBERS

**Issue:**

- Chapters 1-10 establish the cell as: Yasmine, Malik, Hassan Medjahed, Inès Benmansour, and Abdelkrim Diallo (the wheelchair bomber).
- Chapter 11 introduces the escape plan with Yasmine, Malik, Hassan Jr., and Amina — four names, of which Hassan Jr. and Amina are entirely new.
- Chapter 17 introduces **Farid Messaoud** and **Leila Hamadi** — again, entirely new cell members, never mentioned before.

**Impact:** The cell's composition changes unexpectedly across chapters. Readers who track characters will notice these additions as inconsistencies. Good spy fiction requires a consistent, established cast.

**Fix:** In the investigation chapters (particularly Ch 5-6 at DGSE headquarters), Thomas should receive a broader intelligence picture: the cell is larger than initially thought, with additional "outer ring" members handling logistics and escape. Name Farid and Leila at that point as known/suspected associates so their later appearance feels like confirmation, not invention.

---

### M4 — INÈS BENMANSOUR: WOUNDED, ARRESTED, THEN FORGOTTEN

**Issue:**

- **Chapter 9:** Inès is shot in the arm during a gunfight in an underground location. She drops her detonator. She's neutralized by Thomas's team.
- **Chapter 11:** *"Inès Benmansour is not there. She was captured by police during the evacuation. She's being held. Being interrogated. Staying silent."*

After Chapter 11, Inès is **never mentioned again**. She's an arrested, injured terrorist being interrogated by DGSE with knowledge of the entire cell's structure. She should either:
- Provide intelligence that advances the investigation, or
- Be shown refusing to cooperate (which raises the question of how DGSE knows so much anyway)

**Fix:** Add one brief reference in Chapter 14 or 15 to Inès's interrogation status (still silent, but forensics from her clothing match the Mantes lab), or in Chapter 30 (Thomas's intelligence review) note that "Inès gave them nothing useful — she'd been radicalized too deeply."

---

### M5 — MOREAU: PRE-EXISTING COLLEAGUE vs. NEWLY ASSEMBLED TEAM MEMBER

**Issue:**

- In Chapters 5-9, a character named "Moreau" appears as Thomas's existing DGSE colleague in Paris headquarters — someone Thomas clearly knows and works with regularly.
- In Chapter 18, Thomas introduces his assembled team: *"Moreau. Communications and technical operations. Eleven years DGSE. I handle intercepts."* — presented as if Thomas is meeting him for the first time.

**Fix:** If Moreau is the same character (most likely), his Chapter 18 introduction should acknowledge the prior relationship: *"You know Moreau already — he's been handling signals intelligence since Paris."* If they're two different Moreaus, the Paris Moreau should be given a first name or title to differentiate him.

---

### M6 — THE CATHEDRAL SEQUENCE (CHAPTER 9) vs. THE LOUVRE ATTACKS (CHAPTER 10): TIMELINE UNCLEAR

**Issue:**

Chapter 9 ("GUNFIRE") describes Thomas leading a tactical team in a subterranean confrontation involving Hassan Medjahed, Inès Benmansour, and **four additional bombs in an underground cathedral**. This strongly implies a second bomb plot that Thomas's team intercepted.

Chapter 10 then describes the massive truck bombing wave (Louvre, Élysée, Eiffel, Bercy) executed by Yasmine and Malik — which means the attacks were NOT stopped.

**Questions raised:**
- Did the cathedral confrontation happen **before** the truck attacks? If so, Hassan and Inès were already in custody when the trucks went off — without them being involved in the truck bombs.
- Or did the cathedral confrontation happen **after** the truck attacks? If so, why were there still four active bombs in a cathedral?
- How does Yasmine's presence in Chapters 5-6 (still free, interacting with her cell) fit relative to the cathedral confrontation in Chapter 9?

**Fix:** The chapter notes suggest the cathedral sequence is a **flashback/interlude** that occurs during the metro bombing's immediate aftermath (Day 1), showing how Hassan and Inès were captured before the truck wave. This chronology needs to be made explicit at the start of Chapter 9 with a timestamp: *"Day 1. 08:30. Four hours after the metro attack."*

---

### M7 — HASSAN MEDJAHED'S CUSTODY TIMELINE

**Issue:**

- **Chapter 9:** Hassan Medjahed is knocked unconscious during the underground confrontation and presumably arrested.
- **Chapter 11:** *"Hassan Medjahed is not there. He's in custody. In a DGSE holding facility. Being interrogated. But Hassan won't talk."*
- **Chapter 35 notes:** *"Hassan Medjahed (cell ideologue, captured in Lyon) broke under DGSE interrogation and revealed Tadrart."*

If Hassan is captured on Day 1 (Ch 9/11) and "won't talk," but eventually breaks and reveals Tadrart many weeks later — this timeline is plausible but requires Hassan to maintain silence for weeks while Thomas's team eliminates four other cell members through other intelligence.

**Fix:** Add a brief reference in Chapter 30 or 33 noting that Hassan has finally begun talking under sustained interrogation — this creates dramatic urgency (he may break before they can use the information) and confirms why Tadrart's coordinates came late.

---

## 3. MINOR INCONSISTENCIES 🟡

---

### m1 — YASMINE'S AGE

**Chapter 35:** *"Yasmine Boudjellal. Twenty-two years old."*

A 22-year-old as the operational mastermind behind five simultaneous attacks killing 2,391 people — including obtaining military-grade RDX, building synchronized bombs, recruiting four wheelchair bombers, coordinating escape routes across four continents — strains credibility. The TEAM_DOSSIER doesn't list her age. 

**Fix:** Consider aging Yasmine to 28-30. This still gives her the youth and urgency of the narrative, but makes her recruitment, radicalization, planning period (multiple years, given Abdelkrim's 2021 paralysis and 2023 recruitment), and operational sophistication more believable.

---

### m2 — THOMAS'S RANK

- **Chapter 16/18:** Called "Commander Dieudegard"
- **TEAM_DOSSIER:** "Colonel, DGSE"

In French military/intelligence structure, "Colonel" and "Commander" are different ranks (Commandant is roughly equivalent to Major; Colonel is a higher rank). Standardize to one or the other throughout.

**Fix:** Use "Colonel" consistently, which matches his 20+ years of experience and authorization level. "Commander" may have been a translation of "Commandant" (Major), which would be too low a rank for someone with direct Presidential authorization.

---

### m3 — TARKOVSKY: "CONTRACTOR" vs. "LIEUTENANT"

- **Chapter 18 (Thomas's introduction):** *"Tarkovsky. Former Russian Spetsnaz. Defected in 2001. Now DGSE contractor."*
- **TEAM_DOSSIER:** "Lieutenant, DGSE Special Operations"

**Fix:** Either he's a commissioned DGSE Lieutenant (TEAM_DOSSIER) or a contractor. If he's a naturalized French citizen who defected in 2001, he may have been fully commissioned over 20+ years of service. Use "Lieutenant" throughout.

---

### m4 — ABDELKRIM'S FIRST NAME (BELKACEM vs. DIALLO)

- **README:** *"Abdelkrim Belkacem"*
- **All Chapters:** *"Abdelkrim Diallo"*

These are two different surnames. The README represents the original story bible (now superseded by the actual chapters). **"Diallo" is established in the chapters and should be canonical.**

---

### m5 — HASSAN BOUDJELLAL NEVER RESOLVED

**Chapter 13** introduces Hassan Boudjellal — Yasmine's cousin, the financer who "never left Paris." He arranges the Tadrart refuge, provides the driver, sets up servants. He's a distinct and interesting character (the mundane backstage organizer) but disappears completely after this one appearance.

**Fix:** One brief reference later in the novel — perhaps Thomas's team identifies him through the financial network, or he's mentioned in a DGSE debriefing — would close this thread. It's also unclear why Thomas's team never goes after him (he presumably remains in Paris throughout the novel, accessible to French intelligence).

---

### m6 — THE MOTORCYCLE THAT VANISHED

Thomas rides his MV Agusta motorcycle from Paris south toward Marseille (Ch 11). He arrives in Marseille later by Falcon 7X (Ch 16). The motorcycle is never mentioned again.

**Fix:** Either establish that Thomas drove to Lyon and then flew from there, or have Beaumont mention that the MV Agusta is being held at a DGSE garage in Marseille.

---

### m7 — CHAPTER 26 REDUNDANCY

Chapter 26 ("ZUG OPERATIONS") covers largely the same ground as Chapter 24 ("ZUG WEALTH"): Malik's routine in Zug, his wealth accumulation, his false sense of security. Both chapters describe him converting cryptocurrency, buying gold, maintaining a lake-view house. The actual content difference is minimal.

**Fix:** Merge Chapters 24 and 26, or make Chapter 26 more tightly focused on Thomas's surveillance team being positioned in Zug (from their perspective), rather than repeating Malik's interior monologue.

---

### m8 — DR. SYLBERSTEIN'S NAME

Chapter 15 introduces "Dr. Sylberstein" but then the dialogue has Thomas calling her "Sylberstein" while also saying *"Good work, Sylberstein"* — this is consistent. However, her first name is never given. For a character who gets an entire dedicated chapter, a first name would be appropriate.

---

### m9 — YASMINE BUYS A BURKA IN ALGIERS

**Chapter 13 (and repeated in Chapter 28):** Yasmine buys a burka from a vendor *"near the docks"* immediately upon arrival in Algiers. However, the burka is described in Chapter 13 as failing to disguise her ("underneath, everyone can tell she's wearing it"). The same scene is then re-described in Chapter 28 from a slightly different angle.

Chapter 28 appears to be a **rewrite or alternate version of Chapter 13's Algeria arrival sequence**. Both chapters cover Yasmine arriving in Algiers, buying a burka, feeling like a foreigner, going to the Museum of Martyrs, and calling Hassan. These scenes overlap significantly.

**Fix:** Consolidate. Either Chapter 13 covers the Algeria arrival (as it does now) and Chapter 28 covers a later week in Algiers, OR Chapter 28 replaces Chapter 13's Algeria content. Currently both chapters exist and describe essentially the same events from different angles.

---

## 4. TECHNICAL/FACTUAL ISSUES 🔵

---

### T1 — SUPER FRELON vs. SUPER PUMA (CRITICAL TECHNICAL ERROR)

**Chapter 33:** *"Two Super Frelon helicopters waiting. Heavy-lift birds..."*

The **Super Frelon** was retired from French Navy service in **2010**. It would not be in service in 2026. The chapter later correctly identifies the insertion helicopter as a **Super Puma** (which is in active French service). Chapter 35 confirms: *"Thomas is aboard a Super Puma helicopter."*

**Fix:** Replace all instances of "Super Frelon" in Chapter 33 with "Super Puma" or the NH90. The two helicopter types look different and perform differently, and military readers will catch this immediately.

---

### T2 — THE FORBIN (D620): WRONG SHIP TYPE

**Chapter 33:** *"The Forbin. Frégate porte-hélicoptères. Helicopter carrier."*

The **FS Forbin (D620)** is a **Horizon-class air-defence destroyer** — not a helicopter carrier. It's a powerful warship, but its helicopter capability is limited to one or two maritime patrol helicopters. It is not a "porte-hélicoptères."

French actual helicopter carriers are the **Mistral-class BPC** (Bâtiment de projection et de commandement): Mistral, Tonnerre, Dixmude. These are the ships that carry full tactical teams and multiple Super Pumas.

**Fix:** Either rename the ship to the *Tonnerre* or *Mistral* (actual French helicopter carriers), or remove the "porte-hélicoptères" descriptor and simply call the Forbin a "French naval frigate" capable of helicopter operations.

---

### T3 — HELICOPTER RANGE TO TADRART FROM WESTERN SAHARA COAST

**Chapter 33:** The Forbin positions *"off the coast of Western Sahara"* before launching helicopter insertion to Tadrart.

**Problem:** Tadrart is in **southeastern Algeria**, near Djanet — approximately **2,000 km from the Western Sahara coast**. A Super Puma has a maximum range of approximately **850 km**. This mission is physically impossible.

A more geographically accurate positioning would be off the **Libyan or Tunisian coast** in the Mediterranean, which is approximately 800-1,000 km from Tadrart — still at the edge of helicopter range, but achievable with a refueling stop or a closer naval position.

**Fix:** Change the Forbin's approach route. Instead of going through Gibraltar and down the Atlantic coast, the Forbin operates from the **central Mediterranean** (its normal patrol area for a Toulon-based frigate), positions off the Libyan coast, and the helicopter insertion follows a route Toulon → Libya coast → Tadrart. This is geographically plausible.

---

### T4 — TWO DIFFERENT GPS COORDINATES FOR TADRART HOUSE

**Chapter 33 provides two separate coordinates for Yasmine's location:**

1. From the deed: *"25.3667° North, 9.6167° East"* (= near Djanet, southeastern Algeria — **geographically accurate** for Tadrart Rouge)
2. Written on Thomas's palm: *"24.8731° North, 8.4422° East"* (= approximately 160 km northwest of the first coordinate, near Illizi)

These are two distinctly different locations. Only one can be Yasmine's house.

**Fix:** Pick one set of coordinates and use it consistently. The first (25.3667° N, 9.6167° E) is more accurate for the Tadrart Rouge UNESCO heritage area near Djanet. Delete the second pair.

---

### T5 — THE LOUVRE PYRAMID ARCHITECTURE

**Chapter 10:** *"The pyramid has a hollow center. A basement. An underground space for storage and machinery. The truck crashes through the internal structure. Glass explodes inward. Metal beams collapse. The truck falls into the hole beneath the pyramid."*

The actual Louvre pyramid (I. M. Pei, 1989) sits in the **Cour Napoléon** courtyard. Below it is the **Hall Napoléon** — but this underground space is accessed via escalators and stairs from the ground level. The pyramid itself is a glass-and-steel frame on a reinforced concrete base. A truck driving across the courtyard would not fall into the Hall Napoléon — it would hit the pyramid's frame and glass structure at ground level.

**Fix:** Adjust the physics. The truck could realistically: (a) drive into the courtyard at high speed and ram the pyramid's base, causing catastrophic glass and structural collapse outward; (b) be an IED-laden vehicle parked adjacent to the pyramid and detonated; (c) fall into the underground hall only if the courtyard surface was breached by the explosion itself. Option (b) is most realistic and requires the least rewriting.

---

### T6 — "PIG FAT + RDX" AND THE FIGHT CLUB REFERENCE

**Chapter 15:** Dr. Sylberstein identifies the explosive as *"pig fat mixed with RDX... The same method used in the book. Fight Club. Tyler Durden's soap bomb."*

**Technical issue:** In *Fight Club*, Tyler Durden extracts **nitroglycerin from human body fat** — not pig fat. He makes nitroglycerin (not an RDX mixture) by processing fat chemically. The "soap" is a cover story. This is a misreference to Fight Club's actual plot.

Additionally, "pig fat mixed with RDX" is not a standard explosive formulation. RDX is typically mixed with plasticizers and binders (waxes, polymers) to make plastic explosive (C-4, PE4). Pig fat could theoretically serve as a plasticizer, but would be unusual and unprofessional.

**Fix:** Either (a) drop the Fight Club reference and describe the explosive accurately as a homemade plastic explosive using RDX and animal fat as a binder (forensically interesting on its own terms), or (b) reference Fight Club correctly: *"the same principle Tyler Durden used — rendering down fat for its chemical properties."*

---

### T7 — MANTES-LA-JOLIE POPULATION SIZE

**Chapter 14:** *"The government orders evacuation of the entire population of Mantes-la-Jolie. Fifty thousand people."*

The actual population of Mantes-la-Jolie is approximately **45,000** (2019 census). The figure of "fifty thousand" is close enough to be plausible as a round figure in the narrative, but the evacuation of an entire French city of 45,000 people without any legal framework, court orders, or political debate would be legally and logistically extraordinary even under martial law. This is a deliberate narrative choice (showing France's authoritarian response) — but worth flagging as something that will attract attention from readers who know the city.

---

## 5. STRUCTURAL ISSUES (README vs. CHAPTERS)

---

### S1 — THE STORY BIBLE IS COMPLETELY OUTDATED

The `README.md` describes a **fundamentally different novel** from the one written:

| Element | README (Original Plan) | Actual Chapters |
|---------|----------------------|----------------|
| Setting | Paris, 2018 | Paris + Europe + Algeria, ~2026 |
| Cell leader | Yasmin **Aliyev** (Chechen-Russian) | Yasmine **Boudjellal** (French-Algerian) |
| Cell members | Marko Sladović, Hassan Mehran, Inès van der Meer | Malik Benhadj, Hassan Medjahed, Amina Zeroual, etc. |
| Abdelkrim's age | 19 | 28-34 |
| Abdelkrim's surname | Belkacem | Diallo |
| Attack scope | Metro bombing only | Metro + Louvre + Élysée + Eiffel + Bercy |
| Deaths | "43+" | 2,391 |
| Chapter count | 20 | 35+ |
| Geographic scope | Paris only | 7 countries |
| Ending | Yasmine dies by own hand in Paris tunnels | Yasmine shot by Thomas in Tadrart desert |
| Thomas's motivation | Childhood trauma (1995 RER bombing) | Jérôme (friend in Metro 14) |

**Fix:** The README must be completely rewritten to reflect the actual story. This is not a contradiction to fix in the manuscript — the manuscript is the canon. But the README as a project document misleads anyone reading the repository.

---

### S2 — YEAR OF SETTING UNCLEAR

The README says 2018. The chapters reference:
- Abdelkrim's crash in **2021**
- His recruitment in **early 2023**
- The attack presumably in **2023-2024**

The novel cannot be set in 2018 if the crash that causes Abdelkrim's paralysis is in 2021. A consistent timeline should be established.

**Suggested timeline (working backward from events):**
- **2021:** Abdelkrim's motorcycle crash, paralysis
- **Early 2023:** Yasmine begins recruitment, meets Abdelkrim
- **2024:** Cell operational, bombing planned
- **2025:** The Metro 14 attack occurs (novel's opening)
- **2025-2026:** The hunt across Europe and Algeria (rest of novel)

---

## 6. MASTER TIMELINE OF EVENTS

Based on chapter text (not README), reconstructed in chronological order:

### PRE-NOVEL (Backstory)

| Date | Event | Source |
|------|-------|--------|
| **2021 (March)** | Abdelkrim Diallo (28) flees police traffic stop, crashes motorcycle, suffers L4-L5 spinal cord transection, permanent paraplegia | Ch 11.5 |
| **2021-2022** | Abdelkrim in hospital, rehabilitation, deep depression; begins attending political meetings about Algerian colonial history | Ch 11.5 |
| **Early 2023** | Yasmine Boudjellal appears at a political meeting in Mantes-la-Jolie; recruits Abdelkrim | Ch 11.5 |
| **2023** | Cell forms: Yasmine (leader), Malik Benhadj (finance), Hassan Medjahed (ideologue), Inès Benmansour (logistics), Abdelkrim (operations/wheelchair) | Ch 5, 6 |
| **2023** | Hassan Medjahed trains Abdelkrim in explosives construction | Ch 11.5 |
| **2023-2024** | Mantes-la-Jolie warehouse rented; TNT laboratory established; explosives manufactured using pig fat + RDX formula | Ch 12, 15 |
| **2023-2024** | Malik Benhadj begins pre-positioning Tadrart property; sets up financial networks | Ch 13, 33 |
| **Night before attack** | Abdelkrim deliberately sabotages his device: disconnects electrical lead, drains battery | Ch 11.5 |

### ACT I: THE ATTACK (Day 0)

| Time | Event | Source |
|------|-------|--------|
| **~5:47 AM** | Thomas Dieudegard wakes in Paris apartment (Rue des Rosiers) | Ch 1 |
| **~6:00 AM** | Cell members board Métro 14 with three wheelchair bombs | Ch 3, 6 |
| **~6:10 AM** | First two bombs detonate in Métro 14; Abdelkrim's third bomb fails | Ch 3, 6 |
| **~6:20 AM** | Ambulance bomb at Saint-Lazare Cour de Rome; emergency responders killed | Ch 2, README |
| **~6:45 AM** | Thomas arrives at Saint-Lazare scene | Ch 2 |
| **08:30 AM** | Thomas and DGSE tactical team pursue Hassan and Inès in underground location; gunfight; Hassan arrested; Inès shot and captured | Ch 9 |
| **Morning** | Abdelkrim arrested with failed device; forensic recovery begins | Ch 6, 12 |
| **Day 0 afternoon** | Yasmine and remaining cell members escape; four-bomb cathedral plot intercepted | Ch 9 |

### ACT II: THE SECOND WAVE (Day 1-2)

| Time | Event | Source |
|------|-------|--------|
| **Day 1** | Yasmine and Malik execute second wave: Louvre pyramid (Iveco truck, 4MT TNT, 478 dead), Élysée Palace (341 dead), Eiffel Tower (289 dead), Bercy barge (956 dead) | Ch 10 |
| **Day 1** | Total dead: 2,391. France shocked | Ch 10 |
| **Day 1 night** | Dr. Sylberstein begins forensic analysis of bomb fragments at DGSE lab (Quai d'Orsay) | Ch 15 |
| **Day 2** | France declares martial law; President in bunker | Ch 11 |
| **Day 2** | Suburbs celebrate (Mantes-la-Jolie, Clichy, Saint-Denis) | Ch 11 |
| **Day 2, ~midnight** | Cell scatters: safe house meeting; escape plan coordinated | Ch 11 |
| **Night Day 2/3** | Cell disperses: Yasmine → Lyon; Malik → northeast/Switzerland; Hassan Jr. → Italy; Amina → Nantes/Brittany; others scatter | Ch 11, 17 |

### ACT III: THE INVESTIGATION (Days 3-10)

| Time | Event | Source |
|------|-------|--------|
| **Day 3** | Thomas discovers Mantes laboratory; cell identified | Ch 12 |
| **Day 3** | Mantes riots erupt; military arrives; mass detention begins | Ch 12 |
| **Day 3** | ~2,000 people detained in shipping containers (Mantes men's population) | Ch 12 |
| **Day 3** | Thomas sees Abdelkrim Diallo in container detention | Ch 12 |
| **Day 4** | Dr. Sylberstein completes forensic analysis: pig fat + RDX from Mantes lab | Ch 15 |
| **Day 4** | Farid Messaoud captured at checkpoint near Toulouse | Ch 17 |
| **Days 5-6** | Louvre artwork evacuation; French cultural heritage secured | Ch 14 |
| **Days 5-7** | Mantes evacuation ordered; 50,000 residents relocated | Ch 14 |
| **Days 5-7** | Thomas travels south toward Marseille (MV Agusta/Falcon 7X — see C6) | Ch 11, 16 |

### ACT IV: MARSEILLE AND CROSSING (Days 7-14)

| Time | Event | Source |
|------|-------|--------|
| **~Day 10** | Yasmine boards Rachid Bouazza's fishing boat in Marseille; pays 3,000€ | Ch 20 |
| **~Day 12** | Yasmine arrives Algiers harbor at dawn | Ch 13, 28 |
| **Day 12** | Yasmine buys burka; takes taxi to safe apartment overlooking sea | Ch 13, 28 |
| **Day 12** | Thomas arrives Marseille; meets Beaumont; traces Yasmine's boat crossing | Ch 16 |
| **Day 12-13** | Thomas calls Director; requests 6-person elimination team | Ch 16 |
| **Day 13** | Malik crosses into Switzerland at Basel; drives to Zug | Ch 17 |
| **Day 14** | Hassan Jr. reaches Palermo via train (Paris→Lyon→Turin→Sicily) | Ch 17 |
| **~Day 14** | Amina reaches Barcelona (bus); boards ferry to Tunisia | Ch 17 |
| **~Day 14** | Leila Hamadi reaches Portugal via Spain | Ch 17 |
| **Day 14, evening** | Thomas briefs six-person elimination team at Marseille safe house | Ch 18 |

### ACT V: THE HUNT (Weeks 2-8)

| Time | Event | Source |
|------|-------|--------|
| **Week 2-3** | De Vergennes traces Malik's blockchain transactions to Zug (specific address within days) | Ch 19 |
| **Week 2** | Yasmine waits in Algiers; feels alienated; no cell members arrive | Ch 13 |
| **Week 3-4** | Beaumont and Tarkovsky conduct surveillance in Palermo | Ch 21 |
| **Week 4** | Tarkovsky eliminates Hassan Jr. at Via Alloro apartment (Palermo) | Ch 22 |
| **Week 4** | Moreau intercepts Amina's call from Tunis; Richelieu and Leclerc sent | Ch 23 |
| **Week 4** | Amina escapes Tunis apartment; bus to Bizerte, then ferry to Portugal | Ch 23 |
| **Week 5** | Amina establishes cover in Lisbon (hotel cleaner, "Fatima"); eliminated by Leclerc and Moreau | Ch 25 |
| **Week 5-6** | Yasmine gives up on Algiers; calls Hassan Boudjellal (cousin); arranges Tadrart departure | Ch 13 |
| **Week 6** | Yasmine boards Touareg Land Cruiser; three-day drive south | Ch 29 |
| **~Week 6** | Yasmine arrives Tadrart (Hassan's stone house, servants waiting) | Ch 29 |
| **Week 6** | Malik accumulating wealth in Zug (gold, diamonds, bearer bonds) | Ch 24, 26 |
| **Week 8** | Surveillance team confirms Malik's address (Seestrasse 47) and routine | Ch 30, 31 |

### ACT VI: ZUG AND TADRART (Weeks 8-12)

| Time | Event | Source |
|------|-------|--------|
| **Friday, Week 8** | Thomas's team executes Zug operation during Malik's party | Ch 31, 32, 34 |
| **Friday night** | Malik's safe opened; gold, diamonds, bonds, watches, cash, **documents about Tadrart** removed | Ch 32, 34 |
| **Friday night** | Malik drowned in lake; team extracts via Switzerland→France border (Saint-Gingolph) | Ch 32, 34 |
| **~02:45** | Team crosses border at Saint-Gingolph; arrives Evian safe house ~03:15 | Ch 32 |
| **Saturday, ~06:00** | Thomas reads deed; Tadrart coordinates identified | Ch 33 |
| **Saturday, ~08:00** | Team drives to Lyon airbase | Ch 33 |
| **Saturday, ~10:45** | Falcon 900 flies Lyon to Toulon (1 hour) | Ch 33 |
| **Saturday, ~11:20** | Team boards Forbin at Toulon | Ch 33 |
| **Days following** | Forbin sails Mediterranean toward North Africa (3-5 days at sea) | Ch 33 |
| **Day ~4-5 at sea** | Touareg surveillance confirms Yasmine still at Tadrart stone house | Ch 35 |
| **Thursday/Friday night** | Super Puma inserts Thomas's team from ship; Touareg Land Cruisers drive 3 hours to Tadrart | Ch 35 |
| **Dawn** | Two servants eliminated; Yasmine confronted by Thomas; final shot | Ch 35 |
| **Aftermath** | Team extracts; Tadrart remains silent; hunt ends | Ch 35 |

---

## 7. CHARACTER APPEARANCES PER CHAPTER

### Thomas Dieudegard (protagonist)
**Chapters:** 1, 2, 3, 5, 6, 8, 9, 10, 11, 12, 15 (phone), 16, 17 (mentioned), 18, 19, 21 (direction), 22 (confirmation), 23 (direction), 24 (arrives last), 25 (confirmation), 27, 30, 31, 32, 33, 34, 35

### Yasmine Boudjellal (antagonist/cell leader)
**Chapters:** 1 (indirectly), 3, 5, 6, 9, 10, 11, 13, 16 (trail), 17, 20, 23 (network), 25 (network), 27, 28, 29, 30, 33 (target), 34 (mentioned), 35

### Malik Benhadj (financier)
**Chapters:** 6, 11, 17, 19 (tracked), 24, 26, 30, 31, 32, 34

### Hassan Medjahed (ideologue, arrested Day 0)
**Chapters:** 6, 9, 11, 35 (notes)

### Inès Benmansour (logistics, arrested Day 0)
**Chapters:** 6, 9, 11

### Abdelkrim Diallo (wheelchair bomber, arrested Day 0)
**Chapters:** 6, 11.5, 12

### Hassan Jr. (operations, eliminated Palermo)
**Chapters:** 11, 17, 18, 21, 22

### Amina Zeroual (communications, eliminated Lisbon)
**Chapters:** 11, 17, 18, 23, 25

### Farid Messaoud (logistics, arrested near Toulouse)
**Chapters:** 17 only

### Leila Hamadi (logistics, fate unclear)
**Chapters:** 17, 18

### Hassan Boudjellal (cousin, financer)
**Chapters:** 13 only

### Beaumont (DGSE surveillance)
**Chapters:** 16, 18, 19, 21, 22 (offscreen), 23, 27, 30, 31, 32, 34

### Tarkovsky (DGSE elimination)
**Chapters:** 18, 21, 22, 30, 31, 32, 34, 35

### De Vergennes (DGSE financial)
**Chapters:** 18, 19, 24, 30, 31, 32, 33, 34

### Leclerc (DGSE medic)
**Chapters:** 18, 23, 25, 30, 32, 34, 35

### Richelieu (DGSE weapons)
**Chapters:** 18, 23

### Moreau (DGSE communications)
**Chapters:** 5-9 (possibly different Moreau), 18, 19, 23, 25, 30, 31, 32

### Dr. Sylberstein (DGSE forensics)
**Chapters:** 15 only

### Rachid Bouazza (smuggler)
**Chapters:** 16, 20

### Captain Gerard (Forbin)
**Chapters:** 33 only

---

## 8. SUMMARY OF CORRECTIONS REQUIRED

### Priority 1 — Fix Before Any Other Work (Breaks Story)

| # | Issue | Fix |
|---|-------|-----|
| C1 | Jérôme is son/friend | Fix Ch 8: "son" → "holiday friend" |
| C2 | Ch 7 = duplicate of Ch 10 | Write new Chapter 7 content |
| C3 | 2,391 vs. 3,000 dead | Standardize to 2,391 everywhere |
| C4 | Three conflicting Tadrart discovery mechanisms | Consolidate: hawala hint → deed → confirmation |
| C5 | Two different people own Tadrart house | Reconcile Boudjellal/Malik ownership |
| C6 | MV Agusta vs. Falcon 7X Marseille arrival | Choose one; fix Ch 11 or Ch 16 |
| C7 | Hassan Jr.'s age: 21 vs. 32 | Fix Ch 11: "twenty-one" → "thirty-two" |
| C8 | Malik's age: 41 vs. 55 | Fix Ch 6 or Ch 34 notes |

### Priority 2 — Fix Before Publication (Significant Gaps)

| # | Issue | Fix |
|---|-------|-----|
| M1 | Safe contents differ Ch 24/32 | Standardize all numbers |
| M2 | Amina killed in Portugal (not Tunisia) vs. target assignment | Clarify Leila Hamadi's fate |
| M3 | Farid/Leila never established as cell members | Mention them earlier (Ch 5-6) |
| M4 | Inès disappears after Ch 11 | Add one reference to her interrogation |
| M5 | Moreau appears twice as different people | Clarify it's the same Moreau |
| M6 | Cathedral sequence timing unclear | Add timestamp to Ch 9 |
| M7 | Hassan Medjahed's silence duration | Add note in Ch 30/33 about him breaking |

### Priority 3 — Polish Pass

| # | Issue | Fix |
|---|-------|-----|
| m1 | Yasmine age 22 (implausible) | Age to 28-30 |
| m2 | Thomas's rank: Commander vs. Colonel | Standardize to Colonel |
| m3 | Tarkovsky: Contractor vs. Lieutenant | Use Lieutenant |
| m4 | Chapters 24/26 redundancy | Merge or differentiate |
| m5 | Hassan Boudjellal unresolved | Add one brief resolution |
| m6 | MV Agusta vanishes | Add one line explaining it |
| m7 | Two almost-identical Algeria arrival scenes (Ch 13/28) | Consolidate or differentiate clearly |

### Priority 4 — Technical/Factual Corrections

| # | Issue | Fix |
|---|-------|-----|
| T1 | Super Frelon retired in 2010 | Replace with Super Puma everywhere |
| T2 | Forbin is wrong ship type | Use Mistral or Tonnerre |
| T3 | Helicopter cannot reach Tadrart from Western Sahara coast | Reposition Forbin to Mediterranean/Libyan coast |
| T4 | Two different GPS coordinates for Tadrart | Pick one set; delete the other |
| T5 | Louvre pyramid physics | Adjust truck bomb to surface explosion model |
| T6 | Fight Club misreference (nitroglycerin, not pig fat) | Correct the reference or remove it |
| T7 | README: completely wrong story bible | Rewrite README to match actual chapters |

---

## 9. STRENGTHS (NOT TO CHANGE)

The following elements are well-executed and internally consistent. Do not alter them during the editing pass:

- **Abdelkrim's backstory** (Ch 11.5): The paralysis-to-radicalization pipeline is psychologically nuanced, emotionally authentic, and the sabotage decision is one of the novel's most morally complex moments.
- **Yasmine's alienation in Algiers** (Ch 13/28): The theme of being "too French for Algeria, too bloody for France" is powerful and original.
- **Dr. Sylberstein's forensic chapter** (Ch 15): Technical authenticity, professional voice, the forensic detail of pig fat as a binder is interesting (even if the Fight Club reference needs fixing).
- **The Palermo operation** (Ch 21-22): Clean, professional, tension well-executed.
- **Thomas's voice throughout**: Consistently austere, effective, Lee Child-adjacent prose.
- **The Mediterranean as moral geography**: The sea as a boundary between hunter and hunted, between Europe and Africa, between law and its absence — this motif works beautifully.
- **Mass detention at Mantes** (Ch 12, 14): The government's authoritarian overreach is rendered without authorial editorializing — the horror speaks for itself.
- **Yasmine's final confrontation** (Ch 35): Her calm acceptance, her seeing Thomas's grief without knowing his name — this is a quietly devastating ending.
- **The TEAM_DOSSIER**: Well-constructed, internally consistent, useful reference document.
- **The hawala tracking method** (Ch 30): Realistic intelligence tradecraft.

---

*End of COHERENCE_REPORT.md — Maxime Grenu, February 2026*
