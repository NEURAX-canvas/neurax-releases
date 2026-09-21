# NEURAX — desktop downloads

NEURAX analyses a neural network architecture before it is trained: parameters,
FLOPs, memory, latency, cost, energy and carbon, across a database of
accelerators. The desktop studio runs the whole compiler on your machine —
your designs and data never leave it.

This repository only hosts the installers. It contains no source code.

## Install

**Linux and macOS**, one command:

```bash
curl -fsSL https://raw.githubusercontent.com/NEURAX-canvas/neurax-releases/main/install.sh | sh
```

It installs under `~/.local` (no sudo), adds NEURAX to your applications menu
and makes `neurax` available in the shell.

    curl -fsSL …/install.sh | sh -s -- --version v0.20.1   # a specific release
    curl -fsSL …/install.sh | sh -s -- --uninstall         # remove it again

**Windows**, or to install by hand, take a file from the
[latest release](https://github.com/NEURAX-canvas/neurax-releases/releases/latest):

| Platform | File |
|---|---|
| Linux, any distribution | `NEURAX_<version>_amd64.AppImage` |
| Debian, Ubuntu | `NEURAX_<version>_amd64.deb` |
| Fedora, RHEL | `NEURAX-<version>-1.x86_64.rpm` |
| macOS, universal | `NEURAX_<version>_universal.dmg` |
| Windows | `NEURAX_<version>_x64-setup.exe` or `.msi` |

## First launch

The studio opens after you sign in with your NEURAX account. "Log in" opens
[neuraxs.dev](https://neuraxs.dev) in your browser; once you are signed in
there, the studio opens by itself. The sign-in is kept in your system keychain,
so later launches go straight in.

## Problems

Open an issue in this repository.

---

Copyright © 2024–2026 Martial. All rights reserved. NEURAX is proprietary
software; these binaries are provided for use, not redistribution.
