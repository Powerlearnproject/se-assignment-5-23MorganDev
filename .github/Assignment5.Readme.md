 1:Installation of VS Code:
   Navigate to this url (https://code.visualstudio.com/) which is the VS Code website.
   Select the type the OS type of your machine and download the compatible version of VS Code for your machine. 
   You have to make sure that your machine is 64 Bit and if you are using Windows OS it has to be either Windows 10 or 11.

2. First-time Setup:
    User Settings: These are user profiles that depend on how you want your VS Code to appear when you open. They are stored in a settings.json file and can be accessed via the Settings editor (File > Preferences > Settings) or directly by opening the settings.json file with the Preferences: Open User Settings (JSON) command. reference :https://code.visualstudio.com/docs/getstarted/settings

3. User Interface Overview:
  Activity Bar: Located on the far left-hand side of the VS Code window.
  Purpose: The Activity Bar lets you switch between different views and provides context-specific indicators. It acts as a navigation hub, allowing quick access to various functionalities like Explorer, Search, Source Control, Run, Debug, and Extensions. You can change the position of the Activity Bar according to your preference.

  Side Bar (Primary and Secondary):
  Primary Side Bar: Contains different views like the Explorer to assist you while working on your project. It provides access to files, folders, and resources within your project.
  Secondary Side Bar: Offers an alternative location for displaying views opposite the Primary Side Bar. This can be useful for having two views visible simultaneously, such as the File Explorer on one side and the Source Control view on the other.
  You can toggle between the primary and secondary using this command (Ctrl+Alt+B) or go to View > Appearance > Secondary Side Bar.

  Editor Group: Used to split the editor space according to how you need it. You can split in down, to the left, to the right, up.
  View > Editor Layout > Select the split you want

  Status Bar
  Location: Located at the bottom of the VS Code window.
  Purpose: Displays information about the opened project and the files you are currently editing. It shows details such as the current line and column numbers, encoding, file size.

4. Command Palette: It is a fetaure that provides access to various features and commands in the vs code.
     You can access it by using this shortcut (Ctrl+Shift+P).
     Reference : (https://code.visualstudio.com/docs/getstarted/userinterface)
     USAGE:
    You can use the Command Palette to customize your VS Code environment, including changing settings, managing extensions, and configuring tasks.
     It offers access to commands provided by installed extensions and integrated tools, enabling you to manage extensions, run tasks and debug applications.

    TASKS:
    Running Tasks: Custom tasks can be defined in VS Code to automate repetitive tasks such as compiling code, running tests, or deploying applications. 
    Debugging: The Command Palette provides access to debugging commands, allowing you to start debugging sessions and set breakpoints directly from the editor.
    Managing Extensions: You can install, update, disable, or remove extensions using the Command Palette, streamlining the management of your development tools.
    Reference : (https://code.visualstudio.com/docs/getstarted/userinterface)

5. Extensions in VS Code:Extensions extend the capabilities of VSC Code allowing developers to add languages, debuggers and tools  that support  their dvelopment workflow.
   The Extensions view, accessible via the Extensions icon in the Activity Bar or the View: Extensions command (Ctrl+Shift+X on Windows/Linux), displays a list of popular extensions from the VS Code Marketplace.
   Installing Extensions: To install an extension, simply click on it in the Extensions view. VS Code will handle the download and installation process. Reference: (https://code.visualstudio.com/docs/editor/extension-marketplace)
   Managing Extensions: VS Code provides easy management of extensions through the Extensions view, Command Palette, or command-line switches. Users can enable, disable, update, and uninstall extensions as needed.

   Essential Extensions for Web Development:
   Live Server: Automatically refreshes the browser whenever you save changes to your HTML, CSS, or JavaScript files, simulating a live development server.
   Path Intellisense: Autocompletes filenames in import statements, making it easier to correctly reference files in your project.
   Prettier: An opinionated code formatter that supports many languages, including HTML, CSS, and JavaScript. It ensures consistent formatting across your projects.
   ESLint: Integrates ESLint into VS Code, providing real-time feedback on potential errors in your JavaScript code. It helps maintain code quality and adhere to coding standards.
   Debugger for Chrome: Allows debugging of JavaScript code running in Google Chrome directly from VS Code, simplifying the debugging process for web applications.

6. Integrated Terminal:
    Navigate to Terminal > New Terminal or View > Terminal from the menu bar to open a new terminal session.
    You can also use the keyboard shortcut (Ctrl+Shift+P on windows).

    ADVANTAGES:
    Keeping the terminal integrated within VS Code reduces the need to switch contexts between the editor and an external terminal application, streamlining the development workflow.
    It supports features like links and error detection, enhancing the usability and effectiveness of terminal commands within the VS Code environment.
    Reference: (https://code.visualstudio.com/docs/terminal/basics)

7. File and Folder Management:
    To create a new file, use the (File > New File menu option )or the Ctrl+N (Windows/Linux)keyboard shortcut. This opens a new untitled file in the editor.
    Save the file by selecting (File > Save ) or using the Ctrl+S (Windows/Linux).
    To open an existing file, use the File > Open File... menu option or the Ctrl+O (Windows/Linux). Navigate to the files location to access it.
    The Explorer view, located in the sidebar on the left, provides a hierarchical view of your project's files and folders.
     To add a folder to your workspace, open the folder in VS Code using the File > Open Folder... menu option or the Ctrl+K Ctrl+O (Windows). This adds a new  folder in your workplace.
     Use the Ctrl+P (Windows) shortcut to quickly open files by typing part of their names.

8. Settings and Preferences: Users can find and customize settings through the Settings editor and the settings.json file.
    To change the theme color Go to ( File > Preferences > Color Theme) or use the Preferences: Color Theme command (Ctrl+K Ctrl+T on Windows/Linux) to open the Color Theme picker.
     Use the Up and Down keys to navigate through the list and preview the colors of the theme. The active color theme is stored in your user settings (settings.json) under "workbench.colorTheme"
     Reference: (https://code.visualstudio.com/docs/getstarted/themes)

     FONTS 

     Open the Settings editor (Ctrl+, on Windows/Linux) and search for "font size". Adjust the editor.fontSize setting to your preferred size.
     Directly in settings.json: Add or modify the editor.fontSize property in your settings.json file.
   
9. Debugging in VS Code:
     Start by opening your project in VS Code. If you're working on a new project, create a new folder and open it in VS Code.

     Generate  a launch.json: Go to the Run and Debug view by clicking on the Run and Debug icon in the Activity Bar or pressing Ctrl+Shift+D (Windows/Linux). Then, click on "create a launch.json file" link. VS Code will prompt you to select an environment. Choose the appropriate environment for your project (e.g., Node.js, Python, etc.). If VS Code cannot automatically detect your environment, you may need to select it manually. 
     Configure a launch.json: VS Code creates a launch.json file in the .vscode folder at the root of your project. This file contains configurations for debugging. Reference: (https://code.visualstudio.com/docs/editor/debugging).

     From the Run and Debug View: Select the configuration you want to use from the dropdown at the top of the Run and Debug view, then press the green play button or press F5 to start debugging. 
     Directly from the Code: You can also start debugging by right-clicking anywhere in your code and selecting "Start Debugging", or by pressing F5.
     Reference :(https://code.visualstudio.com/docs/editor/debugging)

10. Using Source Control:
    Open Your Project: Start by opening your project in VS Code. If you're starting a new project, create a new folder and open it in VS Code.
    Initialize Repository: In the Source Control view, click on the "Initialize Repository" button. This action creates a new Git repository in the current folder, allowing you to start tracking code changes. This is equivalent to running git init on the command line.
    Reference :(https://code.visualstudio.com/docs/sourcecontrol/intro-to-git)

    Making Commits: 

  Stage Changes: After making changes to your files, you'll see the changes listed in the Source Control view. To stage changes for commit, click on the "+" icon next to each file or select "Stage All Changes" to stage all modified files.
  Commit Changes: Enter a commit message in the input box at the top of the Source Control view and press Enter to commit the staged changes. Commit messages should briefly describe the changes made.

  Pushing Changes to GitHub :

  Connect to GitHub: Before pushing changes, ensure you're signed into GitHub in VS Code. You can sign in through the Accounts menu in the lower right of the Activity bar. This enables features like cloning and publishing repositories from GitHub.

  Clone or Publish: If you're working with an existing repository on GitHub, you can clone it to your local machine by clicking on the "Clone Repository" button in the Source Control view and entering the URL of the GitHub repository. If you're starting a new project, you can publish it to GitHub by clicking on the "Publish to GitHub" button in the Source Control view and following the prompts to create a new repository on GitHub . Reference :(https://code.visualstudio.com/docs/sourcecontrol/intro-to-git)


  Push Changes: Once your remote repository is connected, you can push your committed changes to GitHub. In the Source Control view, click on the "..." (more actions) button and select "Push" to send your changes to the remote repository. Alternatively, you can use the integrated terminal in VS Code to run (git push origin main) to push your changes .
  Reference: (https://www.gitkraken.com/blog/vs-code-git)

     
