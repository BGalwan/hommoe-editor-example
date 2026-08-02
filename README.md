# 🏰 HOMM Olden Era Editor Examples

Welcome! This repository serves as a curated collection of focused sample maps designed to demonstrate the features and mechanics of the **Heroes of Might and Magic: Olden Era** Map & Campaign Editor.

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Example List](#-example-list)
- [Example Structure](#-example-structure)
- [Installation & Usage](#-installation--usage)
- [Contributing](#-contributing)

---

## 🔍 Overview

Instead of hunting through full-length maps, this repository provides **focused, isolated examples** for key editor features. Each map is engineered to cleanly demonstrate **one or two specific mechanics**.

---

## 📂 Example List

| Map / Feature | Description | Key Mechanics |
| :--- | :--- | :--- |
| **`EventOnDayOne`** | Displays a dialog with an avatar and triggers localization mechanisms when starting the map. | Hidden quest, Day 1 auto-trigger event, Dialogs, Localization. |
| **`MarkSubQuestDone`** | Tracks troop encounters (killing or making them flee) and triggers a dialog before marking a subquest as completed. | Counter tracking, Encounter events, Subquest completion, Dialog boxes. |

---

## 🏗️ Example Structure

Each example project consists of three main components:

1. **JSON File:** Contains counter triggers, interruptions, and logic setups (typically edited with the [Map Editor JSON Tool](https://github.com/mimiasei/map-editor-json-tool)).
2. **Map File (`.map`):** A lightweight map (typically 16×16) containing only the essential elements required for the demonstration.
3. **ZIP Archive (`.zip`):** Mirrors the file structure of `Core.zip` and contains the dialog assets and localization tokens.

---

## 🚀 Installation & Usage

To run these examples in your local game editor:

1. **Copy the JSON and Map files** to your game's map folder:
   ```text
   <your install path>\Heroes of Might and Magic Olden Era\HeroesOldenEra_Data\StreamingAssets\maps
   ```

2. **Copy the ZIP archive** into the same folder as `Core.zip`:
   ```text
   <your install path>\Heroes of Might and Magic Olden Era\HeroesOldenEra_Data\StreamingAssets
   ```

3. Open the game or map editor to load and test the example.

---

## 🤝 Contributing

Contributions are welcome! This is an open-source community effort to build a comprehensive catalog of map-editing techniques.

### How to Contribute

1. **Open an Issue First:** Before writing code or creating maps, open a GitHub Issue describing your proposed feature or fix. This avoids duplicate effort and allows maintainers to provide early feedback.
2. **Fork & Branch:**
   ```bash
   git checkout -b feature/my-new-example
   ```
3. **Commit Your Changes:** Keep commit messages clear and concise.
4. **Push & Open a PR:**
   ```bash
   git push origin feature/my-new-example
   ```
   Open a pull request referencing your issue (e.g., `Closes #42`).

> **Note:** Please keep Pull Requests focused on a single feature or example. PRs without a corresponding issue may be closed or placed on hold.

### 💡 Good First Contributions
- Adding simple, single-mechanic scenarios or map templates to enrich the catalog.
- Improving documentation, comments, or localization token coverage.