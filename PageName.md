# 0 Requirements #

You need to have an installed Cubic IDE and at least Hollywood 3.0 to use this add on. With version 1.1 hw4cubic automatically distinguishes between Hollywood 3 and Hollywood 4, as with Hollywood 4 you have additonal features!
It was created with AmiKit and OS 3.9, but should work on all platforms that can run Cubic IDE. But if you encounter problems on your platform write a mail to the address provided in the Legal Notice section or post a report in the hw4cubic-Thread at Amiga-Resistance.info: http://www.amig-resistance.info/phpbb33/viewtopic.php?f=38&t=1919

You can download hw4cubic here: http://www.amiga-resistance.info/phpbb33/downloads.php?view=detail&df_id=391

1 General
1.1: syntax highlightning for all Hollywood keywords and functions (depending on you Hollywood version); special labeling for obsolete Hollywood commands, so updating the source code to recommend Hollywood version should be much easier now


1.2: help information after entering a Hollywood function at bottom of Cubic (context sensitive)


1.3: quick access to all chapters form the Hollywood documentation at bottom of Cubic


1.4.1: all hws and hwd files that are located in the same (project) directory are listed on left side of Cubic for quicker access.


1.4.2: Now also image files of the types iff, jpg, png, gif, bmp are listed in a third section. If you simple click the filename of an image it will be opened. If you hold the Shift key while clicking it the filename will be insert into you sourcecode. (V 1.1)

1.5: access to all example source codes that are shiped with Hollywood on left side of Cubic


1.6: automatic indention for the following control structures and blocks:
- If-Else-ElseIf-EndIf
- While-Wend
- For-Next
- Repeat-Until
- Switch-Case-EndSwitch
- Function-EndFunction
- Block-EndBlock

1.7: corressponding bracket (), [.md](.md), {} is marked when cursor is over the other bracket

1.8: separate Hollywood menu while holding right mouse button over GoldED title bar or top of screen respectively

1.9: available in English and German

1.10: compile, debug and error output: Hollywood 4 users will now recognize a new container called "Output". This container show all compile, debug and error output instead of opening a new shell window. Additionally, if you click on a message line that shows an error you will be directed to the corresponding line in the source code. (V 1.1) Attention: AmiKit users should read the FAQ!


1.11: if you right click a file name like --@BRUSH 1, "test.iff"-- you can choose to open the media file (with multiview) (V 1.1)

2 Functions via toolbar
2.1: insert template text of a minimalistic Hollywood programm for quick coding start


2.2: compile source code with separate tool "HWCC" (Hollywood-Cubic-Compiler), which is a GUI for compiling for different plattforms at once


2.3: directly compile versions for AmigaOS 3, AmigaOS 4, AROS, MacOS, MacOS Intel (V 1.1 - just with Hollywood 4), MorphOS, WarpOS, Windows and the Applet version (see screenshot 2.2)

2.4: Button to directly run the coded application (left button on screenshot)


2.5: Button to view the Hollywood documentation guide (second button from the right on screenshot 2.4)

2.6: Button to view the Hollywood tutorial code (right button on screenshot 2.4)

2.7: Button for quick insert of (hard to remember) constants for objects, attributes, coordinates, colors, transitions, fonts and fill styles


3 Functions via keyboard
3.1: pressing F1 while the cursor is over a Hollywood function or keyword displays the corresponding section in the Hollywood documentation guide (context sensitive help); if cursor is not over a word, the main topic of the help guide is displayed


3.2: pressing Shift+F1 while cursor is over a Hollywood function opens the corresponding section of the hollywood.guide in write protect mode within GoldED in a new document, so you can now easily copy examples etc. and paste it into your source code

3.3: pressing F2 compiles the source code to a choosen path and file as a programm for the platform you are working on

3.4: pressing Shift+F2 compiles the source code to a choosen path and file as an applet

3.5: pressing F4 directly runs the coded application in window mode (V 1.0), while Shift+F4 runs it in fullscreen mode. (V 1.1)

3.6: pressing F7 starts HWCC with given paths and file/application names (see screenshot 2.2)

3.7: pressing ESC after typing the beginning of a Hollywood function or keyword completes the word automatically

3.8: pressing Strg+Space after typing the beginning of a Hollywood function or keyword shows a list of all possible functions to insert at cursor position (intellisense)


3.9: pressing Shift+Space after typing in some text completes the word if it was already typed in before (standard Cubic feature)

3.10: several patterns can be typed it to insert complete text templates at cursor position for control structures and blocks
==>
The following patterns are supported:
- If. ==> If-EndIf
- Ifel. ==> If-Else-EndIf
- Ifelif. ==> If-ElseIf-Else-EndIf
- Whi. ==> While-Wend
- For. ==> For-To-Next
- Forst. ==> For-To-Step-Next
- Rep. ==> Repeat-Until
- Swi. ==> Switch-Case-Default-EndSwitch
- Func. ==> Function-EndFunction
- Blo. ==> Block-EndBlock

3.11: pressing Amiga+/ shows a list of all of your defined functions in your source code; clicking at a function will jump to its definition


3.12: pressing Ctrl+f when the cursor is over the call of a user defined function will jump to its definition

4 Troubleshooting/FAQ
Q: I use AmiKit and Hollywood 4. Nearly everytime I compile my source code AmiKit freezes and I have to reboot. What's the problem?
A: It isn't completely clear yet what causes the problem, but a workaround is to disable the tooltype "TOOLPRI" of the application "LimpidClock" (right click on "Limpid Clock" icon, choose "Information", scroll down and double click the entry "TOOLPRI", and save the settings)

Q: I already have an older version of hw4cubic installed. How can I update?
A: Just download the latest archive, unpack it and run the install script (choose "Install ...").
Version History
1.0 (??.04.2009):
- all Hollywood output is send to new GoldEd container (just for Hollywood 4)
- opening the media file from mouse context menu (suggested by Andreas Falkenhahn)
- Shift+F4 runs the application in fullscreen mode (suggested by Andreas Falkenhahn)
- added support for MacOS Intel compiling
- changed folding code from ;/// to ;;;
- the pattern "Func." now also includes the new folding code - altered HWCC (thanks to Martin "McFly" Cornelius and Dominic "Tipsi" Lauternegger for hints and bug finding)
- several bugfixes and changes due to differences between Hollywood 3 and 4 (syntax highlightning and quick help for new functions, ...) (thanks to Dominic "Tipsi" Lauternegger and Andreas Falkenhahn for beta testing)

1.0 (23.11.2008):
- Initial release
Legal Notice
This add on is freeware and was created by Michael "Clyde Radcliffe" Jurisch with the help of the following people:
Dietmar Eilert
Andreas Falkenhahn
Fabio Falcucci
and the Hollywood mailinglist ...

Greetings go to the folks at http://www.amiga-resistance.info

The separate tool HWCC was programmed in Hollywood (of course :-)) and with Fabio Falcuccis ScuiLib. It was compiled natively for AOS3, AOS4 and MorphOS and the correct version will be installed depending on your platform.

copyright 2008/2009 by Michael Jurisch and for plug-in and icons by Dietmar Eilert

Please send bug reports, comments, suggestions, and Pay Pal donations to radcliffe@gmx.de

YOU USE THIS SOFTWARE AT YOUR OWN RISK