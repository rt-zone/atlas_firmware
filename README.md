These are the files for building the atlas firmware using micropython (https://github.com/micropython/micropython.git). Put the py files in the modules folder in /ports/rp2. Put the cmodules in /ports/rp2.

To change the firmware version name, change (git_tag = "v1.27.0-pibody") in the makeversionhdr.py file in the file_data parameter.

Build command: make BOARD=RPI_PICO_W USER_C_MODULES=cmodules

your firmware.uf2 is in build-RPI_PICO_W
