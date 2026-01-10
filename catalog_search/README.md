# Finding a book in catalog

## Context

During high-demand sales, bookstore workers need to quickly locate books in the catalog using their `bookID`. The catalog is already sorted in ascending order from a previous processing step.

## Problem Statement

Given a sorted list of books, efficiently locate a specific book by its `bookID`

## Resolution

**Binary search** is used to significantly reduce lookup time, improving the search complexity from `O(n)` (linear search) to `O(log n)`. This makes book retrieval much faster.