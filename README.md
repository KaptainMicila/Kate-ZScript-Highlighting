# Kate-ZScript-Highlighting
[ZDoom ZScript](https://zdoom.org/wiki/ZScript) syntax highlighter for [KDE's Kate text editor](https://kate-editor.org/).

Syntax highlighter made with the help from: [marrub--](https://github.com/marrub--)'s [ZScript documentation](https://github.com/marrub--/zdoom-doc) and the basic [Katepart syntax highlighter's documentation](https://docs.kde.org/stable5/en/applications/katepart/highlight.html).

## HOW DO I USE IT?
### PREREQUISITES
- [Kate text editor](https://kate-editor.org/get-it/)

### GETTING THE .XML FILE
You can either get it from the source code from the main branch, or go the the "releases" section and get one version from there.

***IMPORTANT:*** Getting it from the main branch can be dangereous, as that's where the editing appears.
### WHERE TO PUT THE .XML FILE
From the "Overview" section of Katepart's documentation:
#### LINUX
Custom .xml highlight definition files are located in **org.kde.syntax-highlighting/syntax/** in your user folder found with qtpaths--paths GenericDataLocation which usually is **$HOME/.local/share**

***IMPORTANT**: for me, it was $HOME/.var/app/org.kde.kate/data/org.kde.syntax-highlighting/syntax/, where the "org.kde.syntax-highlighting/syntax/ **did not exist**, so I had to create it."*
#### WINDOWS
On Windows these files are located **%USERPROFILE%/AppData/Local/org.kde.syntax-highlighting/syntax**. %USERPROFILE% usually expands to C:\\Users\\user.

### SPECIAL THANKS
- [Nash Muhandes](https://github.com/nashmuhandes) for giving me the will to make this syntax highlighter;
- [marrub--](https://github.com/marrub--) for the ZScript documentation;
- [KDE](https://kde.org/) for giving me the text editor where to write the code;
