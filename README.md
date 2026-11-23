# Symulator-automatu-z-napojami
Projekt wykonany na laboratorium z Zaawansowanego Programowania Obiektowego

## Instalacja i uruchomienie testów

```bash
python -m venv .venv
.venv\Scripts\activate           # Windows
source .venv/bin/activate        # Linux / macOS
pip install -e ".[dev]"
python -m pytest
```

## Rejestr użycia LLM

| Plik / fragment | Narzędzie | Do czego użyto i jak zweryfikowano |
|---|---|---|
| .gitignore | Claude | wygenerowany, użyty bez zmian; sprawdzono ignorowanie __pycache__ i .venv |
| pyproject.toml | Claude | wygenerowany, użyty bez zmian; sprawdzono `python -m pip install -e ".[dev]"` i `python -m pytest` |
| vending/__init__.py | Claude | jednolinijkowy docstring pakietu |