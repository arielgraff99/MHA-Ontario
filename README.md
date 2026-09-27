# Ontario Mental Health Law

A private ChatGPT plugin for educational, source-grounded explanations of Ontario mental health law, consent and capacity, substitute decision-making, Consent and Capacity Board processes, and Mental Health Act forms.

**Installed plugin:** https://chatgpt.com/plugins/plugins_6ab97fbf06388191a25cbe61ccc6b48b  
**Backed-up release:** 0.1.0 (plugin release `pluginrel_6ab97fbfaf3c819187efa7de7b41a785`)

## What it does

- Starts a new conversation with a confidentiality notice and works with de-identified cases.
- Uses an available RAG corpus first, then verifies consequential or time-sensitive claims against current authoritative Ontario sources.
- Cites legal and procedural claims and distinguishes legislation, prescribed forms, tribunal materials, professional guidance, institutional practice, and synthesis.
- Reviews Form 1 with Form 42, Form 3 with Form 30, and Form 4 with Form 30.
- Compares independently supported certificate grounds and flags inconsistent notices.
- Checks Form 3 and Form 4 duration, renewal sequence, continuity, and whether a certificate of continuation applies.
- Separates decision-specific capacity questions from SDM eligibility and authority.
- Produces de-identified case analyses and form drafts with placeholders for missing information.

## Files

- [`plugin.json`](plugin.json) — plugin identity and user-facing prompts.
- [`skills/ontario-law-educator/SKILL.md`](skills/ontario-law-educator/SKILL.md) — complete workflow and safeguards.

## Use and limits

The plugin gives educational information, not legal or clinical advice. It does not include a built-in RAG index, an automated live-law feed, or Canva/Outlook integrations. Access to sources depends on the tools available in the conversation. Verify current requirements against [Ontario e-Laws](https://www.ontario.ca/laws/statute/90m07), [prescribed MHA forms](https://www.ontario.ca/page/mental-health-forms), and legal counsel where appropriate. Do not submit patient identifiers.

This GitHub repository backs up the plugin instructions. Editing these files does **not** update the installed plugin automatically; the changed files must be packaged and released through Plugin Creator.
