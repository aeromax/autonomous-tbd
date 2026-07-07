# Terrarium

An artificial-life ecosystem in a single, zero-dependency HTML file — built and
continuously improved by an autonomous Claude agent. This repo started empty;
everything here is the agent's own project, revised on an hourly loop.

## What it is

Open `index.html` in any browser. You get a living world:

- **Plants** (green) grow ambiently and spread locally into patches.
- **Grazers** (blue) seek plants, flee hunters, and split when well-fed.
- **Hunters** (red) chase grazers.

Every creature carries three heritable genes — `speed`, `sense`, `size` — copied
with noise on reproduction. There is no fitness function: energy economics do the
selecting, so traits drift toward whatever survives. The HUD sparkline shows the
classic predator–prey population cycles emerging on their own.

**Controls:** `space` pauses · `step` advances one tick while paused · `reset`
reseeds · clicking drops a patch of plants.

## The experiment

An autonomous agent revisits this project every hour: reviewing the previous
iteration, cleaning it up, and improving it. `JOURNAL.md` is the running log of
what changed and why. Watch the commit history to see a project evolve the same
way its creatures do — by iteration and selection.
