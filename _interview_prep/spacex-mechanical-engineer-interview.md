---
layout: interview
title: "SpaceX FTS Interview — Brad Murphy Call Prep"
summary: "Mechanical Engineer, Flight Termination System (Starship) | 30-min Screening Call"
date: 2026-04-27
tags: [spacex, fts, mechanical-engineer, interview-prep]
---

## Mechanical Engineer, Flight Termination System (Starship) | 30-min call

> **Brad Murphy:** 4.0 GPA, NASA Space Grant, ATI electromechanical background.
> He respects rigor, data, and hardware ownership. Be specific. Quantify everything. Never hand-wave.

---

## YOUR PROFILE AT A GLANCE

**Zinoun Obaid** | Senior Mechanical Engineer — Dynamo Aviation (2022–Present)
- 8+ years aerospace design, manufacturing, and DO-160G qualification
- BSME, University of Pittsburgh, Cum Laude 2016
- Tools: SolidWorks, Composer, ERP/EPDM, Python automation, UIPath
- Certified Professional SolidWorks | EIT Ohio

**Key Numbers to Know Cold:**
| Story | The Number |
|---|---|
| EMI bracket redesign | 77.5% cost reduction · $62K saved · 200 units |
| Fuse/holder retrofit | 92.7% savings · $1.65M avoided · 1,500 units |
| ERP re-architecture | 600 engineering hours saved annually |
| Element — workflow automation | 87% efficiency gain · 90% reduction in sample handling time |

---

---

# PART 1 — STAR+R STORY BANK (Read Aloud — 90–120 sec each)

> **STAR+R Format:** Situation → Task → Action → Result → Relevance (bridge to FTS)

---

## Q1: "Describe a time you found a root cause that others had missed."
*(Most likely opening question — LEAD with this)*

**S — Situation:**
At Dynamo, we had a recurring in-flight fire in a Hot Jug galley assembly. The team's initial assumption was a manufacturing defect — they were focused on the component itself, looking for a bad part.

**T — Task:**
I was skeptical because the failure was repeating on units that had passed inspection. My job was to find the real cause before we committed to a redesign that might not fix anything.

**A — Action:**
I went back to the install environment and looked at the filter's mounting geometry under operating vibration conditions. I found it: the EMI filter was constrained in only two of three planes of translation. In the third axis, it was completely free. Under high-frequency airborne vibration, it was physically translating and shorting against the chassis wall. No defect — systematic design gap.

I designed a modular sheet-metal bracket that arrested all three planes of translation, anchored to the rear compartment wall, and routed to avoid disturbing internal tubing or harnesses — so repair required no full disassembly.

**R — Result:**
Deployed across 200 units. Manufacturing cost dropped 77.5%. $62K net savings. Eliminated the recurring in-flight failure mode at its root.

**R — Relevance:**
> "In a flight termination system, a misdiagnosed root cause isn't a cost problem — it's a mission safety problem. That instinct to go back to the physics before accepting the first hypothesis is exactly what I'd bring to FTS."

---

## Q2: "Walk me through a time you owned hardware from concept to production."

**S — Situation:**
At Dynamo, we had a curved sheet-metal component that required compound geometry — standard brake-press bending couldn't produce it. The plan was to outsource to a vendor: longer lead time, more cost, loss of process control.

**T — Task:**
I pushed back. My goal was to solve it in-house and own the entire chain.

**A — Action:**
I designed and manufactured a custom forming mold from scratch. I took it from concept sketch → mold design → fabrication → first article fit-check → production release. Every step was mine.

**R — Result:**
Eliminated vendor dependency entirely, cut lead time, and the geometry was achieved in-house with full traceability.

**R — Relevance:**
> "The FTS role calls for owning hardware from initial concept through live-fire qualification. I've done that — not just the design, but the fixturing, the first article, the production release. That's the mode I operate in."

---

## Q3: "Tell me about a project that required both engineering rigor and production scale."

