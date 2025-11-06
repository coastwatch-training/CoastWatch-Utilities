# Unit 3 Quiz Answers

### Question 1

Documentation for the command line tools is only available in the CoastWatch Utilities User's Guide.

- [ ] True

- [x] False

**General feedback:** The command line tools are documented in the appendices of the user's guide, but also are accessible from the Unix command line as man pages.  The user's guide Chapter 1 has details on how and where to set the PATH and MANPATH variables for easy operation on Linux and Mac.

### Question 2

The **cwinfo** tool prints out: (choose all answers that apply)

- [x] Date and time

- [x] Projection

- [x] Data variables

- [ ] Modification history

**General feedback:** The modification history is often encoded into a data file with the attribute name **history**, but the **cwinfo** tool doesn't show that information.  For displaying full file metadata, you can try using **ncdump**, **hdp**, or **HDFView** (linked from the [HDF and NetCDF Software](../Unit-1-Introduction-to-the-CoastWatch-Utilities/HDF-and-NetCDF-Software.md) page), or **CDAT** or **hdatt** (CoastWatch Utilities tools).

### Question 3

The **cwrender** tool creates different types of images including: (choose all answers that apply)

- [x] Color enhancements with a color bar legend

- [x] Plots of colored vectors or wind barbs

- [x] Three-variable RGB composites

- [ ] Contour plots of variable data

**General feedback:** The **cwrender** tool doesn't create contour plots, but you can create plots with contour-like steps by specifying `--function stepN` where N is the number of steps that you want.  Then ranges of values in the output image are easier to see.

### Question 4

The logo in the upper-right corner of **cwrender** output images can't be changed.

- [ ] True

- [x] False

**General feedback:** This wasn't mentioned in this module, but **cwrender** takes a `--logo` option to specify your own logo file, and has some built in logos discoverable using the `--logolist` option.

### Question 5

One of the following is _not_ a function of the **cwstats** tool:

- [ ] Computes the minimum, maximum, and mean of data variables

- [ ] Can limit computation to a specified fraction of the total data

- [ ] Shows the count of valid data values used in the computation

- [x] Accepts a geographic name and radius to limit the computation

**General feedback:** Many of the **cwstats** tool features are shown on the [Statistics Computations (cwstats)](Statistics-Computations-cwstats.md) page, and the `--region` options accepts a latitude, longitude, and radius, but not a geographic name.

### Question 6

The **cwsample** tool is a good way to get data from specific geographic locations in a data file into a comma-separated value (CSV) file for a spreadsheet program like Excel.

- [x] True

- [ ] False

**General feedback:** The [Sampling Locations (cwsample)](Sampling-Locations-cwsample.md) page shows an example of this operation.

### Question 7

One of the following is _not_ an output format supported by the **cwexport** tool:

- [x] ESRI shapefile

- [ ] Raw binary values

- [ ] GeoTIFF with 32-bit floating-point values

- [ ] NetCDF 4

**General feedback:** The output formats for **cwexport** are shown on the [Data Export (cwexport)](Data-Export-cwexport.md) page, and ESRI shapefile format is not among them.  Shapefiles aren't generally considered a scientific data format.

---

[« Previous](Unit-3-Quiz.md)

