# Security policy

**Please do not report security vulnerabilities through public issues.**

Report them privately instead: open the **Security** tab of this repository
and choose **Report a vulnerability**. Only the NEURAX maintainers can read
what you send there.

Please include the NEURAX version (`neurax --version`, or the file name you
installed), your operating system, and the steps to reproduce.

We acknowledge reports as soon as we see them and fix active vulnerabilities
as a priority. Users affected by a critical issue will be told directly.

## Verifying a download

Only install NEURAX from the
[releases of this repository](https://github.com/NEURAX-canvas/neurax-releases/releases)
or from [neuraxs.dev](https://neuraxs.dev). Each release lists a SHA-256
checksum for every file (`SHA256SUMS.txt`):

```bash
sha256sum -c SHA256SUMS.txt --ignore-missing
```
