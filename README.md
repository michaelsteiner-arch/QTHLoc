# QTHLoc
Python Script to calculate distance and bearing to other amateur radio station

This claas you can use in your own python program.  
It contains 3 functions:  
ConvLocToDeg   Converts max. 6 digits long QTH Locator into longitudinal and latitudinal values in degrees  
ConvLocToRad   As above, but in radians. Is used by CalcDistBear.  
CalcDistBear   Takes as Arguments 2 QTH locators and returns distance in Km and direction (bearing) in degrees.

Little error occours, because earth is not taken as elipsoid as in reality.
Correction will follow in next version.
