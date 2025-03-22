# 2025.03.15 session
## online meeting room
- [meeting room](https://meet.google.com/wuz-jexe-rhq)
## prelim
- the course will cover GitHub first, then Git
- subfolder can be created in file field following by a slash line, so GitHub will recognize it as a subfoler rather than a file
```markdown
## hyperlink
- [link](./subfolder)
```
## markdown basic
- create a README.md inside a GitHub repository, and it will appear in the bottom section of folder (or subfolder)
- repository purpose: project-based folder
- *.md* stands for markdown
- on GitHub, markdown syntax might differ from markdown(s) in other interface   
[instruction](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- linebreak: back slash or double space in the end of sentence
- other commands refer to [link](./subfolder/README.md)
- crossout by tilda
```markdown
~~deleted~~
```
- subcript denoted by ac<sub>c</sub>
- a tag can be expressed by parentheses `tag`
- underline a text can be expressed with
```
something to <ins>underscore</ins>
```
## header structure
- denoted by pound key
- up to sixth header is possible in markdown syntax
## insert picture
![text to display](./Untitled.png)
## track change in Github: show diff
- commit: note the change in this version (by clicking "show diff") as this functions in a similar way to MS Word track edit
- inside commit a message can be attached to memo update/revision in this file
## An online IDE: GitHub Codespaces 
- from *Codespaces*, user can launch vscode with access to virtual machine that executes the script
- make sure to terminate a session to prevent credit/token exhaustion 

# 2025.03.22 session
![screenshot](./202503220938.png)
## Git setup
- Git is default installed in Mac and Linux, but not in Windows
- download via [download link](https://git-scm.com/downloads/win)
## Git bash 
```
cd "(path)"
git init
rm -r .git
```
- this function can be executed via VSCode interface, or terminal within VSCode
- once a `.git` was created in a folder, all of its subfolders are linked
- namely, do not create `.git` for subfoler
## VSCode
- `U` untracked
- `M` modified
- `D` deleted
### procedure
1. change 變更
2. staged change 儲存變更
3. commit 提交 (with a commit message)
![screenshot](./202503221135.png)
> for commit message, `vim` syntax is used. `i` for insert, `ESC` exits the insert mode
> `:w` indicates writ, while `:q` exits
