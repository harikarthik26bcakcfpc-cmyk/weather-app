# Breeze Peak 🌤️

A minimal, mood-driven weather app concept for iOS, designed around calm typography, soft color palettes, and a poetic tone rather than dense data dashboards.

## Overview

Breeze Peak reframes weather as something to *feel*, not just check. Instead of leading with charts and numbers, each screen opens with a short, human sentence ("Today the sky is soft.", "One perfect autumn day") and layers the data underneath.

## Screens

| Screen | Purpose |
|---|---|
| **Splash / Welcome** | Full-bleed photography with the Breeze Peak wordmark, setting the "weather · nature · you" tone before entering the app. |
| **Home** | Current conditions for the active city (temperature, condition icon, "feels like," wind, humidity) plus a short descriptive caption and a search bar to look up other places. |
| **Search** | A list of featured destinations (e.g. Kerala, Washington, Paris, Tokyo) with live temperature, letting the user quickly switch locations. |
| **Day View** | A single day broken into Morning / Noon / Evening / Night blocks, each with a time range, short description, temperature, and condition icon — the currently active period is highlighted. |
| **Closing / Thank You** | A sign-off screen shown when leaving the app, reinforcing the brand and travel-companion feel. |

## Design Language

- **Palette:** warm neutrals (cream, sand) paired with one accent color per screen (amber for clear/soft skies, orange for highlighted time blocks, teal for the closing screen).
- **Typography:** large, soft serif/script wordmark for branding; clean sans-serif for data and UI text.
- **Tone of voice:** short, evocative captions instead of clinical weather terms (e.g. "Bright golden hour, clear skies" instead of "Sunny, 18°").
- **Cards:** rounded corners, generous padding, low-contrast shadows — data is grouped into soft cards rather than dense tables.

## Core Features

- Current conditions with wind and humidity at a glance
- Search and switch between featured or saved destinations
- Day broken into four time-of-day segments with per-segment forecasts
- Descriptive, narrative captions generated per condition/time of day

## Status

This README documents an early visual/UX concept (5 mock screens). No functional code, API integration, or navigation logic has been implemented yet.

## Suggested Next Steps

- Define the weather data source/API to power live conditions
- Build out the design system (spacing, color tokens, type scale)
- Prototype navigation between Home → Search → Day View
- Add a settings/profile screen and unit toggle (°C/°F)
