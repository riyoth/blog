+++
title = "Refactoring Checklist"
date = 2024-06-26T13:38:50-04:00
images = []
tags = []
categories = ["development"]
draft = false
+++

Refactoring is a critical part of writing software and should be encourage. Good test make the process much easier.

### Definition

During a refactoring you will improve a pieces of codes without changing it's behavior. Improving code can take multiple form. You can refactor to improve performance, readibility, remove a deprecated library or make the code easier to test.

A few rules to follow when refactoring:
 - A refactoring shouldn't change the behavior. 
 - You shouldn't change the method/function signature. 
 - The tests shouldn't change.

### When to refactor

When should you refactor your code. The easy answer is all the time but that not always possible. In the Test driven development world it's a integral part of writing software. The process goes as follow:
 - Write test
 - Write code to make the test pass
 - Refactor your code

It's a good process for new code but we don't always write new code. You refactore to cleanup your code for the next persons.  For existing code, refactore before a big change to make the change easier.

### The Check list:

Follow those step to make your refactoring easier:
- Start with a commit, for easy revert
- use in-line variable instead of declaring variable only to pass it to a function
- Don't repeat yourself (but don't do it too much)
- Extract "Magic" values
- Make public function easy to scan, extract specification in private method
- Move value creation to construction time, 
- Try to remove comment, make the code easier to understand


### Refactoring excerices

- [Gilded Rose](https://github.com/emilybache/GildedRose-Refactoring-Kata)
