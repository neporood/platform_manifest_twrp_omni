Minimal Manifest for building TWRP Using OMNIROM Source
------------------

To initialize your local repository using the OMNIROM trees to build TWRP, use a command like this:

    repo init -u git://github.com/neporood/twrp_omni.git -b twrp-6.0

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; lunch omni_<device>-eng; mka recoveryimage
