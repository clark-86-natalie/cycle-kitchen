# Cycle Kitchen

Food for every phase of your cycle, and for perimenopause too.

Cycle Kitchen is a prototype web app that tells you what to eat for the phase of your cycle you're in today, and helps you prepare for the next one. It also offers phase-aware movement and sleep notes, supplement suggestions by life stage, and a dedicated perimenopause section.

**Try it:** https://clark-86-natalie.github.io/cycle-kitchen/

## Features

- **Today:** current phase and cycle day, foods to focus on (with easy ways to eat each one), a preview of the next phase, "Now's a great time to…", a sleep note, and extra tips for any symptoms logged today.
- **Cycle history:** pick the tracker you use now (Flo, Clue, Natural Cycles, Apple Health, Samsung Health, Garmin Connect or another app) for step-by-step export instructions and a link to its help page. Upload the export (JSON, CSV, XML or zip), or add period dates by hand, then keep logging in Cycle Kitchen.
- **Predictions:** next period from a weighted average of recent cycle lengths; ovulation about 14 days before it. Irregular cycles show a date range instead.
- **Dietary needs:** allergies are hard filters (nuts and seeds are separate); preferences such as vegetarian are soft filters. Seed cycling is swapped for seed-free foods for anyone with a seed allergy.
- **Logging:** one-tap period, symptom and sleep logging.
- **Perimenopause:** explainer, what helps, and a symptom-led mode for irregular cycles.
- **Supplements:** grouped by life stage, nudged only for ones you don't already take, with a monthly check-in.
- **Phase colours:** the whole app changes colour with your cycle phase.

## Data and privacy

In this version, everything you enter is saved in your own browser only. Nothing is sent to a server. Accounts that sync across devices are planned for a later version.

## Running it

It's a single `index.html` file with no build step. Open it in a browser, or serve the folder with any static host.

## Disclaimer

Cycle Kitchen is a prototype. Its suggestions are general wellbeing information, not medical advice.
