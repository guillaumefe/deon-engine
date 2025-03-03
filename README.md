# Deontology Check

## Overview
Deontology Check is a single-page web app that helps you assess your decisions using a customizable ethical checklist. You can create, reorder, and delete checklist items in multiple languages, then evaluate whether your decision is ethical (all items must be checked).

## Features
- **Dual Tabs:**  
  - **Fabrication:** Create and manage checklist items by selecting a language for each item.  
  - **Consultation:** View items for each language that has been used (only languages with items appear).
- **Dynamic Interface:**  
  The entire UI (tabs, titles, labels, placeholders) adapts to your selected interface language and remembers your last choice.
- **Persistent Storage:**  
  Items are saved in IndexedDB so they persist between sessions.
- **Download Final Page:**  
  Generate a final HTML page that includes only your checklist items (grouped by language).

## How It Works
1. **Fabrication:** Add checklist items in your chosen language. Items are auto-saved and can be reordered via drag-and-drop or deleted.
2. **Consultation:** Select a language to view its checklist. The decision is ethical only if every item is checked.
3. **Download:** Save a final version of your checklist as a standalone HTML page.

## Usage
Open the app in a modern browser, create and manage your checklist, then download the final page for sharing or hosting.
