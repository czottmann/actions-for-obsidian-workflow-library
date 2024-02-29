# Notes for Calendar Events

This workflow will do the following:

1. Fetches a list of all events for today from a single calendar.
1. For each event in this list, a new related note will be created in Obsidian, containing key details, in a folder named "Meeting Notes".
1. The link to the Obsidian note will be appended to its related event.
1. All new notes will be appended to the current Daily Note.

Please note _(pun not intended)_: The workflow assumes there’s a current daily note.

[Screenshot of the workflow](<Notes for Calendar Events.png>)

&nbsp;

## Download

[Download Apple Shortcuts workflow `Notes for Calendar Events.shortcut`](<Notes for Calendar Events.shortcut?raw=1>)

Double-click the downloaded file to install the workflow in Shortcuts.

&nbsp;

## Author & Copyright

This workflow is part of the [**Actions for Obsidian** Workflow Library](https://obsidian.actions.work/workflows).

&copy; Carlo Zottmann, https://github.com/czottmann, [MIT license](../LICENSE).

&nbsp;

## Workflow history / Change log

### 2024-02-29

Adjusts vault handling to work with AFO 2024.1.


### 2023-03-17

Fixes the mystery of the silently failing "If" block for calendar entries with an empty Notes attribute. Thanks to TK for the heads-up!


### 2023-02-03

First version.
