# BroAmp EXG
a decent sized bio amp so i can wire it myself and so that it will be cheaper to produce unlike the other ones on the market <img src="https://emoji.slack-edge.com/T09V59WQY1E/ultrafastparrot/40d59f6df4da8934.gif" alt="partyparrot" width="20"/>


## features <img src="https://emoji.slack-edge.com/T09V59WQY1E/woooo/da7f7c8575baa744.gif" alt="wow" width="20"/>
 - same as the BioAmp EXG Pill just easier to produce using cheap parts
 - can do EEG (activity in parts of the brain), EMG (muscle activity, e.g when you move your hand), ECG (heart rate detection) and EOG (eye blink detection)
 - i think you could probably use it for more but thats all that it was listed for on the original page
 - it can send the data back to pretty much any microcontroller with an analog input (ADC)
 - you can configure the gain, bandpass, filter and electrodes all on the board itself

## changes so i dont get cooked by licensing <img src="https://emoji.slack-edge.com/T09V59WQY1E/thumbs-up/e974300682924889.png" alt="thumbs up" width="20"/>
 - date of modifications: June 2026
 - i have made the capacitors and resistors larger to make it easier to hand solder/machine
 - i have changed the board dimensions to 36.5 mm x 48 mm to again, make it easier to hand solder/machine
 - i have kept the same licsense on the hardware (CERN OHL S v2)
 - i have acknowledged the source on the silkscreen
 - the complete source for the modified design is in this github that you're reading this from


thanks to the project by [upsidedownlabs](https://github.com/upsidedownlabs/BioAmp-EXG-Pill) because it was super good and cool.

software demos [here](https://github.com/upsidedownlabs/BioAmp-EXG-Pill#software)

you can find the pcb files in the production folder

and [here](https://github.com/not-willem/BroAmp-EXG/blob/main/BOM%20and%20notes.csv) some notes and a BOM that you can put straight into LCSC to get the parts

but yeah heres some photos

![image1](https://github.com/not-willem/BroAmp-EXG/blob/main/imagesforreadme/image%20(1).png)

Also some wiring stuff

![iamge2](https://github.com/not-willem/BroAmp-EXG/blob/main/imagesforreadme/fgfhssfhfhs.png)

also theres more ways you can use this [here](https://github.com/upsidedownlabs/BioAmp-EXG-Pill/tree/main/graphics/circuits/v1.0), its the same pins to wire they're not called anything different.

I haven't actually built it YET (i'll update this when i do) but i've 3d printed a prototype so you can see the size of it
![image3](https://github.com/not-willem/BroAmp-EXG/blob/main/imagesforreadme/WIN_20260701_17_08_50_Pro.jpg)
*stalagmite for scale

but yeah once stardance funds me i can make it and put it here

also big update i found the [chip](https://www.lcsc.com/product-detail/C4370424.html?s_z=n_q_TL074H) so if you want you can buy that or not idk

This design is released under the CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S-2.0).
