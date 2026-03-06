# lumide_rust

[![pub package](https://img.shields.io/pub/v/lumide_rust.svg)](https://pub.dev/packages/lumide_rust) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Powered by SoFluffy](https://img.shields.io/badge/Powered%20by-SoFluffy-orange)](https://sofluffy.io)

The official Rust extension for [Lumide IDE](https://lumide.dev).

`lumide_rust` enables world-class Rust development in Lumide powered by the `rust-analyzer` language server.

## Features

### 🛠 Industrial-Grade Rust Support
- **IntelliSense**: Precise code completions, type hints, and macro expansion.
- **Diagnostics**: Real-time compiler errors and lints right as you type.
- **Navigation**: Powerful go-to-definition, find references, and symbol search.
- **Refactoring**: Specialized Rust code transformations and automated fixes.

### ⚡ Seamless Integration
- **Cargo Native**: Fully understands workspace-level and project-level `Cargo.toml`.
- **LSP Efficient**: Lean starting and immediate responsiveness for large codebases.

## Commands

Access these via the Command Palette (`Cmd+Shift+P` / `Ctrl+Shift+P`):

| Command ID | Title | Description |
|---|---|---|
| `lumide_rust.restartLsp` | **Rust: Restart Language Server** | Restart the `rust-analyzer` process |

## Requirements

- **Rust**: The Rust toolchain must be installed.
- **Rust Analyzer**: The official Rust language server.
    - **Installation**: `rustup component add rust-analyzer`
    - Ensure `rust-analyzer` is in your system `PATH`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Built with ❤️ by [SoFluffy](https://sofluffy.io).

## Happy Coding 🦊
