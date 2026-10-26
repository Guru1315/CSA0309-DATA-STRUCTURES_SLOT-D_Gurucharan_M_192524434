# Assessment Tool 2: Technical Presentation

Course: **Data Structures (CSA0309)**, SIMATS Engineering
Presented by: Guru Charan M, Reg. No. 192524434 (dated 09/10/2026)

| File | What it is |
|---|---|
| [`Data_Structures_Technical_Presentation.pptx`](Data_Structures_Technical_Presentation.pptx) | A 13-slide deck: title, questions, rubrics, introduction, four case studies with two slides each, and a closing slide |

## Purpose

Choose a data structure for four real-world computing tasks and justify each choice using the operations needed, time complexity and space complexity.

## The four case studies

| # | Task | Structure chosen | Why |
|---|---|---|---|
| 1 | Marks for 1,000 students | Array of `Student` records (`int` ID, name, `float`/`double` marks) | Indexed access or update is O(1); a scan for the average or a search is O(n); inserting or deleting in the middle is O(n) because elements shift. Simple and memory-efficient for a fixed-size list |
| 2 | City navigation | Weighted graph stored as an adjacency list (cities are vertices, roads are edges, distance or time is the weight) | Space is O(V + E), good for sparse road networks. BFS only suits equal edge costs, and negative weights need another algorithm such as Bellman-Ford |
| 3 | Browser Back button | Stack ADT (LIFO) | Push the current page when visiting, pop to go back. Push, pop and peek are O(1); space is O(h) for h history entries |
| 4 | ISBN search among 50,000 books | Hash table keyed by ISBN, with chaining or open addressing for collisions | Expected O(1) lookup, against O(n) for an unsorted list and O(log n) (about 16 comparisons) for a balanced search tree |

## Slide outline

1. Title
2. Questions
3. Rubrics
4. Introduction
5. Question 1: Student marks management
6. Question 1: Efficiency justification
7. Question 2: City navigation system
8. Question 2: Efficiency justification
9. Question 3: Browser back navigation
10. Question 3: Efficiency justification
11. Question 4: Digital library ISBN search
12. Question 4: Time complexity comparison
13. Thank you

The Questions and Rubrics slides (2 and 3) carry their content as images, so open the deck to read them.

Back to [Unit 1](../README.md).
