# Shutdown

VB6 NT shutdown UI (`ShutDown.exe`, CheckFree): toggles a timed `InitiateSystemShutdown`-style shut down / abort via `clsNTPrivileges` (message “Buh-bye”, 20s). Open `Shutdown.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `ShutDown` (`Shutdown.vbp`) | VB6 | WinForms exe | Timed shutdown/abort with NT privilege helper |
