# channel-pages

The pages that go with the videos, plus the files viewers take with them.

**Start here:** https://alexander-domanov.github.io/channel-pages/

## Videos

| # | Page | What it covers |
|---|---|---|
| 01 | [Voiceover for free instead of $22 a month](https://alexander-domanov.github.io/channel-pages/v/01-local-voice/) | Two open models on an 8 GB laptop |

## How this repo is laid out

```
index.html                 the list of videos, with a search box
style.css                  shared styles for every page
v/01-local-voice/          one folder per video: NN-slug
  index.html               the page the link opens
  README.md                the same thing in Markdown, for reading on GitHub
  files/*.html             the downloads
```

Two ways in, on purpose:

- **From a video description** → the GitHub Pages link. That's a real page: designed, searchable from
  the list, works on a phone.
- **From GitHub** → this README. GitHub shows HTML files as source code, so the links above are the
  ones to hand out, not the files in the folders.

## Rules

- One folder per video, numbered the same as in the private base.
- A page goes live with the video, never before it.
- English, conversational American. Pages, commit messages, repo description.
- Commit messages in English too.
- No external fonts, no third-party scripts. The search box is a few lines of inline JavaScript.
- Anything over 10 MB goes in Releases, not here.
- Other people's prompts and files never go up, only ours.

## Adding a video

1. Copy the previous video's folder and rename it `v/NN-slug`.
2. Replace the text with what's actually on screen in the video.
3. Add a card to `index.html` and a row to the table above.
4. Commit and push. Pages rebuilds in about a minute.
