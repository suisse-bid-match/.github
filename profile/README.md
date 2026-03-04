# SuisseBidMatch 🇨🇭
**Spec- & rule-driven tender matching for Swiss public procurement (SIMAP).**

> Unofficial project — not affiliated with simap.ch.

## What we do
SuisseBidMatch helps companies **find the tenders they can actually win**:
- Ingest your **internal product specs, capabilities, and business rules**
- Understand SIMAP tenders (DE/FR/IT) and extract requirements
- Rank opportunities with **explainable match reasons** (why it fits / why it doesn’t)

## Key features
- 🔎 **Best-fit matching** (beyond keywords/CPV)
- ✅ **Rule checks** (must-have requirements, exclusions, compliance gates)
- 🧠 **RAG context** from your product catalog + past bids (optional)
- 📝 **Explainability**: fit score + evidence snippets

## How it works (high level)
1) Tender ingestion → normalize fields + text  
2) Requirement extraction → constraints & signals  
3) Matching engine → rules + embeddings + rerank  
4) Output → ranked list + reasons + action checklist

## Demo
- Live demo: <link>
- Pitch deck / video: <link>

## Repositories
- `suissebidmatch` – main platform
- `data` – ingestion & parsing
- `matcher` – matching engine
- `docs` – docs & architecture
- `eval` – evaluation suite

## Contributing
We welcome issues & PRs. See `CONTRIBUTING.md`.

## Contact
- Email: <team@email>
- Devpost: <link>
