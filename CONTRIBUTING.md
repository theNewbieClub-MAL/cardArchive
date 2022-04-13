# Contributing

By contributing to this project, you agree to the following:

* [x] [`cardArchive`'s Code of Conduct](CODE_OF_CONDUCT.md) by [Contributor Covenant](https://contributor-covenant.org/).
* [x] Committer acknowledge if the files sent to this repo will be available publicly and can be downloaded/cloned freely.
* [x] Committer granted repo maintainer to list committer's username as commit co-author.
* [x] For staff: staff granted copyright holder to contact for takedown notice.

## For Staff

### By GitHub push (for staff)

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
   <editionID>-<camelCasedEditionTitle>
   ```

   Sample:

   ```html
   2112B-utaite
   ```

   * Format edition title using camelCase model, and exclude any symbols.

     Sample:
     * Kimetsu no Yaiba → kimetsuNoYaiba
     * Valentine's → valentines
     * 10K Members Milestone → 10KMembersMilestone
     * Haikyuu! → haikyuu

   * For `<editionId>`, please refer to The Newbie Club's Delivery Database Spreadsheet (for staff) **OR** [🚛 Card Delivery Tracking](https://myanimelist.net/forum/?topicid=1981019) thread on MyAnimeList (for general use).
     * However, you can "generate" the ID based on when the edition is released, and numbering the editions in chronological order.
     * Format of the ID is `YYMM(Sq.)`, where `YY` is the year, `MM` is the month, and `Sq.` is the sequence number in alphabetical format.
     * Sample:
       On October 2021, there is 3 edition released:
       1. [Fall Edition](https://myanimelist.net/forum/?topicid=1961525). Released on October 3, 2021. Thus making the ID `2110A`.
       2. [Genshin Impact Edition](https://myanimelist.net/forum/?topicid=1965234https://myanimelist.net/forum/?topicid=1965234). Released on October 17, 2021. Thus making the ID `2110B`.
       3. [TNC X HNE Halloween Collab Edition](https://myanimelist.net/forum/?topicid=1967957). Released on October 28, 2021. Thus making the ID `2110C`.

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

### By issuing a GitHub issue (for staff)

1. Visit [this issue template](https://github.com/theNewbieClub-MAL/cardArchive/issues/new?assignees=nattadasu&labels=carddump&template=attachStaff.yml&title=%5BDump%5D%3A+XYZ+Edition+by+ABC+staff).
2. Fill data that required on the template.
3. Submit.
4. Wait for staff to review, triage, and approve.
5. Safe.

### By inserting data to Google Spreadsheet

1. Open The Newbie Club Delivery Log spreadsheet. Link is available on `#activities-log`'s channel description.
2. Go to `Data` sheet and search your name on current release
3. Insert your link on **`Delivery Link`** column.
   * If your link has expiration date, insert the estimated date to **`Link Expired on`** column by using `YYYY-MM-DD` format.
4. Wait until "Your Personal Neko Len" bot on `#activities-log` channel send you a message.
5. Profit.

### By old-school way

1. DM/ping the repo maintainer, GFX admin, deputy, or club owner on Discord or MyAnimeList. See contact details on [this section](#contacts).
2. *ggwp*.

## For Members

### By GitHub push (for members)

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
   <editionID>-<camelCasedEditionTitle>
   ```

   Sample:

   ```html
   2112B-utaite
   ```

   * Format edition title using camelCase model, and exclude any symbols.

     Sample:
     * Kimetsu no Yaiba → kimetsuNoYaiba
     * Valentine's → valentines
     * 10K Members Milestone → 10KMembersMilestone
     * Haikyuu! → haikyuu

   * For `<editionId>`, please refer to The Newbie Club's Delivery Database Spreadsheet (for staff) **OR** [🚛 Card Delivery Tracking](https://myanimelist.net/forum/?topicid=1981019) thread on MyAnimeList (for general use).
     * However, you can "generate" the ID based on when the edition is released, and numbering the editions in chronological order.
     * Format of the ID is `YYMM(Sq.)`, where `YY` is the year, `MM` is the month, and `Sq.` is the sequence number in alphabetical format.
     * Sample:
       On October 2021, there is 3 edition released:
       1. [Fall Edition](https://myanimelist.net/forum/?topicid=1961525). Released on October 3, 2021. Thus making the ID `2110A`.
       2. [Genshin Impact Edition](https://myanimelist.net/forum/?topicid=1965234https://myanimelist.net/forum/?topicid=1965234). Released on October 17, 2021. Thus making the ID `2110B`.
       3. [TNC X HNE Halloween Collab Edition](https://myanimelist.net/forum/?topicid=1967957). Released on October 28, 2021. Thus making the ID `2110C`.

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

### By issuing a GitHub Issue (for members)

1. Open this [link](https://github.com/theNewbieClub-MAL/cardArchive/issues/new?assignees=nattadasu&labels=attachment&template=attachMember.yml&title=%5BAttach%5D%3A+ZIP+of+XYZ+Edition+by+ABC+staff).
2. Fill data that required on the template.
3. Submit.
4. Wait for staff to review, triage, and approve.
5. Safe.
