# Customize Ubuntu
Let'scustomize :
1. [icons & themes](#icons-and-themes)
2. [desktop extensions](#desktop-extensions)
3. [Sources](#sources)
4. [Package Manager](#package-manager)

## Icons and Themes
1. create hidden folders
    + .icons
    + .themes
2. download (eg gnome-look.org) icons (full icons themes) package and theme (GTK3 themes) package
    + theme : sweet-dark
    + icons : sweet-rainbow & candy
3. extract into their hidden folders
4. install "GNOME Tweaks" app from "Ubuntu Software" store
5. apply changes to "applications" and "icons"

## Desktop Extensions
Extentions needed, it's required to install two packages to handle extentions to allow customizations.
1. sudo apt install gnome-shell-extensions chrome-gnome-shell
2. visit extensions.gnome.org
3. install the chrome plugin "GNOME Shell integration" (this allow us to install extensions for ubuntu system)
4. "Dynamic Panel Transparency" ("On" to install)
5. "Dash to Dock" (customize icons dock)

## Sources
Update and configure best sources.
1. open "software & updates"
2. "Ubuntu Software"
    + check all (except CD-ROM...)
    + "download from" select : Other > "Select Best Server"
3. "Other Software"
    + plaine "Canonical Partners" checkbox
4. "Adition drivers" > check and update
5. "close" button and "restart" option

## Package Manager
Ubuntu does not come with a package manager. Let's install Synaptic.
1. "Ubuntu Software" store > "Synaptic Package Manager"
2. open "Synaptic Package Manager" > search
    + "ubuntu-restricted-extras" (windows fonts and codexs)
    + flatpak 
        * flatpak (support more packages)
        * gnome-software-plugin-flatp
    + openjdk (a.k.a java > "openjdk-11-jdk")
    + flash (for java) "adobe-flashplugin"
3. "Mark all upgrades"
4. "Apply"
5. terminal installation > flatpak tools : sudo flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
