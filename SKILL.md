---
name: awesome-deck-pdf
description: Generate polished HTML slide decks and export as PDF. Works with OpenClaw, Claude Code, and Codex. Supports .pptx templates, images, website URLs, and style keywords.
---

# Awesome Deck PDF

Generate beautiful HTML slides and export them as PDF files.

## What it does

- Creates HTML slides (1440x900px) from a design style
- Exports to PDF using Puppeteer
- Works with OpenClaw, Claude Code, Codex

## Input types

1. .pptx file - Extract colors, fonts, layout
2. Image/screenshot - Analyze design elements
3. Website URL - Clone visual style
4. Style keywords - e.g. "Apple", "Notion", "Linear"

## Output

- slides.html - The HTML slide deck
- slides.pdf - The exported PDF file

## Usage

Just tell the agent what kind of slides you want:
- "Make slides in Apple style"
- "Create a presentation about our product"
- "Build a deck with our company template"

The agent will guide you through the process.

## Requirements

- Node.js with Puppeteer
- Chrome or Chromium browser
- For full setup instructions, see references/install.md
