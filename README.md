## Colour detector for images

Extracts the top 'n' colours from an image and classifies them in the most aproximate colour name from a 865 colours database.

Steps for the algorithm
1. Takes an image path and the number of colours you want to extract.
2. Resizes it and compares every pixel with a csv file that contains 865 colours with their RGB code.
3. The stored colours are counted and ordered by how many times it's in the picture.
4. Finally, the script plots the image and a little rectangle for the 'n' top colours more present in the image.

_The extraction takes few minutes._

Output example:

![Image Result](https://github.com/camilogo1016/Colour_detector/blob/master/results/result_vivaldi.jpg?raw=true)
