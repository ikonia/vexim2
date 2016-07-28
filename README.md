# Virtual Exim 2
## README AND INSTALL GUIDE

Thanks for picking the Virtual Exim package, for your virtual mail hosting needs! :-)

This document provides a basic guide on how to get Virtual Exim working on your system. In this guide, I assume that you have *a little* knowledge of both MySQL and Exim.

Before we go into any details, thanks must go to Philip Hazel and the Exim developers for a fine product. with additional thanks the postmasters at various domains for letting me play havoc with their mail while I set this up.

The Virtual Exim project currently lives on GitHub: https://github.com/avleen/vexim2
And its mailing list/Google group is available at: https://groups.google.com/group/vexim

## Prerequisites

* A modern / current Linux or BSD flavour operating system
* Exim 4 or later
* Apache 2.2 or later
* Mysql 5 or later - or a binary compatible equivilent from MariaDB 
* PHP 5.3 or later - with the following extensions available.
  * PDO
  * pdo_mysql or pdo_pgsql
  * imap
  * gettext
  * iconv


## Optional Software

* Mailman
* clamav
* spamassissign

VExim might work with older (or newer) versions of these packages, but you may have to perform some adaptation work to achieve that. In any case, you are welcome to file bugs and/or provide patches on GitHub


## Installation
In an attempt to make the installation process clear and simple guides have been written to cover the major operating system platforms. This is by no means a defenitive list and you should feel free to add a new install file to the documentation to guide a user in the setup of VExim2 on a specific platform.

Find the install file in the install-guides directory that matches your distribution and follow that process through
