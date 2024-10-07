Have you ever wanted to have a digital Notice screen system that runs on low power and from a small device? 
Well this might very well be the answer! Introducing the Raspberry Pi Notice Screen system!

While out walking, I started noticing that shops and even large corporations were using TV screens with bulky computer
towers which is such a waste of electricity and seems awkward to manage. Notice Screens are not really a hot topic but
can drive sales and also add a professional facade.

This project started in August 2022 from an idea I had for a very long time, I'm not any professional programmer by any means
but I'm proud of this project and... it works!
I designed this system to be configured by IT Staff in terms of deployment and configuration. When changes are needed, there are 
some methods where by no changes are needed from the Management system. Examples are using Google Slides where designated staff members
can make changes online through Google Slides which will automatically loaded after a set time. I have included a Google Slideshow template
which is located in the ASSETS folder inside a folder called 'HTMLExamples'. There are plenty more options than Google Slides but that is
an example that works really well in both testing and business use. There are endless possibilities with this system!

Features:

* Supports: HTML, Video/Audio, Slideshows and even audio playback.
* Super lightweight design (The system can fit on a 1.44MB Floppy disk for an idea of size).
* A dedicated Management System which is used to make changes to Notice Screens.
* Apache is installed on the Management system which will allow you to host webpages locally.
* Easy and quick command changes.
* Endless possibilities - customize your own HTML pages.
* Make mass changes up to 10 Raspberry Pi devices.
* Clone the contents and operating mode of up to 10 notice screens at once.
* Easy installation and setup.
* Automatic event logging for audit purposes of any changes made through the Management System.
* Create IMG backups of both Notice Screens and the Management System over USB.
* Automatic updates to the Raspberry Pi OS and installed Software for security.
* Can be used on a VLAN with no internet thanks to Apache (After installing the Software over the internet).
* With Network Manager, both LAN and WLAN can be used.

Basic Requirements:

 * X1 Raspberry Pi 16-32GB SD Card       - For the Management System.
 * Raspberry Pi devices 8-16GB SD Card   - For a Notice Screen(s).
 * Networking - Cables, networking infrastructure, Static IPV4 Address.
 * Suitable TV / Display device.
 * Computer to connect, setup and configure the Notice Screen system.

Tested Hardware:
Note: The system is not limited to just the below Hardware Devices.
Please feel free to test on newer or different models and post the outcome here on GitHub.
They should still work (Providing the correct Hardware is present).

Management System:
- Raspberry Pi Model B Rev 2, 512MB (2012)
- Raspberry Pi 3 Model B Rev 1.2M

Notice Screens:
- Raspberry Pi Model B Rev 2, 512MB (2012) (NOT RECCOMDNED FOR VIDEO PLAYBACK OR HEAVY HTML PAGES).
- Raspberry Pi 3 Model B Rev 1.2M


Setup and operating guide for the Raspberry Pi Notice Screen System:

[Raspberry Pi Notice Screen Setup Guide 1.0.pdf](https://github.com/user-attachments/files/17271220/Raspberry.Pi.Notice.Screen.Setup.Guide.1.0.pdf)



Error code and troubleshooting reference manual:

[Error code Reference.pdf](https://github.com/user-attachments/files/17271131/Error.code.Reference.pdf)
