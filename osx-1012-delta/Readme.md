Delta
=====

There is quite a delta between the bridgesupport file found in the system and
the one generated by BridgeSupport.

Instructions for generation were taken from here:
https://gist.github.com/Watson1978/bc1a8216678905f924bb5c6ee85791ec#file-gistfile1-txt-L7

Missing enums
-------------

Found in the original one, but missing in the generated one:
    #AppKit
    <enum name='NSStatusWindowLevel' value='25'/>
    <enum name='NSSubmenuWindowLevel' value='3'/>

    #Foundation
    <enum name='NSNotFound' value='2147483647' value64='9223372036854775807'/>