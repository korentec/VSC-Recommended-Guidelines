# Visual Studio Code (VSC) Recommended Guidelines

This document will show a recommended guidelines & extensions for proper web developing in VSC.

##  Topics

1. [Introduction](#introduction)

2. [Prerequisites](#prerequisites)

3. [Code Linters](#code-linters)
  3.1. [ESLint](#eslint)
  3.2. [TypeScript ESLint](#https://github.com/typescript-eslint/typescript-eslint)
  3.3. [Prettier](#prettier)
  3.4. [ESLint + Prettier Integration](https://dev.to/chgldev/getting-prettier-eslint-and-vscode-to-work-together-3678)

4. [Code Guidelines](#code-guidelines)
  4.1. [Airbnb Style Guide](#airbnb-style-guide)

5. [Recommended Extensions Reference](#recommended-extensions-reference)

6. [Summary](#summary)

---

## 1. Introduction

  As a web developer in Korentec and as a developer in general, we want to write quality code.
  Our code should be written according to the last languages ​standards, that updating frequently.
  We also have to keep the same rules whithin the team, for uniform code and conflicts prevention.
  In this document we will explore the tools that will help us to keep our code standards in the team.

---

## 2. Prerequisites

  * VSC IDE installed in your computer ([download](https://code.visualstudio.com/))

  * Basic knowlage in web development ([basic tutorial](https://developer.mozilla.org/en-US/docs/Learn))

---

## 3. Code Linters

  We useing code linters in our code to flag programming errors, bugs, stylistic errors, and suspicious constructs.
  With the accompanying libraries we can format our code according the linter guidelines.
  We can manage our linter rules by ourself and use some exist guidelines like [Airbnb Guidelines](#airbnb-guidelines).
  The linter configuration should works the same for each developer that works the same project code.
  The code fixing can run manual by command or run automatically on save or on commit.

### 3.1. ESLint

  ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs. In many ways, it is similar to JSLint and JSHint with a few exceptions. ([getting started with ESLint](https://eslint.org/docs/user-guide/getting-started))

### 3.3. Prettier

  A opinionated code formatter that support many languages and integrates with most editors.
  We will use it as a VSC extension and node dev dependency. ([prettier docs](https://prettier.io/))

---

## 4. Code Guidelines

  Coding guidelines help in detecting errors in the early phases, so it helps to reduce the extra cost incurred by the software project. 
  If coding guidelines are maintained properly, then the software code increases readability and understandability thus it reduces the complexity of the code.

### 4.1. Airbnb Style Guide

  There are some common JS style guides out there, we in Korentec chose to adopt the Airbnd style guide as the main JS code guidelines.
  You can extends its rules in the ESLint cofig file, course the rules can be overridden of course according to the need for the specific project.
  In the bottom linem, the project manager is the one to decide the rules for the relevant project. ([airbnb JS style guide](https://airbnb.io/javascript/))

---

# 5. Recommended Extensions Reference

  The table bellow list recommended VSC extensions to keep the code guidelines and help you developing in general. 

  | Name | Desc | Link |
  | ------ | ------ | ------ |
  | ESLint | Integrates ESLint JavaScript into VS Code | [link](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) |
  | Prettier | Prettier is an opinionated code formatter. It enforces a consistent style. | [link](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) |
  | Code Spell Checker | A basic spell checker that works well with camelCase code | [link](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) |
  | GitLens | Helps to mange the git repo | [link](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) |
  | Live Server | Launch a development local Server with live reload feature for static & dynamic pages | [link](https://marketplace.visualstudio.com/items?itemName=ritwickdey.liveserver) |

  \* There are many more good extensions, welcome to add here.

---

# 6. Summary

  
