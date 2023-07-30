# mpv mediaplayer snap with a main focus on Wayland support
\
Configuration files can be placed under /home/$USER/snap/mpv-wayland/common/.config/mpv/ directory.  
YouTube should work out of the box.

___
Allow access to /media, /run/media and /mnt:

snap connect mpv-wayland:removable-media
