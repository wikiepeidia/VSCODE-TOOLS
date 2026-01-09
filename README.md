# VSCODE tools and ultitlieis

## VSCODE configured for cl.exe batch quick startup

- new update: we have improved the batch file to automatically detect the VS installation path and GIGGLES, so you don't need to edit the batch file anymore.
- Quick batch file to open developer VS 2022 and configure VSCODE properly for C++/C cl.exe
- You need VS 2022 for this, if you have a lower version, consider editing the code.
- Run ` dir "\VsDevCmd*" /s ` in cmd to know the location of the DEV cmd for VS, copy the path and use it depending on what you have on your PC.
- ![image]( https://github.com/user-attachments/assets/7b90ecc1-2a90-491e-8b18-eec911446d3d )
- When copying to the batch file, please change all the slash \ into / ínstead.
- ![ image ]( https://github.com/user-attachments/assets/a993c3a6-a914-42a7-b7f6-d58f14b2aa5a )
- For those who don't use VS 2022, use BTOOLS <https://visualstudio.microsoft.com/fr/downloads/?q=build+tools> with the given batch file.
- TASK.json has been added because there are currently no proper ways to automatically place the outputted file into a folder, so you need to put this file in the `.vscode` folder.
![image](https://github.com/user-attachments/assets/af82658f-c2ce-4e82-b2fe-be5959321073)

## VSCODE git unignore for git projects

- A git unignore task file to unignore some useful files that are usually ignored by default in VSCODE git projects.
- useful when you accidentally push gabage to github and you wanna unignore it asap
- to run simply do RUn task on vscode or run a command written in task.json to get the alias `git unignore` command
- currently optimize for Windows git bash. Linux need tweaks
