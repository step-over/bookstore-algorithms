# Representing categories

# Context

As new books arrive to the bookstore, the catalog not only increases in size but also in variety. To better organize the stock, books are classified into **categories** and **subcategories**. Workers need to add new categories without reorganizing everything and be able to easily traverse the structure to display the entire catalog. 

# Problem Statement

The bookstore needs a data structure that can represent categories and subcategories in a hierarchical way, allowing new categories to be added as the catalog grows. Using a simple array is not suitable for this type of hierarchical representation.

# Resolution

A **tree structure** is used to model the catalog categories. This allows hierarchical relationships to be represented naturally and enables traversal of the entire catalog using Depth-First-Search (DFS).