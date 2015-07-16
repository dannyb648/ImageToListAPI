# ImageToListAPI
Small API which analyses Images and returns a Multi-Dimensional list based on arguments.

### For Now ###
This code is currently in Development.
During our first year at Coventry University, Myself and Samanthy created a algorithm which turned a google map image into a list.
This list would actually be a 2d map of the map, during intergers to represent roads and not roads.
Sam provided the majority of the code, and I thought up and penned the actual theortical algorithm. The project went well.

However we realised that this algorithm could be quite useful to others, so we are releasing it as an API.
I will be taking the inital algorithm and making it so any image can be turned into a 2d map.

The code currently relies on PIL, which is depreciated, so during development I hope to move over to a better alternitive.
Hopefully this is Pillow.

My intention is that the first release will simply take arguments as a stand alone script e.g
        imageToList image outputname HTMLcolor int to represent  HTMLcolor int to represent HTMLcolor int to represent etc.

And secondly it will function as a library which can be used within other code.
        imageToList(image, outputname, HTMLcolor int to represent  HTMLcolor int to represent)
        
Finally my goal is that it can pull the color to int arguments from a .txt, saving time when creating big int maps.

This Readme will update as dev goes on, and will be overhauled just before release v1.0

You can follow the actual development on my blog www.danbeglin.co.uk/blog
