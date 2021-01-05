file copy -force ../FILENAMEINPUT.bit ./

# To generate the MCS file for kc705
write_cfgmem -force -format MCS -size 128 -interface BPIx16 -loadbit "up 0x00000000 FILENAMEINPUT.bit" FILENAMEOUTPUT.mcs
28f00ap30t-bpi-x16
BPI_RS_PINS {25:24}
