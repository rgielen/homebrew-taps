# rgielen/homebrew-taps

Personal Homebrew tap by [@rgielen](https://github.com/rgielen).

## Usage

```bash
brew tap rgielen/taps
brew install <formula>
```

## Available formulas

| Formula | Description | Upstream |
|---|---|---|
| `leitum` | Launch Claude Code against alternative LLM routers | [rgielen/leitum](https://github.com/rgielen/leitum) |

## Continuous integration

Every pull request builds each changed formula from source on macOS and Linux,
runs `brew audit --strict` and `brew test`, and smoke-checks the installed
binary. Version bumps opened by
[rgielen/leitum](https://github.com/rgielen/leitum)'s release workflow are
merged automatically once that passes; anything else is merged by a human.

## License

Each formula's license is the license of the upstream project it packages.
The formula files themselves are released under the BSD 2-Clause license to
match the Homebrew project convention.
