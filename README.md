# UnityEditorConfigPostprocessor
 A script to include the .editorConfig in a Visual Studio Solution for a Unity project
 
# What and Why
In Unity 2020 the old way of inserting the editorConfig-File into the visual studio solution file now longer works.
This script will fill the gap.
Still works fine with Unity 6.X btw ;-)
 
Requirements
* Unity 2020 with, "Visual Studio Editor".Package in Projekt at least 2.0.5.
* I use VS2019 16.8.1 with VisualStudioTools for Unity.

Links
* How to configure your editorConfig: https://docs.microsoft.com/en-us/visualstudio/ide/editorconfig-code-style-settings-reference?view=vs-2017.
* Including .editorConfig the previous way: https://github.com/zaikman/unity-editorconfig
* Discussion why the old code no longer works: https://forum.unity.com/threads/bug-unity-2020-1-enable_vstu-define-is-gone-and-projectfilegeneration-event-isnt-raised-anymore.942664/

# How
* Put this in Assets/Editor
* Put the .editorConfig in the same folder as Assets and the generated Solutionfile.
* Unity Edit -> Preferences -> External Tools -> Regenerate Project Files.
