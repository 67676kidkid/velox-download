# VeloX Optimizer — Downloads

**This repository only hosts the built application. It contains no source code.**

VeloX Optimizer is a portable Windows optimizer: safe, reversible tweaks that
improve gaming, streaming and everyday responsiveness — with a Restore Center
that can undo every change.

---

## ⬇ Download

**[Download VeloX (portable .exe)](https://github.com/67676kidkid/velox-download/releases/latest/download/VeloX-portable.exe)**

| | |
|---|---|
| Platform | **Windows 10 / 11, 64-bit** — **Windows only** (no macOS/Linux) |
| RAM | 4 GB or more (it runs on 2 GB, but slowly) |
| Install | Portable — just run it, nothing to install |
| Requires | Administrator rights — Windows shows the UAC prompt automatically on launch |
| License | Free tier available; Premium / Premium+ / Ultimate unlock Pro Rooms |

Storefront, activation and support: **https://veloxoptimize.vercel.app**

> ⚠️ **Windows 7, 8 and 8.1 will not work.** VeloX runs on the same engine as modern
> browsers (Chromium 110+), which cannot start on those versions — the app simply will
> not open there. 32-bit Windows is not supported either.

---

## 📦 Which file do I need?

Always use the link above. It points at the *latest* release automatically, so
you never have to guess which version is current.

After downloading, you can confirm you got the official file by comparing the
SHA-256 checksum published on the
[download page](https://veloxoptimize.vercel.app/download/).

Windows may show *"Windows protected your PC"* for new applications. Click
**More info → Run anyway** (or right-click the file → **Properties** →
**Unblock**). This is standard behaviour for a new app, not a virus warning.

## 🖥️ Black or blank window? (older PCs / weak graphics)

Version **1.0.3 and newer** detects an unusable graphics driver and switches itself to
software rendering automatically, so the window still appears.

If you are on an older build, or the window is still black / blank / flickering, start
VeloX once in safe mode:

```
VeloX-portable.exe --disable-gpu
```

The choice is remembered, so you only do this once. To switch hardware acceleration
back on:

```
VeloX-portable.exe --force-gpu
```

Still nothing? Make sure you are on 64-bit Windows 10/11, accept the UAC prompt, and
check that your antivirus did not quarantine the file (add an exception if it did).

## 🔑 Activating a paid plan

1. Run VeloX and open the **License** screen.
2. Paste the key you received after purchase.
3. Confirm — premium features unlock immediately.

Keys are cryptographically signed (Ed25519), verified locally on every launch
and never contain any personal data.

## 💬 Support & refunds

- Email: **help.velox@gmail.com**
- 7-day refund if VeloX does not work on your PC — see
  [refund policy](https://veloxoptimize.vercel.app/refund/).

---

*VeloX is not affiliated with Microsoft, PayPal or Discord.*
