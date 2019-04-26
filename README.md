# flutter_samsung_j4_crash

This project is a sample to show the crash occurring on Samsung J4 (and maybe many more) devices.

## MAPS API KEY

You have to pick a maps api key and place it into the Android.manifest.
DONT FORGET THAT!

You can follow the instructions on the maps library page here: https://pub.dartlang.org/packages/google_maps_flutter#-readme-tab-


## HOW TO REPRODUCE THE CRASH
1. Run the app into a Samsung J4 device. 
2. After the map loads, press the back button. 
3. Wait about 3 seconds.
4. BOOM!

This is also happening sometimes (unkown chance) when opening the keyboard on a TextField with the GoogleMap somewhere in the widget tree.