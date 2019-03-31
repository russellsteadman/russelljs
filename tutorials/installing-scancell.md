---
title: How to Install Scan Cell
redirect_from: 
    - /scancell
---
# How to Install Scan Cell

This guide will walk you through how to install, build, and host Scan Cell.

## Instructions

Make sure git, Node.js, and Yarn are installed on your build machine. They are not required to serve the code.

#### Packages:
* [Git SCM](https://git-scm.com/downloads)
* [Node.js](https://nodejs.org/en/download/)
* [Yarn Package Manager](https://yarnpkg.com/en/docs/install)

### Step 1: Clone Repository

```sh
git clone https://github.com/teamtofu/scancell.git
cd scancell
```

### Step 2: Install Dependencies

```sh
yarn install
```

### Step 3: Set Your URL

Replace `https://scancell.osu.edu/` with the exact URL that will be used to serve Scan Cell. The URL **must** have a trailing slash. If you plan to use a subdirectory, specify it, (e.g. `https://nano.osu.edu/scancell/`).

Windows:
```sh
set PUBLIC_URL=https://scancell.osu.edu/
```

Linux and MacOS:
```sh
export PUBLIC_URL=https://scancell.osu.edu/
```

### Step 4: Build the Website

```sh
yarn build
```

### Step 5: Host the Website

The website is now available in the `docs/` subfolder. It is entirely static and can be hosted using virtually any hosting service. For an easy and free option, you can use [GitHub pages](https://pages.github.com/).

## Contact

Feel free to contact me at [steadman.21@osu.edu](mailto:steadman.21@osu.edu).