# Surface Pro 4 (i7/i5) Hackintosh base on Opencore 0.9.2
## Works with Big Sur, Monterey and Ventura 13.3.1      
&nbsp;
<h1 align="center">What's working?</h1>

* Graphics Acceleration
* Battery
* TypeCover Trackpad: w/gestures, settings for the trackpad
* TypeCover Hotplug
* WiFi & Bluetooth (DONGLE ONLY.)
* More to be added.         
&nbsp;

<h1 align="center">What isn't working?</h1>

* Native WiFi
* Native Bluetooth (goddamn Marvell chipsets)         
&nbsp;

<h1 align="center">Notice for users with i5</h1>

Install with the default config.plist.
After installing, edit your EFI, and import the config.plist from
/EFI/OC/i5config, and enjoy.

DO NOT INSTALL WITH THE I5CONFIG PLIST. YOU WILL FACE ISSUES.         
&nbsp;

<h1 align="center">Ready to try?</h1>

Requirements:
* Must have [genSMBIOS](https://github.com/corpnewt/GenSMBIOS)
* Must have [properTree](https://github.com/corpnewt/ProperTree)

Instructions:

* Open up genSMBIOS, and run the .bat file or whatever extension is suitable.
* Select option 1.
* Then, select option 2.
* Drag and drop your config.plist.
* Then, select option 3.
* Use a suitable SMBIOS.
* After it spits out the generated information, double check the serial number against apple database.
* If it comes back valid, regen.
* If it comes back false, open the config.plist and check if the variables was set properly. (you can use propertree)

Awesome! You are ready to install.         
&nbsp;

<h1 align="center">Screenshots</h1>

<h1 align="center">TypeCover Features</h1>
<p align="center"> <a href="https://ibb.co/SNqYDFp"><img src="https://i.ibb.co/gysqbkC/Screenshot-2023-04-20-at-8-11-56-AM.png" alt="Screenshot-2023-04-20-at-8-11-56-AM" border="0" /></a>         
&nbsp;

<h1 align="center">SurfacePro4 (i7)</h1>
<p align="center"> <a href="https://ibb.co/jkHgYsR"><img src="https://i.ibb.co/SwJRgGr/Captura-de-pantalla-2023-04-20-a-las-1-09-20.png" alt="Captura-de-pantalla-2023-04-20-a-las-1-09-20" border="0" /></a>         
&nbsp;

<h1 align="center">SurfacePro4 (i5)</h1>
<p align="center"> <a href="https://ibb.co/Kz1SwRd"><img src="https://i.ibb.co/S7LGrWb/Screenshot-2023-04-20-at-8-13-43-AM.png" alt="Screenshot-2023-04-20-at-8-13-43-AM" border="0" /></a>         
&nbsp;

<h1 align="center">Credits & Thank yous</h1>

Thanks to:
* Dortania for the awesome guide
* Xiashangning
* acidanthera
* balopez83
* chris1111
* corpnewt
* r/hackintosh
* the hackintosh community!

Main credit to:
* xmiguel911x for creating the EFI.

Want to donate? Donate to the original author please!:
* https://www.paypal.com/paypalme/xmiguel911x