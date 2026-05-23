---
abstract: |
    Decision Tree is a commonly used algorithm in **Supervised Learning**, for **Classification** and **Regression** tasks. It has the shape of a flowchart, each branch represents a question, and depends on your answer, you move on to the next step. It breaks downs complex datasets into more easy-to-interpret structures.
---

# Introduction to Decision Tree

![alt text](figures/tree_structure.png)

## What is a Decision Tree?
A decision tree is a machine learning model that helps make decisions by asking a series of simple questions.

It learns from examples that already have answers, and then uses those patterns to make predictions on new data.

## Structure of a Tree
A tree data structure, much like a real tree, grows from a root node and expands into multiple branches, with leaves at the ends.
- The root, unlike in nature, is positioned at the top and is considered an internal node. 
- Branches (internal nodes) have both incoming and outgoing edges, while leaves (external nodes) only have incoming edges.
- Any two nodes connected by an edge have a parent–child relationship, with the edge pointing from the parent to the child.
- Nodes that share the same parent are called siblings.

## How Decision Trees Work
Think of it like a guessing game:

Each branch asks a yes/no (or simple) question
Each answer takes you down a different path
You keep going until you reach a final answer at a leaf

## How to pick the smartest question for each branch?
