The Aur installer is a program designed to complement a system that uses the pacman package manager, and allows the user to search and install from the AUR repositorys on github.
Aur installer automatically finds, installs, and builds projects in the AUR repositories, and works while a pacman installation is working (except during final steps where
it's installing.

It functions similarly to pacman in syntax, in version 1.0 3 commands function:
aur -S    //install
aur -Ss   //search
aur -H    //help
I am planning to add an update feature in the future.

Issues are KNOWN with this project in the current state, many of wich I plan to fix in the near future.
A primary one I am planning to fix soon is here
https://github.com/BlueSpaceCatno2/Aur-installer/issues/1#issue-3691114444
