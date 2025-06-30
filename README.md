# AunNote - Personal Note-Taking System

This repository contains my personal notes, managed in Markdown. The system is designed to be a personal knowledge base (or "second brain") and task management system, primarily focused on topics related to BIM, Revit, Dynamo, and Rail/Track modeling.

## Structure

The repository is organized as follows:

- **`/notes`**: Contains all individual notes.
  - **`/notes/zettelkasten`**: The core of the knowledge base. Notes are created using the Zettelkasten method, where ideas are atomic and linked together. The file naming convention `YYYYMMDD-Topic.md` is used to create unique, sortable identifiers.
  - **`/notes/tasks`**: Contains task lists and project-specific to-do items.
- **`/media`**: Stores any images or other media embedded in the notes.
- **`/templates`**: Holds templates for different types of notes, such as the `zettelkasten-template.md` and `task-template.md`.

## Tools & Workflow

This system is built to be simple and future-proof by using plain Markdown files.

- **Editor:** Any text editor can be used, but it is optimized for use with tools like [Obsidian](https://obsidian.md/) or [VS Code](https://code.visualstudio.com/) with the [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) extension.
- **Linking:** Notes are linked together using the `[[YYYYMMDD-note-title]]` syntax, making it easy to navigate between related concepts.
