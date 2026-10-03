pwd prints the absolute path of your current working directory starting from the root folder (e.g., /home/username/coding-cafe).
ls -a reveals hidden files and directories (those starting with a dot, like . and ..), which are omitted by a plain ls command.
The first column in ls -l represents the file type and access permissions (read, write, execute) for the owner, group, and others.
This works because coding-cafe/week02 is interpreted relative to my current location, which is my home directory. It is a relative path because it does not start from the root directory /.
mv did two different jobs: First, mv moved a file from one directory to another. Second, it renamed a file within the same directory.
there are 10 colons
/Library/Frameworks/Python.framework/Versions/3.14/bin/python3
They may be different because different computers can have Python installed in different locations. Their PATH can also be configured differently depending on how Python was installed.
The shell searched the folders listed in my PATH for a program called pyton3, but it could not find one. Since pyton3 was also a typo, there was no matching command to run.
.venv did not appear with plain ls because its name begins with a dot, so it is a hidden directory. ls -a shows hidden files and directories.
(.venv) appeared at the beginning of my prompt. This shows that the virtual environment is currently activated.
It is different from the path I recorded in Q7. Activating the virtual environment changed my PATH so that the .venv/bin directory comes earlier, causing the shell to find the virtual environment's Python first.
The second list contains requests, which was not in the first list. It also installed dependencies required by requests, such as urllib3, certifi, charset-normalizer, and idna.
/Library/Frameworks/Python.framework/Versions/3.14/bin/python3
ls -h displays file sizes in a human-readable format, such as KB, MB, or GB, instead of only showing the size as a number of bytes.
Ctrl+C interrupts the current process, while Ctrl+D sends an end-of-file signal. In this case, Ctrl+C interrupted Python and Ctrl+D then told the interpreter there was no more input, allowing it to exit.