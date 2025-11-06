# Unit 4 Quiz Answers

### Question 1

Unscramble the table below by matching each task that you want to perform in the CoastWatch Data Analysis Tool (CDAT) in the left column with the software feature in the right column:

| Task | CDAT Feature |
|:---- |:------------ |
| Create a true color image | *Color composite* |
| Draw a 1000 meter bathymetric contour | *Topography overlay* |
| Draw ESRI format polygon lines | *Shape overlay* |
| Label a place with its name | *Drawing annotations* |
| Create a histogram plot of a rectangular area | *Data surveys* |
| Highlight in pink all values greater than 20 | *Expression mask overlay* |

### Question 2

A bitmask overlay depends on several inputs: (choose all answers that apply)

- [x] Color to mask the data pixels

- [x] Quality variable

- [x] Integer value to use in the bitwise AND operation

- [ ] Quality variable flag_meanings attribute

**General feedback:** A bitmask overlay needs a color, variable, and mask value.  The flag_meanings attribute if it exists is useful to help the data user make sense of the quality variable.  See the [Bitmask Overlays](Bitmask-Overlays.md) page for more details.

### Question 3

A multilayer mask overlay is useful for:

- [x] Looking at the individual bits stored in a quality variable

- [ ] Saving and loading multiple overlay layers

- [ ] Layering multiple variables into a composite image

- [ ] Comparing the same geographic area across multiple data files

**General feedback:** Although all the answers are features of CDAT, multilayer mask overlays are a way of turning on and off the individual bits stored in a quality variable to see what features in a data variable are being masked.  See the [Multilayer Mask Overlays](Multilayer-Mask-Overlays.md) page for more information.

### Question 4

CDAT contains a fixed set of topographic and bathymetric contours for use in a topography overlay.

- [ ] True

- [x] False

**General feedback:** Topographic and bathymetric contours are computed on-the-fly from an elevation data file built into CDAT.  See the [Topographic and Bathymetric Contours](Topographic-and-Bathymetric-Contours.md) page for examples of how to use this feature. 

### Question 5

A shape overlay can render data from:

- [x] ESRI shapefiles

- [ ] KML files

- [ ] CSV files

- [ ] NetCDF trajectory files

**General feedback:** ESRI shapefiles are an industry standard way of storing shape information for polygons and lines.  See the [Shape Overlays](Shape-Overlays.md) page for examples of shapefile rendering.  Other geographic formats such as KML, CSV, and NetCDF are not supported for shape data.

### Question 6

Help and examples for using CDAT are available: (choose all answers that apply)

- [x] From YouTube videos

- [x] In the user's guide

- [x] From in-application help within CDAT

- [x] From the CoastWatch help desk at coastwatch.info@noaa.gov

**General feedback:** These are all ways of getting help on how to use CDAT.

### Question 7

Overlay layers cannot be saved and used again for another data file.

- [ ] True

- [x] False

**General feedback:** Overlay layers can be grouped together, saved, and re-loaded.  The page on [Saving and Loading Overlay Groups](Saving-and-Loading-Overlay-Groups.md) shows how to do this.

### Question 8

Performing a data survey on a variable results in: (choose all answers that apply)

- [x] Data statistics

- [x] An X versus Y plot

- [ ] A PDF report

- [x] Survey extent lat/lon values

**General feedback:** Performing a survey results in a report on the data extents, statistics, and a plot.  See the [Surveying Data Variables](Surveying-Data-Variables.md) page for more details.

### Question 9

Creating a color composite image can only be done with visible data in the 665 nm, 560 nm, and 490 nm wavelength range.

- [ ] True

- [x] False

**General feedback:** Although Sentinel-2 MSI 665/560/490 bands work well to create a true color image (not shown in this course), <span style="text-decoration: underline;">any</span> combination of data variables in a file can be used to create a color composite image.  The exercises on [Color Composite Mode](Color-Composite-Mode.md) in CDAT show examples and link to material on other variable combinations and how to interpret them.

---

[« Previous](Unit-4-Quiz.md)

