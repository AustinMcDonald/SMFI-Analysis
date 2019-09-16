First add your data into the spot folder. If you have multiple spots just make more folders.
If more than 1 slide do the same with the slide directory.


Next step is to run through the Spot_Shaper
This takes the spot and crops the image, also loads all teh frames into 1 h5 file.
The frames are opended one by one anc converted into photo-electrons at this point.


After the Spot shaper then run Trajectory_maker
This takes the spot and finds all the high points, and makes the fluorescent trejectories. 
It saves them as a class in a dictonary for wasy access.

once this is done the ANA_step can be loaded and then you have acces to the dictonary yo loaded previsould and can easily see the trejectories and apply any cuts you want. 


