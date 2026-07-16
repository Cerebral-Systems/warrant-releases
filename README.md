# Warrant Releases

Public, signed macOS and GNU/Linux artifacts for the Warrant local agent policy
gateway.

Install with Homebrew:

```sh
brew install cerebral-systems/tap/warrant
```

Homebrew is the supported macOS installation path. Ubuntu 24.04 users can download the
AMD64 or ARM64 archive and its matching `.sha256` file from the latest release, then
verify it before extraction:

```sh
sha256sum --check warrant-v0.4.0-linux-amd64.tar.gz.sha256
```

Each release includes architecture-specific archives, SHA-256 manifests, SPDX SBOMs,
and Sigstore signing evidence. The artifacts and Homebrew tap are anonymously readable.

v0.4.0 is a local CLI release. It does not include hosted API onboarding. Warrant is an
integrated application boundary, not an OS sandbox or a claim that every agent path is
formally verified. See the
[v0.4.0 release notes](https://github.com/Cerebral-Systems/warrant-releases/releases/tag/v0.4.0)
for the supported agents, versions, and exact source commit.
