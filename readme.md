# #StandWithUkraine Filter

 This project uses backgroundnet to create a filter for videos and images that replaces the background with an image supporting Ukraine.  The user chooses from images of sunflowers, the Ukrainian flag, the shape of Ukraine, dolls in traditional Ukrainian embroidery, and a field of grain.  The purpose of this filter is to make it easy for people to show their support for Ukraine as Ukrainians continue fighting for their sovereignty.

## The Algorithm

The algorithm is a modified version of backgroundnet.py called my-filter.py.  This algorithm is initialized by the following command: python3 my-filter.py [name of input file (the file you want to filter)] [name of output file].  The file you want to filter can be a video, photograph, or live camera footage.  At a certain point, the program uses a conditional and user input to let the user choose their background image out of five options, which were explained above.  Then, the input file is edited by backgroundnet.py to replace the background with the background chosen by the user. The resulting file it outputted under the name chosen by the user.

## Running this project

1. Open up your linux terminal and access the directory containing the #StandWithUkraine filter.
2. Make sure the sys, argparse, jetson_inference, and jetson_utils libraries are imported.
3. Write the following command: python3 my-filter.py [name of input file (the file you want to filter)] [name of output file]
4. If you know what image you want to filter, upload it to the same directory.
5. When prompted, enter a number corresponding to the background image you want.

[View a video explanation here](https://watch.screencastify.com/v/jQ4qJ8nqoS9q4RXF9hGL)
