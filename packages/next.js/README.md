# quasar-proton [WIP]
## A fresh take on creating cross-platform apps.
[![official icon](https://img.shields.io/badge/Quasar%201.0-Official-blue.svg)](https://quasar.dev) 
[![status](https://img.shields.io/badge/Status-Internal%20Review-yellow.svg)](https://github.com/quasarframework/quasar/tree/proton)
[![version](https://img.shields.io/badge/Version-unreleased-yellow.svg)](https://github.com/quasarframework/quasar/tree/proton)

[![Join the chat at https://chat.quasar.dev](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://chat.quasar.dev)
<a href="https://forum.quasar.dev" target="_blank"><img src="https://img.shields.io/badge/community-forum-brightgreen.svg"></a>
[![https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg](https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg)](https://good-labs.github.io/greater-good-affirmation)

**Proton** brings a mode to build Quasar Apps that creates tiny, blazing  <img align="right" src="https://cdn.quasar.dev/logo/proton/proton-logo-240x240.png">
fast binaries for all major desktop platforms. In Quasar's 
[neverending quest](https://quasar.dev/introduction-to-quasar#Why-Quasar%3F) 
for performance and security, the core team is proud to offer an
alternative to Electron.

Whether you are just starting out making apps for your meetup or 
regularly crunch terabyte datasets, we are absolutely confident that 
you will love using Proton as much as we love making and maintaining it.

It leverages Cocoa/WebKit on macOS, gtk-webkit2 on Linux and MSHTML
(IE10/11) or Webkit via Edge on Windows. **Proton** is based on the 
MIT licensed prior work known as [webview](https://github.com/zserge/webview).
The default binding to the underlying webview library uses Rust, but 
other languages are possible (and only a PR away).

### Current Status
We are in the process of vetting this new mode. It is not yet available to
use without jumping through some development hurdles. If you don't care,
please reach out to the team at https://chat.quasar.dev and we'll guide
you through the process.

### Comparison between Proton and Electron

|  | Proton | Electron |
|--|--------|----------|
| Binary Size MacOS | 3.6 MB | 148.7 MB |
| Memory Consumption MacOS | 13 MB | 34.1 MB |
| Benchmark FPS † | TODO | TODO |
| Interface Service Provider | Varies | Chromium |
| Quasar UI | VueJS | VueJS |
| Backend Binding | Rust | Node.js (ECMAScript) |
| Underlying Engine | C++ | V8 (C/C++) |
| FLOSS | Yes | No |
| Multithreading | Yes | No |
| Bytecode Delivery | Yes | No |
| Multiple Windows | Yes | Yes |
| Can Render PDF | Yes | No |
| Updater | Yes | Yes |
| Inter Process Communication (IPC) | Yes | Yes |
| Cross Platform | Yes | Yes |
| Custom App Icon | Yes | Yes |

## Relation to Upstream Origins
We have made the decision to fork, enhance and maintain several upstream
projects here in this repository, in order to guarantee the security of the
code and our ability to enhance it with features that may not be needed for
other consumers.

We hope that this code is useful, but make no claims to suitability or 
guarantees that it will work outside of the Quasar ecosystem.

This has been done with our best attempt at due diligence and in
respect of the original authors. Thankyou - this project would never have
been possible without your amazing contribution to open-source and we are
honoured to carry the torch further. Of special note:
- [zserge](https://github.com/zserge) for the original webview approach
- [Boscop](https://github.com/Boscop) for the Rust Bindings

## Documentation
Head over to the Quasar Framework official website: [https://quasar.dev](https://quasar.dev)

## Stay in Touch
For latest releases and announcements, follow on Twitter: [@quasarframework](https://twitter.com/quasarframework)

## Chat Support
Get realtime help at the official community Discord server: [https://chat.quasar.dev](https://chat.quasar.dev)

## Community Forum
Ask complicated questions at the official community forum: [https://forum.quasar.dev](https://forum.quasar.dev)

## Contributing

Please make sure to read the [Contributing Guide](./.github/CONTRIBUTING.md) before making a pull request. If you have a Quasar-related project/component/tool, add it with a pull request to [this curated list](https://github.com/quasarframework/quasar-awesome)!

Thank you to all the people who already <a href="https://github.com/quasarframework/quasar/graphs/contributors">contributed to Proton</a>!

## Semver
Quasar is following [Semantic Versioning 2.0](https://semver.org/).

## Licenses
Code: (c) 2019 - Daniel Thompson-Yvetot, Razvan Stoenescu, Lucas Nogueira.
MIT and where applicable Apache

Logo: CC-BY-NC-ND
Original Proton Logo Design by [Daniel Thompson-Yvetot](https://github.com/nothingismagick)
Based on the prior work by [Emanuele Bertoldi](https://github.com/zuck)

Note: This license notice will not be complete until we have performed an 
upstream audit. If you feel that your name should be listed here, please
create a PR to this file and provide references so we can fact-check. Thanks!
