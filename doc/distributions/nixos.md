NixOS
=====

The *NixOS Wiki* installation notes for UEFI on NixOS on ARM should be
followed.

 - https://nixos.wiki/wiki/NixOS_on_ARM/UEFI

They will refer back to Tow-Boot as a source of *Platform Firmware*.
You will need to know that once NixOS is booted, it and Tow-Boot cannot write to EFI variables anymore.

The installation is similar to what it would be with `x86_64`. The main issues
are noted on the Wiki page.
