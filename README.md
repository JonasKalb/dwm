# dwm
This is my configuration for the Suckless software dwm.

# Install
git clone https://github.com/JonasKalb/dwm.git
cd dwm
sudo make clean install

Add to xinit file:
while true; do
  dwm >/dev/null 2>&1
done
exec dwm

Press shift+alt+q to restart dwm.
