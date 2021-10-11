# Link-Prediction-in-Social-Networks
## AIM
Given two nodes in a social network, our system will find the probability of bidirectional acceptance of friend requests. The system calculates the centrality measures of the given EGO network to strong ties between the individual nodes as well as the negative ties. This helps us build a cluster where the centrality measures become maximum and along with the combined effect of the negative ties as we can estimate the probability of a friend request getting accepted. 

## DATASET
Links between various Facebook users

## ARCHITECTURE DIAGRAM
![CSE3021 Flowchart@2x](https://user-images.githubusercontent.com/42903837/136744607-3201a9a9-33bd-43fd-9877-8b315f1bfd53.png)

## APPROACH
We have calculated various centrality measures on our dataset and clustered the nodes accordingly. This is based on the assumption that since centrality measures compute the amount of connectibility between nodes, nodes of the same cluster are supposedly expected to have connections between them. Having acquired this data, we can now set a significance level for testing our hypothesis and this level is based on the z-scores of all our nodes. Aggregating the z-scores as the significance level gives us a stable distribution of probabilities for each pair of nodes. 
