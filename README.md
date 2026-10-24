# Gemini Notebook CLI & MCP Expert

> **Tri-Platform Agent Skill** for Claude Desktop / Code, Grok CLI, and Google Antigravity / Gemini.  
> Comprehensive guidance and automation orchestrator for Gemini Notebook CLI (nlm) and MCP server tools.

---

## Overview

`nlm-skill` provides standardized capabilities across conversational AI platforms:
- Dual-mode execution architecture supporting both MCP tools and the nlm CLI.\n- Comprehensive notebook lifecycle management: create, list, rename, describe, and share.\n- Multi-source ingestion pipeline: URLs, YouTube videos, raw text, and Google Drive.\n- Automated Studio generation for podcasts, audio overviews, study guides, and reports.\n- Tri-platform NTFS junctions connecting Claude, Grok, and Antigravity.

---

## Tri-Platform Architecture

Zero duplicate code across platforms. Canonical source resides in `.agents`:
- **Canonical Source**: `C:\Users\<you>\.agents\skills\nlm-skill`
- **Claude**: `C:\Users\<you>\.claude\skills\nlm-skill` (NTFS Junction)
- **Grok**: `C:\Users\<you>\.grok\skills\nlm-skill` (NTFS Junction)
- **Antigravity**: `C:\Users\<you>\.gemini\config\skills\nlm-skill` (NTFS Junction)

---

## Documentation Suite

- [`HOW_TO_USE.txt`](HOW_TO_USE.txt): Standardized user guide and prompt templates.
- [`IMPLEMENTATION_PLAN.md`](IMPLEMENTATION_PLAN.md): Feature checklist and roadmap.
- [`App Changes Tracker.html`](App%20Changes%20Tracker.html): Interactive visual version log.
- [`SKILL.md`](SKILL.md): Agent system instructions and triggers.
