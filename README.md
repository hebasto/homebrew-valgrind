# homebrew-valgrind
Homebrew Tap for Valgrind macOS

## Installation

First, tap this repository:
```
brew tap hebasto/valgrind
```

Then, install `valgrind`:
```
brew install --HEAD hebasto/valgrind/valgrind
```

You can now use `valgrind` as normal.

## Update

Any `brew upgrade` will now correctly rebuild the latest `hebasto/valgrind` instead of the upstream one (which doesn't support latest macOS versions).

```
brew upgrade --fetch-HEAD hebasto/valgrind/valgrind
```
