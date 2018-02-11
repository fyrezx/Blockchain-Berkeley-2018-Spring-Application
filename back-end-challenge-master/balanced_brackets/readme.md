# Balancing Brackets
## Introduction
A bracket is considered to be any one of the following characters:
(, ), {, }, [, or ].d

Two brackets are considered to be a matched pair if the an opening bracket
(i.e., (, [, or {) occurs to the left of a closing bracket
(i.e., ), ], or }) of the exact same type.

There are three types of matched pairs of brackets: [], {}, and ().

A matching pair of brackets is not balanced if the set of brackets it
encloses are not matched. For example, {[(])} is not balanced because the
contents in between { and } are not balanced. The pair of square brackets
encloses a single, unbalanced opening bracket, (, and the pair of
parentheses encloses a single, unbalanced closing square bracket, ].

## The Problem
By this logic, we say a sequence of brackets is considered to be balanced
if the following conditions are met:

- It contains no unmatched brackets.
- The subset of brackets enclosed within the confines of a matched pair of
brackets is also a matched pair of brackets.

Given n strings of brackets, determine whether each sequence of brackets
is balanced. If a string is balanced, print `YES` on a new line; otherwise,
print `NO` on a new line.

## Running Tests
Run tests by opening a terminal and typing `python3 test_balanced.py`.

Writing your own tests is not required but highly recommended. All that matters is you pass our internal test cases.