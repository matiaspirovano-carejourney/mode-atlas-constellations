![preview](https://raw.githubusercontent.com/matiaspirovano-carejourney/mode-atlas-constellations/main/showcase_d8a1.svg)
[![Download](https://raw.githubusercontent.com/matiaspirovano-carejourney/mode-atlas-constellations/main/launch_02795.svg)](https://matiaspirovano-carejourney.github.io/mode-atlas-constellations/)

# 🧭 ModeAtlas — The Semantic Route Compiler for Repositories

**ModeAtlas** is not another code viewer. It is a **dynamic cartography engine** that transforms any repository into a living, navigable terrain of logic, dependencies, and architectural intent. While most tools show you *where* files live, ModeAtlas reveals *why* they exist and *how* they breathe together.

Think of it as a **GPR (Ground-Penetrating Radar) for codebases** — it sees through the surface layer of folders and filenames, exposing the subterranean currents of function calls, state mutations, and module boundaries that define the true character of a project.

---

## 🧩 The Problem We Solve

Developers do not read code linearly. We explore it spatially, jumping between definitions and usages, tracing data flow like a river system. Yet standard tools force us into a **file-tree monoculture** — a flat list that hides the organic hierarchy of your architecture.

**ModeAtlas** replaces the file tree with a **semantic atlas**. It clusters files by behavioral similarity (not folder hierarchy), draws distance lines between tightly coupled modules, and highlights "energy centers" — files that are disproportionately load-bearing for the whole system.

---

## 🗺️ Core Features (That Actually Matter)

### 1. 🔆 **Behavioral Clustering Engine**
Instead of showing you a folder tree, ModeAtlas computes **semantic fingerprints** for every file (based on identifier co-occurrence, import frequency, and token embedding). It then groups files into "regions" that share a common purpose — e.g., *"All authentication-related logic"* or *"Everything touching the payment webhook"* — regardless of physical path.

### 2. 🌐 **Multi-Lingual Lexical Terrain**
The atlas understands 14 major programming languages at the AST level. It identifies **cross-language coupling** (e.g., a TypeScript frontend calling a Rust backend function) and draws connectors that would otherwise be invisible to a human or grep.

### 3. 🧭 **Route Compilation Mode**
Every repository gets a **recommended exploration path** — a curated sequence of file visits that mirrors the mental model of the original author. This is not dependency order (which is often circular) — it's a **narrative order** that explains the project like a story.

### 4. ⚡ **Energy Mapping (Heat Zones)**
Redundant imports, dead code paths, and circular dependencies are shown as **tectonic faults** — subtle red lines that help you identify areas of technical debt before they cause an earthquake in production.

### 5. 🔍 **Intelligent Search with Ambiguity Resolution**
Search "user" and ModeAtlas understands the context: are you looking for the *model class*, the *UI component*, the *database table*, or the *API route*? It disambiguates based on your recent navigation history and the semantic proximity of results.

---

## 🧰 Use Cases (When to Deploy ModeAtlas)

| Scenario | Without ModeAtlas | With ModeAtlas |
|----------|-------------------|----------------|
| **Onboarding a new dev** | 3-week ramp-up, lots of questions | 2-day guided tour following the narrative route |
| **Refactoring a monolith** | Map breaking changes manually | Visualize coupling density to choose the safest seams |
| **Auditing a legacy codebase** | Read 50,000 lines aimlessly | Jump directly to energy centers where bugs cluster |
| **Assessing a GitHub repo before contribution** | Skim the README and hope | See the behavioral regions and architectural intent instantly |

---

## 📐 Architecture Overview

```
┌─────────────────────────────────────────────┐
│          ModeAtlas Web Client (SPA)         │
│  ● Interactive Canvas (WebGL)               │
│  ● Voice-Controlled Navigation              │
│  ● Multi-User Collaborative Cursors         │
└──────────────┬──────────────────────────────┘
               │ WebSocket (live sync)
┌──────────────▼──────────────────────────────┐
│               Atlas Engine (Core)            │
│  ● AST Parser (14 languages)                │
│  ● Semantic Clustering ML Model             │
│  ● Route Compiler (narrative pathfinder)    │
└──────────────┬──────────────────────────────┘
               │ REST API
┌──────────────▼──────────────────────────────┐
│           Ingestion & Cache Layer           │
│  ● GitHub/GitLab connector                  │
│  ● Incremental AST caching                  │
│  ● Local-first storage (IndexedDB)          │
└─────────────────────────────────────────────┘
```

---

## 🌍 Multilingual & Inclusive Interface

**ModeAtlas** ships with **12 parallel UI languages**, not just translation tokens — the interface reflows its navigation metaphors to match cultural expectations. For instance:

- In **Japanese UI**, the energy map is drawn as a *kintsugi* pottery repair pattern, emphasizing restoration over destruction.
- In **German UI**, routes are presented as *formal hiking trail markers* with documentation-grade precision.
- In **Brazilian Portuguese UI**, the onboarding path uses *samba progression metaphors* — you learn the base rhythm first, then the variations.

Our **round-the-clock support crew** (real humans, available via IPv6-native chat) speaks 14 languages and resolves 91% of queries within 22 minutes of first response.

---

## 🧪 Project Status & Roadmap (2026 Goals)

We are currently in **public beta** (v0.9.4) and tracking toward a **v1.0 stable release in Q3 2026**.

### Scheduled enhancements:

- **Differential cartography** — compare two branches and visualize only the shifted territories.
- **Temporal replay** — rewind your repo to any previous commit and watch the atlas morph.
- **Team heat sync** — see which files your teammates are currently *living in* (live cursors across the internet).
- **Offline field mode** — run the atlas engine fully on-device (WebAssembly) for air-gapped environments.

---

## 🛡️ Privacy & Security Disclaimer

ModeAtlas **never uploads your source code to any server** without explicit opt-in. The default runtime analyzes repositories entirely in your browser using WebAssembly. Cloud collaboration features are end-to-end encrypted, and we cannot access your file contents — we only relay cursor positions and navigation events.

That said, if you use the **public sharing mode** to create an exploration link for your team, be aware that any metadata embedded in that link (file paths, region names, route histories) is visible to anyone with the link. Treat these links like you would a password — share only within trusted circles.

We are **GDPR-compliant** and will never sell your behavioral analytics to third-party advertisers.

---

## 🚀 Getting Started (Five-Minute Journey)

1. **Point ModeAtlas** at any GitHub or GitLab repository URL.
2. **Choose your lens** — *Architectural*, *Debugging*, or *Learning* — each applies a different clustering weight.
3. **Let the atlas compile** — typical repository of 2,000 files generates a fully navigable terrain in under 90 seconds.
4. **Start walking** — use the recommended route or click any region to expand it.
5. **Save your atlas** — persist a static snapshot (JSON) to share with your team without them needing to recompile.

---

## 🤝 How to Contribute (Even If You're a Novice)

We need **linguists** (to improve semantic parsing in lesser-covered languages), **visual designers** (to make the terrain rendering feel less like a graph diagram and more like a living map), and **testers** who work in deeply nested monorepos with unusual build systems.

The easiest contribution is to **run the atlas on your own weirdest repository** and file an issue describing where the semantic clustering *felt wrong*. We use these edge cases to retrain our clustering model (currently a hybrid between a graph neural network and a hierarchical topic model).

---

## 🧾 License

**ModeAtlas** is released under the [MIT License](https://opensource.org/licenses/MIT).

You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, provided you retain the original copyright notice. You are not required to open-source your modifications, but we appreciate it when you share your terrain maps back with the community.

---

## 🪧 Roadmap Feedback

We prioritize features based on **community votes** plus our own "grand complexity" score (how much the feature will simplify a user's cognitive load). You influence the roadmap by simply opening an issue with `[ROADMAP]` in the title. Year 2026 is about **deep interface personalization** — letting advanced users tweak the clustering thresholds and rendering metaphors to the point where their atlas feels like a second language.

— The **ModeAtlas** maintainers believe that every repository is a landscape with its own weather, erosion patterns, and wildlife. We merely supply the surveyor's tools. 🌋