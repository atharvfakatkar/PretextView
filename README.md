# PretextView
Paired REad TEXTure Viewer. OpenGL Powered Pretext Contact Map Viewer.<br/>

PretextView is a desktop application for viewing pretex contact maps.<br/>

# Usage
Use the middle mouse button or the 'u' key to bring up the GUI. Pan by holding down the right mouse button. Click and drag with the left mouse button to select an are to zoom to. Scroll to zoom. A three button mouse is recomended.

# Requirments, running
OpenGL 3.3<br/>
2G of RAM<br/>

# Mac and Linux Builds
The prebuilt apps for Mac and Linux are highly recomended over building the app yourself.<br/>
The Mac app was built for MacOS 10.13.6<br/>
The Linux app was built for kernel 3.13<br/>

The Linux app is a binary can be launched from the command line.<br/>

More prebuilt versions will be added if there's demand for them.

# Windows Builds
Coming soon...

# Requirments, installation
Installation is only recomended if the prebuilt apps don't work for you.<br/>
Only unix (Mac and Linux) installations are supported currently, Windows installation will be coming in the future...<br/>

cmake<br/>
make<br/>
python (2 or 3) to run the installation script<br/>
clang or gcc to compile<br/>

Tested on Ubuntu linux kernel 3.13 with clang-9, gcc-4.9, gcc-5.5, gcc-8.3<br/>
Tested on MacOS 10.13.6 with clang-9, clang-10-apple<br/>

PretextView requires libdeflate (https://github.com/ebiggers/libdeflate). By default the install script will clone and build the libdeflate.a static library for compilation with PretextView. You can specify your own version to the install script if you wish (you'll have to specify appropriate liking flags as well if you specify a shared library).<br/>

PretextView requires GLFW (https://github.com/glfw/glfw). By default the install script will clone and build the libglfw3.a static library for compilation with PretextView. You can specify your own version to the install script if you wish (you'll have to specify appropriate liking flags as well if you specify a shared library).<br/>

run ./install to build (run ./install -h to see options)
