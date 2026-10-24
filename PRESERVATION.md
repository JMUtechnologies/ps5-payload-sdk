# Preservation record

## Origin

- Original project: https://github.com/ps5-payload-dev/sdk
- Official release: https://github.com/ps5-payload-dev/sdk/releases/tag/v0.42
- Original credit: John Törnblom and contributors, with additional upstream credits retained in the original README and files.
- Preserved by: JMUtechnologies.
- Preservation date: 2026-10-24.
- Source tag: `v0.42`.
- Source commit: `4eb701204fc3f8d31e84cf8ca272974e2be9c867`.

This is a preservation copy, not an official continuation or a claim of original authorship. PS5 Payload SDK is a separate upstream project from BlackBearReloaded's work.

## Binary SDK verification

The ZIP was copied from this workstation's existing SDK cache. Its 8,816,075 bytes have SHA-256:

```text
8cfbc7cd5811e719eb4f0c47eea668d3dc7b40bc8ab11c4a5031d40c23ec02da  ps5-payload-sdk-v0.42.zip
```

This matches both the workstation installer's pinned digest and GitHub's digest for the official v0.42 asset, originally named `ps5-payload-sdk.zip`. Only the preserved asset filename differs; its contents are unchanged. The ZIP passed its CRC check. All 2,923 installed SDK files were compared with the archive and matched byte for byte, with none missing.

## Matching source

The official `v0.42` source tag resolves to commit `4eb701204fc3f8d31e84cf8ca272974e2be9c867`. The upstream Git repository passed a full object integrity check. All 1,992 tracked source files were reconstructed from that commit and checked against their original Git blob hashes, retaining executable file modes and symbolic links.

The release includes an unchanged source snapshot archive generated from that commit, alongside the unchanged SDK ZIP. It also includes a convenience preservation bundle containing both archives, the original SDK license, supplemental LLVM notices, this record, and checksums. LLVM source is an external input pinned by the original `libcxx.sh`; its license texts are included, while its full source distribution remains external.

This repository imports the v0.42 source snapshot with new preservation history. It does not import the upstream project's complete Git history, issues, pull requests, or unrelated release versions.

## Preservation changes

- Added a preservation notice above the original README. The original content follows the separator unchanged.
- Added this preservation record and supplemental third-party notices.
- Added original LLVM 18.1.8 component license texts under `LICENSES/LLVM-18.1.8/`.
- Retained the two original GitHub Actions workflows unchanged under `.github/preserved-workflows/`, where they are inactive. Review their destinations and dependencies before enabling them.

All other upstream tracked files retain their original paths, contents, and modes. No source implementation was changed. Local credentials, console settings, build caches, and uncommitted workstation changes were not imported.

## Validation limits

Archive integrity, installed-file identity, source object identity, and available script syntax were checked. The SDK and its examples were not rebuilt or executed for this preservation import. No console connection or PS5 hardware run was performed. Preservation of v0.42 does not establish compatibility with every host or console environment.
