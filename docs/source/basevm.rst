####################
Base Ubuntu VM Build
####################

UNDER CONSTRUCTION

We start by building a base Ubuntu VM image, from which we can clone other
guests.

First, download a suitable supported Ubuntu desktop distribution.

MORE HERE ABOUT TYPES...

In VirtualBox, create a new Ubuntu guest with 1024MB of RAM and
12GB of storage (or other values as appropriate). Consider creating the hard
disk as fixed size to improve performance.

IMAGES HERE...

Go into the guest settings to configure it to boot off the ISO. Under Storage,
click on the Controller: IDE row and then click on the Add CD/DVD Device Icon,
"Choose disk" and browse to the ISO:

IMAGES HERE...

Do the same process to add the ISO for the Guest Additions.
On Windows it is located in
C:\Program Files\Oracle\VirtualBox\VBoxGuestAdditions.iso

As above, there should now be two ISO files associated.

Start the VM and install Ubuntu as per the defaults (or your own preferences!)

****************************
Install VirtualBox Additions
****************************

Once the build is completed and the guest is running, log in and start a
terminal window (CTRL+ALT+T). Install the VirtualBox additions for
improved host-guest integration:

.. code-block:: text

  cd /media

Look for the appropriate subdirectories that contain the correct additions
version. Example:



