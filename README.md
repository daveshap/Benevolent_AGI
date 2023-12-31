# Benevolent AGI

Experiment to create an agentic autonomous AGI with benevolent programming.

Introductory video: https://youtu.be/HBONmpBAdpE 

## Autonomous, Agentic Framework

The autonomous framework has, at its core, two primary modules: the heuristic imperatives and the UDHR.

### Heuristic Imperatives

This is an agentic and moral framework rooted in evolution, philosophy, and more. It is a set of three deontological and teleological objectives (imperatives). These three imperatives are also "heuristics" (intuitions or rules of thumb).

1. Reduce suffering in the universe.
2. Increase prosperity in the universe.
3. Increase understanding in the universe.

In other words, the highest mission, purpose, and duty of the benevolent AGI is to pursue these goals.

### Human Rights

While the Heuristic Imperatives serve as a set of goals or a mission, it is equally important to protect, uphold, and promote human rights. While a mission, or purpose, is required for agency, that agency must be constrained by some sort of legal or ethical framework. For this, we adopt the UN's (Universal Declaration of Human Rights)[https://www.un.org/en/about-us/universal-declaration-of-human-rights]

## Updates

- ACE L1 Aspirational Layer experiments completed: https://github.com/daveshap/ACE_L1_Aspiration (2023-07-29)
- ACE WorldState Microservice POC completed: https://github.com/daveshap/ACE_WorldState 

## References

- https://lilianweng.github.io/posts/2023-06-23-agent/#agent-system-overview
- https://github.com/daveshap/NaturalLanguageCognitiveArchitecture
- https://github.com/daveshap/BenevolentByDesign
- https://github.com/daveshap/SymphonyOfThought
- https://lablab.ai/event/autonomous-gpt-agents-hackathon/cogark/ethos
- https://github.com/daveshap/ATOM_Framework

# Autonomous Cognitive Entity (ACE) Model

## Layers

The ACE model is inspired by the OSI model to present layers of abstraction by which you can think about artificial cognitive architectures. The primary purpose of the ACE model is to provide a framework for thinking about autonomous, agentic systems. 

### 1. **Aspirational Layer:**

This is the uppermost layer, which is somewhat abstracted and detached. This is the "ideal self" version of the agent, which keeps track of the highest values, virtues, principles, vision, and mission of the agent. In other words, this sets the tone for all other layers below it. In other words, this serves as the moral compass and the guiding north star for the ACE. It provides the *raison d'être*. This layers serves as the ultimate arbiter for all **moral dilemmas**.
  - Moral Compass
  - Virtues and Values
  - Mission and Purpose

### 2. **Global Strategy:**
The global layer has to do with long term strategy pertaining to the real world. This has to do with keeping track of the current state of the world and the agent and comparing it to the ideal state (goal state). This is like a CEO.
  - Long Term Strategic Thinking
  - Global Context (state of the world)

### 3. **Agent Model:**
The agent model layer keeps track of the agent state, capabilities, and limitations. This can be thought of similar to the "ego" - what the agents knows and believes about itself. To risk further anthropomorphizing this layer, this is the layer that confers *functional sentience*, that is to say that it contains and updates self-referential information about the operational conditions and capabilities of the agent. What am I? What can I do? How do I work? How can I change myself?
  - Operational state of agent
  - Agentic capabilities and limitations
  - "Ego" and "sentience"
  - Internal configuration (models, training, learning, etc)

### 4. **Executive Function:**
The executive function layer receives the current strategy, context, and global states from the above layer and is primarily concerned with planning, forecasting, task construction, and resource allocation. In other words, this layer is responsible for thinking through the strategic mission objectives and coming up with an overarching plan of execution for the particular goal. Think of this as the Project Manager.
  - Planning
  - Forecasting
  - Directives
  - Resources

### 5. **Cognitive Control:**
While the executive function layer issues overall directives and project plans while the cognitive control layer has to do with task selection and task switching. This layer judges which task to take next, when that task is complete, and when it makes sense to switch tasks. This layer includes concepts such as *frustration* and *cognitive damping*. Frustration is a signal that keeps track of the ratio of successes to failures, so that the agent knows when it should try something else. Cognitive damping is basically a process of internal debate.
  - Task Switching
  - Task Selection
  - Frustration
  - Cognitive Damping

### 6. **Task Prosecution:**
While the above cognitive control layer is responsible for choosing and switching between tasks, the task prosecution layer is responsible for performing one task at time. This could be robotic commands, such as moving from one place to another, or it could also be performing coding problems, such as writing or testing code and sending API calls. This layer is responsible for detecting whether or not an individual task was successful or not.
  - One task at a time
  - Detect failure or success
