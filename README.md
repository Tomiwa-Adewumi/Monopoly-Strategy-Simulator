# Monopoly Strategy Simulator

Monopoly Strategy Simulator is a Java-based simulation of the classic board game Monopoly. The project implements various player strategies to analyze their effectiveness in competitive gameplay.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Implemented Strategies](#implemented-strategies)
4. [Experiment Design](#experiment-design)
5. [Results and Analysis](#results-and-analysis)
6. [Technologies Used](#technologies-used)
---

## Project Overview
Monopoly Strategy Simulator recreates the mechanics of Monopoly to evaluate how different player strategies perform under simulated conditions. Players aim to accumulate wealth, develop properties, and outlast their opponents by avoiding bankruptcy.

---

## Features
- **Core Monopoly Mechanics**:
  - Property purchasing and upgrading.
  - Turn-based gameplay.
  - Special spaces like "Go to Jail."

- **Player Strategies**:
  - Customizable strategies implemented via a Strategy interface.

- **Simulation Metrics**:
  - Number of wins per strategy.
  - Average player balance.
  - Properties owned by players.

- **Customizable Gameplay**:
  - Adjustable starting balances and turn limits.

---

## Implemented Strategies
1. **Collector Strategy**:
  - Focuses on monopolizing a specific color group of properties.
  - Prioritizes upgrading properties of the target color.

2. **Cautious Saver Strategy**:
  - Maintains a financial safety buffer before making purchases or upgrades.
  - Prioritizes financial stability over rapid expansion.

3. **Disruptive Strategy**:
  - Blocks opponents by purchasing diverse properties to prevent monopolies.
  - Does not prioritize upgrades.

4. **Aggressive Buyer Strategy**:
  - Acquires as many properties as possible without considering risks.
  - Encourages aggressive property upgrades.

---

## Experiment Design
- **Simulation Parameters**:
  - Players start with a balance of $750 and begin at position 0 on the board.
  - Simulations run for a maximum of 100 turns or until only one player remains.

- **Metrics Collected**:
  - Number of wins per strategy.
  - Average player balance at the end of the game.
  - Average number of properties owned.

---

## Results and Analysis
| Strategy              | Wins | Avg. Balance | Avg. Properties Owned |
|-----------------------|------|--------------|------------------------|
| Collector Strategy    | 23   | $131         | 2                      |
| Cautious Saver        | 10   | $474         | 1                      |
| Disruptive Strategy   | 22   | $0           | 0                      |
| Aggressive Buyer      | 5    | $257         | 1                      |

**Key Insights**:
- The **Collector Strategy** emerged as the most effective, balancing targeted investments and property upgrades.
- The **Cautious Saver** maintained financial stability but struggled to compete due to a lack of property acquisitions.
- The **Disruptive Strategy** effectively hindered opponents but sacrificed financial stability.
- The **Aggressive Buyer Strategy** was the least successful due to its high-risk approach.

---

## Technologies Used
- **Java**: Core programming language for the simulation.
- **GitHub**: Version control.

---

