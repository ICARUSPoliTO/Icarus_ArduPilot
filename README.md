To set ardupilot up:<br />
- clone the repo using: <br />
  git clone --recurse-submodules \<url\>
- from terminal, in the installation folder:<br />
  Tools/environment_install/install-prereqs-ubuntu.sh -y<br />
  ~/.profile <br />
  ./waf configure <br />

To start ardupilot: <br />
    sim_vehicle.py -v \<vehicle type\> -f \<frame name\> --model JSON --console --map
