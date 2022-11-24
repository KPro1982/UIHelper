# UIHelper
 The installation files necessary to use UIHelper
This script was designed for folder structure where the mod directory contains a workbench directory. This folder structure is based off of Dabsframework which may have been based off of expansion.

Modname
|
|-- Scripts
|   |
|   |-- Editor
|       |
|       -- Plugins  <--- build.c goes here
|
|
|-- Workbench  
    |   
    |--batchfiles   <--- CreatUniformlayout.bat goes here
    |
    |-- UIHelper   <--- copy UIHelper folder here
    
Step 1 -- build.c  
Build.c contains a simple structure for implementing commands through the plugins menu in workbench. You should already have a build.c so make a backup of that file.  You can either copy the build.c provided or else copy the portion of the file that relates to UIHelper into yours.

Step 2 -- CreateUniformlayout.bat
CreateUniformlayout.bat is called by build.c from step 1.  Simply copy it into the batchfiles directory.

Step 3 -- UIHelper folder
Copy the entire UIHelper folder and all its subfolders into the Workbench folder.

Step 4 -- UIHelper.cfg
Open UIHelper.cfg in notepad++ and replace the file paths so that they point to your modfolder and layouts folder.

Close and restart workbench.  You should have an option in plugins to createuifromlayout.

Note.  If you have a different folder structure you may have to make changes to scripts.
