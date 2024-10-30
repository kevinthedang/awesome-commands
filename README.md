## Awesome Commands
Cool commands/stuff to know

#### `winget`
Upgrade Apps and Packages Command for Windows.
Run `Command Prompt` in Administrator.
```sh
winget upgrade

...

winget upgrade --all
```

Here is a sample output:
```sh
C:\Windows\System32>winget upgrade --all
Name                                                         Id                          Version      Available    Source
-------------------------------------------------------------------------------------------------------------------------
Microsoft Visual C++ 2010  x64 Redistributable - 10.0.30319  Microsoft.VCRedist.2010.x64 10.0.30319   10.0.40219   winget
Azul Zulu JDK 17.52.17 (17.0.12), 64-bit                     Azul.Zulu.17.JDK            17.52.17     17.54.21     winget
Microsoft Visual C++ 2013 Redistributable (x64) - 12.0.30501 Microsoft.VCRedist.2013.x64 12.0.30501.0 12.0.40664.0 winget
Microsoft .NET Runtime - 6.0.16 (x64)                        Microsoft.DotNet.Runtime.6  6.0.16       6.0.35       winget
Microsoft Visual C++ 2013 Redistributable (x86) - 12.0.30501 Microsoft.VCRedist.2013.x86 12.0.30501.0 12.0.40664.0 winget
Discord                                                      Discord.Discord             1.0.9166     1.0.9168     winget
GitHub Desktop                                               GitHub.GitHubDesktop        3.4.6        3.4.8        winget
Microsoft Visual Studio Code (User)                          Microsoft.VisualStudioCode  1.94.2       1.95.0       winget
Dev Home                                                     Microsoft.DevHome           0.1800.640.0 0.1801.640.0 winget
9 upgrades available.
1 package(s) have version numbers that cannot be determined. Use --include-unknown to see all results.
```