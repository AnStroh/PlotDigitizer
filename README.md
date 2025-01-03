# PlotDigitizer
This package is used to extract X, Y values from 2D plots.

# Installation

Clone this repo to your computer and open the julia REPL. Navigate to the DigitizePlot directory and activate the environment by typing

```julia
julia> ]
```
 
 to enter the julia package manager and then 

```julia
(@v1.10) pkg> activate .
```

to activate the environemt. Following type 

```julia
(PlotDigitizer) pkg> instantiate
```

to download and precompile the correct versions of the needed packages. 

# How to Use PlotDigitizer

To digitize points from a 2D plot you need to call the ```digitizePlot()``` function which will open a new window. The needed input of this function are the boundary consitions of the X and Y axis, each as a ```Tuple``` as well as the path to the image to be digitized as a ```String```.

### Creating a Line of Points

Once the window has opened, you are free to click in the window to add points to create a line. This line is a list of points in the coordinate system defined by the boundary conditions of the axis. The coordinates of the new point will appear in the REPL.

### Deleting Points

If you misclick, you can remove the last point by holding the ```d``` key when clicking the left mouse button.

### Creating a New Line of Points

Multiple lines can be generated by holding the ```n``` key when clicking the left mouse button. The number of lines will be shown in the REPL.

### Switching Between lines

To switch between lines, hold the ```s``` key while clicking the left mouse button. The active line will be shown in the REPL and will have a different color than the other lines.

### Exporting Data

To export the values of the active line, hold the ```e``` key while clicking the left mouse button. The default name of the .csv file will be "digitized_data_line#.csv". The name can be changed as a keyword argument in the function.


