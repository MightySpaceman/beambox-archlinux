# beambox-archlinux
Quick archlinux port of the debian-only linux release of beambox studio.

I probably won't maintain this, so here are the instructions (it takes 2 minutes)

Install debtap: `yay -S debtap`
Download the latest release of beambox studio for Ubuntu/Debain from (https://flux3dp.com/downloads/)[https://flux3dp.com/downloads/]
Navigate to the folder where it is downloaded in, and run `sudo debtap <FILENAME>.deb`
Follow the prompts, and once it is done, run `sudo pacman -U <CONVERTED-PACKAGE-FILENAME>.pkg.tar.zst`

Then run `beam-studio --disable-gpu` - remember the --disable-gpu flag to disable GPU acceleration, or it won't work...for some reason...
