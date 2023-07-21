# #StandWithUkraine Filter

 This project uses backgroundnet to create a filter for videos and images that replaces the background with an image supporting Ukraine.  The user chooses from images of sunflowers, the Ukrainian flag, the shape of Ukraine, dolls in traditional Ukrainian embroidery, and a field of grain.  The purpose of this filter is to make it easy for people to show their support for Ukraine as Ukrainians continue fighting for their sovereignty.

## The Algorithm

The algorithm is a modified version of backgroundnet.py called my-filter.py.  This algorithm is initialized by the following command: `python3 my-filter.py [name of input file (the file you want to filter)] [name of output file]`.  The file you want to filter can be a video, photograph, or live camera footage.  At a certain point, the program uses a conditional statement to help the user choose their background image out of five options, which were explained above.  Then, the input file is edited by backgroundnet.py to replace the background with the background chosen by the user. The resulting file it outputted under the name chosen by the user.
[Image of Conditional Statement](https://i.imgur.com/EDAjH5J.png)

## Running this project

1. Open up your linux terminal and access the directory containing the #StandWithUkraine filter.
2. Make sure the sys, argparse, jetson_inference, and jetson_utils libraries are imported.
3. Download the python and image files in this github.
4. If you know what image you want to filter, upload it to the same directory.
5. Write the following command: `python3 my-filter.py [name of input file (the file you want to filter)] [name of output file]`.  For example, if you input an image called `image1.jpg` and output a file called `output1.jpg`, you would do 'python3 my-filter.py input.jpg output.jpg`.  If you are inputing a video, you would do the same thing but using a different extension than `.jpg`, such as `.mp4`.  If you are inputting live video, you would do `python3 my-filter.py /dev/video output.mp4`.
6. When prompted, enter a number corresponding to the background image you want.
7. Retrieve your newly filtered file.

[View a video explanation here](https://youtu.be/u66XpFIK2pY)
