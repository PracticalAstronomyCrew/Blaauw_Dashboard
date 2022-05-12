# Blaauw Dashboard
I have started working on creating a UI where users can interact a bit easier with the Kapteyn archive. This is still in heavy development and definitely not yet finished. For now the only thing it basically does is retrieve entries from the archive. In the program users can specify a date range and some columns and based on these specifications the program will update the table. Entries from the table can be selected and they are then displayed on a different tab, but this will be used to plot the images. The filenames are also displayed, so it should be easier to find the wanted data in the archive. Users can enter the name of an object, such as M1, and do a cone search around this object. SIMBAD will then find the coordinates for the object and the Blaauw Dashboard will then return all entries in the archive which are in the cone. If SIMBAD cannot find the object, it will display an error and if there are no entries in the archive, it will also display an error. There are now reset buttons, to reset the date range and do a complete reset of all search parameters. There are now more columns available and the table containing the selections now shows a better summary of the file. Theere is also a static plot, which I will update to be dynamic.
You can start the notebook from the command line using "panel serve --show Blaauw_Dashboard.ipynb". This will automatically open a new tab in your browser and then you can interact with the program. For some reason when starting the program from a notebook, the error messages do not work. So, for now it is only possible to start the program from the commandline, if you also want to be able to see the error messages.
If you have suggestions for features you want to see or maybe some code that could be better, definitely let me know.

TODO:
- Plot data
- Preview images
- Align and combine images
- Probably much more
