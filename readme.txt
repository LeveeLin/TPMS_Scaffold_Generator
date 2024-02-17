TPMS_Scaffold_Generator Executable

1. Prerequisites for Deployment 

Verify that version 9.8 (R2020a) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2020a 
from the following link on the MathWorks website:

    https://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.

2. Files to Deploy and Package

Files to Package for Standalone 
================================
-TPMS_Scaffold_Generator.exe
-MCRInstaller.exe 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime included in package" link in the
    Deployment Tool.
-This readme file 



3. Definitions

For information on deployment terminology, go to
https://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.


4. Function of the TPMS_Scaffold_Generator

It offers three function tabs which are homogeneous tab, heterogeneous tab and multisymmetrical tab, respectively. Variables of the tabs include topology type, volume fraction, unit cell size, the length of architecture in X, Y, Z direction, accuracy, and the style of gradient and so forth. In addition, the tabs are able to determine whether to generate shell-based scaffold or skeleton-based scaffold. Therefore, TPMS_Scaffold_Generator can generate various TPMS scaffolds, especially ultralight and multisymmetrical scaffolds.


5. Process of installation
First setep: Run the MyAppInstaller_web.exe till the installation succeeds.
Second setep: Operate the TPMS_Scaffold_web.exe.
