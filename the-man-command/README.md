<h1>
  <span class="headline">Intro to the CLI</span>
  <span class="subhead">The <code>--help</code> Command</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to use the `--help` flag to find information about commands and their available options.

Each command has different flags and arguments that change how it works.

Fortunately, we can find information about commands directly in our terminal!

## Using `--help`

Many commands support a `--help` flag. This displays information about what the command does and which flags it accepts.

For example, run the following command:

```
rm --help
```

This displays information about the `rm` command, including the flags we can use when removing files.

Try another command:

```
ls --help
```

This shows the available options for listing files and directories.

> 💡 Tip: Some commands use `-h` instead of `--help`. Not every command supports these flags, but they are a useful place to start.

## Using `man` (macOS and Linux)

On macOS and Linux, we can also use the `man` command, which is short for manual.

For example:

```
man rm
```

This opens the manual page for the `rm` command.

You can even run:

```
man man
```

to learn more about the `man` command itself!

> 💡 Windows users: Git Bash does not normally include the `man` command. Use `--help` instead.
