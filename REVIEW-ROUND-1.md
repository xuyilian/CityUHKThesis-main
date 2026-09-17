# First-round review: Prof. Pakpong Chirarattananon

Annotations from the marked-up PDF, transcribed by location. The PDF was a
build predating the Chapter 5 results and the citation work, so some items
were already resolved when the review arrived; those are marked DONE.

Status key: **DONE** fixed · **OPEN** outstanding · **DECIDE** needs a judgement call

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

## The five substantive problems

Everything above clusters into five. In rough priority order:

1. **Chapter 2's writing style.** Said four different ways. Sections 2.1 and 2.5
   are written as an essay and need rewriting to be direct. Largest single item.

2. **Related work has no *why*.** Four annotations ask the same question: why is
   leaving water hard, why impulsive jumping, why do people study spinning
   multirotors, why reduced attitude dynamics. The section lists what exists
   without explaining the physics of the difficulty.

3. **Section 2.5 has no stated purpose.** No design requirement, no performance
   metric, and no energy analysis, so the design study has nothing to be
   evaluated against. His own summary is the sharpest statement of the problem.

4. **The spin-rate claim.** Recommendation above: delete rather than defend.

5. **Missing figures.** Vehicle schematic (1.2), mechanism (2.1), chord wetting
   (2.12), force decomposition (2.17), coordinate frames (4.1).

## Numbers he flagged that have since changed

He highlighted `-1.55 m/s` and `106 ms` and noted the contact was far longer than
the model predicts. Both were superseded by the corrected contact detection:
entry is now taken at the knee of the velocity rise rather than the velocity
minimum, giving **-1.53 m/s and 75 ms** for the same hop. Worth telling him, since
his instinct that 106 ms was implausible was right.
