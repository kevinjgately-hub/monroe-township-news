# Monroe Township News

An independent, plain-language news site covering local government in Monroe Township, Middlesex County, New Jersey — built from the township's own public meeting recordings.

**Not affiliated with, endorsed by, or operated by Monroe Township, Middlesex County, or any government body.**

## Why this exists

Monroe Township posts full video of every council meeting, but a two-hour meeting full of ordinance numbers and procedural language is a lot to ask of anyone with a job and a family. This site condenses each meeting into a short, plain-language article that explains terms and context as it goes, rather than assuming the reader already follows local politics.

## Structure

```
index.html          Home page — latest story + project blurb
archive.html         All stories, newest first
about.html            What this project is and isn't
news/                 Individual meeting recap articles
styles.css            Shared stylesheet
```

## Adding a new meeting recap

1. Copy `news/monroe-council-meeting-2026-08-03.html` as a template.
2. Update the headline, dek, quick-facts box, and body from the new meeting's transcript.
3. Add a new `<article class="story-card">` entry to both `index.html` (replacing the "Latest" card) and `archive.html` (added above the previous entries).
4. Commit and push — GitHub Pages redeploys automatically.

## Corrections

Open an issue on this repository if something is wrong or misleading.
