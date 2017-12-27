## Download URL
Go to https://github.com/atom/atom/releases/ and find the latest stable release and then download `atom-x64-windows.zip` file 
for Windows or `atom-mac.zip` for Mac OS.

### Use atom as a default program after an update
1. Open Atom
2. Open Settings (File -> Settings)
3. Navigate to the Systems tab
4. Uncheck and recheck the following options:
  * Register as file handler
  * Show in file context menus
  * Show in folder context menus


## Getting Spell Check Working on Windows
1. Inside of Atom, Click on `File` then `Settings`

2. Select `Packages`

3. Search for `spell-check`

4. Click on the `Settings` button for the `spell-check` package

5. Under `Locale Paths` type the following
    ```
    <path-to-Atom>\Atom x64\resources\app\node_modules\spellchecker\vendor\hunspell_dictionaries
    ```

    Example:
    ```
    C:\Users\<user-name>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Portable Apps\Portable Repo\atom-x64-windows\Atom x64\resources\app.asar.unpacked\node_modules\spellchecker\vendor\hunspell_dictionaries
    ```

    **Note 1:** the `Locale Path` may change depending on the version of atom being used, just make sure to find a directory within the atom parent directory that is named `hunspell_dictionaries` and has the following files:
      * `en_US.aff`
      * `en_US.dic`

    **Note 2:** the `hunspell_dictionaries` may be downloaded from this url: `https://sourceforge.net/projects/hunspell/files/Spelling%20dictionaries/en_US/en_US.zip/download` and placed in any path you like, just type the path in `Locale Paths`.

***Spell checking should now work the way it is supposed to after restarting Atom***

############### Packages

### Suggested Packages to install
1. atom-beautify
    > https://atom.io/packages/atom-beautify

2. file-icons
    > https://atom.io/packages/file-icons

3. file-types
    > https://atom.io/packages/file-types

4. highlight-selected
    > https://atom.io/packages/highlight-selected

5. markdown-preview-enhanced
    > https://atom.io/packages/markdown-preview-enhanced

6. minimap
    > https://atom.io/packages/minimap

7. platformio-ide-terminal
    > https://atom.io/packages/platformio-ide-terminal

8. split-diff
    > https://atom.io/packages/split-diff

9. sync-settings
    > https://atom.io/packages/sync-settings

10. git-plus
    > https://atom.io/packages/git-plus

### Suggested Packages to disable:
1. markdown-preview
2. metrics

## Themes

* Note: there are thousands of themes to choose from.
  * The official site is: https://atom.io/themes
  * I'd recommend is this website to make the search easier: http://atomthemes.io/

### Suggested UI Themes to install:
1. atom-material-ui
    > https://atom.io/themes/atom-material-ui

### Suggested Syntax Themes to install:
1. grey-goo-syntax
    > https://atom.io/themes/grey-goo-syntax

2. improved-chester-atom-syntax
    > https://atom.io/themes/improved-chester-atom-syntax
Add Comment Collapse
