# [macintacos](github.com/macintacos) Config

There are two files that make up my configuration for ease of iteration:

1. `vspacecode-config.json` - contains actual VSpaceCode overrides
2. `other-config.json` - contains "other settings" needed to make sure the aforementioned VSpaceCode overrides work as expected.

## Setup

The actual overrides are in `vspacecode-config.json`, however there is some additional settings/extensions needed to get every command to behave the way I expect which are defined in `other-config.json`.

- I use [VSCodeVim](https://github.com/VSCodeVim/Vim). `vim.visualModeKeyBindingsNonRecursive` and `vim.normalModeKeyBindingsNonRecursive` have the `vspacecode.space` invocation set to `<space>`. 90% of the time this isn't a problem – for the other 10%, vote for: https://github.com/microsoft/vscode/issues/103845.
- I use [multi-command](https://github.com/ryuta46/vscode-multi-command). There is an array of `multiCommand.commands` that are used later on in the overrides.
- I use [Settings Cycler](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-settings-cycler) for cycling through line number types; there's probably an easier solution for this but I haven't found it.
- There's some minor configuration for `whichkey` (I added a delay because if I know the chord I don't need the menu to render really).

## Caveats

- I don't use `edmagit`, so my `SPC g ...` commands are custom made and will likely stay that way. I lived without `magit` for a bit too long when I switched to VSCode, so I just got used to my Sublime Merge workflow.
- I use _probably_ too many extensions, so you're going to have to do some downloading if you want to steal this whole config.

Copy/paste at your own risk.

## Extensions Used

Here are the extensions you would need in order to make sure that everything works:

- [VSCodeVim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
- [multi-command](https://marketplace.visualstudio.com/items?itemName=ryuta46.multi-command)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [File Utils](https://marketplace.visualstudio.com/items?itemName=sleistner.vscode-fileutils)
- [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
- [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)
- [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
- [MongoDB for VS Code](https://marketplace.visualstudio.com/items?itemName=mongodb.mongodb-vscode)
- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
- [Copy Relative Path and Line Numbers](https://marketplace.visualstudio.com/items?itemName=ezforo.copy-relative-path-and-line-numbers)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Git File History](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-git-history)
- [Sublime Merge for VSCode](https://marketplace.visualstudio.com/items?itemName=giovdk21.vscode-sublime-merge)
- [Open in Github](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-open-in-github)
- [Open in GitHub, Bitbucket, Gitlab, VisualStudio.com !](https://marketplace.visualstudio.com/items?itemName=ziyasal.vscode-open-in-github) (now that I see I have two "open in GH" extensions, might simplify at some point...)
- [Confluence markup](https://marketplace.visualstudio.com/items?itemName=denco.confluence-markup)
- [Better Align](https://marketplace.visualstudio.com/items?itemName=wwm.better-align)
- [Excel Viewer](https://marketplace.visualstudio.com/items?itemName=GrapeCity.gc-excelviewer)
- [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
- [Settings Cycler](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-settings-cycler)
- [Remove empty lines](https://marketplace.visualstudio.com/items?itemName=usernamehw.remove-empty-lines)
- [Go](https://marketplace.visualstudio.com/items?itemName=golang.Go)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)