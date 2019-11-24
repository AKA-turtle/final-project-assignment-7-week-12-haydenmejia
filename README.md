# CPE 1040 - Introduction to Computer Engineering

 

## Assignment: Final Project

 

## Part I (Week 12, Assignment #7)

 

#### Week 12 - micro:bit I/O

 

### LEDs:

 

   1. The [micro:bit original-guide](original-guide.js) program utilizes  3 external LEDs of different colors that are secured  to a circuit board. The LEDs will light up, changing state one at a time. This video showcases the micro:bit program working, [micro:bit original-guide video](https://www.youtube.com/watch?v=UwvZo6rz1pk&feature=youtu.be).
   
   2. [micro:bit enable-matrix](enable-matrix.js) is a rewritten program of micro:bit original-guide that enables the LED matrix, this will display a heart and turn on/off the LEDs. Here a short video of its operation, [micro:bit enable-matrix video](http://imgur.com/gallery/ohaQHvc).
   
   3. [micro:bit twenty-eight](twenty-eight.js) is an extension of the screensaver program and adds the external LEDs into the changing patterns. Here is a link to showcase the project [micro:bit twenty-eight](http://imgur.com/gallery/VqaPnSS).
   
### Soil Sensor:

 

   1. This micro:bit digital-in project was previously released, here a video [micro:bit digital-in video](https://imgur.com/gallery/0Vkbxuh).
   
   2.  The project [micro:bit manual-calibration](manual-calibration.js) makes use of a soil sensor which returns a large value range i.e. 7-831. We then manually take this wide range and remap it to something more user friendly, 0-4. After mapping we periodically turn on power to the sensor and take a reading before turning it off soon after. This saves on power and sensor life. Then we use the reading to display 1 to 4 bars on the LED to symbolize moisture level.  [micro:bit manual calibration](http://imgur.com/gallery/YWcCOuL).
   
   3. This [micro:bit auto-calibration](auto-calibration.js) project uses the micro:bit manual-calibration program, but instead it will automatically store the soil moister values. It starts by displaying a south icon, then prompts the users to take three samples of the low and three of the high ranges. The micro:bit auto-calibration will recorded the results. It will take the average of the low and set it to the minimum range. it will also take the high average and set it to the max. It will perform the mapping, exit the calibration, then will display "calibration success," and finally it the program will operate as normal. Here is a short video of the [micro:bit auto-calibration](http://imgur.com/gallery/YWcCOuL). 
