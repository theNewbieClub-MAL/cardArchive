# The Newbie Club Official Cards Archival Project

*This repo is powered by [GitHub Copilot](https://copilot.github.com) AI for phrase generator. ~~No time wasted because the suggested phrases are almost good to go~~*

> Also, rule of thumb: this is not official repo of MAL.
> If you are looking for MAL repo, well sorry to break your hopes, but it is proprietary.

## Introduction

Welcome to the official repo for cards archival project! As the name suggests, this repo will be one-all-stop archival from past releases until current releases.

This repo only includes any cards that have been delivered by designer themselves, or assisted by deliverer team member.

## Table of Contents

* [Introduction](#introduction)
* [Table of Contents](#table-of-contents)
* [Content Index](#content-index)
* [Folder Structure](#folder-structure)
* [Contributing](#contributing)
  * [For Staff](#for-staff)
    * [By GitHub push (for staff)](#by-github-push-for-staff)
    * [By issuing a GitHub issue (for staff)](#by-issuing-a-github-issue-for-staff)
    * [By inserting data to Google Spreadsheet](#by-inserting-data-to-google-spreadsheet)
    * [By old-school way](#by-old-school-way)
  * [For Members](#for-members)
    * [By GitHub push (for members)](#by-github-push-for-members)
    * [By issuing a GitHub Issue (for members)](#by-issuing-a-github-issue-for-members)
* [Takedown Notice](#takedown-notice)
* [FAQ](#faq)
  * [What is this repo?](#what-is-this-repo)
  * [Well, I know exactly the purpose of this repo by looking the name, but what is cards exactly?/?](#well-i-know-exactly-the-purpose-of-this-repo-by-looking-the-name-but-what-is-cards-exactly)
  * [Uh, I couldn't understand how to navigate on this site. Need halp](#uh-i-couldnt-understand-how-to-navigate-on-this-site-need-halp)
  * [Directly using GitHub](#directly-using-github)
  * [Using mirror site](#using-mirror-site)
  * [Wait, when I visited certain designer's folder, why I saw either .gitkeep or README.md with Attention as title?](#wait-when-i-visited-certain-designers-folder-why-i-saw-either-gitkeep-or-readmemd-with-attention-as-title)
* [Contacts](#contacts)
  * [Repo Maintainer](#repo-maintainer)
  * [Club Administrators](#club-administrators)

## Content Index

Please refer to [index.md](index.md)

## Folder Structure

There is two folder structures of this repo:

### Scheduled releases

For scheduled (bi-weekly, monthly) release, the folder structure is:

```html
./<year>/<editionID>-<editionName>/<gfxUsername>/<content>
```

However, for [TNC x HNE Halloween Collab (`2110C`)](2021/2110C-tncXHneHalloweenCollab), the `<gfxUsername>` is not existent. Content is directly in the `2110C-tncXHneHalloweenCollab` folder.

### Special releases

For any releases that is not routinely scheduled, such Honor cards, achievements, badges, etc, the folder structure is:

```html
./special/<name>/<gfxUsername>/<content>
```

## Contributing

### For Staff

#### By GitHub push (for staff)

1. Fork this repository.
2. Clone forked repository to your machine.
   * **For Windows/macOS/Linux/BSD**:
     * Download [GitKraken](https://www.gitkraken.com/download)
     * Install the programs using recommended steps.
     * Open GitKraken, Login, and click on `New Repository`
     * Click on `Clone with URL`, and paste the link to the forked repo.
     * Open the forked repo in file explorer.
3. Put your card by following [folder structure](#folder-structure), where `<content>` is your true card content.
4. Rename edition title by using this format:

   ```html
   <edition>-<Edition title lowercase>
   ```

   Sample:

   ```html
   2112B-utaite
   ```

   * Format edition title using camelCase model, and exclude any symbols.

     Sample:
     * kimetsuNoYaiba
     * valentines
     * 10kMembersMilestone
     * haikyuu

5. Add files to staging, note that this might take a time to load.
   * On GitKraken, click on `Stage all changes`.
6. Commit your artworks with this name format:

   ```html
   Cards archival of MAL@<your mal username>
   ```

   * On GitKraken's right sidebar, insert the name format to `Summary`.
   * Click on `Stage files/changes to commit`.
7. Click `Push` button on top toolbar.
8. Make a PR.
   * From GitKraken left toolbar, click `+` on `Pull request`.
   * Select your forked repo on "From Repo" drop box, and select theNewbieClub/cardArchive on "To Repo" drop box, with `main` as branch.
   * Write your PR title, and click `Create Pull Request`.
9. ???
10. Profit.

#### By issuing a GitHub issue (for staff)

1. Visit [this issue template](https://github.com/theNewbieClub-MAL/cardArchive/issues/new?assignees=nattadasu&labels=carddump&template=attachStaff.yml&title=%5BDump%5D%3A+XYZ+Edition+by+ABC+staff).
2. Fill data that required on the template.
3. Submit.
4. Wait for staff to review, triage, and approve.
5. Safe.

#### By inserting data to Google Spreadsheet

1. Open The Newbie Club Delivery Log spreadsheet. Link is available on `#activities-log`'s channel description.
2. Go to `Data` sheet and search your name on current release
3. Insert your link on **`Delivery Link`** column.
   * If your link has expiration date, insert the estimated date to **`Link Expired on`** column by using `YYYY-MM-DD` format.
4. Wait until "Your Personal Neko Len" bot on `#activities-log` channel send you a message.
5. Profit.

#### By old-school way

1. DM/ping the repo maintainer, GFX admin, deputy, or club owner on Discord or MyAnimeList. See contact details on [this section](#contacts).
2. *ggwp*.

### For Members

#### By GitHub push (for members)

1. Fork this repository.
2. Clone forked repository to your machine.
   * **For Windows/macOS/Linux/BSD**:
     * Download [GitKraken](https://www.gitkraken.com/download)
     * Install the programs using recommended steps.
     * Open GitKraken, Login, and click on `New Repository`
     * Click on `Clone with URL`, and paste the link to the forked repo.
     * Open the forked repo in file explorer.
3. Put your card by following [folder structure](#folder-structure), where `<content>` is your true card content.
4. Rename edition title by using this format:

   ```html
   <edition>-<Edition title lowercase>
   ```

   Sample:

   ```html
   2112B-utaite
   ```

   * Format edition title using camelCase model, and exclude any symbols.

     Sample:
     * kimetsuNoYaiba
     * valentines
     * 10kMembersMilestone
     * haikyuu

5. Add files to staging, note that this might take a time to load.
   * On GitKraken, click on `Stage all changes`.
6. Commit your artworks with this name format:

   ```html
   Cards archival of MAL@<designer mal username>
   ```

   * On GitKraken's right sidebar, insert the name format to `Summary`.
   * Click on `Stage files/changes to commit`.
7. Click `Push` button on top toolbar.
8. Make a PR.
   * From GitKraken left toolbar, click `+` on `Pull request`.
   * Select your forked repo on "From Repo" drop box, and select theNewbieClub/cardArchive on "To Repo" drop box, with `main` as branch.
   * Write your PR title, and click `Create Pull Request`.
9. ???
10. Profit.

#### By issuing a GitHub Issue (for members)

1. Open this [link](https://github.com/theNewbieClub-MAL/cardArchive/issues/new?assignees=nattadasu&labels=attachment&template=attachMember.yml&title=%5BAttach%5D%3A+ZIP+of+XYZ+Edition+by+ABC+staff).
2. Fill data that required on the template.
3. Submit.
4. Wait for staff to review, triage, and approve.
5. Safe.

## Takedown Notice

Please send a takedown request to dmca@nattadasu.my.id. We will try our best to take it down within a day or earlier.

Or, if you are not able to send a takedown request via email, you can submit a GitHub issue with [this link](https://github.com/theNewbieClub-MAL/cardArchive/issues/new?assignees=nattadasu&labels=takedown&template=takedownNotice.yml&title=%5BTakedown+Notice%5D+XYZ+Edition+by+ABC+staff).

## FAQ

### What is this repo?

`theNewbieClub-MAL/cardArchive` is archival repository for cards that have been delivered by designer themselves, or assisted by deliverer team member. Aimed for giving an inspiration for new staff or returning on designing their own cards, and also for those who are looking for a way to retrieving back their cards when link given by designer/deliverer is broken/expired.

### Well, I know exactly the purpose of this repo by looking the name, but what is cards exactly?/?

> Cards or card editions are a club thing that don’t serve a real purpose, but are rather collectibles that you can for example just save, show off in a blog post on MAL such as in this example here, or display them in your MAL profile, your forum signature, etc.
> [*The Newbie Club's Official GFX Encyclopedia*](https://thenewbieclub-mal.github.io/gfxEncyclopedia/#/gfx/cards)

### When this repo is created? Why there's just a few cards archived?

This repo was created and announced on [February 17, 2022](https://github.com/theNewbieClub-MAL/cardArchive/commit/6bd360bd212f2de1178fa1802474f2bd9e26f197). Some of the links given by designers before the announcement were broken, and some of the cards were not designed/created by the designer themselves due to resignation.

### Uh, I couldn't understand how to navigate on this site. Need halp

To navigate/explore, you can choose any method below:

#### Directly using GitHub

1. Click `Go on file` on top toolbar, or click this [link](https://github.com/theNewbieClub-MAL/cardArchive/find/main)
2. Start searching!

#### Using mirror site

1. First, visit [this link](https://theNewbieClub-MAL.github.io/cardArchive/) to go to the mirror site.
2. On right top, there is a search box, type in your search query, and click `Search`.
3. Start searching!

### Wait, when I visited certain designer's folder, why I saw either .gitkeep or README.md with Attention as title?

Those files are placeholder for Git read "empty" directory. By default, empty directory is not shown on Git, so you need to add `.gitkeep` file on that folder.

However, for `README.md` file, there is an additional note why the folder is empty. Mostly it is due to the link designer/deliverer has given is expired, but it also can be due to the designer resigned from the club.

## Contacts

### Repo Maintainer

* Natsu Tadama. *[GitHub](https://github.com/nattadasu) | [MyAnimeList](https://myanimelist.net/profile/nattadasu) | [Email](mailto:hello@nattadasu.my.id)*

### Club Administrators

* Karasian, **Club owner**. *[GitHub](https://github.com/Karasian) | [MyAnimeList](https://myanimelist.net/profile/Karasian)*
* Natsu Tadama, **GFX-CD Administrator**. *[GitHub](https://github.com/nattadasu) | [MyAnimeList](https://myanimelist.net/profile/nattadasu) | [Email](mailto:hello@nattadasu.my.id)*
* Annie_Law, **GFX-CD Deputy**. *[MyAnimeList](https://myanimelist.net/profile/Annie_Law)*
