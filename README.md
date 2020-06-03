# Visual Studio Code (VSC) Recommended Guidelines

This document will show a recommended guidelines for proper web developing in VSC.

##  Topics:

1. [Introduction](#introduction)

2. [Prerequisites](#prerequisites)

3. [Code Linters](#code-linters)
  3.1. [ESLint](#eslint)
  3.2. [TypeScript ESLint](#https://github.com/typescript-eslint/typescript-eslint)
  3.3. Prettier
  3.4. ESLint + Prettier Integration

4. Code Guidelines
  4.1. Code Quality
  4.2. Airbnb Guidelines

5. Recommended Extensions Reference

---

## 1. Introduction:

  As a web developer in Korentec and as a developer in general, we want to write quality code.
  Our code should be written according to the last languages ​standards, that updating frequently.
  We also have to keep the same rules whithin the team, for uniform code and conflicts prevention.
  In this document we will explore the tools that will help us to keep our code standards in the team.

---

## 2. Prerequisites:

  * VSC IDE installed in your computer ([download](https://code.visualstudio.com/))

  * Basic knowlage in web development ([basic tutorial](https://developer.mozilla.org/en-US/docs/Learn))

---

## 3. Code Linters:

  We useing code linters in our code to flag programming errors, bugs, stylistic errors, and suspicious constructs.
  With the accompanying libraries we can format our code according the linter guidelines.
  We can manage our linter rules by ourself and use some exist guidelines like [Airbnb Guidelines](#airbnb-guidelines).
  The linter configuration should works the same for each developer that works the same project code.
  The code fixing can run manual by command or run automatically on save or on commit.

### 3.1. ESLint:

  ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs. In many ways, it is similar to JSLint and JSHint with a few exceptions. ([getting started with ESLint](https://eslint.org/docs/user-guide/getting-started))

---