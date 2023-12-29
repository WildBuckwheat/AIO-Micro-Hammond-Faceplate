# AIO-Micro-Hammond-Faceplate

A PCB faceplate that fits the AgOpenGPS All-in-One (AIO) Micro and Hammond 1455T2201 plastic bezel. This faceplate contains no traces, its FR4 cut to the right dimensions with silkscreen.

This faceplate does not fit the AIO Standard, it only fits the AIO Micro. The AIO Standard version is located here: https://github.com/WildBuckwheat/AIO-Standard-Hammond-Faceplate


# Pictures

The real life pictures shown are of v1.0, the files are of v1.1. Between versions the silkscreen changed slightly and the hole for the GPS receiver was changed to the right position (left shown in pictures). The copper logo on the backside was removed. The spacer solder mask layers were added in so that the spacer can be ordered in colour. The files match the gerber previews.


<img src="https://github.com/WildBuckwheat/AIO-Micro-Hammond-Faceplate/blob/main/Images/Front_Mounted.jpg" height="350">
<img src="https://github.com/WildBuckwheat/AIO-Micro-Hammond-Faceplate/blob/main/Images/PCBs.jpg" height="350">

<img src="https://github.com/WildBuckwheat/AIO-Micro-Hammond-Faceplate/blob/main/Images/Faceplate_Top_Gerber.JPG" height="150">
<img src="https://github.com/WildBuckwheat/AIO-Micro-Hammond-Faceplate/blob/main/Images/Faceplate_Bottom_Gerber.JPG" height="150">
<img src="https://github.com/WildBuckwheat/AIO-Micro-Hammond-Faceplate/blob/main/Images/Spacer_Gerber.JPG" height="150">


# Features

The faceplate offers cutouts for the Ampseal housing, the RJ45 jack, and the right GPS receiver. If you are using dual and/or radio you will need additional holes. The locations for the additional holes are marked with silkscreen and with a via. The via is intended to act as a drill guide, similar to a center-punch mark.

The LED areas of the board have oval windows. These windows are devoid of silkscreen and soldermask, leaving the bare FR4 fiberglass, which is translucent. The LEDs are able to shine through these windows, albeit dimly. The LEDs are well visible in low light conditions, and are visible in daylight if you shade them with your hand. The LEDs may or may not be visible in bright daylight conditions.

The back of the faceplate offers a small area to write your firmware version or other notes in permanent marker.

The faceplate works with all versions of the AIO Micro to date (latest version to date is v4.1). The faceplate may work with later versions as well.


# Spacer

AIO Micro versions before v4.0 will need a 1.6mm spacer between the faceplate and the ampseal connector. This spacer can be ordered as a PCB, or can be 3d printed. The necesary files are provided. AIO Micro versions v4.0 and later do not require the 1.6mm spacer.


# Screws

The ampseal connector uses 4x M2.5 self tapping screws. 10mm length if using the spacer, or 8mm if not using the spacer.

The hammond box uses 4x #6-3/8" screws to attach the faceplate. Countersunk screws are provided with the Hammond box. Sadly it is not possible for a gerber file to contain a countersunk hole, and most PCB manufacturers do not offer countersinking capability. You can use the provided screws without modification, you can countersink the hole yourself, or you can use screws with a different head.


# Ordering

Upload the gerber files to your board manufacturer and double check that the selected PCB is 1.6mm thickness. 1.6mm is the default thickness of most board manufacturers. If ordering from JLCPCB, you should set "Remove Order Number" to "Specify a Location." That will place the order number on the JLCJLCJLCJLC placeholder.