---
abstract: |
    Decision Tree is a commonly used algorithm in **Supervised Learning**, for both **Classification** and **Regression** tasks. It has the shape of a flowchart, each branch represents a question, and depends on your answer, you move on to the next step. It breaks downs complex datasets into more easy-to-interpret structures.
---

# Introduction to Decision Tree

Decision trees are fundamental machine learning models and also serve as building blocks for more advanced methods such as **Random Forests** and **Gradient Boosting Machines**.

## Structure of a Tree
A tree data structure, much like a real tree, grows from a root node and expands into multiple branches, with leaves at the ends.
- The root, unlike in nature, is positioned at the top and is considered an internal node. 
- Branches (internal nodes) have both incoming and outgoing edges, while leaves (external nodes) only have incoming edges.
- Any two nodes connected by an edge have a parent–child relationship, with the edge pointing from the parent to the child.
- Nodes that share the same parent are called siblings.
- Tree depth: the number of edges from the root node to it furthest leaf.

## What is a Decision Tree?
A decision tree is a flow chart that helps make decisions by asking a series of simple questions, it is used for both Classification and Regression tasks. What this simply means is that it can be used to predict categorical data (like Dog or Cat), but it can also be used to predict a number (like housing prices). These 2 tasks essentially have the same structure, but with different output.

Below is an example of a Decision Tree used for Classification, helping you decide which mode of transportation to take today. As shown in the figure, there are 4 things notable here:
- Each internal node must have at least 2 children
- The same tree can have mixed data types: numerical data and categorical data.
- Numerical thresholds can be different for the same data.
- Final outcome can be repeated.

**Note**: Although categorical data in Decision Trees can include more than two classes, the following chapters will focus only on binary (two-class) cases for simplicity.

![alt text](figures/tree_structure.png)

## How does a Decision Tree work?
Think of it like a guessing game, and if you've ever played this game before, you'll know that the smartest approach is **NOT** to begin with any specific guess but rather a question that cuts the possibilities in half. 

For example, if I ask you to guess a famous person I’m thinking of, a question like “Are they a woman?” eliminates far more options than something specific like “Is it Michael Jackson?”.

Similarly, when building a Decision Tree, each branch should choose a question that would give it the most information possible, using the data it already has. This way, you'll able to reach the answer much faster.

### How do we pick the smartest question for each branch?
The tree is basically an optimizer. It tries different features and thresholds, then eventually picks the question that reduces the most **uncertainty**. This is usually mathematically measured using criteria like **Entropy**, **Gini impurity**, or **Misclassification error**, and is selected through **Information gain**.

A much deeper dive on these criteria will be discussed in our next chapter.
