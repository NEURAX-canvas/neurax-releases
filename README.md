# NEURAX — desktop downloads

NEURAX is a local studio for designing, analyzing, and training AI models. Its mission is to make every architecture decision measurable before execution: parameters, FLOPs, memory, time, cost, and hardware compatibility.

This repository only hosts the installers. It contains no source code.

## Install

On **Linux or macOS**, one command installs the newest release in your home
directory (no `sudo`), after checking the download against the release's
published `SHA256SUMS.txt`:

```sh
curl -fsSL https://raw.githubusercontent.com/NEURAX-canvas/neurax-releases/main/install.sh | sh
```

Options, after `| sh -s --`: `--version v0.24.3` for a given release,
`--prefix <dir>` to install elsewhere than `~/.local`, `--uninstall` to remove
it (your projects and settings are kept). The script is
[`install.sh`](install.sh) in this repository: read it before running it.

Or download the file for your platform from
[neuraxs.dev/download](https://neuraxs.dev/download), or take one directly
from the [latest release](https://github.com/NEURAX-canvas/neurax-releases/releases/latest),
and check it against that release's `SHA256SUMS.txt`:

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

Open an issue in this repository. For a security vulnerability, do not open a
public issue — see [SECURITY.md](SECURITY.md).

---

Copyright © 2024–2026 Martial. All rights reserved. NEURAX is proprietary
software; these binaries are provided for use, not redistribution.
