# ♟️ Predict the Unpredictable

### Predicting Chess Game Outcomes with Machine Learning

Can a chess game be predicted before it is over?

**Predict the Unpredictable** explores whether the outcome of a chess game can be estimated using information available while the game is still being played.

The project is based on more than **130,000 Lichess games** and combines game metadata with move-level information obtained through the **Lichess API** and **Stockfish**.

We analyze factors such as:

- ♟️ Stockfish position evaluation
- ⏱️ Remaining time and time pressure
- 🎯 Centipawn loss
- 📈 Player Elo ratings
- 🕹️ Game format and time control
- 📊 Player performance throughout the game

Different approaches are compared, ranging from simple heuristic rules to machine learning models including **Logistic Regression**, **Decision Trees**, and **Random Forests**.

The goal is not only to predict whether White wins, but also to produce meaningful **win probabilities** and evaluate how well those probabilities are calibrated.

---

## Models

- Heuristic Prediction Rules
- Logistic Regression
- Decision Tree
- Random Forest

---

## Tech Stack

`R` · `Machine Learning` · `Lichess API` · `Stockfish` · `Data Analysis` · `Data Visualization`

---

## Research Question

> **Can probabilities of outcomes in a chess game be predicted using in-game metrics?**

---

## Dataset

The analysis uses data from more than **130,000 chess games played on Lichess**, enriched with additional move-level information such as engine evaluation, remaining time, centipawn loss, and game phase.

---

## Key Idea

Traditional chess engines evaluate the objective strength of a position assuming near-optimal play.

Human players, however, are influenced by factors such as **time pressure, mistakes, playing strength, and consistency**.

This project investigates whether combining these human factors with engine evaluations can provide a better estimate of the actual game outcome.
