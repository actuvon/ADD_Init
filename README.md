# Project Name

This is a template for AI-driven-development projects. This repo offers a particular structure and a set of instructions that works well for teaching AI how to work efficiently with its context, its human, and other resources.

The use-case involves cloning this repo, then editing this README and the Kanban/other files to give the AI some guidance and then put it to work.

# Repo Structure

| Path                     | Description                                                                                           |
| ------------------------ | ----------------------------------------------------------------------------------------------------- |
| ./README.md              | This file - the basic top-level information about this repo.                                          |
| ./ActiveTasks/           | The boss. The Kanban. Tells us what we're working on, what's left to-do, and what's already done.     |
| ./ActiveTasks/Kanban.md  | The master file that tells us what work is active and what comes next.                                |
| ./ActiveTasks/Journal.md | The chronological history of things done recently.                                                    |
| ./CLAUDE.md              | The repo's AI context initializer. Claude will read this file before processing the first prompt.     |
| ./src/                   | Source code goes here.                                                                                |
| ./bin/                   | Compiled executables go here.                                                                         |
| ./data/                  | Data models, database schemas, migration scripts, and all documentation on data models and their use. |
| ./Hardware/              | Physical components from the real world.                                                              |

# Architecture

Recommend making an architecture directory or at least an Architecture.md that gets called out here after briefly describing things from a high level.

# Active Tasks / Development Status

Development status in this repo is tracked using a Kanban board in `./ActiveTasks/Kanban.md`.

