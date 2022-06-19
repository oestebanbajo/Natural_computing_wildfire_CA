# Natural_computing_wildfire_CA
Repository for a Cellular Automata for modeling wildfire as well as controlled burning.

## Example of use
The code and visualizations are all included in the Jupyter notebook. The initialization hyperparameters can be modified under the Build and call CA section. 

The size variable defines the lattice horizontal and vertical size. This can be modified as well as the number of steps until the simulation stops. Other variables such as epochs will only change the capacity of the plots to generalize better, but will carry an important computational weigth. `show_im` allows to set the number of steps until a new visualization is shown.

Variable `veg` can take `'low'`, `'mid'`, `'hig'`, setting the vegetation density from low to mid to high. `hum` also has 3 levels, which can take values 20, 50 or 60.
