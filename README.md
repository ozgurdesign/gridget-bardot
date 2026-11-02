# Gridget Bardot

A Mac menu-bar app that draws guides and layout grids over your whole screen.

**[Download the latest version](https://github.com/ozgurdesign/gridget-bardot/releases/latest)** · [ozgur.ca](https://ozgur.ca/projects/gridget-bardot)

## What it does

- **Guides** sit above every window, the menu bar, the Dock and full-screen apps. Clicks pass straight through them.
- **Add one at a time** at the pointer with ⌃⌥⌘V (vertical) or ⌃⌥⌘H (horizontal).
- **Add several at once.** Spread a number of guides evenly across a range, or lay out a grid by width, columns, margin and gutter.
- **Edit mode** (⌃⌥⌘E) shows each guide's position and the gap between neighbours. Drag a guide, nudge it with the arrow keys, or click a number and type an exact value.
- **16 colours**, and guides stay where you left them after a restart.

Positions are in points, measured from the top-left corner of each screen. At 100% zoom a point equals a CSS pixel.

## Shortcuts

| Action | Keys |
| --- | --- |
| Vertical guide at the pointer | ⌃⌥⌘V |
| Horizontal guide at the pointer | ⌃⌥⌘H |
| Edit guides | ⌃⌥⌘E |
| Show or hide guides | ⌃⌥⌘G |

In edit mode, drag a guide to move it, double-click to remove it, use the arrow keys to nudge it (Shift for 10), and press Esc when done.

## Download

Each release has one disk image, `GridgetBardot-<version>.dmg`, for macOS 14 Sonoma and later, on Apple silicon and Intel.

The "Source code" links GitHub adds to every release only contain this README and the licence. The app is the `.dmg`.

## First launch

Gridget Bardot is not notarized by Apple, so macOS asks before opening it the first time.

1. Open the disk image and drag Gridget Bardot to Applications.
2. Open Gridget Bardot once. macOS says it can't check the app.
3. Go to System Settings › Privacy & Security and click Open Anyway.

You only need to do this once.

## Privacy

Gridget Bardot needs no permissions and has no network access. Nothing is collected.

## About this repository

This repository hosts releases only. The source code is not public, and issues and pull requests are turned off.

## Licence

Gridget Bardot by [Oz Gultekin](https://ozgur.ca) is licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/). See [LICENSE](LICENSE).
