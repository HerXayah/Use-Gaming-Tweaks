# Use-Gaming-Tweaks
This Guide describes the Correct Usage for CHEF-KOCHS Gaming Tweaks Repo for dummies

[![Twitter URL](https://img.shields.io/twitter/url?label=Follow%20me&style=social&url=https%3A%2F%2Ftwitter.com%2FAzarielDev)](https://twitter.com/AzarielDev)
[![Discord](https://img.shields.io/discord/622504866132000768?logo=Discord)](https://discord.gg/8AyNesa)

* [Use-Gaming-Tweaks](#use-gaming-tweaks)
* [Credits](#credits)
* [Disclaimer](#disclaimer)
* [Part 1](#part-1)
* [Part 2](#part-2)
* [Part 3](#part-3)
* [Part 4](#part-4)
* [Part 5](#part-5)
* [Part 6](#part-6)
* [Part 7](#part-7)
* [Additional Tweaks](#additional-tweaks)
* [End?](#end)



# Credits

Full Credits for this go to [CHEF-KOCH](https://github.com/CHEF-KOCH) and his [GamingTweaks](https://web.archive.org/web/20200420131857/https://github.com/CHEF-KOCH/GamingTweaks) Repo <3
![Matrix](https://img.shields.io/matrix/cknews:matrix.org.svg?label=CK%27s%20Technology%20News%20-%20Matrix%20Chat&server_fqdn=matrix.org&style=popout)
![Twitter Follow](https://img.shields.io/twitter/follow/@CKsTechNews.svg?label=Follow%20%40CKsTechNews&style=social)
[![Discord](https://discordapp.com/api/guilds/418256415874875402/widget.png)](https://discord.me/CHEF-KOCH)

# Disclaimer

Im not responsible for any damage that your pc has after using these files/tweaks.
You use them on your own caution. Please do a registry backup and restore point before using the stuff i list here.

# Part 1

Do not use Tweakers and All-in-One Shit e.g AdvancedSystem Care etc etc.
Nor use these fishy Regedits from Minecraft Youtubers. If you did i advise you do a clean Install of Windows

To start now we will Tweaky Tweak Windows a bit.
You can skip the Part 1 if you want because it involves getting a better Windows Version and installing this Version.
If your willing to upgrade your Windows without loosing Data then proceed :3

What you wanna do first is open [this](https://gist.githubusercontent.com/CHEF-KOCH/7ab8229825cf6912d1a6db3a0a4f39c1/raw/ecad7acb99808d894c784b904174721fb473c9ec/esd.txt) List and scroll down to x64.
When your at x64 look for your Language code at the end, like for me, i come from Germany so i take x64fre_de-de_ if i want german language.
If you want english language ill provide a quick link for you [here](http://b1.download.windowsupdate.com/d/upgr/2020/02/19041.84.200218-1143.vb_release_svc_refresh_clientbusiness_vol_x64fre_en-gb_094ecffbbf0c70b2a9aa6038432e3b42e4f1383d.esd).

When you finished downloading it go to your C Drive and in the Folder ESD and paste the downloaded file in there.
What you wanna grab next is [wimlib-decrypter](https://github.com/abbodi1406/WHD/raw/master/scripts/esd-decrypter-wimlib-53.7z)
Unzip it in the ESD Folder and drag the .esd file you downloaded onto the decrypt.bat. A window will pop up looking like this
<p align="center">
<img src="https://nuke.bayern/1sZThUKvzy.png?key=Z1eVKdgluspqrj">
</p>
Press 2 and then 3!!! You need to select Windows Enterprise
<p align="center">
<img src="https://i.uwu.plus/qmeHscM3qQ.png?key=9ocMBydy3K8xOc">
</p>
and in the next screen Press 2 for ISO with compressed install.esd
<p align="center">
<img src="https://nuke.bayern/D6bU2JYjRV.png?key=f1GhsBJE2p3fLb">
</p>
Now just wait untill its done with decrypting. After that you should have a ISO File in the Folder.
Doubleklick it and open setup.exe
<p align="center">
<img src="https://sexin.church/BFyGG2rX2a.png?key=GstZCRTLKbPTQL">
</p>
Then choose ,,keep my Files,, and let it run and reboot you multiple times and your now on 2004 Enterprise.
What you wanna do next to get a valid liscense is this https://github.com/CHEF-KOCH/HWIDGEN-SRC/archive/master.zip
When you unzip it go into HWIDGEN-SRC-master\src\externals then open the hwid.kms38.gen.mk6.exe.
When its open do like i do here
<p align="center">
<img src="https://sexin.church/XQeNXNYCoU.gif?key=FUcwTKAAYJ4r4D">
</p>
Now your Windows should be activated :3 ❤

Now we can Continue to Part 2

# Part 2

For that open Regedit by Pressing Windows + R and then type Regedit.
When open navigate to ```HKEY_CURRENT_USER\Control Panel\Mouse```
<p align="center">
<img src="https://fuckedyour.mom/64YU4TitqG.png?key=wGopqBi8hXm6fI">
</p>
Then change the Circled Values to this
<img src="https://sexin.church/Kmozzu8yqJ.png?key=n04AQiSQHUqMAT">
Credits to CHEF-KOCH bc i stole that IMG from his Repo

After you have done that go into the Control Panel and go into mouse settings and edit them like here
<p align="center">
<img src="https://i.imgur.com/sE4uLvg.png">
</p>
*Edit: Make sure you dont change Pointer Speed

If you want something cool to have for less Input Delay go to [MouseSync](https://mousesync.com/)
When you unzip it Open the exe, let it install and then reboot.
After you rebooted set the Values like this. edit it to your own values though
<p align="center">
<img src="https://womenare.properties/jq2tRxSdwp.png?key=1wWZxre6QRs296">
</p>
How to use Credits to MouseSync.com Github-Page
- MouseDPI is DPI of the mouse

- Polling rate: Does nothing for now

- Resolution X is autofilled (eg 1920 etc etc)

- Resolution Y is autofilled (eg 1080 etc etc)

- Physical Screen X is the width of your monitor SCREEN in millimeter for that google your screen and find the active screen resolution

- Physical Screen Y is the height of your monitor SCREEN in millimeter, for that google your screen and find the active screen resolution

- Sensitivity X and Y are your Windows Sens in Mouse Settings. If this is in the Middle put 10 and if its 1 bar more left put 12 vice vera

- Extra Scale X is Sensitivity, Leave it on 1

- Extra Scale Y is Sensitivity, Leave it on 1

After that press start and wait for it to start and your done.
You need to manually open it every time though and if you wanna close it just press stop and close.

After that we move to Part 3

# Part 3

Now we come to Network and again full Credits to CHEF-KOCH here

Rightclick your Internet Adapter and do these settinghs

- Optional disable/change the following in your Network Adapter
- Disable Adaptive Inter-Frame Spacing
- Disable Flow Control
- Disable Interrupt Moderation
- Set Interrupt Moderation Rate to OFF (not needed if you disable Interrupt Moderation)
- Set Enable PME to Disabled
- Disable all “Offload” features
- Disable Packet Priority & VLAN
- Disable Jumbo Packet
- Set Receive Side Scaling (RSS) - ENABLED
- RSS Balancing Mode - NUMAScaling
- Don't touch Speed & Duplex, leave it on Auto Negotiation

then open CMD and paste this into it
```
netsh interface teredo set state disabled
netsh interface 6to4 set state disabled
netsh winsock reset
netsh interface isatap set state disable
netsh int tcp set global timestamps=disabled
netsh int tcp set heuristics disabled
netsh int tcp set global autotuninglevel=disable
netsh int tcp set global congestionprovider=ctcp
netsh int tcp set supplemental Internet congestionprovider=CTCP
netsh int tcp set global chimney=disabled
netsh int tcp set global ecncapability=disabled
netsh int tcp set global rss=enabled
netsh int tcp set global rsc=disabled
netsh int tcp set global dca=enabled
netsh int tcp set global netdma=enabled
PowerShell Disable-NetAdapterChecksumOffload -Name "*"
PowerShell Disable-NetAdapterLso -Name "*"
PowerShell Disable-NetAdapterRsc -Name "*"
PowerShell Disable-NetAdapterIPsecOffload -Name "*"
PowerShell Disable-NetAdapterPowerManagement -Name "*"
PowerShell Disable-NetAdapterQos -Name "*"
PowerShell Disable-MMAgent -MemoryCompression
```
and after that this

```bash
netsh interface teredo set state disable
netsh interface 6to4 set state disable disable
netsh interface isatap set state disable
REG ADD "HKLM\SYSTEM\CurrentControlSet\services\TCPIP6\Parameters" /v "EnableICSIPv6" /t REG_DWORD /d 0 /f
REG ADD "HKLM\SYSTEM\CurrentControlSet\services\TCPIP6\Parameters" /v "DisabledComponents" /t REG_DWORD /d 255 /f
```
and the last one is this which you need to paste into a .txt and then save it as .reg file
```
Windows Registry Editor Version 5.00

; I do not recommended using this!
; Starting with Windows 1909 this is not anymore needed.
; https://github.com/CHEF-KOCH/GamingTweaks/issues/5

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Multimedia\SystemProfile]
"NetworkThrottlingIndex"=dword:ffffffff
"SystemResponsiveness"=dword:00000000

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Multimedia\SystemProfile\Tasks\Games]
"Scheduling Category"="High"
"SFIO Priority"="High"
"Background Only"="False"2
"Priority"=dword:00000001
"Clock Rate"=dword:00002710
"GPU Priority"=dword:00000001
"Affinity"=dword:0000000
```

<p align="center">
<img src="https://i.uwu.plus/2E8g5PUPv2.png?key=UBOgqE7kOcjEum">
</p>
then just execute it.

# Part 4

Now we come to the OS Settings.
Disable and dont use any Core Unparking Software, as its pretty much useless.

Copy the following text and save it as `antitelemetry.cmd`.

```sh
@echo off
%windir%\system32\reg.exe query "HKU\S-1-5-19" 1>nul 2>nul || goto :eof
echo.
echo Anti-Telemetry blocking script
echo Some of the commands may return error(s) - you can ignore them!
reg add HKLM\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate /v DisableOSUpgrade /t REG_DWORD /d 1 /f >nul 2>&1
reg add "HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsUpdate\Auto Update" /f /v IncludeRecommendedUpdates /t REG_DWORD /d 0 >nul 2>&1
reg delete "HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsUpdate\OSUpgrade" /f >nul 2>&1
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsUpdate\OSUpgrade /v AllowOSUpgrade /t REG_DWORD /d 0 /f >nul 2>&1
reg add "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\Appraiser" /v HaveUploadedForTarget /t REG_DWORD /d 1 /f >nul 2>&1
reg add "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\AIT" /v AITEnable /t REG_DWORD /d 0 /f >nul 2>&1
reg delete "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\ClientTelemetry" /f >nul 2>&1
reg add "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\ClientTelemetry" /v DontRetryOnError /t REG_DWORD /d 1 /f >nul 2>&1
reg add "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\ClientTelemetry" /v IsCensusDisabled /t REG_DWORD /d 1 /f >nul 2>&1
reg add "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\ClientTelemetry" /v TaskEnableRun /t REG_DWORD /d 1 /f >nul 2>&1
reg delete "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\AppCompatFlags" /v UpgradeEligible /f >nul 2>&1
reg delete "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\Appraiser" /f >nul 2>&1
reg delete "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\TelemetryController" /f >nul 2>&1
reg add HKLM\SOFTWARE\Microsoft\SQMClient\IE /v CEIPEnable /t REG_DWORD /d 0 /f >nul 2>&1
reg add HKLM\SOFTWARE\Microsoft\SQMClient\IE /v SqmLoggerRunning /t REG_DWORD /d 0 /f >nul 2>&1
reg add HKLM\SOFTWARE\Microsoft\SQMClient\Reliability /v CEIPEnable /t REG_DWORD /d 0 /f >nul 2>&1
reg add HKLM\SOFTWARE\Microsoft\SQMClient\Reliability /v SqmLoggerRunning /t REG_DWORD /d 0 /f >nul 2>&1
reg add HKLM\SOFTWARE\Microsoft\SQMClient\Windows /v DisableOptinExperience /t REG_DWORD /d 1 /f >nul 2>&1
reg add HKLM\SOFTWARE\Microsoft\SQMClient\Windows /v CEIPEnable /t REG_DWORD /d 0 /f >nul 2>&1
reg add HKLM\SOFTWARE\Microsoft\SQMClient\Windows /v SqmLoggerRunning /t REG_DWORD /d 0 /f >nul 2>&1
sc.exe config DiagTrack start= disabled >nul 2>&1
sc.exe stop DiagTrack >nul 2>&1
reg delete HKLM\SYSTEM\ControlSet001\Control\WMI\AutoLogger\AutoLogger-Diagtrack-Listener /f >nul 2>&1
reg delete HKLM\SYSTEM\ControlSet001\Control\WMI\AutoLogger\Diagtrack-Listener /f >nul 2>&1
reg delete HKLM\SYSTEM\ControlSet001\Control\WMI\AutoLogger\SQMLogger /f >nul 2>&1
reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Diagnostics\DiagTrack /f >nul 2>&1
reg delete HKLM\SOFTWARE\Policies\Microsoft\Windows\DataCollection /f >nul 2>&1
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Diagnostics\DiagTrack /v DiagTrackAuthorization /t REG_DWORD /d 0 /f >nul 2>&1
takeown /f %ProgramData%\Microsoft\Diagnosis /A /r /d y >nul 2>&1
icacls %ProgramData%\Microsoft\Diagnosis /grant:r *S-1-5-32-544:F /T /C >nul 2>&1
del /f /q %ProgramData%\Microsoft\Diagnosis\*.rbs >nul 2>&1
del /f /q /s %ProgramData%\Microsoft\Diagnosis\ETLLogs\* >nul 2>&1
schtasks /Change /TN "\Microsoft\Windows\Application Experience\Microsoft Compatibility Appraiser" /DISABLE >nul 2>&1
schtasks /Change /TN "\Microsoft\Windows\Application Experience\ProgramDataUpdater" /DISABLE >nul 2>&1
schtasks /Change /TN "\Microsoft\Windows\Application Experience\AitAgent" /DISABLE >nul 2>&1
schtasks /Change /TN "\Microsoft\Windows\PerfTrack\BackgroundConfigSurveyor" /DISABLE >nul 2>&1
schtasks /Delete /F /TN "\Microsoft\Windows\Application Experience\Microsoft Compatibility Appraiser" >nul 2>&1
schtasks /Delete /F /TN "\Microsoft\Windows\Application Experience\ProgramDataUpdater" >nul 2>&1
schtasks /Delete /F /TN "\Microsoft\Windows\Application Experience\AitAgent" >nul 2>&1
schtasks /Delete /F /TN "\Microsoft\Windows\PerfTrack\BackgroundConfigSurveyor" >nul 2>&1
TIMEOUT /T 5
```
then copy this file you created to C:\Windows, open a cmd and type
```
SCHTASKS /Create /F /RU "SYSTEM" /RL HIGHEST /SC ONSTART /TN BlockW10 /TR "cmd /c %windir%\antitelemetry.cmd"
```
```
Credits to CHEF-KOCH
```

A big part is also to Disable the Windows Update Service or to set it to Manual in Services.msc

Download [this](https://vvvv.org/sites/all/modules/general/pubdlcnt/pubdlcnt.php?file=https://vvvv.org/sites/default/files/uploads/TimerToolV3.zip&nid=112931), then unzip it in a Folder and in that foler create a Txt. In that txt you paste
```
start "" "C:\PathToTool\TimerTool.exe" -t 0.5 -minimized
exit
```
after you have done this save the Txt as a .bat file, rightclick the created bat, make a shortcut.
Then press Win + R and type
```
shell:Startup
```
and paste the Shortcut you created in there.
Voila ur done

# Part 5

Drivers? If you use an NVIDIA GPU use these Drivers repacked by Chef-Koch.
To install them uninstall your old Driver with [this](https://www.wagnardsoft.com/content/ddu-guide-tutorial) Guide.
After your back to Windows open a CMD and type
```
bcdedit -set loadoptions DISABLE_INTEGRITY_CHECKS

bcdedit -set testsigning ON

shutdown.exe /r /o
```
Now install the driver with ,,Latest release,, and not ,,Pre-Release,, found [here](https://github.com/CHEF-KOCH/nVidia-modded-Inf/releases)

After it installed successfully open CMD again without rebooting and copy paste this
```
bcdedit -set loadoptions ENABLE_INTEGRITY_CHECKS

bcdedit -set TESTSIGNING OFF
```

After you have done that download [this](https://github.com/CHEF-KOCH/MSI-utility/releases/download/2.0/MSI_util_v2.zip), open it as Admin and select your GPU like i do here
<p align="center">
<img src="https://fuckedyour.doctor/s3wS5mQuJg.png?key=EM9fylDuv2B0Oj">
</p>
then press Apply and reboot

# Additional Tweaks

Open a Txt and paste these in and save them as .reg to execute them
```
Windows Registry Editor Version 5.00

; Boost the CPU priority, it's normally not nessary but on some AMD machines that can be useful
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\GTA5.exe\PerfOptions]
"CpuPriorityClass"=dword:00000003

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\gtavlauncher.exe\PerfOptions]
"CpuPriorityClass"=dword:00000005

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\subprocess.exe\PerfOptions]
"CpuPriorityClass"=dword:00000005
```
```
Windows Registry Editor Version 5.00

; Speed up the Shell and the Desktop by increasing (lowering) some timeout's
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"DesktopLivePreviewHoverTime"=dword:00000001
[HKEY_CURRENT_USER\Control Panel\Mouse]
"MouseHoverTime"="1"
[HKEY_CURRENT_USER\Control Panel\Desktop]
"MenuShowDelay"="1"
[HKEY_CURRENT_USER\Control Panel\Desktop]
"ActiveWndTrackTimeout"=dword:0000000a
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"Start_ShowRun"=dword:00000001
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer]
"NoLowDiskSpaceChecks"=dword:00000001
"LinkResolveIgnoreLinkInfo"=dword:00000001
"NoResolveSearch"=dword:00000001
"NoResolveTrack"=dword:00000001
"NoInternetOpenWith"=dword:00000001
[HKEY_CURRENT_USER\Control Panel\Desktop]
"AutoEndTasks"="1"
"HungAppTimeout"="2000"
"MenuShowDelay"="0"
"WaitToKillAppTimeout"="3000"
"LowLevelHooksTimeout"="2000"
[HKEY_LOCAL_MACHINE\SYSTEM\ControlSet002\Control]
"WaitToKillServiceTimeout"="2000"
[HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control]
"WaitToKillServiceTimeout"="2000"
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control]
"WaitToKillServiceTimeout"="2000"
```
```
Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\NvTelemetryContainer]
"Start"=dword:00000004
```
```
Windows Registry Editor Version 5.00

; Disable Shadowplay and nVidia Backend (NvBackend) (the little icon in the taskbar)

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run]
- "NvBackend"="\"C:\\Program Files (x86)\\NVIDIA Corporation\\Update Core\\NvBackend.exe\""
- "ShadowPlay"="\"C:\\Windows\\system32\\rundll32.exe\" C:\\Windows\\system32\\nvspcap64.dll,ShadowPlayOnSystemStart"
```
Credits to CHEF-KOCH again


# Part 6

Windows/Driver Debloating?

Since you can debloat Windows, ill link the Tool on how to do it.
It can be found [here](https://github.com/Sycnex/Windows10Debloater)

There is also a Way to Debloat NVIDIA Drivers, which can be found
[here](https://www.techpowerup.com/download/techpowerup-nvcleanstall/).
Its pretty Self-Explainable


# Part 7

Here are some services you can disable to get about 50 Processes on Startup, written by me also this time
https://linustechtips.com/topic/1261199-which-services-should-i-disable/?do=findComment&comment=14433444

# End?

If i find more stuff i will obv post it in here but that is it for now ❤❤


