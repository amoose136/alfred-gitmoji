# GitMoji for Alfred

Some Alfred Snippets to make putting the true unicode equivalents of things like :sparkles:, :lipstick:, and other emojis used it git comments easier to type. It gives them names relavent to coding. 
Of course the official gitmoji has a CLI but suppose you want to use an IDE or don't want to install npm but already have Alfred Powerpack,or you just want a more inline way way of adding emoji, or you want the emoji to work with `$git log` (e.g. `:sparkles:` will not be interpretted by `git log`); if so, this is for you. 

## Examples:

* `:sparkles:` -> `:add:` Because one uses ✨ when adding new features
* `:penguin:` -> `:lin:` Because one uses 🐧 when making linux related changes
* `:checkered_flag:` -> `:win:` Because one uses 🏁 for windows related 
changes
* `:heavy_plus_sign:` -> `:+dep:` Because one uses ➕   when adding dependancies

_etc.._

Added benefit of making emojis appear with `$git log` because they are just unicode after using this.
Inspired by: https://gitmoji.carloscuesta.me/
And also: https://github.com/atom/atom/blob/7929e261a0d6e78ff4ca5196c8b385946e64dbd9/CONTRIBUTING.md#git-commit-messages 

## Full Mapping
|Input Text     | Result | Description                               |
|---------------|--------|-------------------------------------------|
|               |        |                **Git related**            |
|`:first:`      |🎉      |for the first commit                       |
|`:merge:`      |🔀      |merge git branches                         |
|`:doc:`        |📝      |write documentation                        |
|`:legal:`      |📄      |change/update license                      |
|`:tag:`        |🔖      |version tagging                            |
|`:rewind:`     |⏪      |undo changes                               |
|               |        |           **Add and Remove Stuff**        |
|`:add:`        |✨      |add a new feature                          |
|`:rm:`         |🔥      |remove code or files                       |
|               |        |               **Fix Types**               |
|`:bug:`        |🐛      |fix a bug                                  |
|`:config:`     |🔧      |changing internal configurations/settings  |
|`:hotfix:`     |🚑      |fix critical bug                           |
|`:leak:`       |🚱      |plug memory leaks                          |
|               |        |               **API related**             |
|`:api:`        |👽      |external api related changes               |
|`:downgrade:`  |⬇️      |downgrade dependancy                       |
|`:upgrade:`    |⬆️      |upgrade dependancy                         |
|`:-dep:`       |➖      |remove a dependancy                        |
|`:+dep:`       |➕      |add a dependancy                           |
|               |        |               **Platforms**               |
|`:mac:`        |🍎      |changes specific to macOS                  |
|`:win:`        |🏁      |changes specific to Windows                |
|`:lin:`        |🐧      |changes specific to Linux                  |
|               |        |               **Change Types**            |
|`:pseudo:`     |💩      |write shit code to be replaced later       |
|`:wip:`        |🚧      |code that is a work in progress / this commit semi breaks things|                                       
|`:refactor:`   |🔨      |large backend changes                      |
|`:tidy:`       |🎨      |improve format/structure of code           |
|`:typo:`       |✏️       |fix typo                                   |
|`:speed:`      |🐎      |improve performance                        |
|`:gui:`        |💄      |related to look and feel                   |
|`:intl:`       |🌐      |internationalization/locale                |
|               |        |               **Meta/stability**          |
|`:stats:`      |📈      |performance diagnostics                    |
|`:test:`       |✅      |add/change tests                           |
|`:lint:`       |👕      |remove linter warnings                     |


##Potential downside##
Viewing git messages from a platform that does not support unicode could cause an unpleasant experience but most platforms support unicode in 2017.