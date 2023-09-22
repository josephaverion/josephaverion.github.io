---
layout: essay
type: essay
title: "The Essence of Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2023-09-21
published: true
labels:
  - Coding Style
  - Collaboration
---

<img width="350px" length="622px" class="rounded float-start pe-4" src="../img/coding-style/collaborating-on-codebase.png">

In software development, the ways one writes their code, often called coding standards, are a big deal. While some might find coding standards annoying due to always making sure to check the indents or spacing in their code or where they put certain symbols, they're actually much more important than one may think. Developers must be able to adapt and follow coding standards because they make code more readable and help you learn programming.

## Learning Through a Standard

Coding standards serve as valuable learning tools for mastering programming languages. Encountering diverse codebases written in various styles can be overwhelming, especially for those just starting their programming journey. However, when code is given and tasks are told to be done with a set of coding rules, the learning curve becomes less steep. The code you read and write will be more organized, so you focus on the syntax on the code instead of wondering why a “{“ is on a separate line in one problem while another “{“ isn’t in another problem.

## Improved Collaboration

In a team environment, you will encounter code written by others, or write up code together. This is especially true for large projects in companies where there are numerous developers working on the same codebase. To ensure readability, everyone on the team must maintain the same coding standard. Imagine a scenario where each team member follows their own coding style. Some use tabs for indentation, there's a mix of curly brace placements, and others use spaces between operators. Reading such a codebase would be similar to reading a book where every chapter follows a different writing style or structure. Interpreting these variations can significantly slow down the development process and introduce room for errors. With a consistent coding standard, developers can work on different sections of the project without having to mentally switch between them.

## How to Get Used To a Coding Standard

With the awareness of the benefits of following a coding standard, developers could use the ESLint plugin to get used to one. ESLint is a plugin that signals us if the code is not adhering to a specific coding standard. You can either let it be a warning or an error. In my ICS314 class we are required to set ESLint to tell the compiler that it is an error for not following coding standard. In my opinion it can be annoying, but it help people adapt to a coding standard. As stated earlier, being consistent in a certain coding standard is a crucial skill for software development. ESLint helped me to be consistent to one by giving me errors to not allow my code to run when I don't follow the coding standard. I don't want to encounter errors, so with ESLint on I subconsciously get more used to making sure ESLint doesn’t cause errors. Thus, I get more adpated to the coding standard ESLint was set to.