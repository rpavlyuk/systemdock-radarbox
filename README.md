# Radarbox on SystemDock
SystemDock (https://github.com/rpavlyuk/systemdock) wrapper for RadarBox (https://www.radarbox.com/) docker container to run it as SystemD service. The container itself is maintained by third-party projects: https://github.com/mikenye/docker-radarbox

 # Installation and Usage
 * Install SystemDock by following instructions from https://github.com/rpavlyuk/systemdock
 * Get the source code:
 ```
 git clone https://github.com/rpavlyuk/systemdock-radarbox && cd systemdock-radarbox
 ```
 * Install the profile:
 ```
 sudo make install
 ```
 * You can build and install the RPM package if you're using RPM-based Linux distro:
 ```
 sudo make install-rpm && sudo make clean
 ```
