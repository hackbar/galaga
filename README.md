# Galaga Disassembly

(forked from https://github.com/neiderm/arcade, which was forked from
https://github.com/gary-seven/eightysArcade)

## Summary:
 - ASxxx project:
    Assembly sources to generate exact image of machine code.  
    Requires asez80 assembler by Alan R. Baldwin to build:  
     ftp://shop-pdp.net/pub/asxxxx/av5p10.zip  
    Requires srecord-1.64:  
     http://srecord.sourceforge.net/srecord-1.64.tar.gz  
    Code::Blocks project (.cbp) is provided to browse/edit the assembly code  
    (C::B lexer config in _ASxxx/contrib/lexer_zilog_z80.xml).  

 Assembly files are also built by make ... see _ASxxx/Makefile, there are 
 different names which are created - this needs to be handled better, but the 
 purpose was to allow operation in multiple OS environments where I ended up 
 with different versions of (x)mame to support.
