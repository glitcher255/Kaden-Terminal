<a href="">
    <img width="1024" alt="Warp Agentic Development Environment product preview" src="/JUNK/preview.png" />
</a>
&nbsp;

## Kaden Terminal

Kaden is a Terminal Emulator and a fork of warp with proper clipboard support and fully configurable keybindings - designed to be bloat and telemetry free.

## Why Kaden?
- Configure your own hotkeys with full clipboard support and smart copy / kill, no more using your mouse to select your code or awkward ctrl-shift-c to perform basic copy pasting.
- No warp AI, sign in, account, cloud or drive prompts.
- Local-first, no telemetry, background network request or auto-updates.
- Decluttered clean UI.
- Modular code-base for easier faster development (in-progress).
- Fast, built in Rust with a leaner binary.

### Build & Compiling

```bash
cargo run # Testing and development
cargo build --release --bin warp-oss # Create release binary
```

## Contribute

Found a bug or would like to submit a feature or code contribution? please open a GitHub issue.

## Licensing

UI framework (`warpui_core` and `warpui` crates) are licensed under the [MIT license](LICENSE-MIT).

All other code in this repository is licensed under the [AGPL v3](LICENSE-AGPL).

## Open Source Dependencies

- [Tokio](https://github.com/tokio-rs/tokio)
- [NuShell](https://github.com/nushell/nushell)
- [Fig Completion Specs](https://github.com/withfig/autocomplete)
- [Warp Server Framework](https://github.com/seanmonstar/warp)
- [Alacritty](https://github.com/alacritty/alacritty)
- [Hyper HTTP library](https://github.com/hyperium/hyper)
- [FontKit](https://github.com/servo/font-kit)
- [Core-foundation](https://github.com/servo/core-foundation-rs)
- [Smol](https://github.com/smol-rs/smol)
