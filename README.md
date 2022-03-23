## writespersec

### writespersec

A script file to calculate the number of writes per second occurring to the system SD card.  It will give you an idea of the potential lifetime of your Home Assistant SD card.

### writespersec-ha

Used for my HA system.  It has an SSD drive plugged into a USB connector. The HA database is linked via a softlink and stored there. Writes are about 15 per second.  Guaranteed to kill an SD card in a few months or so.

The mount point for the SSD database partition is identified in line 24 of this script as "/media/db2"
