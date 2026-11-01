# Convict Conditioning Tracker

A free workout tracker for bodyweight training in the style of *Convict Conditioning*. Log your reps, watch every set climb, and install it on your phone like an app.

**Open the tracker:** [https://thaqib-07.github.io/Convict-Conditioning-Tracker/](https://thaqib-07.github.io/Convict-Conditioning-Tracker/)

## What it does

- **Progression:** a graph for each exercise showing your reps for Set 1, Set 2 and Set 3 over your last 15 workouts. Tap a graph to see your full history from the start.
- **Input:** log reps and the date for each workout. The workout number is shown as you enter it.
- **Categories and exercises:** add, rename, move or remove them from the ⋮ menu.
- **Targets:** set a target rep goal for each exercise. It is shown above the graph.
- **Completed:** mark an exercise as completed and it moves to the bottom of the Progression page.
- **Backup:** share or download your data as a file, and import it again on any device.

## Install on your phone

1. Open the tracker link in Chrome on Android.
2. Tap the ⋮ menu and choose **Install app**.
3. Open it from your home screen. It also works offline.

On iPhone, open the link in Safari, tap Share, then **Add to Home Screen**.

## Your data

Everything is saved **only in your own browser**. There is no account and no server, and nobody else can see your workouts, including the author of this project.

This also means:

- Clearing your browser data erases your workouts.
- Each phone or browser keeps its own separate data.
- Use **Share backup** or **Download backup** in the Input tab to keep a copy, and **Import backup** to load it back.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app |
| `sw.js` | Lets the app install and work offline |
| `manifest.webmanifest` | App name and icons |
| `icon-*.png`, `apple-touch-icon.png` | App icons |

## Run it yourself

Download the files into one folder and host them anywhere that serves static pages, such as GitHub Pages. No build step is needed.
