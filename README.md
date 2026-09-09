# All-in-One Server Management Toolkit

This repository contains the `tools.sh` script retrieved from the following Codeberg URL:

```text
https://codeberg.org/nkka404/all-in-one/raw/branch/main/tools.sh
```

## Usage

**Review the script before running it.** The script requires root privileges and can make significant changes to a VPS. To download and run the current GitHub copy:

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/karyan779/all-in-one-tools/main/tools.sh)
```

For a safer review-first workflow:

```bash
curl -fsSL https://raw.githubusercontent.com/karyan779/all-in-one-tools/main/tools.sh -o tools.sh
less tools.sh
bash tools.sh
```

## Important warnings

The script can perform privileged and potentially destructive operations, including installing software from external URLs, modifying Docker and system services, saving Cloudflare tokens under `/root`, changing cron and shell configuration, clearing logs and temporary directories, rebooting the VPS, and reinstalling the operating system. Use it only on a server you own or administer, and make a backup before selecting any installation, cleanup, downgrade, or reboot option.

The source file was uploaded unchanged. It passed `bash -n` syntax validation before publication. It was not executed during preparation.

## Source integrity

SHA-256 of the retrieved `tools.sh` at publication time:

```text
f8c56878ea10e055d3f2912d5a763e223b30ecd251f4e3530ecf9ea9fe5baf5b
```
