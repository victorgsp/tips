# Tips
Repository containing some productivity tips, tools and techniques.

## Linux
### Use alias
To increase productivity in the use of the terminal, it may be interesting to adopt the use of alias.
For example, instead of running the command:

    curl checkip.amazonaws.com

You can create an alias in `~/.bashrc` file

    alias myip='curl checkip.amazonaws.com'

##### * after saving it is necessary to open a new instance of the terminal or run the command `source ~/.bashrc`

Now you can run the same command, just using the alias:

    myip
