# Hello World in Prolog

A minimal Prolog implementation of "Hello, World!".

## Installation

### macOS
```bash
brew install swi-prolog
```

### Linux
```bash
sudo apt install swi-prolog  # Ubuntu/Debian
sudo dnf install pl  # Fedora/RHEL
```

### Windows
Download SWI-Prolog from https://www.swi-prolog.org/download/stable

## Running

```bash
swipl -q -s hello.pl -t main -halt
```

## Code Explanation

Uses write/1 predicate for output and nl/0 for newline.
