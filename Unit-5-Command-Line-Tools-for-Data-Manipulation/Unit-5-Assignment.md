# Unit 5 Assignment

The goal of this assignment is to:

  - Use the command line tools in the CoastWatch Utilities for working with data files (data processing, map projections, etc).
  - Learn about the command line options by reading the manual pages.

Follow these steps:

  1. Look at the contents of the SMAP sea surface salinity data files. Find out: 
     - What physical measurement data does the **ssw** variable hold?
     - What are its units?
     - What is the map projection?
     - What is the pixel resolution in degrees?
  2. Create a 7-day composite of the **ssw** variable.
  3. Using your new composite data file, create a new variable called **ssw_kts** that holds the same data as **ssw** but with units in knots.
  4. Register your new **ssw_kts** data to a custom map of the Atlantic Ocean using a Mercator projection with 28 km resolution pixels and overall dimensions 500 rows by 500 columns, centred at [0°N, 30°W].
  5. Create an image of your Mercator map data using the **Wind-0-50** palette and a range of 0 to 50 knots, with coastlines and grid lines.
  6. Save all the commands you used for steps 2-5 in a Unix script or Windows batch file that accepts the SMAP NetCDF file names as inputs and runs completely automatically.
  7. Rather than performing step 3, is there another way that you can create an image of the **ssw** data in knots? Modify your script accordingly.
  8. Bonus question: If a sailboat started in Cuba and sailed along a straight line on your map to Spain, would it be taking the shortest route?

Assignment hints:

  - Look for help both in the manual pages and in the examples and information throughout Units 3 and 5.
  - You may need to run **CDAT** or **ncdump** for some information.
  - For step 3, you'll need to know the numerical conversion factor between the units. Also, take a look at the `--units` option in **cwmath**.
  - Use can use a web search and Google Maps to help you on some parts.

---

[« Previous](Automated-Data-Processing.md) · [Next »](Unit-5-Quiz.md)
