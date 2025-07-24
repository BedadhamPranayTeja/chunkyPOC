# 🧠 ChunkyDB – Symbolic Memory POC

> ✨ A prototype exploring how symbolic tagging, context cubes, and satellite mapping can transform file-based knowledge into an interactive memory system.

## 🚀 Live Demo

Check it out here → [chunkyPOC on GitHub Pages](https://bedadhampranayteja.github.io/chunkyPOC/)

---

## 🧊 What is ChunkyDB?

ChunkyDB is a symbolic tagging system that:

- **Splits files** into sections ("chunks") using meaningful tags
- **Visualizes structure** via cube-based grid views
- **Enables deeper connections** with inline, nested, and crosslinked tags
- **Offers intuitive previews** via plain text, tag syntax, and satellite graph views

---

## 📦 Current Features (POC)

- ✅ Grid View System: Main Cube / Node Cube / Context Cube (`XY Grid with Z-hover`)
- ✅ Preview Modes:
  - **Text View**: Rendered tag content
  - **Tag View**: Raw symbolic syntax
  - **Satellite View**: Skeleton file cards + badge linkage
- ✅ Tag Types:
  - `inline` – direct text substitution
  - `nested` – tag containing other tags
  - `cross` – connect to another file’s tag

---

## 📁 Mock Files

We simulate the experience using JSON files:

| File Name            | Description                       |
| -------------------- | --------------------------------- |
| `readme.json`        | Intro to the concept              |
| `cubesbrief.json`    | Explains cube view logic          |
| `previewsbrief.json` | Describes preview rendering types |
| `syntaxbrief.json`   | Covers tag syntax and formats     |

---

## 🧠 Preview Logic

When selecting a file, user can toggle between:

1. **Text View** – Shows expanded content
2. **Tag View** – Shows symbolic tag syntax
3. **Satellite View** – Interactive graph of file, tags, and references

---

## 🔧 How to Run Locally

```bash
git clone https://github.com/bedadhampranayteja/chunkyPOC.git
cd chunkyPOC
open index.html   # or serve with Live Server
```

---

## 🗺️ Vision Ahead

- AI-enhanced symbolic agent
- GraphQL hybrid APIs for content resolution
- WebSocket-based real-time mapping
- Personal context modeling

---

## 📌 Author

Made with ❤️ by [@bedadhampranayteja](https://github.com/bedadhampranayteja)

> Symbolic notes meet spatial thinking.
