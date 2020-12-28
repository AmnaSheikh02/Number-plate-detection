
# Vehicle Number plate detection using image image processing
## Abstract
Automatic Number Plate Recognition (ANPR) is one of the technologies employed in Intelligent Transportation Systems.
This system is provided with vehicle images and it would segment the number plate from the image using image processing techniques.
Also it recognises the Alphanumeric characters in that particular number plate.
This type of system is widely used in Traffic control areas, tolling, parking area, Security System etc. 

## The ANPR process typically involves three stages: 
* Plate detection
* Plate segmentation
* Character recognition

The ability of the algorithm to detect the plate depends on the Plate Detection Stage as a failure at this stage immediately means complete failure of the algorithm. 
After the Plate is recognized and detected all the alphanumeric characters are to be extracted from that particular number plate so we segment each character region from our number plate and pass it to our template in order to match that character
