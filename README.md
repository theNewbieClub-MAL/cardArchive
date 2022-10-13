<!-- markdownlint-disable MD033 -->

# Setting Up

> This tutorial assumes you're using Windows.

1. Clone `main` branch of repository.
   * After clone the repo, open directory, hide all of folders and files on root except:
     * `.\20*`
       * Sample: `.\2019`, `.\2020`, `.\2021`, `.\2022`
     * `.\special`
   * Search `.gitkeep` on Explorer, and hide those files.
2. Clone `gh-pages` branch of repository.
3. Download [Snap2HTML](https://rlvision.com/snap2html/about.php) ZIP and unzip to `gh-pages` branch directory you cloned.
4. Open Snap2HTML executable to initialize `settings` file.
5. Set the configuration in app:
   * Root folder
     * Path: *your working git directory of `main` branch*
     * Include hidden items: false
     * Include system items: false
   * Page title: `Snapshot of {{repo}}`
     * Available placeholder:
       * `{{author}}`: author of repository
       * `{{repo}}`: name of repository
       * `{{committer}}`: username of committer
   * Link files
     * Check: true
     * Path to link files: `https://raw.githubusercontent.com/{{repo}}/main`
       > **Warning** |
       > Do not replace the placeholders to avoid conflict
6. Generate HTML file as `index.html` in this branch.
7. Open code editor to edit `index.html`.
8. <kbd>Ctrl</kbd> + <kbd>H</kbd> (or <kbd>Cmd</kbd> + <kbd>H</kbd> for macOS) on code editor to find and replace string.
9. Take the last string of the full directory path to replace query.
   * For Windows, replace backslash (`\`) to slash (`/`) to get matching result.
     * Example: `C:/Users/user/Documents/GitHub/repo/`, to: `repo/`.
   > **Note** |
   > This step is required if you want to maintain privacy.
10. Save and commit the change to GitHub.
11. GitHub Action Bot will automatically replace rest of the strings (`{{repo}}`, and `{{committer}}`).
