
INSTALLATION
============

Just un-zip the files in 1 folder.
Firsttime: execute installUdevRules.sh in terminal window! This only need to be executed once.
This will add a Udev rule so Vmarker sensors are accessable by the FirmwareUpdate and the VmarkerUtility tool.

To start the VmarkerUtility just execute 'startUtility.sh'
This version will automatically connect to the Vmarker sensor II when there is one connected to the computer.

If the application doesn't open, probably there is no Vmarker with correct firmware connected, or the UdevRules are not correct.
Run installUdevRules.sh and restart the computer, and try again.

