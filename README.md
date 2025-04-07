# QLpicoVGA_PCB
[Going to add a licence later. Not my cup of tea, but I think one of the Cern Licences will do the job}

This is a Tiny QLpicoVGA PCB converter board based on the design by Holmatic.
His Github repo is here: https://github.com/holmatic/video_if_ql_vga

Instead of using an off the shelf Pico with a daughterboard, I combined all in one single PCB.

![QLpicoVGA v7](https://github.com/user-attachments/assets/1b5679c7-5b00-4d78-8289-11e73a950140)

If you are going to order a PCB make sure you select 1mm thick FR4, not the standard 1.6mm. Otherwise the PCB won't slide between the top two rows of the D-sub 15 pin VGA connector.
It is best to trim the middle row of pins on the VGA connector. The connectors I got had extended pins which makes soldering to the board a bit tricky.

On the bottom side you have to connect the Hsync and Vsync signal to the board. I used thin unstranded wire.

![QLpicoVGA v12](https://github.com/user-attachments/assets/b9adeb00-2a8e-4e35-aa2c-550dde411eee)

The enclosure can be found on Makerworld.
https://makerworld.com/en/models/1292430-sinclair-ql-qlpicovga#profileId-1322934
You also need four M3x12mm screws with a countersunk head. In QL black of course!
The complete bill of materials can be found in the same directory as the schematic.

![QLpicoVGA v6](https://github.com/user-attachments/assets/7bcf3490-32a0-443c-ba1d-784999c98415)

Note that the converter is powered over USB, so an extra lead is needed to power it.
Another option is to power it from the QL itself. It is a tricky procedure though!
Short K4 with a blob of solder (see schematic). If you have a 6 core wire you can solder the unused one to K1, pin 1, marked "P". On the QL side you have to use one of the pins of the DIN connector and supply 5V there. More info is in the schematic on page 2.

![QLpicoVGA v5](https://github.com/user-attachments/assets/1bcc91b4-5461-4a37-a74b-2e02751b4b03)

Some additional photos which might help in assembling.

![IMG_7710](https://github.com/user-attachments/assets/3556425a-b54c-4fd1-9cc1-b436a310888e)

![IMG_7711](https://github.com/user-attachments/assets/792ed7b8-9762-4e23-962b-be276b609a97)

![IMG_7712](https://github.com/user-attachments/assets/0b6ced56-a854-48c4-a526-8967fccb87be)

![IMG_7713](https://github.com/user-attachments/assets/ed01cd0b-078d-4070-982e-841e59dec5c5)

![IMG_7720](https://github.com/user-attachments/assets/549cf53d-373d-4718-8533-e860170cfdf3)

