# gregMod.ConsoleInputGuard (FMF.ConsoleInputGuard)

Suppresses accidental **P** hotkey actions while a UI text field is focused (`InputField` / `TMP_InputField`).

| | |
|:---|:---|
| **In workspace** | Path `gregFramework/gregMod.ConsoleInputGuard/`. Overview: [gregFramework README](../README.md). |
| **Remote** | [`mleem97/gregConsoleInputGuard`](https://github.com/mleem97/gregConsoleInputGuard) |

## Build

```powershell
Set-Location $PSScriptRoot
dotnet build .\FMF.ConsoleInputGuard.csproj -c Release -p:GameDir="C:\Program Files (x86)\Steam\steamapps\common\Data Center"
```

(Adjust `GameDir` to your local installation.)
