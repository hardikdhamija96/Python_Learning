# Python Learning — Practical Track

A structured, section-by-section Python curriculum for a data analyst moving into automation, agents, and eventually BigQuery-driven tooling. Taught as a knowledge-transfer: concepts are paired with the real-world failure modes they cause, not just syntax.

## Structure

| Folder | Contents |
|---|---|
| `slides/` | Source files for the recap slide deck (one deck per phase). Live, viewable deck: see "Live deck" below. |
| `assignments/` | One doc per section — short exercises to cement each topic before moving on. |

## Live deck

The current recap deck (Foundations → Data Types → Control Flow → Collections) is published here:
https://claude.ai/artifact/3WoqqtXV6zC7nabuBckXDg

`slides/project/` holds the underlying source (`deck.json` + one HTML file per slide) so the deck's content is versioned here even though it's rendered elsewhere.

## Curriculum phases

1. **Basics** — running Python, variables/types, operators, strings, conditions, loops, lists/dicts/tuples/sets, functions, reading errors, files/modules.
2. **Core** — objects & references, mutability, comprehensions, args/kwargs, scope, exceptions, classes, pathlib, json/csv, regex, logging, debugging, pytest, venv/pip, datetime, collections/itertools.
3. **Design** — typing/protocols, dataclasses/Pydantic, decorators, generators, context managers, async, architecture patterns, project structure.
4. **Agents** — tool design, agent state, validation, retries/timeouts, logging/tracing, config/secrets, Docker/deploy.

## Running project

A single project grows across sessions: a sales-report script (read orders → total revenue → write a report), which later becomes an agent that answers business questions by querying BigQuery.

## Progress tracking

Session-by-session topic log, clarity ratings, and what tripped up each topic are tracked outside this repo (coaching memory), not duplicated here.
