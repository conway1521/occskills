# occskills

One notebook, `OccProfiles.ipynb`, that looks at how the skills that occupations ask for have moved over 2018-2023, and takes a first attempt at answering where they are heading.

The data is Lightcast skill exports, split by skill type (software, common, specialized, defining, distinguishing, and so on). It is not available in the repo as is proprietary to Jobs for the Future, (JFF). The notebook reads a handful of CSVs from their local paths, but the codebase can be updated with a new user's own Lightcast data.

Rough order of things: clean the raw exports, build a profile per occupation, plot the skill trends and how the type mix shifts, then put posting demand next to growth projections to see where they agree and where they don't. The last two sections, a short forecast and some automation scenarios, are unfinished.

Tech stack includes pandas and plotly-dash.
