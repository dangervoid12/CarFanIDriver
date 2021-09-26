# CarFanIDriver
Controller for car radiator fans based on D1mini 

Circuit:
Batt 12v +.                          Gnd chassis 
     !                                              ! 
     !                                    |    
     ! - - - - - - - - - - - -             |
     ! - - - - - -            !             |
Fan1+        !            !              |
               Fan2 +.    !             |------
                               !             |    |
                         +            -    |
               12v to 5v conv    |
|-----------------------------+    -    |
|                                    |        |    -----------------------------D1MINI        |
|    |    |    |    |    |    
5v+     A0     Gnd    |    |    |    
|    |    |      Relay    ---------    |    
|    |    |    |    |        
|    |    |    Fan1-    Fan2 - 
|    |    |
|    |    Resistor
|    |    |
|    |---------|
|    |
|    |
Gnd    Data
Sensor
