# modified-iwlist
Modified version of iwlist for radio mapping

This version of iwlist records the start and end time of a 12-channel sweep across the 2.4 GHz Wi-Fi spectrum. Relating time with positions from another source, this modified version of iwlist provides the necessary input for a Wi-Fi radio map.

Usage example: ./iwlist wlan0 scan > observations.txt

(Original code and development page available at https://hewlettpackard.github.io/wireless-tools/Tools.html)
