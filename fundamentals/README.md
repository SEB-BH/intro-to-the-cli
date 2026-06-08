<h1>
  <span class="headline">Intro to the CLI</span>
  <span class="subhead">Fundamentals</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to open their OS's terminal application and run basic commands.

## Open the terminal application

How you open your terminal application will depend upon your OS.

#### macOS

In macOS, use Spotlight to search for and open Terminal. Press `⌘ Command` + `Space` to open Spotlight and search for `Terminal`. Press `Enter` to open it.

#### Windows

Use your `⊞ Windows key` to search for `Git Bash` and launch it. 

![The Git Bash app in Windows](./assets/git-bash.png)

<details>

<summary> <b> Ubuntu </b>  </summary>

Ubuntu is cool and has a built-in keyboard shortcut to launch the Terminal application: `Ctrl` + `Alt` + `T`.

You can search for `Terminal` on your system and launch the Terminal app that way.

A quick note on the Ubuntu Terminal - copying and pasting uses a different keyboard combination in the terminal.

To copy from the Ubuntu terminal, use `Ctrl` + `Shift` + `C`. To paste text in the Ubuntu terminal, use `Ctrl` + `Shift` + `V`.

</details>


## The terminal interface

Regardless of your operating system, when your terminal application launches, you should see a window similar to the following:

![The terminal app in macOS](./assets/terminal.png)


Here, you'll see the *prompt*. Let's dissect it:

```bash
Omar@DESKTOP-ABC123 MINGW64 ~/code
$
```

Breakdown:

- **Omar** → your username
- **DESKTOP-ABC123** → your computer name
- **MINGW64** → the shell environment
- **~/code** → your current folder
- **$** → ready for a command

> 📚 The *prompt* is a sequence of characters used in a command-line interface to indicate readiness to accept commands.

## Your first command

Since the computer is ready to receive input, let's type in a command:

```bash
whoami
```

Notice that we have control over when this command is executed. If you make a typo, there's still time to go back and fix it. Use your keyboard's arrow keys for this though; clicking with the mouse doesn't work here!

No typos? All ready to run this? Hit `Enter`!

![The whoami command successfully running and printing student](./assets/whoami.png)

This command has a simple job - print the username of the user that runs this command. In the screenshot above, the username is `student`. Yours will likely be different!

After that command finished executing, we were greeted by the prompt once again, and we're free to type more commands!

Let's try an invalid command, just to see what happens:

```bash
blahblah
```

Again, after you've typed this in, hit `Enter` to execute it.

![Oh no, blahblah isn't a valid command!](./assets/blahblah.png)

Our first error! And it's pretty self-explanatory - `zsh: command not found: blahblah`.

We purposefully ran a command we knew was invalid, so it makes sense that it wasn't found. When you see this error, you're trying to run an invalid command!

> 🧠 Notice that the arrow `➜` at the start of the line after we received our error is red. All that this means is that the last command we ran failed in some way; we can still write and execute commands on this line.
