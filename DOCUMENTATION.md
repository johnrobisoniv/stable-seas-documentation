# Stable Seas Interface

# Documentation Brainstorm

Overall code structure

- Issue Areas
- Regions

The Load process

- index.html
- Which scripts in what order

Dependent Libraries and Frameworks

- D3.js
- v4
- color
- interpolate
- scale-chromatic
- jQuery
- topojson.js
- Bootstrap

# Site Structure

Issue areas and regions Anatomy of a page

- Nav header and footer
- Interactive map
- Card menu
- Cards

# Scripts

## `/js/main.js`

The `main.js` file both defines many of the variables and functions that the interactive interface relies on and executes the sequence of events that dynamically builds the interface on page load.

## #

- /js/modal-video.js -

# Data sources

- /data/main-data.js
- /data/{issue area}/{issue area}-data.js
- /data/regions-data.js
- /data/{issue area}/{issue area}.csv
- Google Drive

# Content

For content contributors to update the content on the site, follow the following process:

## Setup

1. Create a github account.
2. [Fork](https://help.github.com/articles/fork-a-repo/) the [Stable Seas base branch](https://github.com/johnrobisoniv/stable-seas) repository.
3. Clone your fork of the repository to your local machine. (You will have to use the git command line interface or download Github Desktop. This is possible on Windows, Mac and Linux).
4. (If you're using Github Desktop) Add the project folder to Github Desktop.
5. Download [Atom](https://atom.io/) or your favorite text editor.
6. Add the base repository (**not your fork**) as one of the remote repositories on your local repo:<br />

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On the command line:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`git add remote upstream https://github.com/johnrobisoniv/stable-seas.git`

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In Github Desktop:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

## Updating Content
### Content Creators
1. Open the project folder in Atom (or your text editor).
2. *Best Practice: update your local master branch to reflect the upstream/master (AKA base) branch. This will minimize the risk of conflicts*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`git fetch upstream`

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`git reset --hard upstream/master`

**This should make your local master branch look exactly the same the base master branch - now your local codebase is identical to the production version.**

3. Make the changes you need to make to the content files.
4. Commit changed files to your local `master` branch.
5. Push local `master` to your remote repository's `origin/master` branch. (You should now see your changes reflected on the files on your github account forked repo.)
6. Submit a pull request to the base branch (https://github.com/johnrobisoniv/stable-seas) and let the base branch owner know, especially if time sensitive.

### Site Administrator
1. Keep the base `master` branch up to date with the production server version of the site.
2. Monitor email / github for pull requests from content creators.
3. When a pull request is received, review changes and merge. *You may have to resolve conflicts if they exist.*
4. `git pull` the `master` branch from your origin repository to your local `master`.
5. Deploy the updated code onto the production server.
**Now the up-to-date version of the site is synced with the production server, your origin master branch on github and your local machine's master branch.**
**We think it is important to close this process (i.e. merge the pull request) before initiating another revision process. We suspect this will create conflicts or complicated merge processes.**
