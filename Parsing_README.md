# Match list of IDs to an attribute file

_Usage: ID_file.txt Attribute_file.txt > Output_file.txt_

Compare a list of IDs against an file containing annotations and extract the relevant annotations.  
This script will extract any line in which the identifier occurs, regardless of the column.  


### Example of ID_file.txt
    ENSP00000003302
    ENSP00000004982
    ENSP00000007516
### Example of Attribute_file.txt
    9606.ENSP00000003302 9606.ENSP00000004531 165
    9606.ENSP00000003302 9606.ENSP00000007516 282
    9606.ENSP00000003302 9606.ENSP00000156084 222
    9606.ENSP00000003302 9606.ENSP00000156471 740
    9606.ENSP00000004921 9606.ENSP00000472467 211
    9606.ENSP00000004921 9606.ENSP00000473047 294
    9606.ENSP00000004982 9606.ENSP00000202788 220
    9606.ENSP00000004982 9606.ENSP00000215659 186
    9606.ENSP00000005284 9606.ENSP00000007516 225
    9606.ENSP00000005284 9606.ENSP00000009105 250
    9606.ENSP00000005284 9606.ENSP00000023897 197
    9606.ENSP00000004531 9606.ENSP00000003302 165
    9606.ENSP00000004531 9606.ENSP00000005257 161

### Example of Output_file.txt
    9606.ENSP00000003302 9606.ENSP00000004531 165
    9606.ENSP00000003302 9606.ENSP00000007516 282
    9606.ENSP00000003302 9606.ENSP00000156084 222
    9606.ENSP00000003302 9606.ENSP00000156471 740
    9606.ENSP00000004531 9606.ENSP00000003302 165
    9606.ENSP00000004982 9606.ENSP00000202788 220
    9606.ENSP00000004982 9606.ENSP00000215659 186
    9606.ENSP00000003302 9606.ENSP00000007516 282
    9606.ENSP00000005284 9606.ENSP00000007516 225