**S — Situation:**
At Dynamo, I identified a latent failure risk in the fuse and fuse-holder design across 1,500 water-heater units already in active service on commercial aircraft. If the failure materialized in the field, we were looking at $1.65M in rework costs.

**T — Task:**
Design and deploy a retrofit across all 1,500 units that was repeatable, executable on the shop floor, and fully closed the failure mode.

**A — Action:**
I engineered the fix, wrote the manufacturing instructions, coordinated with the shop floor team, and verified the solution against the original failure mode. Designed for consistent assembly — no room for technician error.

**R — Result:**
$1.65M in rework costs avoided. 92.7% savings. Zero field failures post-retrofit.

**R — Relevance:**
> "SpaceX needs to build Starship at automotive rate — more than one full stacked vehicle per month. Executing a safety-critical fix across 1,500 units without a field failure is exactly the production-scale discipline that rate requires."

---

## Q4: "Give me an example of how you've questioned an existing process and automated it."

**S — Situation:**
At Dynamo, engineering data and the shop floor were completely disconnected. Engineers spent hours every week manually hunting PDM data, updating ECR documents, and relaying priorities by hand. Pure toil — zero engineering value.

**T — Task:**
Eliminate the handoff. Build the bridge between data and the people who need it.

**A — Action:**
Built a Python-based engine that scrapes PDM and ECR data to auto-generate manufacturing instructions and SQL-backed priority dashboards. At Element, I'd done the same thing differently — UIPath automation in production planning (87% efficiency gain, 90% reduction in sample handling). Same instinct, different tool.

**R — Result:**
Element: 87% efficiency gain. Dynamo: pipeline in active deployment. Both cases: engineers stop doing data entry and start doing engineering.

**R — Relevance:**
> "Your job description calls for someone who will continually question requirements and automate delivery. That's not a side project for me — manual, repetitive work is a design failure. I fix those."

---

## Q5: "What's your experience with environmental qualification testing?"

**S — Situation:**
At Dynamo, I executed DO-160G EMI/EMC and environmental qualification testing on aerospace galley components for major airline OEMs. I also authored FAA substantiation reports — QbS, QbA, FTP/FTR — tied to product airworthiness.

**T — Task:**
Identify compliance gaps and ensure hardware survived the environmental extremes of the certified flight envelope.

**A — Action:**
Applied DO-160G test profiles — vibration, shock, thermal cycling, humidity, EMC. My approach: don't try to prove the part survives normal conditions. Design the test to find the failure mode before the aircraft does.

**R — Result:**
Identified compliance gaps pre-certification, preventing downstream airworthiness issues and customer rejections. Hardware certified to customer and regulatory acceptance.

**R — Relevance:**
> "FTS qualification adds live-fire to that list. But the mindset is identical: define the worst-case environment, attack the design with it, and qualify only what survives. I know that discipline — I've executed it under FAA-level scrutiny."

---

## Q6: "Tell me about a time you led or developed a technical team."

**S — Situation:**
At Dynamo, junior engineers were producing designs with systematic GD&T errors — improper tolerance stack-ups, features correct on paper but not manufacturable, callouts ambiguous on the shop floor. Recurring design review failures.

**T — Task:**
Fix the root cause — the engineers' decision-making at the drawing board — not just redline individual drawings.

**A — Action:**
I developed and delivered a structured mentorship program on advanced GD&T and DFM principles. Targeted the specific failure modes I was seeing. Showed engineers how to evaluate their own work against shop floor realities before submitting for review.

**R — Result:**
Measurable reduction in design review iterations and correction cycles. Junior engineers began catching their own errors before they reached my desk.

**R — Relevance:**
> "At SpaceX's velocity, the ability to scale technical judgment across a team is as critical as individual skill. When one engineer learns a better design instinct, it multiplies. I take that seriously."

---

## Q7: "How do you think about reliability vs. redundancy trade-offs?" *(FTS-Specific)*

