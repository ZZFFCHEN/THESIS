# Model inputs and targets preparation
Each model input data has following shape: sequence length(here we set as 20 days), the maximum city node number, node features. Note that the node feaures cover following parts: Node ID, traffic volumes in 4 different directions, target labels and subgraph numbers.<br>

Targets have this shape: predicion lengh(here we assume as 10 days), the maximum city node number, node feaures. The features here are different to inputs' features and cover Node ID, traffic volumes in 4 different directions and target labels

 Target label: if a node belongs to city one, its target label is zero otherwise other numbers<br>
 Subgraph number: if a node belongs to the n-th subgraph for a certain city, its subgraph number is n.
