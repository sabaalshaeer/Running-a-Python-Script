# Running-a-Python-Script
Start a Windows command prompt console.
    Select the Start button to show the Windows Start menu.
    Type cmd to search for the Command Prompt program.
    Select the Command Prompt tile to load the Windows Command Prompt window.
Examine the project files.
    In the Command Prompt console, type cd \094021Data and press Enter.
    this changes the current working directory to the location where the course data files are located. If they have been set up in a different location, your instructor will guide you through the steps to navigate to the right location.
    Type dir and press Enter to see a directory listing of this location.
    This lists the files and subdirectories contained in the current working directory. Each directory contains the files for a lesson in the course. The project that contains the script you want to run is located within the "Setting Up Python and Developing a Simple Application Folder". This is a long name for a directory, but to reduce some typing you can use a shortened version of that name to navigate into it.
    Type dir /x and press Enter.
    Shortened alternatives to the long directory names are now shown. The short name for the directory you want to navigate into is "SETTIN~1".
    Type cd settin~1 and press Enter.
    Type dir and press Enter.
    There are two subdirectories, Errors and Finished.
    Type cd finished and press Enter.
    Type dir and press Enter.
    This directory contains a finished version of the project you will create in this course. There are various text files and two Python scripts.
    bartleby.txt, large_file.txt, open-boat.txt, and small.txt are text files containing various book manuscripts that you can pass in to the WordCount program for analysis.
    wordcount.py is a Python script that contains the actual program you will run.
    wordexceptions.py and wordprocess.py are supporting files that contain additional Python code used by the program in wordcount.py.
    wordsEn.txt is a text file that contains a list of over 100,000 common English words that will be searched for within the manuscript when performing an analysis.
Run a completed Python script.
    Type python wordcount.py and press Enter.
    This issues the python command, which loads the Python interpreter.
    Because you passed in the name of the script wordcount.py, that script is loaded into the Python interpreter, translated into machine code, and run.
    The program displays a welcome message, then prompts you for the name of the file you want to analyze.
    Type bartleby.txt and press Enter.
    Progress messages are shown as the program loads the file and analyzes it. A prompt is displayed, asking whether you would like to exclude common words from the results.
    Type y and press Enter.
    After some processing, the word counts are displayed in the console window, with some output possibly scrolling out of view.
    You are asked whether you want to output the results to a file.
    In a moment, you will respond to the input prompt and have the program produce an output file, which will be stored in the WordCount Output folder. If that folder doesn't already exist on the desktop, then the program will create it for you.
    Before you finish running the program, position the Command Prompt window where it will not obstruct your view of the left side of your Windows desktop (the area where This PC, Recycle Bin, and other icons are normally located).
    Type y and press Enter.
    The WordCount Output folder is automatically created on the desktop, and the program lists the files now contained in that folder.
    In the Command Prompt window, type exit and press Enter.
Examine the output files.
    On the desktop, open the Wordcount Output folder.
    Double-click bartleby_results.txt and examine its contents.
    The word counts have been saved in the file.
    Exit the text editor.
    Double-click the dated backup file and examine its contents.
    This file is an exact copy of the results file.
    If you were to run wordcount.py again, the new results would overwrite the contents of the bartleby_results.txt file. However, the new backup file would have a different time in its file name, so the previous dated backup file would remain intact.
    Close the editor where you are viewing the backup file and the File Explorer window where you viewed the contents of the Wordcount Output folder.
    On the desktop, delete the Wordcount Output folder.

