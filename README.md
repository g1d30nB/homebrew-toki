# Homebrew tap for Toki

[Toki (時)](https://github.com/g1d30nB/toki) is a desk robot that shows what your Claude agents are doing, and keeps a scrapbook of your days together in stickers. It runs on an M5Stack StackChan.

```bash
brew install g1d30nB/toki/toki
toki setup
```

`toki setup` walks you through everything, one step at a time. See [Toki's README](https://github.com/g1d30nB/toki#readme) for what you need.

Bottles are built here by GitHub Actions (`brew test-bot`) for Apple Silicon Macs on macOS 15 or later, so installing there doesn't need Xcode. On macOS 14 or an Intel Mac, Homebrew builds Toki from source and asks for Apple's Command Line Tools first (`xcode-select --install`).
