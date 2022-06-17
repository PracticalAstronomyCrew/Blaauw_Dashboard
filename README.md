# Blaauw Dashboard
This is the beginning of the Blaauw Dashboard. It is a web-based application to make interacting with the Kapteyn archive easier. It it still in development, but mostly finished. In the program users can specify some filtering options, which will create a query and then returns a table with entries from the archive. It is also possible to search for a specific object, which uses SIMBAD to fetch the coordinates of the object. Searching by coordinates is also possible. These searches can be executed as either a box or cone search.  
Entries from the main table can be selected, which creates a new table on a different tab. From here the images can be plotted for a quick and easy inspection.  
It is also possible to get some standard statistics from a specific night. This will create plots where the specific night is compared to the data of all previous nights.
You can start the notebook from the command line using "panel serve --show Blaauw_Dashboard_Kapteyn.ipynb". This will automatically open a new tab in your browser and then you can interact with the program.

TODO:
- Present more observation information, such as airmass and seeing, for specific nights and maybe over time
- Allow connection to Kapteyn servers (hopefully)
- Probably much more
