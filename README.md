# channel-pages

The pages that go with the videos, plus the files viewers take with them. This repo is public, so
only what a viewer needs after watching goes in here. Drafts, measurements and club links stay in
the private `channel-base`.

## Layout

```
index.html                 list of videos
style.css                  shared page styles
v/01-local-voice/          one folder per video: NN-slug
  index.html               the steps from the video
  files/*.html             the downloads
```

## Rules

- One folder per video, numbered the same as in the private base.
- A page goes live with the video, never before it.
- Everything in English, conversational American. Write it the way you'd say it out loud.
- Commit messages in English too.
- No external fonts, no scripts. The page has to work offline and on a phone.
- Anything over 10 MB goes in Releases, not here.
- Other people's prompts and files never go up, only ours.

## Adding a video

1. Copy the previous video's folder and rename it `v/NN-slug`.
2. Replace the text with what's actually on screen in the video.
3. Add a line to `index.html`.
4. Commit and push. Pages rebuilds in about a minute.
