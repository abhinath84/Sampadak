# Sampadak
A Text editor which support Unicode.

An `open-source project` which supports all major Operating System - **Windows, Linux, MacOS**.
Sampadak editor is based on `QT framework`. Currently we support **three color scheme**, those are as follows:

![Light Color Scheme](https://user-images.githubusercontent.com/13361448/46593423-7f7eb080-cae9-11e8-8a21-0443bdfa6544.png)
![Dark Color Scheme](https://user-images.githubusercontent.com/13361448/46593429-8b6a7280-cae9-11e8-9b85-3e50135e4ce0.png)
![Blue Color Scheme](https://user-images.githubusercontent.com/13361448/46593433-958c7100-cae9-11e8-855e-23a2ba7fbf97.png)

## Features
Sampadak supports most of the common text editor features. Below is the list of it's **higlighting** features:

- Command prompt support
- Documents List Viewer, Filesystem Viewer, Project Viewer
- Remember last session.
- Go to lines
- Syntax highlighter
- Find/Replace
- Highlight Similar words
- Toggle braces
- Preferences
- Report a problem

Below is the description of each **highlighting** features.

### 1. Command prompt support

User can execute sampadak from command prompt. Open any shell and execute following command:
```
sampadak.exe <file_1> <file_2> <file_3>...<file_N>
```

> Note: <file_1> = provide filename with fullpath without <> bracket.

> Example: sampadak.exe d:\doc\text doc.txt

### 2. Documents List Viewer, Filesystem Viewer, Project Viewer
We provide three viewer - **Document list**, **Filesystem**, **Project** on **Left Side** of the app. Each having seperate functionality, described as follows:

- **Documents List Viewer**

Store all the document names those are opened on Sampadak. User can change **current editor** tab by clicking on the desired document name from the list.

![documents_pane](https://user-images.githubusercontent.com/13361448/46593064-0598f800-cae6-11e8-9e8a-e6718eb45e4f.png)

- **Filesystem Viewer**

Filesystem viewer is a replica of `System File/Folder hierarchy` which help user to open document directly by `double click` on any document. 

User can add **Project Folder** (which described below) from Filesystem Viewer using RMB menu on the selected folder.

![filesystem_pane](https://user-images.githubusercontent.com/13361448/46593069-1cd7e580-cae6-11e8-86c5-ede36302f273.png)

- **Project Viewer**

Project Viewer store all the project direcories which are added through various options. `Each project folder is a representation of that folder on System Folder/File hierarchy`.

User can add projeoct folder using any of the following option:
- `From menu item. Goto File -> Open -> Project Folder...` or <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>O</kbd>
- `Click on Project Folder (3rd item) on Toolbar`.
- `On Filesystem Viewer, select folder (which you want to add as Project). Then do RMB and click 'Add Project Folder' option`.

![projects_pane](https://user-images.githubusercontent.com/13361448/46593074-35e09680-cae6-11e8-9623-88ab3192226e.png)

### 3. Remember last session
One of the key feature of Sampadak is to remember last session. When user close the app, it remember opened files & projects.
And next time when user open Sampadak, it will restore all the files & projects of the last session.

Now you can close your editor any time without worry about last session's information.

### 4. Goto Line Numbers
For a big file, it's hard to move to any perticular line. User has sto do lot of scrolling or page up/down whihc is sometime annoying. To solve this problem we provide `Go To Lines...` feature.

User can go to a particular line number and a particular cell/column of that line by clicking `Search -> Go To Lines...` menu or <kbd>Ctrl</kbd> + <kbd>G</kbd>.

Sampadak will open following red marked dialog.

> If you want to go a particular line, then put **line number only**. And hit <kbd>Enter</kbd>

> If you want to go a particular cell/column of any line, then put **line number:cell/column number**. And hit <kbd>Enter</kbd>

> If you want to return editor, then select line number textbox and hit <kbd>Enter</kbd>.

![gotoline](https://user-images.githubusercontent.com/13361448/46593088-66283500-cae6-11e8-9121-4168a19a803c.png)

### 5. Syntax Highlighter
Syntax highlighting is an essential component for every user who is dealing with code. Sampadak also provide this feature to speed up the work of those people.

Currently, we support **Syntax highlighting** for following file type:

`c, cpp, java, js, html, php, jsp, xml, css`

In future we will add sytan highlighting support for more file type.

![syntax](https://user-images.githubusercontent.com/13361448/46593095-8526c700-cae6-11e8-8aa6-91f3030a5a84.png)

### 6. Find/Replace
We made searching simple & robust. We integarted Find/Replace dialog at the bottom of the editor, so that user can freely access editor while doing search.

User can execute find by clicking `Search -> Find` or <kbd>Ctrl</kbd> + <kbd>F</kbd>.

And replace by `Search -> Replace` or <kbd>Ctrl</kbd> + <kbd>H</kbd>.

To do find next, user can do any of following:

- Hit <kbd>Enter</kbd> when search textbox is active in Find dialog.
- Press '>' on find dialog.
- Do <kbd>F3</kbd>

For replace, we support two options: Replace Next & Replace All.

![find-replace](https://user-images.githubusercontent.com/13361448/46593184-7a206680-cae7-11e8-9388-31ce79fb315a.png)

### 7. Highlight Similar words
Another cool feature of Sampadak is **highligting similar words**. When user `double click` on any word, Sampadak will highlight all the similar words on that document. This will help user to do quick search for any key word or any function or other valuable information. Sampadak highlight exactly similar words. 

![similar words](https://user-images.githubusercontent.com/13361448/46593205-9d4b1600-cae7-11e8-86a4-66b773a1a6f6.png)

### 8. Preferences
Preference dialog having all the settings related to Sampadak. We made preference options live, when user do any changes in any option in preference dialog its execute immediately. To open Preference dialog, click `Settings -> Preferences`.

User can reset to default preferences by clicking `Reset` button.

Preference dialog has following five sections, those are as follows:

* View :

![view](https://user-images.githubusercontent.com/13361448/46593238-e1d6b180-cae7-11e8-914c-d9fe44adeb2a.png)

* Editor :

![editor](https://user-images.githubusercontent.com/13361448/46593243-f0bd6400-cae7-11e8-89e6-42654672d82c.png)

* Font & Color :

![fontncolor](https://user-images.githubusercontent.com/13361448/46593247-003cad00-cae8-11e8-96f1-ea1062d14f04.png)

* Document :

![document](https://user-images.githubusercontent.com/13361448/46593253-0c286f00-cae8-11e8-8647-2a8ba40ae798.png)

* Default Directory :

![default directory](https://user-images.githubusercontent.com/13361448/46593258-15b1d700-cae8-11e8-99c3-0292ca012719.png)

## Installation

Please download Sampadak setup (Windows) from the ![Releases](https://github.com/abhinath84/Sampadak/releases) page.

## Report a Problem
User can report for a bug or any feature enhancement. To report a problem or enhancement requist, click `Help -> Report a Problem...` nemu.

This will redirect to following link:

[Sampadak issue tracker](https://github.com/abhinath84/Sampadak/issues)

Now, click on `New issue` and follow the process.

## Future Plans

- Plug-in support
- More File type Syntax highlighter
- Image file support
- Two Document Editor support

## License
[GNU General Public License](https://opensource.org/licenses/GPL-3.0)
