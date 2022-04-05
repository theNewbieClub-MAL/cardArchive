# Setting Up

1. Download [Snap2HTML](https://rlvision.com/snap2html/about.php) ZIP and unzip to this directory.
2. Open Snap2HTML executable to initialize `settings` file.
3. Set the configuration in app:
   * Root folder
     * Path: *your working git directory*
     * Include hidden items: false
     * Include system items: false
   * Page title: `Snapshot of theNewbieClub-MAL/cardArchive`
   * Link files
     * Check: true
     * Path to link files: `https://raw.githubusercontent.com/theNewbieClub-MAL/cardArchive/main`
4. Generate HTML file as `index.html`.
5. Open code editor to edit `index.html`.
6. <kbd>Ctrl</kbd> + <kbd>H</kbd> (or <kbd>Cmd</kbd> + <kbd>H</kbd> for macOS) on code editor to find and replace string.
7. Replace your working directory path to empty string.
   * For Windows, replace backslash (`\`) to slash (`/`) to get matching result.
8. Save and commit the change to GitHub.