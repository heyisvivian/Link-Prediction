# Link-Prediction
Goal: Predicting missing links in an actor co-occurence network. Edges have been deleted at random from a graph. Your mission is to accurately reconstruct the initial network using both graph-theoretical and node feature information.

In this competition, we define an actor network where nodes represent actors and edges between two nodes stand for co-occurrence on the same Wikipedia page. This is a proxy for their joint participation in the same movie, for their personal relation, for their level of fame, etc. In addition to the graph structure, each node (i.e., actor) is also associated with textual information processed from its Wikipedia page, from which some keywords were extracted. Only the processed features are available here. Your goal is to utilize information from both the underlying actor network and the processed Wikipedia description in order to accurately predict missing edges.

