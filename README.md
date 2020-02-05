# minimalFailingMixedSln4Ionide

This solution exposes a bug in Ionide Fsharp. It has:

1) a csproj referencing a sibling fsproj
2) and the above mentioned fsproj.

it should be possible to reproduce the bug by just opening the solution:

```powershell
code .
```

It is created with this version of the sdk:

```powershell
dotnet --info
.NET Core SDK (reflecting any global.json):
 Version:   3.1.100
 Commit:    cd82f021f4

Runtime Environment:
 OS Name:     Windows
 OS Version:  10.0.17134
 OS Platform: Windows
 RID:         win10-x64
 Base Path:   C:\Program Files\dotnet\sdk\3.1.100\

Host (useful for support):
  Version: 3.1.0
  Commit:  65f04fb6db
  ...
```
