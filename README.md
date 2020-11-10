# Calculator

The project was carried out as part of the C programming course in the spring semester of the second year of MIPT. 
We worked in a team of 3 people. We have implemented a scientific calculator console application. 

*Detailed instructions in Russian are in [the file](https://github.com/Lerafdn/Calculator/blob/master/description.pdf)*

## Description
App is designed for calculations with floating point numbers. The calculator operates with eight-digit decimal numbers. If the number is fractional, then one character is used under the decimal point and the number can be seven-digit.

## Install & Run (Mac)
Put these file in project directory:

- computations.cpp
- computations.hpp
- frame.cpp
- frame.hpp
- comp-mac

If you don't have the wxWidgets library installed:
```bash
brew install wxmac
```

Compilation:
```bash
./comp-mac computations frame
./computations
```
