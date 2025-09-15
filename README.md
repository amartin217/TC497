EECS 280 Euchre Project

This project is a C++ implementation of the card game Euchre.

❓ What it does: Allows two teams of players (human or computer) to play a full game of Euchre.

👩‍💻 Who it’s for: Students learning C++ fundamentals such as object-oriented design, polymorphism, operator overloading, and unit testing.

🤷‍♀️ Why it exists: Developed as a  project for Michigan EECS 280 (Programming and Intro Data Structures), this project integrates multiple course concepts into one larger system.


## Table of Contents
- Quickstart Guide
- Features
- Architecture Overview
- Usage Examples
- FAQ
- Dependencies
- Contributing
- Acknowledgements
## Quickstart Guide

#### Prerequisites
- C++ compiler supporting C++11 or later (e.g., g++, clang++)
- make for build automation

#### Installation
- Clone the repository:

```bash
git clone https://github.com/amartin217/p3-euchre.git
cd p3-euchre
```

- Build the project:

```bash
make euchre.exe
```

- Run the game:

```bash
./euchre (parameters here)
```

Example Run:
![Demo](Sequence%2003.gif)


## Features

#### Card & Deck System:
- Full 24-card Euchre deck (pack class)
- Shuffling, dealing, and operator-overloaded comparison

#### Player Types:
- Human player (command-line interaction)
- AI "Simple" player (follows basic heuristic rules)

#### Gameplay Mechanics:
- Trump selection & ordering up
- Trick-taking logic
- Team scoring

#### Testing:
- Unit tests for Card, Deck, and Player classes


## Architecture Overview

Euchre Project Architecture Diagram:
![Demo](Untitled%Diagram.drawio)
