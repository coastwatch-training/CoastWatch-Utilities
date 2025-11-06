# The CoastWatch Utilities Online Course

Welcome! This course is about using the CoastWatch Utilities software package to help with processing satellite imagery and derived data products. The course covers working with data files (i) visually using a graphical user interface, and (ii) by typing commands at the Unix or Windows command prompts. No programming experience is needed, though it can be helpful when automating data processing.

### Introduction to the CoastWatch Utilities Course (7 mins)

[<img src="https://img.youtube.com/vi/RJ8wqwYf8RU/maxresdefault.jpg" width="600"/>](https://www.youtube.com/watch?v=RJ8wqwYf8RU)

View the [video transcript](Introduction-Video-Transcript.md)

### Prerequisites

The course material requires that you have the CoastWatch Utilities software installed so that you can follow along on your own computer and work with the example data provided. You can install the CoastWatch Utilities by visiting the [NOAA CoastWatch central operations](https://coastwatch.noaa.gov/) web site and downloading the software (available in the _Data Tools_ section). There are separate packages for Windows, Mac, and Linux. The command line tools in the software are more easily used if you also set the command line path (see Chapter 1 in the user's guide below on how to do that). The course material and user interface images are based on version 4.0.0 of the software released in May, 2024, but other versions can also be used.

### Resources

Throughout this course, we'll refer to sections of the [CoastWatch Utilities User's Guide](downloads/cwutils_ug_4_0_0.pdf) for documentation. You'll also need to download the [cw_utils_sample_data.zip](downloads/cw_utils_sample_data.zip) file that contains all the sample data for the course. Inside the ZIP file is a table of contents `00-Contents.txt` that describes all the data files — we'll use a subset of the data files in each unit.

### Table of Contents

- [**Unit 1 - Introduction to the CoastWatch Utilities**](./Unit-1-Introduction-to-the-CoastWatch-Utilities/README.md)
  - [CoastWatch Data Files](Unit-1-Introduction-to-the-CoastWatch-Utilities/CoastWatch-Data-Files.md)
  - [Graphical Versus Command Line](Unit-1-Introduction-to-the-CoastWatch-Utilities/Graphical-Versus-Command-Line.md)
  - [Software Functionality](Unit-1-Introduction-to-the-CoastWatch-Utilities/Software-Functionality.md)
  - [HDF and NetCDF Software](Unit-1-Introduction-to-the-CoastWatch-Utilities/HDF-and-NetCDF-Software.md)
  - [Unit 1 Quiz](Unit-1-Introduction-to-the-CoastWatch-Utilities/Unit-1-Quiz.md)
  - [Unit 1 Quiz Answers](Unit-1-Introduction-to-the-CoastWatch-Utilities/Unit-1-Quiz-Answers.md)

- [**Unit 2 - Basics of the CoastWatch Data Analysis Tool**](Unit-2-Basics-of-the-CoastWatch-Data-Analysis-Tool/README.md)
  - [Opening a Data File](Unit-2-Basics-of-the-CoastWatch-Data-Analysis-Tool/Opening-a-Data-File.md)
  - [Color Palette and Enhancement Range](Unit-2-Basics-of-the-CoastWatch-Data-Analysis-Tool/Color-Palette-and-Enhancement-Range.md)
  - [Data Overlays](Unit-2-Basics-of-the-CoastWatch-Data-Analysis-Tool/Data-Overlays.md)
  - [Navigating Within the Data View](Unit-2-Basics-of-the-CoastWatch-Data-Analysis-Tool/Navigating-Within-the-Data-View.md)
  - [Data Export](Unit-2-Basics-of-the-CoastWatch-Data-Analysis-Tool/Data-Export.md)
  - [Unit 2 Assignment](Unit-2-Basics-of-the-CoastWatch-Data-Analysis-Tool/Unit-2-Assignment.md)
  - [Unit 2 Quiz](Unit-2-Basics-of-the-CoastWatch-Data-Analysis-Tool/Unit-2-Quiz.md)  
  - [Unit 2 Quiz Answers](Unit-2-Basics-of-the-CoastWatch-Data-Analysis-Tool/Unit-2-Quiz-Answers.md)  
  
- [**Unit 3 - Command Line Tools for Extracting File Information**](Unit-3-Command-Line-Tools-for-Extracting-File-Information/README.md)
  - [Data File Contents (cwinfo)](Unit-3-Command-Line-Tools-for-Extracting-File-Information/Data-File-Contents-cwinfo.md)
  - [Rendering Images (cwrender)](Unit-3-Command-Line-Tools-for-Extracting-File-Information/Rendering-Images-cwrender.md)
    - [Color Enhancement Images](Unit-3-Command-Line-Tools-for-Extracting-File-Information/Color-Enhancement-Images.md)
    - [Color Composite Images](Unit-3-Command-Line-Tools-for-Extracting-File-Information/Color-Composite-Images.md)
    - [Colored Vector Images](Unit-3-Command-Line-Tools-for-Extracting-File-Information/Colored-Vector-Images.md)
    - [Hybrid Images](Unit-3-Command-Line-Tools-for-Extracting-File-Information/Hybrid-Images.md)
  - [Statistics Computations (cwstats)](Unit-3-Command-Line-Tools-for-Extracting-File-Information/Statistics-Computations-cwstats.md)
  - [Sampling Locations (cwsample)](Unit-3-Command-Line-Tools-for-Extracting-File-Information/Sampling-Locations-cwsample.md)
  - [Data Export (cwexport)](Unit-3-Command-Line-Tools-for-Extracting-File-Information/Data-Export-cwexport.md)
  - [Unit 3 Assignment](Unit-3-Command-Line-Tools-for-Extracting-File-Information/Unit-3-Assignment.md)
  - [Unit 3 Quiz](Unit-3-Command-Line-Tools-for-Extracting-File-Information/Unit-3-Quiz.md)
  - [Unit 3 Quiz Answers](Unit-3-Command-Line-Tools-for-Extracting-File-Information/Unit-3-Quiz-Answers.md)
  
- [**Unit 4 - More in Depth with the CoastWatch Data Analysis Tool**](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/README.md)
  - [Mask Overlays](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Mask-Overlays.md)
    - [Bitmask Overlays](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Bitmask-Overlays.md)
    - [Multilayer Mask Overlays](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Multilayer-Mask-Overlays.md)
    - [Expression Mask Overlays](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Expression-Mask-Overlays.md)
  - [Topographic and Bathymetric Contours](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Topographic-and-Bathymetric-Contours.md)
  - [Shape Overlays](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Shape-Overlays.md)
  - [Saving and Loading Overlay Groups](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Saving-and-Loading-Overlay-Groups.md)
  - [Surveying Data Variables](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Surveying-Data-Variables.md)
  - [Drawing Annotations](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Drawing-Annotations.md)
  - [Color Composite Mode](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Color-Composite-Mode.md)
  - [Unit 4 Assignment](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Unit-4-Assignment.md)
  - [Unit 4 Quiz](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Unit-4-Quiz.md)
  - [Unit 4 Quiz Answers](Unit-4-More-in-Depth-with-the-CoastWatch-Data-Analysis-Tool/Unit-4-Quiz-Answers.md)
  
- [**Unit 5 - Command Line Tools for Data Manipulation**](Unit-5-Command-Line-Tools-for-Data-Manipulation/README.md)
  - [Generic Variable Math (cwmath)](Unit-5-Command-Line-Tools-for-Data-Manipulation/Generic-Variable-Math-cwmath.md)
  - [Registration to a Map Projection (cwregister2)](Unit-5-Command-Line-Tools-for-Data-Manipulation/Registration-to-a-Map-Projection-cwregister2.md)
  - [Creating Map Projections (cwmaster)](Unit-5-Command-Line-Tools-for-Data-Manipulation/Creating-Map-Projections-cwmaster.md)
  - [Spatial and Temporal Composites (cwcomposite)](Unit-5-Command-Line-Tools-for-Data-Manipulation/Spatial-and-Temporal-Composites-cwcomposite.md)
  - [Direct Software Library Access (cwscript)](Unit-5-Command-Line-Tools-for-Data-Manipulation/Direct-Software-Library-Access-cwscript.md)
  - [Automated Data Processing](Unit-5-Command-Line-Tools-for-Data-Manipulation/Automated-Data-Processing.md)
  - [Unit 5 Assignment](Unit-5-Command-Line-Tools-for-Data-Manipulation/Unit-5-Assignment.md)
  - [Unit 5 Quiz](Unit-5-Command-Line-Tools-for-Data-Manipulation/Unit-5-Quiz.md)
  - [Unit 5 Quiz Answers](Unit-5-Command-Line-Tools-for-Data-Manipulation/Unit-5-Quiz-Answers.md)

- [Suggested Short Courses](Suggested-Short-Courses.md)

### Feedback

You can email questions, comments, and suggestions on this course or the CoastWatch Utilities software to the CoastWatch help desk at [coastwatch.info@noaa.gov](mailto:coastwatch.info@noaa.gov). 

For feedback on the software itself and/or bug reports, you should include the following information:

  1. **Version and operating system** — for example _CoastWatch Utilities 3.7.1 on Windows 10_.
  2. **Data file format and origin** — for example _CoastWatch NetCDF files obtained from the CoastWatch web site_. If the data origin is unknown, include some example data filenames.
  3. **How to reproduce the issue** — if sending a bug report or asking for clarification, we also need: 
  4. **Command line tool** — a transcript of the terminal session. You can cut and paste the contents of the command used and the output directly into the email.
  5. **Graphical interface tool** — a list of steps to reproduce the problem. For example, _Open data file X, click this button, then that button, etc._

