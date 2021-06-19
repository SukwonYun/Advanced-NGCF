# Advanced-NGCF

# Abstract
In this paper, we propose an advanced version of Neural Graph Collaborative Filtering in the perspective of time sampling. At first, by using side information such as social relationships and item ID, we suggest an advanced version of Heterogeneous Graph Neural Recommender (HGNR). Moreover, we adopted Agglomerative
clustering methodology to effectively capture user’s group information. In the case where side information as social data is unobtainable, we instead made use of time information effectively. Existing models did not sufficiently use time information on their model which might cause a big problem when a sequence of its data becomes crucial. Unlike static graphs in a recommender system, we propose Weight Sequence Neural Graph (WSNG) model which is a dynamic graph that utilizes GRU to efficiently capture historical interactions between a user and the item. In Epinion dataset, WSNG outperforms existing methods by a significant margin.

# Model
<img src="https://user-images.githubusercontent.com/68312164/122628793-451b9d00-d0f3-11eb-845e-588bf3a66461.png"  width="350" height="320">
<img src="https://user-images.githubusercontent.com/68312164/122629093-5e254d80-d0f5-11eb-9c06-f6f70fcdb93b.png"  width="350" height="320">
<img src="https://user-images.githubusercontent.com/68312164/122628825-801dd080-d0f3-11eb-8faa-3c5b65c5881c.png"  width="350" height="320">


# Experiment
<img src="https://user-images.githubusercontent.com/68312164/122628848-aa6f8e00-d0f3-11eb-81f5-b8843cffec8c.png"  width="420" height="400">


