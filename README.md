# Dieu-Donné's Final Research Project AMMI 2023
## Title : Adaptive Deep Q-Networks for Decision Making in Non-Stationary Environments: A Case Study with the Wisconsin Card Sorting Test

Adaptive learning in dynamic environments presents significant challenges in reinforcement learning, especially when the environment's rules change unpredictably. This study introduces an enhanced Deep Q-Network (DQN) architecture designed to effectively handle non-stationary environments, with a focus on the Wisconsin Card Sorting Test (WCST) as a representative problem. Unlike conventional DQN approaches that struggle with rule changes, our method integrates rule context directly into the state space, allowing the agent to adapt its strategy dynamically. We detail the modifications to the traditional DQN architecture, which include extending the input state with rule-specific information and adapting the network to process these extended states efficiently. Experimental results demonstrate that our adaptive DQN significantly outperforms traditional DQN models in terms of flexibility and accuracy in the WCST, showcasing its potential to generalize across different types of non-stationary environments. This approach not only enhances the agent's performance but also contributes to the broader application of deep reinforcement learning in complex, changing systems.


This project was done in collaboration with [Verlon Roel MBINGUI](https://github.com/VerlonRoelMBINGUI/RL_Final_Projects_AMMI2023), [Armandine Sorel Kouyim Meli](https://github.com/sorelkouyim), [Phanie Dianelle Negho](https://github.com/PhanieDianelle) and [Regis Konan Marcel Djaha](https://github.com/RegisKonan)  
 

* The notebook RL_trading_system_good3.ipynb contains the implementation of the Deep Q-Network, Double Deep Q-Network, Dueling 
Double Deep Q-learning networks

* The notebook trading_system_A2C.ipynb contains the implementation of the Deep Q-Network, Double Deep Q-Network, Dueling Double Deep Q-learning networks
  
## Some Results
![DUEL XRP TRADE](https://github.com/dfangnon/RL_Final_Projects_AMMI2023/assets/126726283/b1e3202e-e403-4da1-88e1-1809770816d3)
 ![Duel_XRP_port](https://github.com/dfangnon/RL_Final_Projects_AMMI2023/assets/126726283/4a1bddf6-b519-43cd-b81a-d5e6379db73b)
![Dueling_BTC-USD Trade Signals](https://github.com/dfangnon/RL_Final_Projects_AMMI2023/assets/126726283/726dba1a-c7e2-4d13-8008-c73bc7167b04)
![Dueling_BTC-USD Portofolio Wealth](https://github.com/dfangnon/RL_Final_Projects_AMMI2023/assets/126726283/87fc6d03-3158-4384-a0f1-6fa52afc19d9)
