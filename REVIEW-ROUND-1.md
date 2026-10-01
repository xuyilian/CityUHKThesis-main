# First-round review: Prof. Pakpong Chirarattananon

Annotations from the marked-up PDF, transcribed by location. The PDF was a
build predating the Chapter 5 results and the citation work, so some items
were already resolved when the review arrived.

> **ALL 63 ANNOTATIONS ARE CLOSED as of 2026-10-01.** The OPEN/DECIDE labels
> in the tables below are the state *at the time of transcription* and are
> kept as a record of what the review asked for. See "How each was resolved"
> at the end for what was actually done. Nothing in this file is outstanding.

Status key (as transcribed): **DONE** fixed · **OPEN** outstanding ·
**DECIDE** needs a judgement call

---

## Chapter 1 — Introduction

| Where | Annotation | Status |
|---|---|---|
| 1.1 water contact as terminal state | "there are many counter examples this is a bit superficial" | OPEN |
| 1.1 stone-skipping para | "needs (lots of) refs" | DONE |
| 1.2 mechanism | "this needs a figure" | OPEN |
| 1.2 "a few milliseconds" | "i dont think its only a few ms." | OPEN |
| 1.2 "what makes this efficient" | "efficiency here is not defined. too vague" | OPEN |
| 1.2 dual purpose | "why this the second purpose a purpose?" | OPEN |
| 1.3 aquatic-aerial robots | "this is vague, unspecific. lacking discussion of the challenges and how they are overcome." | OPEN |
| 1.3 leaving the water | "similar, scientifically, why is leaving water difficult? why do you need impulsive jumping?" | OPEN |
| 1.3 water-entry physics | "why do you need spinning? where is that reaction from?" | OPEN |
| 1.3 spinning multirotors | "why do people study them? in what way do they differ from non-spinning robots? why are they difficult to control? why do you need reduced attitude dynamics" | OPEN |
| 1.4 objectives | "these four objectives are reasonable" | *(approval)* |

## Chapter 2 — Dynamic modelling

The chapter drawing the most fire, and the style complaint is repeated four times.

| Where | Annotation | Status |
|---|---|---|
| 2.1 "exchange of energy" | "exchange of energy? what does it mean?" | OPEN |
| 2.1 "few tens of milliseconds" | "that fast?" | OPEN |
| 2.1 | **"change the writing style. this is a thesis, not a popular science book"** | OPEN |
| 2.1 rotation para | "figure" | OPEN |
| 2.1 | "define variables properly" | OPEN |
| 2.1 scope/assumptions | "if you dont take these examples, what do the full approaches involve?" | OPEN |
| 2.2 v_x | "how is this related to omega r earlier?" | DONE (merged section derives v_x(r)=omega r directly) |
| 2.2 v_x | "is this v_x the same everywhere on the hydrofoil?" | DONE (same merge) |
| after eq 2.5 | "wrong indentation" | DONE |
| 2.3 heading | "I think you should merge 2.2/2.3. Introduce the quasi steady model in the context of blade-element method directly." | DONE |
| eq 2.12 c_sub | "figure needed" | OPEN |
| eq 2.17 dF_R | "figure needed" | OPEN |
| eq 2.25/2.26 | "align the equations" | DONE |
| 2.5 params | "mass? moment of inertia?" | OPEN |
| 2.5 params | "why do you test with these parameters?" | OPEN |
| 2.5 "every case ejects" | "ejects?" | OPEN |
| 2.5 results | "the descriptions of the results are shallow. I dont learn much and it doesnt explain the underlying reasons" | OPEN |
| 2.5 "not symmetric" | "i dont see why it should be symmetric" | OPEN |
| 2.5 spin monotonic | "you dont need simulation to have this conclusion, its obvious from the equations" | OPEN |
| 2.5 | "any implication on energy? should we somehow define efficiency? which configuration is better and why?" | OPEN |
| Fig 2.2 | "what about position?" / "I think the plots should be separated." | OPEN |
| 2.5 design space | "This is written in a way that it is difficult to follow" | OPEN |
| Fig 2.3 | **"this analysis lacks purpose. what do you need to get? what's the design requirement? whats the performance metric?"** | OPEN |
| 2.5 retained spin para | "this paragraph is so difficult and impossible to follow" | OPEN |
| 2.5 | **"I think you also need energy analysis"** | OPEN |
| 2.5 conclusion | "your analysis/conclusion is so convoluted." | OPEN |
| 2.5 | "again, need to change the writing style. this is poor. it should be more direct" | OPEN |
| 2.5 closing | **"the message I actually get is: the airfoils need not be large..... this is not enough"** | OPEN |

