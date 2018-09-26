-----------------------
Name: autouae
Version: 0.1
Creator: bslenul
Category: Addons
-----------------------

A new Amiga bin file to make things a little bit easier for users, basically you won't need to copy the template and edit it with the correct path every time:

* Install PUAE and/or UAE4ARM.
* Install the `autouae.hmod`, it will transfer the new bin file and the templates to your console.
* Rename your bios files, insert the needed ones in `WHDLoad.hdf` and create your game .hdf file (check [**the excellent tutorial from qclart**](https://redd.it/8dbqv7), Patton and KMFD also made some Amiga videos!).
* Put `kick31.rom` and `WHDLoad.hdf` files in `/etc/libretro/system` (use FTP or a "bios installer" hmod).
* Now forget the "copy, edit and add the .uae template" part and simply add the **.hdf file of the game** to hakchi CE!
* Uncheck "Compress".
* Change the beginning of the command line by `/bin/autouae`, **by default it will load the OCS template and use PUAE as core**, if you need to change:  
-to run the game with PUAE and the AGA template add `--aga` to the command line, e.g. `/bin/autouae /var/games/CLV-TEST/game.hdf --aga`  
-to run the game with PUAE and the lowAccuracyOCS template add `--lowocs` to the command line, e.g. `/bin/autouae /var/games/CLV-TEST/game.hdf --lowocs`  
-to run the game with UAE4ARM add `--uae4arm` to the command line, e.g. `/bin/autouae /var/games/CLV-TEST/game.hdf --uae4arm`
* Export/sync!

&nbsp;

# OPTIONAL ADVANCED STUFF (but heh, if you're doing Amiga on S/NESC, you'll be fine! :D)

Templates:

* I included all the templates made by the awesome /u/qclart so far!
* You can change the template used by adding `--template` followed by the template filename (extension included).
* If you want to add your own templates, put them in `/etc/libretro/system/amiga_templates`.
* If you add new templates, avoid spaces or any special characters, underscores are fine.
* For games that requires a specific `WHDLoad.hdf` file, after adding the game in hakchi CE right click > `Show in Windows Explorer` and put the modified `WHDLoad.hdf` here before sync/export.

2 examples:

* You want to use the Shadow of the Beast template: `/bin/autouae /var/games/CLV-S-CHUEA/SotB.hdf --template shadow_of_the_beast.uae`.
* You want to use your own template for Agony and use UAE4ARM: `/bin/autouae /var/games/CLV-S-MCSHD/Agony.hdf --uae4arm --template agony.uae`.

&nbsp;

Some options are possible to be changed directly from the command line:

* `--chipset` will change the `chipset` value.
* `--cpu` will change the `cpu_type` value.
* `--res` followed by "min" or "max" will change both `gfx_width` and `gfx_height` values to 320x256 and 724x566 (PUAE only).
* `--mem` will change the `fastmem_size` value.
* `--framerate` will change the `gfx_framerate` value.
* `--fastcopper` will change the `fast_copper` value (UAE4ARM only).

A random example of what it can look like in hakchi CE: `/bin/autouae /var/games/CLV-TEST/game.hdf --chipset ecs --cpu 68020 --res max --mem 8 --framerate 2`.
