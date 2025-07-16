## Decision Trees

Suppose you're launching a startup that grows and sells wild mushrooms.
There's an issue: some mushrooms are poisonous. You need to build a system that can classify whether a mushroom is edible or poisonous based on its physical characteristics.

You already have a small dataset of mushrooms with known features and whether they’re safe to eat. With this, you can build a Decision Tree model to help make accurate classifications for new mushrooms in the future.

Steps for building a decision tree:
 - Start with all examples at the root node
 - Calculate information gain for splitting on all possible features, and pick the one with the highest information gain
 - Split dataset according to the selected feature, and create left and right branches of the tree
 - Keep repeating splitting process until stopping criteria is met

We'll implement the following functions, which will let us split a node into left and right branches using the feature with the highest information gain

 - Calculate the entropy at a node
 - Split the dataset at a node into left and right branches based on a given feature
 - Calculate the information gain from splitting on a given feature
 - Choose the feature that maximizes information gain


<img width="956" height="450" alt="Screenshot 2025-07-16 at 12 26 45" src="https://github.com/user-attachments/assets/e7dacbce-73e9-49ff-ad9c-429aa4c4bf6a" />
