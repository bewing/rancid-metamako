# rancid-metamako
*RANCiD Perl module for Metamako devices*

This module implements some very basic RANCiD commands for Metamako layer-1 crosspoint switches and muxes.  It has been lightly tested against a range
of devices. Strongly based off the aeos.pm contributed by Bill Fenner of Arista Networks.

When building RANCiD, drop `mos.pm.in` in the lib/ directory, and patch lib/Makefile and etc/rancid.types.base with the provided patch to add the "metamako" type.
