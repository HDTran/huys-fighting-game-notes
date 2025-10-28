# Huy's Fighting Game Notes

These are Huy's fighting notes copied over from his Obsidian and published on GitHub.

## Development Notes

Use the following to copy files from Obsidian:

```sh
rm -rf content/Street\ Fighter\ 6
cp -r ~/Library/Mobile\ Documents/iCloud~md~obsidian/Documents/Fighters/Street\ Fighter\ 6 content/Street\ Fighter\ 6
```

If you want to symlink to Obsidian notes instead on macOS, you can use this:

```sh
ln -s ~/Library/Mobile\ Documents/iCloud~md~obsidian/Documents/Fighters/Street\ Fighter\ 6 ./Street\ Fighter\ 6
```

Use the following command to build and serve on port `3000`:

```sh
npx quartz build --serve --port 3000
```

## Quartz v4 by Jacky Zhao

> “[One] who works with the door open gets all kinds of interruptions, but [they] also occasionally gets clues as to what the world is and what might be important.” — Richard Hamming

Quartz is a set of tools that helps you publish your [digital garden](https://jzhao.xyz/posts/networked-thought) and notes as a website for free.
Quartz v4 features a from-the-ground rewrite focusing on end-user extensibility and ease-of-use.

🔗 Read the documentation and get started: https://quartz.jzhao.xyz/
