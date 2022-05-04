# Blaauw Dashboard
I have started working on creating a UI where users can interact a bit easier with the Kapteyn archive. This is still in heavy development and definitely not yet finished. For now the only thing it basically does is retrieve entries from the archive. In the program users can specify a date range and some columns and based on these specifications the program will update the table. Entries from the table can be selected and they are then displayed on a different tab, but this will be used to plot the images.
You can start the notebook from a Jupyter environment by just running all the cells, or from the command line using "panel serve --show Blaauw_Dashboard.ipynb". Both of these options will automatically open a new tab in your browser and then you can interact with the program.
If you have suggestions for features you want to see or maybe some code that could be better, definitely let me know.

TODO:
- Add filename to the displayed columns
- Allow users to search for objects, use SIMBAD to find the corresponding coordinates and query the archive to get the files containing the object
- Plot data
- Preview images
- Align and combine images
- Probably much more
