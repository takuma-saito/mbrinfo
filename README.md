MBR Information analyzer
============================

This software analyze MBR (master boot recorder).

*How to use?*

    $ ./mbrinfo /dev/disk0
    CHS [START]       CHS [END]                   LBA                  Byte      TYPE
    1 |  1023 254  63    1023 254  63   [            1 -    625142448 ]  298  GiB   | ee -> GPT 
    2 |     0   0   0       0   0   0   [            0 -            0 ]    0 Byte   | 00 -> Empty 
    3 |     0   0   0       0   0   0   [            0 -            0 ]    0 Byte   | 00 -> Empty 
    4 |     0   0   0       0   0   0   [            0 -            0 ]    0 Byte   | 00 -> Empty 
    signature: aa55 -> OK


