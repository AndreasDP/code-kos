# Code QOS

## Description

This is a project that reviews a GitHub Pull Request for general code quality.

This is project is still in its early stages and is a work in progress. This document can change at any time.

The process will follow the Double Diamond design process model.

## Discover

### Problem Statement

As a developer, I want to ensure that my code is of high quality and adheres to best practices, so that I can maintain a clean and efficient codebase.
I have noticed that code quality can vary significantly between different contributors, leading to inconsistencies and potential issues in the codebase.
I want a tool that can automatically review my code and provide feedback on areas that need improvement, so that I can learn and grow as a developer.

Problems that I have identified:
  - Inconsistent coding styles
  - Naming conventions not followed
  - Lack of best practices
  - Poorly written or unclear code
  - Lack of documentation or comments
  - Performance issues
  - Missing tests or inadequate test coverage

### Alternatives / Existing Solutions
There are several existing tools that does exactly this, but most of them are paid solutions.
It would be ideal if we can build something in-house that is free to use, using as much open-source software as possible.



# Scratch Pad

This is a scratch pad for ideas and notes

The project should be configurable to allow users to customize the rules and checks according to their specific needs and preferences.
For now, this will be specific to JavasScript and Apex codebases.

Technologies to use:
  - Node.js Scripts
  - Shell Scripts
  - AWS CodeBuild

## Technology Usage Area

### AWS CodeBuild
We already use AWS CodeBuild for our CI/CD pipeline using Infrastructure as Code.
We already run numerous Node.js scripts, so we can add additional scripts to check for code quality.

### Node.JS Scripts
Write scripts to:
  - Check for coding style consistency (Prettier) - Done
  - Check for best practices (ESLint)
  - 

### Shell Scripts
Write scripts to:
  - TODO (more complex scenarios)



### To investigate
  - https://pmd.github.io/
  - https://snyk.io/
  - https://www.sonarsource.com/products/sonarqube/