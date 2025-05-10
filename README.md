# NXDNReflector-Dashboard
Dashboard for NXDNReflector (by G4KLX) forked by YSFReflector-Dashboard of DG9VH
=====================================

About
=====
NXDNReflector-Dashboard is a web-dashboard for visualization of different data like
system temperatur, cpu-load ... and it shows a last-heard-list.

It relies on NXDNReflector by G4KLX (see https://github.com/g4klx/NXDNClients). At 
this place a big thank you to Jonathan for his great work he did with this 
software.

Required are
============
* Webserver like 
* lighttpd or apache(2)
* Updated to work with PHP 8.x >= 8.2.28

Installation
============
* Please ensure to not put loglevels at 0 in NXDNReflector.ini.
* Copy all files into your webroot and enjoy working with it.
* Create a config/config.php by calling setup.php and giving suitable values
* If Dashboard is working, remove setup.php from your webroot

For detailled installation see `linux-step-by-step.md` within this repository.

Contact
=======
Feel free to contact the author via email: iu7igu@yahoo.com
