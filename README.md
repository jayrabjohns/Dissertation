# SPCF: Interpreter Development and Affine Program Transformation Showcase

This project is submitted as part of my dissertation while studying at the University of Bath.

The code for the project can be found here: https://github.com/jayrabjohns/dissertation-refactoring-spcf

## Abstract
We explore the concept of function denesting in SPCF, a derivative of typed $\lambda$-calculus with non-local control. Function nesting involves sharing variables from one function’s scope with another function's arguments. This transformation is based on the work of Laird who provides denotational semantics for a retraction on terms of a higher type into a lower one, and can be seen as rewriting programs to adhere to affine typing rules. We illustrate this transformation working in the real world and evaluate its benefits. 

As part of the project we also build and release an interpreter for SPCF, a language that currently lacks one which is widely available. This both has the focus of illustrating the denesting action working, as well as contributing to the language’s ecosystem, hopefully making it easier to experiment with the language.