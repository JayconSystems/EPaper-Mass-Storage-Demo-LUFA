This is an example LUFA (Lightweight USB Framework for AVRs) demo which allows you to use an Arduino Leonardo to load images to the onboard flash memory of the EPaper development board. The Arduino Leonardo will enumerate over USB as a mass storage device allowing you to drag and drop files into the flash memory.

	Works with all our EPaper development boards: 
		http://www.jayconsystems.com/epaper-development-board-v1-1-44.html
		http://www.jayconsystems.com/epaper-development-board-v1-2-0.html
		http://www.jayconsystems.com/epaper-development-board-v1-2-7.html

	
The LUFA demo was modified to include the AT45DB161D DataFlash and work with the Arduino Leonardo. To compile you will need to add all the included files to the appropriate folders inside the LUFA library. Once compiled you will need to wire up the SPI interface of the Arduino to the EPaper board, and connect the CS pin to D8.

 
Written by Jiten Chandiramani at Jaycon Systems LLC.  
BSD license, all text above must be included in any redistribution.
