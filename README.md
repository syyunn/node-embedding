# node-embedding
Logs of visited/tried/read node embedding techniques
## Usages
node classification, node recommendation, link prediction, node clustering, node retrieval/recommendation
## On Heterogenous graph data
[metapath2vec](https://ericdongyx.github.io/papers/KDD17-dong-chawla-swami-metapath2vec.pdf)

metapath2vec was proposed by incorporating metapaths with node semantics for node embedding learning. However, this approach has several drawbacks: 

1) domain knowledge is required
to define metapaths and those mentioned in are symmetric paths which are unrealistic in many applications;

2) metapath2vec does not consider edge types rather only
node types; and 

3) metapath2vec can only consider one
metapath at one time to generate random walk, it cannot consider all the metapaths at the same time during
random walk


## Goal
What is the good embedding of the nodes embedding?
Interaction are just exists or not, binarily dropping more semantic relational data, then what determined the nodes good embedding? In us lobby network, each actors without semantic relation considered, what determines the unique characteristic of their own? The node embedding should bundle those "unique" nodes' characteristic that might be disentangled and irrelevant from their interactions. We need to answer this question before starts on embedding.
