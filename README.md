### Getting set up
[Hyperterminal](https://hyper.is/) is a modern, multi-platform terminal app.


### Plugins
- hypercwd - With this plugin, you can easily set your starting direcory when opening the terminal.
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



Resources:
[The Front-End Developer's Guide to the Terminal](https://www.joshwcomeau.com/javascript/terminal-for-js-devs/#opening-the-project-in-your-ide-11)