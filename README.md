# mdfind

This is a simple GPTScript wrapper around the `mdfind` command on macOS. It allows you to search for files on your system using the Spotlight index.

> **Warning**: this tool does use the sys.exec tool. It is instructed to only run the command if it is an mdfind command,
> but there is always the chance that the LLM will mess up and run another command.

## Example

```
Tools: github.com/g-linville/mdfind

Find all pdfs in the ~/Downloads directory.
```

## License

This software is available under the Apache 2.0 license. See [LICENSE](LICENSE) for more info.
