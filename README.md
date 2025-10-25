> [!WARNING]
> A recent Blue Archive update now wraps the AES session key with RSA and uses that AES key to encrypt server responses. Because the AES key is sent RSA-encrypted, mitmproxy can no longer decrypt responses to extract the player information, so this tool no longer works.

# Buruaka Player Information Exporter

This is a tool to export player information via mitmproxy WireGuard mode.

## Disclaimer

This repository is for educational purposes only. The author of this repository is not responsible for any misuse of the information.

## Prerequisites

- Python 3.6 or higher
- WireGuard Android app

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```bash
python proxy.py
```

## License

This repository is licensed under the MIT license.