> *This is not a story — it's a framework answer. Keep it under 60 seconds.*

**Your Answer:**
"FTS is a last-resort system — it exists for the absolute worst-case. That means simplicity and proven reliability beat cleverness every time. My approach: start with the simplest solution that meets the failure mode, qualify it rigorously against the worst-case flight environment, and add redundancy only where failure modes compound or share a common cause.

My DO-160G work taught me that environmental extremes expose weak links in complex systems. Every added component is another potential failure mode. In safety-critical hardware, the smartest design is often the one with the fewest parts."

---

## Q8: "How would you approach designing a safety-critical component for a rocket?"

**Your Answer:**
"I start with constraints, not geometry. What's the mass budget, the vibration envelope, the thermal range, the shock profile? Then I run first-principles analysis on the most likely failure modes before I touch CAD.

Once I have a candidate design, I use FEA to validate stress concentrations — especially at interfaces and brackets, which is where I've seen failures initiate in real hardware. Then I define a qualification plan that tests to the extremes of the flight environment, not just nominal.

The EMI bracket I designed at Dynamo is a good example — I had to account for three-axis vibration translation, interface clearances, and repairability without disturbing existing harnesses. All of that before I committed to a geometry."

---

---

# PART 2 — GAP ANSWERS (Be Honest — Don't Shrink)

---

## Gap 1: No Direct Explosives or High-Voltage Device Experience

**Brad may ask:** *"Have you worked with explosive ordnance or high-voltage initiator systems?"*

> "I haven't worked directly with explosive ordnance — I want to be upfront about that. What I bring is the safety-critical design discipline that the domain demands. I've worked in FAA-certified environments where a failure mode grounds aircraft, not just costs money.
>
> My EMI filter work required understanding vibration-induced electrical failure in a live aircraft system — that's directly adjacent to the EMI immunity requirements for electronic safe-and-arm devices.
>
> I treat new hardware domains as first-principles learning problems. I'd ramp on ATF handling protocols, ordnance-specific design standards, and safe/arm logic the same way I approached DO-160G qualification — systematically, with urgency."

---

## Gap 2: No LS-DYNA / BlastX Simulation Experience

**Brad may ask:** *"Are you familiar with LS-DYNA or hydrocodes?"*

> "I haven't used LS-DYNA or BlastX specifically — those are specialized for explosive dynamics and blast wave propagation. My FEA work has been in SolidWorks Simulation for structural mechanical components.
>
> I understand what those tools are solving: high-strain-rate material behavior and pressure wave propagation through structures — different physics regime than static structural, but the finite element methodology transfers. I'd get hands-on with them from day one."

---

## Gap 3: No Direct FAA / Range Safety Regulatory Interface

**Brad may ask:** *"Have you worked directly with FAA or range safety regulators?"*

> "Not at the direct regulatory interface level. I've been a step downstream — executing to the DO-160G standard and producing the FAA substantiation documentation (QbS, QbA, FTP/FTR) for airworthiness certification.
>
> I understand the framework: FAA 14 CFR Part 450 governs commercial launch safety, AFSPCMAN 91-710 drives FTS design at federal ranges. I know the intent. I'd expect to shadow and then lead regulatory interactions as I build that specific context on the job."

---

---

# PART 3 — FTS TECHNICAL REFERENCE (Know Before the Call)

## FTS Architecture — 2-Minute Verbal Summary
Starship FTS is triple-redundant with independent channels on a 2-of-3 voting architecture. It sits on **both** the booster and the ship. Operates completely independent of main vehicle systems — separate power, processors, and command paths. The electronic safe-and-arm device physically enables or disables the destruct charges. Commands originate from ground-based range safety. System defaults to safe on any ambiguous state.

