# Windows Desktop Setup

# Debloat 
Run the following debloat too then also run the functions in [Win10-Setup.ps1](Win10-Setup.ps1)

    iwr -useb https://git.io/debloat|iex

# Software

## General Tools

|Application|Winget ID|
|-----------|-----------|
|[7zip](https://www.7-zip.org/download.html) |winget install -e --id 7zip.7zip|
|[Adobe Reader](https://get.adobe.com/reader/)||
|[Calibre Ebook](https://calibre-ebook.com/download_windows64)|winget install -e --id calibre.calibre|
|[Chrome](https://www.google.com/chrome/)|winget install -e --id Google.Chrome|
|[Dropbox](https://www.dropbox.com/install)|winget install -e --id Dropbox.Dropbox|
|[Firefox](https://www.mozilla.org/en-US/firefox/new/)|winget install -e --id Mozilla.Firefox|
|[KeepassXC](https://keepassxc.org/)|winget install -e --id KeePassXCTeam.KeePassXC|
|[Kindle](https://www.amazon.com.au/kindle-dbs/fd/kcp)||
|[OBSStudio](https://obsproject.com/)|winget install -e --id OBSProject.OBSStudio|
|[Power Toys](https://github.com/microsoft/PowerToys)|winget install -e --id Microsoft.PowerToys|
|[ProtonVPN](https://protonvpn.com/download)|winget install -e --id ProtonTechnologies.ProtonVPN|
|[Speedcrunch](https://speedcrunch.org/)|winget install -e --id SpeedCrunch.SpeedCrunch|
|[VLC](https://www.videolan.org/vlc/download-windows.html)|winget install -e --id VideoLAN.VLC|
|[WinDirStat](https://windirstat.net/)|winget install -e --id WinDirStat.WinDirStat|
|[Windows Remote Desktop](https://www.microsoft.com/en-au/p/microsoft-remote-desktop/9wzdncrfj3ps)|winget install -e --id Microsoft.RemoteDesktop_8wekyb3d8bbwe|
|[Windows Terminal](https://aka.ms/terminal)|winget install -e --id Microsoft.WindowsTerminal|

## Office Applications

|Application|Winget ID|
|-----------|-----------|
|[LibreOffice](https://www.libreoffice.org/)|winget install --id TheDocumentFoundation.LibreOffice|
|[Microsoft Teams](https://teams.microsoft.com/downloads)|winget install -e --id Microsoft.Teams|
|[Microsoft Office]()|winget install -e --id Microsoft.Office|
|[Microsoft Onedrive]()|winget install -e --id Microsoft.OneDrive|

## Messaging Applications

|Application|Winget ID|
|-----------|-----------|
|[Discord](https://discordapp.com/)|winget install -e --id Discord.Discord|
|[Gpg4win](https://www.gpg4win.org/)|winget install -e --id GnuPG.Gpg4win|
|[Microsoft Teams](https://teams.microsoft.com/downloads)|winget install -e --id Microsoft.Teams|
|[Telegram](https://desktop.telegram.org/)|winget install -e --id Telegram.TelegramDesktop|
|[Thunderbird](https://www.thunderbird.net/en-US/)|winget install -e --id Mozilla.Thunderbird|
|[WhatsApp](https://www.whatsapp.com/download/?lang=en)|winget install -e --id WhatsApp.WhatsApp|
|[Zoom](https://zoom.us/support/download)|winget install -e --id Zoom.Zoom|

## Creative Tools

|Application|Winget ID|
|-----------|-----------|
|[Adobe Creative Cloud](https://creativecloud.adobe.com/apps/download/creative-cloud)||
|[Blender](https://www.blender.org/)|winget install -e --id BlenderFoundation.Blender|
|[Darktabke](https://www.darktable.org/install/)|winget install -e --id darktable.darktable|
|[FreeCAD](https://www.freecadweb.org/)|winget install -e --id FreeCAD.FreeCAD|
|[GIMP](https://www.gimp.org/)|winget install -e --id GIMP.GIMP|
|[Handbrake](https://handbrake.fr/downloads.php)|winget install -e --id HandBrake.HandBrake|
|[Hugin](http://hugin.sourceforge.net/download/)|winget install -e --id Hugin.Hugin|
|[Inkscape](https://inkscape.org/)|winget install -e --id Inkscape.Inkscape|
|[Luminance HDR](http://qtpfsgui.sourceforge.net)||
|[OpenSCAD](https://www.openscad.org/)|winget install -e --id OpenSCAD.OpenSCAD|

## Audio Tools

|Application|Winget ID|
|-----------|-----------|
|[Audacity](https://www.audacityteam.org/?ref=winstall)|winget install -e --id=Audacity.Audacity|
|[Equalizer APO](https://equalizerapo.com/download.html)
|[Lisp VST Plugin](https://plugins4free.com/plugin/1662/)
|[Nvidia Broadcast](https://www.nvidia.com/en-au/geforce/broadcasting/broadcast-app/)|winget install -e --id Nvidia.Broadcast|
|[ReaPlugs](https://www.reaper.fm/reaplugs/)

## Development Tools

|Application|Winget ID|
|-----------|-----------|
|[Anaconda3](https://www.anaconda.com/products/individual)|winget install -e --id Anaconda.Anaconda3|
|[Atom](https://atom.io/)|winget install -e --id GitHub.Atom|
|[AWS CLI](https://awscli.amazonaws.com/AWSCLIV2.msi)|winget install -e --id Amazon.AWSCLI|
|[Git](https://git-scm.com/downloads)|winget install -e --id Git.Git|
|[GitHub Desktop](https://desktop.github.com/)|winget install -e --id GitHub.GitHubDesktop|
|[PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)|winget install -e --id PuTTY.PuTTY|
|[RaspberryPi Imager](https://www.raspberrypi.com/software/)|winget install -e --id RaspberryPiFoundation.RaspberryPiImager|
|[RunJS](https://runjs.app/?ref=winstall)|winget install -e --id lukehaas.RunJS|
|[Virtualbox](https://www.virtualbox.org/wiki/Downloads)|winget install -e --id Oracle.VirtualBox|
|[Visual Studio Code](https://code.visualstudio.com/)|winget install -e --id Microsoft.VisualStudioCode|
|[VMWare Workstation](https://www.vmware.com/au/products/workstation-pro/workstation-pro-evaluation.html)
|[WinSCP](https://winscp.net/eng/download.php)|winget install -e --id WinSCP.WinSCP|

## Forensics Tools

|Application|Winget ID|
|-----------|-----------|
|[Arsenal Image Mounter](https://arsenalrecon.com/downloads/)
|[DB Browser for SQLite](https://sqlitebrowser.org/dl/)|winget install -e --id DBBrowserForSQLite.DBBrowserForSQLite|
|[Foremost](http://foremost.sourceforge.net/)
|[FTK Imager](https://accessdata.com/product-download/)
|[GSMARTControl](https://gsmartcontrol.sourceforge.io/home/index.php/Downloads)|winget install -e --id GSmartControl.GSmartControl|
|[HxD Hex Editor](https://mh-nexus.de/en/hxd/)
|[KAPE](https://www.kroll.com/en/insights/publications/cyber/kroll-artifact-parser-extractor-kape)
|[Maltego](https://www.maltego.com/downloads/)
|[pdf-tools](https://blog.didierstevens.com/programs/pdf-tools/)
|[PhotoRec](https://www.cgsecurity.org/wiki/PhotoRec)
|[Plaso](https://github.com/log2timeline/plaso)
|[RegRipper](https://github.com/keydet89/RegRipper2.8)
|[SysInternals](https://docs.microsoft.com/en-us/sysinternals/)
|[TimeSketch](https://github.com/google/timesketch)
|[Volatility](https://github.com/volatilityfoundation/volatility3)
|[Zimmerman Tools](https://ericzimmerman.github.io/)

## Network Security Tools

|Application|Winget ID|
|-----------|-----------|
|[MITMProxy](https://github.com/mitmproxy/mitmproxy)|winget install -e --id mitmproxy.mitmproxy|
|[Nmap](https://nmap.org/)|winget install -e --id Insecure.Nmap|
|[Postman](https://www.getpostman.com/downloads/)|winget install -e --id Postman.Postman|
|[Snort](https://www.snort.org/)
|[Wireshark](https://www.wireshark.org/)|winget install -e --id WiresharkFoundation.Wireshark|
|[ZAProxy](https://github.com/zaproxy/zaproxy)|winget install -e --id OWASP.ZAP|
|[Zeek](https://www.zeek.org/)

## Video Game Launchers

|Application|Winget ID|
|-----------|-----------|
|[Battle.net](https://www.blizzard.com/en-us/apps/battle.net/desktop)
|[CurseForge](https://download.curseforge.com/)||
|[Origin](https://www.origin.com/aus/en-us/store/download)|winget install -e --id ElectronicArts.EADesktop|
|[Steam](https://store.steampowered.com/about/)|winget install -e --id Valve.Steam|
|[Twitch](https://www.twitch.tv/downloads)|winget install -e --id Twitch.Twitch|

## Drivers

|Application|Winget ID|
|-----------|-----------|
|[AMD Chipset Drivers](https://www.amd.com/en/support)
|[Canon EOS Webcam Utility](https://www.canon.com.au/services-and-apps/eos-webcam-utility)
|[Logitech Capture](https://www.logitech.com/en-au/product/capture)
|[Logitech Options](https://www.logitech.com/en-au/product/options)|winget install -e --id Logitech.Options|
|[Nvidia Drivers](https://www.nvidia.com/Download/index.aspx?lang=en-us)
|[WinBtrfs](https://github.com/maharmstone/btrfs)

# Winget

Update supported apps

    winget upgrade --all

# Powershell Setup of additional tools

    Install-Module -Name ExchangeOnlineManagement
    Add-WindowsCapability –online –Name Rsat.ActiveDirectory.DS-LDS.Tools~~~~0.0.1.0
    Add-WindowsCapability -Online -Name Rsat.ServerManager.Tools~~~~0.0.1.0
    Add-WindowsCapability -Online -Name Rsat.BitLocker.Recovery.Tools~~~~0.0.1.0
    Enable-WindowsOptionalFeature -FeatureName "Containers-DisposableClientVM" -All -Online -NoRestart
    Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All -NoRestart

Then enable the following manually

    Core Isolation

# Sysinternals

This script will fetch the latest sysinternals and places it in the build directory. Doubles as an updater too.

    New-Item -Path $HOME\Build -ItemType directory
    New-Item -Path $HOME\Build\SysInternals -ItemType directory
    cd $HOME\Build\SysInternals
    Remove-Item $HOME\Build\SysInternals\*
    Invoke-WebRequest -Uri https://download.sysinternals.com/files/SysinternalsSuite.zip -OutFile SysinternalsSuite.zip
    Expand-Archive -Path SysinternalsSuite.zip -DestinationPath .
    Remove-Item SysinternalsSuite.zip
    $SdeletePath = "$HOME\Build\SysInternals\sdelete.exe"
    Start-Process PowerShell.exe -ArgumentList "copy $SdeletePath C:\Windows\" -Wait -Verb RunAs

# OpenSSH client on Windows

    # Install OpenSSH
    Add-WindowsCapability -Online -Name OpenSSH.Client*
    Set-Service ssh-agent -StartupType Automatic
    Start-Service ssh-agent

Add the workaround for ssh-agent, details [here](https://github.com/PowerShell/Win32-OpenSSH/issues/1234):

    Add-WindowsCapability -Online -Name OpenSSH.Server*
    Set-Service sshd -StartupType Disabled

# Windows Terminal Configuration

Set [Windows Terminal color](https://nerdschalk.com/how-to-change-color-in-windows-terminal/)

    "profiles": {
      "defaults": {
        // Put settings here that you want to apply to all profiles.
        "colorScheme": "One Half Dark"
      },

Add some profiles

        {
          "name": "Debian AWS Cloud Shell",
          "commandline": "wsl -d debian aws-shell",
          "hidden": false,
          "suppressApplicationTitle": true
        },
        {
          "name": "SSH - server",
          "commandline": "ssh server",
          "hidden": false,
          "suppressApplicationTitle": true
        },
        {
          "name": "O365 Exchange Online",
          "commandline": "powershell.exe -NoExit Connect-ExchangeOnline",
          "hidden": false,
          "suppressApplicationTitle": true
        },
        {
          "name": "O365 Security & Compliance Centre",
          "commandline": "powershell.exe -NoExit Connect-IPPSSession",
          "hidden": false,
          "suppressApplicationTitle": true
        },

# WSL2

Install WSL2

    dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
    dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart

Restart

    wsl --set-default-version 2

Open Windows store to install Debian or Ubuntu:

-   [Ubuntu 20.04 LTS](https://www.microsoft.com/en-au/p/ubuntu-2004-lts/9n6svws3rx71)
-   [Debian](https://www.microsoft.com/en-au/p/debian/9msvkqc78pk6)

Post Installation configuration

    # Update system
    sudo apt update && sudo apt dist-upgrade
    sudo apt install libimage-exiftool-perl yara python3-pip xpdf zsh shellcheck wget curl vim unzip imagemagick awscli podman

    # TODO
    # Make the WSL subnet static so it doesnt collide with real ips
    # Also fix the issues with VPN's

    # ZSH config
    sudo wget -O /etc/zsh/zshrc https://git.grml.org/f/grml-etc-core/etc/zsh/zshrc
    sudo chsh -s /bin/zsh $USER
    sudo chsh -s /bin/zsh root
    ln -s ~/.profile ~/.zprofile
    zsh

    # Fix PIP paths
    echo "export PATH=\"${HOME}/.local/bin:$PATH\"" >>"${HOME}"/.bashrc
    echo "alias pip=pip3" >> ~/.bashrc
    echo "alias pip=pip3" >> ~/.zshrc
    sudo ln -s /usr/bin/python3 /usr/bin/python

    # Disable including windows paths
    sudo sh -c 'echo "[interop]" >> /etc/wsl.conf'
    sudo sh -c 'echo  "enabled=false" >> /etc/wsl.conf'
    sudo sh -c 'echo  "appendWindowsPath=false" >> /etc/wsl.conf'

    # Fix the bell
    echo "set bell-style none" >> ~/.inputrc

    # Fix Podman
    echo -e "[registries.search]\nregistries = ['docker.io', 'quay.io']" | sudo tee /etc/containers/registries.conf
    sudo sh -c 'echo "events_logger = \"file\"" >> /etc/containers/containers.conf'
    sudo sh -c 'echo "net.ipv4.ip_unprivileged_port_start=0" >> /etc/sysctl.conf'
    sudo sysctl -p

Python Tools

    pip install pdfx peepdf olefile mupdf mupdf-tools

Install Didier Stevens Tools

    # PDF-Parser
    wget -O ~/.local/bin/pdf-parser.py https://raw.githubusercontent.com/DidierStevens/DidierStevensSuite/master/pdf-parser.py && chmod +x ~/.local/bin/pdf-parser.py
    ln -s ~/.local/bin/pdf-parser.py ~/.local/bin/pdf-parser

    # OleDump
    wget -O /tmp/oledump.zip https://didierstevens.com/files/software/oledump_V0_0_75.zip && unzip -e -d ~/.local/bin /tmp/oledump.zip && chmod +x ~/.local/bin/oledump.py
    ln -s ~/.local/bin/oledump.py ~/.local/bin/oledump

    # PDFID
    wget -O /tmp/pdfid.zip https://didierstevens.com/files/software/pdfid_v0_2_7.zip && unzip -e -d ~/.local/bin /tmp/pdfid.zip && chmod +x ~/.local/bin/pdfid.py
    ln -s ~/.local/bin/pdfid.py ~/.local/bin/pdfid

    # PDFTool
    wget -O ~/.local/bin/pdftool.py https://raw.githubusercontent.com/DidierStevens/DidierStevensSuite/master/pdftool.py && chmod +x ~/.local/bin/pdftool.py
    ln -s ~/.local/bin/pdftool.py ~/.local/bin/pdftool