# Sync Contacts with Notes

In this demo, we’ll sync contacts from a Apple Contacts group named "Shortcuts demo" with Obsidian.

The end result will be a single note for each contact, with up-to-date contact details in the front matter. When the workflow is run again, it’ll find existing notes and update them, and if it finds contacts without a note, it’ll create a new one. The entries in Contacts will gain a clickable link to the Obsidian note.

[Screenshot of the workflow](<Sync Contacts with Notes.png>)

&nbsp;

## Download

[Download Apple Shortcuts workflow `Sync Contacts with Notes.shortcut`](<Sync Contacts with Notes.shortcut?raw=1>)

Double-click the downloaded file to install the workflow in Shortcuts.

&nbsp;

## Author & Copyright

This workflow is part of the [**Actions for Obsidian** Workflow Library](https://obsidian.actions.work/workflows).

&copy; Carlo Zottmann, https://github.com/czottmann, [MIT license](../LICENSE).

&nbsp;

## Workflow history / Change log

### 2024-02-27

Checks whether contact has phone or email before attempting to add them to the dictionary.

### 2023-12-11

- Uses Obsidian 1.4+ file properties instead of writing YAML
- Uses Contacts' own Shortcuts action for storing the Obsidian note URLs for contact
- Obsidian note URLs in Contacts are stored under the label "URL" now (was: "Obsidian note"). It's a result of using Contacts' own actions.


### 2023-03-17

- Adds support for contacts that have more than one phone number or mail address. Numbers and addresses are added to the front matter as YAML lists (`[1, 2, 3]`) now.


### 2023-02-03

- First version.
