# An-already-compiled-GMP-library
Open VS 2019
1. Download the package and decompress it  
2. Create a C++ console application  
3. Project - > Property - > C/C++ -> Additional include directory  
Select the folder where the decompression is located  
Click OK and change the SDL check column to No  
4. Do not exit this window, click on the linker bar to expand  
Click the Attach library directory to add the.libs path  
Click OK, click Enter  
To edit the additional dependency, type libgmp.dll.a  
Click OK, then click Apply in the lower right corner, and click OK to exit  
5. Configure a 64-bit programming environment  
Click on the right drop-down menu to click on Configuration Manager, click on the right active Solution platform change to 64-bit  
6. Copy libgmp-10.dll from the. Libs directory in the GMP library file to the project folder  
