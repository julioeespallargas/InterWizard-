# Job Interview Simulator – concept prototype

Interactive prototype of a B2C job interview rehearsal service, made for **Simulation Wizard** as part of the *Service Design* course at **Laurea University of Applied Sciences** (autumn 2026).

> Concept prototype only. All interview data is example data, and the live interview is not switched on.

## What makes it different

| | Typical interview apps | This concept |
|---|---|---|
| Practice | Lists of questions | Scenarios with a person, a goal and a twist (quiet manager, language switch, salary question, panel…) |
| Feedback | Filler words and eye contact | A guided **debrief** based on simulation pedagogy: reactions, what happened, what it shows, next time |
| Outcome measured | Speech metrics | **Nerves before and after** each rehearsal |
| Planning | Open-ended | **Countdown** to your real interview date with a day-by-day plan |
| Market | English, US hiring | Finnish, Swedish, English and Spanish, built for interviews in Finland |
| Price | Monthly subscription | Pay per interview: a 14-day sprint |

## Features in the prototype

- Sign-up, plans (free rehearsal, interview sprint, ongoing) and optional VR / 360 add-on
- Interview date setup and personal rehearsal plan
- 7 scenarios with pressure levels that unlock as you level up
- Briefing with nerves self-rating, room view, and a 4-phase debrief
- Progress: levels and XP, nerves chart, skills, current and previous sectors, badges
- Interface in English, Finnish and Spanish
- Works on desktop and mobile; progress is stored in the browser (localStorage)

## Run it

No build step and no dependencies. Open `index.html` in a browser.

## Publish with GitHub Pages

1. Create a new repository on GitHub and upload `index.html` (and this README).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute the site is live at `https://<your-user>.github.io/<repository-name>/`.

## Structure

```
index.html    the whole app in one file: HTML, CSS, JavaScript,
              the logo and the Barlow fonts are embedded, so nothing else is needed
.nojekyll     tells GitHub Pages to serve files as they are
```

## Credits

- Simulation Wizard logo and brand belong to Simulation Wizard and are used only for this course project with the client.
- Fonts: Barlow by Jeremy Tribby, SIL Open Font License 1.1.
- Team: Laurea UAS Service Design students.
