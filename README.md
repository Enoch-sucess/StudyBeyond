# StudyBeyond

A study-abroad finder for Nigerian students looking for affordable master's degrees abroad. Students enter their preferences and get ranked university recommendations they can search, filter, and save to a shortlist.

**Track:** Frontend Development
**Stack:** React, Vite, JavaScript, Tailwind CSS
**Live demo:** (https://studybeyond-7f58me1m1-enoch-s-projects2.vercel.app/)

## Project documents

- [Idea one-pager and work plan (Google Drive)](https://drive.google.com/drive/folders/1N9-ZuAehsnSLc7eEGA-0wo2Hi9MstgSA?usp=sharing)

## The problem

Programme details, tuition fees, and scholarship information for universities abroad are scattered across many websites. This makes it hard for students to compare reliable information and find universities that match their goals and budget.

## Core flow

Home → Preference Questionnaire → Recommendations → University Details → Shortlist

## Current status

| Week | Focus                                                | Status      |
| ---- | ---------------------------------------------------- | ----------- |
| 1    | Recommendations results screen, search and filters   | In progress |
| 2    | Components, data fetching, questionnaire             | Not started |
| 3    | Routing, shortlist, tests, accessibility, deployment | Not started |

## Getting started

**Requirements:** Node.js 18 or later

```bash
git clone PASTE_REPO_URL_HERE
cd PASTE_REPO_FOLDER_NAME_HERE
npm install
npm run dev
```

Then open the local URL shown in the terminal.

### Scripts

| Command           | What it does                          |
| ----------------- | ------------------------------------- |
| `npm run dev`     | Starts the development server         |
| `npm run build`   | Creates a production build            |
| `npm run preview` | Previews the production build locally |

_A test command will be added and documented in Week 3._

## Data

University data comes from a curated JSON file that I compile from official university websites. Tuition figures are annual estimates converted to USD, and each record keeps its source link and verification date.

- Unknown tuition is labelled "Fee unknown". It is never treated as zero or as affordable.
- Match scores show how closely a university fits a student's preferences. They are not admission or scholarship guarantees.
- Always confirm current fees and requirements on the official university website.

## Features

_To be filled in as features are completed._

## Technical decisions

_To be filled in as decisions are made (scoring weights, state handling, data structure)._

## Component structure

_Component map to be added in Week 2._

## Testing

_Testing instructions to be added in Week 3._

## Accessibility

_Before and after Lighthouse or axe results to be added in Week 3._

## Known limitations

_To be updated throughout development._

## Use of AI

I used AI tools for planning feedback and for design inspiration for the initial screen mockup. I wrote the application code myself. _(Keep this accurate and update it if your use changes.)_

## Author

Inioluwa Enoch Oladele
[GitHub](https://github.com/Enoch-sucess) · [LinkedIn](https://linkedin.com/in/enoch-oladele-7bb30a201)
