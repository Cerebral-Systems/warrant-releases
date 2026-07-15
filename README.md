# Warrant Releases

Public, signed macOS release artifacts for the Warrant local agent policy gateway.

Install with Homebrew:

```sh
brew install cerebral-systems/tap/warrant
```

Each release includes ARM64 and Intel archives, SHA-256 manifests, SPDX SBOMs, and
Sigstore signing evidence. The application source repository may remain private; these
artifacts and the Homebrew tap are anonymously readable.

v0.2.1 is a local macOS CLI only. It does not include supported hosted API onboarding,
and it does not claim OS containment or formal verification. Homebrew is the supported
installation path; use the formula from the live tap rather than a release asset.
