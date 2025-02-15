# test-goreleaser-workflow

## Install

### Binary release

The following command installs the latest version to `~/.local/bin`

```sh
curl -sSfL https://raw.githubusercontent.com/ttl256/test-goreleaser-workflow/HEAD/install.sh | sh -s -- -b ~/.local/bin
```

```
Usage: install.sh [-b <bindir>] [-d] [<tag>]
  -b sets bindir or installation directory, Defaults to ./bin
  -d turns on debug logging
   <tag> is a tag from
   https://github.com/ttl256/test-goreleaser-workflow/releases
   If tag is missing, then the latest will be used.
```

### MacOS (brew)

```sh
brew tap ttl256/test-goreleaser-workflow && \
brew install test-goreleaser-workflow
```
