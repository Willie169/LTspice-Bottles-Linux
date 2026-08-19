# LTspice-Bottles-Linux

1. Go to <https://www.analog.com/en/resources/design-tools-and-calculators/ltspice-simulator.html>.
2. Click **Download for Windows 10/11 x64**. You will get `LTspice64.msi`. A copy of it compressed as tar.xz and split into [`LTspice64.msi.tar.xz.part.000`](LTspice64.msi.tar.xz.part.000), [`LTspice64.msi.tar.xz.part.001`](LTspice64.msi.tar.xz.part.001), [`LTspice64.msi.tar.xz.part.002`](LTspice64.msi.tar.xz.part.002), and [`LTspice64.msi.tar.xz.part.003`](LTspice64.msi.tar.xz.part.003) is in this repo, which is made solely for archiving purpose is subjected to its own copyright status.
3. Create an Application Bottles in Bottles.
4. If you haven't install Flatpak, install it: (Ubuntu/Debian for example)
  ```
  sudo apt update
  sudo apt install flatpak -y
  ```
  add Flathub:
  ```
  sudo flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
  ```
  and reboot:
  ```
  sudo reboot
  ```
5. Install Bottles:
  ```
  flatpak install flathub com.usebottles.bottles
  ```
6. Launch Bottles:
  ```
  flatpak run com.usebottles.bottles
  ```
7. If `(ERROR) Unable to load libGLX_nvidia.so.0`, run
  ```
  flatpak update -y
  ```
  and launch Bottles again.
8. Click plus sign in the top left corner to Create New Bottles.
9. Give it a name, e.g., LTspice.
10. If the Runner shows `mcsoda-*`, change it to `protosoda-*`.
11. Click Create.
12. Click the Bottle.
13. Click Browse C:/ drive, move `LTspice64.msi` into it.
14. Click Add Shortcuts..., select `drive_c/LTspice64.msi`.
15. Run `LTspice64` listed in Programs.
16. Follow LTspice Setup to install LTspice.
17. Click Add Shortcuts..., select `drive_c/Program Files/ADI/LTspice/LTspice.exe`. A copy of the ADI folder compressed as tar.xz and split into [`ADI.tar.xz.part.000`](ADI.tar.xz.part.000), [`ADI.tar.xz.part.001`](ADI.tar.xz.part.001), and [`ADI.tar.xz.part.002`](ADI.tar.xz.part.002) is in this repo, which is made solely for archiving purpose is subjected to its own copyright status.
18. Done. Run `LTspice` listed in Programs to launch LTspice. Click No if it asks you to update.

