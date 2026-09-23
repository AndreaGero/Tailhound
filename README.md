# Tailhound

A fast desktop app that opens and live-tails log files and understands Laravel, NestJS, JSON-lines (pino, winston), nginx and Apache logs. Local files or remote logs over SSH.

## Download

Get the latest version from **[Releases](https://github.com/AndreaGero/Tailhound/releases/latest)**:

| System | File |
|---|---|
| macOS (Apple silicon and Intel) | `Tailhound_x.y.z_universal.dmg` |
| Windows 10+ | `Tailhound_x.y.z_x64-setup.exe` |
| Linux | `.AppImage`, `.deb` or `.rpm` |

Tailhound updates itself: when a new version is out, a small banner offers to restart.

## First launch on macOS

Tailhound is not notarized yet, so macOS blocks the first launch:

1. Open the `.dmg` and drag Tailhound to Applications.
2. Open Tailhound. macOS says it can't verify the developer; click **Done**.
3. Open **System Settings → Privacy & Security**, scroll to Security, and click **Open Anyway** next to the Tailhound message.
4. Confirm with **Open**. From then on it starts normally.

If macOS says the app "is damaged", run this in Terminal and open it again:

```bash
xattr -dr com.apple.quarantine /Applications/Tailhound.app
```
