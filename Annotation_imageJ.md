## ImageJ installation
Go to this [link](https://imagej.net/software/fiji/). Dowload the .zip file, extract and you are done. 

Optional - A plugin suitable for 3D analysis is MorphoLibJ under the plugin IJPB. To install this plugin, open imagej go to help --> press "update.." it will check for the updates and another window will appear. Press "Manage update sites". Under name find "FIJI", "3D imageJ suite" and "IJPB plugins"; and check the boxes on the left. Then close the current window and press "Apply changes" in the previous window and let it install, once done restart and imageJ is ready. You can open imageJ and under plugin check if you can see MorphLibJ.

## Annotating data set for training

The goal of this step is to identify different phases in your image and identify them (associated pixels) with an integer (1,2,3). 


1. Open imageJ and the main window will appear as shown below
<IMG SRC="ImageJ_main.png" title="ImageJ main window"><br>
2. Open image --> file - open image from file explorer or simply drag and drop
3. Adjust the contrast level if needed --> Image - Adjust - Brightness/contrast --> adjust the scroll bar
4. Change the image to 8-bit --> Image - Type - 8-bit
5. Once you identify the region to be labelled - zoom in --> press icon 2 shown in step 1 - click on the region in the image to zoom in
6. Now we define the value of the pixel to be drawn --> press icon 3 shown in step 1 -


  
