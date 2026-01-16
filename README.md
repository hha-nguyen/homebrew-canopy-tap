# Homebrew Canopy Tap

Official Homebrew tap for [Canopy CLI](https://github.com/hha-nguyen/canopy-backend) - the mobile app policy compliance scanner.

## Installation

```bash
brew tap hha-nguyen/canopy-tap
brew install canopy
```

## Upgrade

```bash
brew update
brew upgrade canopy
```

## Uninstall

```bash
brew uninstall canopy
brew untap hha-nguyen/canopy-tap
```

## Available Formulae

| Formula | Description |
|---------|-------------|
| `canopy` | CLI for Canopy mobile app policy compliance scanner |

## Quick Start

After installation:

```bash
# Authenticate with your API key
export CANOPY_API_KEY=cpk_your_api_key_here

# Scan your mobile app project
canopy scan .

# Scan for specific platform
canopy scan . --platform apple

# Output SARIF for GitHub Code Scanning
canopy scan . --format sarif --output canopy.sarif
```

## Documentation

- [CLI Documentation](https://github.com/hha-nguyen/canopy-cli/blob/main/README.md)
- [API Documentation](https://github.com/hha-nguyen/canopy-backend/blob/main/api/openapi.yaml)

## Issues

If you have issues with the CLI itself, please report them at:
https://github.com/hha-nguyen/canopy-backend/issues

If you have issues with this tap or the Homebrew formula, please report them at:
https://github.com/hha-nguyen/homebrew-canopy-tap/issues

## License

MIT License - see [LICENSE](LICENSE) for details.
