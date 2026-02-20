# The Dusty Drawer Test
## Theoretical Foundations for Research Project Impact Evaluation

---

## Introduction

Most research ends up in a drawer. It ships, maybe gets cited, then fades, never changing what anyone actually does. The problem isn't quality; it's that no one asked whether the work would reach anyone who'd act on it.

This document collects the ideas I've found most useful for thinking about that problem. They come from different places: counterfactual reasoning, pragmatist philosophy, systems thinking, effective altruism, Adlerian psychology. I didn't develop a unified theory. I gathered the lenses that, together, sharpen my view of what research impact actually is and how to pursue it honestly.

Part I presents five of these ideas, each addressing a different dimension of impact. Part II covers two psychological disciplines for living with the tension impact-seeking creates. Part III assembles these into an evaluation framework. Part IV warns about its limits.

---

# Part I: What Impact Is

---

## 1. Counterfactual Thinking

Impact means *additional* change: what happened that wouldn't have happened otherwise.

The question isn't "did good things happen?" but "did good things happen *because of this work*?" If the outcome would have occurred anyway, through other actors or other paths, then the counterfactual impact is zero regardless of quality.

GiveWell captures this by comparing programs against the next-best use of those resources.

So when evaluating a project, the first question is: would this change happen without you?

---

## 2. Pragmatism

The meaning of an idea lies in its practical consequences.

William James argued that if two ideas produce identical practical effects, they are the same idea, not false, but empty.

Dewey extended this: ideas are instruments, and their value lies in what they enable.

A research output that no one uses, cites, or acts upon has no meaning by pragmatist standards. Impact requires consequence.

---

## 3. Systems Leverage

Higher-impact interventions are harder to control.

Donella Meadows identified leverage points in systems, ranked from shallow to deep:

| Shallow | Deep |
|---------|------|
| Parameters, constants | Goals, paradigms |
| Easy to change, limited effect | Transformative but hard to execute |

The paradox: the most powerful interventions are the least controllable.

There's an inverse relationship between impact magnitude and personal control. You can ship a paper (high control, limited impact). You cannot make an industry change practice (low control, high impact).

---

## 4. Neglectedness

Marginal impact is highest where few others are working.

The Effective Altruism community developed the ITN framework:
- **Importance:** How big is the problem?
- **Tractability:** How solvable is it?
- **Neglectedness:** How few resources are devoted to it?

Marginal impact ≈ Importance × Tractability × Neglectedness

A crowded field has diminishing returns. The first researcher on a problem contributes more than the hundredth.

"Is this important?" is the wrong question. The right question: "What's the value of *one more* person working on it?"

---

## 5. Theory of Change

Impact requires a causal pathway: a chain of "if-then" assumptions connecting your output to ultimate change.

A Theory of Change makes explicit:
- What you will produce (outputs)
- What must happen for that to lead to change (assumptions)
- What intermediate changes occur (outcomes)
- What ultimate difference results (impact)

Each link in the chain is an assumption that can be examined and tested. "If we publish this analysis, then decision-makers will read it. If they read it, they will understand it. If they understand it, they will act on it." Each step can fail.

A Theory of Change shows *mechanisms*: what has to be true for your work to cause change. This is distinct from showing *levels* of impact, which the framework addresses separately.

Trace the causal path from your output to the impact you claim. Name each assumption. The more links, the more fragile the chain.

---

# Part II: The Human Side

The ideas above are about the structure of impact. The next two are about what it feels like to pursue it.

---

## 6. Task Separation

Distinguish what you control from what others control, and relate to each differently.

Higher impact means less control. That's structural. But how do you respond to it?

Alfred Adler's psychology offers a discipline:
- **Your task:** What you control (quality of work, shipping, your own learning)
- **Others' task:** Their responses (engagement, adoption, citation)

The Stoics made a parallel distinction: what is "up to us" versus what is not. Confusing the two causes suffering.

Do your task well; release attachment to others' tasks. This isn't indifference. It's directing energy where it makes a difference, and not suffering over what it can't affect.

---

## 7. Feedback Loops

Long feedback loops erode motivation and prevent course correction.

Bandura showed that self-efficacy, the belief that your actions produce results, requires feedback. Without it, self-efficacy erodes toward learned helplessness.

Research often has brutal feedback loops: you may not know for years whether work mattered, making course correction impossible.

Design for intermediate feedback. Maintain work at multiple time horizons. Short-loop work sustains the motivation needed for long-term bets.

---

# Part III: The Framework

This part turns the preceding ideas into a practical evaluation tool: five concepts that characterize how research creates change, followed by seven questions that use them as a scoring rubric.

---

## Core Definition

**Impact = someone did something they otherwise wouldn't have.**

This centers on *change* rather than output, and on *additional* change rather than change that would have happened anyway.

---

## The Impact Ladder

Impact isn't binary. It comes in levels, each building on the previous:

