# Tournament Management System

## Overview

This project is a tournament management system designed to manage players, teams and different types of tournaments.

The system allows a tournament manager to register participants, create tournaments, manage registrations, record match results and update player rankings using an Elo rating system.

The project was designed using object-oriented principles and includes UML diagrams that describe the system requirements, domain model, class structure and main interactions.

## Main Features

- Register individual players
- Register teams
- Search and consult player information
- Create individual or team tournaments
- Select the tournament modality
- Register players or teams in open tournaments
- Automatically create matches when the tournament reaches the required number of participants
- Record match results
- Update player Elo ratings
- Consult open tournaments
- Cancel tournaments

## Main Concepts

The system is based on the following main entities:

- **Player** – represents an individual participant and stores information such as name, registration number and Elo rating.
- **Team** – represents a group of players participating together.
- **Tournament** – contains the tournament configuration, modality, participants and matches.
- **Match** – represents a game between two players or teams.
- **Registration** – connects a participant to a tournament.
- **Modality** – represents the type of activity or competition.
- **Elo System** – updates player rankings according to match results.

## System Workflow

A typical tournament workflow is:

1. A manager creates a tournament.
2. The tournament type, modality and configuration are selected.
3. Players or teams are registered in the tournament.
4. When the maximum number of participants is reached, registrations are closed and the matches are created.
5. The manager records the results of each match.
6. Player rankings are updated through the Elo rating system.

## Documentation

The repository includes system analysis and design documentation, such as:

- Domain model
- Use case diagram
- System sequence diagrams
- Operation contracts
- Interaction diagrams
- Class diagram

## Project Status

This repository contains the design and implementation of the main tournament management functionalities. Additional features and improvements may be added in the future.
