[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/T6sJM4w6)
# Week 5 — Midnight Mail Train

## Summary
This assignment focuses on implementing a doubly linked list, recursion, and basic string and validation problems. It simulates a train system where cars are added and removed, ticket codes are validated, and radio messages are cleaned.

## Approach

- Problem 1:
  Implemented a doubly linked list using nodes with `prev` and `next` pointers. Handled edge cases like empty list, single node, and multiple nodes.

- Problem 2:
  Checked ticket codes using string methods. Ensured format starts with "MM-" and ends with exactly 4 digits.

- Problem 3:
  Used recursion to count occurrences of a target label in a list by breaking the list into smaller subproblems.

- Problem 4:
  Used recursion to remove spaces from a string by processing one character at a time.

## Complexity

- append_car:
  Time: O(1), Space: O(1)
  Reason: Direct insertion at tail.

- detach_last_car:
  Time: O(1), Space: O(1)
  Reason: Direct removal from tail pointer.

- to_reverse_list:
  Time: O(n), Space: O(n)
  Reason: Traverses all nodes once.

- is_valid_ticket_code:
  Time: O(1), Space: O(1)
  Reason: Only checks fixed parts of string.

- count_priority_labels:
  Time: O(n), Space: O(n)
  Reason: Recursively processes each label once.

- clean_radio_message:
  Time: O(n), Space: O(n)
  Reason: Recursively processes each character.

## Edge-case checklist

- [x] empty train
- [x] one train car
- [x] invalid ticket code
- [x] empty label list
- [x] empty message
- [x] one-character or all-space message

## Assistance & Sources

- AI used? Y
- What it helped with: Understanding linked lists, recursion, debugging test cases, and writing README structure.
- Other sources used: Lecture slides and class notes