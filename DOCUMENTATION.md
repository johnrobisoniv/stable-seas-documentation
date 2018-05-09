Stable Seas Interface
=====================

# Documentation Brainstorm

Overall code structure
- Issue Areas
- Regions

The Load process
- index.html
- Which scripts in what order

Dependent Libraries and Frameworks
- D3.js
* v4
* color
* interpolate
* scale-chromatic
- jQuery
- topojson.js
- Bootstrap


# Site Structure
Issue areas and regions
Anatomy of a page
- Nav header and footer
- Interactive map
- Card menu
- Cards

# Scripts

## ``` /js/main.js ```

The ```main.js``` file both defines many of the variables and functions that the interactive interface relies on and executes the sequence of events that dynamically builds the interface  on page load.

###

- /js/modal-video.js
-

# Data sources
- /data/main-data.js
* /data/{issue area}/{issue area}-data.js
- /data/regions-data.js
- /data/{issue area}/{issue area}.csv
- Google Drive


# Content

For content contributors to update the content on the site, follow the following process:

## Setup
1. Create a github account.
2. Fork the [Stable Seas](https://github.com/johnrobisoniv/stable-seas) repository.
3. Clone your fork of the repository to your local machine. (You will have to use the git command line interface or download Github Desktop. This is possible on Windows, Mac and Linux).
4. Add the project folder to Github Desktop.
5. Download [Atom](https://atom.io/) or your favorite text editor.
6. Add the master repository (**not your fork**) as one of the remote repositories on your local repo.

```git add remote upstream https://github.com/johnrobisoniv/stable-seas.git```

## Updating Content
1. Open the project folder in Atom (or your text editor).
2.
