<a href="">
    <img width="1024" alt="Warp Agentic Development Environment product preview" src="/JUNK/preview.png" />
</a>
&nbsp;

<h1></h1>

## About
Kaden is a fork from Warp terminal
* Removed all sign in, account, drive and AI prompts
* Local-first, disabled all telemetry, network request and auto-updates
* Decluttered cleaner UI
* Modular code-base for easier faster development (in-progress)

## Licensing

Warp's UI framework (the `warpui_core` and `warpui` crates) are licensed under the [MIT license](LICENSE-MIT).

The rest of the code in this repository is licensed under the [AGPL v3](LICENSE-AGPL).

### Build & Compiling

```bash
cargo run                                                # Testing
cargo build --release --bin warp-oss # Create executable binary
```

## Support and Questions

[`#oss-contributors`](https://warpcommunity.slack.com/archives/C0B0LM8N4DB).

## Open Source Dependencies

[Warp license webpage](https://docs.warp.dev/help/licenses)
- [Tokio](https://github.com/tokio-rs/tokio)
- [NuShell](https://github.com/nushell/nushell)
- [Fig Completion Specs](https://github.com/withfig/autocomplete)
- [Warp Server Framework](https://github.com/seanmonstar/warp)
- [Alacritty](https://github.com/alacritty/alacritty)
- [Hyper HTTP library](https://github.com/hyperium/hyper)
- [FontKit](https://github.com/servo/font-kit)
- [Core-foundation](https://github.com/servo/core-foundation-rs)
- [Smol](https://github.com/smol-rs/smol)
