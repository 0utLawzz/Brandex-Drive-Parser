# Contributing to Drive-Data

## Setup

```bash
git clone https://github.com/0utLawzz/Drive-Data.git
cd Drive-Data
pip install -r requirements.txt
# Place credentials.json locally (never commit it)
python main.py
```

## Guidelines

- Keep pattern rules in `parser_v2/` and `custom_rules.json` consistent.
- Do not commit client folder dumps, credentials, or production Sheet IDs with PII.
- Prefer focused PRs with a short description of the change.

## Security

See [SECURITY.md](SECURITY.md).
