# Capy

Peer-to-peer meeting rooms: private calls, notes made on your own device, no accounts and no servers that can read them.

**Download:** https://capy.ciranda.dev/downloads · **Releases:** https://github.com/ciranda-dev/capy-releases/releases · **What's new:** [CHANGELOG.md](CHANGELOG.md)

| Platform | File | Status |
| --- | --- | --- |
| macOS (Apple Silicon) | `Capy-darwin-arm64.dmg` | Beta |
| macOS (Intel) | `Capy-darwin-x64.dmg` | Beta |
| Windows (x64) | `Capy-win32-x64.msix` + `Capy-windows-certificate.cer` | Beta |
| Linux (x64, ARM64) | `Capy-linux-<arch>.AppImage`, or `sudo snap install capy --beta` | Beta |
| Android, iOS | [capy-mobile-releases](https://github.com/ciranda-dev/capy-mobile-releases) | Beta |

Once installed, Capy updates itself over the air. Step-by-step install instructions for each system are on the [downloads page](https://capy.ciranda.dev/downloads).

## Verify the download

Each file on a release page shows its SHA-256. To check a file you downloaded, run:

```sh
shasum -a 256 <file>        # macOS and Linux (or: openssl sha256 <file>)
certutil -hashfile <file> SHA256   # Windows
```

and compare it with the one on the release page.

## Report a bug

- In the app: Settings → Help & feedback → Report a bug
- Or open an [issue](https://github.com/ciranda-dev/capy-releases/issues): what you did, what you expected, what happened, and your system and Capy version (Settings → About)

## Other languages

**Português:** Baixe o Capy em https://capy.ciranda.dev/downloads. Cada versão também está na página de [releases](https://github.com/ciranda-dev/capy-releases/releases), e o que mudou está no [CHANGELOG](CHANGELOG.md).

**Español:** Descarga Capy en https://capy.ciranda.dev/downloads. Cada versión también está en la página de [releases](https://github.com/ciranda-dev/capy-releases/releases), y lo que cambió está en el [CHANGELOG](CHANGELOG.md).

**العربية:** نزّل Capy من https://capy.ciranda.dev/downloads. كل إصدار موجود أيضًا في صفحة [الإصدارات](https://github.com/ciranda-dev/capy-releases/releases)، وما تغيّر موجود في [سجل التغييرات](CHANGELOG.md).

---

Capy is proprietary software, © 2026 Ciranda. Each release includes the source of the LGPL components it uses.
