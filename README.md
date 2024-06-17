[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15288718&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   -Ensure that you on windows 11
   -Make sure you have internet connection 
   -Dowload installer by visiting https://code.visualstudio.com/
   -Click on dowload for windows
   -Save installer file to your pc
   -Run installer 
   -Follow the prompts
   -Launch Visual studio code


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

-Theme (Choose the theme that you are comfortable with ) through file>preference>settings, search 
-Font and zoom functions
-File auto save
-Extensions -to intsall over extensions such as python code run and etc 
-Accessing terminals 

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

-Activity bar is located on the far left-hand side, this vertical bar contains icons for quick access to different views and features, such as Explorer, Search, Source Control, Debug, and Extensions
-Side bar is adjacent to the Activity Bar, the Side Bar displays various panels that provide more information and actions related to the icon selected in the Activity Bar.
-Editor group is the large central area where you can view and edit files. You can have multiple editor groups open side by side or stacked vertically.
-Status bar is located at the bottom of the window, the Status Bar shows important information about your project and files you’re working on. It displays things like line number, column number, indentation settings, language mode, and feedback on errors and warnings.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

-Press F1 or Ctrl+Shift+P.

-Opening files-type ‘open’ followed by the file name.
-Changing themes-type ‘theme’ to see a list of available themes.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

-Find Extensions
Click on the Extensions icon in the Activity Bar or use the shortcut Ctrl+Shift+X.
Search for extensions by name or functionality.
-Install Extensions
Browse the list of extensions or search results.
Click ‘Install’ on the extension you want to add to VS Code.
-Manage Extensions
View installed extensions in the Extensions view.
Update, disable, or uninstall extensions as needed.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

-Open Terminal- use the shortcut Ctrl+` (backtick) or go to View > Terminal.
-Use Terminal- once open, you can type and execute commands just like in an external terminal.

Advantages of using the integrated terminal compared to an external terminal include:

-Convenience- it’s embedded within VS Code, so you don’t need to switch windows.
-Context aware -atomatically opens with the path set to your current project’s directory.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

-Create Files/Folders
Right-click in the Explorer pane and select ‘New File’ or ‘New Folder’.
Alternatively, use the icons at the top of the Explorer pane for creating new files or folders.
-Open Files
Click on a file in the Explorer pane to open it in the Editor Group.
You can also use File > Open File... from the menu or the shortcut Ctrl+O.
-Manage Files/Folders
Right-click on a file or folder for options like Rename, Delete, Copy, Paste, etc.
Drag and drop files or folders within the Explorer to reorganize them.
-Navigate Between Files/Directories
Use the ‘Go to File…’ feature (Ctrl+P) to quickly search and open files.
Use tabs at the top of the Editor Group to switch between open files.






8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

-Change the Theme
Go to File > Preferences > Color Theme or use the shortcut Ctrl+K Ctrl+T.
Select a theme from the list to apply it.
-Change Font Size
Open Settings (Ctrl+,).
Search for “Font Size” in the search bar.
Find “Editor: Font Size” and set your desired font size.
-Change Keybindings
Go to File > Preferences > Keyboard Shortcuts or press Ctrl+K Ctrl+S

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

-Open Your Program-Open the file you want to debug.
Set Breakpoints: Click in the left margin next to the line numbers where you want to pause execution (a red dot will appear).
-Configure Debug Settings
Go to the Run view by clicking on the Run icon in the Activity Bar.
Click on ‘create a launch.json file’ and select the environment that matches your programming language.
Adjust any settings if necessary in the generated launch.json file.
-Start Debugging
Press F5 or click on the green ‘Start Debugging’ arrow at the top of the Run panel.
The program will run and pause at any breakpoints you’ve set.



10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

-Initialize Repository
Open your project folder in VS Code.
Open the integrated terminal (Ctrl+``) and type git init` to initialize a new Git repository.
-Make Commits
Make changes to your files.
Open the Source Control panel (click on the Source Control icon in the Activity Bar).
Stage your changes by clicking on the ‘+’ sign next to each file or by right-clicking and selecting ‘Stage Changes’.
Enter a commit message in the input box at the top and press Ctrl+Enter to commit the staged changes.
-Push Changes to GitHub:
Link your local repository to a GitHub repository using git remote add origin [URL] in the terminal, where [URL] is the URL of your GitHub repository.
Use git push -u origin master (for the first push) or git push (for subsequent pushes) to push your commits to GitHub.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

