<h1 align="center">Könclock</h1>

<p align="center">
  A quiet, dependable desktop alarm for Windows.<br>
  Desktop widget · adjustable opacity · always-on-top · system tray · themes & accents · built-in sounds
</p>

<p align="center">
  <strong>Windows 7 SP1+</strong> · <strong>.NET Framework 4.8</strong> · <strong>C# 6 / WinForms</strong> · <strong>x86 + x64</strong>
</p>

---

## Download

**[Get the latest release](../../releases/latest)**

| Your Windows | Installer | Portable |
|---|---|---|
| **64-bit** — recommended for most PCs | `Könclock-1.1.6-Setup-x64.exe` | `Könclock-1.1.6-Portable-x64.zip` |
| **32-bit** — or compatibility fallback | `Könclock-1.1.6-Setup-x86.exe` | `Könclock-1.1.6-Portable-x86.zip` |

Also available on the release page:
- `Könclock-1.1.6-Source.zip` — full source, tests, installer script, and asset generator.

> **Which one should I pick?**  
> Use **x64** if Windows is 64-bit. Use **x86** if Windows is 32-bit, or if you prefer the compatibility build. The x86 build also runs on 64-bit Windows. Install only one architecture; both share the same Könclock settings.

## Features

- **Alarms that repeat the way you expect** — Once, Weekdays, Every day, weekends, or custom days.
- **Desktop widget** — clock and next alarm at a glance, with independent always-on-top and **adjustable opacity (20–100%)**.
- **Main window pinning** and **minimize/close to tray** so alarms keep running.
- **Snooze** with absolute-time rescheduling; simultaneous alarms ring one after another.
- **Missed-alarm catch-up** after wake/reopen, within a configurable safety window.
- **System / Light / Dark** themes plus **System / Blue / Teal / Violet / Amber / Rose** accents.
- **Four built-in sounds** embedded in the EXE, plus import of uncompressed PCM WAV files.
- **Per-alarm volume** with a clearer audio taper, live preview refresh, mute at 0%, original level at 100%.
- **History restore** — bring back a deleted alarm from its snapshot, or re-enable a dismissed/snoozed alarm without creating a duplicate.
- **Settings that stay put** — adjust several settings in one visit. Changing widget opacity no longer pulls the page back down when you next choose a theme/accent; colors update in place without rebuilding the list or resetting scroll.
- **Local-first** — no account, cloud sync, ads, or telemetry.
- **Single-EXE app assets** — icon and built-in sounds are embedded; no runtime DLLs required.

## Requirements

- Windows 7 SP1, Windows 8.1, Windows 10, or Windows 11.
- Microsoft **.NET Framework 4.8**.
- The installer includes Microsoft's small official web bootstrap and asks before using it if .NET 4.8 is missing.
- For offline PCs, install .NET 4.8 first:  
  <https://go.microsoft.com/fwlink/?linkid=2088631>

## Quick start

### Installer
1. Download the installer for your architecture.
2. Run it. A per-user install is offered by default.
3. Launch **Könclock** and add your first alarm.

### Portable
1. Extract the portable ZIP to a writable folder, for example `Documents\Könclock`.
2. Run `Könclock.exe`.
3. Settings are saved beside the EXE as `Könclock.settings.json`; imported sounds go into `Sounds`.

If the portable folder is not writable, Könclock falls back to `%APPDATA%\Könclock` and tells you.

## Data & privacy

| Mode | Settings location |
|---|---|
| Installed | `%APPDATA%\Könclock` |
| Portable | Beside `Könclock.exe`, with AppData fallback |

Könclock stores alarms, settings, history, and imported sounds locally. It does not phone home. The app must be running and the PC awake to ring; it does not wake a sleeping PC.

## License

See [LICENSE](LICENSE)
