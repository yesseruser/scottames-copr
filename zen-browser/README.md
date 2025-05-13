# Zen Browser

[![⚡️Powered By: Copr](https://img.shields.io/badge/⚡️_Powered_by-COPR-blue?style=flat-square)](https://copr.fedorainfracloud.org/)
![📦 Architecture: x86_64](https://img.shields.io/badge/📦_Architecture-x86__64-blue?style=flat-square)
[![Latest Version](https://img.shields.io/badge/dynamic/json?color=blue&label=Version&query=builds.latest.source_package.version&url=https%3A%2F%2Fcopr.fedorainfracloud.org%2Fapi_3%2Fpackage%3Fownername%3Dscottames%26projectname%3Dzen-browser%26packagename%3Dzen-browser%26with_latest_build%3DTrue&style=flat-square&logoColor=blue)](https://copr.fedorainfracloud.org/coprs/scottames/zen-browser/package/zen-browser/)
[![Copr build status](https://copr.fedorainfracloud.org/coprs/scottames/zen-browser/package/zen-browser/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/scottames/zen-browser/package/zen-browser/)

## About

[Zen Browser](https://zen-browser.app/) packaged for Fedora and published to [copr](https://copr.fedorainfracloud.org/coprs/scottames/zen-browser)

### Bugs

- Bugs related to the Zen Browser application should be reported to the [zen-browser GitHub org](https://github.com/zen-browser/desktop/issues)
- Bugs related to this package should be reported to [this Git project](https://github.com/scottames/copr/issues)

>[!INFO]
> This software does not include any licenses of its own.
> The additional `.desktop` file is based on the Firefox Release Channel (default).

## Installation

1. Enable copr repo

```bash
sudo dnf copr enable scottames/zen-browser
```

  - Substitute `dnf` for `yum` if desired

2. (Optional) Update package list

```bash
sudo dnf check-update
```

3. Install

```bash
sudo dnf install zen-browser
```