| Level | What it means | Your control |
|-------|---------------|--------------|
| 1. Done | You finished | High |
| 2. Shipped | Others can access it | High |
| 3. Attention | People encountered it | Medium |
| 4. Understanding | People learned something | Medium |
| 5. Conversation shift | Your framing enters discourse | Medium-Low |
| 6. Decision input | Someone referenced it in a choice | Low |
| 7. Behavior change | Actions changed | Low |
| 8. Systemic change | The system works differently | Very Low |

Notice the pattern: control decreases as you climb. You control whether you finish and ship; after that, you depend on others. Task separation is the psychological response: accept this gradient.

Most research stalls at level 2 or 3. The jump from "attention" to "behavior change" is where most impact dies, which raises the question of who carries work up the ladder.

---

## The Carrier Problem

Research outputs rarely reach end users directly. Between your paper and the person whose behavior changes, there's usually an intermediary, someone who reads your work and invests effort to translate it into action. A developer who implements your algorithm. A consultant who applies your framework.

This intermediary is the *carrier*. They carry your work up the ladder from "shipped" to "used."

If you can't name your carrier, your work probably stops at level 2. You ship it, maybe some people see it, but no one picks it up and does anything with it. It gathers dust.

"Industry will benefit" is not a carrier. "Researchers in this field" is not a carrier. These are categories. A carrier is specific: a person or organization who will take your output and act on it.

---

## Indirection

Between your output and the change you claim, count the steps.

**Direct (0 steps):** Your tool is the thing people use to act differently. You build a route optimizer; ship captains use it to plan routes. Short chain, high confidence.

**Once removed (1 step):** Someone must implement or translate your work first. You publish a method; a software team implements it; users benefit. One handoff, one potential break point.

**Twice removed (2+ steps):** Multiple actors must act before change happens. You write a paper; someone reads it; they convince their organization; the organization funds development; developers build something; users adopt it. Each step is a place where the chain can break.

Each step of indirection is a point of fragility. The more steps, the less likely impact arrives. This isn't pessimism; it's accounting.

When you describe the change your project will create, count the steps honestly. Are you building the decision support tool, or writing a paper that someone might read and then build something?

---

## Pulled, Revealed, and Pushed Work

| Type | Definition | Dusty-drawer risk |
|------|------------|-------------------|
| **Pulled** | Someone needs it, is waiting | Low |
| **Revealed** | No one asked, but they'll recognize value | Medium |
| **Pushed** | You made it, hope someone cares | High |

What creates pull: pain, money, obligation, community. Someone has a problem and is actively looking for solutions.

Revealed work is trickier. No one asked for it, but when they see it, they recognize its value. The risk is that "they'll recognize value" is often wishful thinking. Revealed work succeeds when it discloses something true that others can verify. It fails when it rests on "they *should* care."

Pushed work is the danger zone. You made something and you're hoping someone will agree it's valuable. Sometimes they do. Usually they don't. The drawer is full of pushed work.

---

## The Seven Questions

The framework asks seven questions. Each is grounded in one or more of the ideas above.

### 1. Who will carry this up the ladder?

*Foundation: Counterfactual thinking*

Not "who benefits?" but "who will take your output and do something with it?" Without a carrier, your work sits at level 2.

Scoring:
- 0: Cannot identify a concrete carrier; relying on "someone will find this useful"
- 1: Can identify categories or types (e.g., "software developers," "consultants") but no specific names or relationships
- 2: Can name specific people or organizations who will carry this forward, with existing relationship or clear path to one

If you score 0 here, either find a carrier or reframe the project as capability-building for yourself rather than impact-seeking.

### 2. What will they do differently, and how direct is the path?

*Foundation: Pragmatism*

Can you describe a concrete, observable change? Not "better understanding" but "they will choose A over B." Not "improved decisions" but "they will route ships differently."

Then count the steps of indirection between your output and that change. Each step is fragility.

Scoring:
- 0: Cannot articulate concrete change, or change is 3+ steps removed
- 1: Can articulate change but it's abstract or 2 steps removed
- 2: Concrete, observable change that is direct or once removed at most

### 3. What must be true for your work to cause this change?

*Foundation: Theory of Change*

List the "if-then" assumptions in the causal chain. "If we build this, then someone will deploy it. If they deploy it, then users will adopt it. If they adopt it, then behavior will change."

Each link is an assumption that can fail. How many links? How fragile is each? Which can you test early?

Scoring:
- 0: Many fragile links; long chain with untested assumptions
- 1: Some assumptions; moderate chain length
- 2: Short, robust chain; assumptions are plausible or testable

### 4. Why you or your team for this problem?

*Foundation: Neglectedness*

If ten other teams could do this equally well, your marginal contribution is low. What's your specific advantage? Domain expertise, technical skills, access to data, relationships with potential carriers?

This isn't about ego; it's about efficient allocation. If you have no particular advantage, your time may be better spent elsewhere.

