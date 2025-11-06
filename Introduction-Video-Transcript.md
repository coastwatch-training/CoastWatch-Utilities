# CoastWatch Utilities Online Course Introduction Transcript

### Slide 1 - Introduction to Video - [00:00]

Hello, and welcome! This is an introduction video for the Coastwatch Utilities online course.  My name is Peter Hollemans and I'm the author of the Coastwatch Utilities software package, and I'm also the author of the online course. In this video I'll talk about what the CoastWatch Utilities are and hopefully give you an idea of what you can do with the software in your own work. I'll also talk about the sections of the course and what you can expect to learn in each section. Finally I'll finish up by providing you with links to demonstration videos from previous years so that you can see the software in action and get a sense of what it does. I'll also give you a link to the course itself.

### Slide 2 - Software Functionality - [00:49]

The NOAA CoastWatch program distributes satellite image data either directly from data servers to your data analysis environment, such as R, Python, or ArcGIS, or in data file formats that aren't recognized by most image viewers.  The CoastWatch Utilities is a package of software for viewing and processing those data files with some features that are specific to satellite image data.  The software can also be used by data providers to process data prior to distribution on a data server. The utilities read various formats of geographic data including HDF and NetCDF, both level 2 swath data and level 3 mapped data. The software is agnostic to the type or units of data as long as the pixels can be associated with the grid of latitudes and longitudes. They report on, process, and combine data by compositing or using math expressions, map level 2 data to projections, and generate images among other operations.  The CoastWatch Data Analysis Tool lets you do interactive analysis.

### Slide 3 - Course Description - [02:09]

The CoastWatch Utilities online course is part of a larger effort to provide advanced training material. The course has five units on different topics and it presents both original content and it also links to existing content online such as the user's guide, presentations, and demonstration videos. There are step-by-step examples of using the CoastWatch Data Analysis Tool with screenshots. We have exercises on using command line tools for common data processing tasks with the output that you would expect from the commands.  And in order to reinforce the content, there are bonus exercises that you can choose to do, assignments, quizzes and links to demonstration videos to watch.

### Slide 4 - Units 1-3 - [03:01]

Unit 1 of the course introduces the contents of a data file, the types of CoastWatch Utilities functionality that you'll find, and links to some other NetCDF and HDF software that I've found to be useful that complement the CoastWatch Utilities tools. Unit 2 introduces the CoastWatch Data Analysis Tool, how to open data files and assign a color palette and range to the data image, how to overlay graphics layers like coastlines and grid lines, and how to export data to an image or some other data format. Unit 3 introduces the basic command line tools to get file information — so, contents of the file, statistics of the data, and data values at a set of user-specified sample points. You'll also learn how to convert data files to images and other formats from the command line so that you can use that in scripts. All of the data plots in this video were created using the CoastWatch Utilities so you'll be able to create similar images.

### Slide 5 - Units 4-5 - [04:12]

Unit 4 of the course shows more in the CoastWatch Data Analysis Tool of ways to highlight data values with mask overlays and save the overlays  that you commonly use to customize groupings. You'll also learn how to overlay ESRI shapefiles, perform a survey of the data to generate line plots and statistics, and create red/green/blue composite images from three satellite sensor bands. Finally, Unit 5 is all about processing data files — so, transforming data to a map projection, combining data from different time steps into one file, writing your own math expressions to combine sensor bands, and how to write reusable data processing scripts.

### Slide 5 - Downloading - [05:05]

Now, if you want to download and try the software before taking the course you can find it on the CoastWatch central operations website. The source code and links to installable packages and beta versions are also on GitHub. We create new versions and post them online about every six months to a year. The latest version as of this video is 3.8.0.

### Slide 6 - Demonstration Videos - [05:32]

Now, there are several videos of using the package and two of the latest demonstrations are on YouTube — you can click these links and watch them to get a sense of what the software does. The 2021 demo shows an example of compositing and rendering chlorophyll data and viewing the output in the CoastWatch Data Analysis Tool. The 2022 video shows downloading a level 2 VIIRS chlorophyll data file, getting the file information, calculating statistics, a true color correction, registration from level 2 to a map projection, rendering to an image, and viewing the level 2 and 3 data in the CoastWatch Data Analysis Tool.

### Slide 7 - Summary - [06:18]

So to wrap up and summarize I've talked about what the CoastWatch Utilities software is used for, the various units in the online course, and where to get the software and see some demo videos. The course itself is linked from the learning portal on the CoastWatch central operations website and I've also provided a direct link to it here. Thank you very much for your attention and for your interest in the CoastWatch Utilities!

