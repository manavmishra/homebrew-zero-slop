# Zero Slop for Homebrew

Install the same CLI, offline scorer and portable skill published on npm:

```sh
brew install manavmishra/zero-slop/zero-slop
```

```sh
zero-slop deslop draft.md --genre professional
zero-slop score draft.md -- --json
zero-slop install
```

`deslop` sends the selected draft to the hosted MCP service. `score` runs locally
and does not upload it. Homebrew installs Node.js and Python for these commands.

This tap contains packaging only. The formula pins the published npm tarball and
its verified SHA-256; it does not fork the editor or change plugin installations.

- [CLI reference](https://github.com/manavmishra/ZeroSlop/blob/main/docs/cli.md)
- [Source and issues](https://github.com/manavmishra/ZeroSlop)
- [Privacy and security](https://github.com/manavmishra/ZeroSlop/blob/main/SECURITY.md)
- [macOS installation acceptance](https://github.com/manavmishra/ZeroSlop/actions/runs/34154855725)

The formula has passed a strict audit, source installation and functional tests
on macOS. Linux Homebrew has not been tested.
