# Sampadak
A Text editor which support Unicode.

An `open-source project` which supports all major Operating System - **Windows, Linux, MacOS**.
Sampadak editor is based on `QT framework`.

![Light Color Scheme](https://user-images.githubusercontent.com/13361448/46593423-7f7eb080-cae9-11e8-8a21-0443bdfa6544.png)
![Dark Color Scheme](https://user-images.githubusercontent.com/13361448/46593429-8b6a7280-cae9-11e8-9b85-3e50135e4ce0.png)
![Blue Color Scheme](https://user-images.githubusercontent.com/13361448/46593433-958c7100-cae9-11e8-855e-23a2ba7fbf97.png)

## Features
Sampadak supports most of the common text editor features. Below is the list of it's **higlighing** features:

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

### - Command prompt support

User can execute sampadak from command prompt. Open any shell and execute following command:
```
sampadak.exe <file_1> <file_2> <file_3>...<file_N>
```

> Note: <file_1> = provide filename with fullpath without <> bracket.

### - Documents List Viewer, Filesystem Viewer, Project Viewer
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

#### Remember last session

#### Goto Line Numbers

![gotoline](https://user-images.githubusercontent.com/13361448/46593088-66283500-cae6-11e8-9121-4168a19a803c.png)

#### Syntax Highlighter

![syntax](https://user-images.githubusercontent.com/13361448/46593095-8526c700-cae6-11e8-8aa6-91f3030a5a84.png)

#### Find/Replace

![find-replace](https://user-images.githubusercontent.com/13361448/46593184-7a206680-cae7-11e8-9388-31ce79fb315a.png)

#### Highlight Similar words

![similar words](https://user-images.githubusercontent.com/13361448/46593205-9d4b1600-cae7-11e8-86a4-66b773a1a6f6.png)

#### Preferences
![view](https://user-images.githubusercontent.com/13361448/46593238-e1d6b180-cae7-11e8-914c-d9fe44adeb2a.png)
![editor](https://user-images.githubusercontent.com/13361448/46593243-f0bd6400-cae7-11e8-89e6-42654672d82c.png)
![fontncolor](https://user-images.githubusercontent.com/13361448/46593247-003cad00-cae8-11e8-96f1-ea1062d14f04.png)
![document](https://user-images.githubusercontent.com/13361448/46593253-0c286f00-cae8-11e8-8647-2a8ba40ae798.png)
![default directory](https://user-images.githubusercontent.com/13361448/46593258-15b1d700-cae8-11e8-99c3-0292ca012719.png)


## Future Plans

- Plug-in support
- More File type Syntax highlighter
- Image file support
- Two Document Editor support

## License
[GNU General Public License](https://opensource.org/licenses/GPL-3.0)
