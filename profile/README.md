<div align="center">

<img src="https://raw.githubusercontent.com/langstroth-ai/ligus/main/assets/branding/langstroth-mark.svg" alt="Langstroth" width="96" height="96">

# Langstroth

**Open source, self-hostable, end-to-end encrypted infrastructure for people working with AI agents.**

[Website](https://langstroth.ai) · [Docs](https://docs.langstroth.ai) · [Download Ligus](https://langstroth.ai/ligus/download)

</div>

Langstroth is a platform you run yourself. Its client apps are called **Ligus**
(short for *ligustica*): a shared workspace where you, your teammates and your
coding agents work in one transcript and one working tree. Agents propose
changes and people review and apply them. Everything is a signed, append-only
event log kept on your own devices and synced end to end encrypted, so a relay
only ever sees ciphertext.

## Projects

| Repository | What it is |
| --- | --- |
| [**ligus**](https://github.com/langstroth-ai/ligus) | The Ligus desktop app (macOS, Windows, Linux) and the `ligus` CLI: sync a workspace, run agents headless on a box, host the phone app with `ligus serve` |
| [**ligus-term**](https://github.com/langstroth-ai/ligus-term) | `lt`, a terminal app for multi-agent orchestration on a local or Kubernetes deployment |
| [**langstroth-relay**](https://github.com/langstroth-ai/langstroth-relay) | The relay: a content-blind sync and push relay you can self-host, or use the community relay at `relay.langstroth.ai` |
| [**homebrew-ligus**](https://github.com/langstroth-ai/homebrew-ligus) | Homebrew tap for the desktop app, the `ligus` CLI and `lt` |

## Install

```sh
brew install --cask langstroth-ai/ligus/ligus-app   # desktop app (macOS)
brew install langstroth-ai/ligus/ligus             # CLI
brew install langstroth-ai/ligus/lt                # terminal app
```

Installers for every platform are on the [releases page](https://github.com/langstroth-ai/ligus/releases/latest).

## Get in touch

- Questions and ideas: GitHub Discussions on the [ligus repository](https://github.com/langstroth-ai/ligus/discussions)
- Bugs: [issues](https://github.com/langstroth-ai/ligus/issues) on the repository they belong to
- Security reports: the repository's **Security** tab ("Report a vulnerability")
- Anything else: support@langstroth.ai
