*[繁體中文](README.md)*

# NcCycleSense

Cycle time estimation for NC programs. Your NC code never leaves your machine.

The browser version needs no install — drop a file in and it runs:
<https://nccyclesense.com/en/>

## Download

Latest build: [Releases](https://github.com/ming0393639/NcCycleSense-releases/releases/latest).

Windows 10 / 11 (64-bit). Installs to `%LOCALAPPDATA%\NcCycleSense\`, no administrator
rights required. The installer is not code-signed yet, so Windows will report an unknown
publisher — choose **More info** → **Run anyway**.

You get two programs: `NcCycleSense.exe` (the interface) and `nccs.exe` (command line).

## Versions

Every release stays on this page. A licence's update period is compared against a build's
release date, so older builds remain available.

## Licensing

Works without an activation file: the full engine (5-axis, macros, canned cycles, 3D
toolpath), one program at a time, a 10 MB limit, and a watermark on the report.

Pro removes the limit and the watermark, and adds multi-operation totals and batch mode.
Activation files are verified locally — no network access. **Not yet available for
purchase**; see <https://nccyclesense.com/en/pricing.html>.

## No source code here

This repository holds installers only. The auditability notes are at
<https://nccyclesense.com/en/legal.html#audit>.