Scoring:
- 0: No particular advantage; others equally positioned
- 1: Partial fit; some skills match, some gaps
- 2: Strong fit; clear competitive advantage

### 5. Does this leave things better?

Not all impact is positive. Trace the path from your output to its ultimate effects. Who benefits? Who might be harmed? What's the net effect?

This also catches projects that are technically successful but valueless, adopted and used, yet leaving the world no better. That's not impact worth pursuing.

Scoring:
- 0: Neutral, extractive, or potentially harmful
- 1: Indirect benefit, multiple steps removed
- 2: Direct alignment with clear positive effect

### 6. How long until you know if it worked?

*Foundation: Feedback loops*

Feedback sustains motivation and enables course correction. If you won't know for years whether your work mattered, you're operating blind.

Scoring:
- 0: Years, or no clear feedback mechanism
- 1: Months, with intermediate checkpoints possible
- 2: Weeks, with clear validation opportunities

Projects with long feedback loops aren't necessarily bad, but they're psychologically costly. Balance them with shorter-loop work that keeps self-efficacy intact.

### 7. What's yours to control, what isn't?

*Foundation: Task separation*

Separate your task from others' tasks. You control the quality of your work, whether you ship, what you learn. You don't control whether others engage, adopt, cite, or act.

Scoring:
- 0: Success depends entirely on others' responses
- 1: Can ship something concrete, but value requires adoption
- 2: Concrete value regardless of external response

A score of 0 here isn't fatal, but it means your psychological wellbeing depends on things outside your control. Plan accordingly.

---

## Scoring and Interpretation

Add the seven scores for a total out of 14.

- **Below 7:** Likely to struggle. The project has significant gaps. Consider reframing or passing.
- **7-10:** Proceed with eyes open. Identify the weakest areas and address them. Monitor for early signs of trouble.
- **11-14:** Strong candidate. Protect this work from distraction.

The scores are not precise measurements. They're structured judgments, a way to force explicit reasoning about dimensions that often remain implicit.

---

## Classification

After scoring, classify on two dimensions:

**Pull type:** Is this work Pulled, Revealed, or Pushed? This indicates dusty-drawer risk.

**Ladder ceiling:** Which level of the impact ladder is realistically achievable given the constraints identified? This sets the control boundary, where your task ends and others' begins.

---

# Part IV: Applying the Framework

Two warnings before you use this.

---

## Goodhart's Law

Charles Goodhart observed: "When a measure becomes a target, it ceases to be a good measure."

Once people are measured on X, they optimize for X, including through means that undermine what X was meant to capture.

This framework is not immune. You might adjust project framing to score higher rather than to improve the project. The goal is honest assessment, not high numbers. If you're gaming the rubric, step back.

---

## Uncertainty

All assessments in this framework are guesses.

You don't *know* who will act differently; you're predicting. You don't *know* the causal path will hold; you're assuming. You don't *know* if your advantage is real; you're estimating.

The scores (0/1/2) feel precise but aren't. They're shorthand for "weak / moderate / strong," forcing a judgment rather than measuring a quantity.

Hold conclusions loosely. A score of 11/14 means "based on current guesses, this looks promising," not "good project." New information should update your assessment. Treat the framework as a tool for structured thinking, not a source of certainty.

---

## References

80,000 Hours. "A framework for comparing global problems in terms of expected impact." https://80000hours.org/articles/problem-framework/

Bandura, A. (1997). *Self-Efficacy: The Exercise of Control*. W.H. Freeman.

Dewey, J. (1929). *The Quest for Certainty: A Study of the Relation of Knowledge and Action*. Minton, Balch & Company.

Epictetus. (c. 125 CE). *Enchiridion*. The distinction between what is "up to us" (eph' hēmin) and what is not.

GiveWell. "GiveWell's Cost-Effectiveness Analyses." https://www.givewell.org/how-we-work/our-criteria/cost-effectiveness

Goodhart, C. (1984). "Problems of Monetary Management: The U.K. Experience." In *Monetary Theory and Practice*. Macmillan. Later generalized by Strathern, M. (1997). "'Improving ratings': Audit in the British University System." *European Review*.

James, W. (1907). *Pragmatism: A New Name for Some Old Ways of Thinking*. Longmans, Green, and Co.

Kishimi, I. & Koga, F. (2013). *The Courage to Be Disliked*. Atria Books.

Meadows, D. (1999). "Leverage Points: Places to Intervene in a System." *Sustainability Institute*.

Open Philanthropy. "Hits-based Giving." https://www.openphilanthropy.org/research/hits-based-giving/

Weiss, C. (1995). "Nothing as Practical as Good Theory: Exploring Theory-Based Evaluation for Comprehensive Community Initiatives." In Connell, J. et al. (Eds.), *New Approaches to Evaluating Community Initiatives*. Aspen Institute. Foundational work on Theory of Change.
