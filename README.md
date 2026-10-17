# Monroe in Focus

*Every meeting. Every decision. In focus.*

An independent, plain-language site covering local government in Monroe Township, Middlesex County, New Jersey — built from the township's own public meeting recordings.

**Not affiliated with, endorsed by, or operated by Monroe Township, Middlesex County, or any government body.**

## Why this exists

Monroe Township and its school district post full video of their public meetings, but a two-hour meeting full of ordinance numbers and procedural language is a lot to ask of anyone with a job and a family. This site condenses each meeting into a short, plain-language article that explains terms and context as it goes, rather than assuming the reader already follows local politics.

## Structure

```
index.html          Home page — latest stories, Around Monroe, next meeting
archive.html         All stories, newest first
about.html            What this project is and isn't
news/                 Individual meeting recap articles
styles.css            Shared stylesheet
```

## Adding a new meeting recap

1. Copy a recent file in `news/` (for example `news/monroe-council-meeting-2026-10-05.html`) as a template.
2. Update the headline, dek, quick-facts box, and body from the new meeting's transcript.
3. Add a new `<article class="story-card">` entry to both `index.html` (newest first) and `archive.html` (added above the previous entries).
4. Commit and push — GitHub Pages redeploys automatically.

## Corrections

Open an issue on this repository if something is wrong or misleading.
