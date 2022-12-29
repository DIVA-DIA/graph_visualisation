# Graph visualisation
This repository contains a GUI application which enables to draw a graph (stored in a GXL file) on an image.

## Graph Visualisation (./graph_visualisation)
To run the application you simply have to use the `graph_viewer.py` and then you can directly pass in the app the folders containing gxl files and image files. The panels on the right (Node Style/Edge Style) are used to custom nodes and edges of the graph. On the botton you can choose the transparency of the hotspot image, the scaling (Factor by which the x and y coordinates should be multiplied) and color_by_feature (if None -> every node has the same color else every feature node has is own color and can be chosen on the Node Style panel). There is also a save button in order to save the current image after editing it where you just have to specify an output directory.

### Environment
You can set up the conda environment in the directory "./graph_visualisation" by using the following command: `conda env create -f environment.yml`
