# OECD File Format Specification
Open Eddy Current Data format specification

## What is Open Eddy Current Data Format?
The open eddy current data format (.oecd) is an open-source format for storing data collected by eddy current probes. This format is designed to be small, flexible, and easy to use.

## Why use OECD?
Eddy current instruments produce a wide variety of data formats, but most are propriety, archaic, and just plain difficult to work with. The current “common” format for eddy current data are Comma Separated Value files (.csv), which—while easy to read—have large file sizes, and lack the metadata needed properly parse and display the file contents.
OECD is designed to act as a new “common” format, suitable a wide variety of applications, ranging from R&D, to archiving old data, and even native use in commercial software.

## Design Goals
+   *Small File Sizes*: 
binary data storage, and built in compression, ensures extremely small file sizes
+   *Future-Proof*: 
support for 32-bit integers, and floating-point data storage will allow seamless integration with the next generation of eddy current instruments, and the flexibility of storing pre-calibrated data. 
+   *Open*: 
Fully documented, with example implementations, and a commercial-friendly open-source license
