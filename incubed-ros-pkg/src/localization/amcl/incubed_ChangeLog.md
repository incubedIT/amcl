# Changes made by incubed IT

### [13.11.2020] Added possibility to ignore beams during calculating probability for the given pose

**Changes**
* added new ignore-map subscriber to AMCLNode
* added functionality to ignore beams during probability calculation to AMCLLaser

### [06.11.2020] Made scan topic reconfigurable

**Changes**
* moved static scan_topic_ variable as member to AMCLNode class
* added scan_topic to python configuration
* added scan_topic to reconfiguration callback