## Chapter 3 — Design

| Where | Annotation | Status |
|---|---|---|
| 3.1 spin ceiling | **"where is this number from? what do you mean you can research a much higher speed than expected? why?"** | DECIDE |
| 3.1 latency claim | "then how do you claim that this is the limit?" | DECIDE |
| 3.2 75 mm radius | "r_in and r_tip?" | DONE |
| 3.3 flat-plate coefficients | "citation?" | DONE |
| 3.3 beta list | "I dont think you tested all these values" | DONE |
| 3.3 only 30 deg built | "why?" | DONE |

**Recommendation on the spin-rate items:** delete the naive 20-pi ceiling argument
rather than defend it. State the flown rate as a fact and drop the latency
speculation, for which no measurements were kept.

## Chapter 4 — Flight dynamics and control

| Where | Annotation | Status |
|---|---|---|
| 4.1 eta definition | "this should be a separate eq" | DONE |
| 4.1 non-revolving frame | "figure" | OPEN |
| 4.3 "substantive departure" | "for a regular quadcopter omega_z can be selected too" | OPEN |
| 4.4 eta | "cite the eq that defines eta" | DONE |
| 4.4 reduced dynamics | "citation" | OPEN |
| eq 4.29 | "no need to frame the equation" | DONE |
| 4.5 controller | "how is this similar or different from previous works" | OPEN |

## Chapter 5 — Experimental validation

| Where | Annotation | Status |
|---|---|---|
| Ch5 opening | "introduction paragraph" | DONE |
| 5.1 water | "size/depth?" | OPEN (needs the number) |
| 5.2 phase | "explain the diff between phi and psi" | DONE |
| 5.2 | "what about gyroscopic readings?" | OPEN |
| 5.2 figure slot | "no validation of the hopping model?" | DONE |
| 5.3 unpowered descent | "not sure it is justified" | OPEN |
| 5.4.1 contact 106 ms | "a lot longer than your model prediction" | DONE |
| Fig 5.2 | "what about the rotational rate?" | OPEN |
| Fig 5.2 | "how does this compare to the model?" | DONE |
| Fig 5.3 composite | "time stamp?" | DONE |

---

## The five substantive problems, and how each was resolved

1. **Chapter 2's writing style.** §2.1 rewritten in a technical register:
   opens by stating what is modelled, defines every symbol on first use
   against Fig 2.1, no rhetorical paragraph openers. §2.5 rebuilt. The chapter
   got shorter before it got longer again.

2. **Related work has no *why*.** Each paragraph of §1.3 now carries the
   physics: the opposing demands the two media make of one airframe; adhesion
   scaling on contact perimeter against thrust scaling on disk area, which is
   why departure needs stored energy released impulsively; the inertial origin
   of the skipping reaction and the two distinct roles of spin; and for
   spinning multirotors what giving up heading buys, why a rotating actuation
   axis and gyroscopic precession make control hard, and why the reduced
   attitude description follows. No new references were needed.

3. **Section 2.5 has no stated purpose.** The design-space study was CUT. §2.5
   now opens with its purpose, carries a parameter table so it is
   reproducible, and ends with a validation against the eight measured
   contacts plus an energy accounting section. The model is stated to be a
   sizing tool and not a predictive one.

4. **The spin-rate claim.** Deleted rather than defended, as recommended. The
   invented 20*pi ceiling and the latency speculation are gone from §3.1,
   which now states the flown rate as a fact and says the reason is
   unresolved. Checked first whether the obvious explanation held (that the
   onboard projection runs faster than the 100 Hz outer loop); it does not,
   because the yaw angle reaches the firmware only at the packet rate.

5. **Missing figures.** Four added: Fig 1.1 hop cycle, Fig 4.1 non-revolving
   frame, Fig 2.2 rebuilt as three panels, Fig 5.2 given a fourth panel for
   spin rate. Fig 5.3 gained time stamps. The c_sub and force-decomposition
   requests were met by pointing at Fig 2.1, which already showed both.

## What the review got right that the thesis had wrong

- **106 ms contact.** His "a lot longer than your model prediction" was right
  to be suspicious. Corrected detection gives 75 ms and -1.53 m/s.
- **"omega_z can be selected too".** Correct, and the paragraph claiming a
  "substantive departure" was wrong. Selectability is not the distinction;
  decoupling the spin from the lift channel is.
- **"not sure it is justified"** on the unpowered descent. Here he was
  *misled by the thesis's own error*: the text had been softened to say the
  rotors returned during the contact, which came from comparing a lagged
  velocity signal against an unlagged command. Lag-free, the original claim
  stands and the whole contact is unpowered.
