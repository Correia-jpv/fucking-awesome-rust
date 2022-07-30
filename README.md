# Awesome Rust [![build badge](https://github.com/correia-jpv/fucking-awesome-rust/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/correia-jpv/fucking-awesome-rust/actions/workflows/rust.yml) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/rust-unofficial/awesome-rust/)

A curated list of Rust code and resources.

If you want to contribute, please read [this](CONTRIBUTING.md).

## Table of contents

  - [Applications](#applications)
    - [Audio and Music](#audio-and-music)
    - [Cryptocurrencies](#cryptocurrencies)
    - [Database](#database)
    - [Emulators](#emulators)
    - [Games](#games)
    - [Graphics](#graphics)
    - [Image processing](#image-processing)
    - [Industrial automation](#industrial-automation)
    - [Observability](#observability)
    - [Operating systems](#operating-systems)
    - [Productivity](#productivity)
    - [Security tools](#security-tools)
    - [Simulation](#simulation)
    - [System tools](#system-tools)
    - [Task scheduling](#task-scheduling)
    - [Text editors](#text-editors)
    - [Text processing](#text-processing)
    - [Utilities](#utilities)
    - [Video](#video)
    - [Virtualization](#virtualization)
    - [Web](#web)
    - [Web Servers](#web-servers)
  - [Development tools](#development-tools)
    - [Build system](#build-system)
    - [Debugging](#debugging)
    - [Deployment](#deployment)
    - [Embedded](#embedded)
    - [FFI](#ffi)
    - [IDEs](#ides)
    - [Pattern recognition](#pattern-recognition)
    - [Profiling](#profiling)
    - [Services](#services)
    - [Static analysis](#static-analysis)
    - [Testing](#testing)
    - [Transpiling](#transpiling)
  - [Libraries](#libraries)
    - [Artificial Intelligence](#artificial-intelligence)
      - [Genetic algorithms](#genetic-algorithms)
      - [Machine learning](#machine-learning)
    - [Astronomy](#astronomy)
    - [Asynchronous](#asynchronous)
    - [Audio and Music](#audio-and-music-1)
    - [Authentication](#authentication)
    - [Automotive](#automotive)
    - [Bioinformatics](#bioinformatics)
    - [Caching](#caching)
    - [Cloud](#cloud)
    - [Command-line](#command-line)
    - [Compression](#compression)
    - [Computation](#computation)
    - [Concurrency](#concurrency)
    - [Configuration](#configuration)
    - [Cryptography](#cryptography)
    - [Data processing](#data-processing)
    - [Data streaming](#data-streaming)
    - [Data structures](#data-structures)
    - [Data visualization](#data-visualization)
    - [Database](#database-1)
    - [Date and time](#date-and-time)
    - [Distributed systems](#distributed-systems)
    - [Domain driven design](#domain-driven-design)
    - [Email](#email)
    - [Encoding](#encoding)
    - [Filesystem](#filesystem)
    - [Functional Programming](#functional-programming)
    - [Game development](#game-development)
    - [Geospatial](#geospatial)
    - [Graph processing](#graph-processing)
    - [Graphics](#graphics-1)
    - [GUI](#gui)
    - [Image processing](#image-processing)
    - [Language specification](#language-specification)
    - [Logging](#logging)
    - [Macro](#macro)
    - [Markup language](#markup-language)
    - [Mobile](#mobile)
    - [Network programming](#network-programming)
    - [Packaging formats](#packaging-formats)
    - [Parsing](#parsing)
    - [Peripherals](#peripherals)
    - [Platform specific](#platform-specific)
    - [Scripting](#scripting)
    - [Simulation](#simulation-1)
    - [Task scheduling](#task-scheduling-1)
    - [Template engine](#template-engine)
    - [Text processing](#text-processing-1)
    - [Text search](#text-search)
    - [Unsafe](#unsafe)
    - [Virtualization](#virtualization-1)
    - [Web programming](#web-programming)
  - [Registries](#registries)
  - [Resources](#resources)
  - [License](#license)

## Applications

See also 🌎 [Rust — Production](www.rust-lang.org/production) organizations running Rust in production.

*  <b><code>&nbsp;40638⭐</code></b> <b><code>&nbsp;&nbsp;2359🍴</code></b> [alacritty](https://github.com/alacritty/alacritty) — A cross-platform, GPU enhanced terminal emulator
*  <b><code>&nbsp;&nbsp;&nbsp;201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [asm-cli-rust](https://github.com/cch123/asm-cli-rust) — An interactive assembly shell written in rust.
*  <b><code>&nbsp;&nbsp;4420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;273🍴</code></b> [cloudflare/boringtun](https://github.com/cloudflare/boringtun) — A Userspace WireGuard VPN Implementation [![build badge](https://img.shields.io/badge/crates.io-v0.2.0-orange.svg)](https://crates.io/crates/boringtun)
*  <b><code>&nbsp;&nbsp;2282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;403🍴</code></b> [datafusion](https://github.com/apache/arrow-datafusion) — Apache Arrow DataFusion and Ballista query engines
*  <b><code>&nbsp;84306⭐</code></b> <b><code>&nbsp;&nbsp;4551🍴</code></b> [denoland/deno](https://github.com/denoland/deno) — A secure JavaScript/TypeScript runtime built with V8, Rust, and Tokio [![Build Status](https://github.com/denoland/deno/workflows/ci/badge.svg?branch=master&event=push)](https://github.com/denoland/deno/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;185⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Factotum](https://github.com/snowplow/factotum) — 🌎 [A system to programmatically run data pipelines](snowplowanalytics.com/blog/2016/04/09/introducing-factotum-data-pipeline-runner/) [![build badge](https://api.travis-ci.org/snowplow/factotum.svg?branch=master)](https://travis-ci.org/snowplow/factotum)
*  <b><code>&nbsp;&nbsp;1278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [fcsonline/drill](https://github.com/fcsonline/drill) — A HTTP load testing application inspired by Ansible syntax [![build badge](https://api.travis-ci.org/fcsonline/drill.svg?branch=master)](https://travis-ci.org/fcsonline/drill)
*  <b><code>&nbsp;&nbsp;&nbsp;753⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Fractalide](https://github.com/fractalide/fractalide) — Simple Rust Microservices
*  <b><code>&nbsp;&nbsp;2378⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;329🍴</code></b> [habitat](https://github.com/habitat-sh/habitat) — A tool created by Chef to build, deploy, and manage applications.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Herd](https://github.com/imjacobclark/Herd) — an experimental HTTP load testing application
*  <b><code>&nbsp;&nbsp;&nbsp;697⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [jedisct1/flowgger](https://github.com/awslabs/flowgger) — A fast, simple and lightweight data collector
*  <b><code>&nbsp;&nbsp;1065⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [kalker](https://github.com/PaddiM8/kalker) - A scientific calculator that supports math-like syntax with user-defined variables, functions, derivation, integration, and complex numbers. Cross platform + WASM support [![Build Status](https://github.com/PaddiM8/kalker/workflows/Release/badge.svg)](https://github.com/PaddiM8/kalker/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [kytan](https://github.com/changlan/kytan) — High Performance Peer-to-Peer VPN
*  <b><code>&nbsp;&nbsp;1527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;228🍴</code></b> [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) — Ultralight service mesh for Kubernetes.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [MaidSafe](https://github.com/maidsafe) — A decentralized platform.
* 🌎 [mdBook](crates.io/crates/mdbook) — A command line utility to create books from markdown files [![Build Status](https://github.com/rust-lang/mdBook/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/mdBook/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [nicohman/eidolon](https://github.com/nicohman/eidolon) — A steam and drm-free game registry and launcher for linux and macosx [![build badge](https://api.travis-ci.org/nicohman/eidolon.svg?branch=master)](https://travis-ci.org/nicohman/eidolon)
*  <b><code>&nbsp;&nbsp;2151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [notty](https://github.com/withoutboats/notty) — A new kind of terminal
* 🌎 [Pijul](pijul.org) — A patch-based distributed version control system
*  <b><code>&nbsp;&nbsp;2379⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [rx](https://github.com/cloudhead/rx) — Vi inspired Modern Pixel Art Editor
*  <b><code>&nbsp;21390⭐</code></b> <b><code>&nbsp;&nbsp;2646🍴</code></b> [Servo](https://github.com/servo/servo) — A prototype web browser engine
*  <b><code>&nbsp;&nbsp;&nbsp;632⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [shuttle](https://github.com/shuttle-hq/shuttle) — A serverless platform built for Rust
*  <b><code>&nbsp;&nbsp;&nbsp;778⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [tiny](https://github.com/osa1/tiny) — A terminal IRC client
* 🌎 [trust-dns](crates.io/crates/trust-dns) — A DNS-server [![Build Status](https://github.com/bluejekyll/trust-dns/workflows/test/badge.svg?branch=main)](https://github.com/bluejekyll/trust-dns/actions?query=workflow%3Atest)
*  <b><code>&nbsp;12679⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;554🍴</code></b> [wasmer](https://github.com/wasmerio/wasmer) — A safe and fast WebAssembly runtime supporting WASI and Emscripten [![Build Status](https://github.com/wasmerio/wasmer/workflows/build/badge.svg?style=flat-square)](https://github.com/wasmerio/wasmer/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;214⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Weld](https://github.com/serayuzgur/weld) — Full fake REST API generator [![build badge](https://api.travis-ci.org/serayuzgur/weld.svg?branch=master)](https://travis-ci.org/serayuzgur/weld)
*  <b><code>&nbsp;&nbsp;5169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;262🍴</code></b> [wezterm](https://github.com/wez/wezterm) — A GPU-accelerated cross-platform terminal emulator and multiplexer
*  <b><code>&nbsp;&nbsp;7163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [zellij](https://github.com/zellij-org/zellij) — A terminal multiplexer (workspace) with batteries included

### Audio and Music

*  <b><code>&nbsp;&nbsp;&nbsp;170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [enginesound](https://github.com/DasEtwas/enginesound) — A GUI and command line application used to procedurally generate semi-realistic engine sounds. Featuring in-depth configuration, variable sample rate and a frequency analysis window.
*  <b><code>&nbsp;&nbsp;&nbsp;886⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Glicol](https://github.com/chaosprint/glicol) — Graph-oriented live coding language written in Rust for collaborative musicking in browsers.
*  <b><code>&nbsp;&nbsp;3066⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [ncspot](https://github.com/hrkfdn/ncspot) - Cross-platform ncurses Spotify client, inspired by ncmpc and the likes. [![build badge](https://github.com/hrkfdn/ncspot/workflows/Build/badge.svg)](https://github.com/hrkfdn/ncspot/actions?query=workflow%3ABuild)
*  <b><code>&nbsp;&nbsp;&nbsp;932⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [Polaris](https://github.com/agersant/polaris) — A music streaming application.  [![build badge](https://api.travis-ci.org/agersant/polaris.svg?branch=master)](https://travis-ci.org/agersant/polaris)
*  <b><code>&nbsp;12821⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;412🍴</code></b> [Spotify TUI](https://github.com/Rigellute/spotify-tui) — A Spotify client for the terminal written in Rust. ![Continuous Integration](https://github.com/Rigellute/spotify-tui/workflows/Continuous%20Integration/badge.svg?branch=master)
*  <b><code>&nbsp;&nbsp;6266⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;362🍴</code></b> [Spotifyd](https://github.com/Spotifyd/spotifyd) — An open source Spotify client running as a UNIX daemon. ![Continuous Integration](https://github.com/Spotifyd/spotifyd/workflows/Continuous%20Integration/badge.svg?branch=master)

### Cryptocurrencies

*  <b><code>&nbsp;&nbsp;&nbsp;471⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Akula](https://github.com/akula-bft/akula) - Rust Ethereum Execution Layer (EL) Client (WIP)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Bitcoin Satoshi's Vision](https://github.com/brentongunning/rust-sv)  🌎 [sv](crates.io/crates/sv)] — A Rust library for working with Bitcoin SV .
*  <b><code>&nbsp;&nbsp;&nbsp;241⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [ChainX](https://github.com/chainx-org/ChainX) — Fully Decentralized Interchain Crypto Asset Management on Polkadot.
*  <b><code>&nbsp;&nbsp;1262⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [CITA](https://github.com/citahub/cita) — A high performance blockchain kernel for enterprise users.
*  <b><code>&nbsp;&nbsp;&nbsp;124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [coinbase-pro-rs](https://github.com/inv2004/coinbase-pro-rs) — Coinbase pro client in Rust, supports sync/async/websocket [![build badge](https://api.travis-ci.org/inv2004/coinbase-pro-rs.svg?branch=master)](https://travis-ci.org/inv2004/coinbase-pro-rs)
*  <b><code>&nbsp;16477⭐</code></b> <b><code>&nbsp;&nbsp;2565🍴</code></b> [Diem](https://github.com/diem/diem) — Diem’s mission is to enable a simple global currency and financial infrastructure that empowers billions of people.
*  <b><code>&nbsp;&nbsp;&nbsp;621⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;249🍴</code></b> [electrumrs](https://github.com/romanz/electrs) — An efficient re-implementation of Electrum Server in Rust.
*  <b><code>&nbsp;&nbsp;&nbsp;318⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;145🍴</code></b> [ethabi](https://github.com/rust-ethereum/ethabi) - Encode and decode smart contract invocations.
*  <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [ethaddrgen](https://github.com/Limeth/ethaddrgen) — Custom Ethereum vanity address generator made in Rust [![build badge](https://api.travis-ci.org/Limeth/ethaddrgen.svg?branch=master)](https://travis-ci.org/Limeth/ethaddrgen)
*  <b><code>&nbsp;&nbsp;1124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;267🍴</code></b> [ethers-rs](https://github.com/gakonst/ethers-rs) - Complete Ethereum & Celo library and wallet implementation in Rust. ![Build Status](https://github.com/gakonst/ethers-rs/workflows/Tests/badge.svg)
*  <b><code>&nbsp;&nbsp;&nbsp;198⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [etk](https://github.com/quilt/etk) - etk is a collection of tools for writing, reading, and analyzing EVM bytecode.
*  <b><code>&nbsp;&nbsp;&nbsp;460⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [Forest](https://github.com/ChainSafe/forest) - Rust Filecoin implementation [![Build Status](https://img.shields.io/circleci/build/gh/ChainSafe/forest/main?branch=master)](https://app.circleci.com/pipelines/github/ChainSafe/forest?branch=main)
*  <b><code>&nbsp;&nbsp;3874⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;495🍴</code></b> [Foundry](https://github.com/foundry-rs/foundry) - Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust. ![Build Status](https://img.shields.io/github/workflow/status/foundry-rs/foundry/test?style=flat-square)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Grin](https://github.com/mimblewimble/grin/) — Evolution of the MimbleWimble protocol
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [hdwallet](https://github.com/jjyr/hdwallet)  🌎 [hdwallet](crates.io/crates/hdwallet)] — BIP-32 HD wallet related key derivation utilities.
*  <b><code>&nbsp;&nbsp;&nbsp;637⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Holochain](https://github.com/holochain/holochain) — Scalable P2P alternative to blockchain for all those distributed apps you always wanted to build. [![detect critical check failures](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml/badge.svg)](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [ibc-rs](https://github.com/informalsystems/ibc-rs) - Rust implementation of the 🌎 [Interblockchain Communication](ibcprotocol.org/) protocol
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [infincia/bip39-rs](https://github.com/infincia/bip39-rs)  🌎 [bip39](crates.io/crates/bip39)] — Rust implementation of BIP39.
*  <b><code>&nbsp;&nbsp;&nbsp;165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [interBTC](https://github.com/interlay/interbtc) — Trustless and fully decentralized Bitcoin bridge to Polkadot and Kusama.
*  <b><code>&nbsp;&nbsp;&nbsp;147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [Joystream](https://github.com/Joystream/joystream) — A user governed video platform [![Build Status](https://api.travis-ci.org/Joystream/joystream.svg?branch=master)](https://travis-ci.org/Joystream/joystream)
*  <b><code>&nbsp;&nbsp;1794⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;388🍴</code></b> [Lighthouse](https://github.com/sigp/lighthouse) — Rust Ethereum Consensus Layer (CL) Client [![Build Status](https://github.com/sigp/lighthouse/workflows/test-suite/badge.svg?branch=master)](https://github.com/sigp/lighthouse/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;364⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [mev-inspect-rs](https://github.com/flashbots/mev-inspect-rs) - Ethereum MEV Inspector in Rust
*  <b><code>&nbsp;&nbsp;1744⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;343🍴</code></b> [near/nearcore](https://github.com/near/nearcore) — decentralized smart-contract platform for low-end mobile devices.
*  <b><code>&nbsp;&nbsp;1005⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;187🍴</code></b> [Nervos CKB](https://github.com/nervosnetwork/ckb) — Nervos CKB is a public permissionless blockchain, the common knowledge layer of Nervos network.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Nimiq](https://github.com/nimiq/core-rs) — Rust implementation of Nimiq node
*  <b><code>&nbsp;&nbsp;&nbsp;199⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [opensea-rs](https://github.com/gakonst/opensea-rs) - Rust bindings & CLI to the Opensea API and Contracts.
*  <b><code>&nbsp;&nbsp;&nbsp;705⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;210🍴</code></b> [Parity-Bitcoin](https://github.com/paritytech/parity-bitcoin) — The Parity Bitcoin client [![build badge](https://api.travis-ci.org/paritytech/parity-bitcoin.svg?branch=master)](https://app.travis-ci.com/github/paritytech/parity-bitcoin)
*  <b><code>&nbsp;&nbsp;&nbsp;283⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [Phala-Network/phala-blockchain](https://github.com/Phala-Network/phala-blockchain) — Confidential smart contract blockchain based on Intel SGX and Substrate
*  <b><code>&nbsp;&nbsp;6100⭐</code></b> <b><code>&nbsp;&nbsp;1328🍴</code></b> [Polkadot](https://github.com/paritytech/polkadot) — Heterogeneous multi‑chain technology with pooled security
*  <b><code>&nbsp;&nbsp;&nbsp;270⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [revm](https://github.com/bluealloy/revm) - Revolutionary Machine (revm) is a fast Ethereum virtual machine written in rust.
*  <b><code>&nbsp;&nbsp;1129⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;344🍴</code></b> [rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) — Library with support for de/serialization, parsing and executing on data structures and network messages related to Bitcoin.
*  <b><code>&nbsp;&nbsp;&nbsp;762⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;199🍴</code></b> [rust-lightning](https://github.com/lightningdevkit/rust-lightning) [![Crate](https://img.shields.io/crates/v/lightning.svg?logo=rust)](https://crates.io/crates/lightning) — Bitcoin Lightning library written in Rust. The main crate,`lightning`, does not handle networking, persistence, or any other I/O. Thus,it is runtime-agnostic, but users must implement basic networking logic, chain interactions, and disk storage.po on linking crate.
*  <b><code>&nbsp;&nbsp;9179⭐</code></b> <b><code>&nbsp;&nbsp;2264🍴</code></b> [Solana](https://github.com/solana-labs/solana) — Incredibly fast, highly scalable blockchain using Proof-of-History.
*  <b><code>&nbsp;&nbsp;7312⭐</code></b> <b><code>&nbsp;&nbsp;2274🍴</code></b> [Substrate](https://github.com/paritytech/substrate) — Generic modular blockchain template written in Rust
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [svm-rs](https://github.com/roynalnaruto/svm-rs) - Solidity-Compiler Version Manager.
*  <b><code>&nbsp;&nbsp;&nbsp;360⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [tendermint-rs](https://github.com/informalsystems/tendermint-rs) - Rust implementation of Tendermint blockchain data structures and clients
*  <b><code>&nbsp;&nbsp;&nbsp;502⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [wagyu](https://github.com/AleoHQ/wagyu)  🌎 [wagyu](crates.io/crates/wagyu)] — Rust library for generating cryptocurrency wallets [![build badge](https://api.travis-ci.com/AleoHQ/wagyu.svg?branch=master)](https://api.travis-ci.com/AleoHQ/wagyu.svg?branch=master)
*  <b><code>&nbsp;&nbsp;4633⭐</code></b> <b><code>&nbsp;&nbsp;1948🍴</code></b> [zcash](https://github.com/zcash/zcash) — Zcash is an implementation of the "Zerocash" protocol.

### Database

*  <b><code>&nbsp;&nbsp;4299⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;450🍴</code></b> [Databend](https://github.com/datafuselabs/databend) - A Modern Real-Time Data Processing & Analytics DBMS with Cloud-Native Architecture [![Release](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml/badge.svg)](https://github.com/datafuselabs/databend/actions/workflows/databend-release.yml)
* 🌎 [indradb](crates.io/crates/indradb) — Rust based graph database [![build badge](https://api.travis-ci.org/indradb/indradb.svg?branch=master)](https://travis-ci.org/indradb/indradb)
*  <b><code>&nbsp;&nbsp;&nbsp;279⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Lucid](https://github.com/lucid-kv/lucid) — High performance and distributed KV store accessible through a HTTP API. [![Build Status](https://github.com/lucid-kv/lucid/workflows/Lucid/badge.svg?branch=master)](https://github.com/lucid-kv/lucid/actions?workflow=Lucid)
*  <b><code>&nbsp;&nbsp;4263⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;328🍴</code></b> [Materialize](https://github.com/MaterializeInc/materialize) - Streaming SQL database powered by Timely Dataflow :heavy_dollar_sign: [![Build status](https://badge.buildkite.com/97d6604e015bf633d1c2a12d166bb46f3b43a927d3952c999a.svg?branch=main)](https://buildkite.com/materialize/tests)
*  <b><code>&nbsp;&nbsp;4331⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;223🍴</code></b> [noria](https://github.com/mit-pdos/noria)  🌎 [noria](crates.io/crates/noria)] — Dynamically changing, partially-stateful data-flow for web application backends [![build badge](https://api.travis-ci.org/mit-pdos/noria.svg?branch=master)](https://travis-ci.org/mit-pdos/noria)
*  <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [ParityDB](https://github.com/paritytech/parity-db) — Fast and reliable database, optimised for read operation
*  <b><code>&nbsp;&nbsp;1299⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [PumpkinDB](https://github.com/PumpkinDB/PumpkinDB) — an event sourcing database engine
*  <b><code>&nbsp;&nbsp;2088⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [Qdrant](https://github.com/qdrant/qdrant) - An open source vector similarity search engine with extended filtering support [![Tests](https://github.com/qdrant/qdrant/workflows/Tests/badge.svg)](https://github.com/qdrant/qdrant/actions)
*  <b><code>&nbsp;&nbsp;1605⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [seppo0010/rsedis](https://github.com/seppo0010/rsedis) — A Redis reimplementation in Rust [![build badge](https://api.travis-ci.org/seppo0010/rsedis.svg?branch=master)](https://travis-ci.org/seppo0010/rsedis)
*  <b><code>&nbsp;&nbsp;2973⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;230🍴</code></b> [Singularity-Data/RisingWave](https://github.com/singularity-data/risingwave) - the next-generation streaming database in the cloud [![CI](https://github.com/singularity-data/risingwave/actions/workflows/main.yml/badge.svg)](https://github.com/singularity-data/risingwave/actions/workflows/main.yml/badge.svg?branch=main)
*  <b><code>&nbsp;&nbsp;1161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Skytable](https://github.com/skytable/skytable) — A multi-model NoSQL database ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/skytable/skytable/Tests?style=flat-square)
* 🌎 [sled](crates.io/crates/sled) — A (beta) modern embedded database [![Build Status](https://github.com/spacejam/sled/workflows/Rust/badge.svg?branch=master)](https://github.com/spacejam/sled/actions?workflow=Rust)
*  <b><code>&nbsp;&nbsp;&nbsp;289⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [TerminusDB](https://github.com/terminusdb/terminusdb-store) - open source graph database and document store [![Build Status](https://github.com/terminusdb/terminusdb-store/workflows/Build/badge.svg?branch=master)](https://github.com/terminusdb/terminusdb-store/actions)
*  <b><code>&nbsp;11508⭐</code></b> <b><code>&nbsp;&nbsp;1801🍴</code></b> [tikv](https://github.com/tikv/tikv) — A distributed KV database in Rust [![Build Status](https://ci.pingcap.net/job/tikv_ghpr_test/badge/icon)](https://ci.pingcap.net/job/tikv_ghpr_test/)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [vorot93/libmdbx-rs](https://github.com/vorot93/libmdbx-rs)  🌎 [mdbx-sys](crates.io/crates/mdbx-sys)] — Rust bindings for MDBX, a "fast, compact, powerful, embedded, transactional key-value database, with permissive license". This is a fork of mozilla/lmdb-rs with patches to make it work with libmdbx.
*  <b><code>&nbsp;&nbsp;&nbsp;110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [WooriDB](https://github.com/naomijub/wooridb) - General purpose time serial database inspired by Crux and Datomic.

### Emulators

See also 🌎 [crates matching keyword 'emulator'](crates.io/keywords/emulator).

* CHIP-8
  *  <b><code>&nbsp;&nbsp;&nbsp;228⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [ColinEberhardt/wasm-rust-chip8](https://github.com/ColinEberhardt/wasm-rust-chip8) — A WebAssembly CHIP-8 emulator written with Rust
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [starrhorne/chip8-rust](https://github.com/starrhorne/chip8-rust) — Yet another rust chip8 emulator
* Commodore 64
  *  <b><code>&nbsp;&nbsp;&nbsp;204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [kondrak/rust64](https://github.com/kondrak/rust64) — [![build badge](https://api.travis-ci.org/kondrak/rust64.svg?branch=master)](https://travis-ci.org/kondrak/rust64)
* Flash Player
  *  <b><code>&nbsp;10300⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;496🍴</code></b> [Ruffle](https://github.com/ruffle-rs/ruffle) — Ruffle is an Adobe Flash Player emulator written in the Rust programming language. Ruffle targets both the desktop and the web using WebAssembly. [![build badge](https://img.shields.io/circleci/build/github/ruffle-rs/ruffle)](https://app.circleci.com/pipelines/github/ruffle-rs/ruffle)
* Gameboy
  *  <b><code>&nbsp;&nbsp;&nbsp;762⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Gekkio/mooneye-gb](https://github.com/Gekkio/mooneye-gb) — [![build badge](https://api.travis-ci.org/Gekkio/mooneye-gb.svg?branch=master)](https://travis-ci.org/Gekkio/mooneye-gb)
  *  <b><code>&nbsp;&nbsp;1115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [mohanson/gameboy](https://github.com/mohanson/gameboy) — Full featured Cross-platform GameBoy emulator. Forever boys!.
  *  <b><code>&nbsp;&nbsp;&nbsp;492⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [mvdnes/rboy](https://github.com/mvdnes/rboy) — [![build badge](https://api.travis-ci.org/mvdnes/rboy.svg?branch=master)](https://travis-ci.org/mvdnes/rboy)
* Gameboy Advance
  *  <b><code>&nbsp;&nbsp;&nbsp;472⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [michelhe/rustboyadvance-ng](https://github.com/michelhe/rustboyadvance-ng) - RustboyAdvance-ng is a Gameboy Advance emulator with desktop, android and 🌎 [WebAssembly](michelhe.github.io/rustboyadvance-ng/) support. [![build badge](https://github.com/michelhe/rustboyadvance-ng/workflows/Deploy/badge.svg?branch=master)](https://github.com/michelhe/rustboyadvance-ng/actions?query=workflow%3ADeploy)
* Intel 8080 CPU
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [mohanson/i8080](https://github.com/mohanson/i8080) — Intel 8080 cpu emulator by Rust
* NES
  *  <b><code>&nbsp;&nbsp;&nbsp;687⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [koute/pinky](https://github.com/koute/pinky) — [![build badge](https://api.travis-ci.org/koute/pinky.svg?branch=master)](https://travis-ci.org/koute/pinky)
  *  <b><code>&nbsp;&nbsp;&nbsp;715⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [pcwalton/sprocketnes](https://github.com/pcwalton/sprocketnes)
* ZX Spectrum
  *  <b><code>&nbsp;&nbsp;&nbsp;150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [rustzx/rustzx](https://github.com/rustzx/rustzx) — [![RustZX CI](https://github.com/rustzx/rustzx/actions/workflows/ci.yml/badge.svg)](https://github.com/rustzx/rustzx/actions/workflows/ci.yml)

### Games

See also  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Games Made With Piston](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston).

*  <b><code>&nbsp;&nbsp;7070⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;293🍴</code></b> [citybound](https://github.com/citybound/citybound) — The city sim you deserve
*  <b><code>&nbsp;&nbsp;2147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [cristicbz/rust-doom](https://github.com/cristicbz/rust-doom) — A renderer for Doom, may progress to being a playable game [![build badge](https://api.travis-ci.org/cristicbz/rust-doom.svg?branch=master)](https://travis-ci.org/cristicbz/rust-doom)
*  <b><code>&nbsp;&nbsp;&nbsp;483⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [doukutsu-rs](https://github.com/doukutsu-rs/doukutsu-rs) — A Rust reimplementation of Cave Story engine with some enhancements.
*  <b><code>&nbsp;&nbsp;&nbsp;409⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [garkimasera/rusted-ruins](https://github.com/garkimasera/rusted-ruins) — Extensible open world rogue like game with pixel art [![build badge](https://api.travis-ci.org/garkimasera/rusted-ruins.svg?branch=master)](https://travis-ci.org/garkimasera/rusted-ruins)
*  <b><code>&nbsp;&nbsp;&nbsp;428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [gorilla-devs/ferium](https://github.com/gorilla-devs/ferium) — Ferium is a fast and feature rich CLI program for downloading and updating Minecraft mods from Modrinth, CurseForge, and GitHub Releases, and modpacks from Modrinth and CurseForge ![ferium build](https://github.com/gorilla-devs/ferium/actions/workflows/build.yml/badge.svg?branch=main)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [lifthrasiir/angolmois-rust](https://github.com/lifthrasiir/angolmois-rust) — A minimalistic music video game which supports the BMS format [![build badge](https://api.travis-ci.org/lifthrasiir/angolmois-rust.svg?branch=master)](https://travis-ci.org/lifthrasiir/angolmois-rust)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [mara214/rsnake](https://github.com/mara214/rsnake) — Snake written in Rust.
*  <b><code>&nbsp;&nbsp;1217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [ozkriff/zemeroth](https://github.com/ozkriff/zemeroth) — A small 2D turn-based hexagonal strategy game [![build badge](https://api.travis-ci.org/ozkriff/zemeroth.svg?branch=master)](https://travis-ci.org/ozkriff/zemeroth)
*  <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [rhex](https://github.com/dpc/rhex) — hexagonal ascii roguelike
*  <b><code>&nbsp;&nbsp;&nbsp;340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [rsaarelm/magog](https://github.com/rsaarelm/magog) — A roguelike game in Rust
*  <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [SoftbearStudios/mk48](https://github.com/SoftbearStudios/mk48) — Mk48.io is an online multiplayer naval combat game
*  <b><code>&nbsp;&nbsp;&nbsp;133⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [swatteau/sokoban-rs](https://github.com/swatteau/sokoban-rs) — A Sokoban implementation
*  <b><code>&nbsp;&nbsp;&nbsp;191⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [thetawavegame/thetawave-legacy](https://github.com/thetawavegame/thetawave-legacy) - A space shooter game that strives to be an entry point for new game developers to make their first contributions. ![build badge](https://github.com/thetawavegame/thetawave-legacy/actions/workflows/ci.yml/badge.svg?branch=master)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Thinkofname/rust-quake](https://github.com/Thinkofname/rust-quake) — Quake map renderer in Rust
* 🌎 [ttyperacer/terminal-typeracer](gitlab.com/ttyperacer/terminal-typeracer) - Single player typing test game written for the terminal
* 🌎 [Veloren](gitlab.com/veloren/veloren) — An open world, open source multiplayer voxel RPG game currently in alpha development [![build badge](https://gitlab.com/veloren/veloren/badges/master/pipeline.svg)](https://gitlab.com/veloren/veloren/-/pipelines)
*  <b><code>&nbsp;&nbsp;&nbsp;351⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Zone of Control](https://github.com/ozkriff/zoc) — A turn-based hexagonal strategy game [![build badge](https://api.travis-ci.org/ozkriff/zoc.svg?branch=master)](https://travis-ci.org/ozkriff/zoc)

### Graphics

*  <b><code>&nbsp;&nbsp;3231⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [ivanceras/svgbob](https://github.com/ivanceras/svgbob) — converts ASCII diagrams into SVG graphics [![build badge](https://api.travis-ci.org/ivanceras/svgbob.svg?branch=master)](https://travis-ci.org/ivanceras/svgbob)
*  <b><code>&nbsp;&nbsp;&nbsp;176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Limeth/euclider](https://github.com/Limeth/euclider) — A real-time 4D CPU ray tracer [![build badge](https://api.travis-ci.org/Limeth/euclider.svg?branch=master)](https://travis-ci.org/Limeth/euclider)
*  <b><code>&nbsp;&nbsp;1508⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [RazrFalcon/resvg](https://github.com/RazrFalcon/resvg) — An SVG rendering library. [![build badge](https://api.travis-ci.org/RazrFalcon/resvg.svg?branch=master)](https://travis-ci.org/RazrFalcon/resvg)
* 🌎 [turnage/valora](crates.io/crates/valora) — A library for generative fine art ![Rust](https://github.com/turnage/valora/workflows/Rust/badge.svg?branch=master)
*  <b><code>&nbsp;&nbsp;&nbsp;472⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Twinklebear/tray_rust](https://github.com/Twinklebear/tray_rust) — A ray tracer [![build badge](https://api.travis-ci.org/Twinklebear/tray_rust.svg?branch=master)](https://travis-ci.org/Twinklebear/tray_rust)

### Image processing

*  <b><code>&nbsp;&nbsp;&nbsp;426⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Imager](https://github.com/imager-io/imager) — Automated image optimization.

### Industrial automation

*  <b><code>&nbsp;&nbsp;&nbsp;319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [locka99/opcua](https://github.com/locka99/opcua) — A pure rust 🌎 [OPC UA](opcfoundation.org/about/opc-technologies/opc-ua/) library.
*  <b><code>&nbsp;&nbsp;&nbsp;192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [slowtec/tokio-modbus](https://github.com/slowtec/tokio-modbus) — A 🌎 [tokio](tokio.rs)-based 🌎 [modbus](modbus.org) library. [![Build Status](https://api.travis-ci.org/slowtec/tokio-modbus.svg?branch=master)](https://travis-ci.org/slowtec/tokio-modbus)

### Observability

*  <b><code>&nbsp;&nbsp;&nbsp;203⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [avito-tech/bioyino](https://github.com/avito-tech/bioyino) — A high-performance scalable StatsD compatible server.
* 🌎 [OpenTelemetry](crates.io/crates/opentelemetry) — OpenTelemetry provides a single set of APIs, libraries, agents, and collector services to capture distributed traces and metrics from your application. You can analyze them using Prometheus, Jaeger, and other observability tools. [![GitHub Actions CI](https://github.com/open-telemetry/opentelemetry-rust/workflows/CI/badge.svg?branch=master)](https://github.com/open-telemetry/opentelemetry-rust/actions?query=workflow%3ACI+branch%3Amaster)
*  <b><code>&nbsp;&nbsp;2154⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [Quickwit-oss/quickwit](https://github.com/quickwit-oss/quickwit) - Cloud-native and highly cost-efficient search engine for log management. [![CI](https://github.com/quickwit-oss/quickwit/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/quickwit-oss/quickwit/actions?query=workflow%3ACI)
*  <b><code>&nbsp;&nbsp;&nbsp;726⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [Scaphandre](https://github.com/hubblo-org/scaphandre) - A power consumption monitoring agent, to track host and each service power consumption and enable designing systems and applications for more sustainability. Designed to fit any monitoring toolchain (already supports prometheus, warp10, riemann...).
*  <b><code>&nbsp;10800⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;837🍴</code></b> [vectordotdev/vector](https://github.com/vectordotdev/vector) — A High-Performance, Logs, Metrics, & Events Router.

### Operating systems

See also  <b><code>&nbsp;&nbsp;&nbsp;414⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [A comparison of operating systems written in Rust](https://github.com/flosse/rust-os-comparison).
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [0x59616e/SteinsOS](https://github.com/0x59616e/SteinsOS)  — An OS for armv8-a architecture.
* 🌎 [redox-os/redox](gitlab.redox-os.org/redox-os/redox) — [![build badge](https://api.travis-ci.org/redox-os/redox.svg?branch=master)](https://travis-ci.org/redox-os/redox)
*  <b><code>&nbsp;&nbsp;&nbsp;570⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) — [![build badge](https://api.travis-ci.org/thepowersgang/rust_os.svg?branch=master)](https://travis-ci.org/thepowersgang/rust_os)
*  <b><code>&nbsp;&nbsp;1986⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [theseus-os/Theseus](https://github.com/theseus-os/Theseus) — A safe-language, single address space and single privilege level OS written from scratch in pure Rust - [![build badge](https://img.shields.io/github/workflow/status/theseus-os/Theseus/Documentation?label=docs%20build)](https://www.theseus-os.com/Theseus/book/index.html)
*  <b><code>&nbsp;&nbsp;3633⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;500🍴</code></b> [tock/tock](https://github.com/tock/tock) — A secure embedded operating system for Cortex-M based microcontrollers

### Productivity

*  <b><code>&nbsp;&nbsp;&nbsp;281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Bartib](https://github.com/nikolassv/bartib)  🌎 [Bartib](crates.io/crates/bartib)] - A simple timetracker for the command line [![Tests](https://github.com/nikolassv/bartib/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/nikolassv/bartib/actions/workflows/test.yml)
*  <b><code>&nbsp;&nbsp;5375⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;167🍴</code></b> [espanso](https://github.com/espanso/espanso) — A cross-platform Text Expander written in Rust[![CI](https://github.com/espanso/espanso/actions/workflows/ci.yml/badge.svg?branch=dev&event=push)](https://github.com/espanso/espanso/actions/workflows/ci.yml)
* 🌎 [eureka](crates.io/crates/eureka) — A CLI tool to input and store your ideas without leaving the terminal
*  <b><code>&nbsp;&nbsp;&nbsp;369⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [pier-cli/pier](https://github.com/pier-cli/pier) — A central repository to manage (add, search metadata, etc.) all your one-liners, scripts, tools, and CLIs

### Security tools

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [arvancloud/libinjection-rs](https://github.com/arvancloud/libinjection-rs) — Rust bindings for  <b><code>&nbsp;&nbsp;&nbsp;907⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;274🍴</code></b> [libinjection](https://github.com/client9/libinjection) [![build badge](https://api.travis-ci.org/arvancloud/libinjection-rs.svg?branch=master)](https://travis-ci.org/arvancloud/libinjection-rs)
*  <b><code>&nbsp;&nbsp;&nbsp;460⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Cherrybomb](https://github.com/blst-security/cherrybomb) - Stop half-done API specifications with a CLI tool that helps you avoid undefined user behaviour by validating your API specifications.
*  <b><code>&nbsp;&nbsp;3011⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;286🍴</code></b> [epi052/feroxbuster](https://github.com/epi052/feroxbuster) - A simple, fast, recursive content discovery tool written in Rust (
*  <b><code>&nbsp;&nbsp;&nbsp;246⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Inspektor](https://github.com/inspektor-dev/inspektor) - A database protocol-aware proxy that is used to enforce access policies 👮
*  <b><code>&nbsp;&nbsp;&nbsp;326⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [kpcyrd/authoscope](https://github.com/kpcyrd/authoscope) — A scriptable network authentication cracker [![build badge](https://api.travis-ci.org/kpcyrd/authoscope.svg?branch=master)](https://travis-ci.org/kpcyrd/authoscope)
*  <b><code>&nbsp;&nbsp;&nbsp;362⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [kpcyrd/rshijack](https://github.com/kpcyrd/rshijack) — A TCP connection hijacker, rust rewrite of shijack [![build badge](https://api.travis-ci.org/kpcyrd/rshijack.svg?branch=master)](https://travis-ci.org/kpcyrd/rshijack)
*  <b><code>&nbsp;&nbsp;1258⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int) — A semi-automatic OSINT framework and package manager [![build badge](https://api.travis-ci.org/kpcyrd/sn0int.svg?branch=master)](https://travis-ci.org/kpcyrd/sn0int)
*  <b><code>&nbsp;&nbsp;&nbsp;859⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue) — A secure multithreaded packet sniffer [![build badge](https://api.travis-ci.org/kpcyrd/sniffglue.svg?branch=master)](https://travis-ci.org/kpcyrd/sniffglue)
*  <b><code>&nbsp;&nbsp;&nbsp;411⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [ObserverWard](https://github.com/0x727/ObserverWard) — Community based web technologies analysis tool.
*  <b><code>&nbsp;&nbsp;&nbsp;430⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [phra/rustbuster](https://github.com/phra/rustbuster) — A Comprehensive Web Fuzzer and Content Discovery Tool
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [ripasso](https://github.com/cortex/ripasso/) — A password manager, filesystem compatible with pass
*  <b><code>&nbsp;&nbsp;6768⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;557🍴</code></b> [rustscan/rustscan](https://github.com/RustScan/RustScan) — Make Nmap faster with this port scanning tool [![build badge](https://github.com/RustScan/RustScan/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/RustScan/RustScan/actions?query=workflow%3A%22Continuous+integration%22)

### Simulation

*  <b><code>&nbsp;&nbsp;&nbsp;502⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [hEngine](https://github.com/hashintel/hash/tree/main/packages/engine) - A Rust-implemented computational simulation engine, supporting large-scale agent-based modelling, with simulation logic written in JavaScript and Python.

### System tools

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide/) — A fast alternative to `cd` that learns your habits [![release](https://github.com/ajeetdsouza/zoxide/workflows/.github/workflows/release.yml/badge.svg)](https://github.com/ajeetdsouza/zoxide/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Alonely0/Voila](https://github.com/Alonely0/Voila) — Voila is a domain-specific language launched through CLI tool for operating with files and directories in massive amounts in a fast & reliable way. [![Linux build](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/linux-ci.yml) [![macOS build](https://github.com/Alonely0/Voila/actions/workflows/mac-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/mac-ci.yml) [![Windows build](https://github.com/Alonely0/Voila/actions/workflows/windows-ci.yml/badge.svg)](https://github.com/Alonely0/Voila/actions/workflows/windows-ci.yml)
*  <b><code>&nbsp;&nbsp;7229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;219🍴</code></b> [bandwhich](https://github.com/imsnif/bandwhich) — Terminal bandwidth utilization tool [![build badge](https://api.travis-ci.com/imsnif/bandwhich.svg?branch=master)](https://app.travis-ci.com/github/imsnif/bandwhich)
*  <b><code>&nbsp;&nbsp;4636⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [bottom](https://github.com/ClementTsang/bottom) - Yet another cross-platform graphical process/system monitor. [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ClementTsang/bottom/ci/master)](https://github.com/ClementTsang/bottom/actions?query=branch%3Amaster)
*  <b><code>&nbsp;&nbsp;&nbsp;222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [brocode/fblog](https://github.com/brocode/fblog) — Small command-line JSON Log viewer [![build badge](https://api.travis-ci.org/brocode/fblog.svg?branch=master)](https://travis-ci.org/brocode/fblog)
*  <b><code>&nbsp;&nbsp;&nbsp;170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [bustd](https://github.com/vrmiguel/bustd) - Lightweight process killer daemon to handle out-of-memory scenarios on Linux. [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/vrmiguel/bustd/build-and-test)](https://github.com/vrmiguel/bustd/actions?query=branch%3Amaster)
*  <b><code>&nbsp;&nbsp;&nbsp;103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [buster/rrun](https://github.com/buster/rrun) — A command launcher for Linux, similar to gmrun [![build badge](https://api.travis-ci.org/buster/rrun.svg?branch=master)](https://travis-ci.org/buster/rrun)
*  <b><code>&nbsp;&nbsp;4259⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [cantino/mcfly](https://github.com/cantino/mcfly) - Fly through your shell history. Great Scott! [![build badge](https://api.travis-ci.org/cantino/mcfly.svg?branch=master)](https://travis-ci.org/cantino/mcfly)
*  <b><code>&nbsp;&nbsp;&nbsp;208⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [crabz](https://github.com/sstadick/crabz) - Multi-threaded compression and decompression CLI tool [![Build Status](https://github.com/sstadick/crabz/workflows/Check/badge.svg)](https://github.com/sstadick/crabz/actions?query=workflow%3ACheck)
*  <b><code>&nbsp;&nbsp;&nbsp;176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [cristianoliveira/funzzy](https://github.com/cristianoliveira/funzzy) — A configurable filesystem watcher inspired by [entr](http://eradman.com/entrproject/) [![build badge](https://api.travis-ci.org/cristianoliveira/funzzy.svg?branch=master)](https://travis-ci.org/cristianoliveira/funzzy)
*  <b><code>&nbsp;&nbsp;3060⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [dalance/procs](https://github.com/dalance/procs) — A modern replacement for 'ps' written by Rust [![Regression](https://github.com/dalance/procs/actions/workflows/regression.yml/badge.svg)](https://github.com/dalance/procs/actions/workflows/regression.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [ddh](https://github.com/darakian/ddh) — Fast duplicate file finder [![build badge](https://api.travis-ci.org/darakian/ddh.svg?branch=master)](https://travis-ci.org/darakian/ddh)
*  <b><code>&nbsp;&nbsp;1433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [diskonaut](https://github.com/imsnif/diskonaut) — Terminal visual disk space navigator [![build badge](https://api.travis-ci.com/imsnif/diskonaut.svg?branch=main)](https://app.travis-ci.com/github/imsnif/diskonaut)
*  <b><code>&nbsp;&nbsp;4560⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [dust](https://github.com/bootandy/dust) — A more intuitive version of du
* 🌎 [fselect](crates.io/crates/fselect) — Find files with SQL-like queries [![build badge](https://api.travis-ci.org/jhspetersson/fselect.svg?branch=master)](https://travis-ci.org/jhspetersson/fselect)
*  <b><code>&nbsp;&nbsp;8571⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;302🍴</code></b> [gitui](https://github.com/extrawurst/gitui) - Blazing fast terminal client for git written in Rust. [![build](https://github.com/extrawurst/gitui/workflows/CI/badge.svg?branch=master)](https://github.com/extrawurst/gitui/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;602⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Kondo](https://github.com/tbillington/kondo) - CLI & GUI tool for deleting software project artifacts and reclaiming disk space
*  <b><code>&nbsp;&nbsp;&nbsp;365⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [lotabout/rargs](https://github.com/lotabout/rargs)  🌎 [rargs](crates.io/crates/rargs)] — xargs + awk with pattern matching support [![build badge](https://api.travis-ci.org/lotabout/rargs.svg?branch=master)](https://travis-ci.org/lotabout/rargs)
*  <b><code>&nbsp;&nbsp;3423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [lotabout/skim](https://github.com/lotabout/skim) — A fuzzy finder in pure rust [![build badge](https://api.travis-ci.org/lotabout/skim.svg?branch=master)](https://travis-ci.org/lotabout/skim)
*  <b><code>&nbsp;&nbsp;&nbsp;789⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Luminarys/synapse](https://github.com/Luminarys/synapse) — Flexible and fast BitTorrent daemon. [![Build Status](https://api.travis-ci.org/Luminarys/synapse.svg?branch=master)](https://travis-ci.org/Luminarys/synapse)
*  <b><code>&nbsp;&nbsp;1528⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [m4b/bingrep](https://github.com/m4b/bingrep) — Greps through binaries from various OSs and architectures, and colors them. [![build badge](https://api.travis-ci.org/m4b/bingrep.svg?branch=master)](https://travis-ci.org/m4b/bingrep)
*  <b><code>&nbsp;&nbsp;&nbsp;890⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [mitnk/cicada](https://github.com/mitnk/cicada) — A bash-like Unix shell [![build badge](https://api.travis-ci.org/mitnk/cicada.svg?branch=master)](https://travis-ci.org/mitnk/cicada)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [mmstick/concurr](https://github.com/mmstick/concurr) — Alternative to GNU Parallel w/ a client-server architecture
*  <b><code>&nbsp;&nbsp;&nbsp;243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [mmstick/fontfinder](https://github.com/mmstick/fontfinder) — GTK3 application for previewing and installing Google's fonts
*  <b><code>&nbsp;&nbsp;&nbsp;140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [mmstick/tv-renamer](https://github.com/mmstick/tv-renamer) — A tv series renaming application with an optional GTK3 frontend. [![build badge](https://api.travis-ci.org/mmstick/tv-renamer.svg?branch=master)](https://travis-ci.org/mmstick/tv-renamer)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [mxseev/logram](https://github.com/mxseev/logram) — Push log files' updates to Telegram
*  <b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [nickgerace/gfold](https://github.com/nickgerace/gfold)  🌎 [gfold](crates.io/crates/gfold)] - CLI tool to help keep track of multiple Git repositories [![build](https://img.shields.io/github/workflow/status/nickgerace/gfold/merge/main)](https://github.com/nickgerace/gfold/actions?query=workflow%3Amerge+branch%3Amain)
*  <b><code>&nbsp;&nbsp;&nbsp;634⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [nivekuil/rip](https://github.com/nivekuil/rip) - A safe and ergonomic alternative to `rm` [![build badge](https://api.travis-ci.org/nivekuil/rip.svg?branch=master)](https://travis-ci.org/nivekuil/rip)
*  <b><code>&nbsp;18608⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;553🍴</code></b> [ogham/exa](https://github.com/ogham/exa) — A replacement for 'ls' [![build badge](https://api.travis-ci.org/ogham/exa.svg?branch=master)](https://travis-ci.org/ogham/exa)
*  <b><code>&nbsp;&nbsp;1560⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [orhun/kmon](https://github.com/orhun/kmon) — Linux Kernel Manager and Activity Monitor ![https://github.com/orhun/kmon/actions](https://img.shields.io/github/workflow/status/orhun/kmon/Continuous%20Integration/master?label=build)
*  <b><code>&nbsp;&nbsp;&nbsp;624⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [orhun/systeroid](https://github.com/orhun/systeroid) — A more powerful alternative to sysctl(8) with a terminal user interface ![https://github.com/orhun/systeroid/actions](https://img.shields.io/github/workflow/status/orhun/systeroid/Continuous%20Integration/main?label=build)
*  <b><code>&nbsp;&nbsp;&nbsp;573⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [ouch](https://github.com/ouch-org/ouch) - Painless compression and decompression on the command-line [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ouch-org/ouch/build-and-test)](https://github.com/ouch-org/ouch/actions?query=branch%3Amaster)
*  <b><code>&nbsp;&nbsp;8040⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;266🍴</code></b> [Peltoche/lsd](https://github.com/Peltoche/lsd) — An ls with a lot of pretty colors and awesome icons [![build](https://github.com/Peltoche/lsd/workflows/CICD/badge.svg?branch=master)](https://github.com/Peltoche/lsd/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;430⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [pop-os/popsicle](https://github.com/pop-os/popsicle) — GTK3 & CLI utility for flashing multiple USB devices in parallel
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [pop-os/system76-power](https://github.com/pop-os/system76-power/) — Linux power management daemon (DBus-interface) with CLI tool.
*  <b><code>&nbsp;&nbsp;2992⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [pueue](https://github.com/nukesor/pueue) — Manage your long running shell commands. [![GitHub Actions Workflow](https://github.com/nukesor/pueue/workflows/Test%20build/badge.svg?branch=master)](https://github.com/nukesor/pueue/actions)
*  <b><code>&nbsp;&nbsp;1273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [redox-os/ion](https://github.com/redox-os/ion) — Next-generation system shell [![build badge](https://api.travis-ci.org/redox-os/ion.svg?branch=master)](https://travis-ci.org/redox-os/ion)
*  <b><code>&nbsp;36005⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;944🍴</code></b> [sharkdp/bat](https://github.com/sharkdp/bat) — A cat(1) clone with wings. [![CICD](https://github.com/sharkdp/bat/actions/workflows/CICD.yml/badge.svg?branch=master)](https://github.com/sharkdp/bat/actions/workflows/CICD.yml)
*  <b><code>&nbsp;23950⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;616🍴</code></b> [sharkdp/fd](https://github.com/sharkdp/fd) — A simple, fast and user-friendly alternative to find. [![CICD](https://github.com/sharkdp/fd/actions/workflows/CICD.yml/badge.svg)](https://github.com/sharkdp/fd/actions/workflows/CICD.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;373⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [sitkevij/hex](https://github.com/sitkevij/hex) — A colorized hexdump terminal utility. [![build badge](https://api.travis-ci.org/sitkevij/hex.svg?branch=master)](https://travis-ci.org/sitkevij/hex)
*  <b><code>&nbsp;12304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;892🍴</code></b> [uutils/coreutils](https://github.com/uutils/coreutils) — A cross-platform Rust rewrite of the GNU coreutils [[![CICD](https://github.com/uutils/coreutils/actions/workflows/CICD.yml/badge.svg)](https://github.com/uutils/coreutils/actions/workflows/CICD.yml)
*  <b><code>&nbsp;&nbsp;3191⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [watchexec](https://github.com/watchexec/watchexec) — Executes commands in response to file modifications [![build badge](https://api.travis-ci.org/watchexec/watchexec.svg?branch=master)](https://travis-ci.org/watchexec/watchexec)
*  <b><code>&nbsp;&nbsp;6843⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;373🍴</code></b> [XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei) — counts the lines of code [![build badge](https://api.travis-ci.org/XAMPPRocky/tokei.svg?branch=master)](https://travis-ci.org/XAMPPRocky/tokei)

### Task scheduling

*  <b><code>&nbsp;&nbsp;&nbsp;457⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [delicate](https://github.com/BinChengZhao/delicate) — A lightweight and distributed task scheduling platform written in rust. [![Build Status](https://github.com/BinChengZhao/delicate/workflows/CI/badge.svg)](https://github.com/BinChengZhao/delicate/actions)

### Text editors

* 🌎 [amp](amp.rs) — Inspired by Vi/Vim. [![build badge](https://api.travis-ci.org/jmacdonald/amp.svg?branch=master)](https://travis-ci.org/jmacdonald/amp)
*  <b><code>&nbsp;&nbsp;1532⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [gchp/iota](https://github.com/gchp/iota) — A simple text editor [![build badge](https://api.travis-ci.org/gchp/iota.svg?branch=master)](https://travis-ci.org/gchp/iota)
*  <b><code>&nbsp;10883⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;664🍴</code></b> [helix](https://github.com/helix-editor/helix) — A post-modern modal text editor inspired by Neovim/Kakoune. [![build badge](https://github.com/helix-editor/helix/actions/workflows/build.yml/badge.svg)](https://github.com/helix-editor/helix/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;791⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [ilai-deutel/kibi](https://github.com/ilai-deutel/kibi) — A tiny (≤1024 LOC) text editor with syntax highlighting, incremental search and more. [![build badge](https://github.com/ilai-deutel/kibi/workflows/CI/badge.svg?branch=master)](https://github.com/ilai-deutel/kibi/actions?query=branch%3Amaster)
*  <b><code>&nbsp;13207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;351🍴</code></b> [lapce](https://github.com/lapce/lapce) — Lightning-fast and Powerful Code Editor written in Rust. [![build badge](https://github.com/lapce/lapce/actions/workflows/release.yml/badge.svg)](https://github.com/lapce/lapce/actions/workflows/release.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;541⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [mathall/rim](https://github.com/mathall/rim) — Vim-like text editor written in Rust
*  <b><code>&nbsp;&nbsp;2783⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [ox](https://github.com/curlpipe/ox) — An independent Rust text editor that runs in your terminal!
*  <b><code>&nbsp;&nbsp;4521⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;334🍴</code></b> [Remacs](https://github.com/remacs/remacs) — A community-driven port of Emacs to Rust. [![build badge](https://api.travis-ci.org/remacs/remacs.svg?branch=master)](https://travis-ci.org/remacs/remacs)
*  <b><code>&nbsp;&nbsp;&nbsp;250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [vamolessa/pepper](https://github.com/vamolessa/pepper)  🌎 [pepper](crates.io/crates/pepper)] — An opinionated modal editor to simplify code editing from the terminal [![build badge](https://github.com/vamolessa/pepper/workflows/rust/badge.svg?branch=master)](https://github.com/vamolessa/pepper)
*  <b><code>&nbsp;19505⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;706🍴</code></b> [xi-editor](https://github.com/xi-editor/xi-editor) — A modern editor with a backend written in Rust.

### Text processing

*  <b><code>&nbsp;&nbsp;1051⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [dominikwilkowski/cfonts](https://github.com/dominikwilkowski/cfonts)  🌎 [cfonts](crates.io/crates/cfonts)] — Sexy ANSI fonts for the console ![build badge](https://github.com/dominikwilkowski/cfonts/actions/workflows/testing.yml/badge.svg)
*  <b><code>&nbsp;&nbsp;5435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [grex](https://github.com/pemistahl/grex) — A command-line tool and library for generating regular expressions from user-provided test cases [![build badge](https://api.travis-ci.org/pemistahl/grex.svg?branch=master)](https://travis-ci.org/pemistahl/grex)
*  <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Lisprez/so_stupid_search](https://github.com/Lisprez/so_stupid_search) — A simple and fast string search tool for human beings
*  <b><code>&nbsp;&nbsp;3897⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Melody](https://github.com/yoav-lavi/melody) - A language that compiles to regular expressions and aims to be more easily readable and maintainable [![build badge](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml/badge.svg)](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml) [![crates.io](https://img.shields.io/crates/v/melody_compiler?label=compiler)](https://crates.io/crates/melody_compiler)
*  <b><code>&nbsp;&nbsp;4794⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [phiresky/ripgrep-all](https://github.com/phiresky/ripgrep-all) — ripgrep, but also search in PDFs, E-Books, Office documents, zip, tar.gz, etc. [![Build Status](https://api.travis-ci.org/phiresky/ripgrep-all.svg?branch=master)](https://travis-ci.org/phiresky/ripgrep-all)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [replicadse/complate](https://github.com/replicadse/complate) — An in-terminal text templating tool designed for standardizing messages (like for GIT commits). [![crates.io](https://img.shields.io/crates/v/complate.svg)](https://crates.io/crates/complate) [![crates.io](https://img.shields.io/crates/d/complate?label=crates.io%20downloads)](https://crates.io/crates/complate) [![build badge](https://github.com/replicadse/complate/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/complate/actions)
* 🌎 [ripgrep](crates.io/crates/ripgrep) — combines the usability of The Silver Searcher with the raw speed of grep [![build badge](https://api.travis-ci.org/BurntSushi/ripgrep.svg?branch=master)](https://travis-ci.org/BurntSushi/ripgrep)
*  <b><code>&nbsp;&nbsp;&nbsp;311⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [ruplacer](https://github.com/your-tools/ruplacer) — Find and replace text in source files [![Run tests](https://github.com/your-tools/ruplacer/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/your-tools/ruplacer/actions/workflows/test.yml)
* 🌎 [sd](crates.io/crates/sd) — Intuitive find & replace CLI
*  <b><code>&nbsp;&nbsp;&nbsp;572⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [sstadick/hck](https://github.com/sstadick/hck) - A faster and more featureful drop in replacement for `cut`  [![build badge](https://github.com/sstadick/hck/workflows/Check/badge.svg?branch=master)](https://github.com/sstadick/hck)
*  <b><code>&nbsp;&nbsp;&nbsp;299⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [vishaltelangre/ff](https://github.com/vishaltelangre/ff) — Find files (ff) by name! [![build badge](https://api.travis-ci.org/vishaltelangre/ff.svg?branch=master)](https://travis-ci.org/vishaltelangre/ff)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [whitfin/bytelines](https://github.com/whitfin/bytelines)  🌎 [bytelines](crates.io/crates/bytelines)] — Read input lines as byte slices for high efficiency.
*  <b><code>&nbsp;&nbsp;&nbsp;160⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [whitfin/runiq](https://github.com/whitfin/runiq) — an efficient way to filter duplicate lines from unsorted input.
* 🌎 [xsv](crates.io/crates/xsv) — A fast CSV command line tool (slicing, indexing, selecting, searching, sampling, etc.) [![build badge](https://api.travis-ci.org/BurntSushi/xsv.svg?branch=master)](https://travis-ci.org/BurntSushi/xsv)

### Image processing

*  <b><code>&nbsp;&nbsp;&nbsp;426⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Imager](https://github.com/imager-io/imager) — Automated image optimization.
*  <b><code>&nbsp;&nbsp;1620⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [shssoichiro/oxipng](https://github.com/shssoichiro/oxipng)  🌎 [oxipng](crates.io/crates/oxipng)] — Multithreaded PNG optimizer written in Rust. [![Build Status](https://github.com/shssoichiro/oxipng/workflows/oxipng/badge.svg)](https://github.com/shssoichiro/oxipng/actions?query=branch%3Amaster) [![Version](https://img.shields.io/crates/v/oxipng.svg)](https://crates.io/crates/oxipng)

### Utilities

*  <b><code>&nbsp;&nbsp;&nbsp;296⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [1History](https://github.com/1History/1History) — Command line interface to backup Firefox/Chrome/Safari history to one SQLite file [![Build Status](https://github.com/1History/1History/actions/workflows/CI.yml/badge.svg)](https://github.com/1History/1History/actions/workflows/CI.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [brycx/checkpwn](https://github.com/brycx/checkpwn) — A Have I Been Pwned (HIBP) command-line utility tool that lets you easily check for compromised accounts and passwords.
*  <b><code>&nbsp;&nbsp;&nbsp;177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [evansmurithi/cloak](https://github.com/evansmurithi/cloak) — A Command Line OTP (One Time Password) Authenticator application.
![CI](https://github.com/evansmurithi/cloak/workflows/CI/badge.svg) [![build badge](https://ci.appveyor.com/api/projects/status/9mlfpfru3ng4c689/branch/master?svg=true)](https://ci.appveyor.com/project/evansmurithi/cloak)
*  <b><code>&nbsp;&nbsp;&nbsp;545⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [fcsonline/tmux-thumbs](https://github.com/fcsonline/tmux-thumbs) — A lightning fast version of tmux-fingers written in Rust, copy/pasting tmux like vimium/vimperator.
*  <b><code>&nbsp;&nbsp;&nbsp;296⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [guoxbin/dtool](https://github.com/guoxbin/dtool) — A useful command-line tool collection to assist development including conversion, codec, hashing, encryption, etc. [![Build Status](https://api.travis-ci.org/guoxbin/dtool.svg?branch=master)](https://travis-ci.org/guoxbin/dtool)
*  <b><code>&nbsp;&nbsp;&nbsp;521⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [mprocs](https://github.com/pvolok/mprocs) — TUI for running multiple processes
*  <b><code>&nbsp;&nbsp;&nbsp;417⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [nomino](https://github.com/yaa110/nomino) — Batch rename utility for developers [![Build Status](https://api.travis-ci.org/yaa110/nomino.svg?branch=master)](https://travis-ci.org/yaa110/nomino)
*  <b><code>&nbsp;&nbsp;&nbsp;157⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [raftario/licensor](https://github.com/raftario/licensor) — write licenses to stdout [![GitHub Actions](https://github.com/raftario/licensor/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/raftario/licensor/actions/workflows/build.yml)
*  <b><code>&nbsp;26444⭐</code></b> <b><code>&nbsp;&nbsp;2336🍴</code></b> [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) — A remote desktop software, great alternative to TeamViewer and AnyDesk.
*  <b><code>&nbsp;&nbsp;&nbsp;183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [tversteeg/emplace](https://github.com/tversteeg/emplace) — Synchronize installed packages on multiple machines
*  <b><code>&nbsp;&nbsp;&nbsp;202⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [vamolessa/verco](https://github.com/vamolessa/verco)  🌎 [verco](crates.io/crates/verco)] — A simple Git/Hg tui client focused on keyboard shortcuts
*  <b><code>&nbsp;17454⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;938🍴</code></b> [vaultwarden](https://github.com/dani-garcia/vaultwarden#readme) [![Build](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml/badge.svg)](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml) — Alternative implementation of the Bitwarden server API written in Rust
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [yaa110/cb](https://github.com/yaa110/cb) — Command line interface to manage clipboard [![Build Status](https://api.travis-ci.org/yaa110/cb.svg?branch=master)](https://travis-ci.org/yaa110/cb)

### Video

*  <b><code>&nbsp;&nbsp;&nbsp;176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [dertuxmalwieder/yaydl](https://github.com/dertuxmalwieder/yaydl)  🌎 [yaydl](crates.io/crates/yaydl)] - A simple video downloader
*  <b><code>&nbsp;&nbsp;&nbsp;467⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [harlanc/xiu](https://github.com/harlanc/xiu) — A powerful and secure live server by pure rust (rtmp/httpflv/hls/relay). [![Build Status](https://api.travis-ci.com/harlanc/xiu.svg?branch=master)](https://app.travis-ci.com/github/harlanc/xiu) [![crates.io](https://img.shields.io/crates/v/xiu.svg)](https://crates.io/crates/xiu)
*  <b><code>&nbsp;&nbsp;2859⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;211🍴</code></b> [xiph/rav1e](https://github.com/xiph/rav1e) — The fastest and safest AV1 encoder. [![build badge](https://api.travis-ci.org/xiph/rav1e.svg?branch=master)](https://travis-ci.org/xiph/rav1e)

### Virtualization

*  <b><code>&nbsp;&nbsp;3684⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;202🍴</code></b> [containers/youki](https://github.com/containers/youki) — A container runtime in Rust [![build badge](https://github.com/containers/youki/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/containers/youki/actions)
*  <b><code>&nbsp;18680⭐</code></b> <b><code>&nbsp;&nbsp;1331🍴</code></b> [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) — A lightweight virtual machine for container workload  🌎 [Firecracker Microvm](firecracker-microvm.github.io/)
*  <b><code>&nbsp;&nbsp;1788⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [tailhook/vagga](https://github.com/tailhook/vagga) — A containerization tool without daemons [![build badge](https://api.travis-ci.org/tailhook/vagga.svg?branch=master)](https://travis-ci.org/tailhook/vagga)

### Web

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [cfal/tobaru](https://github.com/cfal/tobaru) - Port forwarder with allowlists, IP and TLS SNI/ALPN rule-based routing, iptables support, round-robin forwarding (load balancing), and hot reloading.
*  <b><code>&nbsp;&nbsp;6555⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;414🍴</code></b> [LemmyNet/lemmy](https://github.com/LemmyNet/lemmy) — A link aggregator / reddit clone for the fediverse [![Build Status](https://cloud.drone.io/api/badges/LemmyNet/lemmy/status.svg)](https://cloud.drone.io/LemmyNet/lemmy)
*  <b><code>&nbsp;&nbsp;&nbsp;108⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [MASQ-Project/Node](https://github.com/MASQ-Project/Node) — MASQ Node software provides a decentralized mesh-network of nodes for global users to access normal internet content - next evolution of tech beyond Tor & VPN [![build badge](https://github.com/MASQ-Project/Node/actions/workflows/ci-matrix.yml/badge.svg)](https://github.com/MASQ-Project/Node/actions)
*  <b><code>&nbsp;&nbsp;1737⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [Plume-org/Plume](https://github.com/Plume-org/Plume) — ActivityPub federating blogging application [![build badge](https://api.travis-ci.org/Plume-org/Plume.svg?branch=master)](https://travis-ci.org/Plume-org/Plume)
*  <b><code>&nbsp;&nbsp;&nbsp;661⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Revolt/backend](https://github.com/revoltchat/backend) - User-first chat platform built with modern web technologies.
*  <b><code>&nbsp;&nbsp;3117⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [spikecodes/libreddit](https://github.com/spikecodes/libreddit) - An alternative private front-end to Reddit

### Web Servers

*  <b><code>&nbsp;&nbsp;&nbsp;346⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [joseluisq/static-web-server](https://github.com/joseluisq/static-web-server) — A blazing fast and asynchronous web server for static files-serving. ⚡ [![CI](https://github.com/joseluisq/static-web-server/actions/workflows/devel.yml/badge.svg)](https://github.com/joseluisq/static-web-server/actions/workflows/devel.yml?query=branch%3Amaster)
*  <b><code>&nbsp;&nbsp;&nbsp;664⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [mufeedvh/binserve](https://github.com/mufeedvh/binserve) — A blazingly fast static web server with routing, templating, and security in a single binary you can set up with zero code [![build badge](https://github.com/mufeedvh/binserve/workflows/CICD/badge.svg?branch=master)](https://github.com/mufeedvh/binserve/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;118⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [orhun/rustypaste](https://github.com/orhun/rustypaste) — A minimal file upload/pastebin service ![https://github.com/orhun/rustypaste/actions](https://img.shields.io/github/workflow/status/orhun/rustypaste/Continuous%20Integration/master?label=build)
*  <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [ronanyeah/rust-hasura](https://github.com/ronanyeah/rust-hasura) — A demonstration of how a Rust GraphQL server can be used as a remote schema with 🌎 [Hasura](hasura.io/) ![Rust](https://github.com/ronanyeah/rust-hasura/workflows/Rust/badge.svg?branch=master)
*  <b><code>&nbsp;&nbsp;3461⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;193🍴</code></b> [svenstaro/miniserve](https://github.com/svenstaro/miniserve) — A small, self-contained cross-platform CLI tool that allows you to just grab the binary and serve some file(s) via HTTP [![build badge](https://github.com/svenstaro/miniserve/workflows/CI/badge.svg?branch=master)](https://github.com/svenstaro/miniserve/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;353⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [thecoshman/http](https://github.com/thecoshman/http) — Host These Things Please — A basic http server for hosting a folder fast and simply [![build badge](https://api.travis-ci.org/thecoshman/http.svg?branch=master)](https://travis-ci.org/thecoshman/http)
*  <b><code>&nbsp;&nbsp;&nbsp;684⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [TheWaWaR/simple-http-server](https://github.com/TheWaWaR/simple-http-server) — simple static http server
*  <b><code>&nbsp;&nbsp;&nbsp;161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [wyhaya/see](https://github.com/wyhaya/see) — Static HTTP file server [![Build Status](https://api.travis-ci.org/wyhaya/see.svg?branch=master)](https://travis-ci.org/wyhaya/see)

## Development tools

* 🌎 [clippy](crates.io/crates/clippy) — Rust lints [![build badge](https://api.travis-ci.com/rust-lang/rust-clippy.svg?branch=master)](https://travis-ci.org/rust-lang/rust-clippy)
*  <b><code>&nbsp;&nbsp;&nbsp;763⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [clog-tool/clog-cli](https://github.com/clog-tool/clog-cli) — generates a changelog from git metadata  🌎 [conventional changelog](blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html)) [![build badge](https://api.travis-ci.org/clog-tool/clog-cli.svg?branch=master)](https://travis-ci.org/clog-tool/clog-cli)
*  <b><code>&nbsp;&nbsp;&nbsp;224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [comtrya](https://github.com/comtrya/comtrya) — A configuration management tool for localhost / dotfiles [![build badge](https://github.com/comtrya/comtrya/actions/workflows/main.yaml/badge.svg)](https://github.com/comtrya/comtrya/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;745⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [create-rust-app](https://github.com/Wulf/create-rust-app) — Set up a modern rust+react web app by running one command. [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/create-rust-app)
*  <b><code>&nbsp;&nbsp;&nbsp;356⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [dan-t/rusty-tags](https://github.com/dan-t/rusty-tags) — create ctags/etags for a cargo project and all of its dependencies [![build badge](https://api.travis-ci.org/dan-t/rusty-tags.svg?branch=master)](https://travis-ci.org/dan-t/rusty-tags)
*  <b><code>&nbsp;&nbsp;&nbsp;361⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [datanymizer/datanymizer](https://github.com/datanymizer/datanymizer) - Powerful database anonymizer with flexible rules [![build badge](https://github.com/datanymizer/datanymizer/workflows/CI/badge.svg?branch=main)](https://github.com/datanymizer/datanymizer/actions?query=workflow%3ACI+branch%3Amain)
* 🌎 [delta](crates.io/crates/git-delta) — A syntax-highlighter for git and diff output[![build badge](https://github.com/dandavison/delta/workflows/Continuous%20Integration/badge.svg)](https://github.com/dandavison/delta//actions)
*  <b><code>&nbsp;&nbsp;1424⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;125🍴</code></b> [dotenv-linter](https://github.com/dotenv-linter/dotenv-linter) — Linter for `.env` files [![build badge](https://github.com/dotenv-linter/dotenv-linter/workflows/CI/badge.svg?branch=master)](https://github.com/dotenv-linter/dotenv-linter/actions?query=workflow%3ACI+branch%3Amaster)
*  <b><code>&nbsp;&nbsp;1462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [dprint](https://github.com/dprint/dprint) — A pluggable and configurable code formatting platform [![build badge](https://github.com/dprint/dprint/workflows/CI/badge.svg)](https://github.com/dprint/dprint/actions?query=workflow%3ACI)
*  <b><code>&nbsp;&nbsp;&nbsp;366⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [fw](https://github.com/brocode/fw) — workspace productivity booster [![Rust](https://github.com/brocode/fw/actions/workflows/rust.yml/badge.svg)](https://github.com/brocode/fw/actions/workflows/rust.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;988⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [geiger](https://github.com/rust-secure-code/cargo-geiger) — A program that list statistics related to usage of unsafe Rust code in a Rust crate and all its dependencies [![Build Status](https://dev.azure.com/cargo-geiger/cargo-geiger/_apis/build/status/rust-secure-code.cargo-geiger?branchName=master)](https://dev.azure.com/cargo-geiger/cargo-geiger/_build/latest?definitionId=1&branchName=master)
*  <b><code>&nbsp;&nbsp;4415⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [git-cliff](https://github.com/orhun/git-cliff) — A highly customizable Changelog Generator that follows Conventional Commit specifications ![https://github.com/orhun/git-cliff/actions](https://img.shields.io/github/workflow/status/orhun/git-cliff/Continuous%20Integration/main?label=build)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [git-journal](https://github.com/saschagrunert/git-journal/) — The Git Commit Message and Changelog Generation Framework [![build badge](https://api.travis-ci.org/saschagrunert/git-journal.svg?branch=master)](https://travis-ci.org/saschagrunert/git-journal)
*  <b><code>&nbsp;&nbsp;6402⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [just](https://github.com/casey/just) — A handy command runner for project-specific tasks [![build badge](https://api.travis-ci.org/casey/just.svg?branch=master)](https://travis-ci.org/casey/just)
*  <b><code>&nbsp;&nbsp;&nbsp;693⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [mask](https://github.com/jacobdeichert/mask) — A CLI task runner defined by a simple markdown file [![build badge](https://github.com/jacobdeichert/mask/workflows/CI/badge.svg?branch=master)](https://github.com/jacobdeichert/mask/actions?query=workflow%3ACI)
*  <b><code>&nbsp;&nbsp;&nbsp;239⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Module Linker](https://github.com/fiatjaf/module-linker) — Extension that adds `<a>` links to references in `mod`, `use` and `extern crate` statements at GitHub.
*  <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [ptags](https://github.com/dalance/ptags) — A parallel universal-ctags wrapper for git repository [![Build Status](https://api.travis-ci.org/dalance/ptags.svg?branch=master)](https://travis-ci.org/dalance/ptags)
*  <b><code>&nbsp;&nbsp;3348⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;288🍴</code></b> [Racer](https://github.com/racer-rust/racer) — code completion for Rust [![build badge](https://api.travis-ci.org/racer-rust/racer.svg?branch=master)](https://travis-ci.org/racer-rust/racer)
*  <b><code>&nbsp;&nbsp;3563⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;266🍴</code></b> [Rust Language Server](https://github.com/rust-lang/rls) — A server that runs in the background, providing IDEs, editors, and other tools with information about Rust programs
*  <b><code>&nbsp;&nbsp;&nbsp;831⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Rust Search Extension](https://github.com/huhu/rust-search-extension) — A handy browser extension to search crates and docs in address bar (omnibox). [![Build Status](https://github.com/huhu/rust-search-extension/workflows/build/badge.svg?branch=master)](https://github.com/huhu/rust-search-extension/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;764⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [rust-lang/rustfix](https://github.com/rust-lang/rustfix)  — automatically applies the suggestions made by rustc
*  <b><code>&nbsp;&nbsp;4534⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;722🍴</code></b> [rustfmt](https://github.com/rust-lang/rustfmt) — A Rust code formatter [![build badge](https://api.travis-ci.com/rust-lang/rustfmt.svg?branch=master)](https://app.travis-ci.com/github/rust-lang/rustfmt)
*  <b><code>&nbsp;&nbsp;4801⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;745🍴</code></b> [Rustup](https://github.com/rust-lang/rustup) — the Rust toolchain installer [![build badge](https://github.com/rust-lang/rustup/workflows/Linux%20(master)/badge.svg?branch=master)](https://github.com/rust-lang/rustup/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [scriptisto](https://github.com/igor-petruk/scriptisto) A language-agnostic "shebang interpreter" that enables you to write one file scripts in compiled languages. [![Build Status](https://cloud.drone.io/api/badges/igor-petruk/scriptisto/status.svg)](https://cloud.drone.io/igor-petruk/scriptisto)
*  <b><code>&nbsp;&nbsp;&nbsp;892⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [synth](https://github.com/shuttle-hq/synth) — A declarative data generation engine.

### Build system

* 🌎 [Cargo](crates.io/) — the Rust package manager
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [cargo-all-features](https://github.com/frewsxcv/cargo-all-features) - A configurable subcommand to simplify testing, building and much more for all combinations of features [![CI](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml/badge.svg)](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml)
  * 🌎 [cargo-benchcmp](crates.io/crates/cargo-benchcmp) — A utility to compare Rust micro-benchmarks [![build badge](https://api.travis-ci.org/BurntSushi/cargo-benchcmp.svg?branch=master)](https://travis-ci.org/BurntSushi/cargo-benchcmp)
  * 🌎 [cargo-bitbake](crates.io/crates/cargo-bitbake) — A cargo extension that can generate BitBake recipes utilizing the classes from meta-rust [![build badge](https://api.travis-ci.org/cardoe/cargo-bitbake.svg?branch=master)](https://travis-ci.org/cardoe/cargo-bitbake)
  * 🌎 [cargo-cache](crates.io/crates/cargo-cache) — inspect/manage/clean your cargo cache (`~/.cargo/`/`${CARGO_HOME}`), print sizes etc [![Build Status](https://github.com/matthiaskrgr/cargo-cache/workflows/ci/badge.svg?branch=master)](https://github.com/matthiaskrgr/cargo-cache/actions)
  * 🌎 [cargo-check](crates.io/crates/cargo-check) — A wrapper around `cargo rustc -- -Zno-trans` which can be helpful for running a faster compile if you only need correctness checks [![build badge](https://api.travis-ci.org/rsolomo/cargo-check.svg?branch=master)](https://travis-ci.org/rsolomo/cargo-check)
  * 🌎 [cargo-count](crates.io/crates/cargo-count) — lists source code counts and details about cargo projects, including unsafe statistics [![build badge](https://api.travis-ci.org/kbknapp/cargo-count.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-count)
  * 🌎 [cargo-deb](crates.io/crates/cargo-deb) — Generates binary Debian packages [![build badge](https://api.travis-ci.org/mmstick/cargo-deb.svg?branch=master)](https://travis-ci.org/mmstick/cargo-deb)
  * 🌎 [cargo-deps](crates.io/crates/cargo-deps) — build dependency graphs of Rust projects [![build badge](https://api.travis-ci.com/m-cat/cargo-deps.svg?branch=master)](https://travis-ci.org/m-cat/cargo-deps)
  * 🌎 [cargo-do](crates.io/crates/cargo-do) — run multiple cargo commands in a row [![build badge](https://api.travis-ci.org/pwoolcoc/cargo-do.svg?branch=master)](https://travis-ci.org/pwoolcoc/cargo-do)
  * 🌎 [cargo-ebuild](crates.io/crates/cargo-ebuild) — cargo extension that can generate ebuilds using the in-tree eclasses [![build badge](https://api.travis-ci.org/cardoe/cargo-ebuild.svg?branch=master)](https://travis-ci.org/cardoe/cargo-ebuild)
  * 🌎 [cargo-edit](crates.io/crates/cargo-edit) — allows you to add and list dependencies by reading/writing to your Cargo.toml file from the command line [![build badge](https://api.travis-ci.org/killercup/cargo-edit.svg?branch=master)](https://travis-ci.org/killercup/cargo-edit)
  *  <b><code>&nbsp;&nbsp;1041⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [cargo-generate](https://github.com/cargo-generate/cargo-generate) A generator of a rust project by leveraging a pre-existing git repository as a template.
  * 🌎 [cargo-graph](crates.io/crates/cargo-graph) — updated fork of `cargo-dot` with additional features. Unmaintained, see `cargo-deps` [![build badge](https://api.travis-ci.org/kbknapp/cargo-graph.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-graph)
  * 🌎 [cargo-info](crates.io/crates/cargo-info) — queries crates.io for crates details from command line [![build badge](https://api.travis-ci.org/imp/cargo-info.svg?branch=master)](https://travis-ci.org/imp/cargo-info)
  * 🌎 [cargo-license](crates.io/crates/cargo-license) — A cargo subcommand to quickly view the licenses of all dependencies. [![build badge](https://api.travis-ci.org/onur/cargo-license.svg?branch=master)](https://travis-ci.org/onur/cargo-license)
  * 🌎 [cargo-make](crates.io/crates/cargo-make) — Rust task runner and build tool. [![build badge](https://api.travis-ci.org/sagiegurari/cargo-make.svg?branch=master)](https://travis-ci.org/sagiegurari/cargo-make)
  * 🌎 [cargo-modules](crates.io/crates/cargo-modules) — A cargo plugin for showing a tree-like overview of a crate's modules. [![build badge](https://api.travis-ci.org/regexident/cargo-modules.svg?branch=master)](https://travis-ci.org/regexident/cargo-modules)
  * 🌎 [cargo-multi](crates.io/crates/cargo-multi) — runs specified cargo command on multiple crates [![build badge](https://api.travis-ci.org/imp/cargo-multi.svg?branch=master)](https://travis-ci.org/imp/cargo-multi)
  * 🌎 [cargo-outdated](crates.io/crates/cargo-outdated) — displays when newer versions of Rust dependencies are available, or out of date [![build badge](https://api.travis-ci.org/kbknapp/cargo-outdated.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-outdated)
  * 🌎 [cargo-release](crates.io/crates/cargo-release) — tool for releasing git-managed cargo project, build, tag, publish, doc and push [![Rust](https://github.com/crate-ci/cargo-release/actions/workflows/ci.yml/badge.svg)](https://github.com/crate-ci/cargo-release/actions/workflows/rust.yml)
  * 🌎 [cargo-script](crates.io/crates/cargo-script) — lets people quickly and easily run Rust "scripts" which can make use of Cargo's package ecosystem [![build badge](https://api.travis-ci.org/DanielKeep/cargo-script.svg?branch=master)](https://travis-ci.org/DanielKeep/cargo-script)
  * 🌎 [cargo-update](crates.io/crates/cargo-update) — cargo subcommand for checking and applying updates to installed executables [![build badge](https://api.travis-ci.org/nabijaczleweli/cargo-update.svg?branch=master)](https://travis-ci.org/nabijaczleweli/cargo-update)
  * 🌎 [cargo-watch](crates.io/crates/cargo-watch) — utility for cargo to compile projects when sources change [![build badge](https://api.travis-ci.org/passcod/cargo-watch.svg?branch=master)](https://travis-ci.org/passcod/cargo-watch)
  *  <b><code>&nbsp;&nbsp;1551⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand) — Expand macros in your source code
* CMake
  *  <b><code>&nbsp;&nbsp;&nbsp;129⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Devolutions/CMakeRust](https://github.com/Devolutions/CMakeRust) — useful for integrating a Rust library into a CMake project
  *  <b><code>&nbsp;&nbsp;&nbsp;102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [SiegeLord/RustCMake](https://github.com/SiegeLord/RustCMake) — an example project showing usage of CMake with Rust [![build badge](https://api.travis-ci.org/SiegeLord/RustCMake.svg?branch=master)](https://travis-ci.org/SiegeLord/RustCMake)
*  <b><code>&nbsp;&nbsp;2099⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Fleet](https://github.com/dimensionhq/fleet)  🌎 [fleet-rs](crates.io/crates/fleet-rs)] - The blazing fast build tool for Rust.
* Github actions
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [icepuma/rust-action](https://github.com/icepuma/rust-action) — rust github action
  *  <b><code>&nbsp;&nbsp;&nbsp;209⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [peaceiris/actions-mdbook](https://github.com/peaceiris/actions-mdbook) — GitHub Actions for mdBook

### Debugging

* GDB
  *  <b><code>&nbsp;&nbsp;8706⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;519🍴</code></b> [gdbgui](https://github.com/cs01/gdbgui) — Browser based frontend for gdb to debug C, C++, Rust, and go. [![build badge](https://api.travis-ci.org/cs01/gdbgui.svg?branch=master)](https://travis-ci.org/cs01/gdbgui)
* LLDB
  * 🌎 [CodeLLDB](marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — A LLDB extension for 🌎 [Visual Studio Code](code.visualstudio.com/).

### Deployment

* Docker
  *  <b><code>&nbsp;&nbsp;1235⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [emk/rust-musl-builder](https://github.com/emk/rust-musl-builder) — Docker images for compiling static Rust binaries using musl-libc and musl-gcc, with static versions of useful C libraries
  *  <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [kpcyrd/mini-docker-rust](https://github.com/kpcyrd/mini-docker-rust) — An example project for very small rust docker images [![build badge](https://api.travis-ci.org/kpcyrd/mini-docker-rust.svg?branch=master)](https://travis-ci.org/kpcyrd/mini-docker-rust)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [liuchong/docker-rustup](https://github.com/liuchong/docker-rustup) — A multiple version (with musl tools) Rust Docker image
  *  <b><code>&nbsp;&nbsp;&nbsp;680⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [LukeMathWalker/cargo-chef](https://github.com/LukeMathWalker/cargo-chef) - A tool and pre-built images for caching compiling remote dependencies between Docker builds.
  *  <b><code>&nbsp;&nbsp;&nbsp;299⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [messense/rust-musl-cross](https://github.com/messense/rust-musl-cross) — Docker images for compiling static Rust binaries using musl-cross [![build badge](https://api.travis-ci.org/messense/rust-musl-cross.svg?branch=master)](https://travis-ci.org/messense/rust-musl-cross)
  *  <b><code>&nbsp;&nbsp;&nbsp;291⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [rust-lang-nursery/docker-rust](https://github.com/rust-lang/docker-rust) — the official Rust Docker image
* Github Pages
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [wasm-template-rust](https://github.com/sn99/wasm-template-rust) — A wasm template for Rust to publish to gh-pages without npm-deploy
* Heroku
  *  <b><code>&nbsp;&nbsp;&nbsp;496⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [emk/heroku-buildpack-rust](https://github.com/emk/heroku-buildpack-rust) — A buildpack for Rust applications on Heroku

### Embedded
 🌎 [Rust Embedded](rust-embedded.org/) focuses on improving the end-to-end experience of using Rust in resource-constrained environments and non-traditional platforms. See  <b><code>&nbsp;&nbsp;3440⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;250🍴</code></b> [awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) for a curated, and more extended list of embedded Rust resources.

* Arduino
  *  <b><code>&nbsp;&nbsp;&nbsp;579⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [avr-rust/ruduino](https://github.com/avr-rust/ruduino) Reusable components for the Arduino Uno.
* Cross compiling
  *  <b><code>&nbsp;&nbsp;2167⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [japaric/rust-cross](https://github.com/japaric/rust-cross) — everything you need to know about cross compiling Rust programs [![build badge](https://api.travis-ci.org/japaric/rust-cross.svg?branch=master)](https://travis-ci.org/japaric/rust-cross)
  *  <b><code>&nbsp;&nbsp;&nbsp;965⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [japaric/xargo](https://github.com/japaric/xargo) — effortless cross compilation of Rust programs to custom bare-metal targets like ARM Cortex-M [![build badge](https://api.travis-ci.org/japaric/xargo.svg?branch=master)](https://travis-ci.org/japaric/xargo)
* Espressif
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [esp-rs](https://github.com/esp-rs) home to a number of community projects enabling the use of the Rust programming language on various SoCs and modules produced by Espressif Systems.
* nRF
  *  <b><code>&nbsp;&nbsp;&nbsp;305⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [nrf-rs/nrf-hal](https://github.com/nrf-rs/nrf-hal) — A Rust HAL for the nRF family of devices
[![build badge](https://api.travis-ci.org/nrf-rs/nrf-hal.svg?branch=master)](https://travis-ci.org/nrf-rs/nrf-hal)

### FFI

See also 🌎 [Foreign Function Interface](doc.rust-lang.org/book/first-edition/ffi.html),  [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/) (a collection of examples of using code written in Rust from other languages) and  <b><code>&nbsp;&nbsp;1028⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;165🍴</code></b> [FFI examples written in Rust](https://github.com/alexcrichton/rust-ffi-examples).

* C
  *  <b><code>&nbsp;&nbsp;1490⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;202🍴</code></b> [rlhunt/cbindgen](https://github.com/eqrion/cbindgen) — generates C header files from Rust source files. Used in Gecko for WebRender [![build badge](https://api.travis-ci.org/eqrion/cbindgen.svg?branch=master)](https://travis-ci.org/eqrion/cbindgen)
  *  <b><code>&nbsp;&nbsp;&nbsp;188⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Sean1708/rusty-cheddar](https://github.com/Sean1708/rusty-cheddar) — generates C header files from Rust source files [![build badge](https://api.travis-ci.org/Sean1708/rusty-cheddar.svg?branch=master)](https://travis-ci.org/Sean1708/rusty-cheddar)
* C++
  *  <b><code>&nbsp;&nbsp;4002⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;222🍴</code></b> [dtolnay/cxx](https://github.com/dtolnay/cxx) — Safe interop between Rust and C++ [![build badge](https://img.shields.io/badge/github-dtolnay/cxx-8da0cb?style=for-the-badge&labelColor=555555&logo=github)](https://github.com/dtolnay/cxx)
  * 🌎 [rust-cpp](crates.io/crates/cpp) - Embed C++ code directly in Rust. [![Build Status](https://api.travis-ci.org/mystor/rust-cpp.svg?branch=master)](https://travis-ci.org/mystor/rust-cpp) [![Build status](https://ci.appveyor.com/api/projects/status/uu76vmcrwnjqra0u/branch/master?svg=true)](https://ci.appveyor.com/project/mystor/rust-cpp/branch/master)
  *  <b><code>&nbsp;&nbsp;2851⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;545🍴</code></b> [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen) — A Rust bindings generator
* Erlang
  *  <b><code>&nbsp;&nbsp;3301⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [rusterlium/rustler](https://github.com/rusterlium/rustler) — safe Rust bridge for creating Erlang NIF functions [![build badge](https://api.travis-ci.org/rusterlium/rustler.svg?branch=master)](https://travis-ci.org/rusterlium/rustler)
* Haskell
  *  <b><code>&nbsp;&nbsp;&nbsp;294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [mgattozzi/curryrs](https://github.com/mgattozzi/curryrs) — Bridge the gap between Haskell and Rust
* Java
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [bennettanderson/rjni](https://github.com/benanders/rjni) — use Java from Rust
  *  <b><code>&nbsp;&nbsp;&nbsp;311⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [drrb/java-rust-example](https://github.com/drrb/java-rust-example) — use Rust from Java [![build badge](https://api.travis-ci.org/drrb/java-rust-example.svg?branch=master)](https://travis-ci.org/drrb/java-rust-example)
  * 🌎 [j4rs](crates.io/crates/j4rs) — use Java from Rust [![build badge](https://api.travis-ci.org/astonbitecode/j4rs.svg?branch=master)](https://travis-ci.org/astonbitecode/j4rs)
  * 🌎 [jni](crates.io/crates/jni) — use Rust from Java [![build badge](https://api.travis-ci.org/jni-rs/jni-rs.svg?branch=master)](https://travis-ci.org/jni-rs/jni-rs)
  * 🌎 [jni-sys](crates.io/crates/jni-sys) — Rust definitions corresponding to jni.h [![build badge](https://api.travis-ci.org/sfackler/rust-jni-sys.svg?branch=master)](https://travis-ci.org/sfackler/rust-jni-sys)
  * 🌎 [rucaja](crates.io/crates/rucaja) — use Java from Rust [![build badge](https://api.travis-ci.org/kud1ing/rucaja.svg?branch=master)](https://travis-ci.org/kud1ing/rucaja)
* Lua
  *  <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [jcmoyer/rust-lua53](https://github.com/jcmoyer/rust-lua53) — Lua 5.3 bindings for Rust [![build badge](https://api.travis-ci.org/jcmoyer/rust-lua53.svg?branch=master)](https://travis-ci.org/jcmoyer/rust-lua53)
  *  <b><code>&nbsp;&nbsp;&nbsp;120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [lilyball/rust-lua](https://github.com/lilyball/rust-lua) — Safe Rust bindings to Lua 5.1 [![build badge](https://api.travis-ci.org/lilyball/rust-lua.svg?branch=master)](https://travis-ci.org/lilyball/rust-lua)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [tickbh/td_rlua](https://github.com/tickbh/td_rlua)  🌎 [td_rlua](crates.io/crates/td_rlua)] — Zero-cost high-level lua 5.3 wrapper for Rust [![build badge](https://api.travis-ci.org/tickbh/td_rlua.svg?branch=master)](https://travis-ci.org/tickbh/td_rlua)
  *  <b><code>&nbsp;&nbsp;&nbsp;481⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [tomaka/hlua](https://github.com/tomaka/hlua) — Rust library to interface with Lua [![build badge](https://api.travis-ci.org/tomaka/hlua.svg?branch=master)](https://travis-ci.org/tomaka/hlua)
* mruby
  *  <b><code>&nbsp;&nbsp;&nbsp;199⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [anima-engine/mrusty](https://github.com/anima-engine/mrusty) — mruby safe bindings for Rust [![build badge](https://api.travis-ci.org/anima-engine/mrusty.svg?branch=master)](https://travis-ci.org/anima-engine/mrusty)
* Node.js
  *  <b><code>&nbsp;&nbsp;&nbsp;313⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [infinyon/node-bindgen](https://github.com/infinyon/node-bindgen) - Easy way to generate nodejs module using Rust
  *  <b><code>&nbsp;&nbsp;6728⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;269🍴</code></b> [neon-bindings/neon](https://github.com/neon-bindings/neon) — Rust bindings for writing safe and fast native Node.js modules [![build badge](https://api.travis-ci.org/neon-bindings/neon.svg?branch=master)](https://travis-ci.org/neon-bindings/neon)
* Objective-C
  *  <b><code>&nbsp;&nbsp;&nbsp;321⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc) — Objective-C Runtime bindings and wrapper for Rust
* Python
  *  <b><code>&nbsp;&nbsp;1606⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython) — Python bindings [![build badge](https://api.travis-ci.org/dgrunwald/rust-cpython.svg?branch=master)](https://travis-ci.org/dgrunwald/rust-cpython)
  *  <b><code>&nbsp;&nbsp;&nbsp;737⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [getsentry/milksnake](https://github.com/getsentry/milksnake) — extension for python setuptools that allows you to distribute dynamic linked libraries in Python wheels in the most portable way imaginable.
  *  <b><code>&nbsp;&nbsp;6238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;424🍴</code></b> [PyO3/PyO3](https://github.com/PyO3/PyO3) — Rust bindings for the Python interpreter [![build badge](https://api.travis-ci.org/PyO3/pyo3.svg?branch=master)](https://travis-ci.org/PyO3/pyo3)
* Ruby
  *  <b><code>&nbsp;&nbsp;&nbsp;803⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [d-unseductable/ruru](https://github.com/d-unseductable/ruru) — native Ruby extensions written in Rust [![build badge](https://api.travis-ci.org/d-unseductable/ruru.svg?branch=master)](https://travis-ci.org/d-unseductable/ruru)
  *  <b><code>&nbsp;&nbsp;&nbsp;658⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [danielpclark/rutie](https://github.com/danielpclark/rutie) — native Ruby extensions written in Rust and vice versa [![Build Status](https://api.travis-ci.org/danielpclark/rutie.svg?branch=master)](https://travis-ci.org/danielpclark/rutie)
  *  <b><code>&nbsp;&nbsp;1978⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [tildeio/helix](https://github.com/tildeio/helix) — write Ruby classes in Rust [![build badge](https://api.travis-ci.org/tildeio/helix.svg?branch=master)](https://travis-ci.org/tildeio/helix)
* Web Assembly
  *  <b><code>&nbsp;&nbsp;&nbsp;288⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [rhysd/wain](https://github.com/rhysd/wain) - wain: WebAssembly INterpreter from scratch in Safe Rust with zero dependency [![build badge](https://github.com/rhysd/wain/workflows/CI/badge.svg?branch=master&event=push)](https://github.com/rhysd/wain/actions?query=workflow%3ACI+branch%3Amaster+event%3Apush)
  *  <b><code>&nbsp;&nbsp;5468⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;759🍴</code></b> [rustwasm/wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) — A project for facilitating high-level interactions between wasm modules and JS. [![build badge](https://api.travis-ci.com/rustwasm/wasm-bindgen.svg?branch=master)](https://travis-ci.org/rustwasm/wasm-bindgen)
  *  <b><code>&nbsp;&nbsp;4413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;296🍴</code></b> [rustwasm/wasm-pack](https://github.com/rustwasm/wasm-pack) — :package: :sparkles: pack up the wasm and publish it to npm! [![build badge](https://api.travis-ci.com/rustwasm/wasm-pack.svg?branch=master)](https://travis-ci.org/rustwasm/wasm-pack)

### IDEs

See also 🌎 [Are we (I)DE yet?](areweideyet.com/) and 🌎 [Rust Tools](www.rust-lang.org/tools).

  * 🌎 [Atom](atom.io/)
    *  <b><code>&nbsp;&nbsp;&nbsp;229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [rust-lang/atom-ide-rust](https://github.com/rust-lang/atom-ide-rust) — Rust IDE support for Atom, powered by the Rust Language Server (RLS) [![Build Status](https://api.travis-ci.com/rust-lang/atom-ide-rust.svg?branch=master)](https://app.travis-ci.com/grust-lang/atom-ide-rust)
  * 🌎 [Eclipse](www.eclipse.org/)
    *  <b><code>&nbsp;&nbsp;&nbsp;183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Eclipse Corrosion](https://github.com/eclipse/corrosion)
  * 🌎 [Emacs](www.gnu.org/software/emacs/)
    *  <b><code>&nbsp;&nbsp;&nbsp;394⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [emacs-racer](https://github.com/racer-rust/emacs-racer) — Autocompletion (see also 🌎 [company](company-mode.github.io) and  <b><code>&nbsp;&nbsp;1665⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;291🍴</code></b> [auto-complete](https://github.com/auto-complete/auto-complete))
    *  <b><code>&nbsp;&nbsp;&nbsp;110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [flycheck-rust](https://github.com/flycheck/flycheck-rust) — Rust support for  <b><code>&nbsp;&nbsp;2217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;425🍴</code></b> [Flycheck](https://github.com/flycheck/flycheck)
    *  <b><code>&nbsp;&nbsp;&nbsp;861⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;151🍴</code></b> [rust-mode](https://github.com/rust-lang/rust-mode) — Rust Major Mode
    *  <b><code>&nbsp;&nbsp;&nbsp;557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [rustic](https://github.com/brotzeit/rustic) - Rust development environment for Emacs [![build badge](https://github.com/brotzeit/rustic/workflows/CI/badge.svg)](https://github.com/brotzeit/rustic/actions?query=workflow%3ACI)
  * 🌎 [gitpod.io](gitpod.io) — Online IDE with full Rust support based on Rust Language Server
  * 🌎 [gnome-builder](wiki.gnome.org/Apps/Builder) native support for rust and cargo since Version 3.22.2
  * 🌎 [IntelliJ](www.jetbrains.com/idea/)
    *  <b><code>&nbsp;&nbsp;4029⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;343🍴</code></b> [intellij-rust/intellij-rust](https://github.com/intellij-rust/intellij-rust) — [![build badge](https://api.travis-ci.org/intellij-rust/intellij-rust.svg?branch=master)](https://travis-ci.org/intellij-rust/intellij-rust)
  * [Kakoune](http://kakoune.org/)
    *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [kak-lsp/kak-lsp](https://github.com/kak-lsp/kak-lsp/) — 🌎 [LSP](microsoft.github.io/language-server-protocol/) client. Implemented in Rust and supports rls out of the box.
  *  <b><code>&nbsp;&nbsp;&nbsp;171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Ride](https://github.com/madeso/ride) — [![build badge](https://api.travis-ci.org/madeso/ride.svg?branch=master)](https://travis-ci.org/madeso/ride)
  * 🌎 [Sublime Text](www.sublimetext.com/)
    *  <b><code>&nbsp;&nbsp;&nbsp;687⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [rust-lang/rust-enhanced](https://github.com/rust-lang/rust-enhanced) — official Rust package
  * 🌎 [Vim](vim.sourceforge.io/) — the ubiquitous text editor
    *  <b><code>&nbsp;&nbsp;3420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;276🍴</code></b> [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim) — 🌎 [LSP](microsoft.github.io/language-server-protocol/) client. Implemented in Rust and supports rls out of the box.
    *  <b><code>&nbsp;&nbsp;3177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;267🍴</code></b> [rust.vim](https://github.com/rust-lang/rust.vim) — provides file detection, syntax highlighting, formatting, Syntastic integration, and more.
    *  <b><code>&nbsp;&nbsp;&nbsp;624⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [vim-racer](https://github.com/racer-rust/vim-racer) — allows vim to use  <b><code>&nbsp;&nbsp;3348⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;288🍴</code></b> [Racer](https://github.com/racer-rust/racer) for Rust code completion and navigation.
  * Visual Studio
    *  <b><code>&nbsp;&nbsp;&nbsp;110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [dgriffen/rls-vs2017](https://github.com/ZoeyR/rls-vs2017) — Rust support for Visual Studio 2017 Preview [![build badge](https://ci.appveyor.com/api/projects/status/d2lxlincwninhsng?svg=true)](https://ci.appveyor.com/project/dgriffen/rls-vs2017)
    *  <b><code>&nbsp;&nbsp;&nbsp;692⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [PistonDevelopers/VisualRust](https://github.com/PistonDevelopers/VisualRust) — A Visual Studio extension for Rust [![Build status](https://ci.appveyor.com/api/projects/status/5nw5no10jj0y4p3f?svg=true)](https://ci.appveyor.com/project/vosen/visualrust)
  * 🌎 [Visual Studio Code](code.visualstudio.com/)
    * 🌎 [Better TOML](marketplace.visualstudio.com/items?itemName=bungcip.better-toml) - TOML support in vscode
    * 🌎 [CodeLLDB](marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — A LLDB extension
    *  <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [crates](https://github.com/serayuzgur/crates) — crates is an extension for crates.io dependencies. [![build badge](https://img.shields.io/vscode-marketplace/v/serayuzgur.crates.svg)](https://github.com/serayuzgur/crates) [![build badge](https://api.travis-ci.org/serayuzgur/crates.svg?branch=master)](https://travis-ci.org/serayuzgur/crates)
    * 🌎 [rust-analyzer](marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) — An alternative rust language server to the RLS
    * 🌎 [rust-lang/rls-vscode](marketplace.visualstudio.com/items?itemName=rust-lang.rust) — Rust support for Visual Studio Code (supports both RLS and rust-analyzer)

### Profiling

*  <b><code>&nbsp;&nbsp;2664⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs) — Statistics-driven benchmarking library for Rust [![Build Status](https://api.travis-ci.org/bheisler/criterion.rs.svg?branch=master)](https://travis-ci.org/bheisler/criterion.rs)
*  <b><code>&nbsp;&nbsp;2862⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [Bytehound](https://github.com/koute/bytehound) — A memory profiler for Linux
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [ellisonch/rust-stopwatch](https://github.com/ellisonch/rust-stopwatch) — A stopwatch library [![build badge](https://api.travis-ci.org/ellisonch/rust-stopwatch.svg?branch=master)](https://travis-ci.org/ellisonch/rust-stopwatch)
* FlameGraphs
  *  <b><code>&nbsp;&nbsp;&nbsp;603⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [llogiq/flame](https://github.com/llogiq/flame) — [![build badge](https://api.travis-ci.org/llogiq/flame.svg?branch=master)](https://travis-ci.org/llogiq/flame)
  *  <b><code>&nbsp;&nbsp;&nbsp;123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [mrhooray/torch](https://github.com/mrhooray/torch) — generates FlameGraphs based on DWARF Debug Info
*  <b><code>&nbsp;12161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;226🍴</code></b> [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine) — A command-line benchmarking tool [![Version info](https://img.shields.io/crates/v/hyperfine.svg)](https://crates.io/crates/hyperfine) [![Build Status](https://api.travis-ci.org/sharkdp/hyperfine.svg?branch=master)](https://travis-ci.org/sharkdp/hyperfine)

### Services

*  <b><code>&nbsp;&nbsp;&nbsp;341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [deps.rs](https://github.com/deps-rs/deps.rs) — Detect outdated or insecure dependencies
* 🌎 [docs.rs](docs.rs) — Automatic documentation generation of crates

### Static analysis

 🌎 [assert](crates.io/keywords/assert), 🌎 [static](crates.io/keywords/static)]

*  <b><code>&nbsp;&nbsp;&nbsp;732⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [facebookexperimental/MIRAI](https://github.com/facebookexperimental/mirai) — an abstract interpreter operating on Rust's mid-level intermediate representation (MIR) [![Continuous Integration](https://github.com/facebookexperimental/MIRAI/actions/workflows/rust.yml/badge.svg)](https://github.com/facebookexperimental/MIRAI/actions/workflows/rust.yml)
* 🌎 [static_assertions](crates.io/crates/static_assertions) — Compile-time assertions to ensure that invariants are met [![Build Status](https://api.travis-ci.org/nvzqz/static-assertions-rs.svg?branch=master)](https://travis-ci.org/nvzqz/static-assertions-rs/)

### Testing

 🌎 [test](crates.io/keywords/test), 🌎 [testing](crates.io/keywords/testing)]

* Code Coverage
  * 🌎 [tarpaulin](crates.io/crates/cargo-tarpaulin) — A code coverage tool designed for Rust [![build badge](https://api.travis-ci.org/repositories/xd009642/tarpaulin.svg?branch=master)](https://travis-ci.org/xd009642/tarpaulin)
* Continuous Integration
  *  <b><code>&nbsp;&nbsp;1148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [trust](https://github.com/japaric/trust) — A Travis CI and AppVeyor template to test your Rust crate on 5 architectures and publish binary releases of it for Linux, macOS and Windows
* Frameworks and Runners
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [AlKass/polish](https://github.com/AlKass/polish) — Mini Testing/Test-Driven Framework [![Build Status](https://api.travis-ci.org/AlKass/polish.svg?branch=master)](https://travis-ci.org/AlKass/polish) [![Crates Package Status](https://img.shields.io/crates/v/polish.svg)](https://crates.io/crates/polish)
  * 🌎 [cargo-dinghy](crates.io/crates/cargo-dinghy/) - A cargo extension to simplify running library tests and benches on smartphones and other small processor devices.
  * 🌎 [cucumber](crates.io/crates/cucumber) [![Latest Version](https://img.shields.io/crates/v/cucumber.svg)](https://crates.io/crates/cucumber) — An implementation of the Cucumber testing framework for Rust. Fully native, no external test runners or dependencies. [![Build Status](https://github.com/cucumber-rs/cucumber/workflows/CI/badge.svg?branch=master)](https://github.com/cucumber-rs/cucumber)
  * 🌎 [demonstrate](crates.io/crates/demonstrate) — Declarative Testing Framework [![Build Status](https://github.com/CookieBaughter/demonstrate/workflows/Continuous%20Integration/badge.svg?branch=master)](https://github.com/CookieBaughter/demonstrate)
  * 🌎 [rstest](crates.io/crates/rstest) — Fixture-based test framework for Rust [![Build Status](https://github.com/la10736/rstest/workflows/Test/badge.svg?branch=master)](https://github.com/la10736/rstest/actions)
  * 🌎 [speculate](crates.io/crates/speculate) — An RSpec inspired minimal testing framework for Rust
* Mocking and Test Data
  *  <b><code>&nbsp;&nbsp;&nbsp;790⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [asomers/mockall](https://github.com/asomers/mockall)  🌎 [mockall](crates.io/crates/mockall)] — A powerful mock object library for Rust. [![Cirrus Build Status](https://api.cirrus-ci.com/github/asomers/mockall.svg)](https://cirrus-ci.com/github/asomers/mockall)
  *  <b><code>&nbsp;&nbsp;&nbsp;471⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [fake-rs](https://github.com/cksac/fake-rs) —  A library for generating fake data [![build badge](https://api.travis-ci.org/repositories/cksac/fake-rs.svg?branch=master)](https://travis-ci.org/cksac/fake-rs)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [goldenfile](https://github.com/calder/rust-goldenfile)  🌎 [goldenfile](crates.io/crates/goldenfile)] - A library providing a simple API for goldenfile testing. [![build badge](https://api.travis-ci.org/calder/rust-goldenfile.svg?branch=master)](https://travis-ci.org/calder/rust-goldenfile)
  *  <b><code>&nbsp;&nbsp;&nbsp;294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [httpmock](https://github.com/alexliesenfeld/httpmock) — HTTP mocking [![build badge](https://dev.azure.com/alexliesenfeld/httpmock/_apis/build/status/alexliesenfeld.httpmock?branchName=master)](https://dev.azure.com/alexliesenfeld/httpmock/_build/latest?definitionId=2&branchName=master)
  * 🌎 [mockiato](crates.io/crates/mockiato) — A strict, yet friendly mocking library for Rust 2018 [![build badge](https://api.travis-ci.com/mockiato/mockiato.svg?branch=master)](https://app.travis-ci.com/github/mockiato/mockiato)
  * 🌎 [mockito](crates.io/crates/mockito) — HTTP mocking [![build badge](https://api.travis-ci.org/lipanski/mockito.svg?branch=master)](https://travis-ci.org/lipanski/mockito)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [nrxus/faux](https://github.com/nrxus/faux/) [![Latest Version](https://img.shields.io/crates/v/faux.svg)](https://crates.io/crates/faux) — A library to create mocks out of structs. ![build](https://github.com/nrxus/faux/workflows/test/badge.svg?branch=master)
* Property Testing and Fuzzing
  *  <b><code>&nbsp;&nbsp;&nbsp;502⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [mutagen](https://github.com/llogiq/mutagen)  🌎 [mutagen](crates.io/crates/mutagen)) — A source-level mutation testing framework (nightly only) [![build badge](https://api.travis-ci.org/llogiq/mutagen.svg?branch=master)](https://travis-ci.org/llogiq/mutagen)
  * 🌎 [proptest](crates.io/crates/proptest) — property testing framework inspired by the 🌎 [Hypothesis](hypothesis.works/) framework for Python [![build badge](https://api.travis-ci.org/altsysrq/proptest.svg?branch=master)](https://travis-ci.org/altsysrq/proptest)
  * 🌎 [quickcheck](crates.io/crates/quickcheck) — A Rust implementation of 🌎 [QuickCheck](wiki.haskell.org/Introduction_to_QuickCheck1) [![build badge](https://api.travis-ci.org/BurntSushi/quickcheck.svg?branch=master)](https://travis-ci.org/BurntSushi/quickcheck)
  *  <b><code>&nbsp;&nbsp;1245⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [rust-fuzz/afl.rs](https://github.com/rust-fuzz/afl.rs) — A Rust fuzzer, using 🌎 [AFL](lcamtuf.coredump.cx/afl/) [![build badge](https://api.travis-ci.org/rust-fuzz/afl.rs.svg?branch=master)](https://travis-ci.org/rust-fuzz/afl.rs)

### Transpiling

*  <b><code>&nbsp;&nbsp;2152⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [BayesWitnesses/m2cgen](https://github.com/BayesWitnesses/m2cgen) — A CLI tool to transpile trained classic machine learning models into a native Rust code with zero dependencies. [![GitHub Actions Status](https://github.com/BayesWitnesses/m2cgen/workflows/GitHub%20Actions/badge.svg?branch=master)](https://github.com/BayesWitnesses/m2cgen/actions)
*  <b><code>&nbsp;&nbsp;2647⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [immunant/c2rust](https://github.com/immunant/c2rust) — C to Rust translator and cross checker built atop Clang/LLVM. [![Build Status](https://api.travis-ci.org/immunant/c2rust.svg?branch=master)](https://travis-ci.org/immunant/c2rust)
*  <b><code>&nbsp;&nbsp;2108⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [jameysharp/corrode](https://github.com/jameysharp/corrode) — A C to Rust translator written in Haskell.

## Libraries

*  <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [perf-monitor-rs](https://github.com/larksuite/perf-monitor-rs) — A toolkit designed to be a foundation for applications to monitor their performance. [![crates.io](https://img.shields.io/crates/v/perf_monitor.svg)](https://crates.io/crates/perf_monitor)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Phate6660/nixinfo](https://github.com/Phate6660/nixinfo)  🌎 [crate](crates.io/crates/nixinfo)] — A lib crate for gathering system info such as cpu, distro, environment, kernel, etc.

### Artificial Intelligence

#### Genetic algorithms

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [innoave/genevo](https://github.com/innoave/genevo) — Execute genetic algorithm (GA) simulations in a customizable and extensible way.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [m-decoster/RsGenetic](https://github.com/m-decoster/RsGenetic) — Genetic Algorithm library in Rust. In maintenance mode.
*  <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Martin1887/oxigen](https://github.com/Martin1887/oxigen) — Fast, parallel, extensible and adaptable genetic algorithm library. A example using this library solves the N Queens problem for N = 255 in only few seconds and using less than 1 MB of RAM.
*  <b><code>&nbsp;&nbsp;&nbsp;102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [pkalivas/radiate](https://github.com/pkalivas/radiate) — A customizable parallel genetic programming engine capable of evolving solutions for supervised, unsupervised, and reinforcement learning problems. Comes with complete and customizable implementation of NEAT and Evtree. [![Build Status](https://api.travis-ci.com/pkalivas/radiate.svg?branch=master)](https://app.travis-ci.com/github/pkalivas/radiate)![Crates.io](https://img.shields.io/crates/v/radiate)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [willi-kappler/darwin-rs](https://github.com/willi-kappler/darwin-rs) — Evolutionary algorithms with Rust [![Build Status](https://api.travis-ci.org/willi-kappler/darwin-rs.svg?branch=master)](https://travis-ci.org/willi-kappler/darwin-rs)

#### Machine learning

See  🌎 [Machine learning](crates.io/keywords/machine-learning)]

See also 🌎 [About Rust’s Machine Learning Community](medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f) and 🌎 [Are we learning yet?](www.arewelearningyet.com).

*  <b><code>&nbsp;&nbsp;5481⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;275🍴</code></b> [autumnai/leaf](https://github.com/autumnai/leaf) — Open Machine Intelligence framework. [![Build Status](https://api.travis-ci.org/autumnai/leaf.svg?branch=master)](https://travis-ci.org/autumnai/leaf). Abandoned project. The most updated fork is [spearow/juice]( https://github.com/spearow/juice).
*  <b><code>&nbsp;&nbsp;5788⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;494🍴</code></b> [huggingface/tokenizers](https://github.com/huggingface/tokenizers) - Hugging Face's tokenizers for modern NLP pipelines written in Rust (original implementation) with bindings for Python. [![Build Status](https://github.com/huggingface/tokenizers/workflows/Rust/badge.svg?branch=master)](https://github.com/huggingface/tokenizers/actions)
*  <b><code>&nbsp;&nbsp;1741⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;150🍴</code></b> [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs) — Rust language bindings for PyTorch. [![Build Status](https://api.travis-ci.org/LaurentMazare/tch-rs.svg?branch=master)](https://travis-ci.org/LaurentMazare/tch-rs)
*  <b><code>&nbsp;&nbsp;&nbsp;530⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn) — Machine learning crate for Rust. [![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://app.circleci.com/pipelines/github/maciejkula/rustlearn)
*  <b><code>&nbsp;&nbsp;1811⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [rust-ml/linfa](https://github.com/rust-ml/linfa) — Machine learning framework.
*  <b><code>&nbsp;&nbsp;&nbsp;274⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [smartcorelib/smartcore](https://github.com/smartcorelib/smartcore) — Machine Learning Library In Rust [![Build Status](https://img.shields.io/circleci/build/github/smartcorelib/smartcore)](https://smartcorelib.org/)
*  <b><code>&nbsp;&nbsp;3747⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;342🍴</code></b> [tensorflow/rust](https://github.com/tensorflow/rust) — Rust language bindings for TensorFlow. [![Build Status](https://api.travis-ci.org/tensorflow/rust.svg?branch=master)](https://travis-ci.org/tensorflow/rust)

### Astronomy

 🌎 [astronomy](crates.io/keywords/astronomy)]

* 🌎 [fitsio](crates.io/crates/fitsio) — fits interface library wrapping cfitsio [![build badge](https://api.travis-ci.org/mindriot101/rust-fitsio.svg?branch=master)](https://travis-ci.org/mindriot101/rust-fitsio)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [flosse/rust-sun](https://github.com/flosse/rust-sun)  🌎 [sun](crates.io/crates/sun)] — A rust port of the JS library suncalc [![build badge](https://api.travis-ci.org/flosse/rust-sun.svg?branch=master)](https://travis-ci.org/flosse/rust-sun)
*  <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [saurvs/astro-rust](https://github.com/saurvs/astro-rust) — astronomy for Rust [![build badge](https://api.travis-ci.org/saurvs/astro-rust.svg?branch=master)](https://travis-ci.org/saurvs/astro-rust)

### Asynchronous

* 🌎 [async-std](async.rs/) [[async-std]](https://crates.io/crates/async-std) - Async version of the Rust standard library [![CI](https://github.com/async-rs/async-std/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/async-rs/async-std/actions/workflows/ci.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;135⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [dpc/mioco](https://github.com/dpc/mioco) — Scalable, coroutine-based, asynchronous IO handling library [![build badge](https://api.travis-ci.org/dpc/mioco.svg?branch=master)](https://travis-ci.org/dpc/mioco)
*  <b><code>&nbsp;&nbsp;4971⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;594🍴</code></b> [mio](https://github.com/tokio-rs/mio) — MIO is a lightweight IO library for Rust with a focus on adding as little overhead as possible over the OS abstractions [![build badge](https://api.travis-ci.org/tokio-rs/mio.svg?branch=master)](https://travis-ci.org/tokio-rs/mio)
*  <b><code>&nbsp;&nbsp;4423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;525🍴</code></b> [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs) — Zero-cost futures in Rust [![build badge](https://api.travis-ci.com/rust-lang/futures-rs.svg?branch=master)](https://travis-ci.org/rust-lang/futures-rs)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [TeaEntityLab/fpRust](https://github.com/TeaEntityLab/fpRust) — Monad/MonadIO, Handler, Coroutine/doNotation, Functional Programming features for Rust [![build badge](https://api.travis-ci.org/TeaEntityLab/fpRust.svg?branch=master)](https://travis-ci.org/TeaEntityLab/fpRust)
*  <b><code>&nbsp;&nbsp;1157⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Xudong-Huang/may](https://github.com/Xudong-Huang/may) — rust stackful coroutine library [![build badge](https://api.travis-ci.org/Xudong-Huang/may.svg?branch=master)](https://travis-ci.org/Xudong-Huang/may)
*  <b><code>&nbsp;&nbsp;&nbsp;451⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) — A coroutine I/O library with a working-stealing scheduler [![build badge](https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master)](https://travis-ci.org/zonyitoo/coio-rs)

### Audio and Music

 🌎 [audio](crates.io/keywords/audio)]

* 🌎 [hound](crates.io/crates/hound) — A WAV encoding and decoding library [![build badge](https://api.travis-ci.org/ruuda/hound.svg?branch=master)](https://travis-ci.org/ruuda/hound)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [insomnimus/nodi](https://github.com/insomnimus/nodi)  🌎 [nodi](crates.io/crates/nodi)] — A library for playback and abstraction of MIDI files. [![build badge](https://github.com/insomnimus/nodi/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/nodi/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [jhasse/ears](https://github.com/jhasse/ears) — A simple library to play Sounds and Musics, on top of OpenAL and libsndfile [![build badge](https://api.travis-ci.org/jhasse/ears.svg?branch=master)](https://travis-ci.org/jhasse/ears)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [musitdev/portmidi-rs](https://github.com/musitdev/portmidi-rs) — [PortMidi](http://portmedia.sourceforge.net/portmidi/) bindings [![build badge](https://api.travis-ci.org/musitdev/portmidi-rs.svg?branch=master)](https://travis-ci.org/musitdev/portmidi-rs)
*  <b><code>&nbsp;&nbsp;&nbsp;510⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [ozankasikci/rust-music-theory](https://github.com/ozankasikci/rust-music-theory) — A Rust music theory library [![Build Status](https://api.travis-ci.com/ozankasikci/rust-music-theory.svg?branch=master)](https://travis-ci.org/ozankasikci/rust-music-theory)
*  <b><code>&nbsp;&nbsp;&nbsp;805⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [pdeljanov/Symphonia](https://github.com/pdeljanov/Symphonia) — A pure Rust audio decoding and media demuxing library supporting AAC, FLAC, MP3, MP4, OGG, Vorbis, and WAV.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [RustAudio](https://github.com/RustAudio)
  *  <b><code>&nbsp;&nbsp;1536⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;243🍴</code></b> [RustAudio/cpal](https://github.com/RustAudio/cpal) - Low-level cross-platform audio I/O library in pure Rust. [![Actions Status](https://github.com/RustAudio/cpal/workflows/cpal/badge.svg?branch=master)](https://github.com/RustAudio/cpal/actions)
  *  <b><code>&nbsp;&nbsp;1008⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;154🍴</code></b> [RustAudio/rodio](https://github.com/RustAudio/rodio) — A Rust audio playback library [![Build Status](https://api.travis-ci.org/RustAudio/rodio.svg?branch=master)](https://travis-ci.org/RustAudio/rodio)
  *  <b><code>&nbsp;&nbsp;&nbsp;314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio) — PortAudio bindings [![build badge](https://api.travis-ci.org/RustAudio/rust-portaudio.svg?branch=master)](https://travis-ci.org/RustAudio/rust-portaudio)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Serial-ATA/lofty-rs](https://github.com/Serial-ATA/lofty-rs)  🌎 [lofty](crates.io/crates/lofty)] — A library for reading and editing the metadata of various audio formats [![build badge](https://github.com/Serial-ATA/lofty-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Serial-ATA/lofty-rs/actions)

### Authentication

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [constantoine/totp-rs](https://github.com/constantoine/totp-rs)  🌎 [totp-rs](crates.io/crates/totp-rs)] — 2fa library to generate and verify TOTP-based tokens ![Build Status](https://github.com/constantoine/totp-rs/workflows/Rust/badge.svg)
*  <b><code>&nbsp;&nbsp;&nbsp;966⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken) — 🌎 [JSON Web Token](en.wikipedia.org/wiki/JSON_Web_Token) lib in rust  [![Build Status](https://api.travis-ci.org/Keats/jsonwebtoken.svg?branch=master)](https://travis-ci.org/Keats/jsonwebtoken)
*  <b><code>&nbsp;&nbsp;&nbsp;516⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;105🍴</code></b> [oauth2](https://github.com/ramosbugs/oauth2-rs) — Extensible, strongly-typed Rust OAuth2 client library [![Build Status](https://api.travis-ci.org/ramosbugs/oauth2-rs.svg?branch=main)](https://travis-ci.org/ramosbugs/oauth2-rs)
*  <b><code>&nbsp;&nbsp;&nbsp;417⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [oxide-auth](https://github.com/HeroicKatora/oxide-auth) — A OAuth2 server library, for use in combination with actix or other frontends, featuring a set of configurable and pluggable backends [![Build Status](https://api.cirrus-ci.com/github/HeroicKatora/oxide-auth.svg?branch=master)](https://cirrus-ci.com/github/HeroicKatora/oxide-auth)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [sgrust01/jwtvault](https://github.com/sgrust01/jwtvault) — Async library to manage and orchestrate JWT workflow  [![Build Status](https://api.travis-ci.org/sgrust01/jwtvault.svg?branch=master)](https://travis-ci.org/sgrust01/jwtvault)
*  <b><code>&nbsp;&nbsp;&nbsp;162⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [yup-oauth2](https://github.com/dermesser/yup-oauth2) — An oauth2 client implementation providing the Device, Installed and Service Account flows [![Build Status](https://api.travis-ci.org/dermesser/yup-oauth2.svg?branch=master)](https://travis-ci.org/dermesser/yup-oauth2)

### Automotive

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [marcelbuesing/can-dbc](https://github.com/marcelbuesing/can-dbc)  🌎 [can-dbc](crates.io/crates/can-dbc)] — A parser for the DBC format [![build badge](https://api.travis-ci.org/marcelbuesing/can-dbc.svg?branch=dev)](https://travis-ci.org/marcelbuesing/can-dbc)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [marcelbuesing/tokio-socketcan-bcm](https://github.com/marcelbuesing/tokio-socketcan-bcm)  🌎 [tokio-socketcan-bcm](crates.io/crates/tokio-socketcan-bcm)] — Linux SocketCAN BCM support for tokio [![build badge](https://api.travis-ci.org/marcelbuesing/tokio-socketcan-bcm.svg?branch=master)](https://travis-ci.org/marcelbuesing/tokio-socketcan-bcm)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [mbr/socketcan](https://github.com/mbr/socketcan-rs)  🌎 [socketcan](crates.io/crates/socketcan)] — Linux SocketCAN library [![build badge](https://api.travis-ci.org/mbr/socketcan-rs.svg?branch=master)](https://travis-ci.org/mbr/socketcan-rs)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [oefd/tokio-socketcan](https://github.com/oefd/tokio-socketcan) [[tokio-socketcan]](https://crates.io/crates/tokio-socketcan)] — Linux SocketCAN support for tokio based on the socketcan crate
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Sensirion/lin-bus](https://github.com/Sensirion/lin-bus-rs)  🌎 [lin-bus](crates.io/crates/lin-bus)] — LIN bus driver traits and protocol implementation [![build badge](https://circleci.com/gh/Sensirion/lin-bus-rs.svg?style=svg)](https://app.circleci.com/pipelines/github/Sensirion/lin-bus-rs)

### Bioinformatics

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Rust-Bio](https://github.com/rust-bio) — bioinformatics libraries in Rust.

### Caching

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [aisk/rust-memcache](https://github.com/aisk/rust-memcache) — Memcached client library [![build badge](https://api.travis-ci.org/aisk/rust-memcache.svg?branch=master)](https://travis-ci.org/aisk/rust-memcache)
*  <b><code>&nbsp;&nbsp;&nbsp;280⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [al8n/stretto](https://github.com/al8n/stretto) - A high performance thread-safe memory-bound Rust cache [![build badge](https://github.com/al8n/stretto/actions/workflows/ci.yml/badge.svg)](https://github.com/al8n/stretto/actions/workflows/ci.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;885⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [jaemk/cached](https://github.com/jaemk/cached) — Simple function caching/memoization
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [mozilla/sccache](https://github.com/mozilla/sccache/) - Shared Compilation Cache, great for Rust compilation [![build badge](https://api.travis-ci.org/mozilla/sccache.svg?branch=master)](https://travis-ci.org/mozilla/sccache)

### Concurrency

*  <b><code>&nbsp;&nbsp;5081⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;351🍴</code></b> [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam) – Support for parallelism and low-level concurrency in Rust [![build badge](https://api.travis-ci.org/crossbeam-rs/crossbeam.svg?branch=master)](https://travis-ci.org/crossbeam-rs/crossbeam)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [orium/archery](https://github.com/orium/archery)  🌎 [archery](crates.io/crates/archery)] — Library to abstract from `Rc`/`Arc` pointer types. [![build badge](https://api.travis-ci.org/orium/archery.svg?branch=master)](https://travis-ci.org/orium/archery)
*  <b><code>&nbsp;&nbsp;6981⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;377🍴</code></b> [Rayon](https://github.com/rayon-rs/rayon) – A data parallelism library for Rust [![build badge](https://api.travis-ci.org/rayon-rs/rayon.svg?branch=master)](https://travis-ci.org/rayon-rs/rayon)
*  <b><code>&nbsp;&nbsp;&nbsp;394⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [rustcc/coroutine-rs](https://github.com/rustcc/coroutine-rs) – Coroutine Library in Rust [![build badge](https://api.travis-ci.org/rustcc/coroutine-rs.svg?branch=master)](https://travis-ci.org/rustcc/coroutine-rs)
*  <b><code>&nbsp;&nbsp;&nbsp;451⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) – Coroutine I/O for Rust [![build badge](https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master)](https://travis-ci.org/zonyitoo/coio-rs)

### Cloud

* AWS  🌎 [aws](crates.io/keywords/aws)]
  *  <b><code>&nbsp;&nbsp;2167⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [awslabs/aws-lambda-rust-runtime](https://github.com/awslabs/aws-lambda-rust-runtime)  🌎 [lambda_runtime](crates.io/crates/lambda_runtime)] — A Rust runtime for AWS Lambda  [![build badge](https://github.com/awslabs/aws-lambda-rust-runtime/workflows/Rust/badge.svg)](https://github.com/awslabs/aws-lambda-rust-runtime/actions)
  *  <b><code>&nbsp;&nbsp;1743⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [awslabs/aws-sdk-rust](https://github.com/awslabs/aws-sdk-rust) - The new AWS SDK for Rust
  *  <b><code>&nbsp;&nbsp;2565⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;419🍴</code></b> [rusoto/rusoto](https://github.com/rusoto/rusoto) — [![build badge](https://api.travis-ci.org/rusoto/rusoto.svg?branch=master)](https://travis-ci.org/rusoto/rusoto)
* Load Balancer
  *  <b><code>&nbsp;&nbsp;&nbsp;260⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Convey](https://github.com/bparli/convey) - Layer 4 Load Balancer with dynamic configuration loading.
* Multi Cloud
  *  <b><code>&nbsp;&nbsp;1660⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Qovery/engine](https://github.com/Qovery/engine) - Abstraction layer library that turns easy application deployment on Cloud providers in just a few minutes

### Command-line

* Argument parsing
  *  <b><code>&nbsp;&nbsp;9117⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;788🍴</code></b> [clap-rs](https://github.com/clap-rs/clap)  🌎 [clap](crates.io/crates/clap)] — A simple to use, full featured command-line argument parser [![build badge](https://api.travis-ci.org/clap-rs/clap.svg?branch=master)](https://travis-ci.org/clap-rs/clap)
  *  <b><code>&nbsp;&nbsp;&nbsp;741⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [docopt/docopt.rs](https://github.com/docopt/docopt.rs)  🌎 [docopt](crates.io/crates/docopt)] — A Rust implementation of [DocOpt](http://docopt.org) [![build badge](https://api.travis-ci.org/docopt/docopt.rs.svg?branch=master)](https://travis-ci.org/docopt/docopt.rs)
  *  <b><code>&nbsp;&nbsp;1148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [google/argh](https://github.com/google/argh)  🌎 [argh](crates.io/crates/argh)] — An opinionated Derive-based argument parser optimized for code size [![build badge](https://github.com/google/argh/workflows/Argh/badge.svg?branch=master)](https://github.com/google/argh/actions)
  *  <b><code>&nbsp;&nbsp;&nbsp;531⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [killercup/quicli](https://github.com/killercup/quicli)  🌎 [quicli](crates.io/crates/quicli)] — quickly build cool CLI apps in Rust [![build badge](https://api.travis-ci.org/killercup/quicli.svg?branch=master)](https://travis-ci.org/killercup/quicli)
  *  <b><code>&nbsp;&nbsp;&nbsp;205⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [ksk001100/seahorse](https://github.com/ksk001100/seahorse)  🌎 [seahorse](crates.io/crates/seahorse)] — A minimal CLI framework written in Rust [![Build status](https://github.com/ksk001100/seahorse/workflows/CI/badge.svg?branch=master)](https://github.com/ksk001100/seahorse/actions)
  *  <b><code>&nbsp;&nbsp;2485⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [TeXitoi/structopt](https://github.com/TeXitoi/structopt)  🌎 [structopt](crates.io/crates/structopt)] — parse command line argument by defining a struct [![build badge](https://api.travis-ci.org/TeXitoi/structopt.svg?branch=master)](https://travis-ci.org/TeXitoi/structopt)
* Data visualization
  *  <b><code>&nbsp;&nbsp;&nbsp;434⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [nukesor/comfy-table](https://github.com/nukesor/comfy-table)  🌎 [comfy-table](crates.io/crates/comfy-table)] — Beautiful dynamic tables for your cli tools. [![Build status](https://github.com/Nukesor/comfy-table/workflows/Tests/badge.svg?branch=master)](https://github.com/nukesor/comfy-table/actions)
  *  <b><code>&nbsp;&nbsp;&nbsp;961⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [zhiburt/tabled](https://github.com/zhiburt/tabled)  🌎 [tabled](crates.io/crates/tabled)] — An easy to use library for pretty print tables of Rust structs and enums.  [![Build Status](https://github.com/zhiburt/tabled/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/tabled/actions)
* Human-centered design
  *  <b><code>&nbsp;&nbsp;&nbsp;945⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [rust-cli/human-panic](https://github.com/rust-cli/human-panic)  🌎 [human-panic](crates.io/crates/human-panic)] — panic messages for humans [![build badge](https://api.travis-ci.org/rust-cli/human-panic.svg?branch=master)](https://travis-ci.org/rust-cli/human-panic)
* Line editor
  *  <b><code>&nbsp;&nbsp;1008⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [kkawakam/rustyline](https://github.com/kkawakam/rustyline)  🌎 [rustyline](crates.io/crates/rustyline)] — readline implementation in Rust [![build badge](https://api.travis-ci.org/kkawakam/rustyline.svg?branch=master)](https://travis-ci.org/kkawakam/rustyline)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [MovingtoMars/liner](https://github.com/MovingtoMars/liner)  🌎 [liner](crates.io/crates/liner)] — A library offering readline-like functionality [![build badge](https://api.travis-ci.org/MovingtoMars/liner.svg?branch=master)](https://travis-ci.org/MovingtoMars/liner)
  *  <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [murarth/linefeed](https://github.com/murarth/linefeed)  🌎 [linefeed](crates.io/crates/linefeed)] — Configurable, extensible, interactive line reader [![build badge](https://api.travis-ci.org/murarth/linefeed.svg?branch=master)](https://travis-ci.org/murarth/linefeed)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [srijs/rust-copperline](https://github.com/srijs/rust-copperline)  🌎 [copperline](crates.io/crates/copperline)] — pure-Rust command line editing library
* Other
  *  <b><code>&nbsp;&nbsp;&nbsp;142⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [mgrachev/update-informer](https://github.com/mgrachev/update-informer)  🌎 [update-informer](crates.io/crates/update-informer)] — Update informer for CLI applications. It checks for a new version on Crates.io and GitHub [![build badge](https://github.com/mgrachev/update-informer/workflows/CI/badge.svg)](https://github.com/mgrachev/update-informer/actions)
* Pipeline
  *  <b><code>&nbsp;&nbsp;&nbsp;354⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [hniksic/rust-subprocess](https://github.com/hniksic/rust-subprocess)  🌎 [subprocess](crates.io/crates/subprocess)] — facilities for interaction with external pipelines [![build badge](https://api.travis-ci.org/hniksic/rust-subprocess.svg?branch=master)](https://travis-ci.org/hniksic/rust-subprocess)
  * 🌎 [imp/pager-rs](gitlab.com/imp/pager-rs)  🌎 [pager](crates.io/crates/pager)] — pipe your output through an external pager
  *  <b><code>&nbsp;&nbsp;&nbsp;565⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [oconnor663/duct.rs](https://github.com/oconnor663/duct.rs)  🌎 [duct](crates.io/crates/duct)] — A builder for subprocess pipelines and IO redirection [![build badge](https://api.travis-ci.org/oconnor663/duct.rs.svg?branch=master)](https://travis-ci.org/oconnor663/duct.rs)
  *  <b><code>&nbsp;&nbsp;&nbsp;148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [philippkeller/rexpect](https://github.com/philippkeller/rexpect)  🌎 [rexpect](crates.io/crates/rexpect)] — automate interactive applications such as ssh, ftp, passwd, etc [![build badge](https://api.travis-ci.org/philippkeller/rexpect.svg?branch=master)](https://travis-ci.org/philippkeller/rexpect)
  *  <b><code>&nbsp;&nbsp;&nbsp;119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [zhiburt/expectrl](https://github.com/zhiburt/expectrl)  🌎 [expectrl](crates.io/crates/expectrl)] — A library for controlling interactive programs in a pseudo-terminal [![build badge](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml)
* Progress
  *  <b><code>&nbsp;&nbsp;&nbsp;479⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [a8m/pb](https://github.com/a8m/pb)  🌎 [pbr](crates.io/crates/pbr)] — console progress bar for Rust
  *  <b><code>&nbsp;&nbsp;2690⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [console-rs/indicatif](https://github.com/console-rs/indicatif)  🌎 [indicatif](crates.io/crates/indicatif)] — indicate progress to users
  *  <b><code>&nbsp;&nbsp;&nbsp;384⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [FGRibreau/spinners](https://github.com/FGRibreau/spinners)  🌎 [spinners](crates.io/crates/spinners)] — 60+ elegant terminal spinners
* Prompt
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [hashmismatch/terminal_cli.rs](https://github.com/hashmismatch/terminal_cli.rs)  🌎 [terminal_cli](crates.io/crates/terminal_cli)]  — build an interactive command prompt [![build badge](https://api.travis-ci.org/hashmismatch/terminal_cli.rs.svg?branch=master)](https://travis-ci.org/hashmismatch/terminal_cli.rs)
  * 🌎 [starship/starship](starship.rs/)  🌎 [starship](crates.io/crates/starship)]  — A minimal, blazing fast, and extremely customizable prompt for any shell [![Build status](https://github.com/starship/starship/workflows/Main%20workflow/badge.svg?branch=master)](https://github.com/starship/starship/actions)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [ynqa/promkit](https://github.com/ynqa/promkit)  🌎 [promkit](crates.io/crates/promkit)]  — A toolkit for building interactive command-line tools [![Build status](https://github.com/ynqa/promkit/workflows/promkit/badge.svg?branch=master)](https://github.com/ynqa/promkit/actions)
* Style
  *  <b><code>&nbsp;&nbsp;&nbsp;195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [LukasKalbertodt/bunt](https://github.com/LukasKalbertodt/bunt)  🌎 [bunt](crates.io/crates/bunt)] — cross-platform terminal colors and styling with macros [![Build status](https://github.com/LukasKalbertodt/bunt/actions/workflows/ci.yml/badge.svg)](https://github.com/LukasKalbertodt/bunt/actions?query=workflow%3ACI+branch%3Amaster)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [LukasKalbertodt/term-painter](https://github.com/LukasKalbertodt/term-painter)  🌎 [term-painter](crates.io/crates/term-painter)] — cross-platform styled terminal output [![build badge](https://api.travis-ci.org/LukasKalbertodt/term-painter.svg?branch=master)](https://travis-ci.org/LukasKalbertodt/term-painter)
  *  <b><code>&nbsp;&nbsp;1067⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [mackwic/colored](https://github.com/mackwic/colored)  🌎 [colored](crates.io/crates/colored)] — Coloring terminal so simple, you already know how to do it!
  *  <b><code>&nbsp;&nbsp;&nbsp;383⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [ogham/rust-ansi-term](https://github.com/ogham/rust-ansi-term)  🌎 [ansi_term](crates.io/crates/ansi_term)] — control colours and formatting on ANSI terminals [![build badge](https://api.travis-ci.org/ogham/rust-ansi-term.svg?branch=master)](https://travis-ci.org/ogham/rust-ansi-term)
  *  <b><code>&nbsp;&nbsp;&nbsp;143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [SergioBenitez/yansi](https://github.com/SergioBenitez/yansi)  🌎 [yansi](crates.io/crates/yansi)] — A dead simple ANSI terminal color painting library
* TUI
  * BearLibTerminal
    *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [cfyzium/bearlibterminal](https://github.com/nabijaczleweli/BearLibTerminal.rs)  🌎 [bear-lib-terminal](crates.io/crates/bear-lib-terminal)] —  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [BearLibTerminal](https://github.com/tommyettinger/BearLibTerminal) bindings [![build badge](https://api.travis-ci.org/nabijaczleweli/BearLibTerminal.rs.svg?branch=master)](https://travis-ci.org/nabijaczleweli/BearLibTerminal.rs)
  *  <b><code>&nbsp;&nbsp;8124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;411🍴</code></b> [fdehau/tui-rs](https://github.com/fdehau/tui-rs)  🌎 [tui](crates.io/crates/tui)] — A TUI library inspired by  <b><code>&nbsp;14833⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;895🍴</code></b> [blessed-contrib](https://github.com/yaronn/blessed-contrib) and  <b><code>&nbsp;11985⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;755🍴</code></b> [termui](https://github.com/gizak/termui) [![build badge](https://api.travis-ci.org/fdehau/tui-rs.svg?branch=master)](https://travis-ci.org/fdehau/tui-rs)
  *  <b><code>&nbsp;&nbsp;2988⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [gyscos/Cursive](https://github.com/gyscos/Cursive)  🌎 [cursive](crates.io/crates/cursive)] — build rich TUI applications [![build badge](https://api.travis-ci.org/gyscos/Cursive.svg?branch=master)](https://travis-ci.org/gyscos/Cursive)
  *  <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [ivanceras/titik](https://github.com/ivanceras/titik) - a crossplatform TUI widget library with the goal of providing interactive widgets [![Build Status](https://api.travis-ci.com/ivanceras/titik.svg?branch=master)](https://app.travis-ci.com/github/ivanceras/titik)
  * ncurses
    *  <b><code>&nbsp;&nbsp;&nbsp;352⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [ihalila/pancurses](https://github.com/ihalila/pancurses)  🌎 [pancurses](crates.io/crates/pancurses)] — curses library, supports linux and windows [![build badge](https://api.travis-ci.org/ihalila/pancurses.svg?branch=master)](https://travis-ci.org/ihalila/pancurses)
    *  <b><code>&nbsp;&nbsp;&nbsp;611⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs)  🌎 [ncurses](crates.io/crates/ncurses)] — 🌎 [ncurses](www.gnu.org/software/ncurses/) bindings [![build badge](https://api.travis-ci.org/jeaye/ncurses-rs.svg?branch=master)](https://travis-ci.org/jeaye/ncurses-rs)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [ogham/rust-term-grid](https://github.com/ogham/rust-term-grid)  🌎 [term_grid](crates.io/crates/term_grid)] — Rust library for putting things in a grid [![build badge](https://api.travis-ci.org/ogham/rust-term-grid.svg?branch=master)](https://travis-ci.org/ogham/rust-term-grid)
  *  <b><code>&nbsp;&nbsp;1776⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [redox-os/termion](https://github.com/redox-os/termion)  🌎 [termion](crates.io/crates/termion)] — bindless library for controlling terminals/TTY [![build badge](https://api.travis-ci.org/redox-os/termion.svg?branch=master)](https://travis-ci.org/redox-os/termion)
  * Termbox
    *  <b><code>&nbsp;&nbsp;&nbsp;456⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [gchp/rustbox](https://github.com/gchp/rustbox)  🌎 [rustbox](crates.io/crates/rustbox)] — bindings to  <b><code>&nbsp;&nbsp;1862⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [Termbox](https://github.com/nsf/termbox) [![build badge](https://api.travis-ci.org/gchp/rustbox.svg?branch=master)](https://travis-ci.org/gchp/rustbox)
  *  <b><code>&nbsp;&nbsp;1768⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [TimonPost/crossterm](https://github.com/crossterm-rs/crossterm)  🌎 [crossterm](crates.io/crates/crossterm)] — crossplatform terminal library

### Compression

* 🌎 [Brotli](opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
  *  <b><code>&nbsp;&nbsp;&nbsp;612⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli) — Brotli decompressor in Rust that optionally avoids the stdlib
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [ende76/brotli-rs](https://github.com/ende76/brotli-rs) — implementation of Brotli compression
* bzip2
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [alexcrichton/bzip2-rs](https://github.com/alexcrichton/bzip2-rs) — 🌎 [libbz2](www.sourceware.org/bzip2/) bindings [![build badge](https://api.travis-ci.com/alexcrichton/bzip2-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/bzip2-rs)
* gzip
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [zopfli](https://github.com/zopfli-rs/zopfli)  🌎 [zopfli](crates.io/crates/zopfli)] — implementation of the Zopfli compression algorithm for higher quality deflate or zlib compression
* gzp
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [sstadick/gzp](https://github.com/sstadick/gzp/) - multi-threaded encoding and decoding of deflate formats and snappy
* miniz
  *  <b><code>&nbsp;&nbsp;&nbsp;549⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs) — 🌎 [miniz](code.google.com/archive/p/miniz) bindings [![build badge](https://github.com/rust-lang/flate2-rs/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/flate2-rs/actions)
* snappy
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [JeffBelgum/rust-snappy](https://github.com/JeffBelgum/rust-snappy) —  <b><code>&nbsp;&nbsp;5286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;908🍴</code></b> [snappy](https://github.com/google/snappy) bindings [![build badge](https://api.travis-ci.org/JeffBelgum/rust-snappy.svg?branch=master)](https://travis-ci.org/JeffBelgum/rust-snappy)
* tar
  *  <b><code>&nbsp;&nbsp;&nbsp;454⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs) — tar archive reading/writing in Rust [![build badge](https://api.travis-ci.com/alexcrichton/tar-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/tar-rs)
* zip
  *  <b><code>&nbsp;&nbsp;&nbsp;483⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [zip-rs/zip](https://github.com/zip-rs/zip) — read and write ZIP archives [![Build Status](https://api.travis-ci.org/mvdnes/zip-rs.svg?branch=master)](https://travis-ci.org/mvdnes/zip-rs)

### Computation

*  <b><code>&nbsp;&nbsp;&nbsp;467⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [argmin-rs/argmin](https://github.com/argmin-rs/argmin)  🌎 [argmin](crates.io/crates/argmin)] — A pure Rust optimization library [![build badge](https://api.travis-ci.org/argmin-rs/argmin.svg?branch=master)](https://travis-ci.org/argmin-rs/argmin)
* 🌎 [BLAS](en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms)  🌎 [blas](crates.io/keywords/blas)]
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [mikkyang/rust-blas](https://github.com/mikkyang/rust-blas) — BLAS bindings
*  <b><code>&nbsp;&nbsp;1497⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [calebwin/emu](https://github.com/calebwin/emu) — A language for GPGPU numerical computing from a Rust macro
*  <b><code>&nbsp;&nbsp;2741⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;346🍴</code></b> [dimforge/nalgebra](https://github.com/dimforge/nalgebra) — low-dimensional linear algebra library [![build badge](https://api.travis-ci.org/dimforge/nalgebra.svg?branch=dev)](https://travis-ci.org/dimforge/nalgebra)
* [GSL](http://www.gnu.org/software/gsl/)
  *  <b><code>&nbsp;&nbsp;&nbsp;149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez/rust-GSL) — GSL bindings [![build badge](https://api.travis-ci.org/GuillaumeGomez/rust-GSL.svg?branch=master)](https://travis-ci.org/GuillaumeGomez/rust-GSL)
* 🌎 [LAPACK](en.wikipedia.org/wiki/LAPACK)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [stainless-steel/lapack](https://github.com/blas-lapack-rs/lapack) — LAPACK bindings [![build badge](https://api.travis-ci.org/blas-lapack-rs/lapack.svg?branch=master)](https://travis-ci.org/blas-lapack-rs/lapack)
* Parallel
  *  <b><code>&nbsp;&nbsp;&nbsp;655⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) —  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Arrayfire](https://github.com/arrayfire) bindings
  *  <b><code>&nbsp;&nbsp;&nbsp;460⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [autumnai/collenchyma](https://github.com/autumnai/collenchyma) — An extensible, pluggable, backend-agnostic framework for parallel, high-performance computations on CUDA, OpenCL and common host CPU. [![build badge](https://api.travis-ci.org/autumnai/collenchyma.svg?branch=master)](https://travis-ci.org/autumnai/collenchyma)
  *  <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [luqmana/rust-opencl](https://github.com/luqmana/rust-opencl) — 🌎 [OpenCL](www.khronos.org/opencl/) bindings
* Scirust
  *  <b><code>&nbsp;&nbsp;&nbsp;236⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [indigits/scirust](https://github.com/indigits/scirust) — scientific computing library in Rust [![Build Status](https://api.travis-ci.org/indigits/scirust.svg?branch=master)](https://travis-ci.org/indigits/scirust)
* Statrs
  *  <b><code>&nbsp;&nbsp;&nbsp;359⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [statrs-dev/statrs](https://github.com/statrs-dev/statrs) — Robust statistical computation library in Rust [![Build Status](https://api.travis-ci.org/boxtown/statrs.svg?branch=master)](https://travis-ci.org/boxtown/statrs)

### Configuration

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [andoriyu/uclicious](https://github.com/andoriyu/uclicious)  🌎 [uclicious](crates.io/crates/uclicious)] —  <b><code>&nbsp;&nbsp;1449⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;140🍴</code></b> [libUCL](https://github.com/vstakhov/libucl) based feature-rich configuration library. [![CircleCI](https://circleci.com/gh/vstakhov/libucl.svg?style=svg)](https://app.circleci.com/pipelines/github/vstakhov/libucl)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Kixunil/configure_me](https://github.com/Kixunil/configure_me)  🌎 [configure_me](crates.io/crates/configure_me)] — library for processing application configuration easily
*  <b><code>&nbsp;&nbsp;1489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;163🍴</code></b> [mehcode/config-rs](https://github.com/mehcode/config-rs)  🌎 [config](crates.io/crates/config)] — Layered configuration system for Rust applications (with strong support for 12-factor applications). [![build badge](https://api.travis-ci.org/mehcode/config-rs.svg?branch=master)](https://travis-ci.org/mehcode/config-rs)

### Cryptography

 🌎 [crypto](crates.io/keywords/crypto), 🌎 [cryptography](crates.io/keywords/cryptography)]

*  <b><code>&nbsp;&nbsp;2797⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;501🍴</code></b> [briansmith/ring](https://github.com/briansmith/ring) — Safe, fast, small crypto using Rust and BoringSSL's cryptography primitives. [![build badge](https://api.travis-ci.org/briansmith/ring.svg?branch=master)](https://travis-ci.org/briansmith/ring)
*  <b><code>&nbsp;&nbsp;&nbsp;378⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [briansmith/webpki](https://github.com/briansmith/webpki) — Web PKI TLS X.509 certificate validation in Rust. [![build badge](https://api.travis-ci.org/briansmith/webpki.svg?branch=master)](https://travis-ci.org/briansmith/webpki)
*  <b><code>&nbsp;&nbsp;&nbsp;126⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [conradkleinespel/rooster](https://github.com/conradkleinespel/rooster)  🌎 [rooster](crates.io/crates/rooster)] — Simple password manager to use in your terminal
*  <b><code>&nbsp;&nbsp;1562⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [cossacklabs/themis](https://github.com/cossacklabs/themis)  🌎 [themis](crates.io/crates/themis)] — a high-level cryptographic library for solving typical data security tasks, best fit for multi-platform apps. [![build badge](https://circleci.com/gh/cossacklabs/themis/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/cossacklabs/themis)
*  <b><code>&nbsp;&nbsp;1171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;265🍴</code></b> [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto) — cryptographic algorithms in Rust [![build badge](https://api.travis-ci.org/DaGenix/rust-crypto.svg?branch=master)](https://travis-ci.org/DaGenix/rust-crypto)
*  <b><code>&nbsp;&nbsp;&nbsp;579⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek) — Pure Rust implementation of Curve25519 operations
*  <b><code>&nbsp;&nbsp;&nbsp;497⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;194🍴</code></b> [dalek-cryptography/ed25519-dalek](https://github.com/dalek-cryptography/ed25519-dalek) — Pure Rust implementation of Ed25519 digital signatures
*  <b><code>&nbsp;&nbsp;&nbsp;232⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [dalek-cryptography/x25519-dalek](https://github.com/dalek-cryptography/x25519-dalek) — Pure Rust implementation of X25519 key exchange
*  <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [debris/tiny-keccak](https://github.com/debris/tiny-keccak) — Pure Rust implementation of the Keccak family (SHA3)
*  <b><code>&nbsp;&nbsp;1161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;243🍴</code></b> [exonum/exonum](https://github.com/exonum/exonum)  🌎 [exonum](crates.io/crates/exonum)] — extensible framework for blockchain projects [![build badge](https://api.travis-ci.com/exonum/exonum.svg?branch=master)](https://travis-ci.org/exonum/exonum)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [gakonst/ark-circom](https://github.com/gakonst/ark-circom) - Arkworks bindings to Circom's R1CS, for Groth16 Proof and Witness generation in Rust.
*  <b><code>&nbsp;&nbsp;&nbsp;123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [klutzy/suruga](https://github.com/klutzy/suruga) — A Rust implementation of 🌎 [TLS 1.2](datatracker.ietf.org/doc/html/rfc5246)
*  <b><code>&nbsp;&nbsp;&nbsp;158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework) — Bindings for Security Framework (OSX native)
*  <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [libOctavo/octavo](https://github.com/libOctavo/octavo) — Modular hash and crypto library in Rust [![build badge](https://api.travis-ci.org/libOctavo/octavo.svg?branch=master)](https://travis-ci.org/libOctavo/octavo)
*  <b><code>&nbsp;&nbsp;&nbsp;152⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [novifinancial/opaque-ke](https://github.com/novifinancial/opaque-ke) — Pure Rust implementation of the recent 🌎 [OPAQUE](datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/) password-authenticated key exchange. [![build badge](https://github.com/novifinancial/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/novifinancial/opaque-ke)
*  <b><code>&nbsp;&nbsp;&nbsp;419⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [orion-rs/orion](https://github.com/orion-rs/orion) — This library aims to provide easy and usable crypto. 'Usable' meaning exposing high-level API's that are easy to use and hard to misuse. [![Tests](https://github.com/orion-rs/orion/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/orion-rs/orion/actions/workflows/test.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [racum/rust-djangohashers](https://github.com/racum/rust-djangohashers)  🌎 [djangohashers](crates.io/crates/djangohashers)] — A Rust port of the password primitives used in the Django Project. It doesn't require Django, only hashes and validates passwords according to its style. [![build badge](https://api.travis-ci.org/Racum/rust-djangohashers.svg?branch=master)](https://travis-ci.org/Racum/rust-djangohashers)
*  <b><code>&nbsp;&nbsp;1016⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;157🍴</code></b> [RustCrypto/hashes](https://github.com/RustCrypto/hashes) — Collection of cryptographic hash functions written in pure Rust [![build badge](https://api.travis-ci.org/RustCrypto/hashes.svg?branch=master)](https://travis-ci.org/RustCrypto/hashes)
*  <b><code>&nbsp;&nbsp;3578⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;379🍴</code></b> [rustls/rustls](https://github.com/rustls/rustls) — A Rust implementation of TLS
*  <b><code>&nbsp;&nbsp;&nbsp;344⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [sfackler/rust-native-tls](https://github.com/sfackler/rust-native-tls) — Bindings for native TLS libraries
*  <b><code>&nbsp;&nbsp;&nbsp;956⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;573🍴</code></b> [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl) — 🌎 [OpenSSL](www.openssl.org/) bindings [![build badge](https://api.travis-ci.org/sfackler/rust-openssl.svg?branch=master)](https://travis-ci.org/sfackler/rust-openssl)
*  <b><code>&nbsp;&nbsp;&nbsp;639⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;160🍴</code></b> [sodiumoxide/sodiumoxide](https://github.com/sodiumoxide/sodiumoxide) —  <b><code>&nbsp;10298⭐</code></b> <b><code>&nbsp;&nbsp;1593🍴</code></b> [libsodium](https://github.com/jedisct1/libsodium) bindings [![build badge](https://api.travis-ci.org/sodiumoxide/sodiumoxide.svg?branch=master)](https://travis-ci.org/sodiumoxide/sodiumoxide)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [vityafx/randomorg](https://github.com/vityafx/randomorg) - A random.org client library. [![Crates badge](https://img.shields.io/crates/v/randomorg.svg)](https://crates.io/crates/randomorg)
*  <b><code>&nbsp;&nbsp;&nbsp;233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [w3f/schnorrkel](https://github.com/w3f/schnorrkel) - Schnorr VRFs and signatures on the Ristretto group

### Database

 🌎 [database](crates.io/keywords/database)]

* NoSQL  🌎 [nosql](crates.io/keywords/nosql)]

  * 🌎 [ArangoDB](www.arangodb.com)
    * 🌎 [Aragog](gitlab.com/qonfucius/aragog)  🌎 [aragog](crates.io/crates/aragog)] - A Lightweight ArangoDB Object document, relational and graph mapper [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
    *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Arangors](https://github.com/fMeow/arangors)  🌎 [arangors](crates.io/crates/arangors)] - An ArangoDB driver for Rust
  * 🌎 [Cassandra](cassandra.apache.org/_/index.html)  🌎 [cassandra](crates.io/keywords/cassandra), 🌎 [cql](crates.io/keywords/cql)]
    *  <b><code>&nbsp;&nbsp;&nbsp;336⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [AlexPikalov/cdrs](https://github.com/AlexPikalov/cdrs)  🌎 [cdrs](crates.io/crates/cdrs)] — native client written in Rust [![build badge](https://api.travis-ci.org/AlexPikalov/cdrs.svg?branch=master)](https://travis-ci.org/AlexPikalov/cdrs)
    *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [krojew/cdrs-tokio](https://github.com/krojew/cdrs-tokio)  🌎 [cdrs-tokio](crates.io/crates/cdrs-tokio)] - production-ready async Apache Cassandra driver written in pure Rust [![build badge](https://github.com/krojew/cdrs-tokio/actions/workflows/rust.yml/badge.svg)](https://github.com/krojew/cdrs-tokio/actions)
    *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [Metaswitch/cassandra-rs](https://github.com/Metaswitch/cassandra-rs) —  bindings to the DataStax C/C++ client [![build badge](https://api.travis-ci.org/Metaswitch/cassandra-rs.svg?branch=master)](https://travis-ci.org/Metaswitch/cassandra-rs)
  * CouchDB  🌎 [couchdb](crates.io/keywords/couchdb)]
    *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [chill-rs/chill](https://github.com/chill-rs/chill)  🌎 [couchdb](crates.io/crates/chill)] — A Rust client for the CouchDB REST API [![build badge](https://api.travis-ci.org/chill-rs/chill.svg?branch=master)](https://travis-ci.org/chill-rs/chill)
  * 🌎 [DynamoDB](aws.amazon.com/dynamodb/)  🌎 [dynamodb](crates.io/keywords/dynamodb)]
    *  <b><code>&nbsp;&nbsp;&nbsp;189⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [softprops/dynomite](https://github.com/softprops/dynomite) - A library for strongly-typed and convenient interaction with `rusoto_dynamodb` [![build badge](https://github.com/softprops/dynomite/workflows/Main/badge.svg?branch=master)](https://github.com/softprops/dynomite/actions)
  * Elasticsearch  🌎 [elasticsearch](crates.io/keywords/elasticsearch)]
    *  <b><code>&nbsp;&nbsp;&nbsp;217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [benashford/rs-es](https://github.com/benashford/rs-es)  🌎 [rs-es](crates.io/crates/rs-es)] — A Rust client for the 🌎 [Elastic](www.elastic.co/) REST API [![build badge](https://api.travis-ci.org/benashford/rs-es.svg?branch=master)](https://travis-ci.org/benashford/rs-es)
    *  <b><code>&nbsp;&nbsp;&nbsp;252⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [elastic-rs/elastic](https://github.com/elastic-rs/elastic)  🌎 [elastic](crates.io/crates/elastic)] — elastic is an efficient, modular API client for Elasticsearch written in Rust [![build badge](https://ci.appveyor.com/api/projects/status/csa78tcumdpnbur2?svg=true)](https://ci.appveyor.com/project/KodrAus/elastic)
  * etcd
    *  <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [jimmycuadra/rust-etcd](https://github.com/jimmycuadra/rust-etcd)  🌎 [etcd](crates.io/crates/etcd)] — A client library for CoreOS's etcd. [![build badge](https://api.travis-ci.org/jimmycuadra/rust-etcd.svg?branch=master)](https://travis-ci.org/jimmycuadra/rust-etcd)
    *  <b><code>&nbsp;&nbsp;&nbsp;142⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [lodrem/etcd-rs](https://github.com/lodrem/etcd-rs) — An asynchronous etcd client for rust [![CI](https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/lodrem/etcd-rs/actions/workflows/ci.yml)
  * ForestDB
    *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [vhbit/sherwood](https://github.com/vhbit/sherwood) —  <b><code>&nbsp;&nbsp;1164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [ForestDB](https://github.com/couchbase/forestdb) bindings [![build badge](https://api.travis-ci.org/vhbit/sherwood.svg?branch=master)](https://travis-ci.org/vhbit/sherwood)
  * 🌎 [InfluxDB](www.influxdata.com/)
    *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [driftluo/InfluxDBClient-rs](https://github.com/driftluo/InfluxDBClient-rs) — Synchronization interface [![build badge](https://api.travis-ci.org/driftluo/InfluxDBClient-rs.svg?branch=master)](https://travis-ci.org/driftluo/InfluxDBClient-rs)
  * LevelDB
    *  <b><code>&nbsp;&nbsp;&nbsp;159⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [skade/leveldb](https://github.com/skade/leveldb) —  <b><code>&nbsp;30007⭐</code></b> <b><code>&nbsp;&nbsp;6661🍴</code></b> [LevelDB](https://github.com/google/leveldb) bindings [![build badge](https://api.travis-ci.org/skade/leveldb.svg?branch=master)](https://travis-ci.org/skade/leveldb)
  * LMDB  🌎 [lmdb](crates.io/keywords/lmdb)]
    *  <b><code>&nbsp;&nbsp;&nbsp;103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [vhbit/lmdb-rs](https://github.com/vhbit/lmdb-rs)  🌎 [lmdb-rs](crates.io/crates/lmdb-rs)] — 🌎 [LMDB](www.symas.com/symas-embedded-database-lmdb) bindings [![build badge](https://api.travis-ci.org/vhbit/lmdb-rs.svg?branch=master)](https://travis-ci.org/vhbit/lmdb-rs)
  * MongoDB  🌎 [mongodb](crates.io/keywords/mongodb)]
    *  <b><code>&nbsp;&nbsp;1059⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [mongodb/mongo-rust-driver](https://github.com/mongodb/mongo-rust-driver)  🌎 [mongodb](crates.io/crates/mongodb)] — 🌎 [MongoDB](www.mongodb.com/) bindings
  * 🌎 [PickleDB](pythonhosted.org/pickleDB/)
    *  <b><code>&nbsp;&nbsp;&nbsp;132⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [seladb/pickledb-rs](https://github.com/seladb/pickledb-rs) — a lightweight and simple key-value store, heavily inspired by Python's PickleDB. [![build badge](https://api.travis-ci.org/seladb/pickledb-rs.svg?branch=master)](https://travis-ci.org/seladb/pickledb-rs)
  * Redis  🌎 [redis](crates.io/keywords/redis)]
    *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [aembke/fred](https://github.com/aembke/fred.rs)  🌎 [fred](crates.io/crates/fred)] - A high level async 🌎 [Redis](redis.io/) client for Rust with Tokio. [![CircleCI](https://circleci.com/gh/aembke/fred.rs/tree/main.svg?style=svg)] 🌎 [https://circleci.com/gh/aembke/fred.rs/tree/main](app.circleci.com/pipelines/github/aembke/fred.rs?branch=main))
    *  <b><code>&nbsp;&nbsp;2551⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;397🍴</code></b> [redis-rs](https://github.com/redis-rs/redis-rs) — 🌎 [Redis](redis.io/) library in Rust [![Rust](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml)
  * 🌎 [RocksDB](rocksdb.org/)
    *  <b><code>&nbsp;&nbsp;1206⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;494🍴</code></b> [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb) — RocksDB bindings [![RocksDB CI](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml)
  * 🌎 [UnQLite](unqlite.org/)
    *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [zitsen/unqlite.rs](https://github.com/zitsen/unqlite.rs) — UnQLite bindings [![build badge](https://api.travis-ci.org/zitsen/unqlite.rs.svg?branch=master)](https://travis-ci.org/zitsen/unqlite.rs)
  * 🌎 [ZooKeeper](zookeeper.apache.org/)
    *  <b><code>&nbsp;&nbsp;&nbsp;160⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [bonifaido/rust-zookeeper](https://github.com/bonifaido/rust-zookeeper)  🌎 [zookeeper](crates.io/crates/zookeeper)] — A client library for Apache ZooKeeper. [![build badge](https://api.travis-ci.org/bonifaido/rust-zookeeper.svg?branch=master)](https://travis-ci.org/bonifaido/rust-zookeeper)
    *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [krojew/rust-zookeeper](https://github.com/krojew/rust-zookeeper)  🌎 [zookeeper-async](crates.io/crates/zookeeper-async)] - Async Zookeeper client written 100% in Rust, based on tokio.  ![build status](https://github.com/krojew/rust-zookeeper/actions/workflows/rust.yml/badge.svg)
* OGM  🌎 [ogm](crates.io/keywords/ogm)]
    * 🌎 [Aragog](gitlab.com/qonfucius/aragog)  🌎 [aragog](crates.io/crates/aragog)] - A Lightweight ArangoDB Object document, relational and graph mapper [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
* ORM  🌎 [orm](crates.io/keywords/orm)]
  *  <b><code>&nbsp;&nbsp;&nbsp;439⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Brendonovich/prisma-client-rust](https://github.com/Brendonovich/prisma-client-rust) — An autogenerated query builder that provides simple and fully type-safe database access using the Prisma ecosystem. [![Test Status](https://img.shields.io/github/workflow/status/Brendonovich/prisma-client-rust/CI?label=tests&style=flat-square)](https://github.com/Brendonovich/prisma-client-rust/actions)
  *  <b><code>&nbsp;&nbsp;8803⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;795🍴</code></b> [diesel-rs/diesel](https://github.com/diesel-rs/diesel) — an ORM and Query builder for Rust [![Build Status](https://api.travis-ci.org/diesel-rs/diesel.svg?branch=master)](https://travis-ci.org/diesel-rs/diesel)
  *  <b><code>&nbsp;&nbsp;&nbsp;229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [ivanceras/rustorm](https://github.com/ivanceras/rustorm) — an ORM for Rust [![Build Status](https://api.travis-ci.org/ivanceras/rustorm.svg?branch=master)](https://travis-ci.org/ivanceras/rustorm)
  *  <b><code>&nbsp;&nbsp;1471⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [rbatis/rbatis](https://github.com/rbatis/rbatis) — Rust ORM Framework High Performance(JSON based) [![Build Status](https://api.travis-ci.org/zhuxiujia/rbatis.svg?branch=master)](https://travis-ci.org/zhuxiujia/rbatis)
  *  <b><code>&nbsp;&nbsp;2431⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [SeaQL/sea-orm](https://github.com/SeaQL/sea-orm) — an async & dynamic ORM for Rust [![Build Status](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml)
*  <b><code>&nbsp;&nbsp;1087⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [sfackler/r2d2](https://github.com/sfackler/r2d2) — generic connection pool [![build badge](https://api.travis-ci.org/sfackler/r2d2.svg?branch=master)](https://travis-ci.org/sfackler/r2d2)
* SQL  🌎 [sql](crates.io/keywords/sql)]
  * Generic
    *  <b><code>&nbsp;&nbsp;6497⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;674🍴</code></b> [launchbadge/sqlx](https://github.com/launchbadge/sqlx) - async PostgreSQL/MySQL/SQLite connection pool with strong typing support [![build badge](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-square)](https://github.com/launchbadge/sqlx)
  * Microsoft SQL
    *  <b><code>&nbsp;&nbsp;&nbsp;161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [prisma/tiberius](https://github.com/prisma/tiberius) — [![Cargo tests](https://github.com/prisma/tiberius/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/prisma/tiberius/actions/workflows/test.yml)
  * MySql  🌎 [mysql](crates.io/keywords/mysql)]
    *  <b><code>&nbsp;&nbsp;&nbsp;167⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [AgilData/mysql-proxy-rs](https://github.com/AgilData/mysql-proxy-rs) — A MySQL Proxy [![CircleCI](https://circleci.com/gh/AgilData/mysql-proxy-rs/tree/master.svg?style=svg)](https://app.circleci.com/pipelines/github/AgilData/mysql-proxy-rs?branch=master)
    *  <b><code>&nbsp;&nbsp;&nbsp;273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [blackbeam/mysql_async](https://github.com/blackbeam/mysql_async)  🌎 [mysql_async](crates.io/crates/mysql_async)] — asyncronous Rust Mysql driver based on Tokio. [![CircleCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/blackbeam/mysql_async?branch=master)
    *  <b><code>&nbsp;&nbsp;&nbsp;512⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple)  🌎 [mysql](crates.io/crates/mysql)] — A native MySql client [![build badge](https://api.travis-ci.org/blackbeam/rust-mysql-simple.svg?branch=master)](https://travis-ci.org/blackbeam/rust-mysql-simple)
  * PostgreSql  🌎 [postgres](crates.io/keywords/postgres), 🌎 [postgresql](crates.io/keywords/postgresql)]
    *  <b><code>&nbsp;&nbsp;2580⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;304🍴</code></b> [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres)  🌎 [postgres](crates.io/crates/postgres)] — A native 🌎 [PostgreSQL](www.postgresql.org/) client [![build badge](https://api.travis-ci.org/sfackler/rust-postgres.svg?branch=master)](https://travis-ci.org/sfackler/rust-postgres)
  * Sqlite  🌎 [sqlite](crates.io/keywords/sqlite)]
    *  <b><code>&nbsp;&nbsp;1621⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;235🍴</code></b> [rusqlite](https://github.com/rusqlite/rusqlite) — 🌎 [Sqlite3](www.sqlite.org/index.html) bindings [![build badge](https://api.travis-ci.org/rusqlite/rusqlite.svg?branch=master)](https://travis-ci.org/rusqlite/rusqlite)

### Data processing

*  <b><code>&nbsp;&nbsp;&nbsp;154⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [amv-dev/yata](https://github.com/amv-dev/yata) — high perfomance technical analysis library [![Build Status](https://img.shields.io/github/workflow/status/amv-dev/yata/Rust?branch=master)](https://github.com/amv-dev/yata/actions?query=workflow%3ARust)
*  <b><code>&nbsp;&nbsp;2294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;224🍴</code></b> [bluss/ndarray](https://github.com/rust-ndarray/ndarray) — N-dimensional array with array views, multidimensional slicing, and efficient operations
*  <b><code>&nbsp;&nbsp;&nbsp;137⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [kernelmachine/utah](https://github.com/kernelmachine/utah) — Dataframe structure and operations in Rust
*  <b><code>&nbsp;&nbsp;7240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;392🍴</code></b> [pola-rs/polars](https://github.com/pola-rs/polars) - Fast feature complete DataFrame library ![Build and test](https://github.com/pola-rs/polars/workflows/Build%20and%20test/badge.svg?branch=master)
*  <b><code>&nbsp;&nbsp;2800⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [weld-project/weld](https://github.com/weld-project/weld) — High-performance runtime for data analytics applications

### Data streaming

*  <b><code>&nbsp;&nbsp;1183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [infinyon/fluvio](https://github.com/infinyon/fluvio) - Programmable data streaming platform [![CI](https://github.com/infinyon/fluvio/workflows/CI/badge.svg?branch=stable)](https://github.com/infinyon/fluvio/actions)

### Data structures

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [billyevans/tst](https://github.com/billyevans/tst)  🌎 [tst](crates.io/crates/tst)] — Ternary search tree collection [![build badge](https://api.travis-ci.org/billyevans/tst.svg?branch=master)](https://travis-ci.org/billyevans/tst)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [contain-rs](https://github.com/contain-rs) — Extension of Rust's std::collections
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [danielpclark/array_tool](https://github.com/danielpclark/array_tool) — Array helpers for Rust. Some of the most common methods you would use on Arrays made available on Vectors. Polymorphic implementations for handling most of your use cases. [![build badge](https://api.travis-ci.org/danielpclark/array_tool.svg?branch=master)](https://travis-ci.org/danielpclark/array_tool)
*  <b><code>&nbsp;&nbsp;&nbsp;304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [fizyk20/generic-array](https://github.com/fizyk20/generic-array) – a hack to allow for arrays sized by typenums [![build badge](https://api.travis-ci.org/fizyk20/generic-array.svg?branch=master)](https://travis-ci.org/fizyk20/generic-array)
*  <b><code>&nbsp;&nbsp;&nbsp;112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [garro95/priority-queue](https://github.com/garro95/priority-queue) 🌎 [priority-queue](crates.io/crates/priority-queue)] — A priority queue that implements priority changes. [![build badge](https://api.travis-ci.org/garro95/priority-queue.svg?branch=master)](https://travis-ci.org/garro95/priority-queue)
*  <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [mrhooray/kdtree-rs](https://github.com/mrhooray/kdtree-rs) — K-dimensional tree in Rust for fast geospatial indexing and nearest neighbors lookup
*  <b><code>&nbsp;&nbsp;&nbsp;834⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [orium/rpds](https://github.com/orium/rpds)  🌎 [rpds](crates.io/crates/rpds)] — Persistent data structures in Rust. [![build badge](https://github.com/orium/rpds/workflows/CI/badge.svg)](https://github.com/orium/rpds/actions?query=workflow%3ACI)
*  <b><code>&nbsp;&nbsp;&nbsp;466⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs) – Roaring Bitmaps in Rust
*  <b><code>&nbsp;&nbsp;1765⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;225🍴</code></b> [rust-itertools/itertools](https://github.com/rust-itertools/itertools) — [![build badge](https://api.travis-ci.org/rust-itertools/itertools.svg?branch=master)](https://travis-ci.org/rust-itertools/itertools)
*  <b><code>&nbsp;&nbsp;&nbsp;204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [tnballo/scapegoat](https://github.com/tnballo/scapegoat)  🌎 [scapegoat](crates.io/crates/scapegoat)] — Safe, fallible, stack-only alternative to `BTreeSet` and `BTreeMap`. [![GitHub Actions](https://github.com/tnballo/scapegoat/workflows/test/badge.svg?branch=master)](https://github.com/tnballo/scapegoat/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [xfix/enum-map](https://github.com/xfix/enum-map)  🌎 [enum-map](crates.io/crates/enum-map)] — An optimized map implementation for enums using an array to store values. [![build badge](https://api.travis-ci.org/xfix/enum-map.svg?branch=master)](https://travis-ci.org/xfix/enum-map)
*  <b><code>&nbsp;&nbsp;&nbsp;206⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [yamafaktory/hypergraph](https://github.com/yamafaktory/hypergraph)  🌎 [hypergraph](crates.io/crates/hypergraph)] — Hypergraph is a data structure library to generate directed hypergraphs. [![ci](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml)

### Data visualization

*  <b><code>&nbsp;&nbsp;&nbsp;557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [igiagkiozis/plotly](https://github.com/igiagkiozis/plotly) — Plotly for Rust.
*  <b><code>&nbsp;&nbsp;&nbsp;378⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [milliams/plotlib](https://github.com/milliams/plotlib) — [![build badge](https://api.travis-ci.org/milliams/plotlib.svg?branch=master)](https://travis-ci.org/milliams/plotlib)
*  <b><code>&nbsp;&nbsp;2250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [plotters](https://github.com/plotters-rs/plotters) — [![build badge](https://github.com/plotters-rs/plotters/workflows/CI/badge.svg)](https://github.com/plotters-rs/plotters/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [saresend/gust](https://github.com/saresend/Gust) — [![build badge](https://api.travis-ci.org/saresend/Gust.svg?branch=master)](https://travis-ci.org/saresend/Gust)

### Date and time

 🌎 [date](crates.io/keywords/date), 🌎 [time](crates.io/keywords/time)]

*  <b><code>&nbsp;&nbsp;2106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;341🍴</code></b> [chronotope/chrono](https://github.com/chronotope/chrono) — [![build badge](https://api.travis-ci.org/chronotope/chrono.svg?branch=master)](https://travis-ci.org/chronotope/chrono)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Mnwa/ms](https://github.com/Mnwa/ms)  🌎 [ms-converter](crates.io/crates/ms-converter)] — it's a library for converting human-like times to milliseconds [![build badge](https://github.com/Mnwa/ms/workflows/build/badge.svg?branch=master)](https://github.com/Mnwa/ms/actions?query=workflow%3Abuild)
*  <b><code>&nbsp;&nbsp;&nbsp;586⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [time-rs/time](https://github.com/time-rs/time) — [![build badge](https://github.com/time-rs/time/workflows/Build/badge.svg)](https://github.com/time-rs/time/actions)

### Distributed systems

* Antimony
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [antimonyproject/antimony](https://github.com/antimonyproject/antimony)  🌎 [antimony](crates.io/crates/antimony)] — stream processing / distributed computation platform [![build badge](https://api.travis-ci.org/antimonyproject/antimony.svg?branch=master)](https://travis-ci.org/antimonyproject/antimony)
* Apache Kafka
  *  <b><code>&nbsp;&nbsp;&nbsp;962⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka)  🌎 [rdkafka](crates.io/crates/rdkafka)] —  <b><code>&nbsp;&nbsp;6105⭐</code></b> <b><code>&nbsp;&nbsp;2777🍴</code></b> [librdkafka](https://github.com/edenhill/librdkafka) bindings [![build badge](https://api.travis-ci.org/fede1024/rust-rdkafka.svg?branch=master)](https://travis-ci.org/fede1024/rust-rdkafka)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [gklijs/schema_registry_converter](https://github.com/gklijs/schema_registry_converter)  🌎 [schema_registry_converter](crates.io/crates/schema_registry_converter)] — to integrate with 🌎 [confluent schema registry](www.confluent.io/product/confluent-platform/data-compatibility/) [![build badge](https://api.travis-ci.org/gklijs/schema_registry_converter.svg?branch=master)](https://travis-ci.org/gklijs/schema_registry_converter)
  *  <b><code>&nbsp;&nbsp;&nbsp;811⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [kafka-rust/kafka-rust](https://github.com/kafka-rust/kafka-rust) — [![build badge](https://api.travis-ci.org/kafka-rust/kafka-rust.svg?branch=master)](https://travis-ci.org/kafka-rust/kafka-rust)
* Beanstalkd
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [schickling/rust-beanstalkd](https://github.com/schickling/rust-beanstalkd) —  <b><code>&nbsp;&nbsp;6174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;861🍴</code></b> [Beanstalkd](https://github.com/beanstalkd/beanstalkd) bindings [![build badge](https://api.travis-ci.org/schickling/rust-beanstalkd.svg?branch=master)](https://travis-ci.org/schickling/rust-beanstalkd)
* HDFS
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [hyunsik/hdfs-rs](https://github.com/hyunsik/hdfs-rs)  🌎 [hdfs](crates.io/crates/hdfs)] — libhdfs bindings

### Domain driven design

  *  <b><code>&nbsp;&nbsp;&nbsp;102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [serverlesstechnology/cqrs](https://github.com/serverlesstechnology/cqrs)  🌎 [cqrs-es](crates.io/crates/cqrs-es)] — A framework for CQRS and event sourcing with 🌎 [user guide](doc.rust-cqrs.org/)

### Email

 🌎 [email](crates.io/keywords/email), 🌎 [imap](crates.io/keywords/imap), 🌎 [smtp](crates.io/keywords/smtp)]

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs) — unofficial Rust library for SendGrid API [![build badge](https://api.travis-ci.org/gsquire/sendgrid-rs.svg?branch=master)](https://travis-ci.org/gsquire/sendgrid-rs)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [jdrouet/catapulte](https://github.com/jdrouet/catapulte) [![build badge](https://api.travis-ci.com/jdrouet/catapulte.svg?branch=main)](https://travis-ci.org/jdrouet/catapulte) - A microservice to send emails using  <b><code>&nbsp;&nbsp;&nbsp;163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [MRML](https://github.com/jdrouet/mrml) templates.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [jdrouet/jolimail](https://github.com/jdrouet/jolimail) [![pipeline status](https://gitlab.com/jeremie.drouet/jolimail/badges/main/pipeline.svg)](https://gitlab.com/jeremie.drouet/jolimail/-/commits/main) - A web application to build  <b><code>&nbsp;&nbsp;&nbsp;163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [MRML](https://github.com/jdrouet/mrml) templates.
*  <b><code>&nbsp;&nbsp;&nbsp;163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [jdrouet/mrml](https://github.com/jdrouet/mrml) [![build badge](https://api.travis-ci.com/jdrouet/mrml.svg?branch=master)](https://travis-ci.org/jdrouet/mrml) - A library to generate nice email templates working on any mail client.
*  <b><code>&nbsp;&nbsp;1151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;157🍴</code></b> [lettre/lettre](https://github.com/lettre/lettre) — an SMTP-library for Rust [![CI](https://github.com/lettre/lettre/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/lettre/lettre/actions/workflows/test.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;141⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [staktrace/mailparse](https://github.com/staktrace/mailparse)  🌎 [mailparse](crates.io/crates/mailparse)] — A library for parsing real-world email files [![build badge](https://api.travis-ci.org/staktrace/mailparse.svg?branch=master)](https://travis-ci.org/staktrace/mailparse)
*  <b><code>&nbsp;&nbsp;&nbsp;135⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [stalwartlabs/mail-parser](https://github.com/stalwartlabs/mail-parser)  🌎 [mail-parser](crates.io/crates/mail-parser)] - A fast and robust e-mail parsing library with full MIME support [![build badge](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [stalwartlabs/mail-send](https://github.com/stalwartlabs/mail-send)  🌎 [mail-send](crates.io/crates/mail-send)] - E-mail builder and SMTP client library with DKIM support [![build badge](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml)

### Encoding

 🌎 [encoding](crates.io/keywords/encoding)]

* ASN.1
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [alex/rust-asn1](https://github.com/alex/rust-asn1) — A Rust ASN.1 (DER) serializer [![build badge](https://api.travis-ci.org/alex/rust-asn1.svg?branch=master)](https://travis-ci.org/alex/rust-asn1)
* Binary
  *  <b><code>&nbsp;&nbsp;1686⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;215🍴</code></b> [bincode-org/bincode](https://github.com/bincode-org/bincode) — A binary encoder/decoder in Rust [![CI](https://github.com/bincode-org/bincode/actions/workflows/rust.yml/badge.svg?branch=trunk)](https://github.com/bincode-org/bincode/actions/workflows/rust.yml)
  *  <b><code>&nbsp;&nbsp;&nbsp;832⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [m4b/goblin](https://github.com/m4b/goblin)  🌎 [goblin](crates.io/crates/goblin)] —  cross-platform, zero-copy, and endian-aware binary parsing [![build badge](https://api.travis-ci.org/m4b/goblin.svg?branch=master)](https://travis-ci.org/m4b/goblin)
* BSON
  *  <b><code>&nbsp;&nbsp;&nbsp;281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [mongodb/bson-rust](https://github.com/mongodb/bson-rust) — Encoding and decoding support for BSON in Rust
* Byte swapping
  *  <b><code>&nbsp;&nbsp;&nbsp;768⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;125🍴</code></b> [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder) — Supports big-endian, little-endian and native byte orders [![build badge](https://api.travis-ci.org/BurntSushi/byteorder.svg?branch=master)](https://travis-ci.org/BurntSushi/byteorder)
* Cap'n Proto
  *  <b><code>&nbsp;&nbsp;1383⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust) — [![build badge](https://api.travis-ci.org/capnproto/capnproto-rust.svg?branch=master)](https://travis-ci.org/capnproto/capnproto-rust)
* CBOR
  * 🌎 [serde_cbor](crates.io/crates/serde_cbor) — CBOR support for serde [![build badge](https://api.travis-ci.org/pyfisch/cbor.svg?branch=master)](https://travis-ci.org/pyfisch/cbor)
* Character Encoding
  *  <b><code>&nbsp;&nbsp;&nbsp;263⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs)  🌎 [encoding_rs](crates.io/crates/encoding_rs)] — A Gecko-oriented implementation of the Encoding Standard in Rust [![build badge](https://api.travis-ci.org/hsivonen/encoding_rs.svg?branch=master)](https://travis-ci.org/hsivonen/encoding_rs)
  *  <b><code>&nbsp;&nbsp;&nbsp;258⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding) — [![build badge](https://api.travis-ci.org/lifthrasiir/rust-encoding.svg?branch=master)](https://travis-ci.org/lifthrasiir/rust-encoding)
* CRC
  *  <b><code>&nbsp;&nbsp;&nbsp;110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs) — [![build badge](https://api.travis-ci.org/mrhooray/crc-rs.svg?branch=master)](https://travis-ci.org/mrhooray/crc-rs)
* CSV
  *  <b><code>&nbsp;&nbsp;1226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) — A fast and flexible CSV reader and writer, with support for Serde [![build badge](https://api.travis-ci.org/BurntSushi/rust-csv.svg?branch=master)](https://travis-ci.org/BurntSushi/rust-csv)
* EDN
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [naomijub/edn-rs](https://github.com/naomijub/edn-rs)  🌎 [edn-rs](crates.io/crates/edn-rs)] — crate to parse and emit EDN format into Rust types. [![Build Status]( https://api.travis-ci.org/naomijub/edn-rs.svg?branch=master)](https://travis-ci.org/naomijub/edn-rs)
* 🌎 [FlatBuffers](google.github.io/flatbuffers/)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [frol/flatc-rust](https://github.com/frol/flatc-rust) — FlatBuffers compiler (flatc) integration for Cargo build scripts [![build badge](https://api.travis-ci.org/frol/flatc-rust.svg?branch=master)](https://travis-ci.org/frol/flatc-rust)
* HAR
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [mandrean/har-rs](https://github.com/mandrean/har-rs)  🌎 [har](crates.io/crates/har)] — A HTTP Archive Format (HAR) serialization & deserialization library [![Build Status](https://api.travis-ci.org/mandrean/har-rs.svg?branch=master)](https://travis-ci.org/mandrean/har-rs)
* HTML
  *  <b><code>&nbsp;&nbsp;1576⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;194🍴</code></b> [servo/html5ever](https://github.com/servo/html5ever) — High-performance browser-grade HTML5 parser [![build badge](https://api.travis-ci.com/servo/html5ever.svg?branch=master)](https://travis-ci.org/servo/html5ever)
* JSON
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [importcjj/rust-ajson](https://github.com/importcjj/rust-ajson) [[ajson]](https://crates.io/crates/ajson) —  Get JSON values quickly [![build badge](https://api.travis-ci.com/importcjj/rust-ajson.svg?branch=master)](https://app.travis-ci.com/github/importcjj/rust-ajson)
  *  <b><code>&nbsp;&nbsp;&nbsp;475⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [maciejhirsz/json-rust](https://github.com/maciejhirsz/json-rust)  🌎 [json](crates.io/crates/json)] — JSON implementation in Rust [![build badge](https://api.travis-ci.org/maciejhirsz/json-rust.svg?branch=master)](https://travis-ci.org/maciejhirsz/json-rust)
  *  <b><code>&nbsp;&nbsp;&nbsp;593⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [pikkr/pikkr](https://github.com/pikkr/pikkr)  🌎 [pikkr](crates.io/crates/pikkr)] — JSON parser which picks up values directly without performing tokenization in Rust
  *  <b><code>&nbsp;&nbsp;3171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;412🍴</code></b> [serde-rs/json](https://github.com/serde-rs/json)  🌎 [serde\_json](crates.io/crates/serde_json)] — JSON support for  <b><code>&nbsp;&nbsp;5784⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;534🍴</code></b> [Serde](https://github.com/serde-rs/serde) framework [![build badge](https://api.travis-ci.org/serde-rs/json.svg?branch=master)](https://travis-ci.org/serde-rs/json)
  *  <b><code>&nbsp;&nbsp;&nbsp;662⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [simd-lite/simd-json](https://github.com/simd-lite/simd-json)  🌎 [simd-json](crates.io/crates/simd-json)] — High performance JSON parser based on a port of simdjson
* MsgPack
  *  <b><code>&nbsp;&nbsp;&nbsp;778⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust) — A pure Rust low/high level MessagePack implementation [![build badge](https://api.travis-ci.org/3Hren/msgpack-rust.svg?branch=master)](https://travis-ci.org/3Hren/msgpack-rust)
* PEM
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [jcreekmore/pem-rs](https://github.com/jcreekmore/pem-rs)  🌎 [pem](crates.io/crates/pem)] — A Rust based way to parse and encode PEM-encoded data [![build badge](https://api.travis-ci.org/jcreekmore/pem-rs.svg?branch=master)](https://travis-ci.org/jcreekmore/pem-rs)
* ProtocolBuffers
  *  <b><code>&nbsp;&nbsp;2124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;315🍴</code></b> [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) — [![build badge](https://api.travis-ci.org/stepancheg/rust-protobuf.svg?branch=master)](https://travis-ci.org/stepancheg/rust-protobuf)
  *  <b><code>&nbsp;&nbsp;2201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [tokio-rs/prost](https://github.com/tokio-rs/prost) — [![continuous integration](https://github.com/tokio-rs/prost/workflows/continuous%20integration/badge.svg?branch=master)](https://github.com/tokio-rs/prost/actions)
* RON (Rusty Object Notation)
  *  <b><code>&nbsp;&nbsp;2092⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [https://github.com/ron-rs/ron](https://github.com/ron-rs/ron) — [![build badge](https://api.travis-ci.org/ron-rs/ron.svg?branch=master)](https://travis-ci.org/https://github.com/ron-rs/ron)
* Serde
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [vityafx/serde-aux](https://github.com/vityafx/serde-aux/) - additional tools for using with the serde library. [![CI](https://github.com/vityafx/serde-aux/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/serde-aux/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/serde-aux.svg)](https://crates.io/crates/serde-aux)
* TOML
  *  <b><code>&nbsp;&nbsp;1004⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [alexcrichton/toml-rs](https://github.com/alexcrichton/toml-rs) — [![build badge](https://api.travis-ci.com/alexcrichton/toml-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/toml-rs)
* XML
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Florob/RustyXML](https://github.com/Florob/RustyXML) — an XML parser written in Rust [![build badge](https://api.travis-ci.org/Florob/RustyXML.svg?branch=master)](https://travis-ci.org/Florob/RustyXML)
  *  <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [media-io/yaserde](https://github.com/media-io/yaserde) — Yet Another Serializer/Deserializer specialized for XML [![build badge](https://api.travis-ci.org/media-io/yaserde.svg?branch=master)](https://travis-ci.org/media-io/yaserde)
  *  <b><code>&nbsp;&nbsp;&nbsp;390⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [netvl/xml-rs](https://github.com/netvl/xml-rs) — A streaming XML library [![build badge](https://api.travis-ci.org/netvl/xml-rs.svg?branch=master)](https://travis-ci.org/netvl/xml-rs)
  *  <b><code>&nbsp;&nbsp;&nbsp;142⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [shepmaster/sxd-document](https://github.com/shepmaster/sxd-document) — An XML library in Rust [![build badge](https://api.travis-ci.org/shepmaster/sxd-document.svg?branch=master)](https://travis-ci.org/shepmaster/sxd-document)
  *  <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [shepmaster/sxd-xpath](https://github.com/shepmaster/sxd-xpath) — An XPath library in Rust [![build badge](https://api.travis-ci.org/shepmaster/sxd-xpath.svg?branch=master)](https://travis-ci.org/shepmaster/sxd-xpath)
  *  <b><code>&nbsp;&nbsp;&nbsp;723⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [tafia/quick-xml](https://github.com/tafia/quick-xml) — High performance XML pull reader/writer [![build badge](https://api.travis-ci.org/tafia/quick-xml.svg?branch=master)](https://travis-ci.org/tafia/quick-xml)
* YAML
  *  <b><code>&nbsp;&nbsp;&nbsp;523⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [chyh1990/yaml-rust](https://github.com/chyh1990/yaml-rust) — The missing YAML 1.2 implementation for Rust. [![build badge](https://api.travis-ci.org/chyh1990/yaml-rust.svg?branch=master)](https://travis-ci.org/chyh1990/yaml-rust)
  *  <b><code>&nbsp;&nbsp;&nbsp;568⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml)  🌎 [serde\_yaml](crates.io/crates/serde_yaml)] — YAML support for  <b><code>&nbsp;&nbsp;5784⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;534🍴</code></b> [Serde](https://github.com/serde-rs/serde) framework [![build](https://img.shields.io/github/workflow/status/dtolnay/serde-yaml/CI/master)](https://github.com/dtolnay/serde-yaml/actions?query=branch%3Amaster)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [vitiral/stfu8](https://github.com/vitiral/stfu8)  🌎 [stfu8](crates.io/crates/stfu8)] — Sorta Text Format in UTF-8 [![build badge](https://api.travis-ci.org/vitiral/stfu8.svg?branch=master)](https://travis-ci.org/vitiral/stfu8)

### Filesystem

 🌎 [filesystem](crates.io/keywords/filesystem)]
* Operations
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2)  🌎 [dbus-udisks2](crates.io/crates/dbus-udisks2)] - UDisks2 DBus API
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [pop-os/sys-mount](https://github.com/pop-os/sys-mount)  🌎 [sys-mount](crates.io/crates/sys-mount)] — High level abstraction for the `mount` / `umount2` system calls.
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [vitiral/path_abs](https://github.com/vitiral/path_abs)  🌎 [path_abs](crates.io/crates/path_abs)] — Absolute serializable path types and associated methods. [![build badge](https://api.travis-ci.org/vitiral/path_abs.svg?branch=master)](https://travis-ci.org/webdesus/fs_extr://travis-ci.org/vitiral/path_abs)
  *  <b><code>&nbsp;&nbsp;&nbsp;143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [webdesus/fs_extra](https://github.com/webdesus/fs_extra) — expanding opportunities standard library std::fs and std::io [![build badge](https://api.travis-ci.org/webdesus/fs_extra.svg?branch=master)](https://travis-ci.org/webdesus/fs_extra)
* Temporary Files
  *  <b><code>&nbsp;&nbsp;&nbsp;666⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [Stebalien/tempfile](https://github.com/Stebalien/tempfile) — temporary file library [![build badge](https://api.travis-ci.org/Stebalien/tempfile.svg?branch=master)](https://travis-ci.org/Stebalien/tempfile)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Stebalien/xattr](https://github.com/Stebalien/xattr)  🌎 [xattr](crates.io/crates/xattr)] — list and manipulate unix extended file attributes [![build badge](https://api.travis-ci.org/Stebalien/xattr.svg?branch=master)](https://travis-ci.org/Stebalien/xattr)
  *  <b><code>&nbsp;&nbsp;1319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [zboxfs/zbox](https://github.com/zboxfs/zbox)  🌎 [zbox](crates.io/crates/zbox)] — Zero-details, privacy-focused embeddable file system. [![build badge](https://api.travis-ci.org/zboxfs/zbox.svg?branch=master)](https://travis-ci.org/zboxfs/zbox)

### Functional Programming

 🌎 [functional programming](crates.io/keywords/fp)]
* Prelude
  *  <b><code>&nbsp;&nbsp;1046⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [JasonShin/fp-core.rs](https://github.com/JasonShin/fp-core.rs) — A library for functional programming in Rust
  *  <b><code>&nbsp;&nbsp;&nbsp;184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [myrrlyn/tap](https://github.com/myrrlyn/tap) - Suffix-Position Pipeline Behavior

### Game development

See also 🌎 [Are we game yet?](arewegameyet.rs)
* Allegro
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro) — 🌎 [Allegro 5](liballeg.org/) bindings [![build badge](https://api.travis-ci.org/SiegeLord/RustAllegro.svg?branch=master)](https://travis-ci.org/SiegeLord/RustAllegro)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Awesome Quads](https://github.com/ozkriff/awesome-quads) — A curated list of links to miniquad/macroquad-related code & resources
*  <b><code>&nbsp;&nbsp;&nbsp;239⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Awesome wgpu](https://github.com/rofrol/awesome-wgpu) — A curated list of wgpu code and resources
* bracket-lib (previously RLTK)
  *  <b><code>&nbsp;&nbsp;&nbsp;988⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [bracket-lib](https://github.com/amethyst/bracket-lib)  🌎 [bracket-lib](crates.io/crates/bracket-lib)] - The Roguelike Toolkit (RLTK), implemented for Rust. [![Rust](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml/badge.svg)](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml)
* Challonge
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [vityafx/challonge-rs](https://github.com/vityafx/challonge-rs)  🌎 [challonge](crates.io/crates/challonge)] — Client library for the Challonge REST API. Helps to organize tournaments. [![CI](https://github.com/vityafx/challonge-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/challonge-rs/actions/workflows/ci.yml)
* Corange
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [lucidscape/corange-rs](https://github.com/lucidscape/corange-rs) —  <b><code>&nbsp;&nbsp;1513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [Corange](https://github.com/orangeduck/Corange) bindings
* Entity-Component Systems (ECS)
  *  <b><code>&nbsp;&nbsp;2100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;205🍴</code></b> [amethyst/specs](https://github.com/amethyst/specs) — Specs Parallel ECS [![build badge](https://api.travis-ci.org/amethyst/specs.svg?branch=master)](https://travis-ci.org/amethyst/specs)
  *  <b><code>&nbsp;&nbsp;1357⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [legion](https://github.com/amethyst/legion) — A feature rich high performance ECS library with minimal boilerplate [![build badge](https://github.com/amethyst/legion/workflows/CI/badge.svg?branch=master)](https://github.com/amethyst/legion/actions)
* Game Engines
  *  <b><code>&nbsp;17429⭐</code></b> <b><code>&nbsp;&nbsp;1655🍴</code></b> [Bevy](https://github.com/bevyengine/bevy) is a refreshingly simple data-driven game engine built in Rust. - [![Crates.io](https://img.shields.io/crates/v/bevy.svg)](https://crates.io/crates/bevy)
[![Crates.io](https://img.shields.io/crates/d/bevy.svg)](https://crates.io/crates/bevy)
  * 🌎 [Fyrox](fyrox.rs/) — Rust Game engine 3D [![Crates.io](https://img.shields.io/crates/v/fyrox.svg)](https://crates.io/crates/fyrox) [![license](https://img.shields.io/crates/l/fyrox.svg)](https://github.com/FyroxEngine/Fyrox/blob/master/LICENSE.md) [![Crates.io](https://img.shields.io/crates/d/fyrox.svg)](https://crates.io/crates/fyrox)
  *  <b><code>&nbsp;&nbsp;3362⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;386🍴</code></b> [ggez](https://github.com/ggez/ggez) — A lightweight game framework for making 2D games with minimum friction - [![Crates.io](https://img.shields.io/crates/v/ggez.svg)](https://crates.io/crates/ggez) [![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ggez/ggez/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/ggez.svg)](https://crates.io/crates/ggez)
  * [Kiss3d](http://kiss3d.org) — A Keep It Simple, Stupid 3d graphics engine written with Rust [![Crates.io](https://img.shields.io/crates/d/kiss3d.svg)](https://crates.io/crates/kiss3d)
  *  <b><code>&nbsp;&nbsp;&nbsp;247⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [oxidator](https://github.com/Ruddle/oxidator) — A real time strategy game/engine written with Rust and WebGPU
  * 🌎 [Piston](www.piston.rs/) — [![Crates.io](https://img.shields.io/crates/v/piston.svg?style=flat-square)](https://crates.io/crates/piston) [![Crates.io](https://img.shields.io/crates/l/piston.svg)](https://github.com/PistonDevelopers/piston/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/piston.svg)](https://crates.io/crates/piston)
  *  <b><code>&nbsp;&nbsp;&nbsp;364⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Unrust](https://github.com/unrust/unrust) — unrust — A pure rust based (webgl 2.0 / native) game engine
* 🌎 [Godot](godotengine.org/)
  *  <b><code>&nbsp;&nbsp;2652⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [godot-rust/godot-rust](https://github.com/godot-rust/godot-rust)  🌎 [gdnative](crates.io/crates/gdnative)] - Rust bindings to the Godot game engine [![CI](https://github.com/godot-rust/godot-rust/actions/workflows/full-ci.yml/badge.svg)](https://github.com/godot-rust/godot-rust/actions/workflows/full-ci.yml)
* 🌎 [Raylib](www.raylib.com/)
  *  <b><code>&nbsp;&nbsp;&nbsp;435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [deltaphc/raylib-rs](https://github.com/deltaphc/raylib-rs)  🌎 [raylib](crates.io/crates/raylib)] — Rust bindings for raylib
* [SDL](http://www.libsdl.org/)  🌎 [sdl](crates.io/keywords/sdl)]
  *  <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [brson/rust-sdl](https://github.com/brson/rust-sdl) — SDL1 bindings [![build badge](https://api.travis-ci.org/brson/rust-sdl.svg?branch=master)](https://travis-ci.org/brson/rust-sdl)
  *  <b><code>&nbsp;&nbsp;2053⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;385🍴</code></b> [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2) — SDL2 bindings [![build badge](https://api.travis-ci.org/Rust-SDL2/rust-sdl2.svg?branch=master)](https://travis-ci.org/Rust-SDL2/rust-sdl2)
* SFML
  *  <b><code>&nbsp;&nbsp;&nbsp;542⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml) — 🌎 [SFML](www.sfml-dev.org/) bindings
* Tcod-rs
  *  <b><code>&nbsp;&nbsp;&nbsp;225⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [tomassedovic/tcod-rs](https://github.com/tomassedovic/tcod-rs) — Libtcod bindings for Rust.
  * Warning: Not maintained anymore
* Toornament-rs
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [vityafx/toornament-rs](https://github.com/vityafx/toornament-rs) - Toornament.com API bindings for Rust. [![CI](https://github.com/vityafx/toornament-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/toornament-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/toornament.svg)](https://crates.io/crates/toornament)
* Victorem
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [VictoremWinbringer/Victorem](https://github.com/VictoremWinbringer/Victorem)  🌎 [Victorem](crates.io/crates/Victorem)] — Easy UDP Game Server and UDP Client framework for creating simple 2D and 3D online game prototype [![build badge](https://api.travis-ci.org/VictoremWinbringer/Victorem.svg?branch=master)](https://travis-ci.org/VictoremWinbringer/Victorem)

### Geospatial

 🌎 [geo](crates.io/keywords/geo), 🌎 [gis](crates.io/keywords/gis)]

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [DaveKram/coord_transforms](https://github.com/DaveKram/coord_transforms)  🌎 [coord_transforms](crates.io/crates/coord_transforms)] — coordinate transformations (2-d, 3-d, and geospatial) [![build badge](https://api.travis-ci.org/DaveKram/coord_transforms.svg?branch=master)](https://travis-ci.org/DaveKram/coord_transforms)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Georust](https://github.com/georust) — geospatial tools and libraries written in Rust
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [rust-reverse-geocoder](https://github.com/gx0r/rrgeo) — A fast, offline reverse geocoder in Rust, inspired by  <b><code>&nbsp;&nbsp;1772⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;153🍴</code></b> [thampiman/reverse-geocoder](https://github.com/thampiman/reverse-geocoder)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [vlopes11/geomorph](https://github.com/vlopes11/geomorph)  🌎 [geomorph](crates.io/crates/geomorph)] — conversion between UTM, LatLon and MGRS coordinates [![build badge](https://api.travis-ci.org/vlopes11/geomorph.svg?branch=master)](https://travis-ci.org/vlopes11/geomorph)

### Graphics

 🌎 [graphics](crates.io/keywords/graphics)]

* Font
  *  <b><code>&nbsp;&nbsp;&nbsp;271⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [RazrFalcon/rustybuzz](https://github.com/RazrFalcon/rustybuzz) - An incremental harfbuzz port to Rust [![build badge](https://api.travis-ci.org/RazrFalcon/rustybuzz.svg?branch=master)](https://travis-ci.org/RazrFalcon/rustybuzz)
  *  <b><code>&nbsp;&nbsp;&nbsp;557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [redox-os/rusttype](https://github.com/redox-os/rusttype) — A pure Rust alternative to libraries like FreeType [![build badge](https://api.travis-ci.org/redox-os/rusttype.svg?branch=master)](https://travis-ci.org/redox-os/rusttype)
*  <b><code>&nbsp;&nbsp;5171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;573🍴</code></b> [gfx-rs/gfx](https://github.com/gfx-rs/gfx) — A high-performance, bindless graphics API for Rust. [![build badge](https://api.travis-ci.org/gfx-rs/gfx.svg?branch=master)](https://travis-ci.org/gfx-rs/gfx)
*  <b><code>&nbsp;&nbsp;5285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;446🍴</code></b> [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu) - Native WebGPU implementation based on gfx-hal. [![build badge](https://github.com/gfx-rs/wgpu/workflows/CI/badge.svg?branch=master)](https://github.com/gfx-rs/wgpu/actions)
* OpenGL  🌎 [opengl](crates.io/keywords/opengl)]
  *  <b><code>&nbsp;&nbsp;&nbsp;611⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [brendanzab/gl-rs](https://github.com/brendanzab/gl-rs) — [![build badge](https://api.travis-ci.org/brendanzab/gl-rs.svg?branch=master)](https://travis-ci.org/brendanzab/gl-rs)
  *  <b><code>&nbsp;&nbsp;2985⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;369🍴</code></b> [glium/glium](https://github.com/glium/glium) — safe OpenGL wrapper for the Rust language. [![build badge](https://api.travis-ci.org/glium/glium.svg?branch=master)](https://travis-ci.org/glium/glium)
  * 🌎 [glutin](crates.io/crates/glutin) — Rust alternative to 🌎 [GLFW](www.glfw.org/) [![build badge](https://api.travis-ci.org/rust-windowing/glutin.svg?branch=master)](https://travis-ci.org/rust-windowing/glutin)
  * [Kiss3d](http://kiss3d.org) — draw simple geometric figures and play with them with one-liners [![build badge](https://api.travis-ci.org/sebcrozet/kiss3d.svg?branch=master)](https://api.travis-ci.org/repositories/sebcrozet/kiss3d)
  *  <b><code>&nbsp;&nbsp;&nbsp;514⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [PistonDevelopers/glfw-rs](https://github.com/PistonDevelopers/glfw-rs) — [![build badge](https://api.travis-ci.org/PistonDevelopers/glfw-rs.svg?branch=master)](https://travis-ci.org/PistonDevelopers/glfw-rs)
* PDF
  *  <b><code>&nbsp;&nbsp;&nbsp;531⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [fschutt/printpdf](https://github.com/fschutt/printpdf) — PDF writing library [![build badge](https://api.travis-ci.org/fschutt/printpdf.svg?branch=master)](https://travis-ci.org/fschutt/printpdf)
  *  <b><code>&nbsp;&nbsp;&nbsp;966⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf) — PDF document manipulation [![build badge](https://api.travis-ci.org/J-F-Liu/lopdf.svg?branch=master)](https://travis-ci.org/J-F-Liu/lopdf)
  *  <b><code>&nbsp;&nbsp;&nbsp;117⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [kaj/rust-pdf](https://github.com/kaj/rust-pdf) — [![build badge](https://api.travis-ci.org/kaj/rust-pdf.svg?branch=master)](https://travis-ci.org/kaj/rust-pdf)
  *  <b><code>&nbsp;&nbsp;&nbsp;322⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [WASM-PDF](https://github.com/jussiniinikoski/wasm-pdf) – Generates PDF files with JavaScript and WASM (WebAssembly) [![build badge](https://api.travis-ci.org/jussiniinikoski/wasm-pdf.svg?branch=master)](https://travis-ci.org/jussiniinikoski/wasm-pdf)
* 🌎 [Vulkan](www.vulkan.org/)  🌎 [vulkan](crates.io/keywords/vulkan)]
  * 🌎 [erupt](gitlab.com/Friz64/erupt)  🌎 [erupt](crates.io/crates/erupt)] — [![build badge](https://gitlab.com/Friz64/erupt/badges/main/pipeline.svg)](https://gitlab.com/Friz64/erupt/-/pipelines)
  *  <b><code>&nbsp;&nbsp;3281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;352🍴</code></b> [vulkano](https://github.com/vulkano-rs/vulkano)  🌎 [vulkano](crates.io/crates/vulkano)] — [![build badge](https://api.travis-ci.org/vulkano-rs/vulkano.svg?branch=master)](https://travis-ci.org/vulkano-rs/vulkano)

### GUI

 🌎 [gui](crates.io/keywords/gui)]

*  <b><code>&nbsp;&nbsp;&nbsp;251⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [autopilot-rs/autopilot-rs](https://github.com/autopilot-rs/autopilot-rs) — A simple, cross-platform GUI automation library for Rust.
* Cocoa
  *  <b><code>&nbsp;&nbsp;&nbsp;608⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;168🍴</code></b> [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs) — [![build badge](https://api.travis-ci.com/servo/core-foundation-rs.svg?branch=master)](https://travis-ci.org/servo/core-foundation-rs)
*  <b><code>&nbsp;&nbsp;4452⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [DioxusLabs/dioxus](https://github.com/dioxuslabs/dioxus) - a portable, performant, and ergonomic framework for building cross-platform user interfaces in Rust. ![rust ci](https://github.com/dioxuslabs/dioxus/actions/workflows/main.yml/badge.svg)
*  <b><code>&nbsp;&nbsp;6964⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;479🍴</code></b> [Druid](https://github.com/linebender/druid)  🌎 [druid](crates.io/crates/druid)] — 🌎 [Druid](linebender.org/druid/), a data-first Rust-native UI design toolkit. [![build badge](https://github.com/linebender/druid/workflows/.github/workflows/ci.yml/badge.svg)](https://github.com/linebender/druid/actions)
*  <b><code>&nbsp;&nbsp;9852⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;624🍴</code></b> [emilk/egui](https://github.com/emilk/egui) - Simple, fast, and highly portable immediate mode GUI library for Rust. egui runs on the web, natively, and in your favorite game engine. [![Build Status](https://github.com/emilk/egui/workflows/CI/badge.svg)](https://github.com/emilk/egui/actions?workflow=CI)
*  <b><code>&nbsp;&nbsp;&nbsp;716⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [emoon/rust_minifb](https://github.com/emoon/rust_minifb) — minifb is a cross-platform window setup with optional bitmap rendering. It also comes with easy mouse and keyboard input. Primarily designed for prototyping
* 🌎 [FLTK](www.fltk.org/)
  *  <b><code>&nbsp;&nbsp;&nbsp;859⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [fltk-rs](https://github.com/fltk-rs/fltk-rs) — FLTK Rust bindings [![Build](https://github.com/fltk-rs/fltk-rs/workflows/Build/badge.svg?branch=master)](https://github.com/fltk-rs/fltk-rs/actions)
* 🌎 [Flutter](flutter.dev/)
  *  <b><code>&nbsp;&nbsp;1956⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [flutter-rs](https://github.com/flutter-rs/flutter-rs) — Build flutter desktop app in dart & rust.
*  <b><code>&nbsp;&nbsp;5211⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;204🍴</code></b> [fschutt/azul](https://github.com/fschutt/azul) — A free, functional, IMGUI-oriented GUI framework for rapid development of desktop applications written in Rust, supported by the Mozilla WebRender rendering engine. [![build badge](https://api.travis-ci.org/fschutt/azul.svg?branch=master)](https://travis-ci.org/fschutt/azul)
* 🌎 [GTK+](www.gtk.org/)  🌎 [gtk](crates.io/keywords/gtk)]
  *  <b><code>&nbsp;&nbsp;&nbsp;377⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [gtk-rs/gtk3-rs](https://github.com/gtk-rs/gtk3-rs) - GTK3 binding for rust ![CI](https://github.com/gtk-rs/gtk3-rs/workflows/CI/badge.svg)
  *  <b><code>&nbsp;&nbsp;2165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [relm](https://github.com/antoyo/relm) — Asynchronous, GTK+-based, GUI library, inspired by Elm [![build badge](https://api.travis-ci.org/antoyo/relm.svg?branch=master)](https://travis-ci.org/antoyo/relm)
*  <b><code>&nbsp;14521⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;625🍴</code></b> [iced-rs/iced](https://github.com/iced-rs/iced)  🌎 [iced](crates.io/crates/iced)] — A cross-platform GUI library for Rust focused on simplicity and type-safety. Inspired by Elm.
*  <b><code>&nbsp;40072⭐</code></b> <b><code>&nbsp;&nbsp;7043🍴</code></b> [ImGui](https://github.com/ocornut/imgui)
  *  <b><code>&nbsp;&nbsp;1827⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;276🍴</code></b> [imgui-rs](https://github.com/imgui-rs/imgui-rs) — Rust bindings for ImGui [![Build Status](https://github.com/imgui-rs/imgui-rs/workflows/ci/badge.svg?branch=master)](https://github.com/imgui-rs/imgui-rs/actions)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
  *  <b><code>&nbsp;&nbsp;&nbsp;342⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Kiss-ui](https://github.com/KISS-UI/kiss-ui) — A simple UI framework built on IUP [![Build Status](https://api.travis-ci.org/cybergeek94/kiss-ui.svg?branch=master)](https://travis-ci.org/cybergeek94/kiss-ui)
*  <b><code>&nbsp;&nbsp;&nbsp;626⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [ivanceras/sauron-native](https://github.com/ivanceras/sauron-native) - A truly native and cross platform GUI library. One unified code can be run as native GUI, Html Web and TUI. [![Build Status](https://api.travis-ci.com/ivanceras/sauron-native.svg?branch=master)](https://app.travis-ci.com/github/ivanceras/sauron-native)
*  <b><code>&nbsp;10304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;614🍴</code></b> [libui](https://github.com/andlabs/libui)
  *  <b><code>&nbsp;&nbsp;&nbsp;852⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [rust-native-ui/libui-rs](https://github.com/rust-native-ui/libui-rs) — libui bindings [![build badge](https://api.travis-ci.org/rust-native-ui/libui-rs.svg?branch=master)](https://travis-ci.org/rust-native-ui/libui-rs).
*  <b><code>&nbsp;&nbsp;5868⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;367🍴</code></b> [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear)
  *  <b><code>&nbsp;&nbsp;&nbsp;326⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [nuklear-rust](https://github.com/snuk182/nuklear-rust) — Rust bindings for Nuklear
*  <b><code>&nbsp;&nbsp;3661⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;196🍴</code></b> [OrbTk](https://github.com/redox-os/orbtk) — The Orbital Widget Toolkit is a multi platform (G)UI toolkit using SDL2 [![Build and test](https://github.com/redox-os/orbtk/workflows/build/badge.svg?branch=develop)](https://github.com/redox-os/orbtk/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod/) — An easy-to-use, immediate-mode, 2D GUI library written entirely in Rust [![build badge](https://api.travis-ci.org/PistonDevelopers/conrod.svg?branch=master)](https://travis-ci.org/PistonDevelopers/conrod)
* 🌎 [Qt](doc.qt.io)
  *  <b><code>&nbsp;&nbsp;&nbsp;433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [cyndis/qmlrs](https://github.com/cyndis/qmlrs) — QtQuick bindings [![build badge](https://api.travis-ci.org/cyndis/qmlrs.svg?branch=master)](https://travis-ci.org/cyndis/qmlrs)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [rust-qt](https://github.com/rust-qt)
  *  <b><code>&nbsp;&nbsp;&nbsp;462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [woboq/qmetaobject-rs](https://github.com/woboq/qmetaobject-rs) — Integrate Qml and Rust by building the QMetaObject at compile time. [![build badge](https://api.travis-ci.org/woboq/qmetaobject-rs.svg?branch=master)](https://travis-ci.org/woboq/qmetaobject-rs)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [rise-ui](https://github.com/rise-ui/rise) — Simple component-based cross-Platform GUI Toolkit for developing beautiful and user-friendly interfaces.
*  <b><code>&nbsp;&nbsp;&nbsp;149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [saurvs/nfd-rs](https://github.com/saurvs/nfd-rs) —  <b><code>&nbsp;&nbsp;1396⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;172🍴</code></b> [nativefiledialog](https://github.com/mlabbe/nativefiledialog) bindings
* 🌎 [Sciter](sciter.com/)
  *  <b><code>&nbsp;&nbsp;&nbsp;728⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [sciter-sdk/rust-sciter](https://github.com/sciter-sdk/rust-sciter) — Sciter bindings [![build badge](https://ci.appveyor.com/api/projects/status/github/sciter-sdk/rust-sciter?svg=true)](https://ci.appveyor.com/project/sciter-sdk/rust-sciter)
*  <b><code>&nbsp;&nbsp;4706⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [slint-ui/slint](https://github.com/slint-ui/slint)  🌎 [slint](crates.io/crates/slint)] — 🌎 [Slint](slint-ui.com) is a toolkit to efficiently develop fluid graphical user interfaces for embedded devices and desktop applications. [![Build Status](https://github.com/slint-ui/slint/workflows/CI/badge.svg?branch=master)](https://github.com/slint-ui/slint/actions?query=workflow%3ACI)
*  <b><code>&nbsp;47561⭐</code></b> <b><code>&nbsp;&nbsp;1193🍴</code></b> [tauri-apps/tauri](https://github.com/tauri-apps/tauri) — Build smaller, faster, and more secure desktop applications with a web frontend, powered by  <b><code>&nbsp;&nbsp;1798⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [WRY](https://github.com/tauri-apps/wry). [![test library](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+library%22)
*  <b><code>&nbsp;&nbsp;1798⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [tauri-apps/wry](https://github.com/tauri-apps/wry) - Webview Rendering librarY.

### Image processing

*  <b><code>&nbsp;&nbsp;&nbsp;250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [abonander/img_hash](https://github.com/abonander/img_hash) — Perceptual image hashing and comparison for equality and similarity. [![Build Status](https://api.travis-ci.org/abonander/img_hash.svg?branch=master)](https://travis-ci.org/abonander/img_hash)
*  <b><code>&nbsp;&nbsp;3112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;467🍴</code></b> [image-rs/image](https://github.com/image-rs/image) — Basic imaging processing functions and methods for converting to and from image formats [![build badge](https://api.travis-ci.org/image-rs/image.svg?branch=master)](https://travis-ci.org/image-rs/image)
*  <b><code>&nbsp;&nbsp;&nbsp;467⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [image-rs/imageproc](https://github.com/image-rs/imageproc) — An image processing library, based on the `image` library. [![Build Status](https://api.travis-ci.org/image-rs/imageproc.svg?branch=master)](https://travis-ci.org/image-rs/imageproc)
*  <b><code>&nbsp;&nbsp;&nbsp;362⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [rust-cv/cv](https://github.com/rust-cv/cv) — Rust CV is a project to implement computer vision algorithms, abstractions, and systems in Rust. #[no_std] is supported where possible. ![build badge](https://github.com/rust-cv/cv/workflows/tests/badge.svg)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [teovoinea/steganography](https://github.com/teovoinea/steganography)  🌎 [steganography](crates.io/crates/steganography)] — A simple steganography library [![build badge](https://api.travis-ci.org/teovoinea/steganography.svg?branch=master)](https://travis-ci.org/teovoinea/steganography)
*  <b><code>&nbsp;&nbsp;1008⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust) — Rust bindings for OpenCV [![build badge](https://api.travis-ci.org/twistedfall/opencv-rust.svg?branch=cv2)](https://travis-ci.org/twistedfall/opencv-rust)

### Language specification

*  <b><code>&nbsp;&nbsp;&nbsp;164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [shnewto/bnf](https://github.com/shnewto/bnf) — A library for parsing Backus–Naur form context-free grammars. [![build badge](https://api.travis-ci.org/shnewto/bnf.svg?branch=master)](https://travis-ci.org/shnewto/bnf)

### Logging

 🌎 [log](crates.io/keywords/log)]

*  <b><code>&nbsp;&nbsp;&nbsp;679⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [estk/log4rs](https://github.com/estk/log4rs) — highly configurable logging framework modeled after Java's Logback and log4j libraries [![CircleCI](https://circleci.com/gh/estk/log4rs.svg?style=shield)](https://app.circleci.com/pipelines/github/estk/log4rs)
*  <b><code>&nbsp;&nbsp;&nbsp;198⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [jesusprubio/leg](https://github.com/jesusprubio/leg) — Elegant print for lazy devs. Make your CLIs nicer with minimal effort. [![Build Status](https://github.com/jesusprubio/leg/workflows/CI/badge.svg)](https://github.com/jesusprubio/leg/actions/workflows/ci.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [rbatis/fast_log](https://github.com/rbatis/fast_log) — Rust async log High-performance asynchronous logging [![Build Status](https://api.travis-ci.com/rbatis/fast_log.svg?branch=master)](https://travis-ci.org/rbatis/fast_log)
*  <b><code>&nbsp;&nbsp;1443⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [rust-lang/log](https://github.com/rust-lang/log) — Logging implementation for Rust [![Build Status](https://api.travis-ci.org/rust-lang/log.svg?branch=master)](https://travis-ci.org/rust-lang/log)
*  <b><code>&nbsp;&nbsp;&nbsp;350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [seanmonstar/pretty-env-logger](https://github.com/seanmonstar/pretty-env-logger) — A pretty, easy-to-use logger for Rust. [![Build Status](https://api.travis-ci.org/seanmonstar/pretty-env-logger.svg?branch=master)](https://travis-ci.org/seanmonstar/pretty-env-logger)
*  <b><code>&nbsp;&nbsp;1268⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [slog-rs/slog](https://github.com/slog-rs/slog) — Structured, composable logging for Rust [![Build Status](https://api.travis-ci.org/slog-rs/slog.svg?branch=master)](https://travis-ci.org/slog-rs/slog)
*  <b><code>&nbsp;&nbsp;2774⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;410🍴</code></b> [tokio-rs/tracing](https://github.com/tokio-rs/tracing) — An application level tracing framework for async-aware structured logging, error handling, metrics, and more [![Build Status](https://github.com/tokio-rs/tracing/workflows/CI/badge.svg?branch=master)](https://github.com/tokio-rs/tracing/actions?query=workflow%3ACI)

### Macro

* cute
  *  <b><code>&nbsp;&nbsp;&nbsp;294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [mattgathu/cute](https://github.com/mattgathu/cute) — Macro for Python-esque list comprehensions in Rust. [![Build Status](https://api.travis-ci.org/mattgathu/cute.svg?branch=master)](https://travis-ci.org/tensorflow/rust)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Linq-in-Rust](https://github.com/StardustDL/Linq-in-Rust) - Macro and methods for C#-LINQ-like expressions. [![CI](https://github.com/StardustDL/Linq-in-Rust/workflows/CI/badge.svg?branch=master)](https://github.com/StardustDL/Linq-in-Rust/actions?query=workflow%3ACI)

### Markup language

* CommonMark
  *  <b><code>&nbsp;&nbsp;1384⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [raphlinus/pulldown-cmark](https://github.com/raphlinus/pulldown-cmark) — 🌎 [CommonMark](commonmark.org/) parser in Rust

### Mobile

* Android / iOS
  *  <b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [ivanschuetz/rust_android_ios](https://github.com/ivanschuetz/rust_android_ios) — An example of using a shared Rust lib for Android and iOS using rust-swig and cbindgen respectively.
* Generic
  *  <b><code>&nbsp;&nbsp;&nbsp;156⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Geal/rust_on_mobile](https://github.com/Geal/rust_on_mobile)
* iOS
  *  <b><code>&nbsp;&nbsp;&nbsp;394⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo) — A cargo lipo subcommand which automatically creates a universal library for use with your iOS application. [![build badge](https://api.travis-ci.org/TimNN/cargo-lipo.svg?branch=master)](https://travis-ci.org/TimNN/cargo-lipo)

### Network programming

* Bluetooth
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [bluez/bluer](https://github.com/bluez/bluer)  🌎 [bluer](crates.io/crates/bluer)] — Official BlueZ bindings for Rust. [![build badge](https://github.com/bluez/bluer/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/bluez/bluer/actions/workflows/rust.yml)
* CoAP
  *  <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Covertness/coap-rs](https://github.com/Covertness/coap-rs) — A 🌎 [Constrained Application Protocol(CoAP)](datatracker.ietf.org/doc/html/rfc7252) library for Rust. [![build badge](https://api.travis-ci.org/Covertness/coap-rs.svg?branch=master)](https://travis-ci.org/Covertness/coap-rs)
* Docker
  *  <b><code>&nbsp;&nbsp;&nbsp;357⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [fussybeaver/bollard](https://github.com/fussybeaver/bollard) — Docker daemon API in Rust
* FTP
  *  <b><code>&nbsp;&nbsp;&nbsp;143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [mattnenterprise/rust-ftp](https://github.com/mattnenterprise/rust-ftp) — an 🌎 [FTP](en.wikipedia.org/wiki/File_Transfer_Protocol) client for Rust [![build badge](https://api.travis-ci.org/mattnenterprise/rust-ftp.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-ftp)
* gRPC
  *  <b><code>&nbsp;&nbsp;1570⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;223🍴</code></b> [tikv/grpc-rs](https://github.com/tikv/grpc-rs) — The gRPC library for Rust built on C Core library and futures [![Build Status](https://api.travis-ci.org/tikv/grpc-rs.svg?branch=master)](https://travis-ci.org/tikv/grpc-rs)
* IPNetwork
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [achanda/ipnetwork](https://github.com/achanda/ipnetwork) — A library to work with IP networks in pure Rust [![build badge](https://api.travis-ci.org/achanda/ipnetwork.svg?branch=master)](https://travis-ci.org/achanda/ipnetwork)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [candrew/netsim](https://github.com/canndrew/netsim) — A Rust library for network simulation and testing [![build badge](https://api.travis-ci.org/canndrew/netsim.svg?branch=master)](https://travis-ci.org/canndrew/netsim)
* Low level
  *  <b><code>&nbsp;&nbsp;7262⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;600🍴</code></b> [actix/actix](https://github.com/actix/actix) — Actor library for Rust [![build badge](https://api.travis-ci.org/actix/actix.svg?branch=master)](https://travis-ci.org/actix/actix)
  *  <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [dylanmckay/protocol](https://github.com/dylanmckay/protocol) — Custom TCP/UDP protocol definitions
  *  <b><code>&nbsp;&nbsp;1675⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;260🍴</code></b> [libpnet/libpnet](https://github.com/libpnet/libpnet) — A cross-platform, low level networking [![build badge](https://api.travis-ci.org/libpnet/libpnet.svg?branch=master)](https://travis-ci.org/libpnet/libpnet)
  *  <b><code>&nbsp;&nbsp;2596⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;277🍴</code></b> [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp) — A standalone, event-driven TCP/IP stack that is designed for bare-metal, real-time systems [![build badge](https://api.travis-ci.org/smoltcp-rs/smoltcp.svg?branch=master)](https://travis-ci.org/smoltcp-rs/smoltcp)
  *  <b><code>&nbsp;16923⭐</code></b> <b><code>&nbsp;&nbsp;1573🍴</code></b> [tokio-rs/tokio](https://github.com/tokio-rs/tokio) — A network application framework for rapid development and highly scalable production deployments of clients and servers.
* message-io
  *  <b><code>&nbsp;&nbsp;&nbsp;772⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [lemunozm/message-io](https://github.com/lemunozm/message-io) — Event-driven message library to build network applications easy and fast. Supports TCP, UDP and WebSockets. [![build badge](https://img.shields.io/github/workflow/status/lemunozm/message-io/message-io%20ci)](https://github.com/lemunozm/message-io/actions?query=workflow%3A%22message-io+ci%22)
* MQTT
  *  <b><code>&nbsp;&nbsp;&nbsp;560⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [bytebeamio/rumqtt](https://github.com/bytebeamio/rumqtt) - A library for developers to build applications that communicate with the 🌎 [MQTT protocol](mqtt.org) over TCP and WebSockets, with or without TLS. [![Build and Test](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml/badge.svg)](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml)
* NanoMsg
  *  <b><code>&nbsp;&nbsp;&nbsp;368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs) — 🌎 [nanomsg](nanomsg.org/) bindings [![build badge](https://api.travis-ci.org/thehydroimpulse/nanomsg.rs.svg?branch=master)](https://travis-ci.org/thehydroimpulse/nanomsg.rs)
* NATS
  *  <b><code>&nbsp;&nbsp;&nbsp;550⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [nats-io/nats.rs](https://github.com/nats-io/nats.rs) — Rust client for NATS, the cloud native messaging system. [![Build Status](https://github.com/nats-io/nats.rs/workflows/Rust/badge.svg?branch=master)](https://github.com/nats-io/nats.rs/actions)
* Nng
  * 🌎 [neachdainn/nng-rs](gitlab.com/neachdainn/nng-rs)  🌎 [Nng](crates.io/crates/nng)] — 🌎 [Nng (nanomsg v2)](nng.nanomsg.org/index.html) bindings [![build badge](https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg)](https://gitlab.com/neachdainn/nng-rs/-/pipelines)
* NNTP
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [mattnenterprise/rust-nntp](https://github.com/mattnenterprise/rust-nntp)  🌎 [nntp](crates.io/crates/nntp)] — an 🌎 [NNTP](en.wikipedia.org/wiki/Network_News_Transfer_Protocol) client for Rust [![build badge](https://api.travis-ci.org/mattnenterprise/rust-nntp.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-nntp)
* P2P
  *  <b><code>&nbsp;&nbsp;2578⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;533🍴</code></b> [libp2p/rust-libp2p](https://github.com/libp2p/rust-libp2p) — The Rust Implementation of libp2p networking stack. [![Circle CI](https://circleci.com/gh/libp2p/rust-libp2p.svg?style=svg)](https://app.circleci.com/pipelines/github/libp2p/rust-libp2p)
* POP3
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [mattnenterprise/rust-pop3](https://github.com/mattnenterprise/rust-pop3)  🌎 [pop3](crates.io/crates/pop3)] — A 🌎 [POP3](en.wikipedia.org/wiki/Post_Office_Protocol) client for Rust [![build badge](https://api.travis-ci.org/mattnenterprise/rust-pop3.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-pop3)
* QUIC
  *  <b><code>&nbsp;&nbsp;6445⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;450🍴</code></b> [cloudflare/quiche](https://github.com/cloudflare/quiche) — cloudflare implementation of the QUIC transport protocol and HTTP/3 ![build](https://img.shields.io/github/workflow/status/cloudflare/quiche/Stable)
  *  <b><code>&nbsp;&nbsp;1465⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [mozilla/neqo](https://github.com/mozilla/neqo) — an Implementation of QUIC written in Rust
  *  <b><code>&nbsp;&nbsp;2217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [quinn-rs/quinn](https://github.com/quinn-rs/quinn) — Futures-based QUIC implementation in Rust [![build badge](https://dev.azure.com/dochtman/Projects/_apis/build/status/Quinn?branchName=master)](https://dev.azure.com/dochtman/Projects/_build)
* RPC
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [ENQT-GmbH/remoc](https://github.com/ENQT-GmbH/remoc)  🌎 [remoc](crates.io/crates/remoc)] - Remoc provides channels (broadcast, mpsc, oneshot, watch) similar to Tokio's and trait calling over any remote transport. [![build badge](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [smallnest/rpcx-rs](https://github.com/smallnest/rpcx-rs) — A RPC library for Rust for developing microservices in easy and simple way. [![build badge](https://api.travis-ci.org/smallnest/rpcx-rs.svg?branch=master)](https://travis-ci.org/smallnest/rpcx-rs)
* Socket.io
  *  <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [1c3t3a/rust-socketio](https://github.com/1c3t3a/rust-socketio)  🌎 [rust_socketio](crates.io/crates/rust_socketio)] — an implementation of a 🌎 [socket.io](socket.io) client written in Rust. [![build badge](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml/badge.svg)](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml)
* SSH
  *  <b><code>&nbsp;&nbsp;&nbsp;329⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs) — 🌎 [libssh2](www.libssh2.org/) bindings [![build badge](https://api.travis-ci.com/alexcrichton/ssh2-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/ssh2-rs)
  * 🌎 [Thrussh](pijul.org/thrussh)  🌎 [thrussh](crates.io/crates/thrussh)] — an SSH library written from scratch in Rust, backed by 🌎 [libsodium](doc.libsodium.org/)
* Stomp
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs) — A [STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html) client implementation in Rust [![build badge](https://api.travis-ci.org/zslayton/stomp-rs.svg?branch=master)](https://travis-ci.org/zslayton/stomp-rs)
* ZeroMQ
  *  <b><code>&nbsp;&nbsp;&nbsp;670⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [erickt/rust-zmq](https://github.com/erickt/rust-zmq) — 🌎 [ZeroMQ](zeromq.org/) bindings [![build badge](https://api.travis-ci.org/erickt/rust-zmq.svg?branch=master)](https://travis-ci.org/erickt/rust-zmq)

### Parsing

  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Folyd/robotstxt](https://github.com/Folyd/robotstxt) - A native Rust port of Google's robots.txt parser and matcher C++ library
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [freestrings/jsonpath](https://github.com/freestrings/jsonpath) — 🌎 [JsonPath](goessner.net/articles/JsonPath/) engine written in Rust. Webassembly and Javascript support too [![Build Status](https://api.travis-ci.org/freestrings/jsonpath.svg?branch=master)](https://travis-ci.org/freestrings/jsonpath)
  *  <b><code>&nbsp;&nbsp;6770⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;684🍴</code></b> [Geal/nom](https://github.com/Geal/nom) — parser combinator library [![build badge](https://api.travis-ci.org/Geal/nom.svg?branch=master)](https://travis-ci.org/Geal/nom)
  *  <b><code>&nbsp;&nbsp;1107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) — Parsing Expression Grammar (PEG) parser generator
  *  <b><code>&nbsp;&nbsp;2173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;234🍴</code></b> [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop) — LR(1) parser generator for Rust [![Build status](https://api.travis-ci.org/lalrpop/lalrpop.svg?branch=master)](https://travis-ci.org/lalrpop/lalrpop)
  *  <b><code>&nbsp;&nbsp;&nbsp;225⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [m4rw3r/chomp](https://github.com/m4rw3r/chomp) – A fast monadic-style parser combinator [![build badge](https://api.travis-ci.org/m4rw3r/chomp.svg?branch=master)](https://travis-ci.org/m4rw3r/chomp)
  *  <b><code>&nbsp;&nbsp;1078⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [Marwes/combine](https://github.com/Marwes/combine) — parser combinator library [![build badge](https://api.travis-ci.org/Marwes/combine.svg?branch=master)](https://travis-ci.org/Marwes/combine)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [nrc/zero](https://github.com/nrc/zero)  🌎 [zero](crates.io/crates/zero/)] — zero-allocation parsing of binary data
  *  <b><code>&nbsp;&nbsp;3151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [pest-parser/pest](https://github.com/pest-parser/pest) — The Elegant Parser [![Build Status](https://api.travis-ci.org/pest-parser/pest.svg?branch=master)](https://travis-ci.org/pest-parser/pest)
  *  <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [ptal/oak](https://github.com/ptal/oak) — A typed PEG parser generator (compiler plugin)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [replicadse/wavefront_rs](https://github.com/replicadse/wavefront_rs) — A parser for the Wavefront OBJ format. [![crates.io](https://img.shields.io/crates/v/wavefront_rs.svg)](https://crates.io/crates/wavefront_rs) [![crates.io](https://img.shields.io/crates/d/wavefront_rs?label=crates.io%20downloads)](https://crates.io/crates/wavefront_rs) [![build badge](https://github.com/replicadse/wavefront_rs/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/wavefront_rs/actions)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [s-panferov/queryst](https://github.com/s-panferov/queryst) — A query string parsing library for Rust inspired by  <b><code>&nbsp;&nbsp;7196⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;701🍴</code></b> [gs](https://github.com/ljharb/qs#readme)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [softdevteam/grmtools](https://github.com/softdevteam/grmtools/) - A LR parser with better error correction

### Peripherals

* Serial Port
  * 🌎 [Susurrus/serialport-rs](gitlab.com/susurrus/serialport-rs)  🌎 [serialport](crates.io/crates/serialport)] — A cross-platform library that provides access to a serial port

### Platform specific

* Cross-platform
  * 🌎 [svartalf/rust-battery](crates.io/crates/battery) — Cross-platform information about the notebook batteries [![build badge](https://api.travis-ci.org/svartalf/rust-battery.svg?branch=master)](https://travis-ci.org/svartalf/rust-battery)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [vityafx/thread-priority](https://github.com/vityafx/thread-priority/) - Simple, crossplatform thread priority management. [![CI](https://github.com/vityafx/thread-priority/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/thread-priority/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/thread-priority.svg)](https://crates.io/crates/thread-priority)
* FreeBSD
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/)  🌎 [jail](crates.io/crates/jail)] — Rust implementation of a FreeBSD jail library
* Linux
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [arvancloud/nginx-rs](https://github.com/arvancloud/nginx-rs) — 🌎 [Nginx](www.nginx.com) bindings [![build badge](https://api.travis-ci.org/arvancloud/nginx-rs.svg?branch=master)](https://travis-ci.org/arvancloud/nginx-rs)
  *  <b><code>&nbsp;&nbsp;&nbsp;212⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [hannobraun/inotify-rs](https://github.com/hannobraun/inotify-rs) — 🌎 [inotify](en.wikipedia.org/wiki/Inotify) bindings [![Rust](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [pop-os/distinst](https://github.com/pop-os/distinst/) — Linux distribution installer
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [yaa110/rust-iptables](https://github.com/yaa110/rust-iptables)  🌎 [iptables](crates.io/crates/iptables)] — 🌎 [iptables](www.netfilter.org/projects/iptables/index.html) bindings [![build badge](https://api.travis-ci.org/yaa110/rust-iptables.svg?branch=master)](https://travis-ci.org/yaa110/rust-iptables)
* Unix-like
  *  <b><code>&nbsp;&nbsp;1848⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;487🍴</code></b> [nix-rust/nix](https://github.com/nix-rust/nix) — Unix-like API bindings [![Cirrus Build Status](https://api.cirrus-ci.com/github/nix-rust/nix.svg)](https://cirrus-ci.com/github/nix-rust/nix)
  *  <b><code>&nbsp;&nbsp;&nbsp;576⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [rustix](https://github.com/bytecodealliance/rustix) — Safe Rust bindings to POSIX/Unix/Linux/Winsock2 syscalls [![Actions Status](https://github.com/bytecodealliance/rustix/workflows/CI/badge.svg)](https://github.com/bytecodealliance/rustix/actions?query=workflow%3ACI)
  *  <b><code>&nbsp;&nbsp;&nbsp;866⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [zargony/fuse-rs](https://github.com/zargony/fuse-rs) —  <b><code>&nbsp;&nbsp;3961⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;921🍴</code></b> [FUSE](https://github.com/libfuse/libfuse) bindings
* Windows
  *  <b><code>&nbsp;&nbsp;1499⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;370🍴</code></b> [retep998/winapi-rs](https://github.com/retep998/winapi-rs) — Windows API bindings [![Rust](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml/badge.svg?branch=dev)](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml)

### Scripting

 🌎 [scripting](crates.io/keywords/scripting)]

* 🌎 [duckscript](crates.io/crates/duckscript) —  <b><code>&nbsp;&nbsp;&nbsp;312⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Simple, extendable and embeddable scripting language.](https://github.com/sagiegurari/duckscript) [![build badge](https://api.travis-ci.org/sagiegurari/duckscript.svg?branch=master)](https://travis-ci.org/sagiegurari/duckscript)
*  <b><code>&nbsp;&nbsp;&nbsp;334⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [fleabitdev/gamelisp](https://github.com/fleabitdev/glsp) — A LISP-lisk scripting language for Rust game development
*  <b><code>&nbsp;&nbsp;2603⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [gluon-lang/gluon](https://github.com/gluon-lang/gluon) —  A small, statically-typed, functional programming language
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [KusionStack/KCLVM](https://github.com/KusionStack/KCLVM) - A constraint-based record & functional language mainly used in configuration and policy scenarios.
*  <b><code>&nbsp;&nbsp;&nbsp;995⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [metacall/core](https://github.com/metacall/core)  🌎 [metacall](crates.io/crates/metacall)] — Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, Wasm, Java, Cobol and more. [![build badge](https://gitlab.com/metacall/core/badges/master/pipeline.svg)](https://gitlab.com/metacall/core)
*  <b><code>&nbsp;&nbsp;1322⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [mun](https://github.com/mun-lang/mun) — A compiled, statically-typed scripting language with first class hot reloading support [![build badge](https://api.travis-ci.org/mun-lang/mun.svg?branch=master)](https://travis-ci.org/mun-lang/mun)
*  <b><code>&nbsp;&nbsp;&nbsp;713⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [murarth/ketos](https://github.com/murarth/ketos) — A Lisp dialect functional programming language serving as a scripting and extension language for rust
*  <b><code>&nbsp;&nbsp;1473⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon) — A rusty dynamically typed scripting language
*  <b><code>&nbsp;&nbsp;1990⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [rhaiscript/rhai](https://github.com/rhaiscript/rhai) — A tiny and fast embedded scripting language resembling a combination of JavaScript and Rust [![build badge](https://github.com/rhaiscript/rhai/workflows/Build/badge.svg)](https://github.com/rhaiscript/rhai/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;998⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [rune-rs/rune](https://github.com/rune-rs/rune) — An embeddable dynamic programming language for Rust

### Simulation

 🌎 [simulation](crates.io/keywords/simulation)]

* 🌎 [nyx-space](crates.io/crates/nyx-space) - High fidelity, fast, reliable and validated astrodynamical toolkit library, used for spacecraft mission design and orbit determination [![Build Status](https://gitlab.com/nyx-space/nyx/badges/master/pipeline.svg)](https://gitlab.com/nyx-space/nyx/-/pipelines)

### Task scheduling

*  <b><code>&nbsp;&nbsp;&nbsp;241⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [delay-timer](https://github.com/BinChengZhao/delay-timer) — Time-manager of delayed tasks. Like crontab, but asynchronous tasks are possible.
[![Build](https://github.com/BinChengZhao/delay-timer/actions/workflows/rust.yml/badge.svg)](
https://github.com/BinChengZhao/delay-timer/actions)

### Template engine

* Handlebars
  *  <b><code>&nbsp;&nbsp;&nbsp;228⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [botika/yarte](https://github.com/botika/yarte) — Yarte stands for **Y**et **A**nother **R**ust **T**emplate **E**ngine, is the fastest template engine. [![Build Status](https://api.travis-ci.org/botika/yarte.svg?branch=master)](https://travis-ci.org/botika/yarte)
  *  <b><code>&nbsp;&nbsp;&nbsp;866⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust) — Handlebars template engine with inheritance, custom helper support. [![build badge](https://api.travis-ci.org/sunng87/handlebars-rust.svg?branch=master)](https://travis-ci.org/sunng87/handlebars-rust)
* HTML
  *  <b><code>&nbsp;&nbsp;1778⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [djc/askama](https://github.com/djc/askama) — template rendering engine based on Jinja [![build badge](https://api.travis-ci.org/djc/askama.svg?branch=master)](https://travis-ci.org/djc/askama)
  *  <b><code>&nbsp;&nbsp;&nbsp;282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [kaj/ructe](https://github.com/kaj/ructe) — HTML template system for Rust [![build badge](https://api.travis-ci.org/kaj/ructe.svg?branch=master)](https://travis-ci.org/kaj/ructe)
  *  <b><code>&nbsp;&nbsp;2157⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;200🍴</code></b> [Keats/tera](https://github.com/Keats/tera) — template engine based on Jinja2 and the Django template language. [![Actions Status](https://github.com/Keats/tera/workflows/ci/badge.svg?branch=master)](https://github.com/Keats/tera/actions)
  *  <b><code>&nbsp;&nbsp;1310⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [lambda-fairy/maud](https://github.com/lambda-fairy/maud) — compile-time HTML templates [![build badge](https://api.travis-ci.org/lambda-fairy/maud.svg?branch=master)](https://travis-ci.org/lambda-fairy/maud)
  *  <b><code>&nbsp;&nbsp;&nbsp;257⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Stebalien/horrorshow-rs](https://github.com/Stebalien/horrorshow-rs) — compile-time HTML templates [![build badge](https://api.travis-ci.org/Stebalien/horrorshow-rs.svg?branch=master)](https://travis-ci.org/Stebalien/horrorshow-rs)
* Mustache
  *  <b><code>&nbsp;&nbsp;&nbsp;208⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [rustache/rustache](https://github.com/rustache/rustache) — [![build badge](https://api.travis-ci.org/rustache/rustache.svg?branch=master)](https://travis-ci.org/rustache/rustache)

### Text processing

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [becheran/wildmatch](https://github.com/becheran/wildmatch)  🌎 [wildmatch](crates.io/crates/wildmatch)] — Simple string matching with questionmark- and star-wildcard operator [![Actions Status](https://github.com/becheran/wildmatch/workflows/Build/badge.svg?branch=master)](https://github.com/becheran/wildmatch/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;198⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [BurntSushi/suffix](https://github.com/BurntSushi/suffix) — Linear time suffix array construction (with Unicode support) [![build badge](https://api.travis-ci.org/BurntSushi/suffix.svg?branch=master)](https://travis-ci.org/BurntSushi/suffix)
*  <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter) — Elastic tab stops (i.e., text column alignment) [![build badge](https://api.travis-ci.org/BurntSushi/tabwriter.svg?branch=master)](https://travis-ci.org/BurntSushi/tabwriter)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [cpc](https://github.com/probablykasper/cpc) - Parses and calculates strings of math with support for units and unit conversion, from `1+2` to `1% of round(1 lightyear / 14!s to km/h)`.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Daniel-Liu-c0deb0t/triple_accel](https://github.com/Daniel-Liu-c0deb0t/triple_accel)  🌎 [triple_accel](crates.io/crates/triple_accel)] - Rust edit distance routines accelerated using SIMD; supports fast Hamming, Levenshtein, restricted Damerau-Levenshtein, etc. distance calculations and string search [![build badge](https://github.com/Daniel-Liu-c0deb0t/triple_accel/workflows/Test/badge.svg?branch=master)](https://github.com/Daniel-Liu-c0deb0t/triple_accel/actions)
*  <b><code>&nbsp;&nbsp;&nbsp;272⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [fancy-regex/fancy-regex](https://github.com/fancy-regex/fancy-regex)  🌎 [fancy-regex](crates.io/crates/fancy-regex)] - Regular expressions implementation designed to support a relatively rich set of features such as look-around and backtracking. [![crates](https://img.shields.io/crates/v/fancy-regex.svg)](https://crates.io/crates/fancy-regex) [![build badge](https://github.com/fancy-regex/fancy-regex/workflows/ci/badge.svg)](https://github.com/fancy-regex/fancy-regex/actions/workflows/ci.yml)
*  <b><code>&nbsp;&nbsp;&nbsp;755⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;105🍴</code></b> [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs) — Natural language detection library based on trigrams [![build badge](https://api.travis-ci.org/greyblake/whatlang-rs.svg?branch=master)](https://travis-ci.org/greyblake/whatlang-rs)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Lucretiel/joinery](https://github.com/Lucretiel/joinery)  🌎 [joinery](crates.io/crates/joinery)] – Generic string + iterable joining [![build badge](https://api.travis-ci.org/Lucretiel/joinery.svg?branch=master)](https://travis-ci.org/Lucretiel/joinery)
*  <b><code>&nbsp;&nbsp;&nbsp;272⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [mgeisler/textwrap](https://github.com/mgeisler/textwrap)  🌎 [textwrap](crates.io/crates/textwrap)] — Word wrap text (with support for hyphenation) [![build badge](https://api.travis-ci.org/mgeisler/textwrap.svg?branch=master)](https://travis-ci.org/mgeisler/textwrap)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [ps1dr3x/easy_reader](https://github.com/ps1dr3x/easy_reader) — A reader that allows forwards, backwards and random navigations through the lines of huge files without consuming iterators [![build badge](https://api.travis-ci.org/ps1dr3x/easy_reader.svg?branch=master)](https://travis-ci.org/ps1dr3x/easy_reader)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [pwoolcoc/ngrams](https://github.com/pwoolcoc/ngrams)  🌎 [ngrams](crates.io/crates/ngrams)] — Construct 🌎 [n-grams](en.wikipedia.org/wiki/N-gram) from arbitrary iterators [![build badge](https://api.travis-ci.org/pwoolcoc/ngrams.svg?branch=master)](https://travis-ci.org/pwoolcoc/ngrams)
*  <b><code>&nbsp;&nbsp;2376⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;336🍴</code></b> [rust-lang/regex](https://github.com/rust-lang/regex) — Regular expressions (RE2 style) [![build badge](https://api.travis-ci.com/rust-lang/regex.svg?branch=master)](https://travis-ci.org/rust-lang/regex)
* 🌎 [strsim-rs](crates.io/crates/strsim) — String similarity metrics [![build badge](https://api.travis-ci.org/dguo/strsim-rs.svg?branch=master)](https://travis-ci.org/dguo/strsim-rs)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [yaa110/rake-rs](https://github.com/yaa110/rake-rs)  🌎 [rake](crates.io/crates/rake)] — Multilingual implementation of RAKE algorithm for Rust [![build badge](https://api.travis-ci.org/yaa110/rake-rs.svg?branch=master)](https://travis-ci.org/yaa110/rake-rs)

### Text search

*  <b><code>&nbsp;&nbsp;&nbsp;108⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [andylokandy/simsearch-rs](https://github.com/andylokandy/simsearch-rs)  🌎 [simsearch](crates.io/crates/simsearch)] — A simple and lightweight fuzzy search engine that works in memory, searching for similar strings
*  <b><code>&nbsp;&nbsp;1416⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [BurntSushi/fst](https://github.com/BurntSushi/fst)  🌎 [fst](crates.io/crates/fst)] — [![build badge](https://api.travis-ci.org/BurntSushi/fst.svg?branch=master)](https://travis-ci.org/BurntSushi/fst)
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [CurrySoftware/perlin](https://github.com/CurrySoftware/perlin)  🌎 [perlin](crates.io/crates/perlin)]
*  <b><code>&nbsp;28226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;986🍴</code></b> [meilisearch/MeiliSearch](https://github.com/meilisearch/MeiliSearch) — Ultra relevant, instant and typo-tolerant full-text search API. [![Build Status](https://github.com/meilisearch/MeiliSearch/workflows/Cargo%20test/badge.svg?branch=master)](https://github.com/meilisearch/MeiliSearch/actions)
*  <b><code>&nbsp;&nbsp;6764⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;405🍴</code></b> [tantivy](https://github.com/quickwit-oss/tantivy)  🌎 [tantivy](crates.io/crates/tantivy)] — A horse-speed full-text search engine library written in Rust. [![Build Status](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml/badge.svg)](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml)

### Unsafe

* 🌎 [zerocopy](crates.io/crates/zerocopy) — Utilities for safely reinterpreting arbitrary byte sequences as native Rust types

### Virtualization

*  <b><code>&nbsp;&nbsp;&nbsp;203⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [beneills/quantum](https://github.com/beneills/quantum) — Advanced Rust quantum computer simulator [![build badge](https://api.travis-ci.org/beneills/quantum.svg?branch=master)](https://travis-ci.org/beneills/quantum)
*  <b><code>&nbsp;&nbsp;8041⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;740🍴</code></b> [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime) — A standalone runtime for WebAssembly [![Build Status](https://github.com/bytecodealliance/wasmtime/workflows/CI/badge.svg)](https://github.com/bytecodealliance/wasmtime/actions?query=workflow%3ACI)
* 🌎 [chromium/chromiumos/platform/crosvm](chromium.googlesource.com/chromiumos/platform/crosvm/) CrOSVM — Enables Chrome OS to run Linux apps inside a fast, secure virtualized environment
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [saurvs/hypervisor-rs](https://github.com/saurvs/hypervisor-rs) — Hardware-accelerated virtualization on OS X
*  <b><code>&nbsp;&nbsp;&nbsp;128⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [unicorn-rs/unicorn-rs](https://github.com/unicorn-rs/unicorn-rs) — Rust bindings for the unicorn CPU emulator [![Build Status](https://api.travis-ci.org/ekse/unicorn-rs.svg?branch=master)](https://travis-ci.org/ekse/unicorn-rs)

### Web programming

See also 🌎 [Are we web yet?](www.arewewebyet.org) and  <b><code>&nbsp;&nbsp;3192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [Rust web framework comparison](https://github.com/flosse/rust-web-framework-comparison).

* Client-side / WASM
  * 🌎 [cargo-web](crates.io/crates/cargo-web) — A Cargo subcommand for the client-side Web [![Build Status](https://api.travis-ci.org/koute/cargo-web.svg?branch=master)](https://travis-ci.org/koute/cargo-web)
  *  <b><code>&nbsp;&nbsp;1666⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [sauron](https://github.com/ivanceras/sauron) - Client side web framework which closely adheres to The Elm Architecture. [![Build Status](https://api.travis-ci.org/ivanceras/sauron.svg?branch=master)](https://travis-ci.org/ivanceras/sauron)
  * 🌎 [seed](seed-rs.org/) — A Rust framework for creating web apps
  * 🌎 [stdweb](crates.io/crates/stdweb) — A standard library for the client-side Web [![Build Status](https://api.travis-ci.org/koute/stdweb.svg?branch=master)](https://travis-ci.org/koute/stdweb)
  * 🌎 [yew](crates.io/crates/yew) — Rust framework for making client web apps
* HTTP Client
  *  <b><code>&nbsp;&nbsp;&nbsp;849⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;200🍴</code></b> [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust) — 🌎 [libcurl](curl.se/libcurl/) bindings [![build badge](https://api.travis-ci.com/alexcrichton/curl-rust.svg?branch=master)](https://travis-ci.org/alexcrichton/curl-rust)
  *  <b><code>&nbsp;&nbsp;2348⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;296🍴</code></b> [async-graphql](https://github.com/async-graphql/async-graphql) - A GraphQL server library implemented in Rust [![Build Status](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_apis/build/status/graphql-rust.juniper)](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_build/latest?definitionId=1)
  * 🌎 [DoumanAsh/yukikaze](gitlab.com/Douman/yukikaze)  🌎 [yukikaze](crates.io/crates/yukikaze)] — Beautiful and elegant Yukikaze is little HTTP client library based on hyper. [![build badge](https://gitlab.com/Douman/yukikaze/badges/master/pipeline.svg)](https://gitlab.com/Douman/yukikaze)
  *  <b><code>&nbsp;&nbsp;&nbsp;847⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [graphql-client](https://github.com/graphql-rust/graphql-client) — Typed, correct GraphQL requests and responses in Rust. [![Github actions Status](https://github.com/graphql-rust/graphql-client/workflows/CI/badge.svg?branch=master)](https://github.com/graphql-rust/graphql-client/actions)
  *  <b><code>&nbsp;&nbsp;9984⭐</code></b> <b><code>&nbsp;&nbsp;1201🍴</code></b> [hyperium/hyper](https://github.com/hyperium/hyper) — an HTTP implementation [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  *  <b><code>&nbsp;&nbsp;5905⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;680🍴</code></b> [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest) — an ergonomic HTTP Client for Rust. [![build badge](https://api.travis-ci.org/seanmonstar/reqwest.svg?branch=master)](https://travis-ci.org/seanmonstar/reqwest)
* HTTP Server
  *  <b><code>&nbsp;14709⭐</code></b> <b><code>&nbsp;&nbsp;1408🍴</code></b> [actix/actix-web](https://github.com/actix/actix-web) — A lightweight async web framework for Rust with websocket support [![build badge](https://api.travis-ci.org/actix/actix-web.svg?branch=master)](https://travis-ci.org/actix/actix-web)
  * 🌎 [branca](crates.io/crates/branca) — A Pure Rust implementation of Branca for Authenticated and Encrypted API tokens. [![build badge](https://api.travis-ci.org/return/branca.svg?branch=master)](https://travis-ci.org/return/branca)
  *  <b><code>&nbsp;&nbsp;&nbsp;967⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [carllerche/tower-web](https://github.com/carllerche/tower-web)  🌎 [tower-web](crates.io/crates/tower-web)] — A fast, boilerplate free, web framework for Rust [![build badge](https://api.travis-ci.org/carllerche/tower-web.svg?branch=master)](https://travis-ci.org/carllerche/tower-web)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [danclive/sincere](https://github.com/danclive/sincere) — A micro web framework for Rust(stable) based on hyper and multithreading. [![build badge](https://api.travis-ci.org/danclive/sincere.svg?branch=master)](https://travis-ci.org/danclive/sincere)
  *  <b><code>&nbsp;&nbsp;&nbsp;239⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [GildedHonour/frank_jwt](https://github.com/GildedHonour/frank_jwt) — JSON Web Token implementation in Rust. [![build badge](https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master)](https://travis-ci.org/GildedHonour/frank_jwt)
  *  <b><code>&nbsp;&nbsp;2007⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [Gotham](https://github.com/gotham-rs/gotham) — A flexible web framework that does not sacrifice safety, security or speed. [![build badge](https://api.travis-ci.org/gotham-rs/gotham.svg?branch=master)](https://travis-ci.org/gotham-rs/gotham)
  *  <b><code>&nbsp;&nbsp;&nbsp;866⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [handlebars-rust](https://github.com/sunng87/handlebars-rust) — an Iron web framework middleware. [![build badge](https://api.travis-ci.org/sunng87/handlebars-iron.svg?branch=master)](https://travis-ci.org/sunng87/handlebars-iron)
  *  <b><code>&nbsp;&nbsp;9984⭐</code></b> <b><code>&nbsp;&nbsp;1201🍴</code></b> [hyperium/hyper](https://github.com/hyperium/hyper) — an HTTP implementation [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  *  <b><code>&nbsp;&nbsp;6055⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;411🍴</code></b> [Iron](https://github.com/iron/iron) — A middleware-based server framework [![build badge](https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master)](https://travis-ci.org/GildedHonour/frank_jwt)
  *  <b><code>&nbsp;&nbsp;4635⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;384🍴</code></b> [Juniper](https://github.com/graphql-rust/juniper) — GraphQL server library for Rust [![build badge](https://api.travis-ci.org/graphql-rust/juniper.svg?branch=master)](https://travis-ci.org/graphql-rust/juniper)
  *  <b><code>&nbsp;&nbsp;&nbsp;621⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [miketang84/sapper](https://github.com/miketang84/sapper) — A lightweight web framework built on async hyper, implemented in Rust language.
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Nickel](https://github.com/nickel-org/nickel.rs/) — inspired by [Express](http://expressjs.com/) [![build badge](https://api.travis-ci.org/nickel-org/nickel.rs.svg?branch=master)](https://travis-ci.org/nickel-org/nickel.rs)
  *  <b><code>&nbsp;&nbsp;&nbsp;872⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Ogeon/rustful](https://github.com/Ogeon/rustful) — A RESTful web framework for Rust  [![build badge](https://api.travis-ci.org/Ogeon/rustful.svg?branch=master)](https://travis-ci.org/Ogeon/rustful)
  *  <b><code>&nbsp;17979⭐</code></b> <b><code>&nbsp;&nbsp;1273🍴</code></b> [Rocket](https://github.com/SergioBenitez/Rocket) — Rocket is web framework for Rust (nightly) with a focus on ease-of-use, expressability, and speed [![build badge](https://api.travis-ci.org/SergioBenitez/Rocket.svg?branch=master)](https://travis-ci.org/SergioBenitez/Rocket)
  *  <b><code>&nbsp;&nbsp;&nbsp;607⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [Rustless](https://github.com/rustless/rustless) — A REST-like API micro-framework inspired by  <b><code>&nbsp;&nbsp;9569⭐</code></b> <b><code>&nbsp;&nbsp;1217🍴</code></b> [Grape](https://github.com/ruby-grape/grape) and  <b><code>&nbsp;&nbsp;9984⭐</code></b> <b><code>&nbsp;&nbsp;1201🍴</code></b> [Hyper](https://github.com/hyperium/hyper) [![build badge](https://api.travis-ci.org/rustless/rustless.svg?branch=master)](https://travis-ci.org/rustless/rustless)
  *  <b><code>&nbsp;&nbsp;&nbsp;662⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Salvo](https://github.com/salvo-rs/salvo) — an easy to use webframework base on hyper and tokio. [![build build](https://github.com/salvo-rs/salvo/workflows/CI%20(Linux)/badge.svg?branch=master&event=push)](https://github.com/salvo-rs/salvo/actions)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Saphir](https://github.com/richerarc/saphir) — A progressive web framework with low-level control, without the pain.
  *  <b><code>&nbsp;&nbsp;6782⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;602🍴</code></b> [seanmonstar/warp](https://github.com/seanmonstar/warp) — A super-easy, composable, web server framework for warp speeds. [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/warp)
  *  <b><code>&nbsp;&nbsp;&nbsp;747⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [tiny-http](https://github.com/tiny-http/tiny-http) — Low level HTTP server library [![build badge](https://api.travis-ci.org/tiny-http/tiny-http.svg?branch=master)](https://travis-ci.org/tiny-http/tiny-http)
  *  <b><code>&nbsp;&nbsp;5519⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;406🍴</code></b> [tokio/axum](https://github.com/tokio-rs/axum) - Ergonomic and modular web framework built with Tokio, Tower, and Hyper [![Build badge](https://github.com/tokio-rs/axum/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/tokio-rs/axum/actions/workflows/CI.yml)
  *  <b><code>&nbsp;&nbsp;&nbsp;806⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [tomaka/rouille](https://github.com/tomaka/rouille) — Web framework in Rust [![build badge](https://api.travis-ci.org/tomaka/rouille.svg?branch=master)](https://travis-ci.org/tomaka/rouille)
* Miscellaneous
  *  <b><code>&nbsp;&nbsp;&nbsp;178⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [cargonauts](https://github.com/cargonauts-rs/cargonauts) — A web framework intended for building maintainable, well-factored web apps.
  *  <b><code>&nbsp;&nbsp;&nbsp;980⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [causal-agent/scraper](https://github.com/causal-agent/scraper)  🌎 [scraper](crates.io/crates/scraper)] - HTML parsing and querying with CSS selectors. [![Build Status](https://github.com/causal-agent/scraper/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/causal-agent/scraper/actions)
  *  <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [homelyguy/dyer](https://github.com/HomelyGuy/dyer)  🌎 [dyer](crates.io/crates/dyer)] - dyer is designed for reliable, flexible and fast Request-Response based service, including data processing, web-crawling and so on, providing some friendly, flexible, comprehensive features without compromising speed.
  *  <b><code>&nbsp;&nbsp;2624⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [osohq/oso](https://github.com/osohq/oso)  🌎 [oso](crates.io/crates/oso)] - A policy engine for authorization that's embedded in your application. [![Build Status](https://github.com/osohq/oso/workflows/Development/badge.svg?branch=main)](https://github.com/osohq/oso/actions?query=branch%3Amain+workflow%3ADevelopment)
  * 🌎 [pwoolcoc/soup](gitlab.com/pwoolcoc/soup)  🌎 [soup](crates.io/crates/soup)] — A library similar to Python's BeautifulSoup, designed to enable quick and easy manipulation and querying of HTML documents. [![Build Status](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
  *  <b><code>&nbsp;&nbsp;&nbsp;878⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [pyrossh/rust-embed](https://github.com/pyrossh/rust-embed) — A macro to embed static assets into the rust binary
  *  <b><code>&nbsp;&nbsp;2722⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;412🍴</code></b> [serenity-rs/serenity](https://github.com/serenity-rs/serenity)  🌎 [serenity](crates.io/crates/serenity)] - A Rust library for the Discord API
  *  <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [softprops/openapi](https://github.com/softprops/openapi) — A library for processing openapi spec files
  * 🌎 [tbot](gitlab.com/SnejUgal/tbot)  🌎 [tbot](crates.io/crates/tbot)] - Make cool Telegram bots with Rust easily [![pipeline status](https://gitlab.com/SnejUgal/tbot/badges/master/pipeline.svg)](https://gitlab.com/SnejUgal/tbot/-/commits/master)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [teloxide/teloxide](https://github.com/teloxide/teloxide/) - An elegant Telegram bots framework for Rust [![Build Status](https://github.com/teloxide/teloxide/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/teloxide/teloxide/actions)
  *  <b><code>&nbsp;&nbsp;&nbsp;801⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs)  🌎 [select](crates.io/crates/select)] — A library to extract useful data from HTML documents, suitable for web scraping. [![Build Status](https://api.travis-ci.org/utkarshkukreti/select.rs.svg?branch=master)](https://travis-ci.org/utkarshkukreti/select.rs)
* Reverse Proxy
  *  <b><code>&nbsp;&nbsp;1776⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;131🍴</code></b> [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu)  🌎 [sozu](crates.io/crates/sozu)] — A HTTP reverse proxy. [![CI](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml)
* Static Site Generators
  *  <b><code>&nbsp;&nbsp;1112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs) — Static site generator written in Rust [![Build Status](https://dev.azure.com/cobalt-org/cobalt-org/_apis/build/status/cobalt.rs?branchName=master)](https://dev.azure.com/cobalt-org/cobalt-org/_build?definitionId=2)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs)  🌎 [mdblog](crates.io/crates/mdblog)] — Static site generator from markdown files.
  *  <b><code>&nbsp;&nbsp;9071⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;660🍴</code></b> [getzola/zola](https://github.com/getzola/zola)  🌎 [zola](www.getzola.org/)] — An opinionated static site generator with everything built-in. [![Build Status](https://dev.azure.com/getzola/zola/_apis/build/status/getzola.zola?branchName=master)](https://dev.azure.com/getzola/zola/_build)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [leven-the-blog/leven](https://github.com/leven-the-blog/leven)  🌎 [leven](crates.io/crates/leven)] — A simple, parallelized blog generator. [![build badge](https://api.travis-ci.org/quadrupleslap/leven.svg?branch=master)](https://travis-ci.org/quadrupleslap/leven)
* 🌎 [WebSocket](datatracker.ietf.org/doc/rfc6455/)
  *  <b><code>&nbsp;&nbsp;1300⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;207🍴</code></b> [housleyjk/ws-rs](https://github.com/housleyjk/ws-rs) — lightweight, event-driven WebSockets for Rust [![build badge](https://api.travis-ci.org/housleyjk/ws-rs.svg?branch=stable)](https://travis-ci.org/housleyjk/ws-rs)
  *  <b><code>&nbsp;&nbsp;1194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;204🍴</code></b> [rust-websocket](https://github.com/websockets-rs/rust-websocket) — A framework for dealing with WebSocket connections (both clients and servers) [![build badge](https://api.travis-ci.org/websockets-rs/rust-websocket.svg?branch=master)](https://travis-ci.org/websockets-rs/rust-websocket)
  *  <b><code>&nbsp;&nbsp;1086⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs) — Lightweight stream-based WebSocket implementation for Rust.
  *  <b><code>&nbsp;&nbsp;4222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [vi/websocat](https://github.com/vi/websocat) — CLI for interacting with WebSockets, with functionality of Netcat, Curl and Socat. [![build badge](https://api.travis-ci.org/vi/websocat.svg?branch=master)](https://travis-ci.org/vi/websocat)
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [vityafx/urlshortener-rs](https://github.com/vityafx/urlshortener-rs) — A very simple urlshortener library for Rust. [![CI](https://github.com/vityafx/urlshortener-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/vityafx/urlshortener-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/urlshortener.svg)](https://crates.io/crates/urlshortener)

## Registries

A registry allows you to publish your Rust libraries as crate packages, to share them with others publicly and privately.

* 🌎 [Cloudsmith :heavy_dollar_sign:](cloudsmith.com/cargo-registry/) — A fully managed package management SaaS, with first-class support for public and private Cargo/Rust registries (plus many others). Has a generous free-tier and is also completely free for open-source.
* 🌎 [Crates](crates.io) — The official public registry for Rust/Cargo.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [w4/chartered](https://github.com/w4/chartered) - A private, authenticated, permissioned Cargo registry [![CI](https://github.com/w4/chartered/actions/workflows/ci.yml/badge.svg)](https://github.com/w4/chartered/actions/workflows/ci.yml)

## Resources

* Benchmarks
  *  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [TeXitoi/benchmarksgame-rs](https://github.com/TeXitoi/benchmarksgame-rs) — Rust implementations for the 🌎 [The Computer Language Benchmarks Game](benchmarksgame-team.pages.debian.net/benchmarksgame/) [![build badge](https://api.travis-ci.org/TeXitoi/benchmarksgame-rs.svg?branch=master)](https://travis-ci.org/TeXitoi/benchmarksgame-rs)
* Decks & Presentations
  * 🌎 [Learning systems programming with Rust](speakerdeck.com/jvns/learning-systems-programming-with-rust) — Presented by 🌎 [Julia Evans](twitter.com/@b0rk) @ Rustconf 2016.
  * 🌎 [Rust: Hack Without Fear!](www.youtube.com/watch?v=lO1z-7cuRYI) — Presented by  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Nicholas Matsakis](https://github.com/nikomatsakis) @ C++Now 2018
  * 🌎 [Shipping a Solid Rust Crate](www.youtube.com/watch?v=t4CyEKb-ywA) — Presented by  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Michael Gattozzi](https://github.com/mgattozzi) @ RustConf 2017
* Learning
  *  <b><code>&nbsp;&nbsp;&nbsp;554⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Awesome Rust Streaming](https://github.com/jamesmunns/awesome-rust-streaming) - A community curated list of livestreams about Rust.
  * 🌎 [awesome-rust-mentors](rustbeginners.github.io/awesome-rust-mentors/) — A list of helpful Rust mentors willing to take mentees and eductate them about Rust and programming.
  * 🌎 [Build a language VM](blog.subnetzero.io/post/building-language-vm-part-00/)
  * 🌎 [CodeCrafters.io](app.codecrafters.io/tracks/rust) — Build your own Redis, Git, Docker, or SQLite in Rust
  *  <b><code>&nbsp;&nbsp;6738⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;301🍴</code></b> [Easy Rust](https://github.com/Dhghomon/easy_rust) - Learn Rust in easy English.
  * 🌎 [exercism.org](exercism.org/tracks/rust) — programming exercises that help you learn new concepts in Rust.
  * 🌎 [Hands-on Rust](pragprog.com/titles/hwrust/hands-on-rust/) - A hands-on guide to learning Rust by making games - by  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Herbert Wolverson](https://github.com/thebracket/) (paid)
  *  <b><code>&nbsp;&nbsp;3743⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [Idiomatic Rust](https://github.com/mre/idiomatic-rust) —  A peer-reviewed collection of articles/talks/repos which teach idiomatic Rust.
  * 🌎 [Learning Rust With Entirely Too Many Linked Lists](rust-unofficial.github.io/too-many-lists/) — in-depth exploration of Rust's memory management rules, through implementing a few different types of list structures.
  * 🌎 [Little Book of Rust Books](lborb.github.io/book/) - Curated list of rust books and how-tos.
  * 🌎 [Programming Community Curated Resources for Learning Rust](hackr.io/tutorials/learn-rust) — A list of recommended resources voted by the programming community.
  * 🌎 [Refactoring to Rust](www.manning.com/books/refactoring-to-rust) - A book that introduces to Rust language.
  * 🌎 [Rust by Example](doc.rust-lang.org/rust-by-example/)
  * 🌎 [Rust Cookbook](rust-lang-nursery.github.io/rust-cookbook/) — A collection of simple examples that demonstrate good practices to accomplish common programming tasks, using the crates of the Rust ecosystem.
  * 🌎 [Rust for professionals](overexact.com/rust-for-professionals/) — A quick introduction to Rust for experienced software developers.
  *  <b><code>&nbsp;&nbsp;&nbsp;433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [Rust Gym](https://github.com/warycat/rustgym) - A big collection of coding interview problems solved in Rust.
  * 🌎 [Rust in Action](www.manning.com/books/rust-in-action) — A hands-on guide to systems programming with Rust by  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Tim McNamara](https://github.com/timClicks) (paid)
  * 🌎 [Rust in Motion](www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) — A video series by  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Carol Nichols](https://github.com/carols10cents) and  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Jake Goulding](https://github.com/shepmaster) (paid)
  * 🌎 [Rust Language Cheat Sheet](cheats.rs/)
  * 🌎 [Rust Online Courses at Classpert](classpert.com/search/rust) — A list of Rust online courses (paid) from Classpert Online Course Search
  * 🌎 [Rust Tiếng Việt](rust-tieng-viet.github.io/) - Learn Rust in Vietnamese.
  *  <b><code>&nbsp;&nbsp;&nbsp;527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [rust-how-do-i-start](https://github.com/jondot/rust-how-do-i-start) - A repo dedicated to answering the question: "So, Rust. How do I _start_?". A beginner only hand-picked resources and learning track.
  *  <b><code>&nbsp;&nbsp;8317⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;564🍴</code></b> [rust-learning](https://github.com/ctjhoa/rust-learning) — A collection of useful resources to learn Rust
  *  <b><code>&nbsp;27854⭐</code></b> <b><code>&nbsp;&nbsp;4385🍴</code></b> [Rustlings](https://github.com/rust-lang/rustlings) — small exercises to get you used to reading and writing Rust code
  *  <b><code>&nbsp;&nbsp;&nbsp;517⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Rusty CS](https://github.com/AbdesamedBendjeddou/Rusty-CS) - A Computer Science Curriculum that helps practice the acquired academic knowledge in Rust
  *  <b><code>&nbsp;&nbsp;1816⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [stdx](https://github.com/brson/stdx) — Learn these crates first as an extension to std
  * 🌎 [Take your first steps with Rust](docs.microsoft.com/en-us/learn/paths/rust-first-steps/) - Lay the foundation of knowledge you need to build fast and effective programs in Rust.
  * [University of Pennsylvania's Comp Sci Rust Programming Course](http://cis198-2016s.github.io/schedule/)
* Podcasts
  * 🌎 [New Rustacean](newrustacean.com) — A podcast about learning Rust
  * 🌎 [Rustacean Station](rustacean-station.org/) — A community project for creating podcast content for Rust
*  <b><code>&nbsp;&nbsp;6037⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;271🍴</code></b> [Rust Design Patterns](https://github.com/rust-unofficial/patterns)
* [Rust Guidelines](http://aturon.github.io/)
* 🌎 [Rust Servers, Services and Apps - MEAP](www.manning.com/books/rust-servers-services-and-apps) - Build backend servers, services, and front-ends in Rust to get fast, reliable, and maintainable applications.
* 🌎 [Rust Subreddit](www.reddit.com/r/rust/) — A subreddit(forum) where rust related questions, articles and resources are posted and discussed
*  <b><code>&nbsp;&nbsp;1899⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [RustBooks](https://github.com/sger/RustBooks) — list of RustBooks
* 🌎 [RustCamp 2015 Talks](www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t)
*  <b><code>&nbsp;&nbsp;2077⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [RustViz](https://github.com/rustviz/rustviz) — generates visualizations from simple Rust programs to assist users in better understanding the Rust Lifetime and Borrowing mechanism.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

## Source
 <b><code>&nbsp;27409⭐</code></b> <b><code>&nbsp;&nbsp;1852🍴</code></b> [rust-unofficial/awesome-rust](https://github.com/rust-unofficial/awesome-rust)