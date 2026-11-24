# AstroKundli — starter project

A React + Vite starter for a Vedic astrology app.

## Run locally

1. Install Node.js (LTS).
2. Open this folder in a terminal.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL printed by Vite.

## Build

Run `npm run build`. The production site is generated in `dist/`.

## Current scope

This starter includes a responsive interface with Home, Monthly Horoscope, Kundli, Kundli Milan, Sade Sati and Dhaiya sections. The horoscope text is sample/demo content.

**Important accuracy note:** This project does not yet calculate real planetary positions or exact Saturn transit dates. Do not publish demo results as factual predictions. For accurate Jyotish calculations, integrate a properly licensed ephemeris (for example, Swiss Ephemeris after reviewing its licensing terms), a timezone/place database, and validated rules for the chosen ayanamsha and calculation conventions.

## Suggested next milestones

1. Decide calculation conventions: sidereal zodiac, Lahiri ayanamsha, true/mean nodes, sunrise and house-system rules.
2. Integrate ephemeris calculations on a secure backend.
3. Implement and test natal chart, Moon sign, Ashtakoota matching, Saturn transit periods and retrograde station handling.
4. Add authentication and encrypted handling of birth details only if accounts are needed.
5. Add tests with independently verified reference charts and transit dates.

## GitHub

Create a repository named `AstroKundli`, upload the contents of this folder, then commit and push changes as you develop.
