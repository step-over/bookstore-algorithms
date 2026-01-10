# Organizing the catalog

## Context 

A bookstore needs to organize its catalog before a high-demand sales event. Each book is identified by a unique `bookID`. Since the catalog contains a large number of entries, inefficient sorting could lead to long processing times and delays.

## Problem Statement

Given a list of books, sort them by bookID in ascending order.

## Resolution

Merge Sort is used because it provides reliable performance on large datasets and guarantees a time complexity of `O(n log n)`, making it proper for handling large catalogs. 