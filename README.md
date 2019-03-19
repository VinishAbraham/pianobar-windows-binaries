pianobar for Windows - portable binaries
========

![pianobar](https://github.com/thedmd/pianobar-windows-binaries/blob/master/screenshots/pianobar.png)

pianobar is a console client for the personalized web radio pandora
(http://www.pandora.com). Source code of the original project can be found at
at http://github.com/PromyLOPh/pianobar/ or http://6xq.net/projects/pianobar/

This project contains binaries for Windows build using Microsoft
Visual Studio 2015.

json-c, vtparse are used to prepare this distributtion.

Source code of this binary can be found at:
https://github.com/thedmd/pianobar-windows-build


CONFIGURATION

Pianobar uses a configuration file. Under Windows this file is named pianobar.cfg
and should be placed in the same directory as pianobar.exe.
There is an example configuration file in the repository you can copy or rename.
Edit it and fill in the marked fields relevant to you, then remove or comment out
those remaining.

Note that non-US users have to have configuration file with control proxy
details set.


GLOBALPANDORA.COM

If you're behind proxy please look into pianobar.cfg.example and copy necessary
settings to your own configuration file. This are necessary, because
globalpandora.com does not support server used in by pianobar.

Forked From : https://github.com/thedmd/pianobar-windows-binaries

Credit: https://github.com/thedmd