# MiniCAM
The MiniCAM is an open-source behaviroal camera for imaging freely behaving animals in behavioral and neuroscience experiments. The goal of the MiniCAM project is to provide an open-source, customizable, high-quality, and affordable alternative to using webcams or scientific USB cameras for behavioral imaging. The MiniCAM is powered and communicates over any commercial 50ohm coaxial cable minimizing the cabling that needs to run into the experimental environment. The coaxial cable connects the MiniDAQ to any version of UCLA Miniscope DAQs or MiniDAQs which then connects over USB3 to a host computer.

Using the [Miniscope Software](https://github.com/Aharoni-Lab/Miniscope-DAQ-QT-Software), multiple Miniscopes and MiniCAMs can be connected, streamed, and time-sync'ed recording simultaniously.

<p align="center">
  <img width="500" src="https://github.com/Aharoni-Lab/MiniCAM/blob/master/img/MiniCAM_assembled.png">
</p>

## MiniCAM Components
The MiniCAM consists of a custom printed circuit board (PCB), a 3D printed housing, an off the shelf M12 lens mount, a M12 camera lens, and an optional LED illumination ring. The PCB contains a 5MP CMOS image sensor, support electronics to power and serialize the imaging data, and an SMA coax connector. The image sensor can be configured through the Miniscope software and the optional LED illumination ring intensity can also be controlled through software. The MiniCAM runs at 50fps with 1024X768 resolution as the default configuration. Higher frame rate can be achieved by choosing smaller resolutions and higher resolution comes with lower frame rate.

<p align="center">
  <img width="600" src="https://github.com/Aharoni-Lab/MiniCAM/blob/master/img/MiniCAM_exploded.PNG">
</p>

## System Layout
The MiniCAM requires a UCLA Miniscope Data Acquisition (DAQ) board (connected over a 50ohm coaxial cable) and a host computer (connected over USB3) running the [Miniscope Software](https://github.com/Aharoni-Lab/Miniscope-DAQ-QT-Software) (or other third-party application that can stream UVC cameras and can communicate through a Miniscope DAQ). You can use any generation of Miniscope DAQ but you must update it with [the newest firmware](https://github.com/Aharoni-Lab/Miniscope-DAQ-Cypress-firmware). You can also use the cheaper and smaller version of the Miniscope DAQ called the MiniDAQ (open-source link coming soon). Once updated to the newest firmware, any Miniscope DAQ device will work with all Miniscope and MiniCAM devices. 

<p align="center">
  <img width="600" src="https://github.com/Aharoni-Lab/MiniCAM/blob/master/img/MiniCAM_layout.PNG">
</p>

## M12 lenses and Coaxial cables
Just like Miniscopes, the MiniCAM uses a 50Ohm coaxial cable for power, communication, and data. Any 50Ohm coax cable should work with the system. A 1mm diameter coax cable can likely function at lengths over 15 feet. 
Vendor: Cooner Wire (can be purchased at other places too)
Part Number: CW8251
Description: Coax cable. 36AWG 26/50SPC TRANSCUCENT PFA TO .016" NOM. O.D. 44AWG SPC SHIELD WITH .010" WHITE SILICONE RUBBER JACKET TO .045" NOM O.D.
