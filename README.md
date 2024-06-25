# XAT


"XTREME AUTOMATION TOOL" - a set of tools to enable everyday users to automate complex or repetitive tasks. 
The project was built with the goal of having minimal impact to the system overall, such that it would not impact performance or power measurement in a testing use case.

![tiny](https://github.com/xaviersykora/XAT/assets/127653784/936b048b-09b5-4acb-9636-bc34552d0f73)

There are two tools that work in tandem:

XAT Recorder/Player - Records user inputs to files, plays them back (individually). User can define iterations for playback, and rest period between iterations (when user defined more than 1 iteration).

XAT Playback Module - Plays back user input files captured with XAT Recorder/Player. User can select multiple files to be played in succession. User can define number iterations for selected files to be played back, rest periods between each file playback, and rest periods between each iteration of files being played back (when user defined more than 1 iteration).

Each application is available in light mode ("_l" suffix) and dark mode ("_d" suffix), in both python (for cross-platform users) and compiled executable (for easy windows use). Files made with the Python version should work with the executable, and vise versa.

Here is a silent walkthrough/demo I threw together last minute, I will provide better documentation soon- but if you're eager this should give you the understanding needed.
https://www.youtube.com/watch?v=Q0hk8aLzncM

Executable Requirements:

Visual C++ Redistributable for Visual Studio 2015
https://www.microsoft.com/en-us/download/details.aspx?id=48145

For Python/Cross-Platform Users:
(not required if using compiled exe)

Built on Python 3.12.4

Requires:
tkinter (pip install as tk)
keyboard
pynput

(I think everything else is included in 3.12.4)


DISCLAIMER:

The program asks for admin permissions because I wanted to have admin abilities when automating my own tasks. If you really care and think I'm up to funny business, use the Python script, compile an exe yourself with the script, or edit the manifest with Resource Hacker and skip the administrator ask. Executable with admin ask is just for convenience (in my world at least).


Unlicensed commercial use of this software is strictly prohibited. For license inquiries, please reach out to xaviersykora@gmail.com with "XAT License" in the subject line.
