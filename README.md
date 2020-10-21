# Kate-ZScript-Highlighting
[ZDoom ZScript](https://zdoom.org/wiki/ZScript) syntax highlighter for [KDE's Kate text editor](https://kate-editor.org/).

Syntax highlighter made with the help from: [marrub--](https://github.com/marrub--)'s [ZScript documentation](https://github.com/marrub--/zdoom-doc) and the basic [Katepart syntax highlighter's documentation](https://docs.kde.org/stable5/en/applications/katepart/highlight.html).

## HOW DO I USE IT?
### PREREQUISITES
- [Kate text editor](https://kate-editor.org/get-it/)
### WHERE TO PUT THE .xml FILE
From the "Overview" section of Katepart's documentation:
#### LINUX
Custom .xml highlight definition files are located in **org.kde.syntax-highlighting/syntax/** in your user folder found with qtpaths--paths GenericDataLocation which usually is **$HOME/.local/share**

***IMPORTANT**: for me, it was $HOME/.var/app/org.kde.kate/data/org.kde.syntax-highlighting/syntax/, where the "org.kde.syntax-highlighting/syntax/ **did not exist**, so I had to create it."*
#### WINDOWS
On Windows these files are located **%USERPROFILE%/AppData/Local/org.kde.syntax-highlighting/syntax**. %USERPROFILE% usually expands to C:\\Users\\user.
