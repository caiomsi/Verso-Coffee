# CLAUDE.md

This file provides guidance to Claude Code when working in this repository.

## What this is

Verso Coffee Roasters — an **agency demo** (fictional specialty coffee bar/roastery,
Portland OR). Static HTML/CSS/JS, no build step. See the root `../CLAUDE.md` for
shared conventions.

## Structure

`index.html` at root, `css/style.css`, `js/main.js`, photos in `images/`
(`verso-barista-steaming-milk.jpg`, `verso-espresso-bar-interior.jpg`,
`verso-espresso-extraction.jpg`, `verso-flat-white-latte-art.jpg`,
`verso-roasted-coffee-beans.jpg`). No custom domain yet
(`caiomsi.github.io/Verso-Coffee`).

## Design language

Dark editorial print aesthetic — "verso" = the left-hand page in print typography.
Espresso-black/bone/copper palette (`--copper #c98548`, `--copper-bright #e0a068`
used for accents and italic highlights). Type: Instrument Serif + Archivo + IBM Plex
Mono. Imagery generated with **Higgsfield**.

## Contact form — wired

POSTs to the shared `MSI-Forms` backend (`https://forms.caiomsi.com/api/submit`,
`site: verso-coffee`) from `js/main.js`.
