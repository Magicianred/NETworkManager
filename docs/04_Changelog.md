---
layout: default
title: Changelog
nav_order: 4
description: "Changelog and download links of all available versions"
permalink: /Changelog
---

# Version 2020.12.2
Date: **28.12.2020**

| File | Checksum [SHA256] |
|---|---|
|[:package: Setup](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.12.2/NETworkManager_2020.12.2_Setup.exe){:target="_blank"}| `4F0EA9AB5969021901AA107A40B0F1C649AB2A39FFC55565DDEF318D983021F9` | 
|[:package: Portable](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.12.2/NETworkManager_2020.12.2_Portable.zip){:target="_blank"}| `7A26775C906586822AE3585CDD2FC3AD361D359D38AC591012E4CB9F82EEA8BA` | 
|[:package: Archiv](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.12.2/NETworkManager_2020.12.2_Archiv.zip){:target="_blank"}| `6094B2C27A279C004049D0AD083C8A23A57864FBD61616DECD2B75A9C3ABDD95` | 

**System requirements**
- Windows 10 / Server (1809 or later)
- [.NET 5.0 / .NET Desktop Runtime 5.0.0](https://dotnet.microsoft.com/download/dotnet/5.0)
- [Microsoft Edge - WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)

## What's new?
- UI reworked / tab size reduced [#398](http://github.com/BornToBeRoot/NETworkManager/issues/398){:target="_blank"} 

## Improvements
- WiFi
  - y-axis is now displayed correct (reversed -100 to 0 dBm) [#366](http://github.com/BornToBeRoot/NETworkManager/issues/366){:target="_blank"} 
  - Space between channel 64 and 100 added (they won't overlap anymore) [#366](http://github.com/BornToBeRoot/NETworkManager/issues/366){:target="_blank"} 
- Add version to title bar [#402](http://github.com/BornToBeRoot/NETworkManager/issues/402){:target="_blank"} 
- Improve title if tab is dragged out (version and application name added) [#414](http://github.com/BornToBeRoot/NETworkManager/issues/414){:target="_blank"} 
- Settings\Language
  - Sort languages by Official, Community and Name [#403](http://github.com/BornToBeRoot/NETworkManager/issues/403){:target="_blank"} 

## Bugfixes
- IP Scanner
  - JSON export fixed it MAC address is null [#392](http://github.com/BornToBeRoot/NETworkManager/issues/392){:target="_blank"} 
- WebConsole
  - Fix dependency (require Edge WebView2 runtime instead if Edge Chromium)  / prevent app crash [#404](http://github.com/BornToBeRoot/NETworkManager/issues/404){:target="_blank"} 
- Context menu icons color fixed [#391](http://github.com/BornToBeRoot/NETworkManager/issues/391){:target="_blank"} 
- Build script fixed if there are spaces in path [#384](http://github.com/BornToBeRoot/NETworkManager/issues/384){:target="_blank"} 
- ToolTip background fixed for LvlCharts [#414](http://github.com/BornToBeRoot/NETworkManager/issues/414){:target="_blank"} 
- Settings
  - Link color/size in About and Language fixed [#391](http://github.com/BornToBeRoot/NETworkManager/issues/391){:target="_blank"} 
  - Groups are now translated [#279](http://github.com/BornToBeRoot/NETworkManager/issues/279){:target="_blank"} 

## Other
- Language files updated

# Version 2020.12.1
Date: **14.12.2020**

| File | Checksum [SHA256] |
|---|---|
|[:package: Setup](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.12.1/NETworkManager_2020.12.1_Setup.exe){:target="_blank"}| `0A84BEF75A65DD457A2CDA64CDE00B3BF380D8D94D6BDB50EBC0869E31F5D2D9` | 
|[:package: Portable](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.12.1/NETworkManager_2020.12.1_Portable.zip){:target="_blank"}| `19D04BA6BBFB323F11889115489A299FE534C49AEA533030DF0F5B47AE7A722E` | 
|[:package: Archiv](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.12.1/NETworkManager_2020.12.1_Archiv.zip){:target="_blank"}| `0F7BF030E4C4ADA8B54DF06C52CA5F19A1E3CA854E67A8E667277544A8882509` | 

**System requirements**
- Windows 10 / Server (1809 or later)
- [.NET 5.0 / .NET Desktop Runtime 5.0.0](https://dotnet.microsoft.com/download/dotnet/5.0)
- [Microsoft Edge - WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)

## What's new?
- Ping Monitor
  - Export as CSV, XML, JSON added [#389](http://github.com/BornToBeRoot/NETworkManager/issues/389){:target="_blank"} [#287](http://github.com/BornToBeRoot/NETworkManager/issues/287){:target="_blank"}

## Improvements
- Network Interface
  - NetworkInterfaceType 53 added [#375](http://github.com/BornToBeRoot/NETworkManager/issues/375){:target="_blank"} 
- About
  - Version is now displayed correctly 2020.12.1 (YEAR.MONTH.PATCH)

## Bugfixes
- DNS Lookup
  - Custom dns resolver fixed [#390](http://github.com/BornToBeRoot/NETworkManager/issues/390){:target="_blank"} 


# Version 2020.12.0
Date: **06.12.2020**

| File | Checksum [SHA256] |
|---|---|
|[:package: Setup](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.12.0/NETworkManager_2020.12.0_Setup.exe){:target="_blank"}| `07B238ADC7B865AB3EB7F7C395674EB2A6C95ADCD4724317941EAB895D3E064D` | 
|[:package: Portable](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.12.0/NETworkManager_2020.12.0_Portable.zip){:target="_blank"}| `191F5A1C7E7DC59EE4B7CB17546564F69339D2963B7EC782FBE48F35C4B10C00` | 
|[:package: Archiv](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.12.0/NETworkManager_2020.12.0_Archiv.zip){:target="_blank"}| `0038524849EAD33A3BAA8B493A424B0416D360E54DB52E931557219C30AAE955` | 

Note: _If you've installed the preview, uninstall it first!_

**System requirements**
- Windows 10 / Server (1809 or later)
- [.NET 5.0 / .NET Desktop Runtime 5.0.0](https://dotnet.microsoft.com/download/dotnet/5.0)
- [Microsoft Edge - WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)

## What's new? 
- Migrated to .NET Desktop 5.0
- Migrated to MahApps.Metro 2.x
- Migrated to WebView2 (Microsoft Edge Chromium)
- Port Scanner
  - Port profiles added [#346](http://github.com/BornToBeRoot/NETworkManager/issues/346){:target="_blank"}
- Profiles
  - Port Scanner - Ports are now optional [#332](http://github.com/BornToBeRoot/NETworkManager/issues/332){:target="_blank"}

## Improvements
- SplashScreen can be disabled in the settings [#331](http://github.com/BornToBeRoot/NETworkManager/issues/331){:target="_blank"}

## Bugfixes
- Discovery Protocol
  - PowerShell fixed [#326](http://github.com/BornToBeRoot/NETworkManager/issues/326){:target="_blank"}
- Settings reset from GUI fixed [#330](http://github.com/BornToBeRoot/NETworkManager/issues/330){:target="_blank"}
- Browse folder/file button in textbox fixed [#329](http://github.com/BornToBeRoot/NETworkManager/issues/329){:target="_blank"}
- About page
  - Open license folder app crash fixed [#327](http://github.com/BornToBeRoot/NETworkManager/issues/327){:target="_blank"}

## Other
- Libraries updated
- Language files updated
  - China (Taiwan) added
  - Hungarian added
  - Polish added
- Resources (OUI, Ports, Whois) updated
- Settings > Language
  - Contributors moved to `.md` file in GitHub repo. Link added to Settings > About.

# Version 2020.9.0 [Preview]
Date: **05.09.2020**

| File | Checksum [SHA256]
|---|---|
|[:package: Setup](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.9.0/NETworkManager_2020.9.0_Setup.exe)| `0EC8C1371C4D62947AE0DC70DBAA91FE105CACECD32DF4A4451C95F71D085014` |
|[:package: Portable](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.9.0/NETworkManager_2020.9.0_Portable.zip)| `E8B60E677E65959BB11F05884F6EA9EC99F09F24ECE869A240B8361F958B4A66` |
|[:package: Archiv](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.9.0/NETworkManager_2020.9.0_Archiv.zip)| `86D13E4C139132BCBA86B6F72ADA4D679C4DD303EA08643D276AE1A5DFD47C47` |

**System requirements**
- Windows 10 x64
- [.NET 5.0 / Desktop Runtime 5.0.0-preview.8](https://dotnet.microsoft.com/download/dotnet/5.0)
- [Microsoft Edge Canary](https://www.microsoftedgeinsider.com/en-us/download)

**Kown issues**
- Application crash on fullscreen [#325](http://github.com/BornToBeRoot/NETworkManager/issues/325)
- [More...](https://github.com/BornToBeRoot/NETworkManager/issues?q=label%3A.NET5.0-feedback+)

## What's new?
- Migration to ~~.NET Core 3.1~~ .NET 5.0!!! (requires [.NET Desktop Runtime 5.0.0-repview.8](https://dotnet.microsoft.com/download/dotnet/5.0)) [#309](http://github.com/BornToBeRoot/NETworkManager/issues/309){:target="_blank"}
- Migration to MahApps.Metro Version 2.x
- Migration to WebView2 (requires [Microsoft Edge Canary](https://www.microsoftedgeinsider.com/en-us/download)) [#252](http://github.com/BornToBeRoot/NETworkManager/issues/252){:target="_blank"}

## Improvements
- WebConsole
  - Untrusted SSL certificates can now be accepted [#266](http://github.com/BornToBeRoot/NETworkManager/issues/266){:target="_blank"}

## Bugfixes
- Subnet Calculator
  - Subnetting - App crash fixed if subnetmask was used [#319](http://github.com/BornToBeRoot/NETworkManager/issues/319){:target="_blank"}

## Other
  - Libraries updated

# Version 2020.5.1
Date: **12.05.2020**

| File | Checksum [SHA256]
|---|---|
|[:package: Setup](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.5.1/NETworkManager_2020.5.1_Setup.exe)| `EC5324009FABF9025A91352C542523B03AC0F55B4090A0E41721AED852A9F968` |
|[:package: Portable](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.5.1/NETworkManager_2020.5.1_Portable.zip)| `FCC6962C65CDC0ED5137ACDFD23DE97801A1ED74557426BE8AD68F6DBFD366B6` |
|[:package: Archiv](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.5.1/NETworkManager_2020.5.1_Archiv.zip)| `E0D10A9CA0E7DAE15C85AE58BB1350E139E8EF6B96D147B40B680AFEB6ED8E85` |

## Bugfixes
- Subnet Calculator
  - Subnetting view fixed
- Connections
  - View fixed
  
# Version 2020.5.0
Date: **11.05.2020**

| File | Checksum [SHA256]
|---|---|
|[:package: Setup](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.5.0/NETworkManager_2020.5.0_Setup.exe)| `B49C7C6B269F3A1B89D7F654CBEA791D4B882CD21A4D77006D5D7DFF1AA300C4` |
|[:package: Portable](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.5.0/NETworkManager_2020.5.0_Portable.zip)| `A2684C73BBBFA2AE7AE3D59A024AA5247B64DE3C002C22B6F7AA4BEA3AC9B5CE` |
|[:package: Archiv](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.5.0/NETworkManager_2020.5.0_Archiv.zip)| `9AACB3B1F0AF7D529606068E3B052C85693C9C97CB8CEBF6D4E181A29FAD06E6` |

## What's new?
- Ping view removed [#272](http://github.com/BornToBeRoot/NETworkManager/issues/272){:target="_blank"}
- Ping Monitor
  - Latency graph added [#286](http://github.com/BornToBeRoot/NETworkManager/issues/286){:target="_blank"}
- HTTP Headers removed [#276](http://github.com/BornToBeRoot/NETworkManager/issues/276){:target="_blank"}
- View improved

## Improvements
- Network Interace
  - Bandwidth graph animation disabled to increase performance
  - Graph improved
- WiFi
  - Channel graph animation disabled to increase performance
  - Graph improved
- IP Scanner
  - IPv6 support added [#283](http://github.com/BornToBeRoot/NETworkManager/issues/283){:target="_blank"}
  - Statistik removed
- Port Scanner
  - IPv6 support added [#283](http://github.com/BornToBeRoot/NETworkManager/issues/283){:target="_blank"}
  - Statistik removed
- Traceroute
  - Statistik removed
- DNS Lookup
  - Statistik removed
- PuTTY
  - Private key option added to settings, profile and connect dialog [#282](http://github.com/BornToBeRoot/NETworkManager/issues/282){:target="_blank"}
  - Log path drag and drop support added [#285](http://github.com/BornToBeRoot/NETworkManager/issues/285){:target="_blank"}
  - PuTTY profile can now contain spaces
- Command line arguments
  - Help added

## Bugfixes
- IP Scanner, Port Scanner, Ping Monitor, Traceroute, Remote Desktop, PowerShell, PuTTY, TigerVNC, WebConsole, Whois
  - Disable `Enter` key while searching for profiles [#275](http://github.com/BornToBeRoot/NETworkManager/issues/275){:target="_blank"}
- DNS Lookup
  - View fixed
- Ping Montitor
  - Searching by Host fixed
- PuTTY
  - Fixed some bugs with "Username" and "PuTTY Profile"

## Other
  - Libraries updated
  - Language files updated
    - Hungarian added

# Version 2020.4.0
Date: **21.04.2020**

| File | Checksum [SHA256]
|---|---|
|[:package: Setup](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.4.0/NETworkManager_2020.4.0_Setup.exe)| `6AA9E156ABEB79BB07574C7C076F53FE0630D69E5680A83E8E1D175E4C75E20A` |
|[:package: Portable](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.4.0/NETworkManager_2020.4.0_Portable.zip)| `36FDC504ECD9BA7E7334131909F81CE36FB91E7FB267DA53B077F95C697B4751` |
|[:package: Archiv](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.4.0/NETworkManager_2020.4.0_Archiv.zip)| `468099D5B9E8862AA6024290BD1FD375FD3A2CE9E7E4FE94AA0DDB97687E81CC` |

## What's new?
- Code has been refactored and improved to simplify future developments.
- New documentation at https://borntoberoot.github.io/NETworkManager/

## Improvements
- Network Interface
  - Button "Clear DNS cache" moved tab "Information" [#248](http://github.com/BornToBeRoot/NETworkManager/issues/248){:target="_blank"}
  - Button "Release & Renew" moved tab "Information" [#248](http://github.com/BornToBeRoot/NETworkManager/issues/248){:target="_blank"}
- PuTTY
  - PuTTY log can be enabled in the settings/profile. Session output will be saved in a file. [#278](http://github.com/BornToBeRoot/NETworkManager/issues/278){:target="_blank"}

## Bugfixes
- Settings
  - Portable modus was not displayed correctly. [#277](http://github.com/BornToBeRoot/NETworkManager/issues/277){:target="_blank"}
- Crash on Server 2019 when select WiFi fixed [#267](http://github.com/BornToBeRoot/NETworkManager/issues/267){:target="_blank"}
- Crash in IP scanner when IP address could not be detected fixed [#268](http://github.com/BornToBeRoot/NETworkManager/issues/268){:target="_blank"}

## Other
  - Libraries updated
  - Language files updated
  - Resources (OUI, Ports, Whois) updated
  - Code cleanup [#261](http://github.com/BornToBeRoot/NETworkManager/issues/261){:target="_blank"}, [#262](http://github.com/BornToBeRoot/NETworkManager/issues/262){:target="_blank"}

# Version 2020.1.0
Date: **26.01.2020**

| File | Checksum [SHA256]
|---|---|
|[:package: Setup](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.1.0/NETworkManager_2020.1.0_Setup.exe)| `A7BD0182269F012701D56285141A66279F41145F748539C7233C3129BE3765CB` |
|[:package: Portable](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.1.0/NETworkManager_2020.1.0_Portable.zip)| `BEA66D1B8E1DE820B6077FD1F98ABDF5BDD4D7CD0477FC27941EFED326DCCEAD` |
|[:package: Archiv](https://github.com/BornToBeRoot/NETworkManager/releases/download/2020.1.0/NETworkManager_2020.1.0_Archiv.zip)| `497C6DEFAD22B074B0E8D0E43948545128503512434C096D221D2978B1344F91` |

## What's new?
- Discovery Protocol - Capture LLDP and/or CDP network packages and display informations like Port, Description, VLAN, etc. [#196](http://github.com/BornToBeRoot/NETworkManager/issues/196){:target="_blank"}
- Web Console added [#244](http://github.com/BornToBeRoot/NETworkManager/issues/244){:target="_blank"}
- Settings > Appearance 
  - Transparency feature removed. Remote Desktop, PowerShell, PuTTY and TigerVNC don't work while transparency is enabled. [#220](http://github.com/BornToBeRoot/NETworkManager/issues/220){:target="_blank"}

## Improvements
- Network Interface > Bandwidth
  - Labels / values improved in the network usage section [#235](http://github.com/BornToBeRoot/NETworkManager/issues/235){:target="_blank"}
  - ToolTip improved [#219](http://github.com/BornToBeRoot/NETworkManager/issues/219){:target="_blank"}
- DNS Lookup
  - Error message now shows the ip address of the dns server [#256](http://github.com/BornToBeRoot/NETworkManager/issues/256){:target="_blank"}
- Command Line Parameter added
  - `--application:[Dashboard|IPScanner|etc.]` [#237](http://github.com/BornToBeRoot/NETworkManager/issues/237){:target="_blank"}
- After restarting the application, the last view is displayed again [#237](http://github.com/BornToBeRoot/NETworkManager/issues/237){:target="_blank"}
- Settings > Language
  - View improved [#231](http://github.com/BornToBeRoot/NETworkManager/issues/231){:target="_blank"}
- Profiles
  - Rows (profiles) should now load faster (tested with ~5k profiles)
  - Search improved on slow systems with many profiles [#227](http://github.com/BornToBeRoot/NETworkManager/issues/227){:target="_blank"}

## Bugfixes
- IP Scanner
  - Context menu redirect ro Ping Monitor [#225](http://github.com/BornToBeRoot/NETworkManager/issues/225){:target="_blank"}
  - Context menu icons are now correct [#257](http://github.com/BornToBeRoot/NETworkManager/issues/257){:target="_blank"}
- Traceroute
  - Context menu redirect ro Ping Monitor [#225](http://github.com/BornToBeRoot/NETworkManager/issues/225){:target="_blank"}
  - Context menu icons are now correct [#257](http://github.com/BornToBeRoot/NETworkManager/issues/257){:target="_blank"}
- Some bugs in the UI fixed (label, translation, placeholder, etc.) 

## Other  
  - Libary Microsoft.Toolkit.Wpf.UI.Controls.WebView added
  - Libraries updated
  - Language files updated

# Version 2019.12.0
Date: **25.12.2019**

| File | Checksum [SHA256]
|---|---|
|[:package: Setup](https://github.com/BornToBeRoot/NETworkManager/releases/download/2019.12.0/NETworkManager_2019.12.0_Setup.exe)| `C615367946A818B4E67632FA99937723B4006385D86F62F52842709DC35CBA1F` |
|[:package: Portable](https://github.com/BornToBeRoot/NETworkManager/releases/download/2019.12.0/NETworkManager_2019.12.0_Portable.zip)| `1A5A16A863425D827E1C58D711C337873C4C44B914D44F3FC27E327043597078` |
|[:package: Archiv](https://github.com/BornToBeRoot/NETworkManager/releases/download/2019.12.0/NETworkManager_2019.12.0_Archiv.zip)| `1942EF7B3541782CB83F37ED802E8FF98DD63579F5772D792462EACF82BE7E72` |

⚠️  **SYSTEM REQUIREMENTS** ⚠️ 
- Windows 10 Build 1809 
- .NET-Framework 4.7.2

## What's new

- WiFi (Networks, Channels)
- Ping Monitor
- Profile - You can now add multiple profile files and select them in the window title bar in a drop down
   - If you want to migrate your profile file from one of the pre-releases... copy the file `%appdata%\NETworkManager\Settings\Profiles.xml` to `%appdata%\NETworkManager\Profiles\Profiles.xml` or in the portable version from the `settings` folder into the new `profiles` folder.
- Version number changed from `Version 1.x.x.x` to `Version {year}.{month} Patch {number}`
- Credential feature removed
- Settings - Make portable feature removed

## Improvements
- Dashboard
  - New icon
- Network Interface - Bandwidth
  - Measure bandwidth over time
  - TooTip improved
  - Legend added
- WiFi
  - Channel - Signal strength sections added
  - Channel - Values (signal strength / channel) are visible, even if no network has been scanned yet
  - Channel - ToolTip improved
- IP Scanner 
  - New icon
  - The selected profile can be used with the `Enter` key when the search textbox or listview is in focus
  - Hostname lookup --> DNS replaced with DnsClient
- Port Scanner 
  - The selected profile can be used with the `Enter` key when the search textbox or listview is in focus
  - Hostname lookup --> DNS replaced with DnsClient
- Ping
  - The selected profile can be used with the `Enter` key when the search textbox or listview is in focus
  - Hostname lookup --> DNS replaced with DnsClient
- Ping Monitor
  - The selected profile can be used with the `Enter` key when the search textbox or listview is in focus
  - Hostname lookup --> DNS replaced with DnsClient
- Traceroute
  - Performance improved when resolving hostnames. Default DNS replaced with DnsClient for reverse lookups.
  - The selected profile can be used with the `Enter` key when the search textbox or listview is in focus
  - Hostname lookup --> DNS replaced with DnsClient
- DNS Lookup
  - Heijden.DNS replaced with DnsClient.NET
  - The selected profile can be used with the `Enter` key when the search textbox or listview is in focus
- Remote Desktop
  - Animation when closing a dialog is now smooth
  - Settings - Display - "Use current view size as screen size" is now default
  - The selected profile can be used with the `Enter` key when the search textbox or listview is in focus
- PowerShell
  - New icon
  - DPI issues fixed
  - Animation when closing a dialog is now smooth
  - The selected profile can be used with the `Enter` key when the search textbox or listview is in focus
- PuTTY
  - New icon
  - Animation when closing a dialog is now smooth
  - DPI issues fixed
  - The selected profile can be used with the `Enter` key when the search textbox or listview is in focus
- TigerVNC
  - Animation when closing a dialog is now smooth
  - DPI issues fixed
  - The selected profile can be used with the `Enter` key when the search textbox or listview is in focus
- HTTP Headers
  - The selected profile can be used with the `Enter` key when the search textbox or listview is in focus
- Whois
  - The selected profile can be used with the `Enter` key when the search textbox or listview is in focus
- Lookup
  - New icon

## Bugfixes
- IP Scanner
  - Heijden.DNS replaced with DnsClient.NET #209
- Ping Monitor
  - ScrollBar fixed

## Other
  - Language files updated
  - Resources (OUI, Ports, Whois) updated
  - Libary Heijden.DNS removed from source
  - Libary DnsClient.NET added
  - Libary Microsoft.Windows.SDK.Contracts added
  - Libraries updated
  - Some small bugfixes and improvements

---

You can find the changelog for version 1.x [here]({{ '/Archiv/Changelog-v1#version-11100' | prepend: site.baseurl }}).
