# UIHelper
The installation files necessary to use UIHelper

INSTALLATION INSTRUCTIONS

The following assumes that you are using workbench.  However, CreateUiFromlayout.bat will run from the command-line also so workbench is not necessary. If you do not use workbench, skip steps 1 - 2 below and copy the UIHelper into the main mod directory. If you use workbench, the follow all steps 1 - 4.  

These instructions are based on the folder structure below, which is based on Dabsframework which in turn was based off of the expansion mod structure.

![image](https://user-images.githubusercontent.com/44187035/203859426-406012ac-8786-4849-af38-429b9a6a623a.png)


Step 1 -- build.c  
Build.c contains a simple structure for implementing commands through the plugins menu in workbench. You should already have a build.c so make a backup of that file.  You can either copy the build.c provided or else copy the portion of the file that relates to UIHelper and paste it into yours.
![image](https://user-images.githubusercontent.com/44187035/203859659-9d7c0799-a832-486e-b552-20a1e26d7497.png)

Step 2 -- CreateUiFromlayout.bat

CreateUiFromlayout.bat is called by build.c from step 1.  Simply copy it into the batchfiles directory.

Step 3 -- UIHelper folder

Copy the entire UIHelper folder and all its subfolders into the Workbench folder.

Step 4 -- UIHelper.cfg

Open UIHelper.cfg in notepad++ and replace the file paths so that they point to your layouts, scripts, and inputs folder. Note that the script requires the slash at the end.

![image](https://user-images.githubusercontent.com/44187035/203859753-3966f837-4ac2-49da-a5e4-4c898ae94c9b.png)


Close and restart workbench.  You should have an option in plugins to createuifromlayout.

Note.  If you have a different folder structure you may have to make changes to scripts.  Feel free to contact me on discord Kpro # 3271 or on Enfusion Modders Discord for help installing.
