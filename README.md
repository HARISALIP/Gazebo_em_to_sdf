# Gazebo_em_to_sdf
gazebo


harisali@ubuntu:~/Downloads$ empy3 configurable_pallet_rack.sdf.em > model.sdf

Sdf to 
World file

haris@haris-HP-Pavilion-Laptop-15t-xx000:~$ export GAZEBO_MODEL_PATH=/usr/share/gazebo-11/modeles/

haris@haris-HP-Pavilion-Laptop-15t-xx000:~$ sudo gazebo plant.world

[sudo] password for haris: 

ALSA lib pcm_dmix.c:1032:(snd_pcm_dmix_open) unable to open slave
AL lib: (EE) ALCplaybackAlsa_open: Could not open playback device 'default': Device or resource busy
^Z
[1]+  Stopped                 sudo gazebo plant.world

haris@haris-HP-Pavilion-Laptop-15t-xx000:~$ sudo killall -9 gazebo gzserver gzclient
haris@haris-HP-Pavilion-Laptop-15t-xx000:~$ export GAZEBO_MODEL_PATH=/usr/share/gazebo-11/models/
haris@haris-HP-Pavilion-Laptop-15t-xx000:~$ sudo gazebo plant.world
ALSA lib pcm_dmix.c:1032:(snd_pcm_dmix_open) unable to open slave
AL lib: (EE) ALCplaybackAlsa_open: Could not open playback device 'default': Device or resource busy




