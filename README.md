# Rebuild — Home Workouts

Version 1.0.1. A self-contained home workout app built with inline HTML, CSS and JavaScript.

## Use

Open `index.html` in Chrome or Edge, or serve it from a static host. No installation, dependencies, build command, API keys or backend are required.

## Features

- Eight routines: dumbbell Full Body A/B, Upper A/B and Lower A/B, plus suspension and kettlebell full-body routines.
- Return to training and Standard workloads; Full and Short session options.
- Editable working weights, saved locally in the browser.
- JSON export/import for backup and transfer.
- Responsive layout and light/dark themes.

## Data

Weights and settings remain in the browser on each device. Hosting does not synchronise them. Export from the local-file app and import into the hosted app when moving to a domain. Keep backups before clearing browser data or changing domains.

## Hosting

Repository: https://github.com/twowindydev/workout

Deploy the repository as a static site on Vercel. The entry point is `index.html` at the repository root. No build step is needed. Configure the chosen custom domain in Vercel and add the DNS records it supplies in Cloudflare.

The downloaded HTML remains usable offline. Opening the hosted URL initially requires a connection; this version has no service worker for guaranteed offline access to the hosted app.

## Known issue

In Return to training mode, suspension and kettlebell Full/Short currently use the same prescription. This is recorded for a future update.

## Scope

This release has no workout history, completion tracking, timers, accounts or automatic device sync.
