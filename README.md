# SeraLang
Seralang inspired by St Serafim of Sarov

sera.initsf(sf)! = Initializes the Seralang runtime environment (must be first).

sera.printsf(sf=...)! = Appends text or a variable value (+varname) to the main output buffer.

sera.showsf(sf)! = Prints and clears the main output buffer.

sera.showsf(stg.sf)! = Prints and clears the secondary system output buffer.

sera.timesf(sf=...)! = Pauses execution for the given number of seconds.

sera.usrinp(sf)! = Prompts for user terminal input and appends it to the main buffer.

sera.loginsf(sf)! = Appends the OS username to the secondary buffer.

sera.platsf(sf)! = Appends the operating system platform to the secondary buffer.

sera.datesf(sf)! = Appends the current date (DD-MM-YYYY) to the secondary buffer.

sera.repsf(sf=...)! = Repeats a command a specified number of times with a separator.

sera.calcsf(sf=...)! = Performs math operations (+, -, *, /) and appends the result.

sera.nlsf(sf)! = Appends a newline to the main buffer.

sera.nlsf(stg.sf)! = Appends a newline to the secondary buffer.

sera.websf(sf=...)! = Opens a web URL or program path in the OS.

sera.varsf(sf=...)! = Stores a key-value variable in memory.

!sera--- = Comments or ignores the line.

sera.guisf(sf)! = Enables GUI mode for the script.

sera.messagesf(sf=...)! = Displays a GUI message box with a title and text.

sera.serafsf(sf)! = Displays a quote popup from St. Seraphim of Sarov.

sera.windsf(sf)! = Creates and shows the main Tkinter window.

sera.textsf(sf=...)! = Adds a text label inside the Tkinter window.

sera.filesf(sf)! = Enables file I/O operations.

sera.flwsf(sf=...)! = Writes content to a file (overwrites existing content).

sera.flrsf(sf=...)! = Reads a file and appends its contents to the main buffer.

sera.flasf(sf=...)! = Appends content to the end of a file.
