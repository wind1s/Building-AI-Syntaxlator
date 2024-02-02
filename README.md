# Syntaxlator

Final project for the Building AI course

## Summary

Syntaxlator is a AI tool designed to solve the challenge of translating code between programming languages. It streamlines the process of code migration by allowing automation and manual review of translations.

## Background

During software development, the need to migrate code between different programming languages comes up frequently. This task is resource intensive, error-prone and time-consuming. It often leads to bugs and compatibility issues. Syntaxlator addresses this problem by providing a reliable solution for translating code snippets.

* **Problem 1:** Manual code translation is prone to errors and can result in functionality issues.
* **Problem 2:** Existing code translation tools may not handle specific language quirks.
* **Problem 3:** Adoption of new programming languages requires efficient code migration solutions.

## How is it used?

Users input a code snippet in the source language, specify the target language, and Syntaxlator generates the translated code with the option to manually review translations. Either entire code files or certain snippets in code can be supplied for translation. 

## Data sources and AI methods

Syntaxlator leverages a curated dataset of code snippets in various programming languages. This is to ensure accuracy and reduce possible introductions of errors and incorrect translations. For gathering data, open source projects from GitHub is the primary resource for data as there are many similar projects done in different languages. 
Also for realizing the translation, [OpenNMT](https://opennmt.net/) is used which is a popular tool for machine translation. 

## Challenges

While Syntaxlator can translate standard code structures, it can encounter challenges with highly specialized or domain-specific code. Additionally, ensuring the translated code follows best practices and becomes as efficient before translation is a large challenge.

## What next?

To enhance Syntaxlator, future developments includes:

* Support for a broader range of programming languages like less popular languages.
* Integration of code analysis tools to optimize translated code helping translated code follow best practices and avoid code smells.
* Collaboration with domain experts to improve translation accuracy for specialized code like hardware specific drivers.

## Acknowledgments
Open-Source community
OpenNMT: https://opennmt.net/
Elements of AI: https://www.elementsofai.com/

