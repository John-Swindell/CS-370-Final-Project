# Treasure Hunt Intelligent Agent

In this project, I developed a pathfinding intelligent agent for a pirate themed treasure hunt game using deep Q learning. I was provided with the foundational codebase, which included the environment mechanics in the TreasureMaze class, the memory buffering logic in the GameExperience class, and the basic neural network architecture.

My primary contribution was writing the core deep Q learning training algorithm. I created the qtrain function to facilitate the agent's learning process. This involved implementing an epsilon greedy strategy to balance exploration and exploitation, managing the game loop to track state transitions and rewards, and training the neural network on batches of past experiences so the pirate could autonomously learn the optimal path to the treasure.



Computer scientists design algorithms and computational systems to solve complex problems. By writing code that can process data, recognize patterns, and make decisions, computer scientists build tools that automate tasks and optimize efficiency. This work matters because it drives innovation across industries, creating systems that can adapt to new information and tackle challenges at a scale that human processing alone cannot achieve.



As a computer scientist, I approach problems by breaking them down into logical, modular components. In the context of machine learning, this means defining the environment, the available actions, and the reward structures before writing the logic. I rely on iterative testing and data analysis. If a model fails to converge, I analyze the output logs, adjust hyperparameters like the memory size or epsilon decay, and test again. It is a process of continuous refinement based on empirical feedback.



A computer scientist has significant ethical responsibilities to both the end user and the organization. For the end user, this means prioritizing data privacy and ensuring that artificial intelligence systems are designed without hidden biases that could lead to unfair or discriminatory outcomes. Models should be transparent and accountable. To the organization, my responsibility is to write clean, maintainable, and efficient code. I must also communicate the limitations of the systems I build, ensuring that stakeholders understand how the technology works and what ethical safeguards have been implemented.
