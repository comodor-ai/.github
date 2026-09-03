<div align="center">

# Comodor

**The coding agent that stops making the same mistake.**

Fix something it wrote, and it never writes it that way again — in this project
or the next one. Not a setting you turn on. Not a file you maintain.

[![PyPI](https://img.shields.io/pypi/v/comodor?label=pypi&color=0A7AFF)](https://pypi.org/project/comodor/)
[![Python](https://img.shields.io/pypi/pyversions/comodor?color=cyan&labelColor=darkcyan)](https://pypi.org/project/comodor/)
[![CI](https://github.com/ifekri/Comodor/actions/workflows/ci.yml/badge.svg)](https://github.com/ifekri/Comodor/actions/workflows/ci.yml)
[![Licence](https://img.shields.io/pypi/l/comodor?color=blue&&labelColor=darkblue)](LICENSE)

<p align="center">
  <a href="https://github.com/ifekri/Comodor/blob/main/docs/README.md">
    <img src="https://img.shields.io/badge/Docs-EN-green?logo=github&logoColor=white&style=plastic&labelColor=darkgreen" alt="English Docs" />
  </a>
  <a href="https://github.com/ifekri/Comodor/blob/main/docs/FA/README.md">
    <img src="https://img.shields.io/badge/Docs-FA-green?logo=github&logoColor=white&style=plastic&labelColor=darkgreen" alt="Persian (Farsi) Docs" />
  </a>
  <a href="https://github.com/ifekri/Comodor/blob/main/docs/AR/README.md">
    <img src="https://img.shields.io/badge/Docs-AR-green?logo=github&logoColor=white&style=plastic&labelColor=darkgreen" alt="Arabic Docs">
 </a>
  <a href="https://github.com/ifekri/Comodor/blob/main/docs/TR/README.md">
    <img src="https://img.shields.io/badge/Docs-TR-green?logo=github&logoColor=white&style=plastic&labelColor=darkgreen" alt="Turkish Docs" />
  </a>
  <a href="https://github.com/ifekri/Comodor/blob/main/docs/DE/README.md">
    <img src="https://img.shields.io/badge/Docs-DE-green?logo=github&logoColor=white&style=plastic&labelColor=darkgreen" alt="Deutsch Docs" />
  </a>
  <a href="https://github.com/ifekri/Comodor/blob/main/docs/ES/README.md">
    <img src="https://img.shields.io/badge/Docs-ES-green?logo=github&logoColor=white&style=plastic&labelColor=darkgreen" alt="Spanish Docs" />
  </a>
  <a href="https://github.com/ifekri/Comodor/blob/main/docs/RU/README.md">
    <img src="https://img.shields.io/badge/Docs-RU-green?logo=github&logoColor=white&style=plastic&labelColor=darkgreen" alt="Russian Docs" />
  </a>
  <a href="https://github.com/ifekri/Comodor/blob/main/docs/FR/README.md">
    <img src="https://img.shields.io/badge/Docs-FR-green?logo=github&logoColor=white&style=plastic&labelColor=darkgreen" alt="French Docs" />
  </a>
  <a href="https://github.com/ifekri/Comodor/blob/main/docs/ZH/README.md">
    <img src="https://img.shields.io/badge/Docs-ZH-green?logo=github&logoColor=white&style=plastic&labelColor=darkgreen" alt="Zhongwen Docs" />
  </a>
</p>


[**comodor.ai**](https://comodor.ai) · [Installation](#install) · [Documentation](docs/README.md 'Comodor Documentation English')

---

[![](https://raw.githubusercontent.com/ifekri/Comodor/main/.github/ascii-comodor.svg)]()
</div>

## Install

### Recommended installation

#### Linux / MacOS

```bash
curl -fsSL get.comodor.ai | sh
```

#### Windows (Powershell)

```bash
irm get.comodor.ai | iex
```

The one-liner above finds a Python, builds an isolated environment, puts
`comodor` on your `PATH`, and fetches a Python if there is none. Verified on a
bare `debian:bookworm-slim` with nothing installed.

Already have a package manager you like?

### Install With [uv](https://docs.astral.sh/uv/getting-started/installation/ 'UV Installation Docs')

```bash
uv tool install comodor
```

> [!NOTE]
> can use : `uv pip install comodor`


### Install With [pip](https://pip.pypa.io/en/stable/installation/ 'pip installation docs')

```bash
pip install comodor
```

> [!NOTE]
> linux on python3 use : `pip3 install comodor`


### Install With [pipx](https://pipx.pypa.io/latest/how-to/install-pipx.html 'How to Install pipx')

```bash
pipx install comodor
```

### In Docker — nothing to install

The agent, a real Chromium, git and ripgrep, in one container. It starts the
**browser interface** and prints the address to open:

```bash
git clone https://github.com/ifekri/Comodor.git && cd Comodor
export ANTHROPIC_API_KEY=...        # or OPENAI_API_KEY, OPENROUTER_API_KEY, ...
docker compose up
```
