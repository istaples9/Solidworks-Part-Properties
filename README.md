# Solidworks-Part-Properties
This VBA scripts finds the overall stock size of the part and creates a custom property called Stock LxWxT which can be used in BOMS. 

1. Unsuppresses the bounding box feature and uses the bounding box to get the stock dimensions of a part.  
2. If the part is sheet metal, stock size is pulled from the flat pattern and a cut list folder is created. 
3. Stock size is then added as a custom property called STOCK LxWxT.
4. After the stock size custom property is added, the bounding box is suppressed so as not to intefere with graphics and drawings.
