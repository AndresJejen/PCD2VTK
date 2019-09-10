# PCD2VTK

In this repository you can convert your PCD files (Point Cloud) to a VTK file (Mesh and surface format).   
Althought this code clean all the ```NAN``` points.   
You can watch the final file in ```.vtk``` format with the free vtk visualizer online or in your pc.   

## Convertion Type File Steps   
- 1. You have to install all PCL Library on your PC. (I´m using Ubuntu with WSL on Windows 10) please follow this repo for install all.   
    https://github.com/AndresJejen/PCD-Viewer-Universal   
- 2. Clone this repo   
- 3. Compile the code with cmake (instructions here too https://github.com/AndresJejen/PCD-Viewer-Universal)   
- 4. Execute the script ```./pcd2vtk <NAME_OF_YOUR_PCD_FILE.pcd>```   

The code generates a result.vtk file in your drectory project.  

## Visualization vtk FIle  

You must have install npm and nodejs   
Visualizer package here: https://www.npmjs.com/package/itk-vtk-viewer   
Install with this: ```npm i -g itk-vtk-viewer```
Execute visualizer with this on your command shell: ```itk-vtk-viewer```   
just click on the screen and up the .vtk file, wait and enjoy it.   


### Andres Jejen on Twitter @andres_jejen
### Medium Page https://medium.com/@andresjejen



