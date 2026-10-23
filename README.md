# Fixopolis

Fixopolis is a civic issue reporting app prototype for **SDG 11: Sustainable Cities and Communities**. It was made for the INFO3315 Human–Computer Interaction group project at the University of Sydney (2026).

Residents report problems such as potholes, dumped rubbish or broken streetlights. They can then follow each report's progress and bump a neighbour's report to show it affects them too.

## Try it

- **Interactive prototype:** https://olibolib.github.io/fixopolis/ (best in Chrome or Edge on a laptop)
- **Clickable PDF prototype:** [Download](https://github.com/olibolib/fixopolis/raw/main/pdf/fixopolis-blueprint-user-testing.pdf) · [Open in browser](https://olibolib.github.io/fixopolis/pdf/fixopolis-blueprint-user-testing.pdf). Every button works, with progress pages between tasks.
- **Design document:** [Download](https://github.com/olibolib/fixopolis/raw/main/docs/fixopolis-design-document.pdf) · [Open in browser](https://olibolib.github.io/fixopolis/docs/fixopolis-design-document.pdf)

GitHub's own file preview turns the PDF links off. Either download the file and open it in Adobe Acrobat or the Chrome/Edge PDF viewer, or use "Open in browser" (this needs GitHub Pages switched on).

## Test tasks

1. You have noticed a pothole on the road outside your home. Report it to the council.
2. A few weeks ago you reported a broken footpath on Hill St. Find out what is happening with it.
3. A neighbour has already reported a broken streetlight on Wattle St. It affects you too. Show your support for their report.

## Usability test mode (interactive prototype)

On the start screen, switch on **Test mode**. The prototype runs the three tasks in order. After each task, a progress panel appears over the finished screen, and Continue picks up from there. It records time, taps, wrong taps and back presses for each task, then shows the SUS questionnaire. In Chrome or Edge you choose a results folder once, and `results_tasks.csv` and `results_survey.csv` fill in automatically with an incrementing participant ID.

### Collecting results on GitHub

At the end of each session, press **Send results to GitHub** on the thank-you screen, then **Submit new issue** on the page that opens. You need to be signed in to GitHub with access to this repo. Each participant becomes one issue titled `[Test results] P1, …`, containing:

- a table of task results
- the SUS answers and score, and the participant's comment
- the raw CSV rows in a collapsible block, ready to paste into one combined spreadsheet

Participant numbers count up on each testing laptop separately, so if you test on more than one laptop, use the date and time in the issue title to tell sessions apart. The repo is public, so results posted here are visible to anyone. They contain no names.

## Files

| Path | What it is |
|---|---|
| `index.html` | The interactive prototype, served by GitHub Pages |
| `prototype/fixopolis-blueprint.html` | The same prototype, to download and open locally |
| `pdf/` | Clickable PDF prototype (download it to use the links) |
| `docs/` | Design document |

All data in the prototype is fictional (Elmwood is not a real suburb).
