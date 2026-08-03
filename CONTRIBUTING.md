# Contributing to Awesome Free University AI/ML Course Notes

Thanks for wanting to contribute! This list has an unusually strict bar on purpose — please read this before opening a PR or issue.

## What counts as a valid entry

An entry qualifies if **all** of the following are true:

- [ ] **Written prose notes.** The material reads like a textbook chapter or a monograph — explanatory text, not just bullet points on a slide. If you could plausibly print it and read it away from a lecture, it qualifies. If it's a PDF export of a slide deck, or a link to a recorded lecture with no accompanying written text, it does **not** qualify — even if it's excellent, official, and free.
- [ ] **Official.** Published by the instructor, the course, or the department — not a student's personal study notes, not a third-party summary (even a very good one).
- [ ] **Free and permanent.** No login, no institutional email, no "request access" form that might be denied, no time-limited availability.
- [ ] **Primary source.** The link goes directly to the professor's page, the course's own site, or the department's site — never a note-sharing platform like Studocu, Course Hero, Scribd, or similar, even if the material originated from an official course.

### Why the "written notes only" rule

This project exists to document something specific and genuinely rare: departments that write and publish their own notes as a textbook replacement (the pattern popularized by MIT 6.390, Harvard CS181, and Princeton COS 324). Slides and video lectures are common and valuable, but they're a different category of resource — and including them would make this list indistinguishable from "any free ML course," which already has many good directories elsewhere. Keeping the bar high is what makes this list useful.

### Explicitly not allowed

- Slide decks (PDF or PPT), even if labeled "lecture notes" by the course.
- Video-only courses (MOOCs, YouTube lecture series) without a written companion text.
- Personal student notes, even if well-written and publicly shared (e.g., a GitHub repo of someone's own study notes from taking the course).
- Material behind a university login, Moodle/Canvas portal, or "request access" gate.
- Note-sharing / study-aid platforms (Studocu, Course Hero, Scribd, CourseHero, Chegg, etc.) — link to the actual course page instead, if one exists.

## How to add an entry

1. **Fork** the repository and create a branch.
2. Add a single row to the correct country table in `README.md` (or create a new `##` country section if needed), in alphabetical order by university name within that section.
3. Use this row format:

   ```markdown
   | University Name | Course Code – Course Title | Instructor(s) | [domain.edu](https://full-url) |
   ```

4. **One entry per pull request.**
5. In your PR description, confirm the entry meets the checklist and link to where you verified it's written prose (not slides) and official.

## Suggesting a university that doesn't currently have an entry

Check the "Universities checked, no qualifying entry" list at the bottom of the README first — if it's already there, we looked and didn't find anything at the time. Things change (a new professor might publish new notes), so feel free to re-check and open an issue if you find something that now qualifies.

## Reporting a broken link

Open an [issue](../../issues/new/choose) with the university, course, current link, and what's wrong.

## Code of Conduct

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md). Disagreements about whether something counts as "written notes" vs. "slides" are normal — when in doubt, open an issue to discuss before investing time in a PR.
