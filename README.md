# AI Playground

A polished browser-based AI utility dashboard.

## Local AI Bridge

The local bridge runs on:

http://127.0.0.1:8765

Start it using:

bridge/start_bridge.bat

or:

bridge/start_bridge.sh

## API Key

The OpenAI API key is stored only in:

bridge/.env

The real `.env` must NEVER be uploaded to GitHub.

The ZIP builder intentionally excludes the real `.env`.

## Model

gpt-5.6-luna

## Frontend

The public frontend is:

frontend/index.html

## Important Architecture

GitHub Pages serves the public frontend.

The local bridge provides private AI functionality.

The browser communicates with:

127.0.0.1:8765

This architecture prevents the OpenAI API key from being exposed
inside the public GitHub Pages JavaScript.

## Natural Language

Examples:

- what's 1 + 1
- open YouTube
- open Microsoft Teams
- open Google Drive
- start a timer
- open calculator
- generate a UUID
- open notes
- roll a dice
- search YouTube for Minecraft
