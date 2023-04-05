# Doom Emacs keybindings

This vspacecode-config.json contains an `vspacecode.binding` array that mimicks the Doom Emacs keybindings as closely as possible.

A few notes to take into account:

- All the exceptions that I'm personally aware of are documented below
- There might be some mistakes / incomplete bindings (work in progress)
- I have kept some keybindings that are not in Doom, but are still useful to have (documented below)
- I did not verify / change the major mode keybindings (SPC m), as it would be a huge amount of effort (bulk of the config)
- Improvements on my end will be made over time which might take some time to be integrated back into this example config

## Not in Doom

Only these keybindings don't correspond with Doom equivalents

### Unused letters

These root letters are not used in Doom (but are present in VSpaceCode)

Kept them as useful keybindings are present

| Description                     | Keybinding |
|---------------------------------+------------|
| Grow and shrink smart selection | SPC v      |
| Jump/join/split                 | SPC j      |
| Zoom/fold                       | SPC z      |
| Diff/compare                    | SPC D      |
| Frame                           | SPC F      |
| Show                            | SPC S      |
| UI/Toggles                      | SPC T      |

### Other purpose

These are mapped to another purpose or are very close

### Root

| Description | Keybinding | Motivation                                                |
|-------------+------------+-----------------------------------------------------------|
| List tasks  | SPC :      | Corresponds to open M-x command in Doom                   |
| Debug       | SPC d      | Not used in Doom, but personally added dired capabilities |
| Errors      | SPC e      | Not used in Doom, but personally added elisp capabilities |

### Buffers

| Description                     | Keybinding    |
|---------------------------------+---------------|
| First and last buffer in window | SPC b (0/1)   |
| Reopen last buffer              | SPC b o       |

### File

| Description                          | Keybinding |
|--------------------------------------+------------|
| Open file with                       | SPC f o    |
| Open active file in new window       | SPC f w    |
| Emacs and VSpaceCode setting options | SPC f e    |
| Indentation options                  | SPC f i    |
| Yank options                         | SPC f y    |

### Projects

| Description     | Keybinding |
|-----------------+------------|
| Recent projects | SPC p r    |

### Toggle

| Description                | Keybinding |
|----------------------------+------------|
| Toggle find case sensitive | SPC t c    |
| Toggle render whitespace   | SPC t s    |

### Search

| Keybinding | VSCode description    | Doom description |
|------------+-----------------------+------------------|
| SPC s r    | Search all references | Jump to mark     |

### Windows

| Description         | Keybinding |
|---------------------+------------|
| Close other windows | SPC w D    |
