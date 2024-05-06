# Dieu-Donné's Final Research Project AMMI 2023
## Title : Adaptive Deep Q-Networks for Decision Making in Non-Stationary Environments: A Case Study with the Wisconsin Card Sorting Test

Adaptive learning in dynamic environments presents significant challenges in reinforcement learning, especially when the environment's rules change unpredictably. This study introduces an enhanced Deep Q-Network (DQN) architecture designed to effectively handle non-stationary environments, with a focus on the Wisconsin Card Sorting Test (WCST) as a representative problem. Unlike conventional DQN approaches that struggle with rule changes, our method integrates rule context directly into the state space, allowing the agent to adapt its strategy dynamically. We detail the modifications to the traditional DQN architecture, which include extending the input state with rule-specific information and adapting the network to process these extended states efficiently. Experimental results demonstrate that our adaptive DQN significantly outperforms traditional DQN models in terms of flexibility and accuracy in the WCST, showcasing its potential to generalize across different types of non-stationary environments. This approach not only enhances the agent's performance but also contributes to the broader application of deep reinforcement learning in complex, changing systems.


This project was done in collaboration with my supervisor [Dr. Eduardo H. Ramirez-Rangel](https://github.com/tozanni) 
 

* The notebook WCST_NS_DQN_Paper_Notebook.ipynb(py) contains all the method that we use for this project, the default environment implementation and the novel one for the WCST NS-DQN agent.
  
## Some Results from the paper
![trio_100](https://github.com/dfangnon/NS-DQN_WCST/assets/126726283/0aa4a635-fc47-42d8-b11f-0775538c1456)
![trio_500](https://github.com/dfangnon/NS-DQN_WCST/assets/126726283/208b3e73-f4b2-40c8-b30f-e2186f0e12a5)
![trio_1000](https://github.com/dfangnon/NS-DQN_WCST/assets/126726283/ca3699ef-bc4a-4f53-9b91-f1e3770f9689)


