# dart-lsp

Dart/Flutter language server for Claude Code, providing code intelligence, diagnostics, and refactoring.

## Supported Extensions
`.dart`

## Installation

The Dart Analysis Server is included with both the Dart SDK and Flutter SDK.

### Via Flutter (recommended for Flutter projects)
```bash
# macOS
brew install --cask flutter

# Or download from https://docs.flutter.dev/get-started/install
```

### Via Dart SDK (for pure Dart projects)
```bash
# macOS
brew tap dart-lang/dart
brew install dart

# Linux (Debian/Ubuntu)
sudo apt-get install apt-transport-https
wget -qO- https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo gpg --dearmor -o /usr/share/keyrings/dart.gpg
echo 'deb [signed-by=/usr/share/keyrings/dart.gpg arch=amd64] https://storage.googleapis.com/download.dartlang.org/linux/debian stable main' | sudo tee /etc/apt/sources.list.d/dart_stable.list
sudo apt-get update
sudo apt-get install dart

# Windows
choco install dart-sdk
# or
winget install Dart.Dart-SDK
```

After installation, ensure `dart` is in your PATH. The language server is started via `dart language-server`.

## More Information
- [Dart SDK](https://dart.dev/get-dart)
- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- [Dart Analysis Server](https://github.com/dart-lang/sdk/tree/main/pkg/analysis_server)
