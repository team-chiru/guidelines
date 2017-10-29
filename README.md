# Team Chiru Guidelines
This guide attempts to be used as a centralized configuration for all team chiru project. It needs to be used as an easy set-up in order to quickly have an operational workspace for each team-chiru's project. This file is simply a list of useful recommendations and cannot be used has a strict guide, but be warmed that all these configurations are supposed to be strongly adopted by all team-chiru's projects.

**Be careful**: this guide must be edited first in the collaborative [Team Chiru Guidelines Draft](https://paper.dropbox.com/doc/Team-Chiru-Guidelines-Draft-YHh8yPhFpgz4b5cRPXlgA) which needs to be used as a suggestions board.

## Configuration Guide
The recommended text editor is [Visual Studio Code](https://code.visualstudio.com/) because it is fast and it has all most advanced features for debugging in *javascript*, *typescript* and *rust*.

### Editor Configuration
All basic configurations are described into an [EditorConfig](http://editorconfig.org/) file. Thus, all files are indented to have the same configuration for all currently used languages:

| Key                      | Value         | Comment             |
| ------------------------ | ------------- | ------------------- |
| end_of_line              | lf            | Because UNIX rules. |
| insert_final_newline     | true          | Because it's cleaner. |
| trim_trailing_whitespace | true          | Because it's also cleaner. |
| charset                  | utf-8         | Because it's 2017. |
| indent_style             | tab           | Because the **Tab key** was created for this use. |
| tab_width                | 4             | Because one day, we'll be all getting old. :eyeglasses: |


### Strongly Recommended Plugins


## Style Guide
### Javascript & Typescript
The style guide is completely provided by the [standardJS style](https://standardjs.com/). It is strongly recommended to have both the StandardJS linter editor plugin and the node command line linter installed. This style convention included the *typescript* style.

The team-chiru's used package manager for js project is [Yarn](https://yarnpkg.com/en/docs/install) and all configuration **doesn't require any `--global` configurations**.

## TODO lists
### New *javascript* project setup
- [ ] Install a decent code editor as VSCode.
- [ ] Copy all the recommended configurations and plugins for this editor.
- [ ] Install the recommended package manager.
- [ ] Add the [common `.editorconfig`](./.editorconfig).
- [ ] Copy all starter [files](./javascript/) into project
- [ ] Run `yarn install` command in order to have all the setup ready for use

