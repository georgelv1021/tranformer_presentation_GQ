# Discussion of Agents with LLM

A presentation regarding the potential of LLM based agents

## Overview

As the modern world progresses towards greater automation, the development of automated agents has become central to numerous technological advancements. At the heart of human-machine interaction lies Large Language Models (LLMs), which have emerged as the foundational support in the evolution of these agents.

This paper delves into the intricacies of LLM-based agents, dissecting their composite elements and examining the various developmental stages and complexities of these sophisticated systems.

### First Question: What is an agent? How do we define agent in the AI world?

## Benefits of LLM for Agents

1. Autonomy: No direct intervention from humans
2. Reactivity: Ability to respond rapidly to changes
3. Pro-activeness: Display goal-oriented actions by taking initiative (Reasoning and Planning)
4. Social ability: Interaction with other agents

## LLM-based Agents Structures

1. Brain: Memory, Knowledge, NLP, Reasoning and Planning, Generalization
2. Perception: Different Input
3. Actions: Textual Output, Tools, Embodied Action

## Types of LLM-based Agents

1. Single Agent
2. Agent-Agent
3. Agent-Human

## Pseudocode: Examples of Difference Between Single Agent & Agent-Human based Agents

GPT-4:

	function respond_to_human(input):
      response = GPT-4.generate_response(input)
      return response
  
	while true:
      human_input = get_input_from_human()
      if human_input is "exit":
          break
      agent_response = respond_to_human(human_input)
      display(agent_response)

AutoGPT:

	function perform_task(goal):
      tasks = AutoGPT.decompose_goal_into_tasks(goal)
      for task in tasks:
            AutoGPT.execute_task(task)
      return AutoGPT.summarize_results()

    user_goal = get_goal_from_user()
		if user_goal is not "exit":
    	final_output = perform_task(user_goal)
    	display(final_output)

### Second Question: What difference can you discover based on these two different types of agents?

## Critical Analysis:

    

   

