
Nimzo_2023 Chess GUI


This program is a fork of the Tarrasch Chess GUI with some enhancements.


HISTORY

I have always enjoyed using Mr Bill Forster's  
Tarrasch Chess GUI.
I think it is the best program to use 
when reading a pdf chess book.

However, I found it rather inconvenient when I wanted to
see best play from a given position.  I had to load the game  
into a different program that had a shootout mode. 

I have some knowledge and experience of programming
and since the Tarrasch source code is open source on the GitHub, 
I decided to try to add this feature.
Given that the Tarrasch program had functions to 
Play white, Play black and Swap sides, all the neccessary functions
were already there and so Shootout mode was not difficult to implement.

I also like doing chess puzzles from PGN files and I usually use 
the open source ChessX program for puzzles because it has a training 
mode that hides the next move in the game and automatically 
responds with the next move for the opposing side.
It also has some nice wooden board bitmaps.
Unfortunately, it does not have a built in clock 
for this mode and I had to use a third-party free timer 
utility called TimeLeft.

So I then decided to add this ChessX training mode with a 
built in timer to the Tarrasch and renamed it puzzle mode.  
It can also be used for studying opening lines.

I also added the capability for user selected board bitmaps.
 
Another feature that I missed using the Tarrasch was 
printing, so I added that as well. 

After this I added a PGN game file search function.

Finally I added the engine vs. engine match capability
and engine tournament functions.



OTHER MINOR FEATURES ADDED

I added some other minor features to the program :-
    
  Edit functions on the right-click pop up variation menu.

  Right mouse click for opposite colour 
  piece placement in position setup	

  Full kibitz option for when the engine is thinking.
  i.e. four distinct lines of play displayed,
       just as when the engine is pondering.

  Game numbers displayed in the game list and 
  Goto game number button

  Bookmark game functions
	
  Goto start/end of game toolbar shortcuts
	
  Display game list toolbar shortcut

  Clear recent files option

  Adjust toolbar height option

  Pause engine toolbar option

  Lightning chess time control option

  Change screen panel backgrounds



FILES  

In the zip file you will find the following files :-


  USER FILES
  ----------

  README1.TXT 	    -  this file    

  setup_Nimzo_2023  -  installation file
  


All of the files that make up the package have been scanned with 
Avast Free Antivirus, program version 23.2.6053

The Nimzo_2023.zip file and the setup_Nimzo_2023.exe file
both check out as totally virus free on VirusTotal.com



INSTALLATION


To install the program run the program  setup_Nimzo_2023.exe 

By default, this will install the program in the directory -

C:\Program Files\Tarrasch  

and PGN files in the 

C:\Users\<user name>\My Documents\Tarrasch directory.

The installation program, CreateInstall free version,
does not associate PGN files with the Nimzo_2023 program.
If you want to implement this feature, 
you have to set it manually with Windows.


If this installation fails, you can download a more comprehensive version
of the installation program from the following links -

https://www.mediafire.com/file/g53mxuczugl527v/Nimzo_2023.7z/file

https://www.dropbox.com/scl/fi/5tgw7uceikb927k4fopjd/Nimzo_2023.7z?rlkey=e8giywjfgl0oebisj8es40xvu&dl=0

This package also contains an installation file for the original
Tarrasch Chess GUI, an opening book utility program,   
separate copies of the files in the installation package and
the source code and developer files used to create the program.

The reason I have not used this package as the default installer
is because it shows a 5/55 virus count on VirusTotal.com
I am pretty sure that these are false positives because this
installer was found to be clean by the following well known virus checkers -
Avast, AVG, Avira, Bitdefender, Kaspersky, McAfee, Sophos
I am sure that one of them would have found a virus if there really was one.



USAGE

Most of the features are faily easy to find and use.

Print.. and Print options.. are in the File menu

Engine match.. and Engine tournament.. are in the Engine menu

Puzzle mode.. is in the Options menu and 
on the toolbar with clock controls

Board bitmaps.. is in the Options menu

All have a help screen that can be seen from the 
selected dialog box.

Change screen colours is in the Options, Colours dialog box.

Adjust toolbar height is in the Options, General dialog box.

The user bitmaps dialog box loads 20 board bitmaps, 
dark and light, from the  \user_bitmaps directory.  
By default this is C:\Program files\Tarrasch\user_bitmaps

The 20 currently in use are bmp_1.bmp up to bmp_20.bmp
However there are a total of 30 bitmaps 
in this directory for you to choose from.

If you want to use a bitmap outside of the top twenty, 
you simply change the names around using windows explorer 
from the \user_bitmaps directory.

e.g.  if you want to use bmp_27 instead of bmp_1
      for the dark squares, rename bmp_1 to bmp_1a or
      something similar and then rename bmp_27 to bmp_1.  

You can also add your own bitmaps to this directory 
but the files have to be converted to .bmp format.  
This can usually be done with windows paint.

I made all of the bitmaps 256 pixels square, 
because other sizes can cause the program to misbehave.

I have added a search games function for PGN files.
This is available when you display the PGN database dialog box.
It is quite extensive in the search options it offers,
but it is rather slow, so I recommend using it on only small
PGN databases, no larger than 50,000 games.


The latest 64-bit Stockfish chess UCI engines can be downloaded from
Stockfish.org

I have made some 32-bit versions of the latest Stockfish engines
which can be downloaded from the following links -

Stockfish_15_1 Mediafire link -

https://www.mediafire.com/file/f52vislcaa4lg5r/Stockfish_15_1_Win32_engines.7z/file

Stockfish_16 Mediafire link -

https://www.mediafire.com/file/geqlgrd9uhmftms/Stockfish_16_Win32_engines.7z/file

Downloads are also available from the following website -

https://nimzo2023chess.000webhostapp.com


TESTING

I have been using the program for a while now with
no problems on a dual core 32-bit Dell computer
with dual boot Windows 7 / Windows 10
I have also tried it on a 64-bit Windows 10 laptop 
using 64-bit UCI engines and it runs ok.

If you have a program crash or other issue and you want me 
to try to fix it, please send me an email at the following address
giving details of the problem and I will try to fix it.    
    
Other comments and feedback can also be sent 
to this address, but I don't guarantee a reply.

    roysf15@outlook.com




ACKNOWLEDGEMENTS

First of all, to Mr Bill Forster, creator of the program.
This is still very much his program and the fact that 
I was able to enhance it is due mainly to his clear and 
easily understood programming style.
He also provided suggestions and advice and pointed out
some bugs which I have now fixed.

Thanks to Mr Julian Smart for his 
wxWidgets printing framework, dialog box templates and 
his book Cross-Platform GUI Programming with wxWidgets

The installation program, setup_Nimzo_2023.exe, 
was made using the free version of the CreateInstall program. 

Other acknowledgements are given within the program.

This program is supplied as freeware with no guarantees 
or waranties of any sort whatsoever.

Feel free to re-distribute the program and the links to it.

Finally, here is the explanation for the name of the program,
which may seem rather curious to many users.
It is a great irony that the idea for this project first
occurred to me when I was studying 'My System' by Aron Nimzowitsch.
Also, it was the preference of Mr Forster that my version
should be called something different to his original program.
I was quite happy to go along with his wishes.


I hope that this program adds to your enjoyment of
the endlessly fascinating game of Chess.


 	Roy Sawyer





