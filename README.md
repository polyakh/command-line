### Getting set up
[Hyperterminal](https://hyper.is/) is a modern, multi-platform terminal app.


### Plugins
- hypercwd - With this plugin, you can easily set your starting directory when opening the terminal.
- hyperterm-dibdabs - Put a little colored dot next to your terminal tabs. Makes a big difference in navigation.
- hyper-search - Search for text in your terminal.
- hyper-blink - Make your cursor blink.
- hyperterm-paste - Makes pasting into hyperterm safe and easy(remove leading $, remove leading whitespaces...)
- hyperlinks - Saving clicks and mouse movements can go a long way.
- hyper-alt-click - An experimental (hacky) plugin to allow moving the cursor by alt+clicking in hyper.
- hyperborder - adds a gradient border to the Hyper terminal
- hyperterm-cursor - a color difference cursor

Settings:
```
{
    fontSize: 30,
    <!-- Powerline fonts -->
    fontFamily: 'Inconsolata for Powerline, Consolas, "Lucida Console", monospace',
}
```

### Navigation
> `cd` => We can move around the file system with the cd (“Change Directory”). => A single dot (.) refers to the current directory. Two dots (..) refer to the parent directory.
> `pwd` => is used to print the 'present working directory'.
> `ls` => contents of the current working directory. 
Flags: 
- -l “long”, which prints the directory contents in a detailed list with metadata. 
- -a "all", which will include hidden files and directories.

### Working with files and folders
> `mkdir` - Creates a directory or subdirectory.
> `touch` - Ceate a file.
>  `rm` - This command allows us to delete individual files. !*It's permanently and irrevocably deleted.
Flags:
- -r This command will delete everything inside some dir<>.
- -f If you have some problem with the file permission, you can use a flag -f (Forse).    

### Interrupting commands
When we're satisfied with the results, we can interrupt it by holding `ctrl` and pressing `c`.
Another helpful command is ctrl + d. This will end the current session. If `ctrl + c` isn't working for some reason, `ctrl + d` may work instead. 

### Opening the project in your IDE
When you fish to start working on a project, you start by navigating to the project's root directory in the terminal. After that, you can run the following command.: `code .`

### Reinstalling dependencies
Here's how we can do this:
`cd <path>` => rm -rf <dir name> => npm/yarn/pnpm

### Working with Git
```
// View changes
git diff

// Create a new local branch
git switch -c [new branch name]

// Switch branches
git switch [branch name]

```

### Lil’ tricks
Suppose we want to bounce back and forth between two directories with cd it's exhausting but we might utilize a helpful comman `-`

Clearing the terminal some different ways:
There are a few ways to accomplish this. There's a `clear` command.
There's you can use a shortcut something like this `ctrl + shift + k`. 


### Aliases
[How to Create Bash Aliases](https://linuxize.com/post/how-to-create-bash-aliases/)


### Switching to a GUI file explorer
On Windows, the `explorer .` command will do this

### Chaining commands
`git add . && git commit -m "Stuff" && git push origin main`
The && operator allows us to chain multiple commands together. The first command will be executed, npm install. The moment it finishes, the second command will be run automatically.

### Terminal tiling and tabs
In Hyper, we can split the window into multiple vertical panes by selecting Shell -> Split down. 
`ctrl + shift + d` to close a current focus window => `ctrl + d`

Resources:
[The Front-End Developer's Guide to the Terminal](https://www.joshwcomeau.com/javascript/terminal-for-js-devs/#opening-the-project-in-your-ide-11)