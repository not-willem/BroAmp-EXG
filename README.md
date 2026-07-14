<p align="center">
  <img src="https://github.com/not-willem/BroAmp-EXG/blob/main/logo.png" alt="logo">
</p>

# BroAmp EXG
a decent sized bio amp so i can wire it myself and so that it will be cheaper to produce unlike the other ones on the market <img src="https://emoji.slack-edge.com/T09V59WQY1E/ultrafastparrot/40d59f6df4da8934.gif" alt="partyparrot" width="20"/>

go to the website i made [here](https://not-willem.github.io/BroAmp-EXG/)

# overview
BroAmp EXG is an open-source project created by yours truly that allows you to turn different body functions that produce a small amount of electricity and amplify them into a more readable signal.

## features <img src="https://emoji.slack-edge.com/T09V59WQY1E/woooo/da7f7c8575baa744.gif" alt="wow" width="20"/>
 - same as the BioAmp EXG Pill just easier to produce using cheap parts
 - can do EEG (activity in parts of the brain), EMG (muscle activity, e.g when you move your hand), ECG (heart rate detection) and EOG (eye blink detection)
 - i think you could probably use it for more but thats all that it was listed for on the original page
 - it can send the data back to pretty much any microcontroller with an analog input (ADC)
 - you can configure the gain, bandpass, filter and electrodes all on the board itself

## documentation <img src="https://emoji.slack-edge.com/T09V59WQY1E/thumbs-up/e974300682924889.png" alt="thumbs up" width="20"/>
 - original project: [here](https://github.com/upsidedownlabs/BioAmp-EXG-Pill)
 - date of modifications: June 2026
 - i have made the capacitors and resistors larger to make it easier to hand solder/machine
 - i have changed the board dimensions to 36.5 mm x 48 mm to again, make it easier to hand solder/machine
 - i have kept the same licsense on the hardware (CERN OHL S v2)
 - i have acknowledged the source on the silkscreen
 - the complete source for the modified design is in this github that you're reading this from

## using the project files
To use the project files provided, download them using the green "Code" button at the top of the page, then Download Zip. All the PCB production files are kept in the "production" folder apart from the BOM.csv which is kept in the main folder. 

## production notes
the only thing you should need to do more micro-soldering for is the main chip itself and the electrodes and bandpass filters. these are optional and you will need to micro solder that on but they are for configuration, which, to be fair you could probably also do on the microcontroller itself. The components can simply be hand soldered and they are spaced apart well enough to not short out in case the wires are touching if you've gotten a bigger capacitor/resistor

thanks to the project by [upsidedownlabs](https://github.com/upsidedownlabs/BioAmp-EXG-Pill) because it was super good and cool. <img src="https://emoji.slack-edge.com/T09V59WQY1E/pepo-clap/3c28429c14af947a.gif" alt="clapping" width="20"/>

software demos [here](https://github.com/upsidedownlabs/BioAmp-EXG-Pill#software)

you can find the pcb files in the production folder

and [here](https://github.com/not-willem/BroAmp-EXG/blob/main/BOM%20and%20notes.csv) some notes and a BOM that you can put straight into LCSC to get the parts

but yeah heres some photos

![front](https://github.com/not-willem/BroAmp-EXG/blob/main/imagesforreadme/jnjnjnjnjnjn.png)
oh hello there
![back](https://github.com/not-willem/BroAmp-EXG/blob/main/imagesforreadme/baclk.png)

Also some wiring stuff

![iamge2](https://github.com/not-willem/BroAmp-EXG/blob/main/imagesforreadme/fgfhssfhfhs.png)

also theres more ways you can use this [here](https://github.com/upsidedownlabs/BioAmp-EXG-Pill/tree/main/graphics/circuits/v1.0), its the same pins to wire they're not called anything different.

I haven't actually built it YET (i'll update this when i do) but i've 3d printed a prototype so you can see the size of it
![image3](https://github.com/not-willem/BroAmp-EXG/blob/main/imagesforreadme/WIN_20260701_17_08_50_Pro.jpg)
*stalagmite for scale

Once the parts arrive I can show you :D

but yeah check the BOM, its completed.

ALSO big news everyone the total cost of parts per board comes in at around $12.17 NZD so hooray!

that's quite cheap compared to the $59.61 NZD for ONE from the actual website (btw you HAVE to buy 2 you can't just get one)

Anyway I really hope you like this project and consider supporting me by starring this project and if you think you'd want to change anything you can fork the project then make a pull request

##### This design is released under the CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S-2.0). <img src="https://emoji.slack-edge.com/T09V59WQY1E/hectarelitre/4b7bd94bf460f5ac.jpg" alt="hectarelitre" width="20"/>
