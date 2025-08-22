# Hello peeps
Just a PKGBUILD script i adapted from the AUR one called "appimagetool-bin" that uses the obsolete version instead of the newer one. 
The one on AUR does not seem to work with Game Maker Studio 2 so i made this to create my games.

!!! This is not actually a package. !!!
It is more like a script that could be turned into a package by someone at the community, if you intend to do that i would recommend using "appimagekit-bin" as the package name to differenciate from the "appimagetool-bin".

# Running 
  mkdir appgms  
  cd appgms  
  wget https://github.com/Hecori/obsolete-appimagetool-gms2/raw/refs/heads/main/PKGBUILD  
  makepkg -si  

# Removing
  sudo rm /usr/local/bin/appimagetool
  sudo pacman -Rd --nodeps appimagekit-bin  
