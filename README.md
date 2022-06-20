Ace3 example with options panel and slash commands.
- https://www.wowace.com/projects/ace3/pages/getting-started
- https://wowpedia.fandom.com/wiki/Ace3_for_Dummies

![](https://github.com/ketho-wow/BearsSwitcher/raw/master/preview.png)

### Folder name
⚠️ If you downloaded it as a zip, rename the `BearsSwitcher-master` folder to `BearsSwitcher`

### About embeds
The Ace3 libs are hard-embedded for simplicity. For how to soft-embed them, see [BigWigs: Preparing the PackageMeta File](https://github.com/BigWigsMods/packager/wiki/Preparing-the-PackageMeta-File).

To still have a working dev setup you can either:
* Use the Ace3 libs standalone by dropping the [Ace3](https://www.wowace.com/projects/ace3) addon in the `AddOns` folder and specifying `## OptionalDeps: Ace3` in your TOC.
* Or exclude your `Libs` folder from the repository with [.gitignore](https://git-scm.com/docs/gitignore).
