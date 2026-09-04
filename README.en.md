*[繁體中文](README.md)*

# NcCycleSense — Downloads

Cycle time estimation for NC programs. **Your NC code is never uploaded** —
everything is computed on your own machine.

Product information and the browser version (no install; drop a file in and it runs):
<https://nccyclesense.com/en/>

## Download

Installers are under **Releases**, on the right. Latest:

<https://github.com/ming0393639/NcCycleSense-releases/releases/latest>

| | |
|---|---|
| System | Windows 10 / 11 (64-bit) |
| Requires | WebView2 (already present on most Windows 10/11 installs) |
| Installs to | `%LOCALAPPDATA%\NcCycleSense\` (no administrator rights needed) |

The installer contains **two executables**: `NcCycleSense.exe` (the graphical
interface) and `nccs.exe` (the command line). The two produce byte-identical
cycle times — that is verified before packaging, and packaging is refused if
they disagree.

> ⚠️ The installer is not code-signed yet, so Windows will say the publisher is
> unknown. Choose **More info** → **Run anyway**.

## Old versions stay here, permanently

**The version you bought keeps working forever.** A build released after your
update period ends runs on the free tier instead, and at that point you need to
be able to go back to the build you paid for — so nothing on this page is ever
removed.

The date shown next to each release is its build date. That is the date your
update period is compared against.

## Licensing

With no activation file the app runs on the **free tier**: the engine is
complete (5-axis, macros, canned cycles, 3D toolpath), with a 10 MB input limit,
one program at a time, and a watermark on the report.

With Pro, download `license.nccs` from
<https://nccyclesense.com/en/account.html>, move it to that computer by any
means, and import it. **Verification is entirely offline** — no network access,
not once. That is exactly what an air-gapped shop needs.

## There is no source code here

This repository holds installers only. The auditability claims — the engine
contains no third-party code, and the browser version lets you confirm in the
DevTools network tab that nothing is uploaded — are explained at
<https://nccyclesense.com/en/legal.html#audit>.
