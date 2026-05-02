# Recorder Share Page

Public share page for the [Screen Recorder Chrome extension](https://github.com/faizansikander/screen-recorder).

Hosted via GitHub Pages at: https://faizansikander.github.io/recorder-share/

The page uses Supabase's public anon key (safe to expose — RLS policies enforce all access control) to fetch and play recordings shared via the extension.

## Update

After editing `index.html`:
```
git add . && git commit -m "Update share page" && git push
```
GitHub Pages picks up the change in ~1 minute.
