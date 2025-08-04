<div class="page-headers">
<h1>JOSM Installation Instructions</h1>
</div>
Depending on your machine, installing JOSM can be straightforward, but sometimes it can be difficult. If you ever get stuck please contact us via our [community chat](https://discord.gg/fBw7ARTUeR) or [via email](mailto:MapYourGrid@openenergytransition.org).  These are the installation instructions we recommend:

## <div class="tools-header">Windows</div>

Installing JOSM on Windows is very easy and straightforward. Simply download the official [Windows Installer](https://josm.openstreetmap.de/download/windows/josm-setup.exe). <br> It will then be on your device, and you can go to <code> Search->Type "JOSM"-> Open the app </code>.

Running `josm-setup.exe` on Microsoft Windows performs the following:

1. Installs two executable files: `JOSM.exe` and `HWConsole.exe` in the directory `%LOCALAPPDATA%\JOSM`
2. Registers `JOSM.exe` as the default application for file extensions: `.osm`, `.geojson`, `.gpx`, `.jos`, and `.joz`
3. Places JOSM shortcut icons on the Desktop and in the Start Menu
4. Adds uninstall data in the appropriate system locations

---
If you are looking for further [instructions using the following link](https://josm.openstreetmap.de/wiki/Download#MSWindows).

## <div class="tools-header">Linux (Ubuntu and Debian)</div>

This is the recommended method for installing JOSM on Ubuntu and Debian-based systems. For other distributions, please refer to the [official instructions here](https://josm.openstreetmap.de/wiki/Download#LinuxRepositories).

To install, open your terminal using `CTRL+ALT+T`. Then copy all the following command:

```bash
echo "deb https://josm.openstreetmap.de/apt $(lsb_release -cs) universe" | sudo tee /etc/apt/sources.list.d/josm.list
wget -O- https://josm.openstreetmap.de/josm-apt.key | sudo tee /usr/share/keyrings/josm-archive-keyring.gpg
sudo apt update
sudo apt install josm
```

Afterwards copy all commands into your terminal using `CTRL+SHIFT+V` and press `Return`.

---

If this does not work, you can also install JOSM through your system’s **App Center**. We recommend using the **Snap** installation. Just search for JOSM and click install.

## <div class="tools-header">macOS</div>

To install JOSM on macOS, you’ll first need to install the Homebrew package manager. Follow the instructions at [https://brew.sh](https://brew.sh/).

After installing Homebrew, open **Terminal** by pressing `Command + Spacebar`, typing “Terminal”, and hitting `Return`.

Then run the following command:

```bash
brew install --cask josm
```

To open JOSM, press `Command + Spacebar` again, search for "JOSM", and launch it.

---

For more detailed instructions, please read the [official documentation](https://josm.openstreetmap.de/wiki/Download).



