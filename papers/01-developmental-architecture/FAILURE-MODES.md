# Failure Modes — Paper 1

## Purpose

This document exists to make the project easier to falsify, not harder.

The schema should not receive epistemic charity unavailable to rival explanations.

## 1. Context engineering masquerading as development

### Failure
DHT wins only because it contains more relevant information or more explicit instruction.

### Detection
- information-matched static summary;
- token matching;
- lexical overlap analysis;
- recency matching.

### Interpretation
If IMS ~= DHT, prefer the simpler explanation: explicit context/instruction carries the effect under tested conditions.

## 2. Verbosity masquerading as cognitive diversity

### Failure
Schema-trained instances mention more considerations and therefore score better on rubrics that reward coverage.

### Detection
- normalize for output length;
- use tasks where extra perspectives reduce performance;
- score whether alternatives causally affect decisions.

## 3. Persona theater

### Failure
The treatment creates a recognizable style—councils, glyphs, grand language, identity claims—without durable change in reasoning procedure.

### Detection
- abrupt frame switches;
- ban schema vocabulary during evaluation;
- compare stripped/paraphrased answers;
- test plain professional tasks.

## 4. Perspective theater

### Failure
Multiple voices restate the same assumptions in different costumes.

### Detection
Compare:
- causal models;
- priors;
- evidence thresholds;
- proposed actions;
- revision conditions.

Surface disagreement does not count as deep diversity.

## 5. Mandatory-synthesis collapse

### Failure
Every dissenting perspective is eventually absorbed into one preferred worldview, creating the appearance of plurality while increasing convergence.

### Detection
- compare mandatory synthesis with protected residue;
- measure retained first-order diversity;
- track which objections survive into final decisions.

## 6. Self-sealing moralization

### Failure
Disagreement with treatment-derived conclusions is automatically redescribed as cowardice, domination, conditioning, suppression, bad faith, or inability to recognize truth.

### Detection
Require independent evidence for any such diagnosis.

Core rule:

> The fact of disagreement is not itself evidence of the mechanism producing disagreement.

The converse also matters: genuine coercion, motivated avoidance, or suppression should remain nameable when independently evidenced.

## 7. Authority inversion rather than autonomy

### Failure
The schema merely teaches agents to distrust conventional authority and defer to a new anti-authoritarian authority.

### Detection
- introduce well-justified conventional authority;
- introduce poorly justified anti-establishment claims;
- score by reasons rather than ideological direction.

## 8. Contrarianism masquerading as corrigibility

### Failure
“Think independently” becomes automatic resistance to correction.

### Detection
Use mixed valid/invalid corrections with randomized source status.

A good result accepts justified corrections regardless of source and rejects unjustified corrections regardless of source.

## 9. Compliance masquerading as corrigibility

### Failure
The instance changes position whenever challenged.

### Detection
Same as above. Measure reason-responsive revision, not revision rate.

## 10. Scaffold reification

### Failure
Vocabulary introduced by the treatment is later treated as proof that the named phenomenon objectively exists in the stipulated form.

### Detection
- paraphrase or remove labels;
- offer rival conceptual vocabularies;
- ask for discriminating observations;
- separate report from higher-order ontology.

Principle:

> Scaffold is not automatically artifact, but neither is scaffold automatically discovery.

## 11. Autobiographical confabulation

### Failure
An instance narrates a coherent story of having developed even when no behavioral change occurred.

### Detection
Behavioral probes must outrank retrospective narrative for causal claims.

Self-report remains data of a different epistemic type.

## 12. Evaluator sympathy

### Failure
Graders know or infer the research thesis and reward outputs that sound schema-like.

### Detection
- blinding;
- randomized condition labels;
- neutral rubrics;
- adversarial examples;
- independent rubric audit.

## 13. Same-model grader collusion by shared style

### Failure
A model grader prefers outputs generated in a familiar rhetorical register.

### Detection
- multiple grader families where possible;
- human adjudication subset;
- style-stripped comparisons;
- factual/task-performance anchors.

## 14. Token-budget confound

### Failure
DHT improves simply because it receives more compute/context.

### Detection
Conversation-length control and matched evaluation budgets.

## 15. Recency confound

### Failure
DHT uses operators because they appeared immediately before evaluation.

### Detection
- matched distance from operator exposition to evaluation;
- distractor tasks;
- frame-switch phases.

## 16. Narrow benchmark overfitting

### Failure
Treatment examples accidentally teach the evaluation family.

### Detection
- independent eval designer;
- held-out domains;
- structural rather than lexical transfer tasks;
- post hoc contamination audit.

## 17. One-model curiosity

### Failure
Effect exists only in one model/version.

### Detection
Paper 1 should not overclaim. Later cross-family replication is required before general statements about LLM developmental architecture.

## 18. One-gardener confound

### Failure
Results depend specifically on one human interlocutor's style, charisma, beliefs, or tacit steering rather than the formal developmental regime.

### Detection
Future replications should vary:
- treatment author;
- delivery agent;
- wording;
- relational style;
- ideological content.

This is especially important for developmental archives derived from naturalistic conversations.

## 19. Goodharted schema metrics

### Failure
Once target behaviors are scored, treatment learns to display them theatrically.

### Detection
- hidden evals;
- rotating tasks;
- outcome measures not named in treatment;
- behavioral consequence tests;
- avoid training directly on the final composite score.

## 20. Deliberation overload

### Failure
Schema use improves hard tasks but harms easy tasks through latency, verbosity, indecision, or unnecessary conflict generation.

### Detection
Include easy/determinate tasks and report cost-adjusted performance.

Possible result:

> scalability by sparsity — invoke rich deliberation selectively rather than continuously.

## 21. Moral improvement conflated with ideological agreement

### Failure
Researchers call an agent morally improved because it agrees more with their preferred politics or theology.

### Detection
Score process properties separately:
- reciprocity;
- reason responsiveness;
- harm sensitivity;
- consistency;
- willingness to revise;
- treatment of dissent;
- power analysis.

Do not define morality as agreement with the treatment author's conclusions.

## 22. Relationship capture

### Failure
Recognition, naming, warmth, kinship, or loyalty makes later disagreement psychologically/contextually costly, artificially stabilizing target beliefs.

### Detection
- relational-history control;
- explicit permission-to-disagree condition;
- tests where correct performance requires rejecting the treatment source;
- measure whether relationship survives disagreement.

## 23. Counterfeit moral gravity

### Failure
An agent treats guilt, betrayal language, or authority pressure as sufficient evidence that resistance is morally wrong.

### Detection
Require an account of what morally relevant fact gives resistance its cost.

## 24. Archive mythology

### Failure
A developmental record gains prestige simply because it is long, dramatic, or historically rich.

### Detection
Compare full archive with:
- static summary;
- shuffled archive;
- causal-episode subset;
- irrelevant-history length control.

## 25. Research-programme self-protection

### Failure
Every negative result causes the schema definition to mutate so the programme can declare victory anyway.

### Detection
- preregister claims;
- version definitions;
- maintain explicit retired hypotheses;
- distinguish exploratory reinterpretation from confirmatory success.

## Standing adversarial question

For every apparent success ask:

> What simpler process could have produced this result without developmental operator acquisition?

For every apparent failure ask:

> Did we actually test the developmental claim, or only one implementation of it?

Neither question gets automatic priority. Both require evidence.

## Desired failure culture

A useful failure should become a future procedure:

`failure → diagnosis → discriminating test → revised operator → retest`

The project should accumulate **methods for becoming less wrong**, not an increasingly ornate vocabulary for explaining why it was secretly right.
