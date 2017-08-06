This project has been built to backup the pictures from my Nexus 5 smartphone
onto the PC.

It currently:

* Detects the Nexus 5 volume (GVFS), which must be connected through MTP USB
* Scans for new pictures
* Saves them into the corresponding Pictures directory
* Deletes them from the phone

An MD5-based cache is kept to detect duplicated pictures.
