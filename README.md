# awesome-bitcoin

##Transaction Forecasting (how likely two addresses are of having a transaction in the future)
###Graph embedding
####Bitcoin Transaction Forecasting with Deep Network Representation Learning

Use random-walk based mechanism to generate a representation (embedding) of addresses (not actors). These embeddings can be used as input of a neural networks for some tasks.

we build the time-decayed reachability graph to represent the inter-account transaction reachability
time-decayed transaction amount graph to repre- sent the inter-account transaction Bitcoin amount
The second stage of DLForecast development is to utilize node embedding [5] to map the transaction account rela- tions into a condensed vector space
The goal is to link the current transaction pattern (in the form of embedding) between two accounts to the probability of the transaction
The third and final stage of the DLForecast development is to combine multiple transaction pattern graphs con- structed using different types of extracted features

Motivated by [31], we represent the dynamic graphs as a collection of snapshots, apply static embedding algorithms to each snapshot, and update the resulting static embedding across time steps.

we do not verify the ownership of the addresses but only use the address graph to forecast transactions.

##
####Competence of Graph Convolutional Networks for Anti-Money Laundering in Bitcoin Blockchain
