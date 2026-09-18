# muOS-Trimui-Smart-Pro-Stick-Fix
There is a bug when pressing up fully on the sticks on the Trimui Smart Pro with muOS. This is a two file fix that replaces the middle man between the physical hardware and the OS and allows for proper stick processing and calibration.


# Installation Instruction
1. Extract the TSP_Controller_Patch.sh file to the Roms/ports folder on your SD card
2. Extract the tsp-controller-experimental folder to the MUOS folder on your SD card
3. Put the SD card back in your console
4. Open the TSP_Controller_Patch in the ports folder
5. Run the stick calibration by pressing the A button
6. Do not touch the sticks a few seconds to allow the center of the stick to calibrate
7. After seeing the message asking you to spin your sticks around the edge, start spinning them at a medium pace
8. If you see your stick jittering in the center of the stick visualizer calibrate a dead zone using the D-pad by adding a percentage point and then spinning the stick a few times and seeing if it stays steady at centered, 7% seems to be good for both of my sticks
9. After completing that it should say Successful in green in the top right corner
10. Press the X button to Install the patch
11. Test it out in a game and see if it works
12. Try the calibration again if you still have issues

If you have any problems with setting it up or running it feel free to report an issue here.