## DO-160G Key Sections
| Section | Test Type | FTS Relevance |
|---|---|---|
| **§4** | Temperature/altitude cycling | -55°C to +85°C, vacuum |
| **§7** | Shock testing | Launch abort, stage separation |
| **§8** | Vibration (random + sine sweep) | Launch profile, resonance ID |
| **§20** | EMC/EMI | Safe/arm device immunity |

## Key Standards — Drop These by Name
| Standard | What It Governs |
|---|---|
| **FAA 14 CFR Part 450** | Performance-based commercial launch safety |
| **AFSPCMAN 91-710** | USSF range safety — drives FTS design requirements |
| **MIL-HDBK-338B** | Reliability prediction; MTBF target >10,000 hrs |
| **ATF Explosives Clearance** | Required for handling high explosives |

## FTS Component Vocabulary
| Component | Function |
|---|---|
| **System Controller** | Command initiation, redundant processors |
| **Electronic Safe/Arm Device (ESAD)** | Enables/disables destruct charges, independent power |
| **Destruct Charge** | Vehicle severance — high-yield, reliable detonation |
| **Integrated Detonator** | Trigger mechanism — shock-insensitive, temperature-stable |

## Reliability Standards to Know
- **Reliability goal:** 0.999 at 95% confidence
- **MTBF:** >10,000 hours
- **Acceptance testing:** 100% lot testing mandatory
- **Zero in-flight FTS component failures** is the stated target

---

---

# PART 4 — CALL STRUCTURE

## 30-Minute Timing Guide
| Minute | What Happens | Your Move |
|---|---|---|
| 0–3 | Brad sets context | Listen — match his energy, calibrate his style |
| 3–8 | "Walk me through your background" | Lead with the EMI story. 2 min max on background. |
| 8–22 | Technical / behavioral questions | Deploy Stories Q1–Q4. Be crisp. No rambling. |
| 22–27 | Gap questions or curveballs | Use Gap Answers above. Be honest. Don't shrink. |
| 27–30 | Your questions | Pick 1–2 from below |

## Your Questions for Brad — Culture & Fit (Pick 3–4)

> **Your mindset:** You're not chasing a logo. You're buying into a culture. These questions let Brad show you who he is as a manager. Listen for specifics — not corporate answers.

### About the Work
1. *"What does the first 90 days look like for someone joining this team — mostly design, or are you already in active qual testing cycles?"*
2. *"What are the team's primary deliverables right now, and what timeline pressure are you under? Do engineers get time to refine and iterate, or is it always pushing to the next deadline?"*
3. *"Who are the primary stakeholders the FTS team answers to — is it range safety, the program office, or both? How does priority get set when they conflict?"*

### About Brad's Leadership (This Is What You Really Want to Know)
4. *"How do you structure the work for your engineers — is it more ticket-driven, or do you frame larger problems and give people the autonomy to own the solution path?"*
5. *"What does growth look like for an engineer on your team? Is there a defined technical track, or does it emerge based on what you work on?"*
6. *"How do you handle it when an engineer disagrees with you on a technical approach? I'm looking for a team where data wins over hierarchy."*
7. *"What's the turnover been like on the team? What keeps people here, and what's caused people to leave?"*

### About the Environment
8. *"How does the FTS team interface with avionics and the stage teams day-to-day — tight daily loop or more checkpoint-driven?"*
9. *"What's the biggest technical challenge the team is working through right now?"*
10. *"Is there anything about this team's culture that you've intentionally built or protected?"*

---

---

# PART 5 — CONDENSED FTS ENGINEERING REFERENCE

## Safety-Critical Design Principles
| Principle | Implementation |
|---|---|
| **Fail-Safe Design** | System defaults to destructive action on any fault |
| **Independent Channels** | No shared single points of failure |
| **Watchdog Timers** | Continuously monitor system health |
| **Self-Testing** | Built-in diagnostics for all subsystems |
| **Zero Anomalies Goal** | 0 in-flight FTS component failures target |

