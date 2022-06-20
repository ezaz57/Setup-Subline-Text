# Setup-Subline-Text


OCreate three new files as shown below and make sure all of them are in the same folder.

file.cpp: The file for writing the code.
inputf.in: The file where we will be giving the input.
outputf.out: The file where the output will be displayed.
Now, perform the following steps:

Select View > Layout > Columns : 3. This will create three columns in the workspace. Move the three files into three columns.
Select View > Groups > Max Columns : 
2. Select the build system we just created from Tools > Build System > CP.
Below is the image to illustrate the same:
Precompile Headers:
The compilation time can speed up by precompiling all the header files i.e., by precompiling the bits/stdc++.h header file. Perform the following steps for doing so:

Navigate to the stdc++.h file. By default, this file is located at: “C:\MinGW\lib\gcc\mingw32\6.3.0\include\c++\mingw32\bits”
Open the Power shell or the command window on the current folder. For this right-click while pressing the Shift key.
Run the below command to compile the header.
g++ stdc++.h -std=c++17
