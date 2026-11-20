# CCHS Senior Assassin 26-27

Player site for Cherry Creek High School Senior Assassin, Class of 2027.

`index.html` is the whole site in one file: Today, My Account, Teams, Calendar and Rules tabs. Open it in a browser; it needs no server or build step.

## How login works

- Players log in with their **team access code** (`XXXX-XXXX`), sent by the coordinators. Name and Instagram login was removed on Nov 20, 2026.
- Targets are stored in `DATA.vault`, encrypted per team code. The codes themselves are not in this repo, so the page only reveals a target to someone who has that team's code.
- Round 1 targets were re-drawn at random on Nov 20, 2026.

## Do not commit

Access codes, the organizer sheet, the full target list, or the admin page. This repo is public.
