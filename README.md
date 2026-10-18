# Towns in Focus

*Every meeting. Every decision. In focus.*

Towns in Focus is an independent, plain-language news project covering local government, built from towns' own public meeting recordings and records. It is **not affiliated with, endorsed by, or operated by** any town, county or government body.

Live at **https://townsinfocus.com/**

## Sites

| Town | Site | Folder |
|---|---|---|
| Monroe Township, Middlesex County, NJ | [Monroe in Focus](https://townsinfocus.com/monroe-nj/) | `monroe-nj/` |

Each town lives in its own subfolder (`/<town>-<state>/`) with its own home page, archive, coverage page, about page, stylesheet and `news/` folder.

## Structure

```
index.html            Towns in Focus landing page
404.html              Not-found page
sitemap.xml           Sitemap for search engines
robots.txt            Points crawlers at the sitemap
CNAME                 Custom domain (townsinfocus.com), managed by GitHub Pages
archive.html, about.html, coverage.html, news/*.html
                      Redirect stubs that send old addresses to /monroe-nj/
monroe-nj/
  index.html          Monroe home: latest stories, Around Monroe, next meeting
  archive.html        All Monroe stories, newest first
  coverage.html       Which township bodies are covered, and how
  about.html          What the project is and isn't, how stories are made, privacy
  styles.css          Shared stylesheet
  news/               Individual recap articles
```

## Adding a new recap

1. Copy a recent file in `monroe-nj/news/` as a template (for example a council recap).
2. Update the headline, dek, quick-facts box and body from the meeting's official recording or records.
3. Add a story card to `monroe-nj/index.html` and `monroe-nj/archive.html` (newest first), and update `monroe-nj/coverage.html` if coverage changed.
4. Add the new page to `sitemap.xml`.
5. Commit and push. GitHub Pages redeploys automatically.

## Adding a new town

Create a new subfolder (for example `/<town>-<state>/`) by copying the Monroe folder, update its pages, link it from the landing page `index.html`, and add its pages to `sitemap.xml`.

## Privacy

Reading the site sets no cookies and does not track individual readers. It uses Cloudflare Web Analytics (a small beacon script at the bottom of each page) to count page views in aggregate.

The email signup page (`monroe-nj/subscribe.html`) is the one exception: it loads a MailerLite form and Google reCAPTCHA, which may set cookies on that page only. The MailerLite script is loaded only on that page. For a new town, create a new MailerLite group and form and embed it on that town's own subscribe page.

## Support link

The Buy Me a Coffee page (https://buymeacoffee.com/townsinfocus) is linked as a plain link from the Monroe home sidebar, About page and footer. No Buy Me a Coffee script or widget is loaded, so the site sets no cookies for it.

## Corrections

Open an issue on this repository if something is wrong or misleading.
