# Zig.tmbundle

TextMate 2 Bundle for [Zig](https://ziglang.org).

## Install

```bash
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone https://github.com/ziglang/Zig.tmbundle.git
```

## Commands

| Command | Description                                   | Keyboard Shortcut |
| --------| --------------------------------------------- | ----------------- |
| Build   | Build the current file using `zig build-exe`. | `⌘B`              |
| Run     | Run the current file using `zig run`.         | `⌘R`              |
| Test    | Test the current file using `zig test`.       | `⇧⌘R`             |


## Specifying the `zig` executable

By default, TextMate will look for the `zig` executable in the following locations:

- `/opt/local/bin/zig`
- `/usr/local/bin/zig`
- `/usr/local/zig/bin/zig`

If your `zig` executable is located elsewhere, you can set the `TM_ZIG` variable to the correct location.
