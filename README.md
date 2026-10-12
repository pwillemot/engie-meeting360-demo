# Engie — Meeting 360 Demo

Static, mobile-style demo of a **Meeting 360** field-visit experience for Engie Belgium,
built around an AB InBev (Leuven) solar + battery storage opportunity.

Single self-contained page (`index.html` + `assets/`) covering:

- **Pre-meeting brief** — Agentforce briefing with the solar + storage talking points
- **Meeting report** — voice-dictated visit report + Agentforce summary, with auto-created follow-up task
- **Account 360** — AI summary, previous notes, and visit history
- **Share** — email the visit summary, Teams / PDF / Print options

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

Prototype for demo purposes only — not connected to a live org.
