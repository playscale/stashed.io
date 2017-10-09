# Stashed community support repository

[![Join the chat at https://gitter.im/playscale/stashed.io](https://badges.gitter.im/playscale/stashed.io.svg)](https://gitter.im/playscale/stashed.io?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Stashed is a fast compiler cache for Microsoft Visual Studio.

This repository is used to track issues and link new releases of Stashed.

Visit us at https://stashed.io

## Changelog

### 1.2.0 (2017-10-09)

- New option to completely disable writes to a drive
- New systray application
- Fix rebuild all triggered after compiling a single file

### 1.1.4 (2017-09-26)

- Fix performance issues

### 1.1.3 (2017-09-25)

- Use vswhere to detect Visual Studio 2017

### 1.1.2 (2017-09-22)

- Fix download link not always up-to-date

### 1.1.1 (2017-09-21)

- Clear log counters when viewing logs
- Better cache state description
- Fix "Note: including" showing up in large projects outputs
- Fix PDB handling

### 1.1.0 (2017-09-15)

- Warn when acceleration is unavailable due to license or service not running
- Go to the license page right after installation to get the free trial started

### 1.0.9 (2017-09-15)

- Explicit license feedback
- Fix typo (thanks Derek)

### 1.0.8 (2017-09-14)

- Correctly handle the unsupported use of mixed PDB's and precompiled headers

### 1.0.7 (2017-09-13)

- Support FastBuild

### 1.0.6 (2017-09-11)

- Support Incredibuild

### 1.0.5 (2017-08-25)

- Support PDB files (`/Zi`)

### 1.0.4 (2017-08-16)

- Log file rotation and download buttons
- Don't buffer writing to Visual Studio Output window
- Fix log date display in dashboard
- Fix Visual Studio 2017 Enterprise detection
- Support passing `.obj` files to `cl.exe`
- Support `/E` and `/EP`
- Better cache folder partitions

### 1.0.3 (2017-08-06)

- Throttle maximum number of original cl.exe to keep VisualStudio responsive
- Provide x86 and x64 versions of cl.exe wrapper
- Fix monospace font on Internet Explorer

### 1.0.2 (2017-08-02)

- Fix signing up behind a proxy
- Add release notes on About page

### 1.0.1 (2017-08-01)

- Automatic proxy detection
- Fix PCH name detection for Visual Studio 2012 and 2013

### 1.0.0 (2017-07-31)

- Initial release
