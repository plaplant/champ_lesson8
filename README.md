# Champ Lesson 8
In this section of the bootcamp, we will be working with raw data from HERA. As part of it, we need to learn how to retrieve raw data. The interface for doing this is called the Librarian, which is currently hosted at Penn.

## Logging in to the Librarian
Information for logging into the librarian is not public. Please follow the instructions at the following link to connect: http://herawiki.berkeley.edu/doku.php/librarian

## Retrieving a specific file
We'll be working with a specific file of HERA data, which we can find with the search bar. We want to download the specific observation `zen.2457796.20174.xx.HH.uvc`. The file name reflects some of the metadata of the observation: the string `2457796.20174` is the decimal Julian date corresponding to the start of the observation. `xx` is the polarization state of the data. `HH` reflects that this is from the "HERA hex" part of the array. The file extension `.uvc` shows that this is a raw `.uv` file that has had some preliminary `c`orrections applied to it.

To download the file from the librarian, go to "search" and enter in the text field:
```
{"name-like": "zen.2457796.20174.xx.HH.uvc"}
```
Click on the file to download it.
