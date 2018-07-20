# Dual_Boot_Protocol
1. Check UEFI or BIOS > If UEFI , disable secure boot from firmware settings
2. Prepare Windows Machine for dual boot: 
   * cmd -> diskmgmt.misc
   * Shrink C drive and leave unallocated
3.Get ubuntu 16.04.iso image from ubuntu website
4.Burn the image using universal USB(BIOS compatible) or rufus(UEFI Compatible)
5.F12/F10 or F2 depending of PC manufacturer
6.Partition Schemes: * Default : Install Ubuntu alongside Windows Boot Manager
                     * Something Else: Customized
                     * Custom Partition Layout: * Size = Atleast 20000 MB
                                                * Type for the new partition = Primary
                                                * Location for NBew partition = Beginning
                                                * Use as = EXT4 journaling frile system
                                                * Mount point = /
7. Proceed to install
8. Choose a username and password for sudo administrative
