KVASD Installer
---------------
This project is obsolete as WSJT-X and WSJT no longer require the KVASD binary
to function properly. The code is left here merely for snippits and reference.

Description
-----------
KVASD Installer is a set of scripts / functions to manage the Installation, Removal
and Testing of the KVASD decoder used with WSJT, WSJT-X and WSPR-X from
Joseph H, Tayolor, K1JT.

The KVASD binary itself **is not** part of this package, as such, does not
violate FOSS.

Usage
-----
- Add the PPA repository:

.. code-block:: bash

   sudo add-apt-repository -y ppa:ki7mt/kvasd-installer
   sudo apt-get update
   sudo apt-get install kvasd-installer
   
   * Run the installer: kvasd-installer
   * Follow the prompts
 
Upstream Project
----------------
* Project Manager: Joe Taylor, K1JT
* Upstream URL: http://physics.princeton.edu/pulsar/k1jt/
* Contact: wsjt-devel@lists.sourceforge.net



