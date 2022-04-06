<!-- markdownlint-disable MD033 -->

# Setting Up

> This tutorial assumes you're using Windows.

1. Download [Snap2HTML](https://rlvision.com/snap2html/about.php) ZIP and unzip to this directory.
2. Open Snap2HTML executable to initialize `settings` file.
3. Set the configuration in app:
   * Root folder
     * Path: *your working git directory*
     * Include hidden items: false
     * Include system items: false
   * Page title: `Snapshot of {{author}}/{{repo}}`
   * Link files
     * Check: true
     * Path to link files: `https://raw.githubusercontent.com/{{author}}/{{repo}}/main`
4. Generate HTML file as `index.html` in this branch.
5. Open code editor to edit `index.html`.
6. <kbd>Ctrl</kbd> + <kbd>H</kbd> (or <kbd>Cmd</kbd> + <kbd>H</kbd> for macOS) on code editor to find and replace string.
7. Take the last string of the full directory path to replace query.
   * For Windows, replace backslash (`\`) to slash (`/`) to get matching result.
     * Example: `C:/Users/user/Documents/GitHub/repo/`, to: `repo/`.
   * This step is required if you want to maintain privacy.
8. Save and commit the change to GitHub.
9. GitHub Action Bot will automatically replace rest of the strings (`{{author}}`, `{{repo}}`, and `{{committer}}`).
