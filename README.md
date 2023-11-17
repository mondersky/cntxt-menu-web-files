# Windows 10 New File Menu Enhancements with web dev file types

This repository provides a simple yet powerful utility to web developers. A pack of registry scripts to enhance the Windows 10 context menu when right-clicking in File Explorer. The script adds options to create new PHP, HTML, CSS, and JS files directly from the context menu.

![demo](docs/demo.gif)

## Installation

1. Clone or download this repository to your local machine.

2. Run the registry file respective to the new file you want to add.

## How do I remove an item from the "new" section of the context menu?

1. press windows + r

2. run "regedit"

3. navigate to HKEY_CLASSES_ROOT

4. look for the extension name (ex .php) and expand it

5. look for ShellNew and delete it


