# spindownd
Many Western Digital hard disks do not include the ability to standby the drive when inactive for a timeout period.  

This is a daemon is similar to hd-idle.  It polls '/proc/diskstats' to determine whether an hard disk should be spun down.  See: http://hd-idle.sourceforge.net

Unfortunately, hd-idle appears not to be maintained, is not prepackaged for many Linux distros, and it is often difficult to determine whether hd-idle is actually working.  This bash script daemon is intended as a simple, understandable, replacement.
