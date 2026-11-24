# Olive Linux — GPL source subset

This repository contains a filtered selection of GPL-licensed Linux source
files from the OS3 kernel checkout, associated with kernel release
**5.10.10-rt24**.

**This is a partial source snapshot. It is not a complete, buildable kernel
tree and is not presented as a complete corresponding-source release for a
device.**

## Contents

- Original source paths and file contents under `linux/`.
- Files with explicit GPL notices, including applicable syscall exceptions.
- Selected GPL-covered working-tree changes, including RT-related changes.
- Original copyright and license notices.
- File hashes, license-selection evidence and change indicators in
  `SOURCE_MANIFEST.json`.

The publication policy excludes device-tree files and bindings, hardware
configuration, binaries, firmware, signing material, credentials, private
project data, and files with permissive, mixed or unclassified license
notices. Private repository history is not included.

These exclusions mean that required build inputs and dependencies are missing.
Do not use this repository alone to rebuild a product or to assert completion
of a GPL source-delivery obligation.

## Provenance

- Snapshot date: 2026-11-24.
- Base project: [STMicroelectronics Linux](https://github.com/STMicroelectronics/linux).
- Base tag: `v5.10-stm32mp-r1`.
- Base commit: `ce6891abb1c895d4849e6f784615687341b3dbde`.
- Kernel Makefile version in the source checkout: `5.10.10`.
- Observed kernel release in the associated build output: `5.10.10-rt24`.

The source checkout contains changes beyond that base commit. The manifest
identifies retained files that differ from the base and retained additions.
It records an observed snapshot, not the authorship or original date of each
change. A complete source-to-binary rebuild and a match to every customer
release have not been established.

## Licenses

The original per-file notices govern each source file. Some GPL files permit
later GPL versions; files with `Linux-syscall-note` retain that exception.
The original kernel `COPYING` and referenced GPL/exception texts are included.
Repository documentation and generated metadata are provided under GPL-2.0-only;
see the root `COPYING`.

Filtering does not relicense any upstream material or change the obligations
that apply to distributed binaries. Upstream links identify provenance; they
are not a statement that this subset supplies all required source.
