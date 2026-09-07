## About
I am a software developer focused on systems and product engineering across C++, Rust, Go, Python, C#, and JavaScript.
I co-founded Brave in 2015 with Brendan Eich and currently serve as CTO and board member.
Before Brave, I worked at Khan Academy, Mozilla, Evernote, and more.
I graduated with a bachelor's degree in Computer Science Honors from the University of Waterloo.

Outside work, I spend time with family and run long distances.

## Projects

**Brave**
- **[Browser](https://github.com/brave/brave-core)** — blocks ads and trackers, saves data, and speeds up web browsing on macOS, Windows, and Linux
- **[Wallet](https://github.com/brave/brave-core)** — secure, native, built-in crypto wallet that supercharges Brave for Web3
- **[Leo](https://github.com/brave/brave-core)** — AI assistant built into the browser for question answering and summarization, all while maintaining privacy
- **[Origin](https://github.com/brave/brave-core)** — a streamlined Brave that keeps best-in-class privacy while letting you manage or remove the features you do not want
- **[Ad Block Engine](https://github.com/brave/adblock-rust)** — Adblock Plus filter parsing and matching for lists like EasyList, significantly faster than other implementations
- **[go-update](https://github.com/brave/go-update)** — Chromium-compatible component update server in Go, built by sniffing Chromium's extension update API
- **[IPFS in Brave](https://github.com/brave/brave-core)** — deep IPFS integration so content loads by hash (CID) through a local node or public gateway
- **[Link Bubble](https://github.com/brave/link-bubble)** — Android browser that loads links in the background and floats them in a bubble, so you never leave the app you are in

**Agents and developer tooling**
- **[Brave Bot](https://github.com/brave-experiments/brave-bot)** — general-purpose coding agent with structural resistance to indirect prompt injection
- **[Brave Dev Bot](https://github.com/brave-experiments/brave-dev-bot)** — Ralph Wiggum loop-inspired agent that implements PRDs, runs tests, creates PRs, and manages CI
- **[Guardrails](https://github.com/bbondy/guardrails)** — native Rust CLI wrapper that blocks unsafe or prompt-injection style output from other CLIs, with blocking and sanitizing modes
- **[Hutter Prize Workspace](https://github.com/bbondy/hutter)** — Rust workspace for experimenting toward a future Hutter Prize submission

**Mozilla and Khan Academy**
- **[Gecko / Firefox](https://github.com/mozilla/gecko-dev)** — mostly Windows C++ work since 2011: Metro Firefox, the installer, silent updates, and hundreds of fixes
- **[Khan Academy for Firefox OS](https://github.com/bbondy/khan-academy-fxos)** — lead and primary developer of the app for Khan Academy's 6,000+ videos and articles
- **[Khan Academy for Windows 8](https://github.com/Khan/khan-windows)** — significant contributor to the Modern UI Windows Store app
- **[Code Firefox](https://github.com/bbondy/codefirefox)** — short, consumable videos outlining how to become a Mozilla contributor, from start to finish

**Personal projects**
- **[Macro Lap](https://github.com/bbondy/macro-lap)** — double-tap the lap button to track a macro lap while single taps still record normal splits, built for backyard ultras
- **[brianbondy.com](https://github.com/bbondy/go-brianbondy)** — my site, currently written in Go, after versions in Node, App Engine, Django, ASP.NET, and Flash
- **[Babel JSM module formatter](https://github.com/bbondy/babel-jsm-plugin)** — Babel plugin that converts ES6 modules into Firefox JavaScript code modules (JSM)
- **[codecheckjs](https://github.com/bbondy/codecheckjs)** — grades JavaScript structure by matching a template against an abstract syntax tree
- **[simple-ec2](https://github.com/bbondy/simple-ec2)** — small AWS SDK wrapper for starting, stopping, listing, and running commands on EC2 instances
- **[Image Flow](https://github.com/bbondy/image-flow)** — image manipulation library covering many formats, with layers and blend modes
- **[Stego Flow](https://github.com/bbondy/stego-flow)** — library and utilities to encode data into an image and decode it later

<details>
<summary><b>Earlier work</b> — products, contract work, and libraries from before 2011</summary>

**Products** (acquired in 2011)
- **ROBOBAK** — enterprise Windows backup in C++ for remote office branch office backup, with deduplication, agentless backup, and replication
- **Vision Backup** — micro business backup of any drive, network computer, or FTP site to disk, FTP, optical media, or tape, with SQL Server and Exchange plugins
- **Cryptex** — encrypted vault that mounts as a drive, grows with your files, and disappears from view when locked
- **Null FTP** — FTP, FTPS, SFTP, HTTP, and WebDAV client and server software; I still use it as my primary FTP client

**Contract work**
- **GlobalDrive** — Windows drive backed by WebDAV, both the C++ client and the C# ASP.NET web side
- **Microsentry** — certified email service built on a Windows TDI filter, certifying sender identity on both ends
- **Auction Tool for eBay** — visible auction counters and tracking through the eBay API, like Google Analytics for listings
- **BidGuru for eBay** — sniping tool that bids on an item just before it expires

**Libraries and systems**
- **Internet Library** — large C++ library supporting FTP/FTPS/SFTP, SMTP, POP3, HTTP(S), TCP/UDP, servers, proxies, and HTML parsing; the basis of several large applications
- **TDI Network Filters** — low level SMTP and POP3 filters that can modify, block, or add to network traffic
- **Virtual disk drive implementation** — a drive Windows can talk to whose data does not actually exist
- **Windows Networking (LAN)** — file search, connections, and administrative share access, treating FTP servers as LAN computers
- **Scheduling Library** — access and control over Windows schedules, used in several large applications
- **Pyroflow Archiving** — cross-platform pack and unpack into a single archive, more efficient than tar; the core of Vision Backup Enterprise
- **Adaptive Huffman Compression** — compression utilities using adaptive Huffman coding, grown well past the original school project
- **Call .NET web services without .NET** — SOAP wrappers for calling .NET web services from any C++ application
- **Counter HTTP server** — serves generated count images over HTTP
- **Computer Vision** — basic computer vision and AI utilities built on Video4Linux and Video4Windows
- **Misc data structures and algorithms** — a collection I built for my own use

**Pyroflow and open source**
- **NullShare** — open source C++ file sharing application, shelved over the legal climate of the time
- **NullShare Convert** — GUI and preview front end over ffmpeg for converting video formats
- **Pyroflow MSN** — MSN Messenger client written from scratch in C++ and Qt3, portable across Linux, Unix, Mac, Windows, and BSD
- **Pyroflow Briefcase** — synchronizes files between two mounted directories on Linux and Unix
- **Pyroflow web site** — the full .NET, XML/XSLT driven site plus a remote updater app
- **True 3D Tetris** — Tetris across the x, y, and z axes with customizable blocks, board size, and particle explosions
- **Qt Extensions** — several reusable Qt widgets
- **Firefox Extensions** — extensions such as user habit tracking

**University**
- **Graphical Pipeline** — modeling, viewing, and perspective transforms with clipping and a resizable viewport, in Python and C++
- **Router Emulator** — OSPF-style router emulation with Dijkstra's algorithm over UDP in C++
- **Reliable transfer protocol** — Go-Back-N reliable delivery on top of UDP, tested over a congested network
- **Simple Language Compiler** — compiles a C++-like language to MIPS assembly using CFG-based bottom up parsing
- **Nachos Operating System** — CS354 operating systems group project
- **Waterloo Aerial Robotics Group** — fully autonomous flying robots, as part of a group effort

**Also**
- **Various tests** — small projects for getting started on something new quickly
- **Other** — hundreds of other libraries, applications, and custom software jobs

Full descriptions live at [brianbondy.com/projects](https://www.brianbondy.com/projects).

</details>

## Contact
📧 [Email](mailto:bbondy@gmail.com) · 🐦 [Twitter](https://twitter.com/brianbondy) · ✍️ [Blog](https://brianbondy.com/all) · 💼 [LinkedIn](https://www.linkedin.com/in/bbondy) · 🏃 [Strava](https://www.strava.com/athletes/bbondy) · 📸 [Instagram](https://www.instagram.com/brianbondy/) · 💡 [Stack Overflow](https://stackoverflow.com/users/3153/brian-r-bondy) · 🔐 [Keybase](https://keybase.io/bbondy)
