# Multi-Linked-Negotiation

## About

This is an implementation of [Multi-Linked Negotiation in Multi-Agent System by Zhang et al.](https://www.researchgate.net/publication/221455095_Multi-Linked_Negotiation_in_Multi-Agent_System) and chapter 2 of [Sophisticated Negotiation in Multi-Agent Systems](https://dl.acm.org/doi/book/10.5555/936752).

It pertains to the field of automated negotiation in multi-agent systems. The project is divided into three phases:

1. **Negotiation ordering**. Each agent decides what it thinks is the optimal (`ordering`, `assignment`) tuple, where `ordering` is the order in which it wishes to negotiate over its negotiation issues and `assignment` is the values it has assigned to variables associated with each issue (such as earliest starting time and deadline).
2. **Negotiations**. The negotiations take place in this round.
3. **Task execution**. Based on the negotiations, the tasks that succeeded are executed in this round, while those that failed Phase 2 propagate their failure to all of the dependencies.

## Installation

```
pip install -r requirements.txt
```
