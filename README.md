# occskills

One notebook, `OccProfiles.ipynb`. It looks at how the skills that occupations ask for have moved over 2018-2023, and takes a first swing at where they're heading.

The data is Lightcast skill exports, split by skill type (software, common, specialized, defining, distinguishing, and so on). It's not in the repo. The notebook reads a handful of CSVs off local paths, so if you want to run it you'll need to point those at wherever your own copies sit.

Rough order of things: clean the raw exports, build a profile per occupation, plot the skill trends and how the type mix shifts, then put posting demand next to growth projections to see where they agree and where they don't. The last two sections, a short forecast and some automation scenarios, are unfinished and marked as such.

Mostly pandas and the usual plotting stack. Nothing to install beyond that.
