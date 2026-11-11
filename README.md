# Awesome-Cloud-Command-Line-Interface-CLI-Terminal

# Top Cloud Command-Line Interface (CLI) Terminal Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Browser-Based Shells, Modern Terminal Emulators & Cloud-Native CLI Environments*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Command-Line Interface (CLI) Terminals**. These tools provide terminal access from anywhere—browser-based cloud shells with persistent storage, modern terminal emulators with AI assistance, and SSH clients for remote infrastructure management—eliminating the need for local terminal configuration while enabling teams to work from any device.

**Examples** include AWS CloudShell, Google Cloud Shell, Azure Cloud Shell, Warp Terminal, Termius, Hyper, Gitpod CLI, Replit Shell, Webminal, and Zoho Terminal (the category leaders).

**Open-source emphasis**: This section highlights every major active project for open-source terminal emulators, web-based terminal libraries, and self-hosted shell environments—ideal for developers, system administrators, and platform engineers building transparent, vendor-neutral terminal infrastructure without per-seat subscriptions.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[AWS CloudShell](https://aws.amazon.com/cloudshell/)** | Browser-based shell pre-authenticated with AWS Console credentials. Includes AWS CLI, SDKs, and common tools. Persistent storage in `$HOME` per Region; VPC environments available for private resource access [citation:1][citation:11]. | Free (pay only for AWS resources used; data transfer at standard rates) | **Free forever**: 1 GB persistent storage per Region, up to 10 concurrent shells per Region, 120-day storage retention after last session, 12-hour max session duration [citation:1][citation:11] |
| **[Google Cloud Shell](https://cloud.google.com/shell)** | Browser-accessible shell for Google Cloud with 5 GB persistent disk mounted at `$HOME`. Includes gcloud CLI, language runtimes, and editors. Ephemeral mode available for shorter startup without persistence . | Free (pay only for GCP resources used) | **Free forever**: 5 GB persistent disk per user, 1-hour idle timeout, 12-hour max session, 50 hours/week usage quota [citation:2] |
| **[Azure Cloud Shell](https://azure.microsoft.com/en-us/products/cloud-shell/)** | Browser-based Bash or PowerShell terminal for Azure resource management. Requires an Azure Storage account for the mounted 5 GB file share that persists `$HOME` [citation:3][citation:13]. | Free host machine; storage costs apply for the required Azure Files share | **Free host**: 5 GB persistent file share (storage billing at standard Azure Files rates), 20-minute idle timeout |
| **[Warp Terminal](https://www.warp.dev/)** | Modern terminal with AI agent integration, block-based output, and collaborative features. Free tier includes core terminal, Warp Agent CLI access, and limited cloud agents [citation:14]. | Free: $0/month; paid tiers available with additional AI usage | **Free forever**: Core terminal features, Warp Agent CLI access, bring-your-own AI inference, limited cloud agents, limited Warp Drive [citation:14] |
| **[Termius](https://termius.com/)** | Modern SSH client with cross-device sync, SFTP, port forwarding, and AI-powered autocomplete. Starter plan free for commercial usage [citation:5][citation:15]. | Starter: Free; Pro/Team tiers available | **Free forever**: Local vault, SSH/SFTP, port forwarding, AI autocomplete, multi-tab/split-view, ad-free [citation:5][citation:15] |
| **[Gitpod](https://www.gitpod.io/)** | Cloud development environment with terminal access in browser or desktop. Free plan includes Gitpod Desktop with unlimited local environments and 5 concurrent cloud environments [citation:7]. | Core: $20/month; OCU add-on: $10 | **Free plan**: 5 concurrent cloud environments, unlimited local environments via Gitpod Desktop, up to 896 cores/12TB RAM/GPUs capacity [citation:7] |
| **[Replit Shell](https://replit.com/)** | Browser IDE with integrated terminal supporting many languages. Free Starter plan provides shell access with usage and performance limits [citation:8]. | Free Starter; paid plans for more compute | **Free Starter**: Browser IDE + terminal, no credit card required, usage/performance limits apply [citation:8] |
| **[Webminal](https://www.webminal.org/)** | Browser-based Linux terminal for learning Bash commands. Free registration required; provides access to gcc, nano, Python, and GNU Bash shell [citation:9]. | Free (learning-focused platform) | **Free**: Full Bash shell access, compiler suite, editor, Python after registration [citation:9] |
| **[Zoho Terminal](https://www.zoho.com/)** | Terminal within Zoho's developer ecosystem (limited public information available; primarily part of Zoho's broader cloud platform). | Included with Zoho platform access | Contact Zoho for current availability and limits |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Hyper](https://github.com/vercel/hyper)** | [![Stars](https://img.shields.io/github/stars/vercel/hyper?style=social&color=white)](https://github.com/vercel/hyper/stargazers) | Terminal built on open web technologies (Electron/TypeScript, MIT). Extensible via plugins, cross-platform (Windows/macOS/Linux), ~43.7k GitHub stars [citation:6]. |
| **[xterm.js](https://github.com/xtermjs/xterm.js)** | [![Stars](https://img.shields.io/github/stars/xtermjs/xterm.js?style=social&color=white)](https://github.com/xtermjs/xterm.js/stargazers) | The industry-standard terminal emulator component for the web. Used by VS Code, Replit, GitHub, and JupyterLab. Supports WebGL rendering for performance [citation:10]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[VS Code Terminal](https://github.com/microsoft/vscode)** | [![Stars](https://img.shields.io/github/stars/microsoft/vscode?style=social&color=white)](https://github.com/microsoft/vscode/stargazers) | Integrated terminal in Visual Studio Code, built on xterm.js with WebGL acceleration. Open-source (MIT) and widely used as a reference implementation for web-based terminals [citation:10]. |
| **[Rio Terminal](https://github.com/raphamorim/rio)** | [![Stars](https://img.shields.io/github/stars/raphamorim/rio?style=social&color=white)](https://github.com/raphamorim/rio/stargazers) | GPU-accelerated terminal emulator written in Rust, designed for performance and cross-platform support. |
| **[WGLT](https://github.com/codyebberson/wglt)** | [![Stars](https://img.shields.io/github/stars/codyebberson/wglt?style=social&color=white)](https://github.com/codyebberson/wglt/stargazers) | WebGL terminal renderer addon for xterm.js, enabling high-performance rendering for demanding terminal workloads [citation:10]. |

**Frameworks for building custom systems**: Combine **xterm.js** for browser-based terminal rendering, **Hyper** for a customizable local terminal, and **VS Code's terminal implementation** as a reference for integrating terminals into web applications—or deploy **AWS/GCP/Azure Cloud Shell** for zero-infrastructure cloud CLI access.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cloud CLI terminals provide access to sensitive cloud resources; enforce least-privilege IAM policies, session timeouts, and audit logging.
- Self-hosted terminal solutions require proper authentication and network isolation; browser-based terminals should be served over HTTPS with secure WebSocket connections.

---

**Made for developers, system administrators, platform engineers, and teams building cloud-native workflows.**  
Let's make cloud CLI terminals more open, accessible, and secure.
