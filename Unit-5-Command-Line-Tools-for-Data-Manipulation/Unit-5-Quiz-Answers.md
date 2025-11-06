# Unit 5 Quiz Answers

### Question 1

The **cwmath** tool: (choose all answers that apply)

- [x] Computes a value at each pixel in the input data file

- [x] Handles multiple input data files

- [ ] Can save data to a 10-bit integer data type

- [x] Uses a C/C++/Java expression syntax

**General feedback:** The features of the **cwmath** tool are shown on the [Generic Variable Math (cwmath)](Generic-Variable-Math-cwmath.md) page.  You'll find in the manual page that the `--size` option allows for 8-bit, 16-bit, 32-bit, and 64-bit output data, but not 10-bit.  You could fit 10-bit data (0-1023) into the least significant bits of a 16-bit value.

### Question 2

The **cwregister2** tool can use multiple CPU threads in parallel.

- [x] True

- [ ] False

**General feedback:** The **cwregister2** tool runs by default in parallel mode.  You can change this behaviour using the `--serial` or `--threads` options.

### Question 3

The **cwmaster** tool can read and write map projection master templates for:

- [x] Polar Stereographic

- [x] Albers Equal Area

- [x] Mercator

- [ ] Icosahedral

**General feedback:** You can run the **cwmaster** tool to discover all the supported map projections.  They're also listed in Section B.6 - GCTP Appendices in the user's guide.  Icosahedral is not one of them, but it is a map projection — NOAA has a [printable demonstration](../downloads/etopo2icosahedron.pdf) of an icosahedral projection available. 

### Question 4

The **cwcomposite** tool accepts multiple input data files and computes at each pixel location:

- [x] The mean, median, minimum, maximum, or latest data value

- [ ] The difference between the largest and smallest data values

- [ ] The standard deviation of the data values

- [ ] The bitwise AND of all data values

**General feedback:** The full list of possibilities for computing a composite data value are listed on the **cwcomposite** tool manual page under the `--method` option.  By default the mean value is computed.  

### Question 5

Using a BeanShell script, the **cwscript** / **cwgscript** tools don't have access to the GUI part of the CoastWatch software library API.

- [ ] True

- [x] False

**General feedback:** All of the CoastWatch software library API is accessible from a BeanShell script.  An example of a GUI script is shown on the [Direct Software Library Access (cwscript)](Direct-Software-Library-Access-cwscript.md) page.  
### Question 6

Calls to the CoastWatch Utilities command line tools can be automated by running them from:

- [ ] Unix shell scripts

- [ ] Windows batch files

- [ ] Python code

- [x] Any of these programming languages

**General feedback:** Any programming language that can call a function to run a program can be used to run the CoastWatch command line tools.  For example, other options include Perl and C.

---

[« Previous](Unit-5-Quiz.md)


