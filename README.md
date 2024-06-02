# Cam740

**Cam740** may be used for diagnosis of Sinumerik 840D, Sinamics or Step7 systems connected via Ethernet, Profibus, MPI or any other interface supported by Siemens S7 systems.

![header](/docs/images/header.png)

web page:  [alxcor.github.io/cam740](https://alxcor.github.io/cam740).

Offline functions, without a connection to a live PLC system:
- Sinumerik alarm bit calculator: DB2 bit for a specific alarm number or alarm number for a specific bit in DB2
- Sinumerik M function calculator: Channel DB bit for quick decoding of an M function
- Sinumerik Fast IO calculator: DB10 bits for monitoring or control of a specific NCK fast input
- Sinamics Help for Alarms: Display the help for a Sinamics specific alarm number

Online functions, when the program is connected to a live PLC system:
- Sinumerik axis / channel diagnosis: a live screen with the status of some of the most important bits for axis / channel diagnosis
- Sinumerik M function logger
- Sinamics drive status diagnosis


The program is based on the older ['Monitor5'](http://alxcor.github.io/monitor5) program.

No installation is needed, the program is portable and saves all data in .INI files in own folder.

To 'uninstall' simply delete the folder.

Versions:
- v240526 [26.05.2024] Log function is functional. Bug fixes and functional improvements.
- v230624 [24.06.2023] first test version. Complete rewrite of Monitor5 project.

-* The project uses Snap7 under LGPL3 License to communicate with the Sinumerik/Sinamics/Step7 equipment.*
-* The project uses Qt under LGPL3 License.*
-* The project may also use PRODAVE interface if the DLL file is provided by user and a license is activated.*

