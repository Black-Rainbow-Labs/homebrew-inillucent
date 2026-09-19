# Homebrew tap for inillucent

```
brew install black-rainbow-labs/inillucent/inillucent
```

That installs the release archive from [inillucent.com](https://inillucent.com), so it is a
download and an unpack rather than a build of thirty-one crates. It covers macOS on Apple
silicon and Intel, and Linux on x86-64 and aarch64.

The formula is generated from a built release by `packaging/homebrew/update.sh` in
[Black-Rainbow-Labs/Inillucent](https://github.com/Black-Rainbow-Labs/Inillucent), which reads
every sha256 out of the release's own `SHA256SUMS`. No checksum in this repository is typed by
hand. Edit the template there, not the formula here.
