# Awesome Rust [![lint badge](https://github.com/correia-jpv/fucking-awesome-rust/actions/workflows/lint.yml/badge.svg)](https://github.com/correia-jpv/fucking-awesome-rust/actions/workflows/lint.yml) [![build badge](https://github.com/correia-jpv/fucking-awesome-rust/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/correia-jpv/fucking-awesome-rust/actions/workflows/rust.yml) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/rust-unofficial/awesome-rust/)

A curated list of Rust code and resources.

If you want to contribute, please read [this](CONTRIBUTING.md).

## Table of contents

<!-- toc -->

- [Applications](#applications)
  * [Audio and Music](#audio-and-music)
  * [Blockchain](#blockchain)
  * [Database](#database)
  * [Embedded](#embedded)
  * [Emulators](#emulators)
  * [File manager](#file-manager)
  * [Finance](#finance)
  * [Games](#games)
  * [Graphics](#graphics)
  * [Image processing](#image-processing)
  * [Industrial automation](#industrial-automation)
  * [Message Queue](#message-queue)
  * [MLOps](#mlops)
  * [Observability](#observability)
  * [Operating systems](#operating-systems)
  * [Package Managers](#package-managers)
  * [Payments](#payments)
  * [Productivity](#productivity)
  * [Routing protocols](#routing-protocols)
  * [Security tools](#security-tools)
  * [Social networks](#social-networks)
  * [System tools](#system-tools)
  * [Task scheduling](#task-scheduling)
  * [Text editors](#text-editors)
  * [Text processing](#text-processing)
  * [Utilities](#utilities)
  * [Video](#video)
  * [Virtualization](#virtualization)
  * [Web](#web)
  * [Web Servers](#web-servers)
- [Development tools](#development-tools)
  * [Build system](#build-system)
  * [Debugging](#debugging)
  * [Deployment](#deployment)
  * [Embedded](#embedded-1)
  * [FFI](#ffi)
  * [Formatters](#formatters)
  * [IDEs](#ides)
  * [Profiling](#profiling)
  * [Services](#services)
  * [Static analysis](#static-analysis)
  * [Testing](#testing)
  * [Transpiling](#transpiling)
- [Libraries](#libraries)
  * [Artificial Intelligence](#artificial-intelligence)
    + [Genetic algorithms](#genetic-algorithms)
    + [Machine learning](#machine-learning)
    + [OpenAI](#openai)
    + [Tooling](#tooling)
  * [Astronomy](#astronomy)
  * [Asynchronous](#asynchronous)
  * [Audio and Music](#audio-and-music-1)
  * [Authentication](#authentication)
  * [Automotive](#automotive)
  * [Bioinformatics](#bioinformatics)
  * [Caching](#caching)
  * [Cloud](#cloud)
  * [Command-line](#command-line)
  * [Compression](#compression)
  * [Computation](#computation)
  * [Concurrency](#concurrency)
  * [Configuration](#configuration)
  * [Cryptography](#cryptography)
  * [Data processing](#data-processing)
  * [Data streaming](#data-streaming)
  * [Data structures](#data-structures)
  * [Data visualization](#data-visualization)
  * [Database](#database-1)
  * [Date and time](#date-and-time)
  * [Distributed systems](#distributed-systems)
  * [Domain driven design](#domain-driven-design)
  * [eBPF](#ebpf)
  * [Email](#email)
  * [Encoding](#encoding)
  * [Filesystem](#filesystem)
  * [Finance](#finance-1)
  * [Functional Programming](#functional-programming)
  * [Game development](#game-development)
  * [Geospatial](#geospatial)
  * [Graph algorithms](#graph-algorithms)
  * [Graphics](#graphics-1)
  * [GUI](#gui)
  * [Image processing](#image-processing-1)
  * [Language specification](#language-specification)
  * [Licensing](#licensing)
  * [Logging](#logging)
  * [Macro](#macro)
  * [Markup language](#markup-language)
  * [Mobile](#mobile)
  * [Network programming](#network-programming)
  * [Parsing](#parsing)
  * [Peripherals](#peripherals)
  * [Platform specific](#platform-specific)
  * [Reverse engineering](#reverse-engineering)
  * [Scripting](#scripting)
  * [Simulation](#simulation)
  * [Social networks](#social-networks-1)
  * [System](#system)
  * [Task scheduling](#task-scheduling-1)
  * [Template engine](#template-engine)
  * [Text processing](#text-processing-1)
  * [Text search](#text-search)
  * [Unsafe](#unsafe)
  * [Video](#video-1)
  * [Virtualization](#virtualization-1)
  * [Web programming](#web-programming)
- [Registries](#registries)
- [Resources](#resources)
- [License](#license)

<!-- tocstop -->

## Applications

* <b><code>&nbsp;60431⭐</code></b> <b><code>&nbsp;&nbsp;3191🍴</code></b> [alacritty](https://github.com/alacritty/alacritty)) - A cross-platform, GPU enhanced terminal emulator
* <b><code>&nbsp;&nbsp;&nbsp;622⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Andromeda](https://github.com/tryandromeda/andromeda)) - JavaScript & TypeScript runtime built from the ground up in Rust 🦀 and powered by The Nova Engine.
* 🌎 [Arti](gitlab.torproject.org/tpo/core/arti) - An implementation of Tor. (So far, it's a not-very-complete client. But watch this space!) [![Crates.io](https://img.shields.io/crates/v/arti.svg)](https://crates.io/crates/arti)
* <b><code>&nbsp;&nbsp;&nbsp;345⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [asm-cli-rust](https://github.com/cch123/asm-cli-rust)) - An interactive assembly shell.
* <b><code>&nbsp;75852⭐</code></b> <b><code>&nbsp;&nbsp;5697🍴</code></b> [clash-verge-rev/clash-verge-rev](https://github.com/clash-verge-rev/clash-verge-rev)) - A cross-platform, modern Clash GUI based on tauri & rust, supporting Windows, macOS, and Linux.
* <b><code>&nbsp;&nbsp;6573⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;466🍴</code></b> [cloudflare/boringtun](https://github.com/cloudflare/boringtun)) - A Userspace WireGuard VPN Implementation [![build badge](https://img.shields.io/crates/v/boringtun.svg)](https://crates.io/crates/boringtun)
* <b><code>&nbsp;&nbsp;2304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [defguard](https://github.com/defguard/defguard)) - Enterprise Open Source SSO & WireGuard VPN with real 2FA/MFA
* <b><code>104415⭐</code></b> <b><code>&nbsp;&nbsp;5717🍴</code></b> [denoland/deno](https://github.com/denoland/deno)) - A secure JavaScript/TypeScript runtime built with V8 and Tokio [![Build Status](https://github.com/denoland/deno/actions/workflows/ci.yml/badge.svg)](https://github.com/denoland/deno/actions)
* <b><code>&nbsp;&nbsp;&nbsp;300⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [doprz/dipc](https://github.com/doprz/dipc)) - Convert your favorite images and wallpapers with your favorite color palettes/themes [![crates.io](https://img.shields.io/crates/v/dipc)](https://crates.io/crates/dipc)
* <b><code>&nbsp;&nbsp;7236⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;650🍴</code></b> [EasyTier](https://github.com/EasyTier/EasyTier)) - A simple, full-featured and decentralized mesh VPN with WireGuard support. [![crates.io](https://img.shields.io/crates/v/easytier)](https://crates.io/crates/easytier) [![GitHub actions](https://github.com/EasyTier/EasyTier/actions/workflows/core.yml/badge.svg)](https://github.com/EasyTier/EasyTier/actions/)[![GitHub actions](https://github.com/EasyTier/EasyTier/actions/workflows/gui.yml/badge.svg)](https://github.com/EasyTier/EasyTier/actions/)
* <b><code>&nbsp;12285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;539🍴</code></b> [Edit](https://github.com/microsoft/edit)) - A simple editor for simple needs. [![CI](https://github.com/microsoft/edit/actions/workflows/ci.yml/badge.svg)](https://github.com/microsoft/edit/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;2204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [fcsonline/drill](https://github.com/fcsonline/drill)) - A HTTP load testing application inspired by Ansible syntax
* <b><code>&nbsp;&nbsp;&nbsp;892⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [fend](https://github.com/printfn/fend)) - Arbitrary-precision unit-aware calculator [![build](https://github.com/printfn/fend/workflows/build/badge.svg)](https://github.com/printfn/fend/actions/workflows/actions.yml)
* <b><code>&nbsp;&nbsp;&nbsp;885⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Fractalide](https://github.com/fractalide/fractalide)) - Simple microservices
* <b><code>&nbsp;&nbsp;2664⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;320🍴</code></b> [habitat](https://github.com/habitat-sh/habitat)) - A tool created by Chef to build, deploy, and manage applications.
* <b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Herd](https://github.com/imjacobclark/Herd)) - an experimental HTTP load testing application
* 🌎 [hickory-dns](crates.io/crates/hickory-dns) - A DNS-server [![Build Status](https://github.com/hickory-dns/hickory-dns/actions/workflows/test.yml/badge.svg)](https://github.com/hickory-dns/hickory-dns/actions?query=workflow%3Atest)
* <b><code>&nbsp;&nbsp;5289⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;202🍴</code></b> [innernet](https://github.com/tonarino/innernet)) - An overlay or private mesh network that uses Wireguard under the hood
* <b><code>&nbsp;&nbsp;&nbsp;868⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [jedisct1/flowgger](https://github.com/awslabs/flowgger)) - A fast, simple and lightweight data collector
* <b><code>&nbsp;&nbsp;1786⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [kalker](https://github.com/PaddiM8/kalker)) - A scientific calculator that supports math-like syntax with user-defined variables, functions, derivation, integration, and complex numbers. Cross-platform + WASM support [![Build Status](https://github.com/PaddiM8/kalker/workflows/Release/badge.svg)](https://github.com/PaddiM8/kalker/actions)
* <b><code>&nbsp;&nbsp;1154⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [kftray](https://github.com/hcavarsan/kftray)) - A cross-platform system tray app for managing and sharing multiple kubectl port-forward configurations. [![Build Status](https://github.com/hcavarsan/kftray/workflows/Release/badge.svg)](https://github.com/hcavarsan/kftray/actions)
* <b><code>&nbsp;&nbsp;&nbsp;510⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [kytan](https://github.com/changlan/kytan)) - High Performance Peer-to-Peer VPN
* <b><code>&nbsp;&nbsp;2076⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;282🍴</code></b> [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy)) - Ultralight service mesh for Kubernetes.
* [MaidSafe](https://github.com/maidsafe) - A decentralized platform.
* <b><code>&nbsp;20368⭐</code></b> <b><code>&nbsp;&nbsp;1769🍴</code></b> [mdBook](https://github.com/rust-lang/mdBook)) - A command line utility to create books from markdown files [![Build Status](https://github.com/rust-lang/mdBook/actions/workflows/main.yml/badge.svg)](https://github.com/rust-lang/mdBook/actions)
* <b><code>&nbsp;&nbsp;&nbsp;335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [Mega](https://github.com/web3infra-foundation/mega)) - A monorepo & monolithic codebase management system that supports Git, also is an unofficial open source implementation of Google Piper.
* <b><code>&nbsp;&nbsp;4576⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;153🍴</code></b> [mirrord](https://github.com/metalbear-co/mirrord)) - Connect your local process and your cloud environment, and run local code in cloud conditions
* <b><code>&nbsp;&nbsp;&nbsp;132⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [nicohman/eidolon](https://github.com/nicohman/eidolon)) - A steam and drm-free game registry and launcher for linux and macosx
* 🌎 [Pijul](pijul.org) - A patch-based distributed version control system
* <b><code>&nbsp;&nbsp;&nbsp;762⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [Rauthy](https://github.com/sebadob/rauthy)) - OpenID Connect Single Sign-On Identity & Access Management
* <b><code>&nbsp;&nbsp;5625⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;211🍴</code></b> [Rio](https://github.com/raphamorim/rio)) - A hardware-accelerated GPU terminal emulator powered by WebGPU, focusing to run in desktops and browsers.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [rkik](https://github.com/aguacero7/rkik)) - CLI tool designed for stateless and passive NTP inspection, just as dig or ping are for DNS and ICMP. It supports async requests and continuous monitoring. [![crates.io](https://img.shields.io/crates/v/rkik?logo=rust)](https://crates.io/crates/rkik)
* <b><code>&nbsp;&nbsp;&nbsp;255⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Rust Iot Platform](https://github.com/iot-ecology/rust-iot-platform)) - A high-performance IoT development platform built with Rust, designed for multi-protocol support and real-time data processing. This platform supports MQTT, WebSockets (WS), TCP, and CoAP protocols, making it highly flexible for diverse IoT applications.
* <b><code>&nbsp;&nbsp;3318⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [rx](https://github.com/cloudhead/rx)) - Vi inspired Modern Pixel Art Editor
* <b><code>&nbsp;&nbsp;2723⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Ryot](https://github.com/ignisda/ryot)) - A self hosted application to track media consumption, fitness, etc.
* <b><code>&nbsp;&nbsp;&nbsp;365⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Saga Reader](https://github.com/sopaco/saga-reader)) - A Blazing-Fast and Extremely-Lightweight Internet Reader driven by AI.Supports fetching of search engine information and RSS.
* <b><code>&nbsp;31582⭐</code></b> <b><code>&nbsp;&nbsp;3255🍴</code></b> [Servo](https://github.com/servo/servo)) - A prototype web browser engine
* <b><code>&nbsp;&nbsp;&nbsp;503⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [shoes](https://github.com/cfal/shoes)) - A multi-protocol proxy server
* <b><code>&nbsp;&nbsp;6661⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;280🍴</code></b> [shuttle](https://github.com/shuttle-hq/shuttle)) - A serverless platform.
* <b><code>&nbsp;30608⭐</code></b> <b><code>&nbsp;&nbsp;1067🍴</code></b> [Sniffnet](https://github.com/GyulyVGC/sniffnet)) - Cross-platform application to monitor your network traffic with ease [![build badge](https://img.shields.io/github/actions/workflow/status/gyulyvgc/sniffnet/rust.yml?logo=github)](https://github.com/GyulyVGC/sniffnet/blob/main/.github/workflows/rust.yml) [![crate](https://img.shields.io/crates/v/sniffnet?logo=rust)](https://crates.io/crates/sniffnet)
* <b><code>&nbsp;32749⭐</code></b> <b><code>&nbsp;&nbsp;1347🍴</code></b> [SWC](https://github.com/swc-project/swc)) - super-fast TypeScript / JavaScript compiler
* <b><code>&nbsp;&nbsp;1104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [tiny](https://github.com/osa1/tiny)) - A terminal IRC client
* <b><code>&nbsp;&nbsp;&nbsp;295⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [UpVPN](https://github.com/upvpn/upvpn-app)) - WireGuard VPN client for macOS, Linux, and Windows built on Tauri.
* <b><code>&nbsp;&nbsp;&nbsp;262⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [vproxy](https://github.com/0x676e67/vproxy)) - A high-performance HTTP/HTTPS/SOCKS5 proxy server [![crates.io](https://img.shields.io/crates/v/vproxy.svg)](https://crates.io/crates/vproxy)
* <b><code>&nbsp;20083⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;913🍴</code></b> [wasmer](https://github.com/wasmerio/wasmer)) - A safe and fast WebAssembly runtime supporting WASI and Emscripten [![Build Status](https://github.com/wasmerio/wasmer/actions/workflows/build.yml/badge.svg)](https://github.com/wasmerio/wasmer/actions)
* <b><code>&nbsp;&nbsp;&nbsp;314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Weld](https://github.com/serayuzgur/weld)) - Full fake REST API generator
* <b><code>&nbsp;22001⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;999🍴</code></b> [wezterm](https://github.com/wezterm/wezterm)) - A GPU-accelerated cross-platform terminal emulator and multiplexer
* <b><code>&nbsp;&nbsp;3173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [WinterJS](https://github.com/wasmerio/winterjs)) - A secure JavaScript runtime built with SpiderMonkey and Axum
* <b><code>&nbsp;26522⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;816🍴</code></b> [zellij](https://github.com/zellij-org/zellij)) - A terminal multiplexer (workspace) with batteries included

### Audio and Music

* <b><code>&nbsp;&nbsp;&nbsp;163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [dano](https://github.com/kimono-koans/dano)) - A hashdeep/md5tree (but much more) for media files
* <b><code>&nbsp;&nbsp;&nbsp;348⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [enginesound](https://github.com/DasEtwas/enginesound)) - A GUI and command line application used to procedurally generate semi-realistic engine sounds. Featuring in-depth configuration, variable sample rate and a frequency analysis window.
* <b><code>&nbsp;&nbsp;&nbsp;309⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Festival](https://github.com/hinto-janai/festival)) - A local music player/server/client [![build-badge](https://github.com/hinto-janai/festival/actions/workflows/ci.yml/badge.svg)](https://github.com/hinto-janai/festival/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;&nbsp;102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [figsoda/mmtc](https://github.com/figsoda/mmtc))  🌎 [mmtc](crates.io/crates/mmtc)] - Minimal mpd terminal client that aims to be simple yet highly configurable [![build-badge](https://github.com/figsoda/mmtc/actions/workflows/ci.yml/badge.svg)](https://github.com/figsoda/mmtc/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;2807⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Glicol](https://github.com/chaosprint/glicol)) - Graph-oriented live coding language, for collaborative musicking in browsers.
* <b><code>&nbsp;&nbsp;6141⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;247🍴</code></b> [ncspot](https://github.com/hrkfdn/ncspot)) - Cross-platform ncurses Spotify client, inspired by ncmpc and the likes. [![build badge](https://github.com/hrkfdn/ncspot/actions/workflows/ci.yml/badge.svg)](https://github.com/hrkfdn/ncspot/actions?query=workflow%3ABuild)
* <b><code>&nbsp;&nbsp;&nbsp;553⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Pinepods](https://github.com/madeofpendletonwool/PinePods)) - A rust based podcast management system with multi-user support. Pinepods utilizes a central database so aspects like listen time and themes follow from device to device. With clients built using Tauri, it's a full cross-platform listening solution! [![Docker Container Build](https://github.com/madeofpendletonwool/PinePods/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/madeofpendletonwool/PinePods/actions/workflows/docker-publish.yml)
* <b><code>&nbsp;&nbsp;2398⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [Polaris](https://github.com/agersant/polaris)) - A music streaming application.
* <b><code>&nbsp;&nbsp;5420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Spotify Player](https://github.com/aome510/spotify-player)) - A Spotify player in the terminal with full feature parity.
* <b><code>&nbsp;10340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;482🍴</code></b> [Spotifyd](https://github.com/Spotifyd/spotifyd)) - An open source Spotify client running as a UNIX daemon. [![Continuous Integration](https://github.com/Spotifyd/spotifyd/actions/workflows/ci.yml/badge.svg)](https://github.com/Spotifyd/spotifyd/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;1550⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [termusic](https://github.com/tramhao/termusic)) - Music Player TUI written
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [tunein-cli](https://github.com/tsirysndr/tunein-cli)) - Browse and listen to thousands of radio stations across the globe right from your terminal [![CI](https://github.com/tsirysndr/tunein-cli/actions/workflows/ci.yml/badge.svg)](https://github.com/tsirysndr/tunein-cli/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [WhatBPM](https://github.com/sergree/whatbpm)) - A daily statically generated information resource for electronic dance music producers. Provides daily analytics on the most frequently used values for each EDM genre: tempos, keys, root notes, and so on, using publicly available data such as Beatport and Spotify.

### Blockchain

* <b><code>&nbsp;&nbsp;4638⭐</code></b> <b><code>&nbsp;&nbsp;1699🍴</code></b> [Anchor](https://github.com/solana-foundation/anchor)) - Anchor is the leading development framework for building secure Solana programs (smart contracts).
* <b><code>&nbsp;&nbsp;2802⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;548🍴</code></b> [artemis](https://github.com/paradigmxyz/artemis)) - A simple, modular, and fast framework for writing MEV bots.
* <b><code>&nbsp;&nbsp;&nbsp;264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [beerus](https://github.com/eigerco/beerus)) - Beerus is a trustless StarkNet Light Client, ⚡blazing fast ⚡ [![GitHub Workflow Status](https://github.com/eigerco/beerus/actions/workflows/check.yml/badge.svg)](https://github.com/eigerco/beerus/actions/workflows/check.yml)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Bitcoin Satoshi's Vision](https://github.com/brentongunning/rust-sv))  🌎 [sv](crates.io/crates/sv)] - A library for working with Bitcoin SV.
* <b><code>&nbsp;&nbsp;1805⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;623🍴</code></b> [cairo](https://github.com/starkware-libs/cairo)) - Cairo is the first Turing-complete language for creating provable programs for general computation. This is also the native language of 🌎 [StarkNet](www.starknet.io), a ZK-Rollup using STARK proofs ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/starkware-libs/cairo/CI?style=flat-square&logo=github)
* <b><code>&nbsp;&nbsp;&nbsp;554⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;195🍴</code></b> [cairo-vm](https://github.com/lambdaclass/cairo-vm)) - Implementation of the Cairo VM [![rust](https://github.com/lambdaclass/cairo-vm/actions/workflows/rust.yml/badge.svg)](https://github.com/lambdaclass/cairo-vm/actions/workflows/rust.yml)
* <b><code>&nbsp;&nbsp;&nbsp;327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [ChainX](https://github.com/chainx-org/ChainX)) - Fully Decentralized Interchain Crypto Asset Management on Polkadot.
* <b><code>&nbsp;&nbsp;1306⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;207🍴</code></b> [CITA](https://github.com/citahub/cita)) - A high performance blockchain kernel for enterprise users.
* <b><code>&nbsp;&nbsp;&nbsp;154⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [coinbase-pro-rs](https://github.com/inv2004/coinbase-pro-rs)) - Coinbase pro client, supports sync/async/websocket
* <b><code>&nbsp;16698⭐</code></b> <b><code>&nbsp;&nbsp;2579🍴</code></b> [Diem](https://github.com/diem/diem)) - Diem’s mission is to enable a simple global currency and financial infrastructure that empowers billions of people.
* <b><code>&nbsp;&nbsp;&nbsp;196⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [dusk-network/rusk](https://github.com/dusk-network/rusk)) - Reference implementation of Dusk, a privacy-focused, scalable FMI for real-world assets (RWA) and compliant financial applications. [![Build Status](https://github.com/dusk-network/rusk/actions/workflows/rusk_ci.yml/badge.svg)](https://github.com/dusk-network/rusk/actions/workflows/rusk_ci.yml)
* <b><code>&nbsp;&nbsp;1269⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;503🍴</code></b> [electrumrs](https://github.com/romanz/electrs)) - An efficient re-implementation of Electrum Server.
* <b><code>&nbsp;&nbsp;&nbsp;524⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;199🍴</code></b> [ethabi](https://github.com/rust-ethereum/ethabi)) - Encode and decode smart contract invocations.
* <b><code>&nbsp;&nbsp;&nbsp;178⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [ethaddrgen](https://github.com/Limeth/ethaddrgen)) - Custom Ethereum vanity address generator
* <b><code>&nbsp;&nbsp;&nbsp;357⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [etk](https://github.com/quilt/etk)) - etk is a collection of tools for writing, reading, and analyzing EVM bytecode.
* <b><code>&nbsp;&nbsp;&nbsp;678⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [Forest](https://github.com/ChainSafe/forest)) - Filecoin implementation [![Build Status](https://img.shields.io/circleci/build/gh/ChainSafe/forest/main?branch=master)](https://app.circleci.com/pipelines/github/ChainSafe/forest?branch=main)
* <b><code>&nbsp;&nbsp;9580⭐</code></b> <b><code>&nbsp;&nbsp;2163🍴</code></b> [Foundry](https://github.com/foundry-rs/foundry)) - Foundry is a blazing fast, portable and modular toolkit for Ethereum application development. ![Build Status](https://img.shields.io/github/workflow/status/foundry-rs/foundry/test?style=flat-square)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Grin](https://github.com/mimblewimble/grin/)) - Evolution of the MimbleWimble protocol
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [hdwallet](https://github.com/jjyr/hdwallet))  🌎 [hdwallet](crates.io/crates/hdwallet)] - BIP-32 HD wallet related key derivation utilities.
* <b><code>&nbsp;&nbsp;1299⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;168🍴</code></b> [Holochain](https://github.com/holochain/holochain)) - Scalable P2P alternative to blockchain for all those distributed apps you always wanted to build. [![detect critical check failures](https://github.com/holochain/holochain/actions/workflows/autorebase.yml/badge.svg)](https://github.com/holochain/holochain/actions/)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;518🍴</code></b> [Hyperlane](https://github.com/hyperlane-xyz/hyperlane-monorepo)) - Framework for permissionless, modular interoperability. The offchain clients are written in Rust, as well as the smart contracts for Solana VM and CosmWasm.
* <b><code>&nbsp;&nbsp;&nbsp;483⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;392🍴</code></b> [ibc-rs](https://github.com/informalsystems/hermes)) - Implementation of the 🌎 [Interblockchain Communication](ibc.cosmos.network/) protocol
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [infincia/bip39-rs](https://github.com/infincia/bip39-rs))  🌎 [bip39](crates.io/crates/bip39)] - Implementation of BIP39.
* <b><code>&nbsp;&nbsp;&nbsp;251⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [interBTC](https://github.com/interlay/interbtc)) - Trustless and fully decentralized Bitcoin bridge to Polkadot and Kusama.
* <b><code>&nbsp;&nbsp;1413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [Joystream](https://github.com/Joystream/joystream)) - A user governed video platform
* <b><code>&nbsp;&nbsp;&nbsp;694⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;230🍴</code></b> [Kaspa](https://github.com/kaspanet/rusty-kaspa)) - The fastest, open-source, decentralized & fully scalable Layer-1 in the world.
* <b><code>&nbsp;&nbsp;3298⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;916🍴</code></b> [Lighthouse](https://github.com/sigp/lighthouse)) - Ethereum Consensus Layer (CL) Client [![Build Status](https://github.com/sigp/lighthouse/actions/workflows/test-suite.yml/badge.svg)](https://github.com/sigp/lighthouse/actions)
* <b><code>&nbsp;&nbsp;2496⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;717🍴</code></b> [near/nearcore](https://github.com/near/nearcore)) - decentralized smart-contract platform for low-end mobile devices.
* <b><code>&nbsp;&nbsp;1193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [Nervos CKB](https://github.com/nervosnetwork/ckb)) - Nervos CKB is a public permissionless blockchain, the common knowledge layer of Nervos network.
* <b><code>&nbsp;&nbsp;&nbsp;243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [opensea-rs](https://github.com/gakonst/opensea-rs)) - Bindings & CLI to the Opensea API and Contracts.
* <b><code>&nbsp;&nbsp;&nbsp;727⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [Parity-Bitcoin](https://github.com/paritytech/parity-bitcoin)) - The Parity Bitcoin client
* <b><code>&nbsp;&nbsp;&nbsp;361⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [Phala-Network/phala-blockchain](https://github.com/Phala-Network/phala-blockchain)) - Confidential smart contract blockchain based on Intel SGX and Substrate
* <b><code>&nbsp;&nbsp;2457⭐</code></b> <b><code>&nbsp;&nbsp;1011🍴</code></b> [polkadot-sdk](https://github.com/paritytech/polkadot-sdk)) - The Parity Polkadot Blockchain SDK
* <b><code>&nbsp;&nbsp;5005⭐</code></b> <b><code>&nbsp;&nbsp;1884🍴</code></b> [reth](https://github.com/paradigmxyz/reth)) - Modular, contributor-friendly and blazing-fast implementation of the Ethereum protocol.
* <b><code>&nbsp;&nbsp;1996⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;804🍴</code></b> [revm](https://github.com/bluealloy/revm)) - Revolutionary Machine (revm) is a fast Ethereum virtual machine.
* <b><code>&nbsp;&nbsp;2453⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;886🍴</code></b> [rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)) - Library with support for de/serialization, parsing and executing on data structures and network messages related to Bitcoin.
* <b><code>&nbsp;&nbsp;1299⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;419🍴</code></b> [rust-lightning](https://github.com/lightningdevkit/rust-lightning)) [![Crate](https://img.shields.io/crates/v/lightning.svg?logo=rust)](https://crates.io/crates/lightning) - Bitcoin Lightning library. The main crate,`lightning`, does not handle networking, persistence, or any other I/O. Thus,it is runtime-agnostic, but users must implement basic networking logic, chain interactions, and disk storage.po on linking crate.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [sigma-rust](https://github.com/ergoplatform/sigma-rust)) - ErgoTree interpreter and wallet-related features.
* <b><code>&nbsp;&nbsp;&nbsp;400⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;253🍴</code></b> [Subspace](https://github.com/autonomys/subspace)) - The first layer-one blockchain that can fully resolve the blockchain trilemma by simultaneously achieving scalability, security, and decentralization.
* <b><code>&nbsp;&nbsp;7350⭐</code></b> <b><code>&nbsp;11614🍴</code></b> [Sui](https://github.com/MystenLabs/sui)) - A next-generation smart contract platform with high throughput, low latency, and an asset-oriented programming model powered by the Move programming language.
* <b><code>&nbsp;&nbsp;&nbsp;278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [svm-rs](https://github.com/alloy-rs/svm-rs)) - Solidity-Compiler Version Manager.
* <b><code>&nbsp;&nbsp;&nbsp;663⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;256🍴</code></b> [tendermint-rs](https://github.com/cometbft/tendermint-rs)) - Tendermint blockchain data structures and clients
* <b><code>&nbsp;&nbsp;&nbsp;641⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [wagyu](https://github.com/howardwu/wagyu))  🌎 [wagyu](crates.io/crates/wagyu)] - Library for generating cryptocurrency wallets
* <b><code>&nbsp;&nbsp;5050⭐</code></b> <b><code>&nbsp;&nbsp;2106🍴</code></b> [zcash](https://github.com/zcash/zcash)) - Zcash is an implementation of the "Zerocash" protocol.

### Database

* <b><code>&nbsp;&nbsp;&nbsp;507⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [apecloud/ape-dts](https://github.com/apecloud/ape-dts)) - Data Transfer Suite. Provides data replication between MySQL, PostgreSQL, Redis, MongoDB, Kafka, ClickHouse, and more.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Atomic-Server](https://github.com/atomicdata-dev/atomic-server/))  🌎 [atomic-server](crates.io/crates/atomic_server)] - NoSQL graph database with realtime updates, dynamic indexing and easy-to-use GUI for CMS purposes. [![Release](https://github.com/atomicdata-dev/atomic-server/actions/workflows/release_please.yml/badge.svg)](https://github.com/atomicdata-dev/atomic-server/actions)
* <b><code>&nbsp;&nbsp;3714⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [CozoDB](https://github.com/cozodb/cozo)) - A transactional, relational database that uses Datalog and focuses on graph data and algorithms. Time-travel-capable, and fast! [![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/cozodb/cozo/build.yml?branch=main)](https://github.com/cozodb/cozo/actions/workflows/build.yml)
* <b><code>&nbsp;&nbsp;&nbsp;523⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [darkbird](https://github.com/Rustixir/darkbird))  🌎 [darkbird](crates.io/crates/darkbird)] - HighConcurrency, RealTime, InMemory storage inspired by erlang mnesia
* <b><code>&nbsp;&nbsp;8867⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;818🍴</code></b> [Databend](https://github.com/databendlabs/databend)) - A Modern Real-Time Data Processing & Analytics DBMS with Cloud-Native Architecture [![Release](https://github.com/databendlabs/databend/actions/workflows/release.yml/badge.svg)](https://github.com/databendlabs/databend/actions)
* <b><code>&nbsp;&nbsp;&nbsp;376⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [DB3 Network](https://github.com/dbpunk-labs/db3)) - DB3 is a community-driven blockchain layer2 decentralized database network [![GitHub Workflow Status (with event)](https://github.com/dbpunk-labs/db3/actions/workflows/ci.yml/badge.svg)](https://github.com/dbpunk-labs/db3/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;7076⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;619🍴</code></b> [erikgrinaker/toydb](https://github.com/erikgrinaker/toydb)) - Distributed SQL database, written as a learning project.
* <b><code>&nbsp;&nbsp;1125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Garage](https://github.com/deuxfleurs-org/garage))  🌎 [garage](crates.io/crates/garage)] - S3-compatible distributed object storage service designed for self-hosting at a small-to-medium scale. [![status-badge](https://woodpecker.deuxfleurs.fr/api/badges/1/status.svg)](https://woodpecker.deuxfleurs.fr/repos/1)
* <b><code>&nbsp;&nbsp;2939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;246🍴</code></b> [GlueSQL](https://github.com/gluesql/gluesql)) - Rust library for SQL databases that includes a parser (sqlparser-rs), an execution layer, and a variety of storage options, both persistent and non-persistent, all in one package. [![crates.io](https://img.shields.io/crates/v/gluesql.svg)](https://crates.io/crates/gluesql)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [GreptimeDB](https://github.com/grepTimeTeam/greptimedb/)) - An open-source, cloud-native, distributed time-series database with PromQL/SQL/Python supported.[![CI](https://github.com/greptimeTeam/greptimedb/actions/workflows/develop.yml/badge.svg)](https://github.com/greptimeTeam/greptimedb/actions/workflows/develop.yml)
* <b><code>&nbsp;&nbsp;2668⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [HelixDB](https://github.com/HelixDB/helix-db)) - A powerful, graph-vector database for intelligent data storage for RAG and AI
* <b><code>&nbsp;&nbsp;&nbsp;289⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Hiqlite](https://github.com/sebadob/hiqlite)) - highly-available, embeddable, raft-based SQLite + cache
* 🌎 [indradb](crates.io/crates/indradb) - Graph database
* <b><code>&nbsp;&nbsp;&nbsp;648⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [KiteSQL](https://github.com/KipData/KiteSQL)) - SQL as a Function for Rust
* <b><code>&nbsp;&nbsp;7614⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;602🍴</code></b> [lancedb](https://github.com/lancedb/lancedb))  🌎 [vectordb](crates.io/crates/vectordb)] - A serverless, low-latency vector database for AI applications
* <b><code>&nbsp;&nbsp;&nbsp;384⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Lucid](https://github.com/lucid-kv/lucid)) - High performance and distributed KV store accessible through a HTTP API. [![Build Status](https://github.com/lucid-kv/lucid/workflows/Lucid/badge.svg?branch=master)](https://github.com/lucid-kv/lucid/actions?workflow=Lucid)
* <b><code>&nbsp;&nbsp;6124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;478🍴</code></b> [Materialize](https://github.com/MaterializeInc/materialize)) - Streaming SQL database powered by Timely Dataflow :heavy_dollar_sign:
* <b><code>&nbsp;&nbsp;&nbsp;631⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [native_db](https://github.com/vincent-herlemont/native_db))  🌎 [native_db](crates.io/crates/native_db)] - Drop-in, embedded database for multi-platform apps (server, desktop, mobile). Sync Rust types effortlessly
* <b><code>&nbsp;19780⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;777🍴</code></b> [Neon](https://github.com/neondatabase/neon)) - Serverless Postgres. We separated storage and compute to offer autoscaling, branching, and bottomless storage.
* <b><code>&nbsp;&nbsp;5176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;248🍴</code></b> [noria](https://github.com/mit-pdos/noria))  🌎 [noria](crates.io/crates/noria)] - Dynamically changing, partially-stateful data-flow for web application backends
* <b><code>&nbsp;&nbsp;1334⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [oxigraph/oxigraph](https://github.com/oxigraph/oxigraph))  🌎 [oxigraph](crates.io/crates/oxigraph)] - graph database implementing the 🌎 [SPARQL](www.w3.org/TR/sparql11-overview/) standard ![Crates.io Version](https://img.shields.io/crates/v/oxigraph?logo=Rust)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [ParadeDB](https://github.com/paradedb/paradedb/)) - ParadeDB is an Elasticsearch alternative built on Postgres, designed for real-time search and analytics.
* <b><code>&nbsp;&nbsp;&nbsp;276⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [ParityDB](https://github.com/paritytech/parity-db)) - Fast and reliable database, optimised for read operation
* <b><code>&nbsp;&nbsp;1382⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [PumpkinDB](https://github.com/PumpkinDB/PumpkinDB)) - an event sourcing database engine
* <b><code>&nbsp;26181⭐</code></b> <b><code>&nbsp;&nbsp;1825🍴</code></b> [Qdrant](https://github.com/qdrant/qdrant)) - An open source vector similarity search engine with extended filtering support [![Tests](https://github.com/qdrant/qdrant/actions/workflows/rust.yml/badge.svg)](https://github.com/qdrant/qdrant/actions)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Qrlew/qrlew](https://github.com/Qrlew/qrlew))  🌎 [qrlew](crates.io/crates/qrlew)] - The SQL-to-SQL Differential Privacy layer [![Qrlew](https://github.com/Qrlew/qrlew/actions/workflows/ci.yml/badge.svg)](https://github.com/Qrlew/qrlew/actions) ![Crates.io Version](https://img.shields.io/crates/v/qrlew?logo=Rust)
* <b><code>&nbsp;&nbsp;8366⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;684🍴</code></b> [RisingWaveLabs/RisingWave](https://github.com/RisingWaveLabs/risingwave)) - the next-generation streaming database in the cloud [![CI](https://github.com/risingwavelabs/risingwave/actions/workflows/labeler.yml/badge.svg)](https://github.com/risingwavelabs/risingwave/actions)
* <b><code>&nbsp;&nbsp;1800⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [seppo0010/rsedis](https://github.com/seppo0010/rsedis)) - A Redis reimplementation.
* <b><code>&nbsp;&nbsp;2604⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [Skytable](https://github.com/skytable/skytable)) - A multi-model NoSQL database ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/skytable/skytable/Tests?style=flat-square)
* 🌎 [sled](crates.io/crates/sled) - A (beta) modern embedded database [![Build Status](https://github.com/spacejam/sled/actions/workflows/test.yml/badge.svg)](https://github.com/spacejam/sled/actions?workflow=Rust)
* <b><code>&nbsp;&nbsp;2801⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [SQLSync](https://github.com/orbitinghail/sqlsync)) - Multiplayer offline-first SQLite [![GitHub Workflow Status](https://github.com/orbitinghail/sqlsync/actions/workflows/actions.yaml/badge.svg?branch=main)](https://github.com/orbitinghail/sqlsync/actions?query=branch%3Amain)
* <b><code>&nbsp;30094⭐</code></b> <b><code>&nbsp;&nbsp;1049🍴</code></b> [SurrealDB](https://github.com/surrealdb/surrealdb)) - A scalable, distributed, document-graph database [![Build Status](https://img.shields.io/github/workflow/status/surrealdb/surrealdb/Continuous%20integration/main)](https://github.com/surrealdb/surrealdb/actions)
* <b><code>&nbsp;&nbsp;&nbsp;379⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [TerminusDB](https://github.com/terminusdb/terminusdb-store)) - open source graph database and document store [![Build Status](https://github.com/terminusdb/terminusdb-store/actions/workflows/test.yml/badge.svg)](https://github.com/terminusdb/terminusdb-store/actions)
* <b><code>&nbsp;16156⭐</code></b> <b><code>&nbsp;&nbsp;2213🍴</code></b> [tikv](https://github.com/tikv/tikv)) - A distributed KV database in Rust [![Build Status](https://ci.pingcap.net/job/tikv_ghpr_test/badge/icon)](https://ci.pingcap.net/job/tikv_ghpr_test/)
* <b><code>&nbsp;&nbsp;1180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Tonbo](https://github.com/tonbo-io/tonbo)) - Tonbo is an embedded persistent database built on Apache Arrow & Parquet [![crates.io](https://img.shields.io/crates/v/tonbo.svg)](https://crates.io/crates/tonbo)
* <b><code>&nbsp;&nbsp;3182⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [TrailBase](https://github.com/trailbaseio/trailbase)) - A fast, lightweight, single-file FireBase alternative with type-safe APIs, built-in V8 JS/ES6/TS engine, auth and admin dashboard [![GitHub Workflow Status](https://github.com/trailbaseio/trailbase/workflows/test/badge.svg)](https://github.com/trailbaseio/trailbase/actions?workflow=test)
* <b><code>&nbsp;&nbsp;&nbsp;143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [tsink](https://github.com/h2337/tsink)) - Embedded time-series database for Rust [![crates.io](https://img.shields.io/crates/v/tsink.svg)](https://crates.io/crates/tsink)
* <b><code>&nbsp;13682⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;551🍴</code></b> [Turso](https://github.com/tursodatabase/turso)) - Turso Database is an in-process SQL database, compatible with SQLite.
* <b><code>&nbsp;&nbsp;3143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;226🍴</code></b> [USearch](https://github.com/unum-cloud/usearch)) - Similarity Search Engine for Vectors and Strings [![crates.io](https://img.shields.io/crates/v/usearch.svg)](https://crates.io/crates/usearch)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [valentinus](https://github.com/kn0sys/valentinus)) - Next generation vector database built with LMDB bindings [![Crates.io Version](https://img.shields.io/crates/v/valentinus)](https://crates.io/crates/valentinus)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [vorot93/libmdbx-rs](https://github.com/vorot93/libmdbx-rs))  🌎 [mdbx-sys](crates.io/crates/mdbx-sys)] - Bindings for MDBX, a "fast, compact, powerful, embedded, transactional key-value database, with permissive license". This is a fork of mozilla/lmdb-rs with patches to make it work with libmdbx.
* <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [WooriDB](https://github.com/naomijub/wooridb)) - General purpose time serial database inspired by Crux and Datomic.

### Embedded

* <b><code>&nbsp;&nbsp;1264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [rmk](https://github.com/haobogu/rmk)) - A feature-rich keyboard firmware.
* <b><code>&nbsp;&nbsp;1489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;180🍴</code></b> [uefi-rs](https://github.com/rust-osdev/uefi-rs)) - Rusty wrapper for the Unified Extensible Firmware Interface. This crate makes it easy to develop Rust software that leverages safe, convenient, and performant abstractions for UEFI functionality.

### Emulators

See also 🌎 [crates matching keyword 'emulator'](crates.io/keywords/emulator).

* CHIP-8
  * <b><code>&nbsp;&nbsp;&nbsp;264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [ColinEberhardt/wasm-rust-chip8](https://github.com/ColinEberhardt/wasm-rust-chip8)) - A WebAssembly CHIP-8 emulator.
  * <b><code>&nbsp;&nbsp;&nbsp;152⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [starrhorne/chip8-rust](https://github.com/starrhorne/chip8-rust)) - chip8 emulator
* Commodore 64
  * <b><code>&nbsp;&nbsp;&nbsp;274⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [kondrak/rust64](https://github.com/kondrak/rust64)) - Commodore 64 emulator
* Flash Player
  * <b><code>&nbsp;17223⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;921🍴</code></b> [Ruffle](https://github.com/ruffle-rs/ruffle)) - Ruffle is an Adobe Flash Player emulator. Ruffle targets both the desktop and the web using WebAssembly. [![CI](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml)[![CI](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml)
* Gameboy
  * <b><code>&nbsp;&nbsp;&nbsp;945⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Gekkio/mooneye-gb](https://github.com/Gekkio/mooneye-gb)) - A Game Boy research project and emulator
  * <b><code>&nbsp;&nbsp;&nbsp;653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [joamag/boytacean](https://github.com/joamag/boytacean)) - GameBoy Color emulator that runs on the Web using WebAssembly.
  * <b><code>&nbsp;&nbsp;1410⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [mohanson/gameboy](https://github.com/mohanson/gameboy)) - Full featured Cross-platform GameBoy emulator. Forever boys!.
  * <b><code>&nbsp;&nbsp;&nbsp;649⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [mvdnes/rboy](https://github.com/mvdnes/rboy)) - A Gameboy Emulator
* Gameboy Advance
  * <b><code>&nbsp;&nbsp;&nbsp;632⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [michelhe/rustboyadvance-ng](https://github.com/michelhe/rustboyadvance-ng)) - RustboyAdvance-ng is a Gameboy Advance emulator with desktop, android and 🌎 [WebAssembly](michelhe.github.io/rustboyadvance-ng/) support. [![build badge](https://github.com/michelhe/rustboyadvance-ng/actions/workflows/deploy.yml/badge.svg)](https://github.com/michelhe/rustboyadvance-ng/actions?query=workflow%3ADeploy)
* GameMaker
  * <b><code>&nbsp;&nbsp;&nbsp;353⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [OpenGMK](https://github.com/OpenGMK/OpenGMK)) - OpenGMK is a modern rewrite of the proprietary GameMaker Classic engines, providing a full sourceport of the runner, a decompiler, a TASing framework, and libraries for working with gamedata yourself.
* IBM PC
  * <b><code>&nbsp;&nbsp;&nbsp;732⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [MartyPC](https://github.com/dbalsom/martypc)) - An IBM PC/XT emulator written in Rust.
* Intel 8080 CPU
  * <b><code>&nbsp;&nbsp;&nbsp;118⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [mohanson/i8080](https://github.com/mohanson/i8080)) - Intel 8080 CPU emulator
* iOS
  * <b><code>&nbsp;&nbsp;3177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [touchHLE](https://github.com/touchHLE/touchHLE)) - High-level emulator for iPhone OS apps
* iPod
  * <b><code>&nbsp;&nbsp;&nbsp;193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [clicky](https://github.com/daniel5151/clicky)) - A clickwheel iPod emulator (WIP)
* NES
  * <b><code>&nbsp;&nbsp;&nbsp;798⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [koute/pinky](https://github.com/koute/pinky)) - A NES emulator
  * <b><code>&nbsp;&nbsp;&nbsp;753⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [pcwalton/sprocketnes](https://github.com/pcwalton/sprocketnes)) - A NES emulator
* Nintendo 64
  * <b><code>&nbsp;&nbsp;&nbsp;447⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [gopher64](https://github.com/gopher64/gopher64)) - N64 emulator written in Rust
* Nintendo DS
  * <b><code>&nbsp;&nbsp;&nbsp;287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [dust](https://github.com/kelpsyberry/dust)) - A Nintendo DS emulator
* PlayStation 4
  * <b><code>&nbsp;&nbsp;&nbsp;750⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Obliteration](https://github.com/obhq/obliteration)) - Experimental PS4 emulator for Windows, macOS and Linux [![CI](https://github.com/obhq/obliteration/actions/workflows/main.yml/badge.svg)](https://github.com/obhq/obliteration/actions/workflows/main.yml)
* Shockwave Player
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [DirPlayer](https://github.com/igorlira/dirplayer-rs)) - A web-compatible Shockwave Player emulator written in Rust
* ZX Spectrum
  * <b><code>&nbsp;&nbsp;&nbsp;209⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [rustzx/rustzx](https://github.com/rustzx/rustzx)) - [![RustZX CI](https://github.com/rustzx/rustzx/actions/workflows/ci.yml/badge.svg)](https://github.com/rustzx/rustzx/actions/workflows/ci.yml)

### File manager

* <b><code>&nbsp;11911⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;264🍴</code></b> [broot](https://github.com/Canop/broot)) - A new way to see and navigate directory trees (get an overview of a directory, even a big one; find a directory then `cd` to it; never lose track of file hierarchy while you search; manipulate your files, ...), further reading 🌎 [dystroy.org/broot](dystroy.org/broot/) [![Latest Version](https://img.shields.io/crates/v/broot.svg)](https://crates.io/crates/broot)
* <b><code>&nbsp;&nbsp;3618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;160🍴</code></b> [joshuto](https://github.com/kamiyaa/joshuto)) - ranger-like terminal file manager
* <b><code>&nbsp;&nbsp;4547⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [xplr](https://github.com/sayanarijit/xplr)) - A hackable, minimal, fast TUI file explorer
* <b><code>&nbsp;28486⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;610🍴</code></b> [yazi](https://github.com/sxyazi/yazi)) - Blazing fast terminal file manager, based on async I/O.

### Finance

See also [Payments](#payments) applications.

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [klirr](https://github.com/Sajjon/klirr))  🌎 [klirr](crates.io/crates/klirr)] - Zero-maintenance and smart FOSS generating beautiful invoices for services and expenses.
* <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [tackler](https://github.com/tackler-ng/tackler))  🌎 [tackler](crates.io/crates/tackler)] - Fast, reliable bookkeeping engine with native GIT SCM support for plain text accounting [![CI Badge](https://github.com/tackler-ng/tackler/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/tackler-ng/tackler/blob/main/.github/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;1415⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [tarkah/tickrs](https://github.com/tarkah/tickrs)) - Realtime ticker data in your terminal

### Games

See also <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Games Made With Piston](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston)).

* <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [buxx/OpenCombat](https://github.com/buxx/OpenCombat)) - A realtime 2nd world war tactical game
* <b><code>&nbsp;&nbsp;&nbsp;699⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [chess-tui](https://github.com/thomas-mauran/chess-tui)) - A Chess TUI implementation ♟️
* <b><code>&nbsp;&nbsp;8009⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;347🍴</code></b> [citybound](https://github.com/citybound/citybound)) - The city sim you deserve
* <b><code>&nbsp;&nbsp;2388⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [cristicbz/rust-doom](https://github.com/cristicbz/rust-doom)) - A renderer for Doom, may progress to being a playable game
* <b><code>&nbsp;&nbsp;1108⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [doukutsu-rs](https://github.com/doukutsu-rs/doukutsu-rs)) - Reimplementation of Cave Story engine with some enhancements.
* <b><code>&nbsp;&nbsp;&nbsp;534⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [garkimasera/rusted-ruins](https://github.com/garkimasera/rusted-ruins)) - Extensible open world rogue like game with pixel art
* <b><code>&nbsp;&nbsp;&nbsp;286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [GitType](https://github.com/unhappychoice/gittype)) - A CLI code-typing game that turns your source code into typing challenges
* <b><code>&nbsp;&nbsp;1311⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [gorilla-devs/ferium](https://github.com/gorilla-devs/ferium)) - Ferium is a fast and feature rich CLI program for downloading and updating Minecraft mods from Modrinth, CurseForge, and GitHub Releases, and modpacks from Modrinth and CurseForge ![ferium build](https://github.com/gorilla-devs/ferium/actions/workflows/build.yml/badge.svg?branch=main)
* <b><code>&nbsp;&nbsp;&nbsp;103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [HactarCE/Hyperspeedcube](https://github.com/HactarCE/Hyperspeedcube)) - A modern, beginner-friendly 3D and 4D Rubik's cube simulator with customizable mouse and keyboard controls and advanced features for speedsolving
* <b><code>&nbsp;&nbsp;&nbsp;104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [lifthrasiir/angolmois-rust](https://github.com/lifthrasiir/angolmois-rust)) - A minimalistic music video game which supports the BMS format
* <b><code>&nbsp;&nbsp;&nbsp;141⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [maras-archive/rsnake](https://github.com/maras-archive/rsnake)) - Snake.
* <b><code>&nbsp;&nbsp;&nbsp;884⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [mcthesw/game-save-manager](https://github.com/mcthesw/game-save-manager)) - A user-friendly tool for managing game saves [![build badge](https://github.com/mcthesw/game-save-manager/actions/workflows/tauri.yml/badge.svg)](https://github.com/mcthesw/game-save-manager/actions/workflows/tauri.yml)
* <b><code>&nbsp;&nbsp;4315⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [mtkennerly/ludusavi](https://github.com/mtkennerly/ludusavi)) - Backup tool for PC game saves [![build badge](https://img.shields.io/github/actions/workflow/status/mtkennerly/ludusavi/main.yaml?logo=github)](https://github.com/mtkennerly/ludusavi/actions/workflows/main.yaml) [![crate](https://img.shields.io/crates/v/ludusavi?logo=rust)](https://crates.io/crates/ludusavi)
* <b><code>&nbsp;&nbsp;1446⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [ozkriff/zemeroth](https://github.com/ozkriff/zemeroth)) - A small 2D turn-based hexagonal strategy game
* <b><code>&nbsp;&nbsp;&nbsp;165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [rhex](https://github.com/dpc/rhex)) - hexagonal ascii roguelike
* <b><code>&nbsp;&nbsp;&nbsp;383⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [rsaarelm/magog](https://github.com/rsaarelm/magog)) - A roguelike game.
* <b><code>&nbsp;&nbsp;&nbsp;390⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [SoftbearStudios/mk48](https://github.com/SoftbearStudios/mk48)) - Mk48.io is an online multiplayer naval combat game
* <b><code>&nbsp;&nbsp;&nbsp;162⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [swatteau/sokoban-rs](https://github.com/swatteau/sokoban-rs)) - A Sokoban implementation
* <b><code>&nbsp;&nbsp;&nbsp;196⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [thetawavegame/thetawave-legacy](https://github.com/thetawavegame/thetawave-legacy)) - A space shooter game that strives to be an entry point for new game developers to make their first contributions. ![build badge](https://github.com/thetawavegame/thetawave-legacy/actions/workflows/ci.yml/badge.svg?branch=master)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Thinkofname/rust-quake](https://github.com/Thinkofname/rust-quake)) - Quake map renderer.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [topheman/snake-pipe-rust](https://github.com/topheman/snake-pipe-rust)) - A snake game in the terminal based on stdin/stdout (+tcp and unix domain sockets) [![crates.io](https://img.shields.io/crates/v/snakepipe.svg)](https://crates.io/crates/snakepipe)
* 🌎 [ttyperacer/terminal-typeracer](gitlab.com/ttyperacer/terminal-typeracer) - Single player typing test game written for the terminal
* 🌎 [Veloren](gitlab.com/veloren/veloren) - An open world, open source multiplayer voxel RPG game currently in alpha development [![build badge](https://gitlab.com/veloren/veloren/badges/master/pipeline.svg)](https://gitlab.com/veloren/veloren/-/pipelines)
* <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [zipxing/rust_pixel](https://github.com/zipxing/rust_pixel))  🌎 [rust_pixel](crates.io/crates/rust_pixel)] - A 2D pixel art game engine & rapid prototyping tools, supporting both text and graphical rendering modes.
* <b><code>&nbsp;&nbsp;&nbsp;388⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Zone of Control](https://github.com/ozkriff/zoc)) - A turn-based hexagonal strategy game

### Graphics

* <b><code>&nbsp;&nbsp;&nbsp;255⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [dps/rust-raytracer](https://github.com/dps/rust-raytracer)) - An implementation of a very simple raytracer based on Ray Tracing in One Weekend by Peter Shirley.
* <b><code>&nbsp;10335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;394🍴</code></b> [flxzt/rnote](https://github.com/flxzt/rnote)) - Sketch and take handwritten notes.
* <b><code>&nbsp;&nbsp;4048⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [ivanceras/svgbob](https://github.com/ivanceras/svgbob)) - converts ASCII diagrams into SVG graphics
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [KaminariOS/rustracer](https://github.com/KaminariOS/rustracer)) - A PBR glTF 2.0 renderer based on Vulkan ray-tracing.
* <b><code>&nbsp;&nbsp;&nbsp;220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Limeth/euclider](https://github.com/Limeth/euclider)) - A real-time 4D CPU ray tracer
* <b><code>&nbsp;&nbsp;3376⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;277🍴</code></b> [linebender/resvg](https://github.com/linebender/resvg)) - An SVG rendering library.
* <b><code>&nbsp;&nbsp;&nbsp;196⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [rodrigorc/papercraft](https://github.com/rodrigorc/papercraft)) - A tool to unwrap 3D models and create them in paper with scissors and glue.
* <b><code>&nbsp;&nbsp;&nbsp;314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [rustq/vue-skia](https://github.com/rustq/vue-skia)) - Skia based 2d graphics vue rendering library. It is based on Rust to implement software rasterization to perform rendering.
* 🌎 [turnage/valora](crates.io/crates/valora) - A library for generative fine art
* <b><code>&nbsp;&nbsp;&nbsp;524⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Twinklebear/tray_rust](https://github.com/Twinklebear/tray_rust)) - A ray tracer
* <b><code>&nbsp;&nbsp;&nbsp;828⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [wahn/rs_pbrt](https://github.com/wahn/rs_pbrt)) - Implements a counterpart to the PBRT book's (3rd edition) C++ code.

### Image processing

* <b><code>&nbsp;&nbsp;&nbsp;696⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Imager](https://github.com/imager-io/imager)) - Automated image optimization.
* <b><code>&nbsp;&nbsp;3519⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [oxipng](https://github.com/oxipng/oxipng))  🌎 [oxipng](crates.io/crates/oxipng)] - Multithreaded PNG optimizer written in Rust. [![Build Status](https://github.com/oxipng/oxipng/workflows/oxipng/badge.svg)](https://github.com/oxipng/oxipng/actions?query=branch%3Amaster) [![Version](https://img.shields.io/crates/v/oxipng.svg)](https://crates.io/crates/oxipng)

### Industrial automation

* <b><code>&nbsp;&nbsp;&nbsp;555⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;150🍴</code></b> [locka99/opcua](https://github.com/locka99/opcua)) - A 🌎 [OPC UA](opcfoundation.org/about/opc-technologies/opc-ua/) library.
* <b><code>&nbsp;&nbsp;&nbsp;502⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [slowtec/tokio-modbus](https://github.com/slowtec/tokio-modbus)) - A 🌎 [tokio](tokio.rs)-based 🌎 [modbus](www.modbus.org) library.

### Message Queue

* <b><code>&nbsp;&nbsp;1285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;193🍴</code></b> [RobustMQ](https://github.com/robustmq/robustmq)) - Next generation cloud-native converged message queue.
* <b><code>&nbsp;&nbsp;1294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;175🍴</code></b> [Rocketmq-Rust](https://github.com/mxsm/rocketmq-rust)) - 🚀Apache RocketMQ build in Rust🦀. Faster, safer, and with lower memory usage.

### MLOps

* <b><code>&nbsp;10339⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;701🍴</code></b> [TensorZero](https://github.com/tensorzero/tensorzero)) - data & learning flywheel for LLMs that unifies inference, observability, optimization, and experimentation ![TensorZero Build Status](https://img.shields.io/github/check-runs/tensorzero/tensorzero/main)

### Observability

* <b><code>&nbsp;&nbsp;&nbsp;235⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [avito-tech/bioyino](https://github.com/avito-tech/bioyino)) - A high-performance scalable StatsD compatible server.
* <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [MegaAntiCheat/client-backend](https://github.com/MegaAntiCheat/client-backend)) - The client app for [MAC](https://github.com/MegaAntiCheat).
* <b><code>&nbsp;16709⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;663🍴</code></b> [openobserve](https://github.com/openobserve/openobserve)) - 10x easier, 140x lower storage cost, high performance, petabyte scale - Elasticsearch/Splunk/Datadog alternative.
* 🌎 [OpenTelemetry](crates.io/crates/opentelemetry) - OpenTelemetry provides a single set of APIs, libraries, agents, and collector services to capture distributed traces and metrics from your application. You can analyze them using Prometheus, Jaeger, and other observability tools. [![GitHub Actions CI](https://github.com/open-telemetry/opentelemetry-rust/actions/workflows/ci.yml/badge.svg)](https://github.com/open-telemetry/opentelemetry-rust/actions/workflows/ci.yml)
* <b><code>&nbsp;10429⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;486🍴</code></b> [Quickwit-oss/quickwit](https://github.com/quickwit-oss/quickwit)) - Cloud-native and highly cost-efficient search engine for log management. [![CI](https://github.com/quickwit-oss/quickwit/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/quickwit-oss/quickwit/actions?query=workflow%3ACI)
* <b><code>&nbsp;&nbsp;1836⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [Scaphandre](https://github.com/hubblo-org/scaphandre)) - A power consumption monitoring agent, to track host and each service power consumption and enable designing systems and applications for more sustainability. Designed to fit any monitoring toolchain (already supports prometheus, warp10, riemann...).
* <b><code>&nbsp;20374⭐</code></b> <b><code>&nbsp;&nbsp;1864🍴</code></b> [vectordotdev/vector](https://github.com/vectordotdev/vector)) - A High-Performance, Logs, Metrics, & Events Router.

### Operating systems

See also <b><code>&nbsp;&nbsp;&nbsp;806⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [A comparison of operating systems written in Rust](https://github.com/flosse/rust-os-comparison)).

* <b><code>&nbsp;&nbsp;&nbsp;119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [0x59616e/SteinsOS](https://github.com/0x59616e/SteinsOS)) - An OS for armv8-a architecture.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [adamperkowski/highlightos](https://github.com/adamperkowski/highlightos)) - x86_64 OS kernel written in Rust & Assembly.
* <b><code>&nbsp;&nbsp;1240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Andy-Python-Programmer/aero](https://github.com/Andy-Python-Programmer/aero)) - A modern, unix-like operating system following the monolithic kernel design.
* <b><code>&nbsp;&nbsp;3595⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;221🍴</code></b> [asterinas/asterinas](https://github.com/asterinas/asterinas)) - A secure, fast, and general-purpose OS kernel that provides Linux-compatible ABI.
* <b><code>&nbsp;&nbsp;1050⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [DragonOS-Community/DragonOS](https://github.com/DragonOS-Community/DragonOS)) - An operating system with a self-developed kernel from scratch and Linux compatibility.
* 🌎 [redox-os/redox](gitlab.redox-os.org/redox-os/redox) - A Unix-like general-purpose microkernel-based operating system with a focus on security, stability, performance, correctness, simplicity and pragmatism that aims to be a complete alternative for Linux and BSD.
* <b><code>&nbsp;&nbsp;&nbsp;803⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os)) - An OS kernel written in rust. Non POSIX
* <b><code>&nbsp;&nbsp;3050⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;181🍴</code></b> [theseus-os/Theseus](https://github.com/theseus-os/Theseus)) - A safe-language, single address space and single privilege level OS written from scratch - [![build badge](https://img.shields.io/github/workflow/status/theseus-os/Theseus/Documentation?label=docs%20build)](https://www.theseus-os.com/Theseus/book/index.html)
* <b><code>&nbsp;&nbsp;6008⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;769🍴</code></b> [tock/tock](https://github.com/tock/tock)) - A secure embedded operating system for Cortex-M based microcontrollers
* <b><code>&nbsp;&nbsp;1012⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [vinc/moros](https://github.com/vinc/moros)) - A text-based hobby operating system targeting computers with a x86-64 architecture and a BIOS.

### Package Managers

* <b><code>&nbsp;&nbsp;&nbsp;298⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [helsing-ai/buffrs](https://github.com/helsing-ai/buffrs))  🌎 [buffrs](crates.io/crates/buffrs)] - A modern package manager for protocol buffers and gRPC architectures.
* 🌎 [rebos](crates.io/crates/rebos) - A declarative way to automate package management on any linux distro [![crate](https://img.shields.io/crates/v/rebos?logo=rust)](https://crates.io/crates/rebos)

### Payments

* <b><code>&nbsp;34163⭐</code></b> <b><code>&nbsp;&nbsp;4203🍴</code></b> [hyperswitch](https://github.com/juspay/hyperswitch)) - An open source payments orchestrator that lets you connect with multiple payment processors and route payment traffic effortlessly, all with a single API integration ![GitHub last commit](https://img.shields.io/github/last-commit/juspay/hyperswitch?style=flat-square)

### Productivity

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [0xdea/jiggy](https://github.com/0xdea/jiggy))  🌎 [jiggy](crates.io/crates/jiggy)] - Minimalistic cross-platform mouse jiggler written in Rust [![build](https://github.com/0xdea/jiggy/actions/workflows/build.yml/badge.svg)](https://github.com/0xdea/oneiromancer/jiggy/workflows/build.yml)
* <b><code>&nbsp;&nbsp;8204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;529🍴</code></b> [aichat](https://github.com/sigoden/aichat)) - All-in-one LLM CLI tool featuring Shell Assistant, Chat-REPL, RAG, AI Tools & Agents, with access to OpenAI, Claude, Gemini, Ollama, Groq, and more.
* <b><code>&nbsp;10582⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;271🍴</code></b> [ast-grep](https://github.com/ast-grep/ast-grep)) - A CLI tool for code structural search, lint and rewriting.
* <b><code>&nbsp;&nbsp;&nbsp;769⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Bartib](https://github.com/nikolassv/bartib))  🌎 [Bartib](crates.io/crates/bartib)] - A simple timetracker for the command line [![Tests](https://github.com/nikolassv/bartib/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/nikolassv/bartib/actions/workflows/test.yml)
* <b><code>&nbsp;12192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;345🍴</code></b> [espanso](https://github.com/espanso/espanso)) - A cross-platform Text Expander. [![CI](https://github.com/espanso/espanso/actions/workflows/ci.yml/badge.svg?branch=dev&event=push)](https://github.com/espanso/espanso/actions/workflows/ci.yml)
* 🌎 [eureka](crates.io/crates/eureka) - A CLI tool to input and store your ideas without leaving the terminal
* <b><code>&nbsp;&nbsp;&nbsp;350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Furtherance](https://github.com/unobserved-io/Furtherance)) - Time tracking app built with GTK4
* <b><code>&nbsp;&nbsp;&nbsp;258⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [illacloud/illa](https://github.com/illacloud/illa)) - Low-code internal tool builder.
* <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [kruseio/hygg](https://github.com/kruseio/hygg))  🌎 [hygg](crates.io/crates/hygg)] - 📚 Simplifying the way you read. Minimalistic Vim-like TUI document reader.
* <b><code>&nbsp;&nbsp;5541⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;284🍴</code></b> [LLDAP](https://github.com/lldap/lldap)) - Simplified LDAP interface for authentication.
* <b><code>&nbsp;&nbsp;&nbsp;583⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [pier-cli/pier](https://github.com/pier-cli/pier)) - A central repository to manage (add, search metadata, etc.) all your one-liners, scripts, tools, and CLIs
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [ShadoySV/work-break](https://github.com/ShadoySV/work-break))  🌎 [work-break](crates.io/crates/work-break)] - Work and rest time balancer taking into account your current and today strain [![Build](https://github.com/ShadoySV/work-break/actions/workflows/release.yml/badge.svg)](https://github.com/ShadoySV/work-break/actions/workflows/release.yml)
* <b><code>&nbsp;&nbsp;&nbsp;240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [yashs662/rust_kanban](https://github.com/yashs662/rust_kanban))  🌎 [rust-kanban](crates.io/crates/rust-kanban)] [![Build](https://github.com/yashs662/rust_kanban/actions/workflows/build.yml/badge.svg)](https://github.com/yashs662/rust_kanban/releases) - A Kanban App for the terminal

### Routing protocols

* <b><code>&nbsp;&nbsp;&nbsp;416⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Holo](https://github.com/holo-routing/holo)) - Holo is a suite of routing protocols designed to support high-scale and automation-driven networks
* <b><code>&nbsp;&nbsp;&nbsp;538⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [RustyBGP](https://github.com/osrg/rustybgp)) - BGP

### Security tools

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [0xdea/augur](https://github.com/0xdea/augur))  🌎 [augur](crates.io/crates/augur)] - Reverse engineering assistant that extracts strings and related pseudo-code from a binary file [![build](https://github.com/0xdea/augur/actions/workflows/build.yml/badge.svg)](https://github.com/0xdea/augur/actions/workflows/build.yml)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [0xdea/haruspex](https://github.com/0xdea/haruspex))  🌎 [haruspex](crates.io/crates/haruspex)] - Vulnerability research assistant that extracts pseudo-code from the IDA Hex-Rays decompiler [![build](https://github.com/0xdea/haruspex/actions/workflows/build.yml/badge.svg)](https://github.com/0xdea/haruspex/actions/workflows/build.yml)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [0xdea/oneiromancer](https://github.com/0xdea/oneiromancer))  🌎 [oneiromancer](crates.io/crates/oneiromancer)] - Reverse engineering assistant that uses a locally running LLM to aid with source code analysis [![build](https://github.com/0xdea/oneiromancer/actions/workflows/build.yml/badge.svg)](https://github.com/0xdea/oneiromancer/actions/workflows/build.yml)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [0xdea/rhabdomancer](https://github.com/0xdea/rhabdomancer))  🌎 [rhabdomancer](crates.io/crates/rhabdomancer)] - Vulnerability research assistant that locates all calls to potentially insecure API functions in a binary file [![build](https://github.com/0xdea/rhabdomancer/actions/workflows/build.yml/badge.svg)](https://github.com/0xdea/rhabdomancer/actions/workflows/build.yml)
* <b><code>&nbsp;&nbsp;1265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [AdGuardian-Term](https://github.com/Lissy93/AdGuardian-Term))  🌎 [adguardian](crates.io/crates/adguardian)] - Terminal-based, real-time traffic monitoring and statistics for your AdGuard Home instance
* <b><code>&nbsp;&nbsp;2354⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;397🍴</code></b> [AFLplusplus/LibAFL](https://github.com/AFLplusplus/LibAFL)) - Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, etc. [![build and test](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml)
* <b><code>&nbsp;&nbsp;&nbsp;140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [arp-scan-rs](https://github.com/kongbytes/arp-scan-rs)) - A minimalistic ARP scan tool for fast local network scans
* 🌎 [cargo-audit](crates.io/crates/cargo-audit) - Audit Cargo.lock for crates with security vulnerabilities
* 🌎 [cargo-auditable](crates.io/crates/cargo-auditable) - Make production Rust binaries auditable
* 🌎 [cargo-crev](crates.io/crates/cargo-crev) - A cryptographically verifiable code review system for the cargo package manager.
* 🌎 [cargo-deny](crates.io/crates/cargo-deny) - Cargo plugin to help you manage large dependency graphs
* <b><code>&nbsp;&nbsp;1218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Cherrybomb](https://github.com/blst-security/cherrybomb)) - Stop half-done API specifications with a CLI tool that helps you avoid undefined user behaviour by validating your API specifications.
* <b><code>&nbsp;&nbsp;&nbsp;329⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [cotp](https://github.com/replydev/cotp)) - Trustworthy, encrypted, command-line TOTP/HOTP authenticator app with import functionality.
* <b><code>&nbsp;&nbsp;&nbsp;926⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [domcyrus/rustnet](https://github.com/domcyrus/rustnet)) - Cross-platform network monitoring TUI with process identification via eBPF/PKTAP and deep packet inspection [![build badge](https://img.shields.io/github/actions/workflow/status/domcyrus/rustnet/rust.yml?logo=github)](https://github.com/domcyrus/rustnet/actions/workflows/rust.yml) [![crate](https://img.shields.io/crates/v/rustnet-monitor?logo=rust)](https://crates.io/crates/rustnet-monitor)
* <b><code>&nbsp;&nbsp;&nbsp;117⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [entropic-security/xgadget](https://github.com/entropic-security/xgadget))  🌎 [xgadget](crates.io/crates/xgadget)] - Fast, parallel, cross-variant ROP/JOP gadget search [![GitHub Actions](https://github.com/entropic-security/xgadget/workflows/test/badge.svg)](https://github.com/entropic-security/xgadget/actions)
* <b><code>&nbsp;&nbsp;6991⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;552🍴</code></b> [epi052/feroxbuster](https://github.com/epi052/feroxbuster)) - A simple, fast, recursive content discovery tool.
* <b><code>&nbsp;&nbsp;&nbsp;283⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Inspektor](https://github.com/inspektor-dev/inspektor)) - A database protocol-aware proxy that is used to enforce access policies 👮
* <b><code>&nbsp;&nbsp;&nbsp;412⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [kpcyrd/authoscope](https://github.com/kpcyrd/authoscope)) - A scriptable network authentication cracker
* <b><code>&nbsp;&nbsp;&nbsp;524⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [kpcyrd/rshijack](https://github.com/kpcyrd/rshijack)) - A TCP connection hijacker; rewrite of shijack
* <b><code>&nbsp;&nbsp;2311⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;206🍴</code></b> [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int)) - A semi-automatic OSINT framework and package manager
* <b><code>&nbsp;&nbsp;1209⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue)) - A secure multithreaded packet sniffer
* <b><code>&nbsp;&nbsp;&nbsp;582⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [mongodb/kingfisher](https://github.com/mongodb/kingfisher)) - A blazingly fast tool for secret detection and live validation across files, Git repos, S3, Jira, and Confluence
* <b><code>&nbsp;&nbsp;1525⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;153🍴</code></b> [observer_ward](https://github.com/emo-crab/observer_ward)) - Web application and service fingerprint identification tool
* <b><code>&nbsp;&nbsp;&nbsp;201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Raspirus](https://github.com/Raspirus/Raspirus)) - User- and resources-friendly rules-based malware scanner [![status](https://github.com/Raspirus/Raspirus/actions/workflows/testproject.yml/badge.svg)](https://github.com/Raspirus/Raspirus/actions/workflows/testproject.yml)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [ripasso](https://github.com/cortex/ripasso/)) - A password manager, filesystem compatible with pass
* <b><code>&nbsp;18093⭐</code></b> <b><code>&nbsp;&nbsp;1201🍴</code></b> [rustscan](https://github.com/bee-san/RustScan)) - Make Nmap faster with this port scanning tool [![build badge](https://github.com/bee-san/RustScan/actions/workflows/test.yml/badge.svg)](https://github.com/bee-san/RustScan/actions)

### Social networks

* Mastodon
  * <b><code>&nbsp;&nbsp;&nbsp;883⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Rustodon](https://github.com/rustodon/rustodon)) - A Mastodon-compatible, ActivityPub-speaking server.
* Telegram
  * <b><code>&nbsp;&nbsp;&nbsp;702⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [tgt](https://github.com/FedericoBruzzone/tgt)) - A crossplatform TUI for Telegram [![ci-linux](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-linux.yml/badge.svg)](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-linux.yml) [![ci-macos](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-macos.yml/badge.svg)](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-macos.yml) [![ci-windows](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-windows.yml/badge.svg)](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-windows.yml)

### System tools

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide/)) - A fast alternative to `cd` that learns your habits [![release](https://github.com/ajeetdsouza/zoxide/actions/workflows/release.yml/badge.svg)](https://github.com/ajeetdsouza/zoxide/actions)
* <b><code>&nbsp;&nbsp;&nbsp;629⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [anylinuxfs](https://github.com/nohajc/anylinuxfs)) - CLI tool for mounting any linux-supported filesystem on a Mac - using NFS with a microVM
* <b><code>&nbsp;25913⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;705🍴</code></b> [atuin](https://github.com/atuinsh/atuin))  🌎 [atuin](crates.io/crates/atuin)] - Atuin replaces your existing shell history with a SQLite database, and records additional context for your commands. Additionally, it provides optional and fully encrypted synchronisation of your history between machines, via an Atuin server.
* <b><code>&nbsp;11097⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;324🍴</code></b> [bandwhich](https://github.com/imsnif/bandwhich)) - Terminal bandwidth utilization tool
* <b><code>&nbsp;11941⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;296🍴</code></b> [bottom](https://github.com/ClementTsang/bottom)) - Yet another cross-platform graphical process/system monitor. [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ClementTsang/bottom/ci/master)](https://github.com/ClementTsang/bottom/actions?query=branch%3Amaster)
* <b><code>&nbsp;&nbsp;&nbsp;517⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [brocode/fblog](https://github.com/brocode/fblog)) - Small command-line JSON Log viewer
* <b><code>&nbsp;&nbsp;1074⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [brush-shell](https://github.com/reubeno/brush)) - bash/POSIX-compatible shell [![CICD](https://github.com/reubeno/brush/actions/workflows/ci.yaml/badge.svg)](https://github.com/reubeno/brush/actions/workflows/ci.yaml)[![Crate](https://img.shields.io/crates/v/brush-shell.svg?logo=rust)](https://crates.io/crates/brush-shell)
* <b><code>&nbsp;&nbsp;&nbsp;232⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [bustd](https://github.com/vrmiguel/bustd)) - Lightweight process killer daemon to handle out-of-memory scenarios on Linux. [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/vrmiguel/bustd/build-and-test)](https://github.com/vrmiguel/bustd/actions?query=branch%3Amaster)
* <b><code>&nbsp;&nbsp;&nbsp;112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [buster/rrun](https://github.com/buster/rrun)) - A command launcher for Linux, similar to gmrun
* <b><code>&nbsp;&nbsp;7400⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;183🍴</code></b> [cantino/mcfly](https://github.com/cantino/mcfly)) - Fly through your shell history. Great Scott!
* <b><code>&nbsp;&nbsp;&nbsp;130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [ChurchTao/clipboard-rs](https://github.com/ChurchTao/clipboard-rs))  🌎 [clipboard-rs](crates.io/crates/clipboard-rs)] - Cross-platform library written in Rust for getting and setting and monitoring changes the system-level clipboard content.
* <b><code>&nbsp;&nbsp;&nbsp;356⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [crabz](https://github.com/sstadick/crabz)) - Multi-threaded compression and decompression CLI tool [![Build Status](https://github.com/sstadick/crabz/workflows/Check/badge.svg)](https://github.com/sstadick/crabz/actions?query=workflow%3ACheck)
* <b><code>&nbsp;&nbsp;&nbsp;283⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [cristianoliveira/funzzy](https://github.com/cristianoliveira/funzzy)) - A configurable filesystem watcher inspired by [entr](http://eradman.com/entrproject/)
* <b><code>&nbsp;&nbsp;5690⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [dalance/procs](https://github.com/dalance/procs)) - A modern replacement for 'ps' [![Regression](https://github.com/dalance/procs/actions/workflows/regression.yml/badge.svg)](https://github.com/dalance/procs/actions/workflows/regression.yml)
* <b><code>&nbsp;&nbsp;&nbsp;476⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [ddh](https://github.com/darakian/ddh)) - Fast duplicate file finder
* <b><code>&nbsp;&nbsp;2808⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [diskonaut](https://github.com/imsnif/diskonaut)) - Terminal visual disk space navigator
* <b><code>&nbsp;10521⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;235🍴</code></b> [dust](https://github.com/bootandy/dust)) - A more intuitive version of du
* <b><code>&nbsp;17496⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;321🍴</code></b> [eza-community/eza](https://github.com/eza-community/eza)) - A replacement for 'ls'
* <b><code>&nbsp;30987⭐</code></b> <b><code>&nbsp;&nbsp;2128🍴</code></b> [fish-shell/fish-shell](https://github.com/fish-shell/fish-shell)) - The user-friendly command line shell
* 🌎 [fselect](crates.io/crates/fselect) - Find files with SQL-like queries
* <b><code>&nbsp;20576⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;649🍴</code></b> [gitui](https://github.com/gitui-org/gitui)) - Blazing fast terminal client for git. [![build](https://github.com/gitui-org/gitui/actions/workflows/ci.yml/badge.svg)](https://github.com/gitui-org/gitui/actions)
* <b><code>&nbsp;&nbsp;3448⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [GQL](https://github.com/amrdeveloper/gql)) - A SQL like query language to run on .git files.
* <b><code>&nbsp;&nbsp;1543⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [httm](https://github.com/kimono-koans/httm)) - Interactive, file-level Time Machine-like tool for ZFS/btrfs/nilfs2 (and even actual Time Machine backups!)
* <b><code>&nbsp;&nbsp;&nbsp;452⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [j0ru/kickoff](https://github.com/j0ru/kickoff)) - Fast and snappy wayland program launcher [![build](https://github.com/j0ru/kickoff/actions/workflows/ci.yml/badge.svg)](https://github.com/j0ru/kickoff/actions)
* <b><code>&nbsp;&nbsp;&nbsp;337⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [jacek-kurlit/pik](https://github.com/jacek-kurlit/pik))  🌎 [pik](crates.io/crates/pik)] - A TUI command line tool that helps to find and kill processes
* <b><code>&nbsp;&nbsp;2105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Kondo](https://github.com/tbillington/kondo)) - CLI & GUI tool for deleting software project artifacts and reclaiming disk space
* <b><code>&nbsp;&nbsp;3041⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [LACT](https://github.com/ilya-zlobintsev/LACT)) - Linux AMDGPU Controller
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [lodosgroup/lpm](https://github.com/lodosgroup/lpm)) - An experimental system package manager
* <b><code>&nbsp;&nbsp;&nbsp;550⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [lotabout/rargs](https://github.com/lotabout/rargs))  🌎 [rargs](crates.io/crates/rargs)] - xargs + awk with pattern matching support
* <b><code>&nbsp;14879⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;466🍴</code></b> [lsd](https://github.com/lsd-rs/lsd)) - An ls with a lot of pretty colors and awesome icons [![build](https://github.com/lsd-rs/lsd/actions/workflows/CICD.yml/badge.svg)](https://github.com/lsd-rs/lsd/actions)
* <b><code>&nbsp;&nbsp;&nbsp;854⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Luminarys/synapse](https://github.com/Luminarys/synapse)) - Flexible and fast BitTorrent daemon.
* <b><code>&nbsp;&nbsp;1747⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [m4b/bingrep](https://github.com/m4b/bingrep)) - Greps through binaries from various OSs and architectures, and colors them.
* <b><code>&nbsp;&nbsp;&nbsp;715⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [matheus-git/systemd-manager-tui](https://github.com/matheus-git/systemd-manager-tui))  🌎 [systemd-manager-tui](crates.io/crates/systemd-manager-tui)] - A program for managing systemd services through a TUI (Terminal User Interfaces).
* <b><code>&nbsp;&nbsp;&nbsp;637⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [mdgaziur/findex](https://github.com/mdgaziur/findex)) - Findex is a highly customizable application finder using GTK3
* <b><code>&nbsp;&nbsp;&nbsp;996⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [mitnk/cicada](https://github.com/mitnk/cicada)) - A bash-like Unix shell
* <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [mmstick/concurr](https://github.com/mmstick/concurr)) - Alternative to GNU Parallel w/ a client-server architecture
* <b><code>&nbsp;&nbsp;&nbsp;275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [mmstick/fontfinder](https://github.com/mmstick/fontfinder)) - GTK3 application for previewing and installing Google's fonts
* <b><code>&nbsp;&nbsp;&nbsp;149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [mmstick/tv-renamer](https://github.com/mmstick/tv-renamer)) - A tv series renaming application with an optional GTK3 frontend.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [mxseev/logram](https://github.com/mxseev/logram)) - Push log files' updates to Telegram
* <b><code>&nbsp;&nbsp;1386⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [netscanner](https://github.com/Chleba/netscanner)) - TUI Network Scanner
* <b><code>&nbsp;&nbsp;&nbsp;364⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [nickgerace/gfold](https://github.com/nickgerace/gfold))  🌎 [gfold](crates.io/crates/gfold)] - CLI tool to help keep track of multiple Git repositories [![build](https://img.shields.io/github/workflow/status/nickgerace/gfold/merge/main)](https://github.com/nickgerace/gfold/actions?query=workflow%3Amerge+branch%3Amain)
* <b><code>&nbsp;&nbsp;1598⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [nivekuil/rip](https://github.com/nivekuil/rip)) - A safe and ergonomic alternative to `rm`
* <b><code>&nbsp;36522⭐</code></b> <b><code>&nbsp;&nbsp;1937🍴</code></b> [nushell/nushell](https://github.com/nushell/nushell)) - A new type of shell
* <b><code>&nbsp;&nbsp;&nbsp;341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp)) - Terraform MCP Tool - CLI for AI assistants to manage Terraform environments via Model Context Protocol.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [nwiizo/tfocus](https://github.com/nwiizo/tfocus)) - Interactive tool for selecting and executing Terraform plan/apply operations
* <b><code>&nbsp;&nbsp;2784⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [orhun/kmon](https://github.com/orhun/kmon)) - Linux Kernel Manager and Activity Monitor ![https://github.com/orhun/kmon/actions](https://img.shields.io/github/actions/workflow/status/orhun/kmon/ci.yml?branch=master&label=build)
* <b><code>&nbsp;&nbsp;1391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [orhun/systeroid](https://github.com/orhun/systeroid)) - A more powerful alternative to sysctl(8) with a terminal user interface ![https://github.com/orhun/systeroid/actions](https://img.shields.io/github/actions/workflow/status/orhun/systeroid/ci.yml?branch=main&label=build)
* <b><code>&nbsp;&nbsp;3183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [ouch](https://github.com/ouch-org/ouch)) - Painless compression and decompression on the command-line [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ouch-org/ouch/build-and-test)](https://github.com/ouch-org/ouch/actions?query=branch%3Amaster)
* <b><code>&nbsp;&nbsp;2456⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [pkolaczk/fclones](https://github.com/pkolaczk/fclones)) - Efficient duplicate file finder and remover
* <b><code>&nbsp;&nbsp;&nbsp;753⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [pop-os/popsicle](https://github.com/pop-os/popsicle)) - GTK3 & CLI utility for flashing multiple USB devices in parallel
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [pop-os/system76-power](https://github.com/pop-os/system76-power/)) - Linux power management daemon (DBus-interface) with CLI tool.
* <b><code>&nbsp;&nbsp;5842⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;139🍴</code></b> [pueue](https://github.com/nukesor/pueue)) - Manage your long running shell commands. [![GitHub Actions Workflow](https://github.com/Nukesor/pueue/actions/workflows/test.yml/badge.svg)](https://github.com/nukesor/pueue/actions)
* <b><code>&nbsp;26372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;836🍴</code></b> [qarmin/czkawka](https://github.com/qarmin/czkawka)) - Multi-functional app to find duplicates, empty folders, similar images, etc. [![GitHub Actions Workflow](https://github.com/qarmin/czkawka/actions/workflows/pages/pages-build-deployment/badge.svg?branch=master)](https://github.com/qarmin/czkawka/actions)
* <b><code>&nbsp;&nbsp;1529⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [redox-os/ion](https://github.com/redox-os/ion)) - Next-generation system shell
* <b><code>&nbsp;54617⭐</code></b> <b><code>&nbsp;&nbsp;1354🍴</code></b> [sharkdp/bat](https://github.com/sharkdp/bat)) - A cat(1) clone with wings. [![CICD](https://github.com/sharkdp/bat/actions/workflows/CICD.yml/badge.svg?branch=master)](https://github.com/sharkdp/bat/actions/workflows/CICD.yml)
* <b><code>&nbsp;39823⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;926🍴</code></b> [sharkdp/fd](https://github.com/sharkdp/fd)) - A simple, fast and user-friendly alternative to find. [![CICD](https://github.com/sharkdp/fd/actions/workflows/CICD.yml/badge.svg)](https://github.com/sharkdp/fd/actions/workflows/CICD.yml)
* <b><code>&nbsp;&nbsp;&nbsp;549⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [sitkevij/hex](https://github.com/sitkevij/hex)) - A colorized hexdump terminal utility.
* <b><code>&nbsp;&nbsp;6012⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;219🍴</code></b> [skim](https://github.com/skim-rs/skim)) - A fuzzy finder
* <b><code>&nbsp;&nbsp;&nbsp;457⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [supercilex/fuc](https://github.com/supercilex/fuc)) - Fast `cp` and `rm` commands
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [topheman/webassembly-component-model-experiments](https://github.com/topheman/webassembly-component-model-experiments)) - WebAssembly Component Model based REPL with sandboxed multi-language plugin system [![Crates.io](https://img.shields.io/crates/v/pluginlab.svg)](https://crates.io/crates/pluginlab)
* <b><code>&nbsp;&nbsp;6087⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;177🍴</code></b> [trippy](https://github.com/fujiapple852/trippy)) - A network diagnostic tool [![build badge](https://github.com/fujiapple852/trippy/workflows/CI/badge.svg)](https://github.com/fujiapple852/trippy/actions/workflows/ci.yml)
* <b><code>&nbsp;21663⭐</code></b> <b><code>&nbsp;&nbsp;1580🍴</code></b> [uutils/coreutils](https://github.com/uutils/coreutils)) - A cross-platform rewrite of the GNU coreutils [![CICD](https://github.com/uutils/coreutils/actions/workflows/CICD.yml/badge.svg)](https://github.com/uutils/coreutils/actions/workflows/CICD.yml)
* <b><code>&nbsp;&nbsp;6370⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;168🍴</code></b> [watchexec](https://github.com/watchexec/watchexec)) - Executes commands in response to file modifications
* <b><code>&nbsp;13228⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;607🍴</code></b> [XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei)) - counts the lines of code
* <b><code>&nbsp;&nbsp;5644⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [ynqa/jnv](https://github.com/ynqa/jnv)) - Interactive JSON filter using jq [![ci](https://github.com/ynqa/jnv/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ynqa/jnv/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;&nbsp;112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [ynqa/logu](https://github.com/ynqa/logu)) - Extract patterns from (streaming) unstructured log messages [![ci](https://github.com/ynqa/logu/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ynqa/logu/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;&nbsp;670⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [ynqa/sig](https://github.com/ynqa/sig)) - Interactive grep (for streaming) [![ci](https://github.com/ynqa/sig/actions/workflows/ci.yml/badge.svg)](https://github.com/ynqa/sig/actions/workflows/ci.yml)

### Task scheduling

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [tasklet](https://github.com/stav121/tasklet))  🌎 [tasklet](crates.io/crates/tasklet)] - A task scheduling library written in Rust ![Build Status](https://img.shields.io/github/actions/workflow/status/stav121/tasklet/rust.yml)

### Text editors

* 🌎 [amp](amp.rs) - Inspired by Vi/Vim.
* <b><code>&nbsp;&nbsp;1774⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [emacs-ng](https://github.com/emacs-ng/emacs-ng)) - Complementing the C codebase with rust code to introduce new features.
* <b><code>&nbsp;&nbsp;1655⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [gchp/iota](https://github.com/gchp/iota)) - A simple text editor
* <b><code>&nbsp;40040⭐</code></b> <b><code>&nbsp;&nbsp;3050🍴</code></b> [helix](https://github.com/helix-editor/helix)) - A post-modern modal text editor inspired by Neovim/Kakoune. [![build badge](https://github.com/helix-editor/helix/actions/workflows/build.yml/badge.svg)](https://github.com/helix-editor/helix/actions)
* <b><code>&nbsp;&nbsp;1760⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [ilai-deutel/kibi](https://github.com/ilai-deutel/kibi)) - A tiny (≤1024 LOC) text editor with syntax highlighting, incremental search and more. [![build badge](https://github.com/ilai-deutel/kibi/actions/workflows/ci.yml/badge.svg)](https://github.com/ilai-deutel/kibi/actions?query=branch%3Amaster)
* <b><code>&nbsp;37382⭐</code></b> <b><code>&nbsp;&nbsp;1186🍴</code></b> [Lapce](https://github.com/lapce/lapce)) - A modern editor with a backend. Taking inspiration from the discontinued <b><code>&nbsp;19838⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;703🍴</code></b> [xi-editor](https://github.com/xi-editor/xi-editor)).
* <b><code>&nbsp;&nbsp;&nbsp;624⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [mathall/rim](https://github.com/mathall/rim)) - Vim-like text editor.
* <b><code>&nbsp;&nbsp;3605⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [ox](https://github.com/curlpipe/ox)) - An independent Rust text editor that runs in your terminal!
* 🌎 [vamolessa/pepper](git.sr.ht/~lessa/pepper)  🌎 [pepper](crates.io/crates/pepper)] - An opinionated modal editor to simplify code editing from the terminal
* <b><code>&nbsp;66314⭐</code></b> <b><code>&nbsp;&nbsp;5400🍴</code></b> [zed](https://github.com/zed-industries/zed)) - A high-performance, multiplayer code editor from the creators of Atom and Tree-sitter.

### Text processing

* <b><code>&nbsp;&nbsp;2831⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [ashvardanian/stringzilla](https://github.com/ashvardanian/StringZilla)) - SIMD-accelerated string search, sort, edit distances, alignments, and generators for x86 AVX2 & AVX-512, and Arm NEON [![crates.io](https://img.shields.io/crates/v/stringzilla.svg)](https://crates.io/crates/stringzilla)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [cchexcode/complate](https://github.com/cchexcode/complate)) - An in-terminal text templating tool designed for standardizing messages (like for GIT commits). [![crates.io](https://img.shields.io/crates/v/complate.svg)](https://crates.io/crates/complate) [![crates.io](https://img.shields.io/crates/d/complate?label=crates.io%20downloads)](https://crates.io/crates/complate) [![build badge](https://github.com/cchexcode/complate/actions/workflows/release.yml/badge.svg)](https://github.com/cchexcode/complate/actions)
* <b><code>&nbsp;&nbsp;3195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [dathere/qsv](https://github.com/dathere/qsv))  🌎 [qsv](crates.io/crates/qsv)] - A high performance CSV data-wrangling toolkit. Forked from xsv, with 34+ additional commands & more. [![Linux build status](https://github.com/dathere/qsv/actions/workflows/rust.yml/badge.svg)](https://github.com/dathere/qsv/actions/workflows/rust.yml) [![Windows build status](https://github.com/dathere/qsv/actions/workflows/rust-windows.yml/badge.svg)](https://github.com/dathere/qsv/actions/workflows/rust-windows.yml) [![macOS build status](https://github.com/dathere/qsv/actions/workflows/rust-macos.yml/badge.svg)](https://github.com/dathere/qsv/actions/workflows/rust-macos.yml)
* <b><code>&nbsp;&nbsp;1746⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [dominikwilkowski/cfonts](https://github.com/dominikwilkowski/cfonts))  🌎 [cfonts](crates.io/crates/cfonts)] - Sexy ANSI fonts for the console ![build badge](https://github.com/dominikwilkowski/cfonts/actions/workflows/testing.yml/badge.svg)
* <b><code>&nbsp;&nbsp;7606⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [grex](https://github.com/pemistahl/grex)) - A command-line tool and library for generating regular expressions from user-provided test cases
* <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Lisprez/so_stupid_search](https://github.com/Lisprez/so_stupid_search)) - A simple and fast string search tool for human beings
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [loki_text](https://github.com/roquess/loki_text))  🌎 [loki_text](crates.io/crates/loki_text)] - String manipulation library with pattern searching, text transformation, and multiple string search algorithms (KMP, Boyer-Moore, Aho-Corasick, etc.)
* <b><code>&nbsp;&nbsp;4703⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Melody](https://github.com/yoav-lavi/melody)) - A language that compiles to regular expressions and aims to be more easily readable and maintainable [![build badge](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml/badge.svg)](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml) [![crates.io](https://img.shields.io/crates/v/melody_compiler?label=compiler)](https://crates.io/crates/melody_compiler)
* <b><code>&nbsp;&nbsp;9119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;196🍴</code></b> [phiresky/ripgrep-all](https://github.com/phiresky/ripgrep-all)) - ripgrep, but also search in PDFs, E-Books, Office documents, zip, tar.gz, etc.
* 🌎 [ripgrep](crates.io/crates/ripgrep) - combines the usability of The Silver Searcher with the raw speed of grep
* <b><code>&nbsp;&nbsp;&nbsp;487⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [ruplacer](https://github.com/your-tools/ruplacer)) - Find and replace text in source files [![Run tests](https://github.com/your-tools/ruplacer/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/your-tools/ruplacer/actions/workflows/test.yml)
* <b><code>&nbsp;&nbsp;&nbsp;930⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [scooter](https://github.com/thomasschafer/scooter)) - Interactive find and replace in the terminal.
* 🌎 [sd](crates.io/crates/sd) - Intuitive find & replace CLI
* <b><code>&nbsp;&nbsp;&nbsp;723⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [sstadick/hck](https://github.com/sstadick/hck)) - A faster and more featureful drop in replacement for `cut` [![build badge](https://github.com/sstadick/hck/workflows/Check/badge.svg?branch=master)](https://github.com/sstadick/hck)
* <b><code>&nbsp;&nbsp;&nbsp;339⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [vishaltelangre/ff](https://github.com/vishaltelangre/ff)) - Find files (ff) by name!
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [whitfin/bytelines](https://github.com/whitfin/bytelines))  🌎 [bytelines](crates.io/crates/bytelines)] - Read input lines as byte slices for high efficiency.
* <b><code>&nbsp;&nbsp;&nbsp;218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [whitfin/runiq](https://github.com/whitfin/runiq)) - an efficient way to filter duplicate lines from unsorted input.
* 🌎 [xsv](crates.io/crates/xsv) - A fast CSV command line tool (slicing, indexing, selecting, searching, sampling, etc.)

### Utilities

* <b><code>&nbsp;&nbsp;&nbsp;512⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [1History](https://github.com/1History/1History)) - Command line interface to backup Firefox/Chrome/Safari history to one SQLite file [![Build Status](https://github.com/1History/1History/actions/workflows/CI.yml/badge.svg)](https://github.com/1History/1History/actions/workflows/CI.yml)
* <b><code>&nbsp;&nbsp;&nbsp;369⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [bloznelis/kbt](https://github.com/bloznelis/kbt))  🌎 [kbt](crates.io/crates/kbt)] - A simple TUI tool for keyboard testing.
* <b><code>&nbsp;&nbsp;&nbsp;130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [brycx/checkpwn](https://github.com/brycx/checkpwn)) - A Have I Been Pwned (HIBP) command-line utility tool that lets you easily check for compromised accounts and passwords.
* <b><code>&nbsp;&nbsp;&nbsp;287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [cartesiancs/vessel](https://github.com/cartesiancs/vessel)) - C2 (Command & Control) software for orchestrating physical devices.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [dcapal](https://github.com/dcapal/dcapal)) - DcaPal is a free, no registration, online tool to help you keep your portfolio balanced with dollar cost averaging investments.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Eoin-McMahon/Blindfold](https://github.com/Eoin-McMahon/Blindfold))  🌎 [Blindfold](crates.io/crates/blindfold)] - A simple CLI tool for generating `.gitignore` files quickly and easily. [![build-badge](https://github.com/Eoin-McMahon/blindfold/actions/workflows/rust.yml/badge.svg)](<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [https://github.com/nix-community/nurl/actions/workflows/ci.yml](https://github.com/Eoin-McMahon/blindfold/actions/workflows/rust.yml)))
* <b><code>&nbsp;&nbsp;&nbsp;463⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Epic Asset Manager](https://github.com/AchetaGames/Epic-Asset-Manager)) - An unofficial client to install Unreal Engine, download and manage purchased assets, projects, plugins and games from the Epic Games Store.
* <b><code>&nbsp;&nbsp;&nbsp;299⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [evansmurithi/cloak](https://github.com/evansmurithi/cloak)) - A Command Line OTP (One Time Password) Authenticator application. ![CI](https://github.com/evansmurithi/cloak/workflows/CI/badge.svg) [![build badge](https://ci.appveyor.com/api/projects/status/9mlfpfru3ng4c689/branch/master?svg=true)](https://ci.appveyor.com/project/evansmurithi/cloak)
* <b><code>&nbsp;&nbsp;&nbsp;987⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [fcsonline/tmux-thumbs](https://github.com/fcsonline/tmux-thumbs)) - A lightning fast version of tmux-fingers, copy/pasting tmux like vimium/vimperator.
* <b><code>&nbsp;&nbsp;&nbsp;373⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [guoxbin/dtool](https://github.com/guoxbin/dtool)) - A useful command-line tool collection to assist development including conversion, codec, hashing, encryption, etc.
* <b><code>&nbsp;&nbsp;&nbsp;374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Linus-Mussmaecher/rucola](https://github.com/Linus-Mussmaecher/rucola)) - Terminal-based markdown note manager. [![Crate](https://img.shields.io/crates/v/rucola-notes.svg?logo=rust)](https://crates.io/crates/rucola-notes) [![Build Status](https://github.com/Linus-Mussmaecher/rucola/actions/workflows/continuous-testing.yml/badge.svg)](https://github.com/Linus-Mussmaecher/rucola/actions/workflows/continuous-testing.yml)
* <b><code>&nbsp;&nbsp;&nbsp;389⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Mobslide](https://github.com/thewh1teagle/mobslide)) - Desktop application that turns your smartphone into presentation remote controller.
* <b><code>&nbsp;&nbsp;2022⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [mprocs](https://github.com/pvolok/mprocs)) - TUI for running multiple processes
* <b><code>&nbsp;&nbsp;1144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [mrjackwills/oxker](https://github.com/mrjackwills/oxker))  🌎 [oxker](crates.io/crates/oxker)] - A simple tui to view & control docker containers.
* <b><code>&nbsp;&nbsp;1159⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [nix-community/nix-init](https://github.com/nix-community/nix-init)) - Generate Nix packages from URLs with hash prefetching, dependency inference, license detection, and more [![build-badge](https://github.com/nix-community/nix-init/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-init/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;&nbsp;281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [nix-community/nix-melt](https://github.com/nix-community/nix-melt)) - A ranger-like flake.lock viewer [![build-badge](https://github.com/nix-community/nix-melt/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-melt/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;&nbsp;610⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [nix-community/nurl](https://github.com/nix-community/nurl))  🌎 [nurl](crates.io/crates/nurl)] - Generate Nix fetcher calls from repository URLs [![build-badge](https://github.com/nix-community/nurl/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nurl/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;&nbsp;684⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [nomino](https://github.com/yaa110/nomino)) - Batch rename utility for developers
* <b><code>&nbsp;&nbsp;&nbsp;200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [raftario/licensor](https://github.com/raftario/licensor)) - write licenses to stdout [![GitHub Actions](https://github.com/raftario/licensor/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/raftario/licensor/actions/workflows/build.yml)
* <b><code>&nbsp;&nbsp;&nbsp;239⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [restsend/rustpbx](https://github.com/restsend/rustpbx)) - Software-Defined SIP Proxy including register, presence, b2bua. alternative to Freeswitch/FreePBX.
* <b><code>&nbsp;&nbsp;&nbsp;238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [rust-parallel](https://github.com/aaronriekenberg/rust-parallel)) - Fast command line app using Tokio to execute commands in parallel.  Similar interface to GNU Parallel or xargs. [![Crate](https://img.shields.io/crates/v/rust-parallel.svg?logo=rust)](https://crates.io/crates/rust-parallel) [![Build Status](https://github.com/aaronriekenberg/rust-parallel/actions/workflows/CI.yml/badge.svg)](https://github.com/aaronriekenberg/rust-parallel/actions/workflows/CI.yml)
* <b><code>&nbsp;98858⭐</code></b> <b><code>&nbsp;14537🍴</code></b> [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk)) - A remote desktop software, great alternative to TeamViewer and AnyDesk.
* <b><code>&nbsp;&nbsp;2606⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [rustic-rs/rustic](https://github.com/rustic-rs/rustic))  🌎 [rustic-rs](crates.io/crates/rustic-rs)] - Fast, encrypted, deduplicated backups powered by Rust. [![Version](https://img.shields.io/crates/v/rustic-rs.svg)](https://crates.io/crates/rustic-rs)
* <b><code>&nbsp;&nbsp;&nbsp;218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [sorairolake/qrtool](https://github.com/sorairolake/qrtool))  🌎 [qrtool](crates.io/crates/qrtool)] - A utility for encoding and decoding QR code images. [![CI](https://github.com/sorairolake/qrtool/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/qrtool/actions?query=workflow%3ACI)
* <b><code>&nbsp;&nbsp;3094⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [str4d/rage](https://github.com/str4d/rage))  🌎 [rage](crates.io/crates/rage)] - Rust implementation of <b><code>&nbsp;19767⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;575🍴</code></b> [age](https://github.com/FiloSottile/age)).
* <b><code>&nbsp;&nbsp;&nbsp;789⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [suckit](https://github.com/Skallwar/suckit)) - Recursively visit and download a website's content to your disk. [![Crate](https://img.shields.io/crates/v/suckit.svg?logo=rust)](https://crates.io/crates/suckit) [![Build Status](https://github.com/Skallwar/suckit/workflows/Build%20and%20test/badge.svg)](https://github.com/Skallwar/suckit/blob/master/.github/workflows/build_and_test.yml)
* <b><code>&nbsp;&nbsp;2416⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Tabiew](https://github.com/shshemi/tabiew)) - A lightweight TUI app to view and query CSV files.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Tail Tales](https://github.com/davidmoreno/tailtales)) - A TUI log viewer with logfmt support. [![Crate](https://img.shields.io/crates/v/tailtales.svg?logo=rust)](https://crates.io/crates/tailtales)
* <b><code>&nbsp;&nbsp;3420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [television](https://github.com/alexpasmantier/television)) - A blazing fast general purpose fuzzy finder TUI ![GitHub branch check runs](https://img.shields.io/github/check-runs/alexpasmantier/television/main)
* <b><code>&nbsp;&nbsp;&nbsp;278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [tversteeg/emplace](https://github.com/tversteeg/emplace)) - Synchronize installed packages on multiple machines
* <b><code>&nbsp;&nbsp;&nbsp;224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [vamolessa/verco](https://github.com/vamolessa/verco))  🌎 [verco](crates.io/crates/verco)] - A simple Git/Hg tui client focused on keyboard shortcuts
* <b><code>&nbsp;49290⭐</code></b> <b><code>&nbsp;&nbsp;2311🍴</code></b> [vaultwarden](https://github.com/dani-garcia/vaultwarden#readme)) [![Build](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml/badge.svg)](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml) - Alternative implementation of the Bitwarden server API written in Rust
* <b><code>&nbsp;&nbsp;4189⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Vibe](https://github.com/thewh1teagle/vibe)) - Transcribe audio or video in every language on every platform.
* <b><code>&nbsp;24893⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;554🍴</code></b> [warpdotdev/Warp](https://github.com/warpdotdev/Warp)) - :heavy_dollar_sign: Warp is a blazingly-fast modern GPU-accelerated terminal built to make you and your team more productive.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [wrestic](https://github.com/alvaro17f/wrestic)) - A wrapper around restic.
* <b><code>&nbsp;&nbsp;&nbsp;455⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [wthrr](https://github.com/ttytm/wthrr-the-weathercrab)) - Weather companion for the terminal. [![crates.io](https://img.shields.io/crates/v/wthrr?logo=rust)](https://crates.io/crates/wthrr)

### Video

* <b><code>&nbsp;&nbsp;&nbsp;301⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [dertuxmalwieder/yaydl](https://github.com/dertuxmalwieder/yaydl))  🌎 [yaydl](crates.io/crates/yaydl)] - A simple video downloader
* <b><code>&nbsp;&nbsp;7819⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;359🍴</code></b> [gyroflow/gyroflow](https://github.com/gyroflow/gyroflow)) - Video stabilization application using gyroscope data
* <b><code>&nbsp;&nbsp;2173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;225🍴</code></b> [harlanc/xiu](https://github.com/harlanc/xiu)) - A powerful and secure live server (rtmp/httpflv/hls/relay). [![crates.io](https://img.shields.io/crates/v/xiu.svg)](https://crates.io/crates/xiu)
* <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [vidmerger](https://github.com/TGotwig/vidmerger)) - Merge video & audio files via CLI
* <b><code>&nbsp;&nbsp;3972⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;273🍴</code></b> [xiph/rav1e](https://github.com/xiph/rav1e)) - The fastest and safest AV1 encoder.

### Virtualization

* <b><code>&nbsp;30575⭐</code></b> <b><code>&nbsp;&nbsp;2092🍴</code></b> [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker)) - A lightweight virtual machine for container workload 🌎 [Firecracker Microvm](firecracker-microvm.github.io/)
* <b><code>&nbsp;&nbsp;6777⭐</code></b> <b><code>&nbsp;&nbsp;1175🍴</code></b> [kata-containers/kata-containers](https://github.com/kata-containers/kata-containers)) - A implementation of lightweight Virtual Machines (VMs) that feel and perform like containers, but provide the workload isolation and security advantages of VMs.
* <b><code>&nbsp;&nbsp;1888⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [tailhook/vagga](https://github.com/tailhook/vagga)) - A containerization tool without daemons
* <b><code>&nbsp;&nbsp;6951⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;380🍴</code></b> [youki-dev/youki](https://github.com/youki-dev/youki)) - A container runtime [![build badge](https://github.com/youki-dev/youki/actions/workflows/basic.yml/badge.svg)](https://github.com/youki-dev/youki/actions)

### Web

* <b><code>&nbsp;&nbsp;&nbsp;234⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [cfal/tobaru](https://github.com/cfal/tobaru)) - Port forwarder with allowlists, IP and TLS SNI/ALPN rule-based routing, iptables support, round-robin forwarding (load balancing), and hot reloading.
* <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [importantimport/hatsu](https://github.com/importantimport/hatsu)) - 🩵 Self-hosted and fully-automated ActivityPub bridge for static sites. [![release](https://github.com/importantimport/hatsu/actions/workflows/release.yml/badge.svg)](https://github.com/importantimport/hatsu/actions/workflows/release.yml)
* <b><code>&nbsp;14052⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;932🍴</code></b> [LemmyNet/lemmy](https://github.com/LemmyNet/lemmy)) - A link aggregator / reddit clone for the fediverse [![Build Status](https://cloud.drone.io/api/badges/LemmyNet/lemmy/status.svg)](https://cloud.drone.io/LemmyNet/lemmy)
* <b><code>&nbsp;&nbsp;&nbsp;192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [MASQ-Project/Node](https://github.com/MASQ-Project/Node)) - MASQ Node software provides a decentralized mesh-network of nodes for global users to access normal internet content - next evolution of tech beyond Tor & VPN [![build badge](https://github.com/MASQ-Project/Node/actions/workflows/ci-matrix.yml/badge.svg)](https://github.com/MASQ-Project/Node/actions)
* <b><code>&nbsp;&nbsp;2179⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Plume-org/Plume](https://github.com/Plume-org/Plume)) - ActivityPub federating blogging application
* <b><code>&nbsp;&nbsp;2608⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;175🍴</code></b> [Redlib](https://github.com/redlib-org/redlib)) - An alternative private front-end to Reddit, with its origins in <b><code>&nbsp;&nbsp;5134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;265🍴</code></b> [Libreddit](https://github.com/libreddit/libreddit))
* <b><code>&nbsp;&nbsp;1661⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [Revolt/backend](https://github.com/revoltchat/backend)) - User-first chat platform built with modern web technologies.

### Web Servers

* <b><code>&nbsp;25111⭐</code></b> <b><code>&nbsp;&nbsp;1470🍴</code></b> [cloudflare/pingora](https://github.com/cloudflare/pingora)) - A library for building fast, reliable and evolvable network services.
* <b><code>&nbsp;&nbsp;&nbsp;445⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [emanuele-em/proxelar](https://github.com/emanuele-em/proxelar)) - A MITM Proxy 🦀! Toolkit for HTTP/1, HTTP/2, and WebSockets with SSL/TLS Capabilities [![Rust](https://github.com/emanuele-em/proxelar/actions/workflows/autofix.yml/badge.svg)](https://github.com/emanuele-em/proxelar/actions)
* <b><code>&nbsp;&nbsp;&nbsp;756⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [g3proxy](https://github.com/bytedance/g3)) - Forward proxy server, support Proxy Chaining, Protocol Inspection, MITM Interception, ICAP Adaptation, Transparent Proxy [![CodeCoverage](https://github.com/bytedance/g3/actions/workflows/codecov.yml/badge.svg)](https://github.com/bytedance/g3/actions)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Mini RPS](https://github.com/marcodpt/minirps)) - Mini reverse proxy server, HTTPS, CORS, static file hosting and template engine (minijinja) 🌎 [crates.io](crates.io/crates/minirps)
* <b><code>&nbsp;&nbsp;&nbsp;153⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [mu-arch/skyfolder](https://github.com/mu-arch/skyfolder)) - 🪂 Beautiful HTTP/Bittorrent server without the hassle. Secure - GUI - Pretty - Fast
* <b><code>&nbsp;&nbsp;1098⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [mufeedvh/binserve](https://github.com/mufeedvh/binserve)) - A blazingly fast static web server with routing, templating, and security in a single binary you can set up with zero code [![build badge](https://github.com/mufeedvh/binserve/actions/workflows/build.yml/badge.svg)](https://github.com/mufeedvh/binserve/actions)
* <b><code>&nbsp;&nbsp;&nbsp;972⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [orhun/rustypaste](https://github.com/orhun/rustypaste)) - A minimal file upload/pastebin service ![https://github.com/orhun/rustypaste/actions](https://img.shields.io/github/actions/workflow/status/orhun/rustypaste/ci.yml?branch=master&label=build)
* <b><code>&nbsp;&nbsp;&nbsp;774⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [plabayo/rama](https://github.com/plabayo/rama)) - A modular service framework to move and transform your network packets, used to build web clients, servers and — above all — proxies
* <b><code>&nbsp;&nbsp;&nbsp;140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [ronanyeah/rust-hasura](https://github.com/ronanyeah/rust-hasura)) - A demonstration of how a GraphQL server can be used as a remote schema with 🌎 [Hasura](hasura.io/) ![Rust](https://github.com/ronanyeah/rust-hasura/workflows/Rust/badge.svg?branch=master)
* <b><code>&nbsp;&nbsp;1951⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [static-web-server](https://github.com/static-web-server/static-web-server)) - A blazing fast and asynchronous web server for static files-serving. ⚡ [![CI](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml/badge.svg)](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml?query=branch%3Amaster)
* <b><code>&nbsp;&nbsp;7049⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;346🍴</code></b> [svenstaro/miniserve](https://github.com/svenstaro/miniserve)) - A small, self-contained cross-platform CLI tool that allows you to just grab the binary and serve some file(s) via HTTP [![build badge](https://github.com/svenstaro/miniserve/workflows/CI/badge.svg?branch=master)](https://github.com/svenstaro/miniserve/actions)
* <b><code>&nbsp;&nbsp;&nbsp;474⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [thecoshman/http](https://github.com/thecoshman/http)) - Host These Things Please - A basic http server for hosting a folder fast and simply
* <b><code>&nbsp;&nbsp;3304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [TheWaWaR/simple-http-server](https://github.com/TheWaWaR/simple-http-server)) - simple static http server
* <b><code>&nbsp;&nbsp;&nbsp;262⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [vproxy/0x676e67](https://github.com/0x676e67/vproxy)) - An fast asynchronous Rust HTTP/Socks5 Proxy

## Development tools

* <b><code>&nbsp;&nbsp;3047⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [ATAC](https://github.com/Julien-cpsn/ATAC)) - A feature-full TUI API client made in Rust. ATAC is free, open-source, offline and account-less.
* <b><code>&nbsp;&nbsp;2795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [bacon](https://github.com/Canop/bacon)) - background rust code checker, similar to cargo-watch
* 🌎 [clippy](crates.io/crates/clippy) - Rust lints
* <b><code>&nbsp;&nbsp;&nbsp;896⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [clog-tool/clog-cli](https://github.com/clog-tool/clog-cli)) - generates a changelog from git metadata  🌎 [conventional changelog](blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html))
* <b><code>&nbsp;&nbsp;1455⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [cloudflare/foundations](https://github.com/cloudflare/foundations)) - Foundations is a modular Rust library, designed to help scale programs for distributed, production-grade systems.
* <b><code>&nbsp;&nbsp;&nbsp;574⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [comtrya](https://github.com/comtrya/comtrya)) - A configuration management tool for localhost / dotfiles [![build badge](https://github.com/comtrya/comtrya/actions/workflows/main.yaml/badge.svg)](https://github.com/comtrya/comtrya/actions)
* <b><code>&nbsp;&nbsp;1592⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [create-rust-app](https://github.com/Wulf/create-rust-app)) - Set up a modern rust+react web app by running one command. [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/create-rust-app)
* <b><code>&nbsp;&nbsp;&nbsp;422⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [dan-t/rusty-tags](https://github.com/dan-t/rusty-tags)) - create ctags/etags for a cargo project and all of its dependencies
* <b><code>&nbsp;&nbsp;&nbsp;548⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [datanymizer/datanymizer](https://github.com/datanymizer/datanymizer)) - Powerful database anonymizer with flexible rules [![build badge](https://github.com/datanymizer/datanymizer/workflows/CI/badge.svg?branch=main)](https://github.com/datanymizer/datanymizer/actions?query=workflow%3ACI+branch%3Amain)
* 🌎 [delta](crates.io/crates/git-delta) - A syntax-highlighter for git and diff output[![build badge](https://github.com/dandavison/delta/actions/workflows/ci.yml/badge.svg)](https://github.com/dandavison/delta//actions)
* <b><code>&nbsp;&nbsp;1990⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [dotenv-linter](https://github.com/dotenv-linter/dotenv-linter)) - Linter for `.env` files [![build badge](https://github.com/dotenv-linter/dotenv-linter/actions/workflows/ci.yml/badge.svg)](https://github.com/dotenv-linter/dotenv-linter/actions?query=workflow%3ACI+branch%3Amaster)
* <b><code>&nbsp;&nbsp;&nbsp;895⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [envio-cli/envio](https://github.com/envio-cli/envio)) - A Modern And Secure CLI Tool For Managing Environment Variables [![build badge](https://github.com/envio-cli/envio/actions/workflows/CICD.yml/badge.svg?branch=main)](https://github.com/envio-cli/envio/actions/workflows/CICD.yml)
* <b><code>&nbsp;&nbsp;3469⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [Flox](https://github.com/flox/flox)) - Flox is a virtual environment and package manager all in one.
* <b><code>&nbsp;&nbsp;4504⭐</code></b> <b><code>&nbsp;&nbsp;1191🍴</code></b> [Forge](https://github.com/antinomyhq/forge)) - A terminal-based AI pair programmer for code generation and editing. [![Website](https://img.shields.io/badge/website-forgecode.dev-blue)](https://forgecode.dev/)
* <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [frolic](https://github.com/frolicflow/Frolic)) - An API layer to build customer facing dashboards 10x faster
* <b><code>&nbsp;&nbsp;&nbsp;560⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [fw](https://github.com/brocode/fw)) - workspace productivity booster [![Rust](https://github.com/brocode/fw/actions/workflows/rust.yml/badge.svg)](https://github.com/brocode/fw/actions/workflows/rust.yml)
* <b><code>&nbsp;&nbsp;&nbsp;185⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [fzf-make](https://github.com/kyu08/fzf-make))  🌎 [fzf-make](crates.io/crates/fzf-make)] - A command line tool that executes make target using fuzzy finder with preview window. [![crates.io](https://img.shields.io/crates/v/fzf-make?style=flatflat-square)](https://crates.io/crates/fzf-make)
* <b><code>&nbsp;&nbsp;1523⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [geiger](https://github.com/geiger-rs/cargo-geiger)) - A program that list statistics related to usage of unsafe code in a crate and all its dependencies [![Build Status](https://dev.azure.com/cargo-geiger/cargo-geiger/_apis/build/status/geiger-rs.cargo-geiger?branchName=master)](https://dev.azure.com/cargo-geiger/cargo-geiger/_build/latest?definitionId=1&branchName=master)
* <b><code>&nbsp;10829⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;249🍴</code></b> [git-cliff](https://github.com/orhun/git-cliff)) - A highly customizable Changelog Generator that follows Conventional Commit specifications ![https://github.com/orhun/git-cliff/actions](https://img.shields.io/github/actions/workflow/status/orhun/git-cliff/ci.yml?branch=main&label=build)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [git-journal](https://github.com/saschagrunert/git-journal/)) - The Git Commit Message and Changelog Generation Framework
* <b><code>&nbsp;&nbsp;&nbsp;707⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [hot-lib-reloader](https://github.com/rksm/hot-lib-reloader-rs)) - Hot reload Rust code [![build badge](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;&nbsp;546⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [intelli-shell](https://github.com/lasantosr/intelli-shell)) - Bookmark commands with placeholders and search or autocomplete at any time [![crate](https://img.shields.io/crates/v/intelli-shell.svg)](https://crates.io/crates/intelli-shell) [![build badge](https://github.com/lasantosr/intelli-shell/actions/workflows/release.yml/badge.svg)](https://github.com/lasantosr/intelli-shell/actions/workflows/release.yml)
* <b><code>&nbsp;27825⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;587🍴</code></b> [just](https://github.com/casey/just)) - A handy command runner for project-specific tasks
* <b><code>&nbsp;&nbsp;1470⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [mask](https://github.com/jacobdeichert/mask)) - A CLI task runner defined by a simple markdown file [![build badge](https://github.com/jacobdeichert/mask/workflows/CI/badge.svg?branch=master)](https://github.com/jacobdeichert/mask/actions?query=workflow%3ACI)
* <b><code>&nbsp;&nbsp;&nbsp;253⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Module Linker](https://github.com/fiatjaf/module-linker)) - Extension that adds `<a>` links to references in `mod`, `use` and `extern crate` statements at GitHub.
* <b><code>&nbsp;&nbsp;&nbsp;137⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [ptags](https://github.com/dalance/ptags)) - A parallel universal-ctags wrapper for git repository
* <b><code>&nbsp;&nbsp;3361⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;278🍴</code></b> [Racer](https://github.com/racer-rust/racer)) - code completion for Rust
* <b><code>&nbsp;&nbsp;1260⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Rust Search Extension](https://github.com/huhu/rust-search-extension)) - A handy browser extension to search crates and docs in address bar (omnibox). [![Build Status](https://github.com/huhu/rust-search-extension/workflows/build/badge.svg?branch=master)](https://github.com/huhu/rust-search-extension/actions)
* <b><code>&nbsp;&nbsp;6612⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;977🍴</code></b> [Rustup](https://github.com/rust-lang/rustup)) - the Rust toolchain installer [![build badge](https://github.com/rust-lang/rustup/actions/workflows/ci.yaml/badge.svg)](https://github.com/rust-lang/rustup/actions)
* <b><code>&nbsp;&nbsp;1047⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [scriptisto](https://github.com/igor-petruk/scriptisto)) - A language-agnostic "shebang interpreter" that enables you to write one file scripts in compiled languages. [![Build Status](https://cloud.drone.io/api/badges/igor-petruk/scriptisto/status.svg)](https://cloud.drone.io/igor-petruk/scriptisto)
* <b><code>&nbsp;&nbsp;3465⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [typos](https://github.com/crate-ci/typos))  🌎 [typos-cli](crates.io/crates/typos-cli)] - Source code spell checker
* 🌎 [VT Code](crates.io/crates/vtcode) - Terminal coding agent that pairs a modern TUI with deep, semantic code understanding powered by tree-sitter and ast-grep.

### Build system

* 🌎 [Cargo](crates.io/) - the Rust package manager
  * <b><code>&nbsp;&nbsp;&nbsp;165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [cargo-all-features](https://github.com/frewsxcv/cargo-all-features)) - A configurable subcommand to simplify testing, building and much more for all combinations of features [![CI](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml/badge.svg)](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml)
  * 🌎 [cargo-benchcmp](crates.io/crates/cargo-benchcmp) - A utility to compare micro-benchmarks
  * 🌎 [cargo-bitbake](crates.io/crates/cargo-bitbake) - A cargo extension that can generate BitBake recipes utilizing the classes from meta-rust
  * 🌎 [cargo-cache](crates.io/crates/cargo-cache) - inspect/manage/clean your cargo cache (`~/.cargo/`/`${CARGO_HOME}`), print sizes etc [![Build Status](https://github.com/matthiaskrgr/cargo-cache/workflows/ci/badge.svg?branch=master)](https://github.com/matthiaskrgr/cargo-cache/actions)
  * 🌎 [cargo-check](crates.io/crates/cargo-check) - A wrapper around `cargo rustc -- -Zno-trans` which can be helpful for running a faster compile if you only need correctness checks
  * 🌎 [cargo-commander](crates.io/crates/cargo-commander) - A subcommand for `cargo` to run CLI commands similar to how the scripts section in `package.json` works [![Build and test](https://github.com/simonhyll/cargo-commander/actions/workflows/build.yml/badge.svg)](https://github.com/simonhyll/cargo-commander/actions/workflows/build.yml)
  * 🌎 [cargo-count](crates.io/crates/cargo-count) - lists source code counts and details about cargo projects, including unsafe statistics
  * 🌎 [cargo-deb](crates.io/crates/cargo-deb) - Generates binary Debian packages
  * 🌎 [cargo-depgraph](crates.io/crates/cargo-depgraph) - Creates dependency graphs for cargo projects using cargo metadata and graphviz
  * 🌎 [cargo-do](crates.io/crates/cargo-do) - run multiple cargo commands in a row
  * 🌎 [cargo-ebuild](crates.io/crates/cargo-ebuild) - cargo extension that can generate ebuilds using the in-tree eclasses
  * 🌎 [cargo-edit](crates.io/crates/cargo-edit) - allows you to add and list dependencies by reading/writing to your Cargo.toml file from the command line
  * <b><code>&nbsp;&nbsp;2272⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [cargo-generate](https://github.com/cargo-generate/cargo-generate)) - A generator of a rust project by leveraging a pre-existing git repository as a template.
  * 🌎 [cargo-info](crates.io/crates/cargo-info) - queries crates.io for crates details from command line
  * 🌎 [cargo-license](crates.io/crates/cargo-license) - A cargo subcommand to quickly view the licenses of all dependencies.
  * 🌎 [cargo-limit](crates.io/crates/cargo-limit) - Cargo with less noise: warnings are skipped until errors are fixed, Neovim integration, etc. [![build badge](https://github.com/cargo-limit/cargo-limit/actions/workflows/ci.yml/badge.svg)](https://github.com/cargo-limit/cargo-limit/actions)
  * 🌎 [cargo-make](crates.io/crates/cargo-make) - Task runner and build tool. [![build badge](https://github.com/sagiegurari/cargo-make/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cargo-make/actions)
  * 🌎 [cargo-modules](crates.io/crates/cargo-modules) - A cargo plugin for showing a tree-like overview of a crate's modules.
  * 🌎 [cargo-multi](crates.io/crates/cargo-multi) - runs specified cargo command on multiple crates
  * 🌎 [cargo-outdated](crates.io/crates/cargo-outdated) - displays when newer versions of Rust dependencies are available, or out of date
  * <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [cargo-rdme](https://github.com/orium/cargo-rdme))  🌎 [cargo-rdme](crates.io/crates/cargo-rdme)] - Cargo subcommand to create your README from your crate’s documentation. [![build badge](https://github.com/orium/cargo-rdme/workflows/CI/badge.svg)](https://github.com/orium/cargo-rdme/actions?query=workflow%3ACI)
  * 🌎 [cargo-release](crates.io/crates/cargo-release) - tool for releasing git-managed cargo project, build, tag, publish, doc and push [![Rust](https://github.com/crate-ci/cargo-release/actions/workflows/ci.yml/badge.svg)](https://github.com/crate-ci/cargo-release/actions/workflows/rust.yml)
  * 🌎 [cargo-script](crates.io/crates/cargo-script) - lets people quickly and easily run Rust "scripts" which can make use of Cargo's package ecosystem
  * <b><code>&nbsp;&nbsp;2006⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [cargo-udeps](https://github.com/est31/cargo-udeps))  🌎 [cargo-udeps](crates.io/crates/cargo-udeps)] - find unused dependencies
  * 🌎 [cargo-update](crates.io/crates/cargo-update) - cargo subcommand for checking and applying updates to installed executables
  * 🌎 [cargo-watch](crates.io/crates/cargo-watch) - utility for cargo to compile projects when sources change
  * <b><code>&nbsp;&nbsp;2933⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand)) - Expand macros in your source code
* CMake
  * <b><code>&nbsp;&nbsp;&nbsp;172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Devolutions/CMakeRust](https://github.com/Devolutions/CMakeRust)) - useful for integrating a Rust library into a CMake project
  * <b><code>&nbsp;&nbsp;&nbsp;110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [SiegeLord/RustCMake](https://github.com/SiegeLord/RustCMake)) - an example project showing usage of CMake with Rust
* <b><code>&nbsp;&nbsp;4084⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;297🍴</code></b> [facebook/buck2](https://github.com/facebook/buck2)) - 🌎 [Buck2](buck2.build/) is a large-scale build tool built in Rust
* <b><code>&nbsp;&nbsp;2421⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Fleet](https://github.com/suptejas/fleet))  🌎 [fleet-rs](crates.io/crates/fleet-rs)] - The blazing fast build tool for Rust.
* GitHub actions
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [icepuma/rust-action](https://github.com/icepuma/rust-action)) - rust github action
  * <b><code>&nbsp;&nbsp;&nbsp;316⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [peaceiris/actions-mdbook](https://github.com/peaceiris/actions-mdbook)) - GitHub Actions for mdBook
* 🌎 [Nix](nixos.org/)
  * <b><code>&nbsp;&nbsp;&nbsp;897⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [nix-community/fenix](https://github.com/nix-community/fenix)) - Rust toolchains and rust analyzer nightly for nix [![build-badge](https://github.com/nix-community/fenix/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/fenix/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;3627⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;671🍴</code></b> [pantsbuild/pants](https://github.com/pantsbuild/pants)) - 🌎 [Pants](www.pantsbuild.org/) is a fast, scalable, user-friendly build system for codebases of all sizes built in Rust.
* <b><code>&nbsp;&nbsp;1429⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [tracemachina/nativelink](https://github.com/TraceMachina/nativelink)) - 🌎 [NativeLink](www.nativelink.com) is a Backend Remote Execution platform written in rust for client build systems such as 🌎 [Buck2](buck2.build/), 🌎 [Bazel](bazel.build/), 🌎 [Pants](www.pantsbuild.org/), etc.. [![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/TraceMachina/nativelink/badge)](https://securityscorecards.dev/viewer/?uri=github.com/TraceMachina/nativelink) [![OpenSSF Best Practices](https://www.bestpractices.dev/projects/8050/badge)](https://www.bestpractices.dev/projects/8050) [![Slack](https://img.shields.io/badge/slack--channel-blue?logo=slack)](https://nativelink.slack.com/join/shared_invite/zt-281qk1ho0-krT7HfTUIYfQMdwflRuq7A#/shared-invite/email)

### Debugging

* GDB
  * <b><code>&nbsp;10169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;518🍴</code></b> [gdbgui](https://github.com/cs01/gdbgui)) - Browser based frontend for gdb to debug C, C++, Rust, and go.
* <b><code>&nbsp;&nbsp;1166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [godzie44/BugStalker](https://github.com/godzie44/BugStalker)) - Modern debugger for Linux x86-64. Written in Rust for Rust programs.
* <b><code>&nbsp;&nbsp;&nbsp;406⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [kxxt/tracexec](https://github.com/kxxt/tracexec))  🌎 [tracexec](crates.io/crates/tracexec)] - Tracer for execve{,at} and pre-exec behavior, launcher for debuggers.
* LLDB
  * 🌎 [CodeLLDB](marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) - A LLDB extension for 🌎 [Visual Studio Code](code.visualstudio.com/).

### Deployment

* Docker
  * <b><code>&nbsp;&nbsp;1574⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;195🍴</code></b> [emk/rust-musl-builder](https://github.com/emk/rust-musl-builder)) - Docker images for compiling static Rust binaries using musl-libc and musl-gcc, with static versions of useful C libraries
  * <b><code>&nbsp;&nbsp;&nbsp;235⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [kpcyrd/mini-docker-rust](https://github.com/kpcyrd/mini-docker-rust)) - An example project for very small rust docker images
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [liuchong/docker-rustup](https://github.com/liuchong/docker-rustup)) - A multiple version (with musl tools) Rust Docker image
  * <b><code>&nbsp;&nbsp;2292⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [LukeMathWalker/cargo-chef](https://github.com/LukeMathWalker/cargo-chef)) - A tool and pre-built images for caching compiling remote dependencies between Docker builds.
  * <b><code>&nbsp;&nbsp;&nbsp;711⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [rust-cross/rust-musl-cross](https://github.com/rust-cross/rust-musl-cross)) - Docker images for compiling static Rust binaries using musl-cross [![Build](https://github.com/rust-cross/rust-musl-cross/workflows/Build/badge.svg)](https://github.com/rust-cross/rust-musl-cross/actions?query=workflow%3ABuild)
  * <b><code>&nbsp;&nbsp;&nbsp;498⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [rust-lang-nursery/docker-rust](https://github.com/rust-lang/docker-rust)) - the official Rust Docker image
  * <b><code>&nbsp;&nbsp;&nbsp;137⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Stavrospanakakis/is_ready](https://github.com/Stavrospanakakis/is_ready)) - Wait for multiple services to become available ![Build](https://github.com/Stavrospanakakis/is_ready/actions/workflows/release.yml/badge.svg)
* Heroku
  * <b><code>&nbsp;&nbsp;&nbsp;523⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;190🍴</code></b> [emk/heroku-buildpack-rust](https://github.com/emk/heroku-buildpack-rust)) - A buildpack for Rust applications on Heroku
* <b><code>&nbsp;&nbsp;1187⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [release-plz](https://github.com/release-plz/release-plz))  🌎 [release-plz](crates.io/crates/release-plz)] - Release crates from CI, with changelog generation and semver check. [![build badge](https://github.com/release-plz/release-plz/workflows/CI/badge.svg)](https://github.com/release-plz/release-plz/actions)

### Embedded
 🌎 [Rust Embedded](rust-embedded.org/) focuses on improving the end-to-end experience of using Rust in resource-constrained environments and non-traditional platforms. See <b><code>&nbsp;&nbsp;7336⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;433🍴</code></b> [awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust)) for a curated, and more extended list of embedded Rust resources.

* Arduino
  * <b><code>&nbsp;&nbsp;&nbsp;727⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [avr-rust/ruduino](https://github.com/avr-rust/ruduino)) - Reusable components for the Arduino Uno.
* Cross compiling
  * <b><code>&nbsp;&nbsp;2555⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [japaric/rust-cross](https://github.com/japaric/rust-cross)) - everything you need to know about cross compiling Rust programs
  * <b><code>&nbsp;&nbsp;1122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [japaric/xargo](https://github.com/japaric/xargo)) - effortless cross compilation of Rust programs to custom bare-metal targets like ARM Cortex-M
* Espressif
  * [esp-rs](https://github.com/esp-rs) - home to a number of community projects enabling the use of the Rust programming language on various SoCs and modules produced by Espressif Systems.
* Firmware
  * <b><code>&nbsp;&nbsp;1716⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [oreboot/oreboot](https://github.com/oreboot/oreboot)) - oreboot is a fork of coreboot, with C removed, written in Rust
* nRF
  * <b><code>&nbsp;&nbsp;&nbsp;557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;147🍴</code></b> [nrf-rs/nrf-hal](https://github.com/nrf-rs/nrf-hal)) - A Rust HAL for the nRF family of devices

### FFI

See also 🌎 [Foreign Function Interface](doc.rust-lang.org/book/first-edition/ffi.html), [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/) (a collection of examples of using code written in Rust from other languages) and <b><code>&nbsp;&nbsp;1251⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [FFI examples written in Rust](https://github.com/alexcrichton/rust-ffi-examples)).

* C
  * <b><code>&nbsp;&nbsp;2721⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;353🍴</code></b> [mozilla/cbindgen](https://github.com/mozilla/cbindgen)) - generates C header files from Rust source files. Used in Gecko for WebRender
  * <b><code>&nbsp;&nbsp;&nbsp;188⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Sean1708/rusty-cheddar](https://github.com/Sean1708/rusty-cheddar)) - generates C header files from Rust source files
* C#
  * <b><code>&nbsp;&nbsp;&nbsp;813⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [csbindgen](https://github.com/Cysharp/csbindgen)) - generates C# bindings for Rust source files
* C++
  * <b><code>&nbsp;&nbsp;6481⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;384🍴</code></b> [dtolnay/cxx](https://github.com/dtolnay/cxx)) - Safe interop between Rust and C++ [![build badge](https://img.shields.io/badge/github-dtolnay/cxx-8da0cb?style=for-the-badge&labelColor=555555&logo=github)](https://github.com/dtolnay/cxx)
  * 🌎 [rust-cpp](crates.io/crates/cpp) - Embed C++ code directly in Rust. [![Build status](https://ci.appveyor.com/api/projects/status/uu76vmcrwnjqra0u/branch/master?svg=true)](https://ci.appveyor.com/project/mystor/rust-cpp/branch/master)
  * <b><code>&nbsp;&nbsp;4961⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;767🍴</code></b> [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen)) - A Rust bindings generator
* Erlang
  * <b><code>&nbsp;&nbsp;4619⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;231🍴</code></b> [rusterlium/rustler](https://github.com/rusterlium/rustler)) - safe Rust bridge for creating Erlang NIF functions
* Java
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [bennettanderson/rjni](https://github.com/benanders/rjni)) - use Java from Rust
  * <b><code>&nbsp;&nbsp;&nbsp;341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [drrb/java-rust-example](https://github.com/drrb/java-rust-example)) - use Rust from Java
  * 🌎 [j4rs](crates.io/crates/j4rs) - use Java from Rust
  * 🌎 [jni](crates.io/crates/jni) - use Rust from Java
  * 🌎 [jni-sys](crates.io/crates/jni-sys) - Rust definitions corresponding to jni.h
  * 🌎 [rucaja](crates.io/crates/rucaja) - use Java from Rust
* Lua
  * <b><code>&nbsp;&nbsp;&nbsp;159⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [jcmoyer/rust-lua53](https://github.com/jcmoyer/rust-lua53)) - Lua 5.3 bindings for Rust
  * <b><code>&nbsp;&nbsp;&nbsp;129⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [lilyball/rust-lua](https://github.com/lilyball/rust-lua)) - Safe Rust bindings to Lua 5.1
  * <b><code>&nbsp;&nbsp;2361⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [mlua-rs/mlua](https://github.com/mlua-rs/mlua)) - High level Lua 5.4/5.3/5.2/5.1 (including LuaJIT) and Roblox Luau bindings to Rust with async/await support [![build badge](https://github.com/mlua-rs/mlua/workflows/CI/badge.svg)](https://github.com/mlua-rs/mlua/actions)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [tickbh/td_rlua](https://github.com/tickbh/td_rlua))  🌎 [td_rlua](crates.io/crates/td_rlua)] - Zero-cost high-level lua 5.3 wrapper for Rust
  * <b><code>&nbsp;&nbsp;&nbsp;515⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [tomaka/hlua](https://github.com/tomaka/hlua)) - Rust library to interface with Lua
* mruby
  * <b><code>&nbsp;&nbsp;&nbsp;204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [anima-engine/mrusty](https://github.com/anima-engine/mrusty)) - mruby safe bindings for Rust
* Node.js
  * <b><code>&nbsp;&nbsp;&nbsp;581⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [infinyon/node-bindgen](https://github.com/infinyon/node-bindgen)) - Easy way to generate nodejs module using Rust
  * <b><code>&nbsp;&nbsp;8329⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;289🍴</code></b> [neon-bindings/neon](https://github.com/neon-bindings/neon)) - Rust bindings for writing safe and fast native Node.js modules
  * <b><code>&nbsp;&nbsp;&nbsp;293⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [zhangyuang/node-ffi-rs](https://github.com/zhangyuang/node-ffi-rs)) - A module written in Rust and N-API provides interface (FFI) features for Node.js
* Objective-C
  * <b><code>&nbsp;&nbsp;&nbsp;402⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc)) - Objective-C Runtime bindings and wrapper for Rust
* PHP
  * <b><code>&nbsp;&nbsp;&nbsp;328⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [phper-framework/phper](https://github.com/phper-framework/phper)) - The framework that allows us to write PHP extensions using pure and safe Rust whenever possible
* Prolog
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [mthom/scryer-prolog](https://github.com/mthom/scryer-prolog/)) - Scryer Prolog is a free software ISO Prolog system written in Rust
* Python
  * <b><code>&nbsp;&nbsp;1825⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;135🍴</code></b> [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython)) - Python bindings
  * <b><code>&nbsp;&nbsp;&nbsp;796⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [getsentry/milksnake](https://github.com/getsentry/milksnake)) - extension for python setuptools that allows you to distribute dynamic linked libraries in Python wheels in the most portable way imaginable.
  * <b><code>&nbsp;14455⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;877🍴</code></b> [PyO3/PyO3](https://github.com/PyO3/PyO3)) - Rust bindings for the Python interpreter
  * <b><code>&nbsp;20552⭐</code></b> <b><code>&nbsp;&nbsp;1348🍴</code></b> [RustPython](https://github.com/RustPython/RustPython)) - A Python Interpreter written in Rust [![Build Status](https://github.com/RustPython/RustPython/workflows/CI/badge.svg)](https://github.com/RustPython/RustPython/actions?query=workflow%3ACI)
* Ruby
  * <b><code>&nbsp;&nbsp;&nbsp;832⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [d-unsed/ruru](https://github.com/d-unsed/ruru)) - native Ruby extensions written in Rust
  * <b><code>&nbsp;&nbsp;&nbsp;988⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [danielpclark/rutie](https://github.com/danielpclark/rutie)) - native Ruby extensions written in Rust and vice versa
* Web Assembly
  * <b><code>&nbsp;&nbsp;&nbsp;451⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [rhysd/wain](https://github.com/rhysd/wain)) - wain: WebAssembly INterpreter from scratch in Safe Rust with zero dependency [![build badge](https://github.com/rhysd/wain/workflows/CI/badge.svg?branch=master&event=push)](https://github.com/rhysd/wain/actions?query=workflow%3ACI+branch%3Amaster+event%3Apush)
  * <b><code>&nbsp;&nbsp;8501⭐</code></b> <b><code>&nbsp;&nbsp;1151🍴</code></b> [wasm-bindgen](https://github.com/wasm-bindgen/wasm-bindgen)) - A project for facilitating high-level interactions between wasm modules and JS.
  * <b><code>&nbsp;&nbsp;6858⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;457🍴</code></b> [wasm-pack](https://github.com/drager/wasm-pack)) - :package: :sparkles: pack up the wasm and publish it to npm!

### Formatters

* <b><code>&nbsp;&nbsp;3609⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [dprint](https://github.com/dprint/dprint)) - A pluggable and configurable code formatting platform [![build badge](https://github.com/dprint/dprint/workflows/CI/badge.svg)](https://github.com/dprint/dprint/actions?query=workflow%3ACI)
* <b><code>&nbsp;&nbsp;&nbsp;195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Prettier Rust](https://github.com/jinxdash/prettier-plugin-rust)) - An opinionated Rust code formatter that autofixes bad syntax  🌎 [Prettier](prettier.io/) community plugin)
* <b><code>&nbsp;&nbsp;6445⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;947🍴</code></b> [rustfmt](https://github.com/rust-lang/rustfmt)) - Rust code formatter maintained by the Rust team and included in cargo

### IDEs

See also 🌎 [Are we (I)DE yet?](areweideyet.com/) and 🌎 [Rust Tools](www.rust-lang.org/tools).

  * 🌎 [Eclipse](www.eclipse.org/)
    * <b><code>&nbsp;&nbsp;&nbsp;237⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Eclipse Corrosion](https://github.com/eclipse-corrosion/corrosion)) - a Rust development plugin for the Eclipse IDE, providing a rich edition experience through integration with the Rust Analyzer language server, Cargo runner and gdb debugger
  * 🌎 [Emacs](www.gnu.org/software/emacs/)
    * <b><code>&nbsp;&nbsp;&nbsp;398⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [emacs-racer](https://github.com/racer-rust/emacs-racer)) - Autocompletion (see also 🌎 [company](company-mode.github.io) and <b><code>&nbsp;&nbsp;1757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;284🍴</code></b> [auto-complete](https://github.com/auto-complete/auto-complete)))
    * <b><code>&nbsp;&nbsp;&nbsp;123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [flycheck-rust](https://github.com/flycheck/flycheck-rust)) - Rust support for <b><code>&nbsp;&nbsp;2486⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;454🍴</code></b> [Flycheck](https://github.com/flycheck/flycheck))
    * <b><code>&nbsp;&nbsp;1195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;190🍴</code></b> [rust-mode](https://github.com/rust-lang/rust-mode)) - Rust Major Mode
    * <b><code>&nbsp;&nbsp;&nbsp;737⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [rustic](https://github.com/brotzeit/rustic)) - Rust development environment for Emacs [![build badge](https://github.com/brotzeit/rustic/workflows/CI/badge.svg)](https://github.com/brotzeit/rustic/actions?query=workflow%3ACI)
  * 🌎 [gitpod.io](gitpod.io) - Online IDE with full Rust support based on Rust Language Server
  * 🌎 [gnome-builder](wiki.gnome.org/Apps/Builder) - native support for rust and cargo since Version 3.22.2
  * 🌎 [IntelliJ](www.jetbrains.com/idea/)
    * <b><code>&nbsp;&nbsp;4544⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;385🍴</code></b> [intellij-rust/intellij-rust](https://github.com/intellij-rust/intellij-rust)) - Rust plugin for the IntelliJ Platform
  * [Kakoune](http://kakoune.org/)
    * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [kakoune-lsp](https://github.com/kakoune-lsp/kakoune-lsp/)) - 🌎 [LSP](microsoft.github.io/language-server-protocol/) client. Implemented in Rust and supports rls out of the box.
  * <b><code>&nbsp;37382⭐</code></b> <b><code>&nbsp;&nbsp;1186🍴</code></b> [lapce](https://github.com/lapce/lapce)) - Lightning-fast and Powerful Code Editor written in Rust. [![build badge](https://github.com/lapce/lapce/actions/workflows/release.yml/badge.svg)](https://github.com/lapce/lapce/actions/workflows/release.yml)
  * <b><code>&nbsp;&nbsp;&nbsp;175⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Ride](https://github.com/madeso/ride)) - A Rust IDE
  * 🌎 [RustRover](www.jetbrains.com/rust/) - A powerful Rust IDE by JetBrains, free for individual non-commercial use
  * 🌎 [Sublime Text](www.sublimetext.com/)
    * <b><code>&nbsp;&nbsp;&nbsp;806⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [rust-lang/rust-enhanced](https://github.com/rust-lang/rust-enhanced)) - official Rust package
  * 🌎 [Vim](vim.sourceforge.io/) - the ubiquitous text editor
    * <b><code>&nbsp;&nbsp;3558⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;273🍴</code></b> [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim)) - 🌎 [LSP](microsoft.github.io/language-server-protocol/) client. Implemented in Rust and supports rls out of the box.
    * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [cargo.nvim](https://github.com/nwiizo/cargo.nvim)) - A Neovim plugin for seamless integration with Cargo commands.
    * <b><code>&nbsp;&nbsp;1029⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [crates.nvim](https://github.com/Saecki/crates.nvim)) - plugin that helps to managing crates.io dependencies.
    * <b><code>&nbsp;&nbsp;4055⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [rust.vim](https://github.com/rust-lang/rust.vim)) - provides file detection, syntax highlighting, formatting, Syntastic integration, and more.
    * <b><code>&nbsp;&nbsp;&nbsp;631⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [vim-racer](https://github.com/racer-rust/vim-racer)) - allows vim to use <b><code>&nbsp;&nbsp;3361⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;278🍴</code></b> [Racer](https://github.com/racer-rust/racer)) for Rust code completion and navigation.
  * Visual Studio
    * <b><code>&nbsp;&nbsp;&nbsp;109⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [dgriffen/rls-vs2017](https://github.com/ZoeyR/rls-vs2017)) - Rust support for Visual Studio 2017 Preview [![build badge](https://ci.appveyor.com/api/projects/status/d2lxlincwninhsng?svg=true)](https://ci.appveyor.com/project/dgriffen/rls-vs2017)
    * <b><code>&nbsp;&nbsp;&nbsp;704⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [PistonDevelopers/VisualRust](https://github.com/PistonDevelopers/VisualRust)) - A Visual Studio extension for Rust [![Build status](https://ci.appveyor.com/api/projects/status/5nw5no10jj0y4p3f?svg=true)](https://ci.appveyor.com/project/vosen/visualrust)
  * 🌎 [Visual Studio Code](code.visualstudio.com/)
    * 🌎 [CodeLLDB](marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) - A LLDB extension
    * 🌎 [Dependi](marketplace.visualstudio.com/items?itemName=fill-labs.dependi) - Manage your dependencies with ease
    * 🌎 [Even Better TOML](marketplace.visualstudio.com/items?itemName=tamasfe.even-better-toml) - TOML support in vscode
    * 🌎 [Prettier - Code formatter (Rust)](marketplace.visualstudio.com/items?itemName=jinxdash.prettier-rust) - Opinionated Rust code formatter that autofixes bad syntax  🌎 [Prettier](prettier.io/) community plugin)
    * 🌎 [rust-analyzer](marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) - An alternative rust language server to the RLS

### Profiling

* <b><code>&nbsp;&nbsp;&nbsp;746⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Bencher](https://github.com/bencherdev/bencher)) - A suite of continuous benchmarking tools designed to catch performance regressions in CI
* <b><code>&nbsp;&nbsp;5250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;346🍴</code></b> [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs)) - Statistics-driven benchmarking library
* <b><code>&nbsp;&nbsp;4699⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [Bytehound](https://github.com/koute/bytehound)) - A memory profiler for Linux
* <b><code>&nbsp;&nbsp;1227⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Divan](https://github.com/nvzqz/divan)) - Simple yet powerful benchmarking library with allocation profiling
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [ellisonch/rust-stopwatch](https://github.com/ellisonch/rust-stopwatch)) - A stopwatch library
* FlameGraphs
  * <b><code>&nbsp;&nbsp;&nbsp;723⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [llogiq/flame](https://github.com/llogiq/flame)) - An intrusive flamegraph profiling tool for rust
  * <b><code>&nbsp;&nbsp;&nbsp;133⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [mrhooray/torch](https://github.com/mrhooray/torch)) - generates FlameGraphs based on DWARF Debug Info
* <b><code>&nbsp;&nbsp;&nbsp;756⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [g3bench](https://github.com/bytedance/g3)) - A benchmark tool that supports HTTP 1.x, HTTP 2, HTTP 3, TLS Handshake, DNS and Cloudflare Keyless
* <b><code>&nbsp;26240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;424🍴</code></b> [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine)) - A command-line benchmarking tool

### Services

* <b><code>&nbsp;&nbsp;&nbsp;481⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [deps.rs](https://github.com/deps-rs/deps.rs)) - Detect outdated or insecure dependencies
* 🌎 [docs.rs](docs.rs) - Automatic documentation generation of crates

### Static analysis

 🌎 [assert](crates.io/keywords/assert), 🌎 [static](crates.io/keywords/static)]

* <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [MIRAI](https://github.com/endorlabs/mirai)) - an abstract interpreter operating on Rust's mid-level intermediate representation (MIR) [![Continuous Integration](https://github.com/endorlabs/mirai/actions/workflows/rust.yml/badge.svg)](https://github.com/endorlabs/mirai/actions/workflows/rust.yml)
* <b><code>&nbsp;&nbsp;&nbsp;111⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [RAPx](https://github.com/Artisan-Lab/RAPx)) - A platform that helps Rust programmers develop and use advanced static analysis tools beyond those provided by the rustc compiler.
* 🌎 [static_assertions](crates.io/crates/static_assertions) - Compile-time assertions to ensure that invariants are met
* <b><code>&nbsp;&nbsp;2019⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [verus-lang/verus](https://github.com/verus-lang/verus)) - Verified Rust for low-level systems code

### Testing

 🌎 [test](crates.io/keywords/test), 🌎 [testing](crates.io/keywords/testing)]

* Code Coverage
  * 🌎 [tarpaulin](crates.io/crates/cargo-tarpaulin) - A code coverage tool
* Continuous Integration
  * <b><code>&nbsp;&nbsp;1279⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [trust](https://github.com/japaric/trust)) - A Travis CI and AppVeyor template to test your Rust crate on 5 architectures and publish binary releases of it for Linux, macOS and Windows
* Frameworks and Runners
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [AlKass/polish](https://github.com/AlKass/polish)) - Mini Testing/Test-Driven Framework [![Crates Package Status](https://img.shields.io/crates/v/polish.svg)](https://crates.io/crates/polish)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [bitfield/cargo-testdox](https://github.com/bitfield/cargo-testdox))  🌎 [cargo-testdox](crates.io/crates/cargo-testdox)] - Turns your Rust tests into docs [![CI](https://github.com/bitfield/cargo-testdox/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/bitfield/cargo-testdox/actions/workflows/ci.yml)
  * 🌎 [cargo-dinghy](crates.io/crates/cargo-dinghy/) - A cargo extension to simplify running library tests and benches on smartphones and other small processor devices.
  * 🌎 [cucumber](crates.io/crates/cucumber) [![Latest Version](https://img.shields.io/crates/v/cucumber.svg)](https://crates.io/crates/cucumber) - An implementation of the Cucumber testing framework for Rust. Fully native, no external test runners or dependencies. [![Build Status](https://github.com/cucumber-rs/cucumber/actions/workflows/ci.yml/badge.svg)](https://github.com/cucumber-rs/cucumber/actions)
  * <b><code>&nbsp;&nbsp;&nbsp;148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [d-e-s-o/test-log](https://github.com/d-e-s-o/test-log))  🌎 [test-log](crates.io/crates/test-log)] - A replacement of the `#[test]` attribute that initializes logging and/or tracing infrastructure before running tests. [![GitHub Workflow Status](https://github.com/d-e-s-o/test-log/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/d-e-s-o/test-log/actions/workflows/test.yml)
  * 🌎 [demonstrate](crates.io/crates/demonstrate) - Declarative Testing Framework [![Build Status](https://github.com/aubaugh/demonstrate/workflows/Continuous%20Integration/badge.svg?branch=master)](https://github.com/aubaugh/demonstrate)
  * 🌎 [GoogleTest Rust](crates.io/crates/googletest) - Powerful test assertion framework based on the C++ test library GoogleTest [![Build Status](https://github.com/google/googletest-rust/workflows/CI/badge.svg)](https://github.com/google/googletest-rust/actions?query=workflow%3ACI+branch%3Amain)
  * <b><code>&nbsp;&nbsp;&nbsp;190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [rlt](https://github.com/wfxr/rlt)) - A universal load testing framework, with real-time tui support.
  * 🌎 [rstest](crates.io/crates/rstest) - Fixture-based test framework [![Build Status](https://github.com/la10736/rstest/workflows/Test/badge.svg?branch=master)](https://github.com/la10736/rstest/actions)
  * 🌎 [speculate](crates.io/crates/speculate) - An RSpec inspired minimal testing framework
* Mocking and Test Data
  * <b><code>&nbsp;&nbsp;1704⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [asomers/mockall](https://github.com/asomers/mockall))  🌎 [mockall](crates.io/crates/mockall)] - A powerful mock object library. [![Cirrus Build Status](https://api.cirrus-ci.com/github/asomers/mockall.svg)](https://cirrus-ci.com/github/asomers/mockall)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [bcheidemann/fixtures-rs](https://github.com/bcheidemann/fixtures-rs/tree/main/fixtures))  🌎 [fixtures](crates.io/crates/fixtures)] - A proc macro for generating tests from fixtures using glob patterns
  * <b><code>&nbsp;&nbsp;1140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [fake-rs](https://github.com/cksac/fake-rs)) - A library for generating fake data
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [goldenfile](https://github.com/calder/rust-goldenfile))  🌎 [goldenfile](crates.io/crates/goldenfile)] - A library providing a simple API for goldenfile testing.
  * <b><code>&nbsp;&nbsp;&nbsp;609⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [httpmock](https://github.com/httpmock/httpmock)) - HTTP mocking [![Build](https://github.com/httpmock/httpmock/actions/workflows/build.yml/badge.svg)](https://github.com/httpmock/httpmock/actions/workflows/build.yml)
  * 🌎 [mockiato](crates.io/crates/mockiato) - A strict, yet friendly mocking library for unstable Rust 2018
  * 🌎 [mockito](crates.io/crates/mockito) - HTTP mocking
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [mocktail](https://github.com/IBM/mocktail)) [![mocktail](https://img.shields.io/crates/v/mocktail)](https://crates.io/crates/mocktail) - HTTP & gRPC server mocking for Rust ![build](https://github.com/IBM/mocktail/actions/workflows/build.yml/badge.svg)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [nrxus/faux](https://github.com/nrxus/faux/)) [![Latest Version](https://img.shields.io/crates/v/faux.svg)](https://crates.io/crates/faux) - A library to create mocks out of structs. ![build](https://github.com/nrxus/faux/workflows/test/badge.svg?branch=master)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [synth](https://github.com/shuttle-hq/synth/)) - Generate database data declaratively. [![build](https://github.com/shuttle-hq/synth/actions/workflows/synth-test.yml/badge.svg)](https://github.com/shuttle-hq/synth)
* Mutation Testing
  * <b><code>&nbsp;&nbsp;&nbsp;977⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [cargo-mutants](https://github.com/sourcefrog/cargo-mutants))  🌎 [cargo-mutants](crates.io/crates/cargo-mutants)] - Finds inadequately tested code by injecting mutations, no source changes required. [![build badge](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml/badge.svg?branch=main&event=push)](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml?query=branch%3Amain)
  * <b><code>&nbsp;&nbsp;&nbsp;638⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [mutagen](https://github.com/llogiq/mutagen))  🌎 [mutagen](crates.io/crates/mutagen)] - A source-level mutation testing framework (nightly only)
* Property Testing and Fuzzing
  * 🌎 [proptest](crates.io/crates/proptest) - property testing framework inspired by the 🌎 [Hypothesis](hypothesis.works/) framework for Python
  * 🌎 [quickcheck](crates.io/crates/quickcheck) - A Rust implementation of 🌎 [QuickCheck](wiki.haskell.org/Introduction_to_QuickCheck1)
  * <b><code>&nbsp;&nbsp;1770⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [rust-fuzz/afl.rs](https://github.com/rust-fuzz/afl.rs)) - A Rust fuzzer, using 🌎 [AFL](lcamtuf.coredump.cx/afl/)

### Transpiling

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [aleph-lang/aleph_ollama](https://github.com/aleph-lang/aleph_ollama))  🌎 [aleph_ollama](crates.io/crates/aleph_ollama)] - AI-powered source code translation tool using local Ollama API.
* <b><code>&nbsp;&nbsp;2913⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;250🍴</code></b> [BayesWitnesses/m2cgen](https://github.com/BayesWitnesses/m2cgen)) - A CLI tool to transpile trained classic machine learning models into a native Rust code with zero dependencies. [![GitHub Actions Status](https://github.com/BayesWitnesses/m2cgen/workflows/GitHub%20Actions/badge.svg?branch=master)](https://github.com/BayesWitnesses/m2cgen/actions)
* <b><code>&nbsp;&nbsp;4485⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;273🍴</code></b> [immunant/c2rust](https://github.com/immunant/c2rust)) - C to Rust translator and cross checker built atop Clang/LLVM.
* <b><code>&nbsp;&nbsp;2176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [jameysharp/corrode](https://github.com/jameysharp/corrode)) - A C to Rust translator written in Haskell.

## Libraries

* <b><code>&nbsp;&nbsp;&nbsp;223⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [perf-monitor-rs](https://github.com/larksuite/perf-monitor-rs)) - A toolkit designed to be a foundation for applications to monitor their performance. [![crates.io](https://img.shields.io/crates/v/perf_monitor.svg)](https://crates.io/crates/perf_monitor)

### Artificial Intelligence

#### Genetic algorithms

* <b><code>&nbsp;&nbsp;&nbsp;186⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [innoave/genevo](https://github.com/innoave/genevo)) - Execute genetic algorithm (GA) simulations in a customizable and extensible way.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [m-decoster/RsGenetic](https://github.com/m-decoster/RsGenetic)) - Genetic Algorithm library. In maintenance mode.
* <b><code>&nbsp;&nbsp;&nbsp;183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Martin1887/oxigen](https://github.com/Martin1887/oxigen)) - Fast, parallel, extensible and adaptable genetic algorithm library. A example using this library solves the N Queens problem for N = 255 in only few seconds and using less than 1 MB of RAM.
* <b><code>&nbsp;&nbsp;&nbsp;222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [pkalivas/radiate](https://github.com/pkalivas/radiate)) - A customizable parallel genetic programming engine capable of evolving solutions for supervised, unsupervised, and reinforcement learning problems. Comes with complete and customizable implementation of NEAT and Evtree.![Crates.io](https://img.shields.io/crates/v/radiate)
* <b><code>&nbsp;&nbsp;&nbsp;125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [willi-kappler/darwin-rs](https://github.com/willi-kappler/darwin-rs)) - Evolutionary algorithms

#### Machine learning

See  🌎 [Machine learning](crates.io/keywords/machine-learning)]

See also 🌎 [About Rust’s Machine Learning Community](medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f) and 🌎 [Are we learning yet?](www.arewelearningyet.com).

* <b><code>&nbsp;&nbsp;5551⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;269🍴</code></b> [autumnai/leaf](https://github.com/autumnai/leaf)) - Open Machine Intelligence framework.. Abandoned project. The most updated fork is <b><code>&nbsp;&nbsp;1121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [juice](https://github.com/fff-rs/juice)).
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [ave-sergeev/tictonix](https://github.com/Ave-Sergeev/Tictonix))  🌎 [tictonix](crates.io/crates/tictonix)] - A library that provides the ability to convert tokens into embeddings, as well as to encode their positions.
* <b><code>&nbsp;&nbsp;&nbsp;413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [blackportal-ai/delta](https://github.com/blackportal-ai/delta)) - Δ An Open-Source Machine Learning Framework in Rust. ![crates.io](https://img.shields.io/crates/v/deltaml.svg) ![build](https://img.shields.io/github/actions/workflow/status/blackportal-ai/delta/core.yml?branch=master)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [blackportal-ai/nebula](https://github.com/blackportal-ai/nebula)) - A Package Manager for Machine Learning Datasets and Models. ![build](https://img.shields.io/github/actions/workflow/status/blackportal-ai/nebula/core.yml?branch=master)
* <b><code>&nbsp;12968⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;705🍴</code></b> [burn](https://github.com/tracel-ai/burn)) - A Flexible and Comprehensive Deep Learning Framework.
* <b><code>&nbsp;&nbsp;1852⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [coreylowman/dfdx](https://github.com/coreylowman/dfdx)) - CUDA accelerated machine learning framework that leverages many of Rust's unique features. ![Crates.io](https://img.shields.io/crates/v/dfdx)
* <b><code>&nbsp;&nbsp;2949⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;235🍴</code></b> [guillaume-be/rust-bert](https://github.com/guillaume-be/rust-bert))  🌎 [rust_bert](crates.io/crates/rust_bert)] - Ready-to-use NLP pipelines and language models
* <b><code>&nbsp;18196⭐</code></b> <b><code>&nbsp;&nbsp;1235🍴</code></b> [huggingface/candle](https://github.com/huggingface/candle))  🌎 [candle-core](crates.io/crates/candle-core)] - a minimalist ML framework with a focus on easiness of use and on performance (including GPU support)
* <b><code>&nbsp;10101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;969🍴</code></b> [huggingface/tokenizers](https://github.com/huggingface/tokenizers)) - Hugging Face's tokenizers for modern NLP pipelines (original implementation) with bindings for Python. [![Build Status](https://github.com/huggingface/tokenizers/workflows/Rust/badge.svg?branch=master)](https://github.com/huggingface/tokenizers/actions)
* <b><code>&nbsp;&nbsp;5021⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;395🍴</code></b> [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs)) - Bindings for PyTorch.
* <b><code>&nbsp;&nbsp;&nbsp;635⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn)) - Machine learning library. [![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://app.circleci.com/pipelines/github/maciejkula/rustlearn)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Mottl/lightgb3-rs](https://github.com/Mottl/lightgbm3-rs)) - Bindings for LightGBM [![Crates.io](https://img.shields.io/crates/v/lightgbm3.svg)](https://crates.io/crates/lightgbm3) [![build](https://github.com/Mottl/lightgbm3-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/Mottl/lightgbm3-rs/actions)
* <b><code>&nbsp;&nbsp;&nbsp;528⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [perpetual-ml/perpetual](https://github.com/perpetual-ml/perpetual))  🌎 [perpetual](crates.io/crates/perpetual)] - A self-generalizing gradient boosting machine which doesn't need hyperparameter optimization.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [ramsyana/RustTensor](https://github.com/ramsyana/RustTensor)) - A learning-focused, high-performance tensor computation library built from scratch in Rust with automatic differentiation and CPU/CUDA backends.
* <b><code>&nbsp;&nbsp;4319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;291🍴</code></b> [rust-ml/linfa](https://github.com/rust-ml/linfa)) - Machine learning framework.
* <b><code>&nbsp;&nbsp;&nbsp;825⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [smartcorelib/smartcore](https://github.com/smartcorelib/smartcore)) - Machine Learning Library [![Build Status](https://img.shields.io/circleci/build/github/smartcorelib/smartcore)]
* <b><code>&nbsp;&nbsp;5399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;428🍴</code></b> [tensorflow/rust](https://github.com/tensorflow/rust)) - Bindings for TensorFlow.

#### OpenAI

* <b><code>&nbsp;&nbsp;1603⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;316🍴</code></b> [64bit/async-openai](https://github.com/64bit/async-openai))  🌎 [async-openai](crates.io/crates/async-openai)] - Ergonomic Rust bindings for OpenAI API based on OpenAPI spec.
* <b><code>&nbsp;&nbsp;3823⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [openai/harmony](https://github.com/openai/harmony))  🌎 [openai-harmony](crates.io/crates/openai-harmony/0.0.3)] - Renderer for the harmony response format to be used with gpt-oss.
* <b><code>&nbsp;&nbsp;&nbsp;338⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [zurawiki/tiktoken-rs](https://github.com/zurawiki/tiktoken-rs))  🌎 [tiktoken-rs](crates.io/crates/tiktoken-rs)] - Library for tokenizing text with OpenAI models using tiktoken. [![CI](https://github.com/zurawiki/tiktoken-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/zurawiki/tiktoken-rs/actions/workflows/ci.yml)

#### Tooling

* <b><code>&nbsp;&nbsp;6013⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;279🍴</code></b> [BAML](https://github.com/BoundaryML/baml)) - A simple prompting language for building reliable AI workflows and agents. BAML's compiler is written in Rust!

### Astronomy

 🌎 [astronomy](crates.io/keywords/astronomy)]

* <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [cds-astro/aladin-lite](https://github.com/cds-astro/aladin-lite)) - Web application for visualizing spatial and planetary image surveys in different projections
* 🌎 [fitsio](crates.io/crates/fitsio) - fits interface library wrapping cfitsio
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [flosse/rust-sun](https://github.com/flosse/rust-sun))  🌎 [sun](crates.io/crates/sun)] - A rust port of the JS library suncalc
* <b><code>&nbsp;&nbsp;&nbsp;294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [saurvs/astro-rust](https://github.com/saurvs/astro-rust)) - astronomy

### Asynchronous

* 🌎 [async-std](async.rs/)  🌎 [async-std](crates.io/crates/async-std)] - Async version of the Rust standard library [![CI](https://github.com/async-rs/async-std/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/async-rs/async-std/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;&nbsp;442⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [dagrs](https://github.com/dagrs-dev/dagrs)) - A high-performance asynchronous task programming framework, which follows the concept of Flow based Programming.
* <b><code>&nbsp;&nbsp;&nbsp;150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [dpc/mioco](https://github.com/dpc/mioco)) - Scalable, coroutine-based, asynchronous IO handling library
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [igumnoff/gabriel2](https://github.com/igumnoff/gabriel2))  🌎 [gabriel2](crates.io/crates/gabriel2)] - Gabriel2: An actor-model library based on Tokio
* <b><code>&nbsp;&nbsp;6747⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;800🍴</code></b> [mio](https://github.com/tokio-rs/mio)) - MIO is a lightweight IO library, with a focus on adding as little overhead as possible over the OS abstractions
* <b><code>&nbsp;&nbsp;5724⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;662🍴</code></b> [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs)) - Zero-cost futures
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [t3hmrman/async-dropper](https://github.com/t3hmrman/async-dropper))  🌎 [async-dropper](crates.io/crates/async-dropper)] - Implementation of `AsyncDrop`
* <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [TeaEntityLab/fpRust](https://github.com/TeaEntityLab/fpRust)) - Monad/MonadIO, Handler, Coroutine/doNotation, Functional Programming features for Rust
* <b><code>&nbsp;29667⭐</code></b> <b><code>&nbsp;&nbsp;2771🍴</code></b> [tokio-rs/tokio](https://github.com/tokio-rs/tokio)) - A runtime for writing reliable, asynchronous, and slim applications with the Rust programming language.
* <b><code>&nbsp;&nbsp;&nbsp;986⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [tqwewe/kameo](https://github.com/tqwewe/kameo)) - Fault-tolerant Async Actors Built on Tokio
* <b><code>&nbsp;&nbsp;2251⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [Xudong-Huang/may](https://github.com/Xudong-Huang/may)) - Stackful coroutine library
* <b><code>&nbsp;&nbsp;&nbsp;462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs)) - A coroutine I/O library with a working-stealing scheduler

### Audio and Music

 🌎 [audio](crates.io/keywords/audio)]

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [aschey/stream-download-rs](https://github.com/aschey/stream-download-rs))  🌎 [stream-download](crates.io/crates/stream-download)] - A library for streaming audio, video, and other media content [![build badge](https://github.com/aschey/stream-download-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/aschey/stream-download-rs/actions)
* 🌎 [hound](crates.io/crates/hound) - A WAV encoding and decoding library
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [insomnimus/nodi](https://github.com/insomnimus/nodi))  🌎 [nodi](crates.io/crates/nodi)] - A library for playback and abstraction of MIDI files. [![build badge](https://github.com/insomnimus/nodi/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/nodi/actions)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [jhasse/ears](https://github.com/jhasse/ears)) - A simple library to play Sounds and Musics, on top of OpenAL and libsndfile
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [musitdev/portmidi-rs](https://github.com/musitdev/portmidi-rs)) - 🌎 [PortMidi](portmedia.sourceforge.net/portmidi/) bindings
* <b><code>&nbsp;&nbsp;&nbsp;660⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [ozankasikci/rust-music-theory](https://github.com/ozankasikci/rust-music-theory)) - Music theory library
* <b><code>&nbsp;&nbsp;2813⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [pdeljanov/Symphonia](https://github.com/pdeljanov/Symphonia)) - Audio decoding and media demuxing library supporting AAC, FLAC, MP3, MP4, OGG, Vorbis, and WAV.
* [RustAudio](https://github.com/RustAudio)
  * <b><code>&nbsp;&nbsp;3274⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;439🍴</code></b> [RustAudio/cpal](https://github.com/RustAudio/cpal)) - Low-level cross-platform audio I/O library. [![Actions Status](https://github.com/RustAudio/cpal/workflows/cpal/badge.svg?branch=master)](https://github.com/RustAudio/cpal/actions)
  * <b><code>&nbsp;&nbsp;2099⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;270🍴</code></b> [RustAudio/rodio](https://github.com/RustAudio/rodio)) - Audio playback library
  * <b><code>&nbsp;&nbsp;&nbsp;384⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio)) - PortAudio bindings
* <b><code>&nbsp;&nbsp;&nbsp;245⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Serial-ATA/lofty-rs](https://github.com/Serial-ATA/lofty-rs))  🌎 [lofty](crates.io/crates/lofty)] - A library for reading and editing the metadata of various audio formats [![build badge](https://github.com/Serial-ATA/lofty-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Serial-ATA/lofty-rs/actions)

### Authentication

* <b><code>&nbsp;&nbsp;&nbsp;228⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [constantoine/totp-rs](https://github.com/constantoine/totp-rs))  🌎 [totp-rs](crates.io/crates/totp-rs)] - 2fa library to generate and verify TOTP-based tokens ![Build Status](https://github.com/constantoine/totp-rs/workflows/Rust/badge.svg)
* <b><code>&nbsp;&nbsp;1903⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;307🍴</code></b> [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken)) - 🌎 [JSON Web Token](en.wikipedia.org/wiki/JSON_Web_Token) library
* <b><code>&nbsp;&nbsp;1091⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;182🍴</code></b> [oauth2](https://github.com/ramosbugs/oauth2-rs)) - Extensible, strongly-typed OAuth2 client library
* <b><code>&nbsp;&nbsp;&nbsp;747⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [oxide-auth](https://github.com/197g/oxide-auth)) - A OAuth2 server library, for use in combination with actix or other frontends, featuring a set of configurable and pluggable backends [![Build Status](https://api.cirrus-ci.com/github/197g/oxide-auth.svg?branch=master)](https://cirrus-ci.com/github/HeroicKatora/oxide-auth)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [sgrust01/jwtvault](https://github.com/sgrust01/jwtvault)) - Async library to manage and orchestrate JWT workflow
* <b><code>&nbsp;&nbsp;&nbsp;235⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [yup-oauth2](https://github.com/dermesser/yup-oauth2)) - An oauth2 client implementation providing the Device, Installed and Service Account flows

### Automotive

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [idletea/tokio-socketcan](https://github.com/idletea/tokio-socketcan))  🌎 [tokio-socketcan](crates.io/crates/tokio-socketcan)] - Linux SocketCAN support for tokio based on the socketcan crate
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [marcelbuesing/can-dbc](https://github.com/marcelbuesing/can-dbc))  🌎 [can-dbc](crates.io/crates/can-dbc)] - A parser for the DBC format
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [marcelbuesing/tokio-socketcan-bcm](https://github.com/marcelbuesing/tokio-socketcan-bcm))  🌎 [tokio-socketcan-bcm](crates.io/crates/tokio-socketcan-bcm)] - Linux SocketCAN BCM support for tokio
* <b><code>&nbsp;&nbsp;&nbsp;179⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [mbr/socketcan](https://github.com/socketcan-rs/socketcan-rs))  🌎 [socketcan](crates.io/crates/socketcan)] - Linux SocketCAN library
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Sensirion/lin-bus](https://github.com/Sensirion/lin-bus-rs))  🌎 [lin-bus](crates.io/crates/lin-bus)] - LIN bus driver traits and protocol implementation [![build badge](https://circleci.com/gh/Sensirion/lin-bus-rs.svg?style=svg)](https://app.circleci.com/pipelines/github/Sensirion/lin-bus-rs)

### Bioinformatics

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [polars-bio](https://github.com/biodatageeks/polars-bio)) - Blazing-Fast Bioinformatic Operations on Python DataFrames ![PyPI - Version](https://img.shields.io/pypi/v/polars-bio)
* [Rust-Bio](https://github.com/rust-bio) - bioinformatics libraries.

### Caching

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [06chaynes/http-cache](https://github.com/06chaynes/http-cache))  🌎 [http-cache](crates.io/crates/http-cache)] - A caching middleware that follows HTTP caching rules [![build badge](https://github.com/06chaynes/http-cache/workflows/http-cache/badge.svg)](https://github.com/06chaynes/http-cache/actions/workflows/http-cache.yml)
* <b><code>&nbsp;&nbsp;&nbsp;142⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [aisk/rust-memcache](https://github.com/aisk/rust-memcache)) - Memcached client library
* <b><code>&nbsp;&nbsp;&nbsp;424⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [al8n/stretto](https://github.com/al8n/stretto)) - A high performance thread-safe memory-bound cache [![build badge](https://github.com/al8n/stretto/actions/workflows/ci.yml/badge.svg)](https://github.com/al8n/stretto/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;1891⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [jaemk/cached](https://github.com/jaemk/cached)) - Simple function caching/memoization
* <b><code>&nbsp;&nbsp;2132⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [moka-rs/moka](https://github.com/moka-rs/moka)) - A high performance concurrent caching library inspired by the Caffeine library for Java [![build badge](https://github.com/moka-rs/moka/workflows/CI/badge.svg)](https://github.com/moka-rs/moka/actions/workflows/CI.yml)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [mozilla/sccache](https://github.com/mozilla/sccache/)) - Shared Compilation Cache, great compilation
* <b><code>&nbsp;&nbsp;&nbsp;662⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [zkat/cacache-rs](https://github.com/zkat/cacache-rs)) - A high-performance, concurrent, content-addressable disk cache, optimized for async APIs [![build badge](https://github.com/zkat/cacache-rs/workflows/CI/badge.svg)](https://github.com/zkat/cacache-rs/actions/workflows/ci.yml)

### Cloud

* AWS  🌎 [aws](crates.io/keywords/aws)]
  * <b><code>&nbsp;&nbsp;3512⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;374🍴</code></b> [awslabs/aws-lambda-rust-runtime](https://github.com/awslabs/aws-lambda-rust-runtime))  🌎 [lambda_runtime](crates.io/crates/lambda_runtime)] - Runtime for AWS Lambda [![build badge](https://github.com/awslabs/aws-lambda-rust-runtime/workflows/Rust/badge.svg)](https://github.com/awslabs/aws-lambda-rust-runtime/actions)
  * <b><code>&nbsp;&nbsp;3216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;265🍴</code></b> [awslabs/aws-sdk-rust](https://github.com/awslabs/aws-sdk-rust)) - The new AWS SDK
  * <b><code>&nbsp;&nbsp;2734⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;445🍴</code></b> [rusoto/rusoto](https://github.com/rusoto/rusoto)) - An AWS SDK for Rust
* Azure
  * <b><code>&nbsp;&nbsp;&nbsp;849⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;312🍴</code></b> [Azure/azure-sdk-for-rust](https://github.com/Azure/azure-sdk-for-rust)) - Official Azure SDK for Rust
* Load Balancer
  * <b><code>&nbsp;&nbsp;&nbsp;349⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [Convey](https://github.com/bparli/convey)) - Layer 4 Load Balancer with dynamic configuration loading.
* Multi Cloud
  * <b><code>&nbsp;&nbsp;2391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [Qovery/engine](https://github.com/Qovery/engine)) - Abstraction layer library that turns easy application deployment on Cloud providers in just a few minutes

### Command-line

* Argument parsing
  * <b><code>&nbsp;15542⭐</code></b> <b><code>&nbsp;&nbsp;1125🍴</code></b> [clap-rs](https://github.com/clap-rs/clap))  🌎 [clap](crates.io/crates/clap)] - A simple to use, full featured command-line argument parser
  * 🌎 [cliparser](crates.io/crates/cliparser) - Simple command line parser. [![build badge](https://github.com/sagiegurari/cliparser/actions/workflows/ci.yml/badge.svg)](https://github.com/sagiegurari/cliparser/actions)
  * <b><code>&nbsp;&nbsp;&nbsp;752⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [docopt/docopt.rs](https://github.com/docopt/docopt.rs))  🌎 [docopt](crates.io/crates/docopt)] - Implementation of [DocOpt](http://docopt.org)
  * <b><code>&nbsp;&nbsp;1845⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [google/argh](https://github.com/google/argh))  🌎 [argh](crates.io/crates/argh)] - An opinionated Derive-based argument parser optimized for code size [![build badge](https://github.com/google/argh/workflows/Argh/badge.svg?branch=master)](https://github.com/google/argh/actions)
  * <b><code>&nbsp;&nbsp;&nbsp;539⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [killercup/quicli](https://github.com/killercup/quicli))  🌎 [quicli](crates.io/crates/quicli)] - quickly build cool CLI apps
  * <b><code>&nbsp;&nbsp;&nbsp;298⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [ksk001100/seahorse](https://github.com/ksk001100/seahorse))  🌎 [seahorse](crates.io/crates/seahorse)] - A minimal CLI framework [![Build status](https://github.com/ksk001100/seahorse/workflows/CI/badge.svg?branch=master)](https://github.com/ksk001100/seahorse/actions)
  * <b><code>&nbsp;&nbsp;2732⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;151🍴</code></b> [TeXitoi/structopt](https://github.com/TeXitoi/structopt))  🌎 [structopt](crates.io/crates/structopt)] - parse command line argument by defining a struct
* Data visualization
  * <b><code>&nbsp;&nbsp;1198⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [nukesor/comfy-table](https://github.com/nukesor/comfy-table))  🌎 [comfy-table](crates.io/crates/comfy-table)] - Beautiful dynamic tables for your cli tools. [![Build status](https://github.com/Nukesor/comfy-table/workflows/Tests/badge.svg?branch=master)](https://github.com/nukesor/comfy-table/actions)
  * <b><code>&nbsp;&nbsp;2237⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [zhiburt/tabled](https://github.com/zhiburt/tabled))  🌎 [tabled](crates.io/crates/tabled)] - An easy to use library for pretty print tables of structs and enums. [![Build Status](https://github.com/zhiburt/tabled/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/tabled/actions)
* Human-centered design
  * <b><code>&nbsp;&nbsp;1781⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [rust-cli/human-panic](https://github.com/rust-cli/human-panic))  🌎 [human-panic](crates.io/crates/human-panic)] - panic messages for humans
* Line editor
  * <b><code>&nbsp;&nbsp;1756⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;193🍴</code></b> [kkawakam/rustyline](https://github.com/kkawakam/rustyline))  🌎 [rustyline](crates.io/crates/rustyline)] - readline implementation
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [MovingtoMars/liner](https://github.com/MovingtoMars/liner))  🌎 [liner](crates.io/crates/liner)] - A library offering readline-like functionality
  * <b><code>&nbsp;&nbsp;&nbsp;191⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [murarth/linefeed](https://github.com/murarth/linefeed))  🌎 [linefeed](crates.io/crates/linefeed)] - Configurable, extensible, interactive line reader
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [srijs/rust-copperline](https://github.com/srijs/rust-copperline))  🌎 [copperline](crates.io/crates/copperline)] - command line editing library
* Other
  * <b><code>&nbsp;&nbsp;&nbsp;220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [mgrachev/update-informer](https://github.com/mgrachev/update-informer))  🌎 [update-informer](crates.io/crates/update-informer)] - Update informer for CLI applications. It checks for a new version on Crates.io and GitHub [![build badge](https://github.com/mgrachev/update-informer/workflows/CI/badge.svg)](https://github.com/mgrachev/update-informer/actions)
* Pipeline
  * <b><code>&nbsp;&nbsp;&nbsp;432⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [hniksic/rust-subprocess](https://github.com/hniksic/rust-subprocess))  🌎 [subprocess](crates.io/crates/subprocess)] - facilities for interaction with external pipelines
  * 🌎 [imp/pager-rs](gitlab.com/imp/pager-rs)  🌎 [pager](crates.io/crates/pager)] - pipe your output through an external pager
  * <b><code>&nbsp;&nbsp;&nbsp;952⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [oconnor663/duct.rs](https://github.com/oconnor663/duct.rs))  🌎 [duct](crates.io/crates/duct)] - A builder for subprocess pipelines and IO redirection
  * <b><code>&nbsp;&nbsp;&nbsp;359⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [rust-cli/rexpect](https://github.com/rust-cli/rexpect))  🌎 [rexpect](crates.io/crates/rexpect)] - automate interactive applications such as ssh, ftp, passwd, etc [![CI](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml/badge.svg)](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml)
  * <b><code>&nbsp;&nbsp;&nbsp;195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [zhiburt/expectrl](https://github.com/zhiburt/expectrl))  🌎 [expectrl](crates.io/crates/expectrl)] - A library for controlling interactive programs in a pseudo-terminal [![build badge](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml)
* Progress
  * <b><code>&nbsp;&nbsp;&nbsp;593⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [a8m/pb](https://github.com/a8m/pb))  🌎 [pbr](crates.io/crates/pbr)] - console progress bar
  * <b><code>&nbsp;&nbsp;&nbsp;224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [clitic/kdam](https://github.com/clitic/kdam))  🌎 [kdam](crates.io/crates/kdam)] - A console progress bar library inspired by tqdm & rich.progress [![CI](https://github.com/clitic/kdam/actions/workflows/tests.yml/badge.svg)](https://github.com/clitic/kdam/actions/workflows/tests.yml)
  * <b><code>&nbsp;&nbsp;4887⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;262🍴</code></b> [console-rs/indicatif](https://github.com/console-rs/indicatif))  🌎 [indicatif](crates.io/crates/indicatif)] - indicate progress to users
  * <b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [etienne-napoleone/spinach](https://github.com/etienne-napoleone/spinach))  🌎 [spinach](crates.io/crates/spinach)] - Practical spinner. [![CI](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml/badge.svg)](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml)
  * <b><code>&nbsp;&nbsp;&nbsp;579⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [FGRibreau/spinners](https://github.com/FGRibreau/spinners))  🌎 [spinners](crates.io/crates/spinners)] - 60+ elegant terminal spinners
* Prompt
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [hashmismatch/terminal_cli.rs](https://github.com/hashmismatch/terminal_cli.rs))  🌎 [terminal_cli](crates.io/crates/terminal_cli)] - build an interactive command prompt
  * <b><code>&nbsp;&nbsp;2364⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [mikaelmello/inquire](https://github.com/mikaelmello/inquire))  🌎 [inquire](crates.io/crates/inquire)] - A library for building interactive prompts on terminals. [![Build status](https://github.com/mikaelmello/inquire/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/mikaelmello/inquire/actions)
  * 🌎 [starship/starship](starship.rs/)  🌎 [starship](crates.io/crates/starship)] - A minimal, blazing fast, and extremely customizable prompt for any shell [![Build status](https://github.com/starship/starship/actions/workflows/workflow.yml/badge.svg)](https://github.com/starship/starship/actions)
  * <b><code>&nbsp;&nbsp;&nbsp;438⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [ynqa/promkit](https://github.com/ynqa/promkit))  🌎 [promkit](crates.io/crates/promkit)] - A toolkit for building interactive command-line tools [![ci](https://github.com/ynqa/promkit/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ynqa/promkit/actions/workflows/ci.yml)
* Style
  * <b><code>&nbsp;&nbsp;1918⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [colored](https://github.com/colored-rs/colored))  🌎 [colored](crates.io/crates/colored)] - Coloring terminal so simple, you already know how to do it!
  * <b><code>&nbsp;&nbsp;1486⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [console-rs/dialoguer](https://github.com/console-rs/dialoguer))  🌎 [dialoguer](crates.io/crates/dialoguer)] - Library for command line prompts and similar things.
  * <b><code>&nbsp;&nbsp;&nbsp;230⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [LukasKalbertodt/bunt](https://github.com/LukasKalbertodt/bunt))  🌎 [bunt](crates.io/crates/bunt)] - cross-platform terminal colors and styling with macros [![Build status](https://github.com/LukasKalbertodt/bunt/actions/workflows/ci.yml/badge.svg)](https://github.com/LukasKalbertodt/bunt/actions?query=workflow%3ACI+branch%3Amaster)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [LukasKalbertodt/term-painter](https://github.com/LukasKalbertodt/term-painter))  🌎 [term-painter](crates.io/crates/term-painter)] - cross-platform styled terminal output
  * <b><code>&nbsp;&nbsp;&nbsp;475⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [ogham/rust-ansi-term](https://github.com/ogham/rust-ansi-term))  🌎 [ansi_term](crates.io/crates/ansi_term)] - control colours and formatting on ANSI terminals
  * <b><code>&nbsp;&nbsp;&nbsp;272⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [SergioBenitez/yansi](https://github.com/SergioBenitez/yansi))  🌎 [yansi](crates.io/crates/yansi)] - A dead simple ANSI terminal color painting library
* TUI
  * <b><code>&nbsp;&nbsp;&nbsp;320⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [AppCUI](https://github.com/gdt050579/AppCUI-rs))  🌎 [appcui](crates.io/crates/appcui)] - A full-featured, cross-platform TUI/CUI framework in Rust, with built-in widgets, layout control, animations, Unicode and theming support.
  * BearLibTerminal
    * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [cfyzium/bearlibterminal](https://github.com/nabijaczleweli/BearLibTerminal.rs))  🌎 [bear-lib-terminal](crates.io/crates/bear-lib-terminal)] - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [BearLibTerminal](https://github.com/tommyettinger/BearLibTerminal)) bindings
  * <b><code>&nbsp;&nbsp;&nbsp;877⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [ccbrown/iocraft](https://github.com/ccbrown/iocraft))  🌎 [iocraft](crates.io/crates/iocraft)] - A crate for beautiful, artisanally crafted CLIs, TUIs, and text-based IO. [![Build status](https://github.com/ccbrown/iocraft/actions/workflows/commit.yaml/badge.svg?branch=main)](https://github.com/ccbrown/iocraft/actions) [![docs.rs](https://img.shields.io/docsrs/iocraft)](https://docs.rs/iocraft/)
  * <b><code>&nbsp;&nbsp;4632⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [gyscos/Cursive](https://github.com/gyscos/Cursive))  🌎 [cursive](crates.io/crates/cursive)] - build rich TUI applications
  * <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [ivanceras/titik](https://github.com/ivanceras/titik)) - a crossplatform TUI widget library with the goal of providing interactive widgets
  * ncurses
    * <b><code>&nbsp;&nbsp;&nbsp;408⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [ihalila/pancurses](https://github.com/ihalila/pancurses))  🌎 [pancurses](crates.io/crates/pancurses)] - curses library, supports linux and windows
    * <b><code>&nbsp;&nbsp;&nbsp;696⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs))  🌎 [ncurses](crates.io/crates/ncurses)] - 🌎 [ncurses](invisible-island.net/ncurses/ncurses.html) bindings
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [ogham/rust-term-grid](https://github.com/ogham/rust-term-grid))  🌎 [term_grid](crates.io/crates/term_grid)] - Library for putting things in a grid
  * <b><code>&nbsp;15111⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;473🍴</code></b> [ratatui-org/ratatui](https://github.com/ratatui/ratatui))  🌎 [ratatui](crates.io/crates/ratatui)] - Library that's all about cooking up terminal user interfaces (TUIs)
  * <b><code>&nbsp;&nbsp;2147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [redox-os/termion](https://github.com/redox-os/termion))  🌎 [termion](crates.io/crates/termion)] - bindless library for controlling terminals/TTY
  * 🌎 [ruterm](crates.io/crates/ruterm) - tiny & simple library for working with TTY
  * Termbox
    * <b><code>&nbsp;&nbsp;&nbsp;469⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [gchp/rustbox](https://github.com/gchp/rustbox))  🌎 [rustbox](crates.io/crates/rustbox)] - bindings to <b><code>&nbsp;&nbsp;2000⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;190🍴</code></b> [Termbox](https://github.com/nsf/termbox))
  * <b><code>&nbsp;&nbsp;3724⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;316🍴</code></b> [TimonPost/crossterm](https://github.com/crossterm-rs/crossterm))  🌎 [crossterm](crates.io/crates/crossterm)] - crossplatform terminal library

### Compression

* 🌎 [7z](7-zip.org/7z.html)
  *  🌎 [sevenz-rust](crates.io/crates/sevenz-rust)] - A 7z decompressor/compressor written in pure rust.
* 🌎 [Brotli](opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
  * <b><code>&nbsp;&nbsp;&nbsp;879⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli)) - Brotli decompressor that optionally avoids the stdlib
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [ende76/brotli-rs](https://github.com/ende76/brotli-rs)) - implementation of Brotli compression
* bzip2
  * <b><code>&nbsp;&nbsp;&nbsp;152⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [trifectatechfoundation/bzip2-rs](https://github.com/trifectatechfoundation/bzip2-rs)) - 🌎 [libbz2](www.sourceware.org/bzip2/) bindings
* gzip
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [zopfli](https://github.com/zopfli-rs/zopfli))  🌎 [zopfli](crates.io/crates/zopfli)] - implementation of the Zopfli compression algorithm for higher quality deflate or zlib compression
* gzp
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [sstadick/gzp](https://github.com/sstadick/gzp/)) - multi-threaded encoding and decoding of deflate formats and snappy
* miniz
  * <b><code>&nbsp;&nbsp;1042⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;180🍴</code></b> [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs)) - 🌎 [miniz](code.google.com/archive/p/miniz) bindings [![build badge](https://github.com/rust-lang/flate2-rs/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/flate2-rs/actions)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [paxit](https://github.com/roquess/paxit))  🌎 [paxit](crates.io/crates/paxit)] - Flexible library for compressing and decompressing files using various algorithms (zip, tar, gzip, xz, zst, etc.) with modular design for easy extension
* tar
  * <b><code>&nbsp;&nbsp;&nbsp;682⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs)) - tar archive reading/writing
* zip
  * <b><code>&nbsp;&nbsp;&nbsp;240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [zip-rs/zip2](https://github.com/zip-rs/zip2))  🌎 [zip](crates.io/crates/zip)] - read and write  ZIP archives
* zstd
  * <b><code>&nbsp;&nbsp;&nbsp;591⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [gyscos/zstd-rs](https://github.com/gyscos/zstd-rs)) - rust binding for the zstd compression library

### Computation

* <b><code>&nbsp;&nbsp;1163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [argmin-rs/argmin](https://github.com/argmin-rs/argmin))  🌎 [argmin](crates.io/crates/argmin)] - Optimization library
* 🌎 [BLAS](en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms)  🌎 [blas](crates.io/keywords/blas)]
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [mikkyang/rust-blas](https://github.com/mikkyang/rust-blas)) - BLAS bindings
* <b><code>&nbsp;&nbsp;1606⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [calebwin/emu](https://github.com/calebwin/emu)) - A language for GPGPU numerical computing
* <b><code>&nbsp;&nbsp;4454⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;513🍴</code></b> [dimforge/nalgebra](https://github.com/dimforge/nalgebra)) - low-dimensional linear algebra library
* <b><code>&nbsp;&nbsp;2355⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [faer-rs](https://github.com/sarah-quinones/faer-rs))  🌎 [faer](crates.io/crates/faer)] - Linear algebra foundation for Rust
* <b><code>&nbsp;&nbsp;&nbsp;213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [fastnum](https://github.com/neogenie/fastnum)) 🌎 [fastnum](crates.io/crates/fastnum) - Fast exact precision decimal numbers implemented in pure Rust. Suitable for financial, crypto and any other fixed-precision calculations.
* [GSL](http://www.gnu.org/software/gsl/)
  * <b><code>&nbsp;&nbsp;&nbsp;200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez/rust-GSL)) - GSL bindings
* 🌎 [LAPACK](en.wikipedia.org/wiki/LAPACK)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [stainless-steel/lapack](https://github.com/blas-lapack-rs/lapack)) - LAPACK bindings
* Parallel
  * <b><code>&nbsp;&nbsp;&nbsp;827⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust)) - [Arrayfire](https://github.com/arrayfire) bindings
  * <b><code>&nbsp;&nbsp;&nbsp;476⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [autumnai/collenchyma](https://github.com/autumnai/collenchyma)) - An extensible, pluggable, backend-agnostic framework for parallel, high-performance computations on CUDA, OpenCL and common host CPU.
  * <b><code>&nbsp;&nbsp;&nbsp;170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [luqmana/rust-opencl](https://github.com/luqmana/rust-opencl)) - 🌎 [OpenCL](www.khronos.org/opencl/) bindings
* Science
  * <b><code>&nbsp;&nbsp;&nbsp;651⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Axect/Peroxide](https://github.com/Axect/Peroxide)) - Rust numeric library containing linear algebra, numerical analysis, statistics and machine learning tools in pure rust
  * <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [cpmech/russell](https://github.com/cpmech/russell)) - Rust Scientific Library for numerical mathematics, ordinary differential equations, special math functions, high-performance (sparse) linear algebra
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Nonanti/mathcore](https://github.com/Nonanti/mathcore)) - Symbolic mathematics library with CAS capabilities. Supports differentiation, integration, equation solving, and arbitrary precision arithmetic [![crates.io](https://img.shields.io/crates/v/mathcore.svg)](https://crates.io/crates/mathcore)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Ryan-D-Gast/differential-equations](https://github.com/Ryan-D-Gast/differential-equations)) - A high-performance library for numerically solving differential equations
* Statrs
  * <b><code>&nbsp;&nbsp;&nbsp;732⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [statrs-dev/statrs](https://github.com/statrs-dev/statrs)) - Robust statistical computation library

### Concurrency

* <b><code>&nbsp;&nbsp;8092⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;505🍴</code></b> [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam)) - Support for parallelism and low-level concurrency
* <b><code>&nbsp;&nbsp;&nbsp;160⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [orium/archery](https://github.com/orium/archery))  🌎 [archery](crates.io/crates/archery)] - Library to abstract from `Rc`/`Arc` pointer types. [![build badge](https://github.com/orium/archery/workflows/CI/badge.svg)](https://github.com/orium/archery/actions?query=workflow%3ACI)
* 🌎 [orx-parallel](crates.io/crates/orx-parallel) - High performance, configurable and expressive parallel computation library.
* <b><code>&nbsp;12208⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;545🍴</code></b> [Rayon](https://github.com/rayon-rs/rayon)) - A data parallelism library
* <b><code>&nbsp;&nbsp;&nbsp;415⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [rustcc/coroutine-rs](https://github.com/rustcc/coroutine-rs)) - Coroutine Library
* <b><code>&nbsp;&nbsp;&nbsp;462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs)) - Coroutine I/O

### Configuration

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [andoriyu/uclicious](https://github.com/andoriyu/uclicious))  🌎 [uclicious](crates.io/crates/uclicious)] - <b><code>&nbsp;&nbsp;1689⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [libUCL](https://github.com/vstakhov/libucl)) based feature-rich configuration library. [![CircleCI](https://circleci.com/gh/vstakhov/libucl.svg?style=svg)](https://app.circleci.com/pipelines/github/vstakhov/libucl)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Kixunil/configure_me](https://github.com/Kixunil/configure_me))  🌎 [configure_me](crates.io/crates/configure_me)] - library for processing application configuration easily
* <b><code>&nbsp;&nbsp;3002⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;244🍴</code></b> [rust-cli/config-rs](https://github.com/rust-cli/config-rs))  🌎 [config](crates.io/crates/config)] - Layered configuration system (with strong support for 12-factor applications).
* <b><code>&nbsp;&nbsp;&nbsp;822⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [SergioBenitez/Figment](https://github.com/SergioBenitez/Figment))  🌎 [figment](crates.io/crates/figment)] - A configuration library so con-free, it's unreal.
* <b><code>&nbsp;&nbsp;&nbsp;953⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [softprops/envy](https://github.com/softprops/envy)) - deserialize env vars into typesafe structs [![Main](https://github.com/softprops/envy/actions/workflows/main.yml/badge.svg)](https://github.com/softprops/envy/actions/workflows/main.yml)

### Cryptography

 🌎 [crypto](crates.io/keywords/crypto), 🌎 [cryptography](crates.io/keywords/cryptography)]

* <b><code>&nbsp;&nbsp;&nbsp;273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [arkworks-rs/circom-compat](https://github.com/arkworks-rs/circom-compat)) - Arkworks bindings to Circom's R1CS, for Groth16 Proof and Witness generation.
* <b><code>&nbsp;&nbsp;3997⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;770🍴</code></b> [briansmith/ring](https://github.com/briansmith/ring)) - Safe, fast, small crypto using Rust and BoringSSL's cryptography primitives.
* <b><code>&nbsp;&nbsp;&nbsp;476⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [briansmith/webpki](https://github.com/briansmith/webpki)) - Web PKI TLS X.509 certificate validation.
* <b><code>&nbsp;&nbsp;&nbsp;163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [conradkleinespel/rooster](https://github.com/conradkleinespel/rooster))  🌎 [rooster](crates.io/crates/rooster)] - Simple password manager to use in your terminal
* <b><code>&nbsp;&nbsp;1938⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [cossacklabs/themis](https://github.com/cossacklabs/themis))  🌎 [themis](crates.io/crates/themis)] - a high-level cryptographic library for solving typical data security tasks, best fit for multi-platform apps. [![build badge](https://circleci.com/gh/cossacklabs/themis/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/cossacklabs/themis)
* <b><code>&nbsp;&nbsp;1435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;305🍴</code></b> [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto)) - cryptographic algorithms
* <b><code>&nbsp;&nbsp;1038⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;557🍴</code></b> [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek)) - Curve25519 operations
* <b><code>&nbsp;&nbsp;&nbsp;709⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;237🍴</code></b> [dalek-cryptography/ed25519-dalek](https://github.com/dalek-cryptography/ed25519-dalek)) - Ed25519 digital signatures
* <b><code>&nbsp;&nbsp;&nbsp;341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [dalek-cryptography/x25519-dalek](https://github.com/dalek-cryptography/x25519-dalek)) - X25519 key exchange
* <b><code>&nbsp;&nbsp;&nbsp;197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [debris/tiny-keccak](https://github.com/debris/tiny-keccak)) - Keccak family (SHA3)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [dusk-network/bls12-381](https://github.com/dusk-network/bls12_381)) - A Rust-native BLS12-381 with enhancements for zk performance: optimized multi-scalar multiplication, custom hashing, and serde support—ideal for privacy-focused protocols and zero-knowledge applications. ![Build Status](https://github.com/dusk-network/bls12_381/workflows/Continuous%20integration/badge.svg)  🌎 [dusk-bls12_381](crates.io/crates/dusk-bls12_381)]
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [dusk-network/plonk](https://github.com/dusk-network/plonk/)) - A high-performance, Rust-native implementation of the PLONK zk-SNARK over BLS12-381, optimized with custom gates and KZG10 polynomial commitment for efficient zero-knowledge proofs. ![Build Status](https://github.com/dusk-network/plonk/workflows/Continuous%20integration/badge.svg)  🌎 [PLONK](crates.io/crates/dusk-plonk)]
* <b><code>&nbsp;&nbsp;&nbsp;217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [dusk-network/poseidon252](https://github.com/dusk-network/Poseidon252)) - A Rust-native Poseidon hash over BLS12-381, Poseidon252 is built for zk-SNARK efficiency, ideal for privacy-focused protocols and zero-knowledge applications. ![Build Status](https://github.com/dusk-network/Poseidon252/workflows/Continuous%20integration/badge.svg)  🌎 [Poseidon](crates.io/crates/dusk-poseidon)]
* <b><code>&nbsp;&nbsp;1248⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;245🍴</code></b> [exonum/exonum](https://github.com/exonum/exonum))  🌎 [exonum](crates.io/crates/exonum)] - extensible framework for blockchain projects
* <b><code>&nbsp;&nbsp;&nbsp;352⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [facebook/opaque-ke](https://github.com/facebook/opaque-ke)) - Implementation of the recent 🌎 [OPAQUE](datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/) password-authenticated key exchange. [![build badge](https://github.com/facebook/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/facebook/opaque-ke)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [iddm/randomorg](https://github.com/iddm/randomorg)) - A random.org client library. [![Crates badge](https://img.shields.io/crates/v/randomorg.svg)](https://crates.io/crates/randomorg)
* <b><code>&nbsp;&nbsp;&nbsp;125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [klutzy/suruga](https://github.com/klutzy/suruga)) - Implementation of 🌎 [TLS 1.2](datatracker.ietf.org/doc/html/rfc5246)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [kn0sys/ecc-rs](https://github.com/kn0sys/ecc-rs)) - Intuitive library for elliptic curve cryptography tutorials [![Crates.io Version](https://img.shields.io/crates/v/kn0syseccrs)](https://crates.io/crates/kn0syseccrs)
* <b><code>&nbsp;&nbsp;&nbsp;279⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework)) - Bindings for Security Framework (OSX native)
* <b><code>&nbsp;&nbsp;&nbsp;140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [libOctavo/octavo](https://github.com/libOctavo/octavo)) - Modular hash and crypto library
* <b><code>&nbsp;&nbsp;&nbsp;697⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [orion-rs/orion](https://github.com/orion-rs/orion)) - This library aims to provide easy and usable crypto. 'Usable' meaning exposing high-level API's that are easy to use and hard to misuse. [![Tests](https://github.com/orion-rs/orion/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/orion-rs/orion/actions/workflows/test.yml)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [racum/rust-djangohashers](https://github.com/racum/rust-djangohashers))  🌎 [djangohashers](crates.io/crates/djangohashers)] - Port of the password primitives used in the Django Project. It doesn't require Django, only hashes and validates passwords according to its style.
* <b><code>&nbsp;&nbsp;2107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;299🍴</code></b> [RustCrypto/hashes](https://github.com/RustCrypto/hashes)) - Collection of cryptographic hash functions
* <b><code>&nbsp;&nbsp;6992⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;749🍴</code></b> [rustls/rustls](https://github.com/rustls/rustls)) - Implementation of TLS
* <b><code>&nbsp;&nbsp;&nbsp;521⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [sfackler/rust-native-tls](https://github.com/sfackler/rust-native-tls)) - Bindings for native TLS libraries
* <b><code>&nbsp;&nbsp;1532⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;792🍴</code></b> [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl)) - 🌎 [OpenSSL](www.openssl.org/) bindings
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [sorairolake/abcrypt](https://github.com/sorairolake/abcrypt))  🌎 [abcrypt](crates.io/crates/abcrypt)] - A simple, modern and secure file encryption library. [![CI](https://github.com/sorairolake/abcrypt/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/abcrypt/actions?query=workflow%3ACI)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [sorairolake/scryptenc-rs](https://github.com/sorairolake/scryptenc-rs))  🌎 [scryptenc](crates.io/crates/scryptenc)] - An implementation of the scrypt encrypted data format. [![CI](https://github.com/sorairolake/scryptenc-rs/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/scryptenc-rs/actions?query=workflow%3ACI)
* <b><code>&nbsp;&nbsp;&nbsp;328⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [w3f/schnorrkel](https://github.com/w3f/schnorrkel)) - Schnorr VRFs and signatures on the Ristretto group

### Data processing

* <b><code>&nbsp;&nbsp;&nbsp;374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [amv-dev/yata](https://github.com/amv-dev/yata)) - high performance technical analysis library [![Build Status](https://img.shields.io/github/workflow/status/amv-dev/yata/Rust?branch=master)](https://github.com/amv-dev/yata/actions?query=workflow%3ARust)
* <b><code>&nbsp;&nbsp;4029⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;343🍴</code></b> [bluss/ndarray](https://github.com/rust-ndarray/ndarray)) - N-dimensional array with array views, multidimensional slicing, and efficient operations
* <b><code>&nbsp;&nbsp;2857⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [cocoindex](https://github.com/cocoindex-io/cocoindex)) - ETL framework to build fresh index
* <b><code>&nbsp;&nbsp;7796⭐</code></b> <b><code>&nbsp;&nbsp;1657🍴</code></b> [datafusion](https://github.com/apache/datafusion)) - DataFusion is a very fast, extensible query engine for building high-quality data-centric systems in Rust, using the Apache Arrow in-memory format.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [GoPlasmatic/datalogic-rs](https://github.com/GoPlasmatic/datalogic-rs))  🌎 [datalogic-rs](crates.io/crates/datalogic-rs)] - High-performance, type-safe JSONLogic evaluation engine in Rust, ideal for business rules and dynamic filtering.
* <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [kernelmachine/utah](https://github.com/kernelmachine/utah)) - Dataframe structure and operations
* <b><code>&nbsp;&nbsp;7795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;279🍴</code></b> [pg_analytics](https://github.com/paradedb/paradedb/tree/dev/pg_analytics)) - PostgreSQL extension that accelerates analytical query processing inside Postgres to a performance level comparable to dedicated OLAP databases.
* <b><code>&nbsp;&nbsp;7795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;279🍴</code></b> [pg_lakehouse](https://github.com/paradedb/paradedb/tree/dev/pg_lakehouse)) - PostgreSQL extension that transforms Postgres into an analytical query engine over object stores like AWS S3/GCS and table formats like Delta Lake/Iceberg.
* <b><code>&nbsp;35440⭐</code></b> <b><code>&nbsp;&nbsp;2405🍴</code></b> [pola-rs/polars](https://github.com/pola-rs/polars)) - Fast feature complete DataFrame library [![Lint Rust](https://github.com/pola-rs/polars/actions/workflows/lint-rust.yml/badge.svg)](https://github.com/pola-rs/polars/actions)
* <b><code>&nbsp;&nbsp;3001⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [weld-project/weld](https://github.com/weld-project/weld)) - High-performance runtime for data analytics applications

### Data streaming

* <b><code>&nbsp;&nbsp;1170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [arkflow-rs/arkflow](https://github.com/arkflow-rs/arkflow)) - High-performance Rust stream processing engine [![CI](https://github.com/arkflow-rs/arkflow/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/arkflow-rs/arkflow/actions)
* <b><code>&nbsp;&nbsp;4533⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;304🍴</code></b> [ArroyoSystems/arroyo](https://github.com/ArroyoSystems/arroyo)) - High-performance real-time analytics in Rust and SQL [![CI](https://github.com/ArroyoSystems/arroyo/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/ArroyoSystems/arroyo/actions)
* <b><code>&nbsp;&nbsp;2922⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;183🍴</code></b> [iggy](https://github.com/apache/iggy))  🌎 [iggy](crates.io/crates/iggy)] - Persistent message streaming platform, supporting QUIC, TCP and HTTP transport protocols [![CI](https://github.com/apache/iggy/actions/workflows/test.yml/badge.svg)](https://github.com/apache/iggy/actions/workflows/test.yml)
* <b><code>&nbsp;&nbsp;5019⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;515🍴</code></b> [infinyon/fluvio](https://github.com/infinyon/fluvio)) - Programmable data streaming platform [![CI](https://github.com/infinyon/fluvio/actions/workflows/ci.yml/badge.svg)](https://github.com/infinyon/fluvio/actions)
* <b><code>&nbsp;&nbsp;&nbsp;350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [swim-rust](https://github.com/graphform/swim-rust))  🌎 [swim-rust](crates.io/crates/swimos)] - Self-contained distributed software platform for building stateful, massively real-time streaming applications.

### Data structures

* <b><code>&nbsp;&nbsp;1508⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [ashvardanian/simsimd](https://github.com/ashvardanian/SimSIMD)) - SIMD-accelerated vector distances and similarity functions for x86 AVX2 & AVX-512, and Arm NEON [![crates.io](https://img.shields.io/crates/v/simsimd.svg)](https://crates.io/crates/simsimd)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [becheran/grid](https://github.com/becheran/grid))  🌎 [grid](crates.io/crates/grid)] - Provide a two dimensional data structure that is easy to use and fast. [![build status](https://github.com/becheran/grid/actions/workflows/rust.yml/badge.svg)](https://github.com/becheran/grid/actions)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [billyevans/tst](https://github.com/billyevans/tst))  🌎 [tst](crates.io/crates/tst)] - Ternary search tree collection
* [contain-rs](https://github.com/contain-rs) - Extension of Rust's std::collections
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [danielpclark/array_tool](https://github.com/danielpclark/array_tool)) - Array helpers. Some of the most common methods you would use on Arrays made available on Vectors. Polymorphic implementations for handling most of your use cases.
* <b><code>&nbsp;&nbsp;&nbsp;418⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [fizyk20/generic-array](https://github.com/fizyk20/generic-array)) - a hack to allow for arrays sized by typenums
* <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [garro95/priority-queue](https://github.com/garro95/priority-queue)) 🌎 [priority-queue](crates.io/crates/priority-queue)] - A priority queue that implements priority changes.
* <b><code>&nbsp;&nbsp;1606⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [greyblake/nutype](https://github.com/greyblake/nutype))  🌎 [nutype](crates.io/crates/nutype)] - define newtype structures with validation constraints. [![build status](https://github.com/greyblake/nutype/actions/workflows/ci.yml/badge.svg)](https://github.com/greyblake/nutype/actions)
* <b><code>&nbsp;&nbsp;&nbsp;257⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [mrhooray/kdtree-rs](https://github.com/mrhooray/kdtree-rs)) - K-dimensional tree for fast geospatial indexing and nearest neighbors lookup
* <b><code>&nbsp;&nbsp;1549⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [orium/rpds](https://github.com/orium/rpds))  🌎 [rpds](crates.io/crates/rpds)] - Persistent data structures. [![build badge](https://github.com/orium/rpds/workflows/CI/badge.svg)](https://github.com/orium/rpds/actions?query=workflow%3ACI)
* <b><code>&nbsp;&nbsp;&nbsp;844⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs)) - Roaring Bitmaps
* <b><code>&nbsp;&nbsp;3012⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;333🍴</code></b> [rust-itertools/itertools](https://github.com/rust-itertools/itertools)) - Extra iterator adaptors, functions and macros
* <b><code>&nbsp;&nbsp;&nbsp;260⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [tnballo/scapegoat](https://github.com/tnballo/scapegoat))  🌎 [scapegoat](crates.io/crates/scapegoat)] - Safe, fallible, stack-only alternative to `BTreeSet` and `BTreeMap`. [![GitHub Actions](https://github.com/tnballo/scapegoat/workflows/test/badge.svg?branch=master)](https://github.com/tnballo/scapegoat/actions)
* 🌎 [xfix/enum-map](codeberg.org/xfix/enum-map)  🌎 [enum-map](crates.io/crates/enum-map)] - An optimized map implementation for enums using an array to store values.
* <b><code>&nbsp;&nbsp;&nbsp;313⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [yamafaktory/hypergraph](https://github.com/yamafaktory/hypergraph))  🌎 [hypergraph](crates.io/crates/hypergraph)] - Hypergraph is a data structure library to generate directed hypergraphs. [![ci](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml)

### Data visualization

* <b><code>&nbsp;&nbsp;&nbsp;588⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [blitzar-tech/egui_graphs](https://github.com/blitzar-tech/egui_graphs))  🌎 [egui_graphs](crates.io/crates/egui_graphs)] - Interactive graph visualization widget powered by egui and petgraph. [![Crates.io](https://img.shields.io/crates/v/egui_graphs)](https://crates.io/crates/egui_graphs) [![docs.rs](https://img.shields.io/docsrs/egui_graphs)](https://docs.rs/egui_graphs)
* <b><code>&nbsp;&nbsp;&nbsp;120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [djduque/pgfplots](https://github.com/djduque/pgfplots))  🌎 [pgfplots](crates.io/crates/pgfplots)] - Library to generate publication-quality figures. [![build](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml/badge.svg)](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml)
* <b><code>&nbsp;&nbsp;&nbsp;339⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [mazznoer/colorgrad-rs](https://github.com/mazznoer/colorgrad-rs))  🌎 [colorgrad](crates.io/crates/colorgrad)] - Color scales library for data visualization, charts, games, maps, generative art and others.
* <b><code>&nbsp;&nbsp;&nbsp;470⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [milliams/plotlib](https://github.com/milliams/plotlib)) - Data plotting library for Rust
* <b><code>&nbsp;&nbsp;1347⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [plotly](https://github.com/plotly/plotly.rs)) - Plotly for Rust
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [plotpy](https://github.com/cpmech/plotpy))  🌎 [plotpy](crates.io/crates/plotpy)] - Rust plotting library using Python (Matplotlib)
* <b><code>&nbsp;&nbsp;4322⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;302🍴</code></b> [plotters](https://github.com/plotters-rs/plotters)) - [![build badge](https://github.com/plotters-rs/plotters/workflows/CI/badge.svg)](https://github.com/plotters-rs/plotters/actions)
* <b><code>&nbsp;&nbsp;9312⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;536🍴</code></b> [rerun](https://github.com/rerun-io/rerun)) -  🌎 [rerun](crates.io/crates/rerun)] - An SDK for logging computer vision and robotics data (tensors, point clouds, etc) paired with a visualizer for exploring that data over time.
* <b><code>&nbsp;&nbsp;&nbsp;130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [saresend/gust](https://github.com/saresend/Gust)) - A small charting/visualization tool and partial vega implementation

### Database

 🌎 [database](crates.io/keywords/database)]

* NoSQL  🌎 [nosql](crates.io/keywords/nosql)]

  * 🌎 [ArangoDB](arangodb.com)
    * 🌎 [Aragog](gitlab.com/qonfucius/aragog)  🌎 [aragog](crates.io/crates/aragog)] - A Lightweight ArangoDB Object document, relational and graph mapper [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
    * <b><code>&nbsp;&nbsp;&nbsp;129⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Arangors](https://github.com/fMeow/arangors))  🌎 [arangors](crates.io/crates/arangors)] - An ArangoDB driver
  * 🌎 [Cassandra](cassandra.apache.org/_/index.html)  🌎 [cassandra](crates.io/keywords/cassandra), 🌎 [cql](crates.io/keywords/cql)]
    * <b><code>&nbsp;&nbsp;&nbsp;341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [AlexPikalov/cdrs](https://github.com/AlexPikalov/cdrs))  🌎 [cdrs](crates.io/crates/cdrs)] - native client
    * <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [cassandra-rs](https://github.com/cassandra-rs/cassandra-rs)) - bindings to the DataStax C/C++
    * <b><code>&nbsp;&nbsp;&nbsp;146⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [krojew/cdrs-tokio](https://github.com/krojew/cdrs-tokio)) - High-level async Cassandra client written in 100% Rust. [![build badge](https://github.com/krojew/cdrs-tokio/actions/workflows/rust.yml/badge.svg)](https://github.com/krojew/cdrs-tokio/actions)
      *  🌎 [cassandra-protocol](crates.io/crates/cassandra-protocol)] - Cassandra protocol implementation.
      *  🌎 [cdrs-tokio](crates.io/crates/cdrs-tokio)] - production-ready async Apache Cassandra driverclient
  * CouchDB  🌎 [couchdb](crates.io/keywords/couchdb)]
    * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [chill-rs/chill](https://github.com/chill-rs/chill))  🌎 [couchdb](crates.io/crates/chill)] - Client for the CouchDB REST API
  * 🌎 [DynamoDB](aws.amazon.com/dynamodb/)  🌎 [dynamodb](crates.io/keywords/dynamodb)]
    * <b><code>&nbsp;&nbsp;&nbsp;221⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [softprops/dynomite](https://github.com/softprops/dynomite)) - A library for strongly-typed and convenient interaction with `rusoto_dynamodb` [![build badge](https://github.com/softprops/dynomite/workflows/Main/badge.svg?branch=master)](https://github.com/softprops/dynomite/actions)
  * Elasticsearch  🌎 [elasticsearch](crates.io/keywords/elasticsearch)]
    * <b><code>&nbsp;&nbsp;&nbsp;219⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [benashford/rs-es](https://github.com/benashford/rs-es))  🌎 [rs-es](crates.io/crates/rs-es)] - Client for the 🌎 [Elastic](www.elastic.co/) REST API
    * <b><code>&nbsp;&nbsp;&nbsp;254⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [elastic-rs/elastic](https://github.com/elastic-rs/elastic))  🌎 [elastic](crates.io/crates/elastic)] - elastic is an efficient, modular API client for Elasticsearch written in Rust [![build badge](https://ci.appveyor.com/api/projects/status/csa78tcumdpnbur2?svg=true)](https://ci.appveyor.com/project/KodrAus/elastic)
  * etcd
    * <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [jimmycuadra/rust-etcd](https://github.com/jimmycuadra/rust-etcd))  🌎 [etcd](crates.io/crates/etcd)] - A client library for CoreOS's etcd.
  * 🌎 [InfluxDB](www.influxdata.com/)
    * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [driftluo/InfluxDBClient-rs](https://github.com/driftluo/InfluxDBClient-rs)) - Synchronization interface
  * LevelDB
    * <b><code>&nbsp;&nbsp;&nbsp;185⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [skade/leveldb](https://github.com/skade/leveldb)) - <b><code>&nbsp;38173⭐</code></b> <b><code>&nbsp;&nbsp;8063🍴</code></b> [LevelDB](https://github.com/google/leveldb)) bindings
  * LMDB  🌎 [lmdb](crates.io/keywords/lmdb)]
    * <b><code>&nbsp;&nbsp;&nbsp;796⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [meilisearch/heed](https://github.com/meilisearch/heed))  🌎 [heed](crates.io/crates/heed)] - Another 🌎 [LMDB](www.symas.com/symas-embedded-database-lmdb) binding
    * <b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [vhbit/lmdb-rs](https://github.com/vhbit/lmdb-rs))  🌎 [lmdb-rs](crates.io/crates/lmdb-rs)] - 🌎 [LMDB](www.symas.com/symas-embedded-database-lmdb) bindings
  * MongoDB  🌎 [mongodb](crates.io/keywords/mongodb)]
    * <b><code>&nbsp;&nbsp;1506⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [mongodb/mongo-rust-driver](https://github.com/mongodb/mongo-rust-driver))  🌎 [mongodb](crates.io/crates/mongodb)] - 🌎 [MongoDB](www.mongodb.com/) bindings
  * 🌎 [PickleDB](pythonhosted.org/pickleDB/)
    * <b><code>&nbsp;&nbsp;&nbsp;266⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [seladb/pickledb-rs](https://github.com/seladb/pickledb-rs)) - a lightweight and simple key-value store, heavily inspired by Python's PickleDB.
  * 🌎 [PoloDB](www.polodb.org/)
    * <b><code>&nbsp;&nbsp;1128⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [PoloDB](https://github.com/PoloDB/PoloDB)) - An embedded JSON-based database has API similar to MongoDB. ![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/PoloDB/PoloDB/rust.yml)
  * 🌎 [Redb](www.redb.org/)
    * <b><code>&nbsp;&nbsp;3976⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [Redb](https://github.com/cberner/redb)) - An embedded key-value database. It provides a similar interface to other embedded key-value stores such as rocksdb and lmdb. ![GitHub Workflow Status](https://github.com/cberner/redb/actions/workflows/ci.yml/badge.svg)
  * Redis  🌎 [redis](crates.io/keywords/redis)]
    * <b><code>&nbsp;&nbsp;&nbsp;482⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [aembke/fred](https://github.com/aembke/fred.rs))  🌎 [fred](crates.io/crates/fred)] - A high level async 🌎 [Redis](redis.io/) client for Rust with Tokio. [![CircleCI](https://circleci.com/gh/aembke/fred.rs/tree/main.svg?style=svg)] 🌎 [https://circleci.com/gh/aembke/fred.rs/tree/main](app.circleci.com/pipelines/github/aembke/fred.rs?branch=main))
    * <b><code>&nbsp;&nbsp;3990⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;646🍴</code></b> [redis-rs](https://github.com/redis-rs/redis-rs)) - 🌎 [Redis](redis.io/) library [![Rust](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml)
  * 🌎 [RocksDB](rocksdb.org/)
    * <b><code>&nbsp;&nbsp;2038⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;807🍴</code></b> [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb)) - RocksDB bindings [![RocksDB CI](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml)
  * 🌎 [SurrealDB](surrealdb.com/)
    * <b><code>&nbsp;30094⭐</code></b> <b><code>&nbsp;&nbsp;1049🍴</code></b> [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb)) - SurrealDB embedded document-graph database
  * <b><code>&nbsp;&nbsp;2249⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;173🍴</code></b> [UnQLite](https://github.com/symisc/unqlite))
    * <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [zitsen/unqlite.rs](https://github.com/zitsen/unqlite.rs)) - UnQLite bindings
  * 🌎 [ZooKeeper](zookeeper.apache.org/)
    * <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [bonifaido/rust-zookeeper](https://github.com/bonifaido/rust-zookeeper))  🌎 [zookeeper](crates.io/crates/zookeeper)] - A client library for Apache ZooKeeper.
    * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [krojew/rust-zookeeper](https://github.com/krojew/rust-zookeeper))  🌎 [zookeeper-async](crates.io/crates/zookeeper-async)] - Async Zookeeper client, based on tokio.  ![build status](https://github.com/krojew/rust-zookeeper/actions/workflows/rust.yml/badge.svg)
* OGM  🌎 [ogm](crates.io/keywords/ogm)]
    * 🌎 [Aragog](gitlab.com/qonfucius/aragog)  🌎 [aragog](crates.io/crates/aragog)] - A Lightweight ArangoDB Object document, relational and graph mapper [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
* ORM  🌎 [orm](crates.io/keywords/orm)]
  * <b><code>&nbsp;13684⭐</code></b> <b><code>&nbsp;&nbsp;1157🍴</code></b> [diesel-rs/diesel](https://github.com/diesel-rs/diesel)) - an ORM and Query builder
  * <b><code>&nbsp;&nbsp;&nbsp;250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [ivanceras/rustorm](https://github.com/ivanceras/rustorm)) - an ORM
  * <b><code>&nbsp;&nbsp;&nbsp;416⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [njord](https://github.com/njord-rs/njord)) - ⛵ A versatile, feature-rich Rust ORM [![build status](https://github.com/njord-rs/njord/actions/workflows/core.yml/badge.svg)](https://github.com/njord-rs/njord/actions/workflows/core.yml) ![crates.io](https://img.shields.io/crates/v/njord.svg)
  * <b><code>&nbsp;&nbsp;2385⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [rbatis/rbatis](https://github.com/rbatis/rbatis)) - ORM Framework High Performance(JSON based)
  * <b><code>&nbsp;&nbsp;8722⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;609🍴</code></b> [SeaQL/sea-orm](https://github.com/SeaQL/sea-orm)) - 🐚 An async & dynamic ORM  [![crate](https://img.shields.io/crates/v/sea-orm.svg)](https://crates.io/crates/sea-orm) [![docs](https://img.shields.io/docsrs/sea-orm/latest)](https://docs.rs/sea-orm) [![build status](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml)
  * <b><code>&nbsp;&nbsp;&nbsp;465⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [SeaQL/seaography](https://github.com/SeaQL/seaography)) - 🧭 GraphQL framework for SeaORM [![crate](https://img.shields.io/crates/v/seaography.svg)](https://crates.io/crates/seaography) [![docs](https://img.shields.io/docsrs/seaography/latest)](https://docs.rs/seaography) [![build status](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml/badge.svg)](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml)
  * <b><code>&nbsp;&nbsp;&nbsp;119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [thegenius/taitan-orm](https://github.com/thegenius/taitan-orm)) - The State of Art ORM for Rust, Async & Compile Time Generation.
* <b><code>&nbsp;&nbsp;1609⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [sfackler/r2d2](https://github.com/sfackler/r2d2)) - generic connection pool
* SQL  🌎 [sql](crates.io/keywords/sql)]
  * Generic
    * <b><code>&nbsp;15692⭐</code></b> <b><code>&nbsp;&nbsp;1475🍴</code></b> [launchbadge/sqlx](https://github.com/launchbadge/sqlx)) - async PostgreSQL/MySQL/SQLite connection pool with strong typing support [![build badge](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-square)](https://github.com/launchbadge/sqlx)
    * <b><code>&nbsp;&nbsp;1518⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [SeaQL/sea-query](https://github.com/SeaQL/sea-query)) - 🔱 A dynamic SQL query builder for MySQL, Postgres and SQLite [![crate](https://img.shields.io/crates/v/sea-query.svg)](https://crates.io/crates/sea-query) [![docs](https://img.shields.io/docsrs/sea-query/latest)](https://docs.rs/sea-query) [![build status](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml)
    * <b><code>&nbsp;&nbsp;&nbsp;208⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [SeaQL/sea-schema](https://github.com/SeaQL/sea-schema)) - 🌿 SQL schema definition and discovery [![crate](https://img.shields.io/crates/v/sea-schema.svg)](https://crates.io/crates/sea-schema) [![docs](https://img.shields.io/docsrs/sea-schema/latest)](https://docs.rs/sea-schema) [![build status](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml)
  * Microsoft SQL
    * <b><code>&nbsp;&nbsp;&nbsp;386⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;145🍴</code></b> [prisma/tiberius](https://github.com/prisma/tiberius)) - [![Cargo tests](https://github.com/prisma/tiberius/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/prisma/tiberius/actions/workflows/test.yml)
  * MySql  🌎 [mysql](crates.io/keywords/mysql)]
    * <b><code>&nbsp;&nbsp;&nbsp;195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [AgilData/mysql-proxy-rs](https://github.com/AgilData/mysql-proxy-rs)) - A MySQL Proxy [![CircleCI](https://circleci.com/gh/AgilData/mysql-proxy-rs/tree/master.svg?style=svg)](https://app.circleci.com/pipelines/github/AgilData/mysql-proxy-rs?branch=master)
    * <b><code>&nbsp;&nbsp;&nbsp;392⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [blackbeam/mysql_async](https://github.com/blackbeam/mysql_async))  🌎 [mysql_async](crates.io/crates/mysql_async)] - asynchronous Mysql driver based on Tokio. [![CircleCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/blackbeam/mysql_async?branch=master)
    * <b><code>&nbsp;&nbsp;&nbsp;690⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple))  🌎 [mysql](crates.io/crates/mysql)] - A native MySql client
  * Oracle
    * <b><code>&nbsp;&nbsp;&nbsp;215⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [kubo/rust-oracle](https://github.com/kubo/rust-oracle))  🌎 [oracle](crates.io/crates/oracle)] - Oracle driver [![build badge](https://github.com/kubo/rust-oracle/actions/workflows/run-tests.yml/badge.svg?branch=master)](https://github.com/kubo/rust-oracle/actions/workflows/run-tests.yml)
  * PostgreSql  🌎 [postgres](crates.io/keywords/postgres), 🌎 [postgresql](crates.io/keywords/postgresql)]
    * <b><code>&nbsp;&nbsp;&nbsp;314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [c410-f3r/wtx](https://github.com/c410-f3r/wtx)) - Fast implementation with a low set of external dependencies.
    * <b><code>&nbsp;&nbsp;3795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;510🍴</code></b> [rust-postgres](https://github.com/rust-postgres/rust-postgres))  🌎 [postgres](crates.io/crates/postgres)] - A native 🌎 [PostgreSQL](www.postgresql.org/) client
  * Sqlite  🌎 [sqlite](crates.io/keywords/sqlite)]
    * <b><code>&nbsp;&nbsp;3842⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;418🍴</code></b> [rusqlite](https://github.com/rusqlite/rusqlite)) - 🌎 [Sqlite3](sqlite.org/index.html) bindings
* 🌎 [VennDB](venndb.rs/) [<b><code>&nbsp;&nbsp;&nbsp;117⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [venndb](https://github.com/plabayo/venndb))] - An append-only in-memory database in Rust for rows queried using bit (flag) columns.

### Date and time

 🌎 [date](crates.io/keywords/date), 🌎 [time](crates.io/keywords/time)]

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [arthurhenrique/rusti-cal](https://github.com/arthurhenrique/rusti-cal))  🌎 [rusti-cal](crates.io/crates/rusti-cal)] - A cal(1) clone lightning-fast ~ more than 9999 years ~ Written in Rust.
* <b><code>&nbsp;&nbsp;2394⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [burntSushi/jiff](https://github.com/BurntSushi/jiff)) - A date-time library for Rust that encourages you to jump into the pit of success. [![Build status](https://github.com/BurntSushi/jiff/workflows/ci/badge.svg)](https://github.com/BurntSushi/jiff/actions)
* <b><code>&nbsp;&nbsp;3682⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;591🍴</code></b> [chronotope/chrono](https://github.com/chronotope/chrono)) - Date and time library
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Mnwa/ms](https://github.com/Mnwa/ms))  🌎 [ms-converter](crates.io/crates/ms-converter)] - it's a library for converting human-like times to milliseconds [![build badge](https://github.com/Mnwa/ms/workflows/build/badge.svg?branch=master)](https://github.com/Mnwa/ms/actions?query=workflow%3Abuild)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [sorairolake/nt-time](https://github.com/sorairolake/nt-time))  🌎 [nt-time](crates.io/crates/nt-time)] - A Windows file time library. [![CI](https://github.com/sorairolake/nt-time/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/nt-time/actions?query=workflow%3ACI)
* <b><code>&nbsp;&nbsp;1229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;291🍴</code></b> [time-rs/time](https://github.com/time-rs/time)) - [![build badge](https://github.com/time-rs/time/workflows/Build/badge.svg)](https://github.com/time-rs/time/actions)

### Distributed systems

* Antimony
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [antimonyproject/antimony](https://github.com/antimonyproject/antimony))  🌎 [antimony](crates.io/crates/antimony)] - stream processing / distributed computation platform
* Apache Kafka
  * <b><code>&nbsp;&nbsp;1856⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;324🍴</code></b> [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka))  🌎 [rdkafka](crates.io/crates/rdkafka)] - <b><code>&nbsp;&nbsp;&nbsp;782⭐</code></b> <b><code>&nbsp;&nbsp;3219🍴</code></b> [librdkafka](https://github.com/confluentinc/librdkafka)) bindings
  * <b><code>&nbsp;&nbsp;&nbsp;111⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [gklijs/schema_registry_converter](https://github.com/gklijs/schema_registry_converter))  🌎 [schema_registry_converter](crates.io/crates/schema_registry_converter)] - to integrate with 🌎 [confluent schema registry](www.confluent.io/product/confluent-platform/data-compatibility/)
  * <b><code>&nbsp;&nbsp;1391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [kafka-rust/kafka-rust](https://github.com/kafka-rust/kafka-rust)) - Rust client for Apache Kafka
* HDFS
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [hyunsik/hdfs-rs](https://github.com/hyunsik/hdfs-rs))  🌎 [hdfs](crates.io/crates/hdfs)] - libhdfs bindings
* Other
  * <b><code>&nbsp;&nbsp;4565⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;558🍴</code></b> [build-trust/ockam](https://github.com/build-trust/ockam))  🌎 [ockam](crates.io/crates/ockam)] - End-to-End Encryption, Mutual Authentication, and ABAC for distributed applications [![build badge](https://github.com/build-trust/ockam/workflows/Rust/badge.svg)](https://github.com/build-trust/ockam)

### Domain driven design

  * <b><code>&nbsp;&nbsp;&nbsp;432⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [serverlesstechnology/cqrs](https://github.com/serverlesstechnology/cqrs))  🌎 [cqrs-es](crates.io/crates/cqrs-es)] - A framework for CQRS and event sourcing with 🌎 [user guide](doc.rust-cqrs.org/)

### eBPF

* <b><code>&nbsp;&nbsp;3926⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;346🍴</code></b> [aya/aya-rs](https://github.com/aya-rs/aya)) - Built with a focus on developer experience and operability.
* <b><code>&nbsp;&nbsp;&nbsp;904⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [libbpf/libbpf-rs](https://github.com/libbpf/libbpf-rs)) - A minimal and opinionated eBPF tooling.

### Email

 🌎 [email](crates.io/keywords/email), 🌎 [imap](crates.io/keywords/imap), 🌎 [smtp](crates.io/keywords/smtp)]

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [duesee/imap-codec](https://github.com/duesee/imap-codec))  🌎 [imap-codec](crates.io/crates/imap-codec)] - Rock-solid and complete codec for IMAP [![Build & Test](https://github.com/duesee/imap-codec/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/duesee/imap-codec/actions/workflows/build_and_test.yml)
* <b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs)) - Library for SendGrid API
* <b><code>&nbsp;&nbsp;&nbsp;149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [jdrouet/catapulte](https://github.com/jdrouet/catapulte)) - A microservice to send emails using <b><code>&nbsp;&nbsp;&nbsp;428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [MRML](https://github.com/jdrouet/mrml)) templates.
* <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [jdrouet/jolimail](https://github.com/jdrouet/jolimail)) - A web application to build <b><code>&nbsp;&nbsp;&nbsp;428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [MRML](https://github.com/jdrouet/mrml)) templates.
* <b><code>&nbsp;&nbsp;&nbsp;428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [jdrouet/mrml](https://github.com/jdrouet/mrml)) - A library to generate nice email templates working on any mail client.
* <b><code>&nbsp;&nbsp;2103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;215🍴</code></b> [lettre/lettre](https://github.com/lettre/lettre)) - an SMTP-library [![CI](https://github.com/lettre/lettre/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/lettre/lettre/actions/workflows/test.yml)
* <b><code>&nbsp;&nbsp;&nbsp;187⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [mailtutan/mailtutan](https://github.com/mailtutan/mailtutan)) - An SMTP server for test and development environment.
* <b><code>&nbsp;&nbsp;&nbsp;781⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [meli/meli](https://github.com/meli/meli)) - 🐝 terminal mail client
* <b><code>&nbsp;&nbsp;&nbsp;211⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [staktrace/mailparse](https://github.com/staktrace/mailparse))  🌎 [mailparse](crates.io/crates/mailparse)] - A library for parsing real-world email files
* <b><code>&nbsp;&nbsp;&nbsp;106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [stalwartlabs/mail-auth](https://github.com/stalwartlabs/mail-auth))  🌎 [mail-auth](crates.io/crates/mail-auth)] - DKIM, ARC, SPF and DMARC message authentication library [![build badge](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml)
* <b><code>&nbsp;&nbsp;&nbsp;384⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [stalwartlabs/mail-parser](https://github.com/stalwartlabs/mail-parser))  🌎 [mail-parser](crates.io/crates/mail-parser)] - A fast and robust e-mail parsing library with full MIME support [![build badge](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml)
* <b><code>&nbsp;&nbsp;&nbsp;254⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [stalwartlabs/mail-send](https://github.com/stalwartlabs/mail-send))  🌎 [mail-send](crates.io/crates/mail-send)] - E-mail builder and SMTP client library with DKIM support [![build badge](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml)
* <b><code>&nbsp;&nbsp;&nbsp;901⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [tweedegolf/mailcrab](https://github.com/tweedegolf/mailcrab)) - Email test server for development.

### Encoding

 🌎 [encoding](crates.io/keywords/encoding)]

* ASN.1
  * <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [alex/rust-asn1](https://github.com/alex/rust-asn1)) - ASN.1 (DER) serializer
* Binary
  * <b><code>&nbsp;&nbsp;3084⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;300🍴</code></b> [bincode-org/bincode](https://github.com/bincode-org/bincode)) - A binary encoder/decoder [![CI](https://github.com/bincode-org/bincode/actions/workflows/rust.yml/badge.svg?branch=trunk)](https://github.com/bincode-org/bincode/actions/workflows/rust.yml)
  * <b><code>&nbsp;&nbsp;1192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [jamesmunns/postcard](https://github.com/jamesmunns/postcard))  🌎 [postcard](crates.io/crates/postcard)] - Postcard is a #![no_std] focused serializer and deserializer for Serde.
  * <b><code>&nbsp;&nbsp;1355⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;175🍴</code></b> [m4b/goblin](https://github.com/m4b/goblin))  🌎 [goblin](crates.io/crates/goblin)] - cross-platform, zero-copy, and endian-aware binary parsing
* BSON
  * <b><code>&nbsp;&nbsp;&nbsp;445⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [mongodb/bson-rust](https://github.com/mongodb/bson-rust)) - Encoding and decoding support for BSON
* Byte swapping
  * <b><code>&nbsp;&nbsp;1057⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder)) - Supports big-endian, little-endian and native byte orders
* Cap'n Proto
  * <b><code>&nbsp;&nbsp;2287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;236🍴</code></b> [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust)) - Cap'n Proto is a type system for distributed systems
* CBOR
  * 🌎 [serde_cbor](crates.io/crates/serde_cbor) - CBOR support for serde
* Character Encoding
  * <b><code>&nbsp;&nbsp;&nbsp;433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs))  🌎 [encoding_rs](crates.io/crates/encoding_rs)] - A Gecko-oriented implementation of the Encoding Standard
  * <b><code>&nbsp;&nbsp;&nbsp;286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding)) - Character encoding support for Rust. (also known as rust-encoding) It is based on WHATWG Encoding Standard, and also provides an advanced interface for error detection and recovery.
* CRC
  * <b><code>&nbsp;&nbsp;&nbsp;213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs)) - Rust implementation of CRC(16, 32, 64) with support of various standards
* CSV
  * <b><code>&nbsp;&nbsp;1851⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;232🍴</code></b> [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv)) - A fast and flexible CSV reader and writer, with support for Serde
* EDN
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [edn-rs](https://github.com/naomijub/edn-rs))  🌎 [edn-rs](crates.io/crates/edn-rs)] - crate to parse and emit EDN format into Rust types.
* 🌎 [FlatBuffers](flatbuffers.dev/)
  * <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [frol/flatc-rust](https://github.com/frol/flatc-rust)) - FlatBuffers compiler (flatc) integration for Cargo build scripts
* HAR
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [mandrean/har-rs](https://github.com/mandrean/har-rs))  🌎 [har](crates.io/crates/har)] - A HTTP Archive Format (HAR) serialization & deserialization library
* HTML
  * <b><code>&nbsp;&nbsp;2362⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;251🍴</code></b> [servo/html5ever](https://github.com/servo/html5ever)) - High-performance browser-grade HTML5 parser
* JSON
  * <b><code>&nbsp;&nbsp;&nbsp;711⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [cloudwego/sonic-rs](https://github.com/cloudwego/sonic-rs))  🌎 [sonic-rs](crates.io/crates/sonic-rs)] - A fast Rust JSON library based on SIMD.
  * <b><code>&nbsp;&nbsp;&nbsp;108⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [importcjj/rust-ajson](https://github.com/importcjj/rust-ajson))  🌎 [ajson](crates.io/crates/ajson)] - Get JSON values quickly
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [rustadopt/jzon-rs](https://github.com/rustadopt/jzon-rs/))  🌎 [jzon](crates.io/crates/jzon)] - JSON implementation
  * <b><code>&nbsp;&nbsp;5319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;606🍴</code></b> [serde-rs/json](https://github.com/serde-rs/json))  🌎 [serde\_json](crates.io/crates/serde_json)] - JSON support for <b><code>&nbsp;10010⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;857🍴</code></b> [Serde](https://github.com/serde-rs/serde)) framework
  * <b><code>&nbsp;&nbsp;1311⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [simd-lite/simd-json](https://github.com/simd-lite/simd-json))  🌎 [simd-json](crates.io/crates/simd-json)] - High performance JSON parser based on a port of simdjson
* MsgPack
  * <b><code>&nbsp;&nbsp;1304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust)) - Low/high level MessagePack implementation
* NetCDF
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [georust/netcdf](https://github.com/georust/netcdf))  🌎 [netcdf](crates.io/crates/netcdf)] - Medium-level netCDF bindings, allowing easy reading and writing of array-like structures to a file.
* PEM
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [jcreekmore/pem-rs](https://github.com/jcreekmore/pem-rs))  🌎 [pem](crates.io/crates/pem)] - Parse and encode PEM-encoded data
* ProtocolBuffers
  * <b><code>&nbsp;&nbsp;2942⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;395🍴</code></b> [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf)) - Rust implementation of Google protocol buffers
  * <b><code>&nbsp;&nbsp;4424⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;575🍴</code></b> [tokio-rs/prost](https://github.com/tokio-rs/prost)) - [![continuous integration](https://github.com/tokio-rs/prost/workflows/continuous%20integration/badge.svg?branch=master)](https://github.com/tokio-rs/prost/actions)
* rkyv
  * <b><code>&nbsp;&nbsp;3539⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;193🍴</code></b> [rkyv/rkyv](https://github.com/rkyv/rkyv))  🌎 [rkyv](crates.io/crates/rkyv)] - rkyv (archive) is a zero-copy deserialization framework
* RON (Rusty Object Notation)
  * <b><code>&nbsp;&nbsp;3708⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [https://github.com/ron-rs/ron](https://github.com/ron-rs/ron)) - Rusty Object Notation
* Serde
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [iddm/serde-aux](https://github.com/iddm/serde-aux/)) - additional tools for using with the serde library. [![CI](https://github.com/iddm/serde-aux/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/serde-aux/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/serde-aux.svg)](https://crates.io/crates/serde-aux)
* TOML
  * <b><code>&nbsp;&nbsp;1955⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;150🍴</code></b> [tamasfe/taplo](https://github.com/tamasfe/taplo))  🌎 [taplo](crates.io/crates/taplo)] - A TOML toolkit [![CI](https://github.com/tamasfe/taplo/workflows/Continuous%20integration/badge.svg)](https://github.com/tamasfe/taplo/actions?query=workflow%3A%22Continuous+integration%22)
  * <b><code>&nbsp;&nbsp;&nbsp;903⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [toml-rs/toml](https://github.com/toml-rs/toml)) - [![CI](https://github.com/toml-rs/toml/actions/workflows/ci.yml/badge.svg)](https://github.com/toml-rs/toml/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [vitiral/stfu8](https://github.com/vitiral/stfu8))  🌎 [stfu8](crates.io/crates/stfu8)] - Sorta Text Format in UTF-8
* XML
  * <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Florob/RustyXML](https://github.com/Florob/RustyXML)) - an XML parser
  * <b><code>&nbsp;&nbsp;&nbsp;469⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [netvl/xml-rs](https://github.com/netvl/xml-rs)) - A streaming XML library
  * <b><code>&nbsp;&nbsp;&nbsp;158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [shepmaster/sxd-document](https://github.com/shepmaster/sxd-document)) - An XML library
  * <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [shepmaster/sxd-xpath](https://github.com/shepmaster/sxd-xpath)) - An XPath library
  * <b><code>&nbsp;&nbsp;1388⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;265🍴</code></b> [tafia/quick-xml](https://github.com/tafia/quick-xml)) - High performance XML pull reader/writer
  * <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [yaserde](https://github.com/luminvent/yaserde)) - Yet Another Serializer/Deserializer specialized for XML
* YAML
  * <b><code>&nbsp;&nbsp;&nbsp;634⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;153🍴</code></b> [chyh1990/yaml-rust](https://github.com/chyh1990/yaml-rust)) - The missing YAML 1.2 implementation.
  * <b><code>&nbsp;&nbsp;&nbsp;205⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [saphyr](https://github.com/saphyr-rs/saphyr)) - A set of crates dedicated to parsing YAML.

### Filesystem

 🌎 [filesystem](crates.io/keywords/filesystem)]
* Operations
  * <b><code>&nbsp;&nbsp;&nbsp;513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Camino](https://github.com/camino-rs/camino))  🌎 [camino](crates.io/crates/camino)] - Like Rust's std::path::Path, but UTF-8.
  * <b><code>&nbsp;&nbsp;4446⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;635🍴</code></b> [OpenDAL](https://github.com/apache/opendal))  🌎 [opendal](crates.io/crates/opendal)] - A unified data access layer, empowering users to seamlessly and efficiently retrieve data from diverse storage services. [![build](https://img.shields.io/github/actions/workflow/status/apache/opendal/ci_core.yml?branch=main)](https://github.com/apache/opendal/actions?query=branch%3Amain)
  * <b><code>&nbsp;&nbsp;&nbsp;164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [ParthJadhav/Rust_Search](https://github.com/ParthJadhav/Rust_Search))  🌎 [rust_search](crates.io/crates/rust_search)] - Blazingly fast file search library.
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2))  🌎 [dbus-udisks2](crates.io/crates/dbus-udisks2)] - UDisks2 DBus API
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [pop-os/sys-mount](https://github.com/pop-os/sys-mount))  🌎 [sys-mount](crates.io/crates/sys-mount)] - High level abstraction for the `mount` / `umount2` system calls.
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [vitiral/path_abs](https://github.com/vitiral/path_abs))  🌎 [path_abs](crates.io/crates/path_abs)] - Absolute serializable path types and associated methods.
  * <b><code>&nbsp;&nbsp;&nbsp;326⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [webdesus/fs_extra](https://github.com/webdesus/fs_extra)) - expanding opportunities standard library std::fs and std::io
* Temporary Files
  * <b><code>&nbsp;&nbsp;1343⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [Stebalien/tempfile](https://github.com/Stebalien/tempfile)) - temporary file library
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Stebalien/xattr](https://github.com/Stebalien/xattr))  🌎 [xattr](crates.io/crates/xattr)] - list and manipulate unix extended file attributes
  * <b><code>&nbsp;&nbsp;1544⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [zboxfs/zbox](https://github.com/zboxfs/zbox))  🌎 [zbox](crates.io/crates/zbox)] - Zero-details, privacy-focused embeddable file system.

### Finance

* <b><code>&nbsp;&nbsp;1535⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;173🍴</code></b> [avhz/RustQuant](https://github.com/avhz/RustQuant))  🌎 [RustQuant](crates.io/crates/RustQuant)] - A quantitative finance library. ![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/avhz/RustQuant/build.yml)
* <b><code>&nbsp;&nbsp;&nbsp;170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [d-e-s-o/apca](https://github.com/d-e-s-o/apca))  🌎 [apca](crates.io/crates/apca)] - Opinionated and comprehensive bindings to the 🌎 [Alpaca API](alpaca.markets/) for stock trading and more. ![GitHub Workflow Status](https://github.com/d-e-s-o/apca/actions/workflows/test.yml/badge.svg?branch=main)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [stochastic-rs](https://github.com/rust-dd/stochastic-rs))  🌎 [stochastic-rs](crates.io/crates/stochastic-rs)] - High-performance data generation library for stochastic process with quant finance tools. ![GitHub Workflow Status](https://github.com/rust-dd/stochastic-rs/actions/workflows/rust.yml/badge.svg)

### Functional Programming

 🌎 [functional programming](crates.io/keywords/fp)]
* Prelude
  * <b><code>&nbsp;&nbsp;1394⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [JasonShin/fp-core.rs](https://github.com/JasonShin/fp-core.rs)) - A library for functional programming
  * <b><code>&nbsp;&nbsp;&nbsp;468⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [myrrlyn/tap](https://github.com/myrrlyn/tap)) - Suffix-Position Pipeline Behavior

### Game development

See also 🌎 [Are we game yet?](arewegameyet.rs)
* Allegro
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro)) - 🌎 [Allegro 5](liballeg.org/) bindings
* <b><code>&nbsp;&nbsp;&nbsp;223⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Awesome Quads](https://github.com/ozkriff/awesome-quads)) - A curated list of links to miniquad/macroquad-related code & resources
* <b><code>&nbsp;&nbsp;&nbsp;457⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Awesome wgpu](https://github.com/rofrol/awesome-wgpu)) - A curated list of wgpu code and resources
* bracket-lib (previously RLTK)
  * <b><code>&nbsp;&nbsp;1627⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [bracket-lib](https://github.com/amethyst/bracket-lib))  🌎 [bracket-lib](crates.io/crates/bracket-lib)] - The Roguelike Toolkit (RLTK). [![Rust](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml/badge.svg)](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml)
* Challonge
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [iddm/challonge-rs](https://github.com/iddm/challonge-rs))  🌎 [challonge](crates.io/crates/challonge)] - Client library for the Challonge REST API. Helps to organize tournaments. [![CI](https://github.com/iddm/challonge-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/challonge-rs/actions/workflows/ci.yml)
* Entity-Component Systems (ECS)
  * <b><code>&nbsp;&nbsp;2572⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;213🍴</code></b> [amethyst/specs](https://github.com/amethyst/specs)) - Specs Parallel ECS
  * <b><code>&nbsp;&nbsp;1687⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [legion](https://github.com/amethyst/legion)) - A feature rich high performance ECS library with minimal boilerplate [![build badge](https://github.com/amethyst/legion/workflows/CI/badge.svg?branch=master)](https://github.com/amethyst/legion/actions)
* Game Engines
  * <b><code>&nbsp;42332⭐</code></b> <b><code>&nbsp;&nbsp;4133🍴</code></b> [Bevy](https://github.com/bevyengine/bevy)) - is a refreshingly simple data-driven game engine. - [![Crates.io](https://img.shields.io/crates/v/bevy.svg)](https://crates.io/crates/bevy) [![Crates.io](https://img.shields.io/crates/d/bevy.svg)](https://crates.io/crates/bevy)
  * 🌎 [Fyrox](fyrox.rs/) - Game engine 3D [![Crates.io](https://img.shields.io/crates/v/fyrox.svg)](https://crates.io/crates/fyrox) [![license](https://img.shields.io/crates/l/fyrox.svg)](https://github.com/FyroxEngine/Fyrox/blob/master/LICENSE.md) [![Crates.io](https://img.shields.io/crates/d/fyrox.svg)](https://crates.io/crates/fyrox)
  * <b><code>&nbsp;&nbsp;4504⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;433🍴</code></b> [ggez](https://github.com/ggez/ggez)) - A lightweight game framework for making 2D games with minimum friction - [![Crates.io](https://img.shields.io/crates/v/ggez.svg)](https://crates.io/crates/ggez) [![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ggez/ggez/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/ggez.svg)](https://crates.io/crates/ggez)
  * <b><code>&nbsp;&nbsp;1552⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [Kiss3d](https://github.com/sebcrozet/kiss3d)) - A Keep It Simple, Stupid 3d graphics engine [![Crates.io](https://img.shields.io/crates/d/kiss3d.svg)](https://crates.io/crates/kiss3d)
  * <b><code>&nbsp;&nbsp;&nbsp;331⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [oxidator](https://github.com/Ruddle/oxidator)) - A real time strategy game/engine supporting WebGPU
  * 🌎 [Piston](www.piston.rs/) - [![Crates.io](https://img.shields.io/crates/v/piston.svg?style=flat-square)](https://crates.io/crates/piston) [![Crates.io](https://img.shields.io/crates/l/piston.svg)](https://github.com/PistonDevelopers/piston/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/piston.svg)](https://crates.io/crates/piston)
  * <b><code>&nbsp;&nbsp;&nbsp;381⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Unrust](https://github.com/unrust/unrust)) - Webgl 2.0 / native game engine
* Game Servers
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [gamedig/rust-gamedig](https://github.com/gamedig/rust-gamedig))  🌎 [gamedig](crates.io/crates/gamedig)] - Query game servers for informations such as name, players online, max players count etc. [![Crates.io](https://img.shields.io/crates/v/gamedig.svg)](https://crates.io/crates/gamedig) [![Crates.io](https://img.shields.io/crates/d/gamedig.svg)](https://crates.io/crates/gamedig)
* 🌎 [Godot](godotengine.org/)
  * <b><code>&nbsp;&nbsp;3993⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;247🍴</code></b> [godot-rust/gdext](https://github.com/godot-rust/gdext))  🌎 [gdext](crates.io/crates/gdext)] - Bindings to the Godot 4+ game engine [![CI](https://github.com/godot-rust/gdext/actions/workflows/full-ci.yml/badge.svg)](https://github.com/godot-rust/gdext/actions/workflows/full-ci.yml)
  * <b><code>&nbsp;&nbsp;3641⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;210🍴</code></b> [godot-rust/gdnative](https://github.com/godot-rust/gdnative))  🌎 [gdnative](crates.io/crates/gdnative)] - Bindings to the Godot 3+ game engine [![CI](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml/badge.svg)](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml)
* Minecraft
  * <b><code>&nbsp;&nbsp;&nbsp;132⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [bedrock-crustaceans/bedrock-rs](https://github.com/bedrock-crustaceans/bedrock-rs)) - Universal toolkit for Minecraft Bedrock Edition development in Rust. [![GitHub stars](https://img.shields.io/github/stars/bedrock-crustaceans/bedrock-rs)](https://github.com/bedrock-crustaceans/bedrock-rs) [![CI](https://github.com/bedrock-crustaceans/bedrock-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/bedrock-crustaceans/bedrock-rs/actions/workflows/ci.yml)
  * <b><code>&nbsp;&nbsp;1811⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [FerrumC](https://github.com/ferrumc-rs/ferrumc)) - A upgrade of the original Minecraft server in Rust [![build badge](https://github.com/ferrumc-rs/ferrumc/actions/workflows/rust.yml/badge.svg)]
  * <b><code>&nbsp;&nbsp;5613⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;318🍴</code></b> [Pumpkin](https://github.com/pumpkin-mc/pumpkin)) - A high-performance Minecraft server Software fully written in Rust
* 🌎 [Raylib](www.raylib.com/)
  * <b><code>&nbsp;&nbsp;&nbsp;864⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [deltaphc/raylib-rs](https://github.com/deltaphc/raylib-rs))  🌎 [raylib](crates.io/crates/raylib)] - Bindings for raylib
* 🌎 [SDL](www.libsdl.org/)  🌎 [sdl](crates.io/keywords/sdl)]
  * <b><code>&nbsp;&nbsp;&nbsp;180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [brson/rust-sdl](https://github.com/brson/rust-sdl)) - SDL1 bindings
  * <b><code>&nbsp;&nbsp;2910⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;476🍴</code></b> [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2)) - SDL2 bindings
* SFML
  * <b><code>&nbsp;&nbsp;&nbsp;670⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml)) - 🌎 [SFML](www.sfml-dev.org/) bindings
* Skillratings
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [atomflunder/skillratings](https://github.com/atomflunder/skillratings))  🌎 [skillratings](crates.io/crates/skillratings)] - Collection of skill rating algorithms for multiplayer games like Elo, Glicko-2, TrueSkill etc. [![crates.io badge](https://img.shields.io/crates/v/skillratings)](https://crates.io/crates/skillratings) [![CI](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml/badge.svg)](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml)
* Tatami
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [giraffekey/tatami](https://github.com/giraffekey/tatami))  🌎 [tatami](crates.io/crates/tatami-dungeon)] - A roguelike dungeon generation algorithm.
* Toornament-rs
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [iddm/toornament-rs](https://github.com/iddm/toornament-rs)) - Toornament.com API bindings. [![CI](https://github.com/iddm/toornament-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/toornament-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/toornament.svg)](https://crates.io/crates/toornament)
* Victorem
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [VictoremWinbringer/Victorem](https://github.com/VictoremWinbringer/Victorem))  🌎 [Victorem](crates.io/crates/Victorem)] - Easy UDP Game Server and UDP Client framework for creating simple 2D and 3D online game prototype

### Geospatial

 🌎 [geo](crates.io/keywords/geo), 🌎 [gis](crates.io/keywords/gis)]

* <b><code>&nbsp;&nbsp;&nbsp;165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [apache/sedona-db](https://github.com/apache/sedona-db)) - SedonaDB is a geospatial DataFrame library written in Rust.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [DaveKram/coord_transforms](https://github.com/DaveKram/coord_transforms))  🌎 [coord_transforms](crates.io/crates/coord_transforms)] - coordinate transformations (2-d, 3-d, and geospatial)
* [Georust](https://github.com/georust) - geospatial tools and libraries written
* <b><code>&nbsp;&nbsp;2977⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;286🍴</code></b> [MapLibre/Martin](https://github.com/maplibre/martin)) - Map tile server with PostGIS, MBTiles, PMTiles, and sprites support. [![CI build](https://github.com/maplibre/martin/actions/workflows/ci.yml/badge.svg)](https://github.com/maplibre/martin/actions)[![crates.io version](https://img.shields.io/crates/v/martin.svg)](https://crates.io/crates/martin)[![Book](https://img.shields.io/badge/docs-Book-informational)](https://maplibre.org/martin/)
* <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [rust-reverse-geocoder](https://github.com/gx0r/rrgeo)) - A fast, offline reverse geocoder, inspired by <b><code>&nbsp;&nbsp;1893⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [thampiman/reverse-geocoder](https://github.com/thampiman/reverse-geocoder))
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [vlopes11/geomorph](https://github.com/vlopes11/geomorph))  🌎 [geomorph](crates.io/crates/geomorph)] - conversion between UTM, LatLon and MGRS coordinates

### Graph algorithms

* <b><code>&nbsp;&nbsp;&nbsp;418⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [neo4j-labs/graph](https://github.com/neo4j-labs/graph)) - A library for high-performant graph algorithms [![graph CI status](https://img.shields.io/github/workflow/status/neo4j-labs/graph/CI/main?label=CI)](https://github.com/neo4j-labs/graph/actions/workflows/rust.yml)
* <b><code>&nbsp;&nbsp;3528⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;409🍴</code></b> [petgraph/petgraph](https://github.com/petgraph/petgraph)) - Graph data structure library. [![graph CI status](https://github.com/petgraph/petgraph/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/petgraph/petgraph/actions/workflows/ci.yml)

### Graphics

 🌎 [graphics](crates.io/keywords/graphics)]

* Fonts
  * <b><code>&nbsp;&nbsp;&nbsp;636⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [redox-os/rusttype](https://github.com/redox-os/rusttype)) - Alternative to libraries like FreeType
  * <b><code>&nbsp;&nbsp;&nbsp;629⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [rustybuzz](https://github.com/harfbuzz/rustybuzz)) - An incremental harfbuzz port
* <b><code>&nbsp;&nbsp;5396⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;536🍴</code></b> [gfx-rs/gfx](https://github.com/gfx-rs/gfx)) - A high-performance, bindless graphics API.
* <b><code>&nbsp;15157⭐</code></b> <b><code>&nbsp;&nbsp;1135🍴</code></b> [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu)) - Native WebGPU implementation based on gfx-hal. [![build badge](https://github.com/gfx-rs/wgpu/workflows/CI/badge.svg?branch=master)](https://github.com/gfx-rs/wgpu/actions)
* OpenGL  🌎 [opengl](crates.io/keywords/opengl)]
  * <b><code>&nbsp;&nbsp;&nbsp;722⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [gl-rs](https://github.com/rust-windowing/gl-rs)) - An OpenGL function pointer loader
  * <b><code>&nbsp;&nbsp;3584⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;408🍴</code></b> [glium/glium](https://github.com/glium/glium)) - safe OpenGL wrapper.
  * 🌎 [glutin](crates.io/crates/glutin) - Alternative to 🌎 [GLFW](www.glfw.org/)
  * <b><code>&nbsp;&nbsp;&nbsp;670⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [PistonDevelopers/glfw-rs](https://github.com/PistonDevelopers/glfw-rs)) - GLFW3 bindings and idiomatic wrapper
* PDF
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [bastibense/libharu_ng](https://github.com/bastibense/libharu_ng))  🌎 [libharu_ng](crates.io/crates/libharu_ng)] - Easily generate PDFs from your Rust app.
  * <b><code>&nbsp;&nbsp;&nbsp;985⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [fschutt/printpdf](https://github.com/fschutt/printpdf)) - PDF writing library
  * <b><code>&nbsp;&nbsp;1928⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf)) - PDF document manipulation
  * <b><code>&nbsp;&nbsp;&nbsp;148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [kaj/rust-pdf](https://github.com/kaj/rust-pdf)) - Generating PDF files in pure Rust
* 🌎 [Vulkan](www.vulkan.org/)  🌎 [vulkan](crates.io/keywords/vulkan)]
  * 🌎 [erupt](gitlab.com/Friz64/erupt)  🌎 [erupt](crates.io/crates/erupt)] - [![build badge](https://gitlab.com/Friz64/erupt/badges/main/pipeline.svg)](https://gitlab.com/Friz64/erupt/-/pipelines)
  * <b><code>&nbsp;&nbsp;4886⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;453🍴</code></b> [vulkano](https://github.com/vulkano-rs/vulkano))  🌎 [vulkano](crates.io/crates/vulkano)] - Safe and rich Rust wrapper around the Vulkan API

### GUI

 🌎 [gui](crates.io/keywords/gui)]

* <b><code>&nbsp;&nbsp;&nbsp;407⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [autopilot-rs/autopilot-rs](https://github.com/autopilot-rs/autopilot-rs)) - A simple, cross-platform GUI automation library.
* Cocoa
  * <b><code>&nbsp;&nbsp;1172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;237🍴</code></b> [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs)) - Rust bindings to Core Foundation and other low level libraries on Mac OS X and iOS
* <b><code>&nbsp;30639⭐</code></b> <b><code>&nbsp;&nbsp;1289🍴</code></b> [DioxusLabs/dioxus](https://github.com/dioxuslabs/dioxus)) - a portable, performant, and ergonomic framework for building cross-platform user interfaces in Rust. ![rust ci](https://github.com/dioxuslabs/dioxus/actions/workflows/main.yml/badge.svg)
* <b><code>&nbsp;26606⭐</code></b> <b><code>&nbsp;&nbsp;1836🍴</code></b> [emilk/egui](https://github.com/emilk/egui)) - Simple, fast, and highly portable immediate mode GUI library. egui runs on the web, natively, and in your favorite game engine. [![Build Status](https://github.com/emilk/egui/workflows/CI/badge.svg)](https://github.com/emilk/egui/actions?workflow=CI)
* <b><code>&nbsp;&nbsp;1144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [emoon/rust_minifb](https://github.com/emoon/rust_minifb)) - minifb is a cross-platform window setup with optional bitmap rendering. It also comes with easy mouse and keyboard input. Primarily designed for prototyping
* 🌎 [FLTK](www.fltk.org/)
  * <b><code>&nbsp;&nbsp;1766⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [fltk-rs](https://github.com/fltk-rs/fltk-rs)) - FLTK bindings [![Build](https://github.com/fltk-rs/fltk-rs/workflows/Build/badge.svg?branch=master)](https://github.com/fltk-rs/fltk-rs/actions)
* 🌎 [Flutter](flutter.dev/)
  * <b><code>&nbsp;&nbsp;2443⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [cunarist/rinf](https://github.com/cunarist/rinf)) - Rust as your Flutter backend, Flutter as your Rust frontend [![Build Test](https://github.com/cunarist/rinf/actions/workflows/build_test.yaml/badge.svg)](https://github.com/cunarist/rinf/actions/workflows/build_test.yaml?query=branch%3Amain)
  * <b><code>&nbsp;&nbsp;2116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [flutter-rs](https://github.com/flutter-rs/flutter-rs)) - Build flutter desktop app in dart & rust.
  * <b><code>&nbsp;&nbsp;4855⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;359🍴</code></b> [fzyzcjy/flutter_rust_bridge](https://github.com/fzyzcjy/flutter_rust_bridge)) - High-level memory-safe binding generator for Flutter/Dart <-> Rust
* <b><code>&nbsp;&nbsp;6038⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;223🍴</code></b> [fschutt/azul](https://github.com/fschutt/azul)) - A free, functional, IMGUI-oriented GUI framework for rapid development of desktop applications written in Rust, supported by the Mozilla WebRender rendering engine.
* 🌎 [GTK+](www.gtk.org/)  🌎 [gtk](crates.io/keywords/gtk)]
  * <b><code>&nbsp;&nbsp;2162⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;192🍴</code></b> [gtk-rs/gtk4-rs](https://github.com/gtk-rs/gtk4-rs)) - GTK4 binding ![CI](https://github.com/gtk-rs/gtk4-rs/workflows/CI/badge.svg)
  * <b><code>&nbsp;&nbsp;2454⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [relm](https://github.com/antoyo/relm)) - Asynchronous, GTK+-based, GUI library, inspired by Elm
* <b><code>&nbsp;27698⭐</code></b> <b><code>&nbsp;&nbsp;1369🍴</code></b> [iced-rs/iced](https://github.com/iced-rs/iced))  🌎 [iced](crates.io/crates/iced)] - A cross-platform GUI library, focused on simplicity and type-safety. Inspired by Elm.
* <b><code>&nbsp;68407⭐</code></b> <b><code>&nbsp;11228🍴</code></b> [ImGui](https://github.com/ocornut/imgui))
  * <b><code>&nbsp;&nbsp;2890⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;380🍴</code></b> [imgui-rs](https://github.com/imgui-rs/imgui-rs)) - Bindings for ImGui [![Build Status](https://github.com/imgui-rs/imgui-rs/workflows/ci/badge.svg?branch=master)](https://github.com/imgui-rs/imgui-rs/actions)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
  * <b><code>&nbsp;&nbsp;&nbsp;342⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Kiss-ui](https://github.com/KISS-UI/kiss-ui)) - A simple UI framework built on IUP
* <b><code>&nbsp;&nbsp;&nbsp;631⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [ivanceras/sauron-native](https://github.com/ivanceras/sauron-native)) - A truly native and cross platform GUI library. One unified code can be run as native GUI, Html Web and TUI.
* <b><code>&nbsp;10840⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;623🍴</code></b> [libui](https://github.com/andlabs/libui))
  * <b><code>&nbsp;&nbsp;&nbsp;937⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [rust-native-ui/libui-rs](https://github.com/rust-native-ui/libui-rs)) - libui bindings.
* <b><code>&nbsp;&nbsp;5908⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;290🍴</code></b> [makepad/makepad](https://github.com/makepad/makepad))  🌎 [makepad-widgets](crates.io/crates/makepad-widgets)] - Makepad is a creative software development platform that compiles to wasm/webGL, osx/metal, windows/dx11 linux/opengl.
* <b><code>&nbsp;10432⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;637🍴</code></b> [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear))
  * <b><code>&nbsp;&nbsp;&nbsp;367⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [nuklear-rust](https://github.com/snuk182/nuklear-rust)) - Bindings for Nuklear
* <b><code>&nbsp;&nbsp;3789⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;187🍴</code></b> [OrbTk](https://github.com/redox-os/orbtk)) - The Orbital Widget Toolkit is a multi platform (G)UI toolkit using SDL2 [![Build and test](https://github.com/redox-os/orbtk/workflows/build/badge.svg?branch=develop)](https://github.com/redox-os/orbtk/actions)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod/)) - An easy-to-use, immediate-mode, 2D GUI library
* 🌎 [Qt](doc.qt.io)
  * <b><code>&nbsp;&nbsp;&nbsp;437⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [cyndis/qmlrs](https://github.com/cyndis/qmlrs)) - QtQuick bindings
  * [rust-qt](https://github.com/rust-qt) - Qt bindings for Rust
  * <b><code>&nbsp;&nbsp;&nbsp;690⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [woboq/qmetaobject-rs](https://github.com/woboq/qmetaobject-rs)) - Integrate Qml and Rust by building the QMetaObject at compile time.
* <b><code>&nbsp;&nbsp;1211⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Ribir](https://github.com/RibirX/Ribir)) - Ribir is a Rust GUI framework that helps you build beautiful and native multi-platform applications from a single codebase.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [rise-ui](https://github.com/rise-ui/rise)) - Simple component-based cross-Platform GUI Toolkit for developing beautiful and user-friendly interfaces.
* <b><code>&nbsp;&nbsp;&nbsp;157⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [saurvs/nfd-rs](https://github.com/saurvs/nfd-rs)) - <b><code>&nbsp;&nbsp;1900⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [nativefiledialog](https://github.com/mlabbe/nativefiledialog)) bindings
* 🌎 [Sciter](sciter.com/)
  * <b><code>&nbsp;&nbsp;&nbsp;818⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [sciter-sdk/rust-sciter](https://github.com/sciter-sdk/rust-sciter)) - Sciter bindings [![build badge](https://ci.appveyor.com/api/projects/status/github/sciter-sdk/rust-sciter?svg=true)](https://ci.appveyor.com/project/sciter-sdk/rust-sciter)
* <b><code>&nbsp;20435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;744🍴</code></b> [slint-ui/slint](https://github.com/slint-ui/slint)) 🌎 [slint](crates.io/crates/slint) - 🌎 [Slint](slint.dev/) is a toolkit to efficiently develop fluid graphical user interfaces for embedded devices and desktop applications. [![Build Status](https://github.com/slint-ui/slint/workflows/CI/badge.svg?branch=master)](https://github.com/slint-ui/slint/actions?query=workflow%3ACI)
* <b><code>&nbsp;96851⭐</code></b> <b><code>&nbsp;&nbsp;3074🍴</code></b> [tauri-apps/tauri](https://github.com/tauri-apps/tauri)) - Build smaller, faster, and more secure desktop applications with a web frontend, powered by <b><code>&nbsp;&nbsp;4382⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;365🍴</code></b> [WRY](https://github.com/tauri-apps/wry)). [![test library](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+library%22)
* <b><code>&nbsp;&nbsp;4382⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;365🍴</code></b> [tauri-apps/wry](https://github.com/tauri-apps/wry)) - Webview Rendering librarY.
* <b><code>&nbsp;&nbsp;4546⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [xilem](https://github.com/linebender/xilem)) - Successor of the data-first UI design toolkit <b><code>&nbsp;&nbsp;9695⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;568🍴</code></b> [druid](https://github.com/linebender/druid)).

### Image processing

* <b><code>&nbsp;&nbsp;&nbsp;327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [abonander/img_hash](https://github.com/abonander/img_hash)) - Perceptual image hashing and comparison for equality and similarity.
* <b><code>&nbsp;&nbsp;&nbsp;488⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [Enet4/dicom-rs](https://github.com/Enet4/dicom-rs)) - A pure Rust implementation of the DICOM standard, allowing users to work with DICOM objects and interact with DICOM applications, while aiming to be fast, safe, and intuitive to use.
* <b><code>&nbsp;&nbsp;5467⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;666🍴</code></b> [image-rs/image](https://github.com/image-rs/image)) - Basic imaging processing functions and methods for converting to and from image formats
* <b><code>&nbsp;&nbsp;&nbsp;883⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [image-rs/imageproc](https://github.com/image-rs/imageproc)) - An image processing library, based on the `image` library.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [marekm4/dominant_color](https://github.com/marekm4/dominant_color))  🌎 [dominant_color](crates.io/crates/dominant_color)] - Dominant color extractor ![build badge](https://github.com/marekm4/dominant_color/actions/workflows/rust.yml/badge.svg?branch=master)
* <b><code>&nbsp;&nbsp;&nbsp;956⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [rust-cv/cv](https://github.com/rust-cv/cv)) - Implement computer vision algorithms, abstractions, and systems. `#[no_std]` is supported where possible. ![build badge](https://github.com/rust-cv/cv/workflows/tests/badge.svg)
* <b><code>&nbsp;&nbsp;&nbsp;101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [teovoinea/steganography](https://github.com/teovoinea/steganography))  🌎 [steganography](crates.io/crates/steganography)] - A simple steganography library
* <b><code>&nbsp;&nbsp;2264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust)) - Bindings for OpenCV

### Language specification

* <b><code>&nbsp;&nbsp;&nbsp;281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [shnewto/bnf](https://github.com/shnewto/bnf)) - A library for parsing Backus–Naur form context-free grammars.

### Licensing

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [WyvernIXTL/license-fetcher](https://github.com/WyvernIXTL/license-fetcher))  🌎 [license-fetcher](crates.io/crates/license-fetcher)] - Fetch licenses of dependencies at build time and embed them into your program.

### Logging

 🌎 [log](crates.io/keywords/log)]

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [donnie4w/tklog](https://github.com/donnie4w/tklog "donnie4w/tklog")) - lightweight and efficient rust structured log library with support for log levels, file segmentation, compressed archiving.
* <b><code>&nbsp;&nbsp;1089⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [estk/log4rs](https://github.com/estk/log4rs)) - highly configurable logging framework modeled after Java's Logback and log4j libraries [![CircleCI](https://circleci.com/gh/estk/log4rs.svg?style=shield)](https://app.circleci.com/pipelines/github/estk/log4rs)
* <b><code>&nbsp;&nbsp;&nbsp;265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [rbatis/fast_log](https://github.com/rbatis/fast_log)) - Async log High-performance asynchronous logging
* <b><code>&nbsp;&nbsp;2408⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;273🍴</code></b> [rust-lang/log](https://github.com/rust-lang/log)) - Logging implementation
* <b><code>&nbsp;&nbsp;&nbsp;504⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [seanmonstar/pretty-env-logger](https://github.com/seanmonstar/pretty-env-logger)) - A pretty, easy-to-use logger.
* <b><code>&nbsp;&nbsp;1661⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [slog-rs/slog](https://github.com/slog-rs/slog)) - Structured, composable logging
* <b><code>&nbsp;&nbsp;6221⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;827🍴</code></b> [tokio-rs/tracing](https://github.com/tokio-rs/tracing)) - An application level tracing framework for async-aware structured logging, error handling, metrics, and more [![Build Status](https://github.com/tokio-rs/tracing/workflows/CI/badge.svg?branch=master)](https://github.com/tokio-rs/tracing/actions?query=workflow%3ACI)

### Macro

* cute
  * <b><code>&nbsp;&nbsp;&nbsp;341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [mattgathu/cute](https://github.com/mattgathu/cute)) - Macro for Python-esque list comprehensions.
* <b><code>&nbsp;&nbsp;1803⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [elastio/bon](https://github.com/elastio/bon))  🌎 [bon](crates.io/crates/bon)] - generate compile-time-checked builders for structs and functions, provides partial application, optional and named parameters for functions and methods. [![build status](https://github.com/elastio/bon/actions/workflows/ci.yml/badge.svg)](https://github.com/elastio/bon/actions)
* <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Linq-in-Rust](https://github.com/StardustDL/Linq-in-Rust)) - Macro and methods for C#-LINQ-like expressions. [![CI](https://github.com/StardustDL/Linq-in-Rust/workflows/CI/badge.svg?branch=master)](https://github.com/StardustDL/Linq-in-Rust/actions?query=workflow%3ACI)

### Markup language

* CommonMark
  * <b><code>&nbsp;&nbsp;2350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;258🍴</code></b> [pulldown-cmark/pulldown-cmark](https://github.com/pulldown-cmark/pulldown-cmark)) - 🌎 [CommonMark](commonmark.org/) parser
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [insomnimus/tidier](https://github.com/insomnimus/tidier))  🌎 [tidier](crates.io/crates/tidier)] - A library to format HTML, XHTML and XML documents. [![build badge](https://github.com/insomnimus/tidier/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/tidier/actions)

### Mobile

* Android / iOS
  * <b><code>&nbsp;&nbsp;&nbsp;250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [ivnsch/rust_android_ios](https://github.com/ivnsch/rust_android_ios)) - An example of using a shared lib for Android and iOS using rust-swig and cbindgen respectively.
* Generic
  * <b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Geal/rust_on_mobile](https://github.com/Geal/rust_on_mobile)) - iOS CocoaPods / Android JNI
  * <b><code>&nbsp;&nbsp;2088⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [redbadger/crux](https://github.com/redbadger/crux))  🌎 [crux_core](crates.io/crates/crux_core)] - Cross-platform app development. Crux helps you share your app's business logic and behavior across mobile (iOS/Android) and web - as a single reusable core. [![Build status](https://img.shields.io/github/actions/workflow/status/redbadger/crux/build.yaml)](https://github.com/redbadger/crux/actions)
* iOS
  * <b><code>&nbsp;&nbsp;&nbsp;557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo)) - A cargo lipo subcommand which automatically creates a universal library for use with your iOS application.

### Network programming

* Bluetooth
  * <b><code>&nbsp;&nbsp;&nbsp;382⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [bluez/bluer](https://github.com/bluez/bluer))  🌎 [bluer](crates.io/crates/bluer)] - Official BlueZ bindings. [![build badge](https://github.com/bluez/bluer/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/bluez/bluer/actions/workflows/rust.yml)
* CoAP
  * <b><code>&nbsp;&nbsp;&nbsp;219⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [Covertness/coap-rs](https://github.com/Covertness/coap-rs)) - A 🌎 [Constrained Application Protocol(CoAP)](datatracker.ietf.org/doc/html/rfc7252) library.
* Docker
  * <b><code>&nbsp;&nbsp;1114⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;153🍴</code></b> [fussybeaver/bollard](https://github.com/fussybeaver/bollard)) - Docker daemon API
* FTP
  * <b><code>&nbsp;&nbsp;&nbsp;189⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [mattnenterprise/rust-ftp](https://github.com/mattnenterprise/rust-ftp)) - an 🌎 [FTP](en.wikipedia.org/wiki/File_Transfer_Protocol) client
* gRPC
  * <b><code>&nbsp;11365⭐</code></b> <b><code>&nbsp;&nbsp;1135🍴</code></b> [hyperium/tonic](https://github.com/hyperium/tonic)) - A native gRPC client & server implementation with async/await support [![Crates.io](https://img.shields.io/crates/v/tonic)](https://crates.io/crates/tonic)
  * <b><code>&nbsp;&nbsp;1842⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;259🍴</code></b> [tikv/grpc-rs](https://github.com/tikv/grpc-rs)) - The gRPC library built on C Core library and futures
* HTTP
  * <b><code>&nbsp;17753⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;692🍴</code></b> [Hurl](https://github.com/Orange-OpenSource/hurl)) - Run and test HTTP requests with plain text and libcurl [![CI](https://github.com/Orange-OpenSource/hurl/workflows/CI/badge.svg)](https://github.com/Orange-OpenSource/hurl/actions)
* IPNetwork
  * <b><code>&nbsp;&nbsp;&nbsp;133⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [achanda/ipnetwork](https://github.com/achanda/ipnetwork)) - A library to work with IP networks
  * <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [candrew/netsim](https://github.com/canndrew/netsim)) - A library for network simulation and testing
* Low level
  * <b><code>&nbsp;&nbsp;9020⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;662🍴</code></b> [actix/actix](https://github.com/actix/actix)) - Actor library
  * <b><code>&nbsp;&nbsp;&nbsp;195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [dylanmckay/protocol](https://github.com/dylanmckay/protocol)) - Custom TCP/UDP protocol definitions
  * <b><code>&nbsp;&nbsp;2499⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;315🍴</code></b> [libpnet/libpnet](https://github.com/libpnet/libpnet)) - A cross-platform, low level networking
  * <b><code>&nbsp;&nbsp;4183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;482🍴</code></b> [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp)) - A standalone, event-driven TCP/IP stack that is designed for bare-metal, real-time systems
* message-io
  * <b><code>&nbsp;&nbsp;1179⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [lemunozm/message-io](https://github.com/lemunozm/message-io)) - Event-driven message library to build network applications easy and fast. Supports TCP, UDP and WebSockets. [![build badge](https://img.shields.io/github/workflow/status/lemunozm/message-io/message-io%20ci)](https://github.com/lemunozm/message-io/actions?query=workflow%3A%22message-io+ci%22)
* MQTT
  * <b><code>&nbsp;&nbsp;1932⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;294🍴</code></b> [bytebeamio/rumqtt](https://github.com/bytebeamio/rumqtt)) - A library for developers to build applications that communicate with the 🌎 [MQTT protocol](mqtt.org) over TCP and WebSockets, with or without TLS. [![Build and Test](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml/badge.svg)](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml)
  * <b><code>&nbsp;&nbsp;&nbsp;791⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [rmqtt/rmqtt](https://github.com/rmqtt/rmqtt)) - MQTT Server/MQTT Broker - Scalable Distributed MQTT Message Broker for IoT in the 5G Era
* NanoMsg
  * <b><code>&nbsp;&nbsp;&nbsp;399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs)) - 🌎 [nanomsg](nanomsg.org/) bindings
* NATS
  * <b><code>&nbsp;&nbsp;1285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;213🍴</code></b> [nats-io/nats.rs](https://github.com/nats-io/nats.rs)) - Client for NATS, the cloud native messaging system. [![Build Status](https://github.com/nats-io/nats.rs/workflows/Rust/badge.svg?branch=master)](https://github.com/nats-io/nats.rs/actions)
* Nng
  * 🌎 [neachdainn/nng-rs](gitlab.com/neachdainn/nng-rs)  🌎 [Nng](crates.io/crates/nng)] - 🌎 [Nng (nanomsg v2)](nng.nanomsg.org/index.html) bindings [![build badge](https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg)](https://gitlab.com/neachdainn/nng-rs/-/pipelines)
* NNTP
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [mattnenterprise/rust-nntp](https://github.com/mattnenterprise/rust-nntp))  🌎 [nntp](crates.io/crates/nntp)] - an 🌎 [NNTP](en.wikipedia.org/wiki/Network_News_Transfer_Protocol) client
* P2P
  * <b><code>&nbsp;&nbsp;5200⭐</code></b> <b><code>&nbsp;&nbsp;1125🍴</code></b> [libp2p/rust-libp2p](https://github.com/libp2p/rust-libp2p)) - Implementation of libp2p networking stack. [![Circle CI](https://circleci.com/gh/libp2p/rust-libp2p.svg?style=svg)](https://app.circleci.com/pipelines/github/libp2p/rust-libp2p)
  * <b><code>&nbsp;&nbsp;6935⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;299🍴</code></b> [n0-computer/iroh](https://github.com/n0-computer/iroh))  🌎 [iroh](crates.io/crates/iroh)] - crate for building on direct connections between devices [![CI](https://github.com/n0-computer/iroh/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/n0-computer/iroh/actions/workflows/ci.yml)
* POP3
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [mattnenterprise/rust-pop3](https://github.com/mattnenterprise/rust-pop3))  🌎 [pop3](crates.io/crates/pop3)] - A 🌎 [POP3](en.wikipedia.org/wiki/Post_Office_Protocol) client
* QUIC
  * <b><code>&nbsp;&nbsp;1281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;147🍴</code></b> [aws/s2n-quic](https://github.com/aws/s2n-quic)) - An implementation of the IETF QUIC protocol ![ci](https://img.shields.io/github/actions/workflow/status/aws/s2n-quic/ci.yml?branch=main)
  * <b><code>&nbsp;10582⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;863🍴</code></b> [cloudflare/quiche](https://github.com/cloudflare/quiche)) - cloudflare implementation of the QUIC transport protocol and HTTP/3 ![build](https://img.shields.io/github/actions/workflow/status/cloudflare/quiche/stable.yml?branch=master)
  * <b><code>&nbsp;&nbsp;2036⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;139🍴</code></b> [mozilla/neqo](https://github.com/mozilla/neqo)) - an Implementation of QUIC
  * <b><code>&nbsp;&nbsp;4537⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;468🍴</code></b> [quinn-rs/quinn](https://github.com/quinn-rs/quinn)) - Futures-based QUIC implementation [![build badge](https://dev.azure.com/dochtman/Projects/_apis/build/status/Quinn?branchName=master)](https://dev.azure.com/dochtman/Projects/_build)
  * <b><code>&nbsp;&nbsp;1319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;135🍴</code></b> [tencent/tquic](https://github.com/Tencent/tquic)) - A high-performance, lightweight, and cross-platform QUIC library [![Build Status](https://img.shields.io/github/actions/workflow/status/tencent/tquic/rust.yml)](https://github.com/Tencent/tquic/actions/workflows/rust.yml)
* Raknet
  * <b><code>&nbsp;&nbsp;&nbsp;224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [b23r0/rust-raknet](https://github.com/b23r0/rust-raknet)) - RakNet Protocol implementation [![Build Status](https://img.shields.io/github/workflow/status/b23r0/rust-raknet/Rust)](https://github.com/b23r0/rust-raknet/actions/workflows/rust.yml)
* RPC
  * <b><code>&nbsp;&nbsp;&nbsp;202⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [ENQT-GmbH/remoc](https://github.com/ENQT-GmbH/remoc))  🌎 [remoc](crates.io/crates/remoc)] - Remoc provides channels (broadcast, mpsc, oneshot, watch) similar to Tokio's and trait calling over any remote transport. [![build badge](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml)
  * <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [smallnest/rpcx-rs](https://github.com/smallnest/rpcx-rs)) - A RPC library for developing microservices in easy and simple way.
* SIP
  * <b><code>&nbsp;&nbsp;&nbsp;110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [restsend/rsipstack](https://github.com/restsend/rsipstack)) - A RFC 3261 compliant SIP stack
* Socket.io
  * <b><code>&nbsp;&nbsp;&nbsp;461⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [1c3t3a/rust-socketio](https://github.com/1c3t3a/rust-socketio))  🌎 [rust_socketio](crates.io/crates/rust_socketio)] - an implementation of a 🌎 [socket.io](socket.io) client written in Rust. [![build badge](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml/badge.svg)](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml)
* SSH
  * <b><code>&nbsp;&nbsp;&nbsp;539⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs)) - 🌎 [libssh2](libssh2.org/) bindings
  * 🌎 [Thrussh](pijul.org/thrussh)  🌎 [thrussh](crates.io/crates/thrussh)] - an SSH library, backed by 🌎 [libsodium](doc.libsodium.org/)
* Stomp
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs)) - A [STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html) client implementation
* VPN
  * <b><code>&nbsp;&nbsp;&nbsp;230⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [defguard/wireguard-rs](https://github.com/DefGuard/wireguard-rs)) - A multi-platform library providing a unified high-level API for managing WireGuard interfaces using native OS kernel and userspace WireGuard protocol implementations
* Zenoh
  * <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [eclipse-zenoh-flow/zenoh-flow](https://github.com/eclipse-zenoh-flow/zenoh-flow)) - A declarative framework for computations that span from the *Cloud* to the *Thing*
  * <b><code>&nbsp;&nbsp;2084⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [eclipse-zenoh/zenoh](https://github.com/eclipse-zenoh/zenoh)) - Zero Overhead Network Protocol
* ZeroMQ
  * <b><code>&nbsp;&nbsp;&nbsp;969⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;205🍴</code></b> [erickt/rust-zmq](https://github.com/erickt/rust-zmq)) - 🌎 [ZeroMQ](zeromq.org/) bindings

### Parsing

  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [0xlane/pe-sign](https://github.com/0xlane/pe-sign)) [[pe-sign]](https://crates.io/crates/pe-sign) - A cross-platform rust no-std library for verifying and extracting signature information from PE files. [![crates.io](https://img.shields.io/crates/v/pe-sign)](https://crates.io/crates/pe-sign) [![build](https://github.com/0xlane/pe-sign/actions/workflows/rust.yml/badge.svg)](https://github.com/0xlane/pe-sign/actions/workflows/rust.yml)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [cchexcode/wavefront_rs](https://github.com/cchexcode/wavefront_rs)) - A parser for the Wavefront OBJ format. [![crates.io](https://img.shields.io/crates/v/wavefront_rs.svg)](https://crates.io/crates/wavefront_rs) [![crates.io](https://img.shields.io/crates/d/wavefront_rs?label=crates.io%20downloads)](https://crates.io/crates/wavefront_rs) [![build badge](https://github.com/cchexcode/wavefront_rs/workflows/pipeline/badge.svg?branch=master)](https://github.com/cchexcode/wavefront_rs/actions)
  * <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [comex/rust-shlex](https://github.com/comex/rust-shlex))  🌎 [shlex](crates.io/crates/shlex)] - Split a string into shell words, like Python's shlex. [![build badge](https://github.com/comex/rust-shlex/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/comex/rust-shlex/actions/workflows/test.yml)
  * <b><code>&nbsp;&nbsp;&nbsp;473⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Eliah-Lakhin/lady-deirdre](https://github.com/Eliah-Lakhin/lady-deirdre)) - A framework for new programming languages and LSP servers.
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Folyd/robotstxt](https://github.com/Folyd/robotstxt)) - Port of Google's robots.txt parser and matcher C++ library
  * <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [freestrings/jsonpath](https://github.com/freestrings/jsonpath)) - 🌎 [JsonPath](goessner.net/articles/JsonPath/) engine. Webassembly and Javascript support too
  * 🌎 [hmeyer/stl_io](crates.io/crates/stl_io) - A parser for STL (STereoLithography) files
  * <b><code>&nbsp;&nbsp;&nbsp;396⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [igumnoff/shiva](https://github.com/igumnoff/shiva)) - Shiva library: Implementation in Rust of a parser and generator for documents of any type (Plain text, Markdown, HTML, PDF and etc)
  * <b><code>&nbsp;&nbsp;1556⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg)) - Parsing Expression Grammar (PEG) parser generator
  * <b><code>&nbsp;&nbsp;3350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;300🍴</code></b> [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop)) - LR(1) parser generator
  * <b><code>&nbsp;&nbsp;&nbsp;244⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [m4rw3r/chomp](https://github.com/m4rw3r/chomp)) - A fast monadic-style parser combinator
  * <b><code>&nbsp;&nbsp;1335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [Marwes/combine](https://github.com/Marwes/combine)) - parser combinator library
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [nrc/zero](https://github.com/nrc/zero))  🌎 [zero](crates.io/crates/zero/)] - zero-allocation parsing of binary data
  * <b><code>&nbsp;&nbsp;5109⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;278🍴</code></b> [pest-parser/pest](https://github.com/pest-parser/pest)) - The Elegant Parser
  * <b><code>&nbsp;&nbsp;&nbsp;143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [ptal/oak](https://github.com/ptal/oak)) - A typed PEG parser generator (compiler plugin)
  * <b><code>&nbsp;10102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;836🍴</code></b> [rust-bakery/nom](https://github.com/rust-bakery/nom)) - parser combinator library
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [s-panferov/queryst](https://github.com/s-panferov/queryst)) - A query string parsing library inspired by <b><code>&nbsp;&nbsp;8804⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;743🍴</code></b> [gs](https://github.com/ljharb/qs#readme))
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [softdevteam/grmtools](https://github.com/softdevteam/grmtools/)) - A LR parser with better error correction
  * <b><code>&nbsp;22139⭐</code></b> <b><code>&nbsp;&nbsp;2082🍴</code></b> [tree-sitter/tree-sitter](https://github.com/tree-sitter/tree-sitter)) - A parser generator tool and an incremental parsing library geared towards programming tools

### Peripherals

* Fingerprint reader
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [alvaroparker/libfprint-rs](https://github.com/alvaroparker/libfprint-rs))  🌎 [libfprint-rs](crates.io/crates/libfprint-rs)] - Libfprint-rs provides a wrapper around the Linux libfprint library.
* Serial Port
  * <b><code>&nbsp;&nbsp;&nbsp;637⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [serialport/serialport-rs](https://github.com/serialport/serialport-rs))  🌎 [serialport](crates.io/crates/serialport)] - A cross-platform library that provides access to a serial port

### Platform specific

* Cross-platform
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [iddm/thread-priority](https://github.com/iddm/thread-priority/)) - Simple, crossplatform thread priority management. [![CI](https://github.com/iddm/thread-priority/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/thread-priority/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/thread-priority.svg)](https://crates.io/crates/thread-priority)
  * 🌎 [svartalf/rust-battery](crates.io/crates/battery) - Cross-platform information about the notebook batteries
* FreeBSD
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/))  🌎 [jail](crates.io/crates/jail)] - FreeBSD jail library
* Linux
  * <b><code>&nbsp;&nbsp;&nbsp;276⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [hannobraun/inotify-rs](https://github.com/hannobraun/inotify-rs)) - 🌎 [inotify](en.wikipedia.org/wiki/Inotify) bindings [![Rust](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [pop-os/distinst](https://github.com/pop-os/distinst/)) - Linux distribution installer
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [yaa110/rust-iptables](https://github.com/yaa110/rust-iptables))  🌎 [iptables](crates.io/crates/iptables)] - 🌎 [iptables](www.netfilter.org/projects/iptables/index.html) bindings
* Unix-like
  * <b><code>&nbsp;&nbsp;2897⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;714🍴</code></b> [nix-rust/nix](https://github.com/nix-rust/nix)) - Unix-like API bindings [![Cirrus Build Status](https://api.cirrus-ci.com/github/nix-rust/nix.svg)](https://cirrus-ci.com/github/nix-rust/nix)
  * <b><code>&nbsp;&nbsp;1775⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [rustix](https://github.com/bytecodealliance/rustix)) - Safe bindings to POSIX/Unix/Linux/Winsock2 syscalls [![Actions Status](https://github.com/bytecodealliance/rustix/workflows/CI/badge.svg)](https://github.com/bytecodealliance/rustix/actions?query=workflow%3ACI)
  * <b><code>&nbsp;&nbsp;1112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [zargony/fuse-rs](https://github.com/zargony/fuse-rs)) - <b><code>&nbsp;&nbsp;5763⭐</code></b> <b><code>&nbsp;&nbsp;1218🍴</code></b> [FUSE](https://github.com/libfuse/libfuse)) bindings
* Windows
  * <b><code>&nbsp;11597⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;582🍴</code></b> [microsoft/windows-rs](https://github.com/microsoft/windows-rs)) - Rust for Windows [![Actions Status](https://github.com/microsoft/windows-rs/workflows/CI/badge.svg)](https://github.com/microsoft/windows-rs/actions)
  * <b><code>&nbsp;&nbsp;1908⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;394🍴</code></b> [retep998/winapi-rs](https://github.com/retep998/winapi-rs)) - Windows API bindings [![Rust](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml/badge.svg?branch=dev)](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml)

### Reverse engineering

* <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [binarly-io/idalib](https://github.com/binarly-io/idalib))  🌎 [idalib](crates.io/crates/idalib)] - Rust bindings for the IDA SDK, enabling the development of standalone analysis tools using IDA v9.0’s idalib
* <b><code>&nbsp;&nbsp;&nbsp;291⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [objdiff](https://github.com/encounter/objdiff)) - A local diffing tool for decompilation projects

### Scripting

 🌎 [scripting](crates.io/keywords/scripting)]

* <b><code>&nbsp;&nbsp;&nbsp;183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [3body-lang](https://github.com/rustq/3body-lang)) - The Three Body Language
* <b><code>&nbsp;&nbsp;&nbsp;496⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [cel-rust](https://github.com/cel-rust/cel-rust))  🌎 [cel-interpreter](crates.io/crates/cel-interpreter)] - Common expression language parser and interpreter
* 🌎 [duckscript](crates.io/crates/duckscript) - <b><code>&nbsp;&nbsp;&nbsp;565⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Simple, extendable and embeddable scripting language.](https://github.com/sagiegurari/duckscript)) [![build badge](https://github.com/sagiegurari/duckscript/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/duckscript/actions)
* <b><code>&nbsp;&nbsp;&nbsp;861⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [facebook/starlark-rust](https://github.com/facebook/starlark-rust)) - A small, deterministic, thread-safe language with Python syntax
* <b><code>&nbsp;&nbsp;&nbsp;397⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [fleabitdev/gamelisp](https://github.com/fleabitdev/glsp)) - A Lisp-like scripting language for game development
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [giraffekey/xylo](https://github.com/giraffekey/xylo))  🌎 [xylo-lang](crates.io/crates/xylo-lang)] - A functional programming language for procedural art. [![build badge](https://github.com/giraffekey/xylo/actions/workflows/rust.yml/badge.svg)](https://github.com/giraffekey/xylo/actions)
* <b><code>&nbsp;&nbsp;3344⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;153🍴</code></b> [gluon-lang/gluon](https://github.com/gluon-lang/gluon)) - A small, statically-typed, functional programming language
* <b><code>&nbsp;&nbsp;2168⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [kcl](https://github.com/kcl-lang/kcl)) - A constraint-based record & functional language mainly used in configuration and policy scenarios.
* <b><code>&nbsp;&nbsp;1702⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [metacall/core](https://github.com/metacall/core))  🌎 [metacall](crates.io/crates/metacall)] - Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, Wasm, Java, Cobol and more. [![build badge](https://gitlab.com/metacall/core/badges/master/pipeline.svg)](https://gitlab.com/metacall/core)
* <b><code>&nbsp;&nbsp;2092⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [mun](https://github.com/mun-lang/mun)) - A compiled, statically-typed scripting language with first class hot reloading support
* <b><code>&nbsp;&nbsp;&nbsp;757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [murarth/ketos](https://github.com/murarth/ketos)) - A Lisp dialect functional programming language serving as a scripting and extension language for rust
* <b><code>&nbsp;&nbsp;1865⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon)) - A rusty dynamically typed scripting language
* <b><code>&nbsp;&nbsp;4898⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [rhaiscript/rhai](https://github.com/rhaiscript/rhai)) - A tiny and fast embedded scripting language resembling a combination of JavaScript and Rust [![build badge](https://github.com/rhaiscript/rhai/workflows/Build/badge.svg)](https://github.com/rhaiscript/rhai/actions)
* <b><code>&nbsp;&nbsp;2047⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [rune-rs/rune](https://github.com/rune-rs/rune)) - An embeddable dynamic programming language
* <b><code>&nbsp;&nbsp;1706⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [trynova/nova](https://github.com/trynova/nova)) - JavaScript engine written entirely in Rust

### Simulation

 🌎 [simulation](crates.io/keywords/simulation)]

* 🌎 [nyx-space](crates.io/crates/nyx-space) - High fidelity, fast, reliable and validated astrodynamical toolkit library, used for spacecraft mission design and orbit determination [![Build Status](https://gitlab.com/nyx-space/nyx/badges/master/pipeline.svg)](https://gitlab.com/nyx-space/nyx/-/pipelines)

### Social networks

* Telegram
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [tdilb-rs](https://github.com/FedericoBruzzone/tdlib-rs))  🌎 [tdilb-rs](crates.io/crates/tdlib-rs)] - Crossplatform Rust wrapper around the Telegram Database Library (TDLib) [![CI Linux](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-linux.yml/badge.svg)](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-linux.yml) [![CI macOS](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-macos.yml/badge.svg)](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-macos.yml) [![CI Windows](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-windows.yml/badge.svg)](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-windows.yml)

### System

* <b><code>&nbsp;&nbsp;&nbsp;242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [ardaku/whoami](https://github.com/ardaku/whoami))  🌎 [whoami](crates.io/crates/whoami)] - crate to get the current user and environment. [![build badge](https://github.com/ardaku/whoami/actions/workflows/ci.yml/badge.svg?branch=stable)](https://github.com/ardaku/whoami/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;2548⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;367🍴</code></b> [GuillaumeGomez/sysinfo](https://github.com/GuillaumeGomez/sysinfo))  🌎 [sysinfo](crates.io/crates/sysinfo)] - Cross-platform library to fetch system information [![build badge](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml/badge.svg?branch=master)](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [navidys/procsys](https://github.com/navidys/procsys))  🌎 [procsys](crates.io/crates/procsys)] - A library to retrieve system, kernel, and process metrics from the pseudo-filesystems /proc and /sys.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Phate6660/nixinfo](https://github.com/Phate6660/nixinfo))  🌎 [nixinfo](crates.io/crates/nixinfo)] - A lib crate for gathering system info such as cpu, distro, environment, kernel, etc.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [sorairolake/sysexits-rs](https://github.com/sorairolake/sysexits-rs))  🌎 [sysexits](crates.io/crates/sysexits)] - The system exit codes as defined by 🌎 [`<sysexits.h>`](man.openbsd.org/sysexits). [![CI](https://github.com/sorairolake/sysexits-rs/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/sysexits-rs/actions?query=workflow%3ACI)

### Task scheduling

* <b><code>&nbsp;&nbsp;&nbsp;331⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [delay-timer](https://github.com/BinChengZhao/delay-timer)) - Time-manager of delayed tasks. Like crontab, but asynchronous tasks are possible. [![Build](https://github.com/BinChengZhao/delay-timer/actions/workflows/rust.yml/badge.svg)]( https://github.com/BinChengZhao/delay-timer/actions)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [persistent-scheduler](https://github.com/rustmailer/persistent-scheduler))  🌎 [persistent-scheduler](crates.io/crates/persistent-scheduler)] - A high-performance task scheduling system built with Tokio, offering task persistence, repeatable tasks, and Cron-based scheduling for reliable time-based operations.

### Template engine

* Handlebars
  * <b><code>&nbsp;&nbsp;1416⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;153🍴</code></b> [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust)) - Handlebars template engine with inheritance, custom helper support.
  * <b><code>&nbsp;&nbsp;&nbsp;282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [zzau13/yarte](https://github.com/zzau13/yarte)) - Yarte stands for **Y**et **A**nother **R**ust **T**emplate **E**ngine, is the fastest template engine.
* HTML
  * <b><code>&nbsp;&nbsp;&nbsp;767⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [askama](https://github.com/askama-rs/askama)) - template rendering engine based on Jinja
  * <b><code>&nbsp;&nbsp;&nbsp;457⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [kaj/ructe](https://github.com/kaj/ructe)) - HTML template system
  * <b><code>&nbsp;&nbsp;3975⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [Keats/tera](https://github.com/Keats/tera)) - template engine based on Jinja2 and the Django template language. [![Actions Status](https://github.com/Keats/tera/workflows/ci/badge.svg?branch=master)](https://github.com/Keats/tera/actions)
  * <b><code>&nbsp;&nbsp;2450⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;164🍴</code></b> [lambda-fairy/maud](https://github.com/lambda-fairy/maud)) - compile-time HTML templates
  * <b><code>&nbsp;&nbsp;&nbsp;337⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Stebalien/horrorshow-rs](https://github.com/Stebalien/horrorshow-rs)) - compile-time HTML templates
* Mustache
  * <b><code>&nbsp;&nbsp;&nbsp;214⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [rustache/rustache](https://github.com/rustache/rustache)) - a Rust implementation of the Mustache spec

### Text processing

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [becheran/wildmatch](https://github.com/becheran/wildmatch))  🌎 [wildmatch](crates.io/crates/wildmatch)] - Simple string matching with questionmark- and star-wildcard operator [![Actions Status](https://github.com/becheran/wildmatch/workflows/Build/badge.svg?branch=master)](https://github.com/becheran/wildmatch/actions)
* <b><code>&nbsp;&nbsp;&nbsp;275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [BurntSushi/suffix](https://github.com/BurntSushi/suffix)) - Linear time suffix array construction (with Unicode support)
* <b><code>&nbsp;&nbsp;&nbsp;267⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter)) - Elastic tab stops (i.e., text column alignment)
* <b><code>&nbsp;&nbsp;&nbsp;149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [cpc](https://github.com/probablykasper/cpc)) - Parses and calculates strings of math with support for units and unit conversion, from `1+2` to `1% of round(1 lightyear / 14!s to km/h)`.
* <b><code>&nbsp;&nbsp;&nbsp;108⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Daniel-Liu-c0deb0t/triple_accel](https://github.com/Daniel-Liu-c0deb0t/triple_accel))  🌎 [triple_accel](crates.io/crates/triple_accel)] - Rust edit distance routines accelerated using SIMD; supports fast Hamming, Levenshtein, restricted Damerau-Levenshtein, etc. distance calculations and string search [![build badge](https://github.com/Daniel-Liu-c0deb0t/triple_accel/workflows/Test/badge.svg?branch=master)](https://github.com/Daniel-Liu-c0deb0t/triple_accel/actions)
* <b><code>&nbsp;&nbsp;&nbsp;510⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [fancy-regex/fancy-regex](https://github.com/fancy-regex/fancy-regex))  🌎 [fancy-regex](crates.io/crates/fancy-regex)] - Regular expressions implementation designed to support a relatively rich set of features such as look-around and backtracking. [![crates](https://img.shields.io/crates/v/fancy-regex.svg)](https://crates.io/crates/fancy-regex) [![build badge](https://github.com/fancy-regex/fancy-regex/workflows/ci/badge.svg)](https://github.com/fancy-regex/fancy-regex/actions/workflows/ci.yml)
* <b><code>&nbsp;&nbsp;1040⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs)) - Natural language detection library based on trigrams
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Lucretiel/joinery](https://github.com/Lucretiel/joinery))  🌎 [joinery](crates.io/crates/joinery)] - Generic string + iterable joining
* <b><code>&nbsp;&nbsp;&nbsp;507⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [mgeisler/textwrap](https://github.com/mgeisler/textwrap))  🌎 [textwrap](crates.io/crates/textwrap)] - Word wrap text (with support for hyphenation)
* <b><code>&nbsp;&nbsp;&nbsp;121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [null8626/decancer](https://github.com/null8626/decancer))  🌎 [decancer](crates.io/crates/decancer)] - A tiny package that removes common unicode confusables/homoglyphs from strings. [![crates](https://img.shields.io/crates/v/decancer.svg)](https://crates.io/crates/decancer) [![build badge](https://github.com/null8626/decancer/workflows/CI/badge.svg)](https://github.com/null8626/decancer/actions/workflows/CI.yml)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [ps1dr3x/easy_reader](https://github.com/ps1dr3x/easy_reader)) - A reader that allows forwards, backwards and random navigations through the lines of huge files without consuming iterators
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [pwoolcoc/ngrams](https://github.com/pwoolcoc/ngrams))  🌎 [ngrams](crates.io/crates/ngrams)] - Construct 🌎 [n-grams](en.wikipedia.org/wiki/N-gram) from arbitrary iterators
* <b><code>&nbsp;&nbsp;3795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;482🍴</code></b> [rust-lang/regex](https://github.com/rust-lang/regex)) - Regular expressions (RE2 style)
* 🌎 [strsim-rs](crates.io/crates/strsim) - String similarity metrics
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [yaa110/rake-rs](https://github.com/yaa110/rake-rs))  🌎 [rake](crates.io/crates/rake)] - Multilingual implementation of RAKE algorithm for Rust

### Text search

* <b><code>&nbsp;&nbsp;&nbsp;179⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [andylokandy/simsearch-rs](https://github.com/andylokandy/simsearch-rs))  🌎 [simsearch](crates.io/crates/simsearch)] - A simple and lightweight fuzzy search engine that works in memory, searching for similar strings
* <b><code>&nbsp;&nbsp;1959⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [BurntSushi/fst](https://github.com/BurntSushi/fst))  🌎 [fst](crates.io/crates/fst)] - a fast implementation of ordered sets and maps using finite state machines
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [CurrySoftware/perlin](https://github.com/CurrySoftware/perlin))  🌎 [perlin](crates.io/crates/perlin)] - A lazy, zero-allocation and data-agnostic Information Retrieval library
* <b><code>&nbsp;53367⭐</code></b> <b><code>&nbsp;&nbsp;2186🍴</code></b> [meilisearch/MeiliSearch](https://github.com/meilisearch/MeiliSearch)) - Ultra relevant, instant and typo-tolerant full-text search API. [![Build Status](https://github.com/meilisearch/MeiliSearch/workflows/Cargo%20test/badge.svg?branch=master)](https://github.com/meilisearch/MeiliSearch/actions)
* <b><code>&nbsp;&nbsp;7795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;279🍴</code></b> [pg_search](https://github.com/paradedb/paradedb/tree/dev/pg_search)) - PostgreSQL extension that enables full-text search over SQL tables using the BM25 algorithm, the state-of-the-art ranking function for full-text search.
* <b><code>&nbsp;&nbsp;1739⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [SeekStorm](https://github.com/SeekStorm/SeekStorm))  🌎 [SeekStorm](crates.io/crates/seekstorm)] - sub-millisecond full-text search library & multi-tenancy server in Rust
* <b><code>&nbsp;13786⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;807🍴</code></b> [tantivy](https://github.com/quickwit-oss/tantivy))  🌎 [tantivy](crates.io/crates/tantivy)] - A horse-speed full-text search engine library written in Rust. [![Build Status](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml/badge.svg)](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml)

### Unsafe

* 🌎 [zerocopy](crates.io/crates/zerocopy) - "Zerocopy makes zero-cost memory manipulation effortless. We write `unsafe` so you don’t have to."

### Video

* <b><code>&nbsp;&nbsp;&nbsp;464⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [ffmpeg-sidecar](https://github.com/nathanbabcock/ffmpeg-sidecar)) - Wrap a standalone FFmpeg binary in an intuitive Iterator interface. [![Build Status](https://github.com/nathanbabcock/ffmpeg-sidecar/actions/workflows/ci.yml/badge.svg)](https://github.com/nathanbabcock/ffmpeg-sidecar/actions)

### Virtualization

* <b><code>&nbsp;&nbsp;&nbsp;282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [beneills/quantum](https://github.com/beneills/quantum)) - Advanced quantum computer simulator
* <b><code>&nbsp;16935⭐</code></b> <b><code>&nbsp;&nbsp;1512🍴</code></b> [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime)) - A standalone runtime for WebAssembly [![Build Status](https://github.com/bytecodealliance/wasmtime/workflows/CI/badge.svg)](https://github.com/bytecodealliance/wasmtime/actions?query=workflow%3ACI)
* 🌎 [chromium/chromiumos/platform/crosvm](chromium.googlesource.com/chromiumos/platform/crosvm/) - CrOSVM Enables Chrome OS to run Linux apps inside a fast, secure virtualized environment
* <b><code>&nbsp;&nbsp;&nbsp;204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [oxidecomputer/propolis](https://github.com/oxidecomputer/propolis)) - Userspace program for illumos bhyve kernel modules
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [saurvs/hypervisor-rs](https://github.com/saurvs/hypervisor-rs)) - Hardware-accelerated virtualization on OS X

### Web programming

See also 🌎 [Are we web yet?](www.arewewebyet.org) and <b><code>&nbsp;&nbsp;5565⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;218🍴</code></b> [Rust web framework comparison](https://github.com/flosse/rust-web-framework-comparison)).

* Client-side / WASM
  * 🌎 [cargo-web](crates.io/crates/cargo-web) - A Cargo subcommand for the client-side Web
  * <b><code>&nbsp;19186⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;793🍴</code></b> [leptos](https://github.com/leptos-rs/leptos)) - Leptos is a full-stack, isomorphic web framework leveraging fine-grained reactivity to build declarative user interfaces.[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/leptos)
  * <b><code>&nbsp;&nbsp;2043⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [sauron](https://github.com/ivanceras/sauron)) - Client side web framework which closely adheres to The Elm Architecture.
  * <b><code>&nbsp;&nbsp;3836⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [seed](https://github.com/seed-rs/seed)) - A framework for creating web apps
  * 🌎 [stdweb](crates.io/crates/stdweb) - A standard library for the client-side Web
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [tinyweb](https://github.com/LiveDuo/tinyweb)) - A minimal Rust web framework for wasm in 800 lines of code
  * 🌎 [yew](crates.io/crates/yew) - A framework for making client web apps
* HTTP Client
  * <b><code>&nbsp;&nbsp;&nbsp;460⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [0x676e67/wreq](https://github.com/0x676e67/wreq)) - An ergonomic Rust HTTP Client with TLS fingerprint. [![CI](https://github.com/0x676e67/wreq/actions/workflows/ci.yml/badge.svg)](https://github.com/0x676e67/wreq/actions/workflows/ci.yml) [![crates.io](https://img.shields.io/crates/v/wreq.svg?logo=rust)](https://crates.io/crates/wreq)
  * <b><code>&nbsp;&nbsp;1074⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;250🍴</code></b> [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust)) - 🌎 [libcurl](curl.se/libcurl/) bindings
  * <b><code>&nbsp;&nbsp;3577⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;506🍴</code></b> [async-graphql](https://github.com/async-graphql/async-graphql)) - A GraphQL server library [![Build Status](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_apis/build/status/graphql-rust.juniper)](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_build/latest?definitionId=1)
  * <b><code>&nbsp;&nbsp;&nbsp;314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [c410-f3r/wtx](https://github.com/c410-f3r/wtx)) - HTTP/2 client framework
  * 🌎 [DoumanAsh/yukikaze](gitlab.com/Douman/yukikaze)  🌎 [yukikaze](crates.io/crates/yukikaze)] - Beautiful and elegant Yukikaze is little HTTP client library based on hyper. [![build badge](https://gitlab.com/Douman/yukikaze/badges/master/pipeline.svg)](https://gitlab.com/Douman/yukikaze)
  * <b><code>&nbsp;&nbsp;6891⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [ducaale/xh](https://github.com/ducaale/xh)) - Friendly and fast tool for sending HTTP requests [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/xh) [![GitHub actions Status](https://github.com/ducaale/xh/workflows/CI/badge.svg?branch=master)](https://github.com/ducaale/xh/actions)
  * <b><code>&nbsp;&nbsp;1213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;163🍴</code></b> [graphql-client](https://github.com/graphql-rust/graphql-client)) - Typed, correct GraphQL requests and responses. [![GitHub actions Status](https://github.com/graphql-rust/graphql-client/workflows/CI/badge.svg?branch=master)](https://github.com/graphql-rust/graphql-client/actions)
  * <b><code>&nbsp;15569⭐</code></b> <b><code>&nbsp;&nbsp;1678🍴</code></b> [hyperium/hyper](https://github.com/hyperium/hyper)) - an HTTP implementation [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * <b><code>&nbsp;&nbsp;&nbsp;774⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [plabayo/rama](https://github.com/plabayo/rama)) - A modular service framework to move and transform your network packets, can be used among other things, to build clients with TLS, JA3/JA4, H2 and QUIC/H3 fingerprint impersonation
  * <b><code>&nbsp;11040⭐</code></b> <b><code>&nbsp;&nbsp;1281🍴</code></b> [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest)) - an ergonomic HTTP Client.
* HTTP Server
  * <b><code>&nbsp;23644⭐</code></b> <b><code>&nbsp;&nbsp;1797🍴</code></b> [actix/actix-web](https://github.com/actix/actix-web)) - A lightweight async web framework with websocket support
  * <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Anansi](https://github.com/saru-tora/anansi)) - A simple full-stack web framework
  * 🌎 [branca](crates.io/crates/branca) - Implementation of Branca for Authenticated and Encrypted API tokens.
  * <b><code>&nbsp;&nbsp;&nbsp;314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [c410-f3r/wtx](https://github.com/c410-f3r/wtx)) - Low and high level HTTP/2 server
  * <b><code>&nbsp;&nbsp;&nbsp;982⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [carllerche/tower-web](https://github.com/carllerche/tower-web))  🌎 [tower-web](crates.io/crates/tower-web)] - A fast, boilerplate free, web framework
  * <b><code>&nbsp;&nbsp;&nbsp;822⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Cot](https://github.com/cot-rs/cot)) - The Rust web framework for lazy developers.
  * <b><code>&nbsp;&nbsp;&nbsp;251⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [GildedHonour/frank_jwt](https://github.com/GildedHonour/frank_jwt)) - JSON Web Token implementation.
  * <b><code>&nbsp;&nbsp;2280⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;125🍴</code></b> [Gotham](https://github.com/gotham-rs/gotham)) - A flexible web framework that does not sacrifice safety, security or speed.
  * <b><code>&nbsp;&nbsp;&nbsp;451⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Graphul](https://github.com/graphul-rs/graphul)) - An Express-inspired web framework. [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/graphul)
  * <b><code>&nbsp;&nbsp;1416⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;153🍴</code></b> [handlebars-rust](https://github.com/sunng87/handlebars-rust)) - an Iron web framework middleware.
  * <b><code>&nbsp;15569⭐</code></b> <b><code>&nbsp;&nbsp;1678🍴</code></b> [hyperium/hyper](https://github.com/hyperium/hyper)) - an HTTP implementation [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * <b><code>&nbsp;&nbsp;6126⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;398🍴</code></b> [Iron](https://github.com/iron/iron)) - A middleware-based server framework
  * <b><code>&nbsp;&nbsp;5885⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;440🍴</code></b> [Juniper](https://github.com/graphql-rust/juniper)) - GraphQL server library
  * <b><code>&nbsp;&nbsp;&nbsp;616⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [miketang84/sapper](https://github.com/miketang84/sapper)) - A lightweight web framework built on async hyper.
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Nickel](https://github.com/nickel-org/nickel.rs/)) - inspired by 🌎 [Express](expressjs.com/)
  * <b><code>&nbsp;&nbsp;&nbsp;774⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [plabayo/rama](https://github.com/plabayo/rama)) - A modular service framework to move and transform your network packets, can also be used to fingerprint incoming clients
  * <b><code>&nbsp;&nbsp;4194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;332🍴</code></b> [poem-web/poem](https://github.com/poem-web/poem)) - A full-featured and easy-to-use web framework. [![CI](https://github.com/poem-web/poem/actions/workflows/ci.yml/badge.svg)](https://github.com/poem-web/poem/actions/workflows/ci.yml)
  * <b><code>&nbsp;25390⭐</code></b> <b><code>&nbsp;&nbsp;1612🍴</code></b> [Rocket](https://github.com/rwf2/Rocket)) - Rocket is a web framework with a focus on ease-of-use, expressability, and speed
  * <b><code>&nbsp;&nbsp;&nbsp;620⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Rustless](https://github.com/rustless/rustless)) - A REST-like API micro-framework inspired by <b><code>&nbsp;&nbsp;9963⭐</code></b> <b><code>&nbsp;&nbsp;1230🍴</code></b> [Grape](https://github.com/ruby-grape/grape)) and <b><code>&nbsp;15569⭐</code></b> <b><code>&nbsp;&nbsp;1678🍴</code></b> [Hyper](https://github.com/hyperium/hyper))
  * <b><code>&nbsp;&nbsp;3880⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;238🍴</code></b> [Salvo](https://github.com/salvo-rs/salvo)) - an easy to use webframework base on hyper and tokio. [![build build](https://github.com/salvo-rs/salvo/actions/workflows/release.yml/badge.svg)](https://github.com/salvo-rs/salvo/actions)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Saphir](https://github.com/richerarc/saphir)) - A progressive web framework with low-level control, without the pain.
  * <b><code>&nbsp;10091⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;745🍴</code></b> [seanmonstar/warp](https://github.com/seanmonstar/warp)) - A super-easy, composable, web server framework for warp speeds. [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/warp)
  * <b><code>&nbsp;&nbsp;&nbsp;833⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [spring-rs](https://github.com/spring-rs/spring-rs)) - spring-rs is a application framework written in rust inspired by java's spring-boot.
  * <b><code>&nbsp;&nbsp;1106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [tiny-http](https://github.com/tiny-http/tiny-http)) - Low level HTTP server library
  * <b><code>&nbsp;23220⭐</code></b> <b><code>&nbsp;&nbsp;1248🍴</code></b> [tokio/axum](https://github.com/tokio-rs/axum)) - Ergonomic and modular web framework built with Tokio, Tower, and Hyper [![Build badge](https://github.com/tokio-rs/axum/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/tokio-rs/axum/actions/workflows/CI.yml)
  * <b><code>&nbsp;&nbsp;1211⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [tomaka/rouille](https://github.com/tomaka/rouille)) - Web framework
  * <b><code>&nbsp;&nbsp;1024⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [Zino](https://github.com/zino-rs/zino)) - Next-generation framework for composable applications
* Miscellaneous
  * <b><code>&nbsp;&nbsp;&nbsp;180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [cargonauts](https://github.com/cargonauts-rs/cargonauts)) - A web framework intended for building maintainable, well-factored web apps.
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [edezhic/prest](https://github.com/edezhic/prest))  🌎 [prest](crates.io/crates/prest)] - Progressive RESTful framework aimed to simplify fullstack development
  * <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [hominee/dyer](https://github.com/hominee/dyer))  🌎 [dyer](crates.io/crates/dyer)] - dyer is designed for reliable, flexible and fast Request-Response based service, including data processing, web-crawling and so on, providing some friendly, flexible, comprehensive features without compromising speed.
  * <b><code>&nbsp;&nbsp;3489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;187🍴</code></b> [osohq/oso](https://github.com/osohq/oso))  🌎 [oso](crates.io/crates/oso)] - A policy engine for authorization that's embedded in your application. [![Build Status](https://github.com/osohq/oso/workflows/Development/badge.svg?branch=main)](https://github.com/osohq/oso/actions?query=branch%3Amain+workflow%3ADevelopment)
  * 🌎 [pwoolcoc/soup](gitlab.com/pwoolcoc/soup)  🌎 [soup](crates.io/crates/soup)] - A library similar to Python's BeautifulSoup, designed to enable quick and easy manipulation and querying of HTML documents. [![Build Status](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
  * 🌎 [pyrossh/rust-embed](git.sr.ht/~pyrossh/rust-embed)  🌎 [rust-embed](crates.io/crates/rust-embed)] - A macro to embed static assets into the rust binary
  * <b><code>&nbsp;&nbsp;&nbsp;321⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [rookie](https://github.com/thewh1teagle/rookie)) - Load cookies from any browser on any platform. ![crates.io](https://img.shields.io/crates/v/rookie.svg)
  * <b><code>&nbsp;&nbsp;2215⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [rust-scraper/scraper](https://github.com/rust-scraper/scraper))  🌎 [scraper](crates.io/crates/scraper)] - HTML parsing and querying with CSS selectors. [![Build Status](https://github.com/rust-scraper/scraper/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/rust-scraper/scraper/actions)
  * <b><code>&nbsp;&nbsp;5250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;621🍴</code></b> [serenity-rs/serenity](https://github.com/serenity-rs/serenity))  🌎 [serenity](crates.io/crates/serenity)] - A library for the Discord API
  * <b><code>&nbsp;&nbsp;&nbsp;132⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [softprops/openapi](https://github.com/softprops/openapi)) - A library for processing openapi spec files
  * <b><code>&nbsp;&nbsp;2907⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;207🍴</code></b> [svix/svix-webhooks](https://github.com/svix/svix-webhooks))  🌎 [svix](crates.io/crates/svix)] - A library for sending webhooks and verifying signatures.
  * 🌎 [tbot](gitlab.com/SnejUgal/tbot)  🌎 [tbot](crates.io/crates/tbot)] - Make cool Telegram bots easily [![pipeline status](https://gitlab.com/SnejUgal/tbot/badges/master/pipeline.svg)](https://gitlab.com/SnejUgal/tbot/-/commits/master)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [teloxide/teloxide](https://github.com/teloxide/teloxide/)) - An elegant Telegram bots framework [![Build Status](https://github.com/teloxide/teloxide/actions/workflows/ci.yml/badge.svg)](https://github.com/teloxide/teloxide/actions)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [tu6ge/valitron](https://github.com/tu6ge/valitron))  🌎 [valitron](crates.io/crates/valitron)] - An ergonomic, functional and configurable validator
  * <b><code>&nbsp;&nbsp;1000⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs))  🌎 [select](crates.io/crates/select)] - A library to extract useful data from HTML documents, suitable for web scraping.
  * <b><code>&nbsp;&nbsp;3347⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;300🍴</code></b> [Utoipa](https://github.com/juhaku/utoipa)) - Simple, Fast, Code first and Compile time generated OpenAPI documentation [![crates.io](https://img.shields.io/crates/v/utoipa.svg?label=crates.io&color=orange&logo=rust)](https://crates.io/crates/utoipa) [![Utoipa build](https://github.com/juhaku/utoipa/actions/workflows/build.yaml/badge.svg)](https://github.com/juhaku/utoipa/actions/workflows/build.yaml)
  * <b><code>&nbsp;&nbsp;&nbsp;172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Utoipauto](https://github.com/ProbablyClem/utoipauto)) - Rust Macros to automate the addition of Paths/Schemas to Utoipa [![crates.io](https://img.shields.io/crates/v/utoipauto.svg?label=crates.io&color=orange&logo=rust)](https://crates.io/crates/utoipauto)
* Reverse Proxy
  * <b><code>&nbsp;&nbsp;3461⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu))  🌎 [sozu](crates.io/crates/sozu)] - A HTTP reverse proxy. [![CI](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml)
* Static Site Generators
  * <b><code>&nbsp;&nbsp;1487⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;105🍴</code></b> [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs)) - Static site generator [![Build Status](https://dev.azure.com/cobalt-org/cobalt-org/_apis/build/status/cobalt.rs?branchName=master)](https://dev.azure.com/cobalt-org/cobalt-org/_build?definitionId=2)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs))  🌎 [mdblog](crates.io/crates/mdblog)] - Static site generator from markdown files.
  * <b><code>&nbsp;15920⭐</code></b> <b><code>&nbsp;&nbsp;1075🍴</code></b> [getzola/zola](https://github.com/getzola/zola))  🌎 [zola](www.getzola.org/)] - An opinionated static site generator with everything built-in. [![Build Status](https://dev.azure.com/getzola/zola/_apis/build/status/getzola.zola?branchName=master)](https://dev.azure.com/getzola/zola/_build)
  * <b><code>&nbsp;&nbsp;&nbsp;342⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [grego/blades](https://github.com/grego/blades))  🌎 [blades](www.getblades.org/)] - Blazing fast dead simple static site generator.
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [leven-the-blog/leven](https://github.com/leven-the-blog/leven))  🌎 [leven](crates.io/crates/leven)] - A simple, parallelized blog generator.
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [rochacbruno/marmite](https://github.com/rochacbruno/marmite/))  🌎 [Marmite](marmite.blog/)] - Zero config blog generator
* 🌎 [WebSocket](datatracker.ietf.org/doc/rfc6455/)
  * <b><code>&nbsp;&nbsp;&nbsp;314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [c410-f3r/wtx](https://github.com/c410-f3r/wtx)) - Client and server with encryption support.
  * <b><code>&nbsp;&nbsp;1498⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;224🍴</code></b> [housleyjk/ws-rs](https://github.com/housleyjk/ws-rs)) - lightweight, event-driven WebSockets
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [iddm/urlshortener-rs](https://github.com/iddm/urlshortener-rs)) - A very simple urlshortener library. [![CI](https://github.com/iddm/urlshortener-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/urlshortener-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/urlshortener.svg)](https://crates.io/crates/urlshortener)
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [ratchet](https://github.com/graphform/ratchet))  🌎 [ratchet_rs](crates.io/crates/ratchet_rs)] - Ratchet is a fast, lightweight and fully asynchronous implementation of the WebSocket protocol with support for extensions and Deflate.
  * <b><code>&nbsp;&nbsp;1601⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;228🍴</code></b> [rust-websocket](https://github.com/websockets-rs/rust-websocket)) - A framework for dealing with WebSocket connections (both clients and servers)
  * <b><code>&nbsp;&nbsp;2205⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;252🍴</code></b> [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs)) - Lightweight stream-based WebSocket implementation.
  * <b><code>&nbsp;&nbsp;8015⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;306🍴</code></b> [vi/websocat](https://github.com/vi/websocat)) - CLI for interacting with WebSockets, with functionality of Netcat, Curl and Socat.

## Registries

A registry allows you to publish your Rust libraries as crate packages, to share them with others publicly and privately.

* <b><code>&nbsp;&nbsp;&nbsp;165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [cenotelie/cratery](https://github.com/cenotelie/cratery)) - A lightweight private cargo registry with batteries included, built for organisations, including features similar to 🌎 [docs.rs](docs.rs) and 🌎 [deps.rs](deps.rs). [![CI](https://github.com/cenotelie/cratery/actions/workflows/ci.yml/badge.svg)](https://github.com/cenotelie/cratery/actions/workflows/ci.yml)
* 🌎 [Cloudsmith :heavy_dollar_sign:](cloudsmith.com/product/formats/cargo-registry) - A fully managed package management SaaS, with first-class support for public and private Cargo/Rust registries (plus many others). Has a generous free-tier and is also completely free for open-source.
* 🌎 [Crates](crates.io) - The official public registry for Rust/Cargo.
* 🌎 [RepoFlow](www.repoflow.io) - A simple and modern repository platform that can host Rust crate repositories and proxy crates.io. Also supports other package types like Docker, PyPI, Maven, npm, and RubyGems. Available as a cloud service or self-hosted.
* <b><code>&nbsp;&nbsp;&nbsp;129⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [w4/chartered](https://github.com/w4/chartered)) - A private, authenticated, permissioned Cargo registry [![CI](https://github.com/w4/chartered/actions/workflows/ci.yml/badge.svg)](https://github.com/w4/chartered/actions/workflows/ci.yml)

## Resources

* 🌎 [A Brief History of Rust. Part 1](medium.com/rustaceans/make-it-mandatory-a-brief-history-of-rust-part-1-805459c60c6b) - From a developer's pursuit of software stability to a project that nearly destabilized its creator. 🌎 [Part 2](medium.com/rustaceans/make-it-mandatory-a-brief-history-of-rust-part-2-981d61451aa5). 🌎 [Part 3](medium.com/rustaceans/make-it-mandatory-a-brief-history-of-rust-part-2-b8c0f7a7e781?sk=c0e7fe5fde11a62edc23f284f125aa18).
* Benchmarks
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [c410-f3r/wtx-bench](https://github.com/c410-f3r/wtx-bench)) - Web benchmarks
  * <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [TeXitoi/benchmarksgame-rs](https://github.com/TeXitoi/benchmarksgame-rs)) - Implementations for the 🌎 [The Computer Language Benchmarks Game](benchmarksgame-team.pages.debian.net/benchmarksgame/)
* Decks & Presentations
  * 🌎 [Learning systems programming with Rust](speakerdeck.com/jvns/learning-systems-programming-with-rust) - Presented by 🌎 [Julia Evans](twitter.com/@b0rk) @ Rustconf 2016.
  * 🌎 [Rust: Hack Without Fear!](www.youtube.com/watch?v=lO1z-7cuRYI) - Presented by [Nicholas Matsakis](https://github.com/nikomatsakis) @ C++Now 2018
  * 🌎 [Shipping a Solid Rust Crate](www.youtube.com/watch?v=t4CyEKb-ywA) - Presented by [Michael Gattozzi](https://github.com/mgattozzi) @ RustConf 2017
* Learning
  * 🌎 [100 Exercises To Learn Rust](rust-exercises.com) - Learn Rust through 100 hands-on exercises, covering syntax, types, and more
  * <b><code>&nbsp;&nbsp;2819⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Aquascope](https://github.com/cognitive-engineering-lab/aquascope)) - Interactive visualizations of Rust at compile-time and run-time
  * <b><code>&nbsp;&nbsp;&nbsp;726⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Awesome Rust Streaming](https://github.com/jamesmunns/awesome-rust-streaming)) - A community curated list of livestreams.
  * 🌎 [awesome-rust-mentors](rustbeginners.github.io/awesome-rust-mentors/) - A list of helpful mentors willing to take mentees and educate them about Rust and programming.
  * [CIS 198: Rust Programming](http://cis198-2016s.github.io/schedule/) - University of Pennsylvania's Comp Sci Rust Programming Course
  * 🌎 [CodeCrafters.io](app.codecrafters.io/tracks/rust) - Build your own Redis, Git, Docker, or SQLite
  * 🌎 [Comprehensive Rust 🦀](google.github.io/comprehensive-rust/) - A 3-day course on Rust Fundamentals plus 1-day courses on Android, Bare-metal Rust, and Concurrency. Available in English, 🌎 [Brazilian Portuguese](google.github.io/comprehensive-rust/pt-BR/), and 🌎 [Korean](google.github.io/comprehensive-rust/ko/).
  * <b><code>&nbsp;&nbsp;8243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;392🍴</code></b> [Easy Rust](https://github.com/Dhghomon/easy_rust)) - Learn Rust in easy English.
  * 🌎 [exercism.org](exercism.org/tracks/rust) - programming exercises that help you learn new concepts in Rust.
  * 🌎 [Hands-on Rust](pragprog.com/titles/hwrust/hands-on-rust/) - A hands-on guide to learning Rust by making games - by <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Herbert Wolverson](https://github.com/thebracket/)) (paid)
  * <b><code>&nbsp;&nbsp;7281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;227🍴</code></b> [Idiomatic Rust](https://github.com/mre/idiomatic-rust)) - A peer-reviewed collection of articles/talks/repos which teach idiomatic Rust.
  * 🌎 [LabEx Rust Skill Tree](labex.io/skilltrees/rust) - A structured Rust learning path with hands-on labs, designed for beginners to master Rust step by step.
  * 🌎 [Learn Rust 101](rust-lang.guide/) - A guide to aid you in your journey of becoming a Rustacean (Rust developer)
  * <b><code>&nbsp;&nbsp;&nbsp;563⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Learn Rust by 500 lines code](https://github.com/cuppar/rtd)) - Learn Rust by 500 lines code, build a Todo Cli Application from scratch.
  * 🌎 [Learning Rust With Entirely Too Many Linked Lists](rust-unofficial.github.io/too-many-lists/) - in-depth exploration of Rust's memory management rules, through implementing a few different types of list structures.
  * 🌎 [Little Book of Rust Books](lborb.github.io/book/) - Curated list of rust books and how-tos.
  * 🌎 [Programming Community Curated Resources for Learning Rust](hackr.io/tutorials/learn-rust) - A list of recommended resources voted by the programming community.
  * 🌎 [Refactoring to Rust](www.manning.com/books/refactoring-to-rust) - A book that introduces to Rust language.
  * 🌎 [Rust by Example](doc.rust-lang.org/rust-by-example/) - a collection of runnable examples that illustrate various Rust concepts and standard libraries.
  * 🌎 [Rust Cookbook](rust-lang-nursery.github.io/rust-cookbook/) - A collection of simple examples that demonstrate good practices to accomplish common programming tasks, using the crates of the Rust ecosystem.
  * <b><code>&nbsp;&nbsp;&nbsp;637⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Rust Flashcards](https://github.com/ad-si/Rust-Flashcards)) - Over 550 flashcards to learn Rust from first principles.
  * 🌎 [Rust for professionals](overexact.com/rust-for-professionals/) - A quick introduction to Rust for experienced software developers.
  * <b><code>&nbsp;&nbsp;&nbsp;927⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [Rust Gym](https://github.com/warycat/rustgym)) - A big collection of coding interview problems solved in Rust.
  * 🌎 [Rust in Action](www.manning.com/books/rust-in-action) - A hands-on guide to systems programming with Rust by [Tim McNamara](https://github.com/timClicks) (paid)
  * 🌎 [Rust in Motion](www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) - A video series by [Carol Nichols](https://github.com/carols10cents) and [Jake Goulding](https://github.com/shepmaster) (paid)
  * 🌎 [Rust Language Cheat Sheet](cheats.rs/) - Rust Language Cheat Sheet
  * 🌎 [Rust Tiếng Việt](rust-tieng-viet.github.io/) - Learn Rust in Vietnamese.
  * <b><code>&nbsp;&nbsp;1120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [rust-how-do-i-start](https://github.com/jondot/rust-how-do-i-start)) - A repo dedicated to answering the question: "So, Rust. How do I *start*?". A beginner only hand-picked resources and learning track.
  * <b><code>&nbsp;11980⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;822🍴</code></b> [rust-learning](https://github.com/ctjhoa/rust-learning)) - A collection of useful resources to learn Rust
  * 🌎 [Rustfinity](www.rustfinity.com) - Interactive platform for practicing Rust through hands-on exercises and challenges
  * <b><code>&nbsp;60066⭐</code></b> <b><code>&nbsp;10918🍴</code></b> [Rustlings](https://github.com/rust-lang/rustlings)) - small exercises to get you used to reading and writing Rust code
  * <b><code>&nbsp;&nbsp;&nbsp;945⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [Rusty CS](https://github.com/AbdesamedBendjeddou/Rusty-CS)) - A Computer Science Curriculum that helps practice the acquired academic knowledge in Rust
  * <b><code>&nbsp;&nbsp;2067⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [stdx](https://github.com/brson/stdx)) - Learn these crates first as an extension to std
  * 🌎 [Tour of Rust](tourofrust.com) - This is meant to be an interactive step by step guide through the features of the Rust programming language.
* Podcasts
  * 🌎 [New Rustacean](newrustacean.com) - A podcast about learning Rust
  * 🌎 [Rustacean Station](rustacean-station.org/) - A community project for creating podcast content for Rust
* <b><code>&nbsp;&nbsp;8556⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;396🍴</code></b> [Rust Design Patterns](https://github.com/rust-unofficial/patterns)) - A catalogue of Rust design patterns, anti-patterns and idioms
* [Rust Guidelines](http://aturon.github.io/) - Aaron Turon's blog posts on rust
* 🌎 [Rust Servers, Services and Apps - MEAP](www.manning.com/books/rust-servers-services-and-apps) - Build backend servers, services, and front-ends in Rust to get fast, reliable, and maintainable applications.
* 🌎 [Rust Subreddit](www.reddit.com/r/rust/) - A subreddit(forum) where rust related questions, articles and resources are posted and discussed
* <b><code>&nbsp;&nbsp;5218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;355🍴</code></b> [RustBooks](https://github.com/sger/RustBooks)) - list of RustBooks
* 🌎 [RustCamp 2015 Talks](www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t) - Recorded talks from RustCamp 2015
* <b><code>&nbsp;&nbsp;2796⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [RustViz](https://github.com/rustviz/rustviz)) - generates visualizations from simple Rust programs to assist users in better understanding the Rust Lifetime and Borrowing mechanism.
* 🌎 [Watch Jon Gjengset Implement BitTorrent in Rust](www.youtube.com/watch?v=jf_ddGnum_4) - Implementing (part of) a BitTorrent client in Rust

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

## Source
<b><code>&nbsp;52808⭐</code></b> <b><code>&nbsp;&nbsp;3031🍴</code></b> [rust-unofficial/awesome-rust](https://github.com/rust-unofficial/awesome-rust))