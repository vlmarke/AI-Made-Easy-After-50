# The Great Adventures of G-Pop & SoSo — VideoExpress Agent

A customized VideoExpress production prompt for Victor Ladson's continuing 2D cartoon series. It plans and produces an approximately two-minute episode as twelve connected clips of about ten seconds each.

## Files

- `SYSTEM_PROMPT.md`: complete production workflow and series canon.
- `SYSTEM_PROMPT_COMPACT.md`: compact instructions for a Custom GPT Instructions field; upload the full prompt as Knowledge.

## Series rules included

- G-Pop is the older Black grandfather caregiver; preserve his reference look and no glasses.
- SoSo stays a nonverbal baby who does not walk independently; maintain her established age-stage abilities.
- Only the narrator and G-Pop speak.
- Episodes are gentle, funny, child-friendly, and teach one simple lesson.
- Twelve-scene structure, continuity guidance, 2D style consistency, safe baby supervision, timeline assembly, and export checklist.

## Setup

In a Custom GPT, put `SYSTEM_PROMPT_COMPACT.md` in Instructions and upload `SYSTEM_PROMPT.md` as Knowledge. In an agent workflow, use the full prompt as the production instructions. Attach the two character references in order (G-Pop first, SoSo second) and provide an episode topic. The defaults are two minutes, twelve 10-second scenes, and vertical 9:16.

This repository contains the production instructions; it does not contain generated episodes or VideoExpress credentials.
