# Supply and Restocking Routes

## Context

The bookstore has multiple warehouses and stores. During sales periods, stores can run out of books and need to be restocked as soon as possible. 

## Problem Statement

Determine the minimum-cost route between warehouses and a specific bookstore to restock books efficiently. 

## Resolution

The network of warehouses and bookstores is modeled as a **graph**, where the buildings are represented as nodes and the routes between them as edges. Each edge has a weight that represents the time required to move books between locations.

The restocking process is modeled as a shortest path problem and is solved using **Dijkstra's algorithm**.