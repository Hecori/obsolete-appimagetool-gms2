# Hello peeps
Just a PKGBUILD script i adapted from the AUR one called "appimagetool-bin" that uses the obsolete version instead of the newer one. 
The one on AUR does not seem to work with Game Maker Studio 2 so i made this to create my games.

# Running 
mkdir appgms
cd appgms
wget https://github.com/Hecori/obsolete-appimagetool-gms2/raw/refs/heads/main/PKGBUILD
makepkg -si
