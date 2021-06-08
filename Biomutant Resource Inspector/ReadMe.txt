The inspector is basically a wrapper for the UnrealPak.exe, which is the original Unreal Engine tool to deal with PAK files.
Since there is no special file format or encryption, we can use this. It's dedicated to v4.18.3.
At the moment the compress function works not correctly, Biomutant will not take the modified PAK file.
The PAK file is located in .Steam\steamapps\common\BIOMUTANT\Biomutant\Content\Paks\Biomutant-WindowsNoEditor.pak

Have in mind, that the PAK resource file is very large, have at least 30gb free space on your hard drive.

The tool works without admin privileges, but if something isn't working correctly, this might help.
Tool requieres .NET Framework 4.7.2 to run, make sure this is installed. If you use a up-to-date Windows 10, this should be installed by default.
This tool is for Windows exclusive, no Mac or Linux distribution is supported.

Happy modding!



PS: There is a bug, when you extract and start a compress after that, or compress and start an extract after that. To work around, reopen the tool for every action.
    If the application exits unexpected, the UNrealPak.exe is maybe still open in background. Go and close it in Taskmanager.