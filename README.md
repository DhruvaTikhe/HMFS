## Hybrid Metaheuristic Feature Selection For Intrusion Detection in IoT based Cyber Security Environments Using Improved Salp Swarm Algorithm

This project focuses on a Hybrid Metaheuristic approach for Feature Selection in IoT based Cyber Security Intrusion Detection
Flow of the project:

1. Dataset Selection

2. Preprocessing

3. Statistical Feature Selection

4. Metaheuristic Feature Selection

5. Deep Learning Classification


***Dataset:*** IoT ID 20 (Find it here: https://sites.google.com/view/iot-network-intrusion-dataset/home).

***Preprocessing:*** Standard machine learning preprocessing including SMOTE, Sampling, Manual Feature Engineering

***Statistical Feature Selection:*** Pearson Correlation Coefficient

***Metaheuristic Feature Selection:*** Improved Salp Swarm Algorithm.

***Deep Learning Classifiers:*** DNN,CNN,RNN,GRU,AutoEncoder.

## Improved Salp Swarm Algorithm

- Salps are seawater creatures which form round chains to survive and find shelter and prey
- The idea of Metaheuristics is to transfer the real world behaviour of animals onto computational terminology to obtain a 'natural' solution
- In this case, each feature is treated as a single Salp organism. Its goal is to either lead the chain (strongest feature) or follow the chain (follower feature). If it is unable to fulfil these, its rejected from the chain (weakest feature)
- For such a case, a target function is evaluated iteratively to ensure each feature's importance is calculated and only the useful ones are kept
