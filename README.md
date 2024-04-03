*scroll down for the English text*

"Poznajemy Forth", dodatkowe materiały do książki Jana Ruszczyca (SOETO 1987, RETRONICS 2024)
=========

Kod w Forth oparty o implementację fig-Forth "APX Extended fig-Forth" dla Atari 8-bit (Atari Archives / APX, poprawione wersje na AtariOnline.pl oraz AtariWiki.org). Zawarto tu:
- obraz ATR, działający z emulatorem (Altirra) i nadający się do skopiowania sektorowego na dyskietkę (QMEG lub DISKCOPY); początkowe ekrany są puste, ekrany 16-17 zawierają spis treści, następne kod z "Poznajemy Forth", dalej wybór kodu z czasopism z lat 80. i 90. (programy te są public domain i/lub oryginalnie były publikowane w celach edukacyjnych)
- skrypt ze źródłami, użyty do "budowania" obrazu ATR (wklejany do Altirry z uruchomionym APX fig-Forth)
- ulotkę, dołączaną do fizycznej dyskietki (w sprzedaży wraz z książką - przez Retronics)

Testy i poprawki w kodzie, adaptacja, kompilacja materiałów została wykonana w całości przez mnie.

Podziękowania dla Retronics za umożliwienie opublikowania części obecnego tu kodu.

-----------------------------------

Additional materials for the book "Poznajemy Forth" ("We study Forth"?), written in Polish by Jan Ruszczyc (SOETO 1987, RETRONICS 2024)
==

The code is based mostly on Atari 8-bit implementation of fig-Forth, called "APX Extended fig-Forth". These materials contain:
- a floppy image (ATR), readable by an emulator (e.g. Altirra), containing sources from the book (Polish word/variable names, consistent with the book) and additional tools (all in English) - published in Forth Dimensions or other magazines from the 1980s/1990s; screens 16-17 contain a list of all included sources, with their origin, dependencies, starting screen and number of screens
- a script (which can be pasted into Altirra according to the included description) which builds above mentioned ATR file, commented mostly in English (with exceptions in Polish, when related to the book)
- a leaflet, added to the physical edition of the floppy, explaining how to run, use and copy it - in Polish, soon to be translated into English 

The book has been released by:
SOETO 1987, RETRONICS 2024.

All the included materials were assembled (often also typed in), embedded into a script, tested, corrected and commented by me.  My thanks go to RETRONICS for allowing me to expose code from their book here.

The APX Forth itself is not included (it can be obtained legally though - see Atari Archive/APX and Atari Wiki/Forth for a fixed version). All the software code had been either originally published with the intention of being used for education and wide usage -- or is explicitly public domain (e.g. Fig editor, the assembler, things from the Forth Dimension). Code from the book itself is itself usually adapted from other Forth materials (books, magazines). 

The below code has been used, adapted, referred to or is otherwise recommended to review (i.e. as the continuation of presented topics):
- Forth Dimensions, Volume   I, Number 5 - Paul Bartholdi, "'TO' Solution Continued...... 'Easter'" (FD issues: https://www.forth.org/fd)
- Forth Dimensions, Volume III, Number 1 - John James, "Correction on Search" 
- Forth Dimensions, Volume III, Number 1 - Kim Harris, "Programming Aids & Utilities"
- Forth Dimensions, Volume III, Number 2 - Paul van der Eijk, "Tracing Colon-Definitions"
- Forth Dimensions, Volume III, Number 3 - S. H. Daniel, "The Forth, Inc. Line Editor"
- Forth Dimensions, Volume III, Number 5 - William F. Ragsdale, "A Forth Assembler for The 6502"
- Forth Dimensions, Volume III, Number 5 - Henry Laxen, "Table Lookup Examples"
- Forth Dimensions, Volume III, Number 6 - Phillip Wasson, "Transient Definitions"
- Forth Dimensions, Volume III, Number 6 - Henry Laxen, "Execution Vectors"
- Forth Dimensions, Volume III, Number 6 - Marc Perkel, "Transportable Control Structures With Compiler Security"
- Forth Dimensions, Volume III, Number 6 - Marc Perkel, "Turning the Stack into Local Variables"
- Forth Dimensions, Volume III, Number 6 - "A Roundtable on Recursion"
- Forth Dimensions, Volume  IV, Number 2 - Robert Dudley Ackerman, "A Recursive Decompiler"
- Forth Dimensions, Volume  IV, Number 3 - Klaxon Suralis, Leo Brodie, "Checksum for Hand-Entered Source Screens"
- Forth Dimensions, Volume   V, Number 1 - Leo Brodie, "Add a Break Point Tool"
- Forth Dimensions, Volume   V, Number 2 - Tom Blakeslee, "Debugging from a Full-Screen Editor"
- Forth Dimensions, Volume   V, Number 4 - Roy W. Sommers, "Vectored Execution and Recursion"
- Forth Dimensions, Volume   V, Number 6 - Norman L. Hills, "Revisited: A Recursive Decompiler"
- Forth Dimensions, Volume  VI, Number 1 - Wendall C. Gates, "Interactive Editing"
- Forth Dimensions, Volume  VI, Number 1 - Birger Olofsson, "Forth List Handling"
- Forth Dimensions, Volume VII, Number 4 - Stephen James, "Atari Painting Forth"
- Compute!, Issue 30 (Nov 1982) - p. 232 - Michael Riley, "Disk Management" (SERT / TRADE)
- Micro (6502 Journal), Number 87 (February 1983) - Mike Dougherty, "EDIT: An Atari FORTH Screen-Oriented Editor"
- Tajemnice Atari (1992-1993) - Roland Pantola, "EDYTOR-FORTH"
- Blinking Characters - RM & COMPUTE 12/81 (??? - TBC)
- FD III/2 for the idea of editor subset (??? - TBC)
- Search: FDIII1p10/KH (??? - TBC)

