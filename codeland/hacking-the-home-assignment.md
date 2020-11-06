---
description: Second session on 07/24/20
---

# Hacking the Home Assignment

> **Eyal Yavor \(presenter\)**
>
> **Bogdan Covrig \(proctor\)**

## Why Talk About Home Assignments?

You can refuse to work on an assignment that seems to be excessive or before you even have a phone call with the company.

### Red Flags

* Sending you a .psd file
* Using your code as theirs
* Crazy scope for a junior position

Working Effectively with Legacy Code --&gt; a recommended book

Real name for workshop: "Working Like a Professional, Even for Short Projects"

## Our Home Assignment

{% embed url="https://github.com/yulkes/PublicSpeaking/blob/master/HackingTheHomeAssignment/SampleHomeAssignment.md" %}

## Analyze First

* Ask question
* Outline how you will tackle the project
  * Outline edge cases and how you would respond to them
* It's okay to send back partial work
* It's okay to spend more time than the company says to take, just don't get carried away
* Reading assigned reading or documentation can save you **tons** of time in coding

## Project Structure & Tech Choices

* Use latest version of your best-known language
* Start from a template
  * Cookiecutter
  * Create-react-app
  * https://start.spring.io/
  * Google: &lt;language&gt; &lt;web framework&gt; project template
* Minimum files at directory root
  * Organize under `app/src`, `tests`, `static`, `config`
* Strict requirements: filenames, classes, functions
* Optionals and nice-to-haves

## Version Control

* Git is global \(GitHub is free\)
* Complete code
* Show progress
* `.gitignore`
  * Add your IDE's files to your `.gitignore` file \(i.e.: `.vsc` directory\)
  * Templates: [https://github.com/github/gitignore](https://github.com/github/gitignore)

## Code Structure & Design

* Code architecture — Model, View, Controller \(MVC\)
* Layer separation
  * REST layer
  * Class for every outside interaction: Filesystem, DB, 3rd party API
  * Your own model classes between the REST layer and service wrapper
* Data types: Beyond strings and ints
* Multiple files
* Code style: Linter, autoformatters
  * Beautify
  * black
* Limits and constraints

## Testing

### The Test Pyramid

* Multiple unit tests
  * Catch errors
  * Different parameters and failures
  * High value for you
* Few integration tests
  * Combination of components
  * Subsystem interaction
* One-two end-to-end tests
  * Sanity
  * Internal or external
  * High value for reviewers

## Environment Reproducibility

* Docker is the leading tool for sharing environments
* Your code runs in isolated containers on the reviewer's machine

## Documentation

* It's never well-defined what's expected here
* Current functionality
* Code structure
* Assumptions and limitations
* Important commands
* What it doesn't do at the moment:
  * Which of the functional requirements you've missed
  * Which non-functional requirements you think would've made sense, but aren't included

For each requirement that you've missed, in case you're called back for a follow-up, have an explanation ready in mind on how you'd implement it.

## Packaging & Distribution

* Remove unused files and code
* Remove `print()` and debug statements
* Makefile for commands
  * Learn on [https://makefiletutorial.com](https://makefiletutorial.com/)
  * For frontend use something like yarn
* Clean up your zip files
* Follow the given instructions
* Send and ask for receipt confirmation

## Hacking the Home Assignment Checklist

{% embed url="https://gumroad.com/l/nyrpqZ" %}

{% file src="../.gitbook/assets/hacking-the-home-assignment-checklist.pdf" caption="Downloadable PDF" %}



