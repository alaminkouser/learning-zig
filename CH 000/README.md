# Chapter 0

Zig is blazingly fast. It is fairly new and has a small community, but it is growing rapidly.

## Installation

Installation is easy. Just download the latest release from the [official website](https://ziglang.org/download/). Current latest version is 0.12.0.

When you have downloaded the binary, you need to unzip/untar it and add the `zig` binary to your `PATH`.

After that, you can run `zig version` to check if the installation was successful. If you see the version number, you are good to go. Else, you need to check your `PATH`.

### LSP

LSP aka Language Server Protocol is a protocol that allows you to use the same editor features across different languages. It will provide you with features like autocompletion, go to definition, find references, etc. You will not need to check the documentation every time you forget a function name or its arguments.

LSP is a must-have for any language. Zig has a Language Server Protocol implementation called `zls`. You can get a pre-built binary from here: [zls](https://github.com/zigtools/zls/releases). You also need to add this binary to your `PATH`.

## Editor

You can use any editor you like, just make sure it supports LSP. I found both `neovim` and `vscode` to be good choices. I personally use `neovim`.
