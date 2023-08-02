# Dactyl-Manuform Keyboard
Handwired dactyl-manuform keyboard with Raspberry Pi Pico RP2040s


## to create/change the keyboard layout
- make your layout on config.qmk.fm
- download the json file
- open terminal in downloads folder and run:
  
  ``qmk compile [filename].json -e CONVERT_TO=kb2040
``
- this creates a new uf2 file in your qmk folder
- click the reset button on the RP2040 or hit the reset keys if you already have firmware loaded
- drag and drop the new uf2 file onto the RP2040
