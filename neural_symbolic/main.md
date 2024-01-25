# Neural Symbolic AI
Comining Neural Learning and Symbolic Algorithms is the deterministic path to build robust machine intelligence.

## Current state of Neuro-Symbolic 
*resource: https://arxiv.org/pdf/2105.05330.pdf | https://en.wikipedia.org/wiki/Neuro-symbolic_AI*

Neural learning is used for "system 1" reasoning through pattern recognition; Symbolic methods are better at "system 2" reasoning, ie. more deterministic, complex algorithms.

> Symbolic algorithms are methods in artificial intelligence that involve the manipulation of symbols to represent problems and compute solutions. They are based on formal logic and can be deterministic, meaning they follow a set of predefined rules to reach a conclusion. Here are some examples:
>1. Expert Systems: These use a set of rules to make inferences and decisions, mimicking the decision-making ability of a human expert.
>2. Logic Programming: Languages like Prolog allow the definition of facts and rules which the system uses to perform automated reasoning.
>3. Symbolic Reasoning: This involves using symbols to represent objects and their relationships in a structured form, such as semantic networks or ontologies, to perform reasoning tasks.
>4. Inductive Logic Programming (ILP): A method of learning logical definitions from examples by inducing general rules from specific observed instances.
>5. Constraint Satisfaction Problems (CSPs): These involve finding solutions to problems defined by constraints on variables, such as scheduling or puzzle solving.
>6. Search Algorithms: Techniques like A or Dijkstra's algorithm, which systematically explore possible paths in a graph or tree structure to find a goal state.
>7. Symbolic Mathematics: Systems like Mathematica or Maple that perform algebraic computations symbolically rather than numerically.
>8. Automated Theorem Proving: Algorithms that prove theorems by systematically exploring the possible space of proofs.
>9. Knowledge Representation and Reasoning (KRR): Techniques for representing knowledge about the world in a form that a computer system can utilize to solve complex tasks.
>10. Decision Trees: A model of decisions represented as a tree where nodes represent decisions or outcomes and the branches represent the consequences of those decisions.

**[Symbolic Neuro Symbolic]** refers to an approach where input and output are presented in symbolic form, however
all the actual processing is neural. Examples are generative language models lile GPT.

**[Symbolic[Neuro]]** refers to a neural pattern recognition subroutine within a symbolic problem solver, with examples such as AlphaGo, AlphaZero, and current approaches to self-driving cars.

**[Neuro ∪ compile(Symbolic)]** refers to an approach where symbolic rules are "compiled" away during training,
e.g. like the 2020 work on Deep Learning For Symbolic Mathematics.

**[Neuro → Symbolic]** refers to a cascading from a neural system into a symbolic reasoner, such as in the NeuroSymbolic Concept-Learner [8].

**[Neuro[Symbolic]]** refers to the embedding of symbolic reasoning inside a neural engine, where symbolic reasoning is understood as "deliberative, type 2 reasoning" as common, e.g., in business AI, and including an
internal model of the system’s state of attention: Concepts are decoded to symbolic entities in an attention
schema when attention to these concepts is high. A goal in the attention schema then signals that deliberative
reasoning be executed.


## AlphaGo
**Resource: **

AlphaGo is a perfect demonstration of Neural Symbolic approach, involving 3 core components:

- (Neural) Policy NN
- (Neural) Reward NN
- (Symbolic) Monte Carlo Tree Search