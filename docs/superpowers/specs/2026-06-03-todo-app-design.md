# Todo App Design

**Date:** 2026-06-03

## Overview
Single-file frontend todo app. No backend, no dependencies.

## Stack
- Single `index.html` (HTML + CSS + JS embedded)
- localStorage for persistence

## Features
- Add todo item (input + button)
- Mark item complete (checkbox)
- Delete item (button)

## Data Model
```json
[{ "id": 1, "text": "할 일", "done": false }]
```
Stored as JSON in `localStorage["todos"]`.

## UI
- Header with title
- Input field + Add button
- Todo list: each row has checkbox, text, delete button
- Completed items shown with strikethrough
