# ClankerShield

ClankerShield is a browser extension that filters low-signal tech content before it reaches your feed.

It helps users hide or reduce posts and comments that look like:

- AI slop
- fake tech influencer content
- career doomposting
- ragebait
- hustlebait
- gender-targeted hostility
- engagement farming

## Problem

Tech feeds are increasingly filled with content designed to provoke anxiety, outrage, comparison, or clicks.

ClankerShield gives users more control over their attention by detecting manipulative or low-quality patterns in posts and comments.

## Features

### MVP

- Detect Reddit posts and comments
- Score content with rule-based filters
- Label suspicious content
- Dim, collapse, or auto-hide filtered content
- Let users adjust filter sensitivity
- Save preferences locally

## Filter Categories

- AI Slop
- Fake Guru Content
- Career Anxiety Bait
- Doomposting
- Ragebait
- Hustlebait
- Gender Hostility
- Low-Signal Influencer Content

## Planned Presets

- Student Mode
- Women in Tech Mode
- Founder Mode
- Deep Work Mode
- Job Search Mode

## Tech Stack

- TypeScript
- React
- Chrome Extension Manifest V3
- Chrome Storage API
- CSS

## Roadmap

- [ ] Set up Chrome extension
- [ ] Add Reddit content script
- [ ] Detect post containers
- [ ] Detect comment containers
- [ ] Build rule-based scoring engine
- [ ] Add visible warning labels
- [ ] Add dim/collapse/hide options
- [ ] Build popup settings UI
- [ ] Save user settings locally
- [ ] Add custom keyword filters
- [ ] Add analytics dashboard
- [ ] Add support for LinkedIn, X, YouTube, and Hacker News
- [ ] Explore optional ML-based classification

## Example

A post like:

> "CS is dead. If you are still studying computer science, you already lost."

could be labeled as:

```txt
Career Anxiety Bait + Doomposting
