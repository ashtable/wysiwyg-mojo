# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

wysiwyg-mojo is a project using Python 3.14 and Mojo (nightly). It uses `uv` for dependency management with the Modular nightly index for Mojo packages.

## Development Setup

```bash
uv sync          # Install dependencies (creates .venv)
uv run main.py   # Run the application
```

## Key Details

- **Python version**: 3.14 (pinned in `.python-version`)
- **Mojo package source**: nightly builds from `https://whl.modular.com/nightly/simple/`
- **Package manager**: uv (see `pyproject.toml` and `uv.lock`)
