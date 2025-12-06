# DFA Simulator

A simple web-based tool to **build**, **visualize**, and **test** Deterministic Finite Automata.  
It enables you to create states, define transitions, set final states, and evaluate input strings based on the DFA you design.

## Description

A *Deterministic Finite Automaton* or *DFA* is a fundamental computational model used to recognize patterns in strings.  
It processes an input string **one character at a time**, transitioning between states according to predefined rules.

This simulator provides an interactive environment to construct DFA diagrams and test custom input strings to determine whether they are **accepted** or **rejected**.

## Rules for Creating a DFA

A valid DFA must follow these properties:

- Each input symbol leads to **exactly one** next state from any given state.
- The DFA **cannot change state** without reading an input symbol.
- A DFA may contain **multiple accepting states**.
