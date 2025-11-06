# Unit 3 Assignment

The goal of this assignment is to:

  - Use the command line tools in the CoastWatch Utilities for working with data files (rendering, extracting information, etc).
  - Learn about the command line options by reading the manual pages.

Follow these steps:

  1. Look at the contents of the two Advanced Microwave Scanning Radiometer (AMSR) ice concentration files. Find out: 
     - Satellite name and country of origin
     - Start and end dates
     - Map projection
     - Pixel resolution
  2. Render images of the ice concentration in each file centered on Alaska at 2x magnification, showing black coastlines, gray land polygons, and white grid lines.
  3. Find the minimum, maximum, and mean ice concentration within a 200 km radius of Anchorage, Alaska from the January data file.
  4. Aerial photographs were taken during January of a number of locations around Alaska to verify the satellite ice concentration measurements. Create a CSV text file of satellite data values to import into Excel — the file should have a header line and lines of data with the latitude/longitude of each station, the ice concentration, the quality flags, and the data file row and column coordinates. The aerial photograph locations are as follows:
     - Photo 1: [57.55°N, 158.28°W]
     - Photo 2: [58.70°N, 160.14°W]
     - Photo 3: [58.07°N, 159.23°W]
     - Photo 4: [60.09°N, 152.18°W]
  5. Export the July ice concentration data to a binary grid file so that it can be used in ArcGIS. Make sure to also create a header file. Bonus question: What is the byte order in the ArcGIS file?

Assignment hints:

  - Use a web search and Google Maps to help you on some parts.
  - You can try using the **Ocean-ice** or **Blue-White** palettes for rendering ice concentration. 
  - Part (4) may require you to use a text editor.
  - Look for help both in the manual pages and in the examples and information throughout Unit 3.

---

[« Previous](Data-Export-cwexport.md) · [Next »](Unit-3-Quiz.md)
