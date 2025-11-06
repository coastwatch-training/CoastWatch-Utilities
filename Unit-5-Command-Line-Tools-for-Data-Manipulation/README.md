# Unit 5 Overview

In this unit, we'll build on the material in [Unit 3 - Command Line Tools for Extracting File Information](../Unit-3-Command-Line-Tools-for-Extracting-File-Information/README.md), and learn these new skills:

  - Computing new data using math expressions (cwmath)
  - Converting data to map projections (cwregister2)
  - Creating map projection specifications (cwmaster)
  - Combining data from different files (cwcomposite)
  - Direct access to CoastWatch software functions (cwscript)
  - Automated data processing

### Prerequisites

To follow along and perform your own command line calls, the CoastWatch Utilities command line tools must be installed. If your operating system is Windows or Mac, there was an option in the CoastWatch Utilities installation wizard for the command line tools. For Linux users, the command line tools are always included in the tar.gz distribution file. For all operating systems, the command line tools reside in the **bin/** directory of the installation path. In the [course overview](../README.md) we mentioned that the command line tools are most easily used when the PATH variable is set in your terminal program:

  - On Windows this is called the **Command Prompt** or **Windows PowerShell**
  - On Linux it's either **xterm** or **Terminal**
  - On Mac it's called **Terminal** and is found inside the **Utilities** folder of the system **Applications**

Linux and Mac users will also benefit from setting the MANPATH so that the Unix **man** program will find the command line tool manual pages. See the [CoastWatch Utilities User's Guide](../downloads/cwutils_ug_4_0_0.pdf) Chapter 1 for details on how and where to set the PATH and MANPATH variables. The user's guide also has all the manual pages for the command line tools in Appendix A as an alternative to using the Unix man pages.

### Resources

For the exercises in this unit, you'll need to download the [cw_utils_sample_data.zip](../downloads/cw_utils_sample_data.zip) file that contains all the sample data for the course. Inside the ZIP file is a table of contents `00-Contents.txt` that describes all the data files — we'll use a subset of the data files in this unit.

Supplementary reading material is available in the user's guide (see link above) in the following sections:

  - Chapter 2 - Common Tasks
  - Chapter 4 - Programmer's API
  - Appendix A.2 - Data Processing
  - Appendix A.3 - Graphics and Visualization
  - Appendix A.4 - Registration and Navigation
  - Appendix A.5 - Hidden command line options

If you prefer to learn by watching videos, there are two YouTube videos with a narrated demonstration of command line tool and CDAT features:

  - [CoastWatch Utilities 2021 Demo](https://youtu.be/wAjttnTBRBA)
  - [CoastWatch Utilities 2022 Demo](https://youtu.be/ZlSvOvd7LPU)

---

[Next »](Generic-Variable-Math-cwmath.md)
