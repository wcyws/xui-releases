# XUI Node releases

This public repository contains XUI Node installation packages and release metadata. Source code is maintained separately in a private repository.

Each explicit version provides Linux amd64 and arm64 binaries for `xnode` and `xnode-agent`, plus `manifest.json` and `SHA256SUMS`. Verify the selected asset digest before execution. Prereleases are candidates pending installation acceptance.

The manifest records the declared source commit and asset digests. A release tag points to a metadata commit in this repository containing the matching `releases/<tag>.json`; that metadata commit is distinct from the private source commit. Published version tags and assets are not replaced.
