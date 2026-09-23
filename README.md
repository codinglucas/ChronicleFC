<div align="center">

# ⚽ [Project Name TBD]

### AI-generated career save ideas for EA Sports FC

![Status](https://img.shields.io/badge/status-in--development-yellow)
![Python](https://img.shields.io/badge/python-3.x-blue)
![LLM](https://img.shields.io/badge/LLM-Google%20AI%20Studio-4285F4)

</div>

---

## About

Ever stared at the club select screen with zero direction? This tool uses an LLM to generate career mode save ideas for EA Sports FC — scenarios, club/player narratives, and roleplay hooks — so every save starts with a story worth playing.

## ✨ Features

- 🎯 **Idea generation** — get a fresh save concept on demand, from underdog rebuilds to legacy-club sagas
- 📦 **Structured output** — every idea comes back as clean, validated JSON, ready to plug into other tools
- ⚡ **Fast & free to run** — built on Google AI Studio's generous free-tier quota

> More features will be checked off here as they're built.

## 🧠 Design Decisions

| Decision | Choice | Why |
|---|---|---|
| LLM provider | **Google AI Studio** | Well-structured API and a generous free daily request quota — ideal for iterative development |
| Output format | **JSON via Pydantic** | Pydantic models validate and type-check every LLM response, so downstream code always gets predictable, well-formed data |

## 🛠️ Tech Stack

- **Python**
- **Google AI Studio** (Gemini API)
- **Pydantic** — schema validation for structured output

## 🚀 Getting Started

```bash
# coming soon
```

## 📍 Roadmap

- [ ] Core idea-generation pipeline
- [ ] Pydantic output schemas
- [ ] CLI / interface
- [ ] Save idea history & favorites

## 📄 License

*TBD*

---

<div align="center">
<sub>Built by Lucas</sub>
</div>
