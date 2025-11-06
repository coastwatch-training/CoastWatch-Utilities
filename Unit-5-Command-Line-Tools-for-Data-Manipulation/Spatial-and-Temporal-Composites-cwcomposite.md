# Spatial and Temporal Composites (cwcomposite)

The **cwcomposite** tool combines data variables across multiple data files by computing a value at each pixel: mean, median, minimum, maximum, or latest value. There are generally two scenarios for using **cwcomposite**:

**Case 1** - Spatial composite over a short time period (~ 1 day):
<table>
  <tr>
    <td><img src="../images/spatial_composite_1.png" alt="Example spatial composite image 1/4"></td>
    <td><img src="../images/spatial_composite_2.png" alt="Example spatial composite image 2/4"></td>
    <td colspan="2" rowspan="2">Spatial composite result:<br><img src="../images/spatial_composite_5.png" alt="Example spatial composite result"></td>
  </tr>
  <tr>
    <td><img src="../images/spatial_composite_3.png" alt="Example spatial composite image 3/4"></td>
    <td><img src="../images/spatial_composite_4.png" alt="Example spatial composite image 4/4"></td>
  </tr>
</table>

**Case 2** - Temporal composite over a longer time period (days/weeks/months):

<table>
  <tr>
    <td><img src="../images/temporal_composite_1.png" alt="Example temporal composite image 1/4"></td>
    <td><img src="../images/temporal_composite_2.png" alt="Example temporal composite image 2/4"></td>
    <td colspan="2" rowspan="2">Temporal composite result:<br><img src="../images/temporal_composite_5.png" alt="Example temporal composite result"></td>
  </tr>
  <tr>
    <td><img src="../images/temporal_composite_3.png" alt="Example spatial composite image 3/4"></td>
    <td><img src="../images/temporal_composite_4.png" alt="Example spatial composite image 4/4"></td>
  </tr>
</table>

Type the following command to create a 7-day composite from daily SMAP sea surface salinity data:

`cwcomposite -v --match sss example_smap_salinity_apr_*.nc example_smap_salinity_apr_7day.hdf`

You should see the composite running in verbose mode as follows:

![Terminal screen showing cwcomposite running on SMAP salinity files](../images/cwcomposite_1.png)

The default for **cwcomposite** is to compute the mean value at each pixel — other composite methods are set using the `--method` option. You can view the output file in CDAT, or render it as follows:

`cwrender --enhance sss --range 30/40 --palette Ocean-haline --grid white --coast black/gray40 example_smap_salinity_apr_7day.hdf example_smap_salinity_apr_7day.png`

You should see the following image:

![Global SMAP sea surface salinity](../images/example_smap_salinity_apr_7day.png)

###  <img src="../images/address_book.png" alt="" height="24" align="top">  Bonus exercises:

  - Read the **cwcomposite** Unix man page or user's guide section. 
  - Add an option to the **cwcomposite** command line to compute the minimum value at each pixel.
  - Find out how to make **cwcomposite** mark a pixel invalid if the number of valid input values at the pixel is less than 5.
  - Suppose a researcher asked for an uninterrupted image of the Pacific Ocean. Try using **cwmaster** and **cwregister2** from the previous exercises to create one, for example:  
  
![Orthographic projection of SMAP sea surface salinity covering the North Pacific](../images/example_smap_salinity_apr_7day_ortho.png)

---

[« Previous](Creating-Map-Projections-cwmaster.md) · [Next »](Direct-Software-Library-Access-cwscript.md)
