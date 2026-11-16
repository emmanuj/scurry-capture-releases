# Scurry Capture for Mac

Public downloads for the Scurry Capture Mac beta. Application source is maintained separately.

The first download will appear under Releases after Developer ID signing and Apple notarization are complete. There is no published beta artifact yet.

## Requirements

- macOS 15 or newer on Apple Silicon or Intel.
- An invited Scurry beta account.

## Install

1. Download the versioned ZIP from a published release and open it in Finder.
2. Move **Scurry Capture.app** to Applications and open it.
3. Sign in with your Scurry beta account.
4. Follow the setup at https://app.heyscurry.com/meeting-capture.

Recording starts only when you click **Start capture**. The app records microphone and computer audio, including sounds from other apps, and sends audio for cloud transcription. Let meeting participants know before recording.

Each published ZIP includes a SHA-256 checksum. Verify it in Terminal from the download folder with `shasum -a 256 -c <archive-name>.sha256`.

Support: hello@heyscurry.com
