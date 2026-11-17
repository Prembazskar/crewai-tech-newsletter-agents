# CrewAI Multi-Agent Tech Newsletter

A multi-agent CrewAI pipeline: a researcher finds the latest technology news and a writer turns it into a newsletter.

> Part of my Gen AI course practice work (Week 4, Day 4).

## Tech stack

- Python 3
- CrewAI
- crewai-tools (SerperDevTool)
- OpenAI

## Features

- Technology News Researcher agent with web news search
- Technology Newsletter Writer agent
- Model configurable with the `MODEL` variable

## Getting started

1. Clone the repository:
   ```bash
   git clone https://github.com/Prembazskar/crewai-tech-newsletter-agents.git
   cd crewai-tech-newsletter-agents
   ```
2. Install and configure:
   ```bash
   pip install -r requirements.txt
   cp .env.example .env   # OpenAI and Serper keys
   ```

Environment variables (set in `.env`, never commit it):

- `OPENAI_API_KEY`
- `SERPER_API_KEY`
- `MODEL`

## Usage

```bash
python News_crew.py
```

## License

MIT, see [LICENSE](LICENSE).
