# Tree
# tree = Node(..., children=[Node(...., ...), Node(...,....)])

## Introduction

The tree is a non-linear data structure that is unlike Linked list and Stack.

## Description

Trees are made up of Parents, Children, Nodes, Different levels and other things. Trees can be wide, meaning that each node has many children. And trees can be deep, meaning that there are many parent-child connections with few siblings per node. A tree also is a data structure made up of nodes and used to store hierarchical data. Each tree node typically stores a value and a reference to its child nodes.

### Example 

class Node:
   def init(self, data):
      self.left = None
      self.right = None
      self.data = data
   def PrintTree(self):
      print(self.data)

root = Node(10)
root.PrintTree()


