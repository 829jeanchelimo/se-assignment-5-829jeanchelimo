[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15289904&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   
1. Visit the [Visual Studio Code](https://code.visualstudio.com/) website and download the Windows installer.
2. Run the downloaded installer and follow the setup wizard, accepting the license agreement and choosing installation options.
3. Complete the installation process by clicking "Finish" and launching Visual Studio Code.
4. Customize your setup, including installing extensions and configuring settings as desired.
5. Visual Studio Code is now installed and ready to use on your Windows 11 system.



2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

python
gitlens
debugger for chrome

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

 Activity Bar
Location**: Vertical bar on the left side.
Purpose**: Provides quick access to main views like Explorer, Search, Source Control, Run and Debug, and Extensions.

Side Bar
Location**: Next to the Activity Bar on the left.
Purpose**: Displays detailed content and tools relevant to the selected view from the Activity Bar, such as the file explorer, search results, and source control details.

Editor Group
Location**: Central area of the window.
Purpose**: Main workspace for writing and viewing code files, supporting multiple tabs and split views for simultaneous file editing.

Status Bar
Location**: Horizontal bar at the bottom of the window.
Purpose**: Shows information about the current state of the editor and workspace, including file details, Git status, errors and warnings, and quick action shortcuts.



4. Command Palette:
   -What is the Command Palett e in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

 open a file
 search for commands
run tasks
 format a document

 It is a powerful feature that provides quick access to many commands and functions within the editor. It allows you to execute various actions without needing to navigate through menus or remember keyboard shortcuts.5. Extensions in VS Code:

   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

 Enhance functionality, customization, productivity, and community contributions.

Prettier, ESLint, Live Server, Debugger for Chrome, Path Intellisense, HTML CSS Support

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

go to the top menu and click on "view" then "terminal"

convenience
context awareness
integrattion with extentions

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

Creating Files: Right-click in the Explorer view or use Ctrl + N to create new files with specific extensions.
Creating Folders: Similarly, create folders by right-clicking in the Explorer view or using Ctrl + Shift + N.
Opening Files: Double-click files in the Explorer view or use Ctrl + O to navigate to and open files.
Opening Folders: Use File -> Open Folder... or Ctrl + K Ctrl + O to open entire folders.
Managing:

Renaming: Right-click and select Rename, or press F2 to rename files or folders.
Deleting: Right-click and select Delete, or press Delete to remove files or folders.
Moving/Copying: Drag and drop within the Explorer view to move files or folders; hold Ctrl while dragging to copy.
Navigation:

Explorer View: Navigate through files and folders using the Explorer view (Ctrl + Shift + E).
Switching Between Files: Use Ctrl + Tab to toggle between recently opened files.
Searching: Utilize Ctrl + Shift + F to search for specific text within files in the workspace.
Shortcuts: Access frequently used commands and settings through the Command Palette (Ctrl + Shift + P).

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

go to th icon file
navigate to preferences
choose your desired preferrence on font size 

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
Setting up debugging in Visual Studio Code (VS Code) involves installing relevant extensions, opening your project, setting breakpoints, and starting debugging with F5 or Run -> Start Debugging. Key controls (F10, F11) navigate program execution, inspect variables, and interact via the Debug Console. Features include multi-language support, breakpoints for pausing code, a versatile Debug Console, and function call stack visualization. Variable inspection and integrated terminal interaction enhance debugging efficiency. Customizable configurations in launch.json tailor debugging setups, while automation and build system integration streamline workflows. VS Code's robust debugging tools empower developers to efficiently diagnose and resolve code issues, ensuring software quality and productivity.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
Integrating Git with Visual Studio Code (VS Code) enables efficient version control for projects:

1. **Initialization**: Use `git init` in VS Code's integrated terminal to initialize a Git repository.
   
2. **Staging Changes**: Stage files with `git add .` or `git add filename` to prepare them for commits.
   
3. **Committing Changes**: Commit changes with `git commit -m "Your commit message"` to record snapshots of your project.
   
4. **Adding Remote Repository**: Link your local repository to a remote one on GitHub using `git remote add origin <remote_repository_url>`.

5. **Pushing Changes**: Push commits to GitHub with `git push -u origin master` to synchronize changes.

6. **Visual Interface**: Utilize VS Code’s Git integration for visualizing changes, managing branches, and resolving conflicts.

7. **Efficiency Tools**: Access Git commands through shortcuts (`Ctrl + Shift + G`) and the Command Palette (`Ctrl + Shift + P`) for streamlined operations.

8. **Collaborative Workflow**: Enhance collaboration by leveraging Git’s capabilities for tracking changes and maintaining project integrity.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

