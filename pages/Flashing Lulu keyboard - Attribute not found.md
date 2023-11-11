public:: true

- # Context
	- Flashing my Lulu keyboard with custom firmware
- # Error:
	- ```
	  p LV4.uf2 /Volumes/RPI-RP2/
	  
	  cp: LV4.uf2: could not copy extended attributes to /Volumes/RPI-RP2/LV4.uf2: Attribute not found
	  ```
- # Result:
	- Ignorable. It does not mean the copy failed, it's that the filesystem doesn't support attributes.