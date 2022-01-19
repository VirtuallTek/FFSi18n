# Fighter Factory Studio Base Translation Sources
These files are used to translate Fighter Factory Studio to any language using Qt Linguist (https://download.qt.io/linguist_releases/).

# How to Translate
Open Qt Linguist, go to File / Open and select a .ts file. You will be prompted to select source and destination languages. Choose English as source and the language you're translating to as destination and confirm.
To know how to use the program follow the manual here: https://doc.qt.io/qt-5/linguist-translators.html

# How to put it into Fighter Factory
Make a copy of the en-us folder and rename it. Edit Info.xml and fill it with the language and your information. Place all translated files in this folder and you're done (must be the .qm file produced by File / Release, not the .ts ones).
To install on Fighter Factory you must put it inside the languages folder. The location varies based on the host OS:
- Windows: C:\ProgramData\Fighter Factory Studio;
- Linux: /usr/local/share/Fighter Factory Studio;
- macOS X: /Contents/Resources inside the App Blundle.
If you want it to be available in Fighter Factory Studio Installer as an optional package, please send it to me.
