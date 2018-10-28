# Slic3r-settings
Slic3r settings

[Slic3r Prusa Edition](https://www.prusa3d.com/slic3r-prusa-edition/) settings for the following printers:
* Prusa i3 MK2 (Stock from [Slic3r Prusa Edition](https://www.prusa3d.com/slic3r-prusa-edition/))
* Sam Bell (Prusa i3 MK2 clone with ZEN Flip-Z probe)
* Replicator 2 (Slic3r settings compatible with [GPX](https://github.com/markwal/GPX) usable from [Octoprint](https://octoprint.org/) with [GPX plugin](https://github.com/markwal/GPX) )

Clone this repository where you would like to put your configuration folders: **printer**, **print**, & **filament**

*(usually **"C:\Users\Public\Documents\Prusa3D\"**)*

You may want to copy your own **simple.ini** and **slic3r.ini** files into **Slic3r-settings**.  They have been added to **.gitignore** because they change frequently and in ways that are not generally meaningful to everyone.

In Windows, create a **Slic3r** link with the following target command line:

**_"C:\Program Files\Prusa3D\Slic3rPE\slic3r.exe" --DataDir "C:\Users\Public\Documents\Prusa3D\Slic3r-settings"_**

and start in the following directory:

**_"C:\Program Files\Prusa3D\Slic3rPE"_**
