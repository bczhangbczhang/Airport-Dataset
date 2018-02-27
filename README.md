# Airport-Dataset

A new dataset for multiple aircraft tracking from an airborne camera is presented. The dataset consists of 6 video sequences with 3,097 fully annotated frames of resolution 596x336 pixels and contains 7031 aircraft, covers their moving and parking in the airport apron, taxiway, and runway. All of them have been collected from the Internet.

The format of the annotation file for each aircraft is:
 <br />
 <br /> *_Frame number    min_x     min_y     width     height     quantized_direction    ID_*
 <br />
 <br />Here, the quantized_direction is a number from 1 to 8 represnts the dirction of the airctaft as the following figure:
 <br />
 ![alt text](https://github.com/bczhangbczhang/Airport-Dataset/blob/master/DON_.jpg)
 <br />
 In that image, the quantized direction is Five.
 <br />The last video sequence was taken in the lab with an aircraft prototype model.
 

