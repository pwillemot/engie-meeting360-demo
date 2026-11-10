# Elia KAM — Meeting 360 (mobile prototype)

Static, mobile-style demo of the **Meeting 360** experience for an Elia Key Account Manager.
It shows the mobile side of the Elia KAM demo org (`elia-demo`): pre-meeting briefing, visit report and Account 360.

**Persona:** Patrice Willemot, KAM Energy. **Today (10 Nov 2026):**
- **Electrabel NV** (main meeting) with Marc Dubois (Head of Short-Term Trading) and Sofie Vermeulen (Head of Asset Management Belgium)
- **Vlaanderen Plant Foods NV (fictional)**: follow-up on the price-signal interview with Ruben Desmet and the advisor Pieterjan Verhaeghe (golden thread)

All figures are in **MW**. There are no € amounts.

## What to show
- **Pre-meeting brief:** a shortened version of the org's *Elia - AI briefing* for Electrabel: relationship, open topics per market role, commitments, confidentiality note. Open Vlaanderen Plant Foods to get its own brief. *Play* plays the recorded Electrabel briefing (`assets/PreMeetingBrief-electrabel.mp3`, ~34 s).
- **Visit report:** *Record visit report* turns a voice note into a note plus a task (Doel 3&4 bay reuse). The Agentforce chat maps a spoken debrief to the agenda and drafts a market signal (mFRR-down → PL Balancing).
- **Account 360:** contacts, market roles (7), access points (4,104 MW, real EANs), recent interactions with their confidentiality, open commitments.
- **Share:** meeting summary email to Marc Dubois (no confidential BRP/BSP details).

## Data source
Accounts, contacts, market roles, access points and interactions mirror the `elia-demo` org (see `../ELIA-STATUS.md`). People are fictional; emails end in `.invalid`. Alpro, the real advisor and the real figures are never used.

## Run locally
Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

Prototype for demo purposes only — not connected to a live org.
