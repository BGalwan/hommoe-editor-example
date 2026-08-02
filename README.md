# hommoe-editor-examples

**Welcome!** This repository serves as a collection of simple sample maps to demonstrate the capabilities of the **Heroes of Might and Magic: Olden Era** (HOMM Olden Era) Map & Campaign Editor.

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Maps](#-map-structure)

---

## 🔍 Overview

Instead of hunting through  full-length maps, this repository provides **focused, isolated examples** for some key feature. Each map is engineered to demonstrate **one or a few mechanic** cleanly.

---

## 📂 Example list

---
EventOnDayOne : demonstrate a hidden quest with an event that will shoot when starting the map : here the event display a dialog with avatar and localization mechanism

MarkSubQuestDone : demonstrate the termination of a subquest after a given event has occured. Here killing or making flee a troglodyte troup increase a dedicated encouter, a quest and a dedicated subquest look for the counter and launch a dialog box with avatar when done. A second action is launched in order to mark the subquest as done.   

---
## 📂 Example structure
Each example is composed of
- a json file usually edited with https://github.com/mimiasei/map-editor-json-tool that contains mainly the counter, interruption and 
- a map file (the simpler as possible 16*16) with necessary elements for the example
- the zip file with the same strcuture than Core.zip and containing Dialogs and localisation token

To make it works, copy : 
- Json file + map file in <your install path>\Heroes of Might and Magic Olden Era\HeroesOldenEra_Data\StreamingAssets\maps
- Zip file in the same folder than Core.zip i.e. <your install path>\Heroes of Might and Magic Olden Era\HeroesOldenEra_Data\StreamingAssets 


## Contributing
This project is open source and contributions are welcome.

- Open an issue first. Before writing any code, create a GitHub issue describing the feature or bug. This keeps work visible, avoids duplicate effort, and lets maintainers give feedback before you invest time in an implementation.

- Fork the repository and create a feature branch off main: git checkout -b feature/my-feature
Commit your changes with a clear message

- Push the branch: git push origin feature/my-feature

- Open a pull request that references the issue (e.g. Closes #42 in the PR description)
Please keep PRs focused — one feature or fix per PR makes review faster. PRs without a corresponding issue may be closed or asked to create one first.

Good first contributions

- add other simple scenario or examples to enrich the catalog