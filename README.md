# ESLint Practice Project

## Overview
This project demonstrates how to set up and configure ESLint in a Node.js environment to enforce consistent code style and identify potential issues early in development.

The project focuses on initializing ESLint, customizing linting rules, and running ESLint on JavaScript files.

---

## Project Setup

### 1. Initialize Node.js Project
A new Node.js project was created using:
bash 
npm.init

2. Install and Configure ESLint
ESLint was installed and configured using:
npx eslint --init

During the setup process, the following options were selected:
JavaScript files
CommonJS modules
No framework
No TypeScript
Node.js environment
npm as the package manager

This created the ESLint configuration file:
eslint.config.mjs

The ESLint configuration was reviewed and customized to enforce consistent coding style. The following rules were added:
Semicolons are required
Single quotes are enforced for strings
Example rule configuration:
rules: {
  semi: ["error", "always"],
  quotes: ["error", "single"]
}

A JavaScript file (mikelint.js) was created with intentional style errors. ESLint was run using:
npx eslint mikelint.js


   









