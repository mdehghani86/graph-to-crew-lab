# From Graph to Crew — The World Cup Lab

Companion code for the talk **"From Graph to Crew: A Hands-On Tour of Agentic AI Frameworks"**
(International Summer School on Generative AI, Rome 2026 · Mohammad Dehghani · [AI2Lab](https://www.ai2lab.ai/)).

We build the **same task twice** — a World Cup match-analysis system that writes a scouting report —
once with **CrewAI** (a *crew* you assemble) and once with **LangGraph** (a *graph* you draw).
Same goal, two architectures, so you can feel the difference.

## Open in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mdehghani86/graph-to-crew-lab/blob/main/graph_to_crew_lab.ipynb)

## What's inside

`graph_to_crew_lab.ipynb` — one self-contained notebook:

1. Install the frameworks
2. Choose a provider and load **your own** API key (as a Colab secret)
3. A pretty-print helper for clean output
4. Mock match data (runs offline)
5. **Build 1 · CrewAI** — agents, tasks, crew
6. **Build 2 · LangGraph** — state, nodes, edges, a conditional loop
7. A side-by-side comparison and stretch goals

## Bring your own key

Each participant uses **their own** API key, stored as a **Colab secret** (the key icon in the
left sidebar) — never pasted into a shared notebook or committed to git. Pick your provider at the
top of Step 2:

| Provider | Secret name | Default model |
|---|---|---|
| Anthropic (default) | `ANTHROPIC_API_KEY` | `claude-haiku-4-5-20251001` |
| OpenAI | `OPENAI_API_KEY` | `gpt-4o-mini` |
| Google | `GOOGLE_API_KEY` | `gemini-2.5-flash` |

## License

MIT. Teaching material, use freely with attribution.
