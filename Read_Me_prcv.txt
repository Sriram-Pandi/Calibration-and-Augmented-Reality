Sriram Pandi & Srinivas Peri 

OS: Windows 11
IDE: visual Studio 2022 
opencv version: 4.6.0. 2022-06-12, using build vc15

After downloading the ConsoleApplication1 zip file add it to your vs 2022 file path and
->Now go to the project icon on the top and to Properties.

->Then in properties go to C/C++ --> General 

->In General Additional Include Directories in place of C:\opencv\build\include give your_file_path\opencv\build\include. 

->Then go to Linker --> General

->In General Additional Library Directories in place of C:\opencv\build\x64\vc15\lib give your yoyu_file_path\opencv\build\x64\vc15\lib 

->Then Go to Linker --> Input

->In Input Additional Dependencies go to the dropdown and choose Edit and add opencv_world460.lib in the empty box.

->Apply all the changes and you should not see any errors.

Now go to Build  and click on build solution.
And Set your configuration manager to Release and x64
you are good to go.

##########################
Extesnsions-
Projecting pictures on to aruco marks was done to which as a addition multiple arucdo marks will be detected and image will be projected onto each aruco mark

###########################

Reason for late submission:
we are using 3 time travel days.

																		
																^^Thank you.^^