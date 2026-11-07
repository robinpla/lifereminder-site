# Life Reminder — website

One-page landing site for the Life Reminder Android app, hosted free on GitHub Pages.

## Before you publish — three placeholders to fill in

Search the files for these and replace them (they appear in `index.html` and `privacy.html`):

| Placeholder      | Replace with                                                        |
|------------------|---------------------------------------------------------------------|
| `PLAY_URL`       | Your Play Store link, e.g. `https://play.google.com/store/apps/details?id=YOUR.PACKAGE.NAME` |
| `SITE_URL`       | The site's address, no trailing slash, e.g. `https://USERNAME.github.io/lifereminder` |
| `EFFECTIVE_DATE` | Today's date, in `privacy.html`                                     |

Also read `privacy.html` once and make sure every sentence is true of the app as shipped.

Optional: replace `assets/phone1.png` … `phone6.png` with your original transparent renders (the ones here had their backgrounds keyed out from flattened copies).

## Publish on GitHub Pages (about 5 minutes)

1. On GitHub, create a new **public** repository. Name it `lifereminder` (or anything — the name becomes part of the URL).
2. Put everything in this folder at the root of the repo (so `index.html` is at the top level, not inside a subfolder). Commit and push.
3. In the repo: **Settings → Pages**. Under *Build and deployment*, set **Source** to *Deploy from a branch*, pick `main` and `/ (root)`, click **Save**.
4. Wait a minute or two. The page shows your URL: `https://USERNAME.github.io/lifereminder/`.
5. Go back and fill in `SITE_URL` with that address (step above), commit, push again.

## After it's live

- **Google Play Console** → Account details → Website: paste the site URL. (Also set it under your app's *Store settings* so it shows on the listing.)
- **Play Console** → your app → *Privacy policy*: paste `https://…/privacy.html`.
- **Google Search Console** (free, search.google.com/search-console): add the site as a URL-prefix property, verify with the HTML-tag method (paste the tag into `<head>` of `index.html`), then *URL inspection → Request indexing*. This gets you into Google in days instead of months.
- Optional: do the same at Bing Webmaster Tools (it also feeds DuckDuckGo).

## Editing later

It's plain HTML and CSS in one file. Change the text, commit, push — the site updates in about a minute.
