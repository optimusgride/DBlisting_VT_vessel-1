# DBlisting_VT_vessel-1
DBlisting of vertical skirt vessel creator for E3D Aveva

Hello everyone,
I'm continuing my series of articles on efficiency—something I believe will be especially useful for young designers, though not exclusively.
As many of you know, even a simple vertical vessel typically consists of at least 12 parts:
-	3 body components
-	5 skirt parts (assuming a skirt is used, and yes, I count cut-outs too)
-	4 nozzles (vent, drain, inlet, outlet)

Additionally, we need at least two of the three key parameters—volume, height, and outside diameter (OD)—to calculate the missing one and define the vessel geometry.
To build a basic vessel, say one with 1 m³ volume and 600 mm OD, it usually takes about an hour, especially for beginners. But what if we could cut that down to just one minute?
I'm excited to share a simple Excel tool with an embedded VBA script that can automatically generate a DBlisting file for AVEVA E3D. All you need to do is input the two most important parameters—say, volume and OD—and it will do the rest.

How it works:

In column A, enter “1” to mark the rows for which you want to generate a DBlisting.
Fill in the following parameters: Volume, Dish Type (2:1 or 4:1 for elliptical or spherical heads), Height, OD, and DN of nozzles.
The current version supports only skirt-type support.
Click the “Generate DBlisting” button.
A .txt DBlisting file will be created in the same folder.
In AVEVA E3D, select a ZONE, and drag-and-drop the .txt file into the Command Window to load the vessel.
You can use the tool completely for free. You also can change everything in this excel file to update to your goals. 

How to get it

You find the excel file with VBA script attached 

##Contact
For questions, open an issue in this repository or email me at optimusgride@gmail.com.

##How to support my project

To help fund my project or you want me to adapt my development for you, consider supporting me on Patreon: https://www.patreon.com/posts/vertical-vessel-128118396?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=postshare_creator&utm_content=join_link 
or by direct transfer to PayPal: kersonia.e@gmail.com 
