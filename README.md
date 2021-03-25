# dotfiles

A collection of configuration files stored here for convenience.

# Linux Setup

Run the Setup.sh file to setup and link configurations to git

## Zsh

Use the ZSH shell

    sudo wget -O /etc/zsh/zshrc https://git.grml.org/f/grml-etc-core/etc/zsh/zshrc
    sudo chsh -s /bin/zsh

# Gnome Theme

Install the theme

    yay -S pop-icon-theme-git pop-gtk-theme-git

Set the font sizes in Tweak Tool

| Name                 | Font                | Size |
| -------------------- | ------------------- | ---- |
| Interface Font       | Fira Sans Book      | 10   |
| Document Text        | Roboto Slab Regular | 11   |
| Monospace Text       | Fira Mono Regular   | 11   |
| Legacy Window Titles | Fira Sans Medium    | 10   |

Install the terminal theme. If you have problems with the script create an new terminal profile and run the script again.

    git clone https://github.com/aaron-williamson/base16-gnome-terminal.git ~/.config/base16-gnome-terminal
    ~/.config/base16-gnome-terminal/color-scripts/base16-ocean.sh

# Windows Setup

Install the following applications:

-   [7zip](https://www.7-zip.org/download.html)
-   [Adobe Creative Cloud](https://creativecloud.adobe.com/apps/download/creative-cloud)
-   [Adobe Reader](https://get.adobe.com/reader/)
-   [Anaconda3](https://www.anaconda.com/)
-   [Atom](https://atom.io/)
-   [Blender](https://www.blender.org/)
-   [Chrome](https://www.google.com/chrome/)
-   [Docker Desktop](https://www.docker.com/products/docker-desktop)
-   [Dropbox](https://www.dropbox.com/install)
-   [Firefox](https://www.mozilla.org/en-US/firefox/new/)
-   [FreeCAD](https://www.freecadweb.org/)
-   [GIMP](https://www.gimp.org/)
-   [GitHub Desktop](https://desktop.github.com/)
-   [Gpg4win](https://www.gpg4win.org/)
-   [Inkscape](https://inkscape.org/)
-   [KeepassXC](https://keepassxc.org/)
-   [LibreOffice](https://www.libreoffice.org/)
-   [Microsoft Teams](https://teams.microsoft.com/downloads)
-   [Nmap](https://nmap.org/download.html)
-   [OpenSCAD](https://www.openscad.org/)
-   [Power Toys](https://github.com/microsoft/PowerToys)
-   [PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)
-   [Sandboxie](https://www.sandboxie.com/DownloadSandboxie)
-   [Speedcrunch](https://speedcrunch.org/)
-   [Thunderbird](https://www.thunderbird.net/en-US/)
-   [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
-   [Visual Studio Code](https://code.visualstudio.com/)
-   [VLC](https://www.videolan.org/vlc/download-windows.html)
-   [WinSCP](https://winscp.net/eng/download.php)
-   [Wireshark](https://www.wireshark.org/)

Forensics Tools:

-   [SysInternals](https://docs.microsoft.com/en-us/sysinternals/)
-   [FTK Imager](https://accessdata.com/product-download/ftk-imager-version-4-2-1)
-   [Arsenal Image Mounter](https://arsenalrecon.com/downloads/)
-   [HxD Hex Editor](https://mh-nexus.de/en/hxd/)
-   [Zimmerman Tools](https://ericzimmerman.github.io/)
-   [PhotoRec](https://www.cgsecurity.org/wiki/PhotoRec)
-   [KAPE](https://www.kroll.com/en/insights/publications/cyber/kroll-artifact-parser-extractor-kape)
-   [pdf-tools](https://blog.didierstevens.com/programs/pdf-tools/)
-   [RegRipper](https://github.com/keydet89/RegRipper2.8)
-   [Foremost](http://foremost.sourceforge.net/)
-   [GSMARTControl](https://gsmartcontrol.sourceforge.io/home/index.php/Downloads)
-   [Volatility](https://github.com/volatilityfoundation/volatility3)
-   [Plaso](https://github.com/log2timeline/plaso)
-   [TimeSketch](https://github.com/google/timesketch)
-   [DB Browser for SQLite](https://sqlitebrowser.org/dl/)

Network Security Tools:

-   [Nmap](https://nmap.org/)
-   [Wireshark](https://www.wireshark.org/)
-   [Zeek](https://www.zeek.org/)
-   [Snort](https://www.snort.org/)
-   [MITMProxy](https://github.com/mitmproxy/mitmproxy)
-   [Postman](https://www.getpostman.com/downloads/)
-   [ZAProxy](https://github.com/zaproxy/zaproxy)

Video Game Launchers

-   [Discord](https://discordapp.com/)
-   [Steam](https://store.steampowered.com/about/)
-   [Battle.net](https://www.blizzard.com/en-us/apps/battle.net/desktop)
-   [Origin](https://www.origin.com/aus/en-us/store/download)
-   [Twitch](https://www.twitch.tv/downloads)

Apps from the Windows Store

-   [Windows Terminal](https://www.microsoft.com/en-au/p/windows-terminal/9n0dx20hk701)

Drivers

-    [Nvidia Drivers](https://www.nvidia.com/Download/index.aspx?lang=en-us)

## Winget

    TODO This section

## Scoop

Install scoop. Note: if you get an error you might need to change the execution policy

    iwr -useb get.scoop.sh | iex

Install some utilities common on Linux

    scoop install git curl aria2 busybox xpdf-tools shellcheck diffutils bind dirhash exiftool file findutils gawk hashcat imagemagick openssl perl which yara

## WSL (alternative to running scoop)

Install WSL2

    dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
    dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
    wsl --set-default-version 2

Open Windows store to install Debian or Ubuntu:

    [Ubuntu 20.04 LTS](https://www.microsoft.com/en-au/p/ubuntu-2004-lts/9n6svws3rx71)
    [Debian](https://www.microsoft.com/en-au/p/debian/9msvkqc78pk6)

Post Installation configuration

    # Update system
    sudo apt update && sudo apt dist-upgrade
    sudo apt install libimage-exiftool-perl yara python3-pip xpdf zsh shellcheck wget curl vim unzip imagemagick

    # Fix PIP paths
    echo "export PATH=\"${HOME}/.local/bin:$PATH\"" >>"${HOME}"/.bashrc
    echo "alias pip=pip3" >> ~/.bashrc
    sudo ln -s /usr/bin/python3 /usr/bin/python

    # Fix the bell
    echo "set bell-style none" >> ~/.inputrc

    # ZSH config
    sudo wget -O /etc/zsh/zshrc https://git.grml.org/f/grml-etc-core/etc/zsh/zshrc
    sudo chsh -s /bin/zsh

Python Tools

    pip install pdfx peepdf olefile

Install Didier Stevens Tools

    # PDF-Parser
    wget -O ~/.local/bin/pdf-parser.py https://raw.githubusercontent.com/DidierStevens/DidierStevensSuite/master/pdf-parser.py && chmod +x ~/.local/bin/pdf-parser.py
    ln -s ~/.local/bin/pdf-parser.py ~/.local/bin/pdf-parser

    # OleDump
    wget -O /tmp/oledump.zip https://didierstevens.com/files/software/oledump_V0_0_60.zip && unzip -e -d ~/.local/bin /tmp/oledump.zip && chmod +x ~/.local/bin/oledump.py
    ln -s ~/.local/bin/oledump.py ~/.local/bin/oledump

    # PDFID
    wget -O /tmp/pdfid.zip https://didierstevens.com/files/software/pdfid_v0_2_7.zip && unzip -e -d ~/.local/bin /tmp/pdfid.zip && chmod +x ~/.local/bin/pdfid.py
    ln -s ~/.local/bin/pdfid.py ~/.local/bin/pdfid


## Windows Terminal Theme

Set [Windows Terminal color](https://nerdschalk.com/how-to-change-color-in-windows-terminal/)

# Firefox Setup

link Firefox_user.js to `~/.mozilla/firefox/\*.default/user.js`.

<!-- Based upon [This](https://github.com/pyllyukko/user.js) user.js file -->

with some tweaks.

Optionally enable resist fingerprinting in about:config

    privacy.resistFingerprinting = true

## Firefox Addons

The following Firefox addons are also installed for security:

-   [Decentraleyes](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/)
-   [Firefox Multi-Account Containers](https://addons.mozilla.org/en-GB/firefox/addon/multi-account-containers/)
-   [KeePassXC-Browser](https://addons.mozilla.org/en-US/firefox/addon/keepassxc-browser/)
-   [NoScript](https://addons.mozilla.org/en-US/firefox/addon/noscript/?src=search)
-   [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)

# Atom Setup

Good packages

    apm install atom-beautify indent-guide-improved file-icons auto-detect-indentation busy-signal highlight-selected minimap minimap-highlight-selected intentions intentions-colorpicker split-diff sort-lines sublime-style-column-selection

Autocomplete packages

    apm install autocomplete-python autocomplete-xml autocomplete-math

Linter packages

    apm install linter linter-ui-default linter-clang linter-flake8 linter-lintr linter-markdown linter-php linter-pydocstyle linter-shellcheck linter-stylelint linter-xmllint