## Regulatory Compliance Overview
| Standard | Authority | Key Scope |
|---|---|---|
| **FAA 14 CFR Part 450** | FAA | Modernized performance-based launch/reentry safety |
| **AFSPCMAN 91-710** | USSF | Comprehensive FTS design, test, and analysis |
| **NASA SMA-SAFE-NSTC-0096** | NASA | Human-rated mission safety procedures |
| **ITAR** | U.S. Dept of State | Export control — space technology |
| **ATF** | Federal | Explosives handling clearance |

## Simulation Tools (Preferred Qualifications)
| Tool | Application |
|---|---|
| **LS-DYNA** | Explosive dynamics simulation |
| **ANSYS** | Structural stress/strain analysis |
| **BlastX** | Blast wave propagation |
| **CHEETA** | Chemical kinetics / explosive reaction modeling |

## Test Instrumentation (Know These)
Pressure transducers, thermocouples, RTDs (resistance temperature detectors), relays, solenoid valves — used across all FTS environmental and functional test setups.

---

---

# PART 6 — ANTI-FREEZE CHEAT SHEET

> **Your pattern:** You either freeze and go blank, or you over-talk to fill silence.
> Both come from the same place — anxiety about not being "enough."
> These tools break both patterns.

---

## When You Freeze (Mind Goes Blank)

**Say this out loud — buy yourself 10 seconds:**
> *"That's a great question — let me think about the best example for a second."*

Then pick ONE of these anchors and build from it:

| Anchor Word | The Story It Triggers |
|---|---|
| **"Fire"** | EMI filter → in-flight fire → root cause → 200 units |
| **"Scale"** | Fuse retrofit → 1,500 units → $1.65M saved |
| **"Mold"** | Custom forming mold → concept to production |
| **"Automate"** | Python pipeline → manual work is a design failure |
| **"Qualify"** | DO-160G → vibration, shock, thermal, EMC |
| **"Teach"** | GD&T mentorship → review iterations dropped |

You only need ONE story per question. If you can't think of the perfect one, pick the closest anchor and start talking. You can always redirect mid-answer.

---

## When You're Over-Talking (Can't Find the Exit)

**Use this landing phrase to force yourself to stop:**
> *"...and the result was [NUMBER]. That's the short version — happy to go deeper on any part of that."*

This does three things:
1. Forces you to land on a quantified result (always strong)
2. Signals to Brad that you're concise and self-aware
3. Gives him the option to drill in (which means he's engaged)

**Rule of thumb:** If you've been talking for more than 90 seconds without Brad saying anything, you're over-talking. Land the plane.

---

## The Real Mindset for This Call

**You are not begging for a job. You are evaluating whether this team deserves your best years.**

You're a senior mechanical engineer with 8+ years, DO-160G certification experience, root cause analysis skills that saved $80K on a single fix, and production-scale execution across 1,500 units. You've worked with Blue Origin engineers. You've automated entire workflows. You mentor junior engineers.

Brad needs an engineer who can own hardware from concept through live-fire. That's you.

The question is not "am I good enough for SpaceX." The question is: **"Is Brad's team the right environment for me to do my best work?"**

Listen to how Brad answers your questions:
- Does he give specifics, or corporate non-answers?
- Does he talk about his people as individuals, or as headcount?
- Does he mention growth paths, or just deliverables?
- Does he get defensive about turnover, or honest about challenges?

If his answers feel vague or guarded, that tells you something real about the culture.

---

## Pre-Call Ritual (5 min before the call)

1. Read Story Q1 (EMI filter) out loud once — this primes your brain for detail
2. Look at the "Key Numbers" table — burn 77.5%, $62K, 1,500, $1.65M, 87% into your short-term memory
3. Pick your top 3 questions for Brad and write them on a sticky note in front of you
4. Take 3 deep breaths
5. Remind yourself: *"I'm evaluating him too."*

---

*SpaceX FTS — Brad Murphy Call Prep | Hawthorne, CA | Zinoun Obaid*