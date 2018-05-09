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
2. Fork the [Stable Seas base branch](https://github.com/johnrobisoniv/stable-seas) repository.
3. Clone your fork of the repository to your local machine. (You will have to use the git command line interface or download Github Desktop. This is possible on Windows, Mac and Linux).
4. Add the project folder to Github Desktop.
5. Download [Atom](https://atom.io/) or your favorite text editor.
6. Add the base repository (**not your fork**) as one of the remote repositories on your local repo.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`git add remote upstream https://github.com/johnrobisoniv/stable-seas.git`

## Updating Content

1. Open the project folder in Atom (or your text editor).
2. *Best Practice: update your local master branch to reflect the upstream/master (AKA base) branch. This will minimize the risk of conflicts*
3. Make the changes you need to make to the content files.
4. Commit changed files to your local `master` branch.
5. Push local `master` to your remote repository's `origin/master` branch. (You should now see your changes reflected on the files on your github account forked repo.)
6. Submit a pull request to the base branch (https://github.com/johnrobisoniv/stable-seas) and let the base branch owner know, especially if time sensitive.
