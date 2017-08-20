---
layout: post
title: Modal Logic Boardgame
---

'Modal logics' are a class of logics that extend propositional and predicate logic to capture more of the expressiveness and nuances of human reasoning. Their names 'aleithic', 'temporal', 'epistemic', 'doxastic', 'deontic', 'dynamic' are beautiful Greek words which hint at a variety of applications. Here is outlined a board game based on a subset of modal logics. Note: it will only make sense if you already know how to draw truth trees for aleithic normal modal logic systems. If you don't, try reading Chapter 3 of 'Modal Logics and Philosophy' (second edition) by Rod Girle, which this boardgame is based on.

For 2-6 players.

### Ingredients

A notepad and pencil for each player, plus a set of formula cards.

### Rules of Play

Each player is initially dealt a single random formula card. The initial system is S5. They will then proceed to draw a truth tree (tableau) in the following manner: in the first round, everyone will negate the target formula. The next round, everyone will write the next line of their truth tree, using any of the rules allowed in S5. However, before the third round begins, a die will be rolled. A 5 or 6 mean that the system will continue to be S5. A 1 means system K, 2 means T, 3 means B and 4 means S4. If anyone has previously performed a step that was invalid in the new system, they must cross out that line (and any following lines that depended on that step). They continue in this way, writing a new line* each round and rolling the dice every \\( n \\)th round, where \\( n = 1 \\) in the most difficult game, and \\( n = 10 \\) in a much easier game. The aim of the game is to be the first to produce a correct derivation of the formula. The validity of each step of the winning derivation should be examined by the other players.

*If the tableau is split, e.g. by dividing \\( p \vee q\\) into \\( p\\) and \\( q\\), then the line is not split, but continues across both halves. It is obligatory to write a line each round: this cannot be skipped. Nor can lines be crossed out unless they are invalid in the present system.

Formula Cards

To make the formula cards, the following formulas (all valid in S5) should be printed on separate cards:

$$ (\diamond (p \vee q) \rightarrow (\diamond p \vee \diamond q)),      (\square (\square (p \rightarrow \square p) \rightarrow \square p) \rightarrow (\diamond \square p \rightarrow \square p))$$

$$ (\square \neg p \rightarrow \square (p \rightarrow \neg p)),     (\square (\square p \vee \square q) \leftrightarrow (\square p \vee \square q))$$

$$ (\square \neg p \rightarrow \square (p \rightarrow q)),      (\diamond \square p \rightarrow p)$$

$$ (\square p \rightarrow (\diamond q \rightarrow \diamond (p \wedge q))),     (\square (p \leftrightarrow q) \rightarrow \square (\square p \leftrightarrow \square q))$$

$$ (\diamond (p \rightarrow q) \leftrightarrow (\square p \rightarrow \diamond q)),      (\diamond (\diamond p \wedge \neg q) \vee \square (p \rightarrow \square q))$$

$$ \square (p \rightarrow \square \diamond p),      ((\diamond \neg p \vee \diamond \neg q) \vee \diamond (p \vee q))$$

$$ (p \rightarrow (\diamond \square \square p \rightarrow \square p)),      (\square (\square p \rightarrow q) \vee \square (\square q \rightarrow p))$$

$$ (\square \diamond p \leftrightarrow \square \diamond \square \diamond p),      \square (p \rightarrow q) \rightarrow \square (\square p \rightarrow \square q)$$

$$ ((\diamond \diamond p \rightarrow \diamond p),     \diamond (p \vee q) \leftrightarrow (\diamond p \vee \diamond q)$$

