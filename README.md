# Server Management Scripts

This public repository contains scripts retrieved from external GitHub sources. **Review every script before running it.**

## `tools.sh`

Source:

```text
https://codeberg.org/nkka404/all-in-one/raw/branch/main/tools.sh
```

Run the published copy:

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/karyan779/all-in-one-tools/main/tools.sh)
```

The source file was uploaded unchanged. SHA-256 at publication time:

```text
f8c56878ea10e055d3f2912d5a763e223b30ecd251f4e3530ecf9ea9fe5baf5b
```

## `DNST`

Source:

```text
https://raw.githubusercontent.com/AAAAAEXQOSyIpN2JZ0ehUQ/SSHPLUS-MANAGER-FREE/master/Plus
```

Run the published copy:

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/karyan779/all-in-one-tools/main/DNST)
```

The file is stored with the requested filename `DNST` and was uploaded unchanged. SHA-256 at publication time:

```text
6804cd373f9e3e9cd94a4bb683055dbc6c49c78aa8ab7a2eb385f2955855627e
```

## Important warnings

Both scripts require or expect root-level system access. `DNST` installs packages with `apt` and `pip`, opens firewall ports, writes files and commands under `/bin` and `/usr/share`, downloads additional scripts and data from external URLs, modifies SSH-related files, and creates or updates user-management data. The scripts may alter or interrupt an existing VPS configuration. Use them only on a server you own or administer, inspect the source first, and make a complete backup before execution.

Neither script was executed during preparation. `tools.sh` passed `bash -n` syntax validation. `DNST` was downloaded and inspected without execution.
