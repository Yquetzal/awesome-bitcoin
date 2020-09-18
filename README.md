# awesome-bitcoin analysis and mining


## Graph analysis

#### Do the rich get richer? an empirical analysis of the bitcoin transaction network.
#### Quantitative analysis of the full bitcoin transaction graph
#### The evolving liaisons between the transaction networks of bitcoin and its price dynamics
#### Bitcoin transaction networks: an overview of recent results


## Miscellaneous Data Analysis

#### Towards open data blockchain analytics: a bitcoin perspective
#### Data-driven analysis of price change, user behavior and wealth ac- cumulation in bitcoin transactions
#### Mining blocks in a row: A sta- tistical study of fairness in bitcoin mining

## Transaction Forecasting (how likely two addresses are of having a transaction in the future)

#### Bitcoin Transaction Forecasting with Deep Network Representation Learning
(Graph embedding)
Use random-walk based mechanism to generate a representation (embedding) of addresses (not actors). These embeddings can be used as input of a neural networks for some tasks.

we build the time-decayed reachability graph to represent the inter-account transaction reachability
time-decayed transaction amount graph to repre- sent the inter-account transaction Bitcoin amount
The second stage of DLForecast development is to utilize node embedding [5] to map the transaction account rela- tions into a condensed vector space
The goal is to link the current transaction pattern (in the form of embedding) between two accounts to the probability of the transaction
The third and final stage of the DLForecast development is to combine multiple transaction pattern graphs con- structed using different types of extracted features

Motivated by [31], we represent the dynamic graphs as a collection of snapshots, apply static embedding algorithms to each snapshot, and update the resulting static embedding across time steps.

we do not verify the ownership of the addresses but only use the address graph to forecast transactions.

## Illegal/Anomalous transaction detection



#### Identification of Darknet Markets' Bitcoin Addresses by Voting Per-Address Classification Results

#### A Study of Bitcoin De-Anonymization: Graph and Multidimensional Data Analysis
https://ieeexplore.ieee.org/abstract/document/9172832
Classic clustering methods, then Illegal transaction detection.

#### Anomaly detection in the bitcoin system - a network perspective

#### Unsupervised learning for robust bitcoin fraud detection

#### A multifaceted approach to bitcoin fraud detection: Global and local outliers

### Elliptic dataset for illicit transaction detection

#### Anti-Money Laundering in Bitcoin: Experimenting with Graph Convolutional Networks for Financial Forensics
(Various ML techniques, including GCN)
Based on an existing dataset, subnetwork with many features, predict if a transaction is legit or not (ground truth from this dataset, provided by a company)
The Elliptic Data Set, a graph network of Bitcoin transac- tions with handcrafted features
203,769 node transactions and 234,355 directed edge payments flows
We  tested standard classification models for the licit/illicit prediction

#### Machine learning methods to detect money laundering in the bitcoin blockchain in the presence of label scarcity
#### Comparative analysis using supervised learning methods for anti-money laundering in bitcoin.
#### Discerning payment patterns in bitcoin from ransomware attacks

### Ponzi Scheme

#### Data mining for detecting bitcoin ponzi schemes

## Actor (clusters of addresses) role identification  

#### Breaking Bad: De-Anonymising Entity Types on the Bitcoin Blockchain Using Supervised Machine Learning
The data provider has clustered, identified and categorised a substantial number of Bitcoin addresses manually or through a variety of clustering techniques (sec. 4).

#### Cascading Machine Learning to Attack Bitcoin Anonymity

## Addresses de-anonymization (actor discovery)

#### BITSCOPE: Scaling Bitcoin Address De-anonymization using Multi-Resolution Clustering
https://blog.zhen-zhang.com/bitscope-public/paper.pdf

#### UNMASKING USER IDENTITIES BY CLUSTERING ADDRESSES AND ANALYZING BEHAVIOR RELATED TO BLOCKCHAIN TRANSACTIONS
https://calhoun.nps.edu/handle/10945/64927
Uses temporal activity patterns to associate addresses to actors.



