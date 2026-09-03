<a href="">
    <img width="1024" alt="Warp Agentic Development Environment product preview" src="/JUNK/preview.png" />
</a>
&nbsp;

## Kaden Terminal

Kaden is a clean feature rich Terminal Emulator where Ctrl+C copies text, Ctrl+A selects it and backspace deletes it, no more awkward three button hotkeys or fiddling with your mouse to perform basic copy pasting.

## Why Kaden?

- **Hotkeys:** Configurable keybindings full clipboard support and smart Ctrl+C to copy / kill, no more using your mouse to select your code or ctrl-shift-c.
- **Zero bloat:** No AI, sign in, account, cloud or drive prompts.
- **Local-first:**, No telemetry, or background network request.
- **Clean:** Beautiful, simple & clutter free UI.
- **Fast:** built in Rust with a lean binary.
- **Modular:** code-base for easier faster development.

### Build & Compiling

```bash
cargo run # Development
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
