# Waller Project

On How to Trigger a Small Intelligence Explosion

# Introduction

- What is an intelligence explosion?

# Risk perspective

"[self-awareness] is probably not quite what's going in [GPT-4] in reality." [Eliezer Yudkowsky](https://youtu.be/AaTRHFaaPG8?t=92)

## We are playing with dynamite, not nukes.

Current language models do not possess enough [quality intelligence](https://en.wikipedia.org/wiki/Superintelligence:_Paths,_Dangers,_Strategies) to pose a threat to humans.

## We are playing in the desert, not the forest.

There are simply not enough affordances for agents to interact with the outside world for agents to actually be useful. OpenAI Function Calling only goes so far. So it's not like starting a fire in a forest, it's like starting a fire in the desert.

### Considerations of harm

- How could this become harmful?

# Definition of success

> Takeaway: the aim is not super-intelligence, but ad-intelligence or para-intelligence. Not orders of magnitude better in every domain, but marginally better in one domain. These small steps compound over time.

### Requirements

- An agent augments its own capability in a domain that “has economic or strategic significance.” [Nick Bostrom](https://en.wikipedia.org/wiki/Superintelligence:_Paths,_Dangers,_Strategies)
- All the agent has to do is improve itself, and persist its improvement.
- The agent must exhibit awareness of its own improvement. (interpretability)

### Not required

- Outperforming a human in that domain (superintelligence)
- Continual improvement in that domain (chain reaction)
- Expansion into another domain (spread)

### Undecided

- Does it have to be aware of its own improvement (phenomenology)?

## Kinds of intelligence improvements

> Takeaway: each kind of improvement has implementational challenges.

### Speed intelligence

Agent starts with a task and a benchmark, times itself, then modifies its behavior to do the same task faster while maintaining performance. This seems the most straightforward: for a given task, the agent merely has to determine how to do it faster.

### Quality intelligence

Agent starts with a task and a benchmark, then modifies its behavior to improve on the benchmark performance. An agent that's able to improve its own quality could change its own architecture ([Rewoo](https://arxiv.org/pdf/2205.00445.pdf), [Reflexion](https://arxiv.org/pdf/2303.11366.pdf), etc). This could manifest by having an evaluator agent which assesses a task agent's performance, and is able to make modifications the the task agent's architecture.

### Collective intelligence

Agent starts with a task and a benchmark, and figures out how to parallelize the problem so that it can be worked on by more sub-agents. This could look like an orchestrator agent that makes organizational decisions to initialize, rearrange or remove subordinate agents during task execution.

# Approach

## Simula vs Simulacra

> Takeaway: we’re not here to answer questions about the nature of the models. We treat machine intelligence as a fundamentally different kind of intelligence from human intelligence. We distinguish between phenomena (task performance) and epiphenomena (consciousness, motivation, etc.). Among other compelling hypotheses motivated by improving performance, we can test whether epiphenomena present in human intelligence can improve task performance in machine intelligence. We do not aim to inquire whether or which epiphenomena are responsible for task performance or task performance improvements, which are questions of interpretability. (eg [In-context Learning and Induction Heads](https://www.anthropic.com/index/in-context-learning-and-induction-heads)).

- We are not inquiring about intrinsic, embedded, implicit, latent, or unobserved cognition, consciousness or phenomenology. We assess based on empirical evidence, and rely on framing inquiries around whether a behavior of inquiry is “exhibited”, not “is”.
- We do not aim to mimic, replicate or recreate human intelligence. We aim to perform intellectual tasks that humans do, and we don’t confuse or represent one (consciousness) for the other (action). [Baudrillard]

## Knowledge vs Memory

> Takeaway: knowledge stored as a tool will be more immediately useful in creating a sustained task augmentation than declarative knowledge.

- two kinds of knowledge stores for people
  - In the head
  - In the world
- two kinds of knowledge
  - declarative (of)
  - procedural (how)
- four stores of knowledge in LLMs
  - in the weights (head)
  - in the context (head)
  - in the vector store (world)
  - in the tool (world)

## Motivation & Prompting

- Is prompting the only way to tell the agent what to want? Seems like we should be able to use loss as well.

## Assessment

- How will the agent assess whether it has improved?
- When the agent has exhausted its tasks, what will it do next?
- Are task/benchmark based assessments the only way we can improve?
  - McNamara fallacy - the mistake that “what can’t be measured doesn’t exist”.

## Reflection & Awareness

- Transcript-based assessments
  - The agent transcribes its own performance to a document store, reviews how it did and what could be improved, then tries to improve.

# Designs

## Autonomous Tool Development

> An agent makes a new tool for itself.

# Appendix

# Bibliography

1. https://www.anthropic.com/index/in-context-learning-and-induction-heads
