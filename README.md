the io3360 zip is a through hole pcb and instructions designed in fritzing to convert the intellimouse optical 1.1 and wheel mouse optical to a pmw3360 by using the jkicklighter board on tindie and a teensy 2.0. It works fine as my daily driver although all it does is add weight. If you wanted to use the files a lighter approach would be to cut off the pcb in fritzing and add in wire holes, like how the ninox classic intellimouse is done on youtube.


the mouse8 folder is a work in progress similar project in kicad 6.0 nightly build using all surface mount parts, aiming for a lighter weight and lower cost. I uploaded the files so interested parties could submit bugfixes and comments. as of yet there are no successful builds, due to slow shipping times and tight budgets on my end. 

The gerbers are complete, although I am still finding critical errors on a weekly basis. the 3360 footprint is proprietary so I could not release it. it is freely available if hunted down though, as are the microswitch and ec10 footprints. 
if anyone cares to make a libre one I will add it here.

I moved the sensor forward for this build, only time will tell if that was the right decision. It is still possible to move it farther with a redesign, although I did not want to change it too much.

The pullup resistors are optional, 10k is recommended for the wheel and a pair of 5k for each microswitch. I recommend not using an ultrabright led as it will exceed the safe average current limits of the mcu pin driving it. it is there merely as a power on indicator.
