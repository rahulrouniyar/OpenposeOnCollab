# OpenposeOnCollab 
# python 
The solution for error related to PYOPENPOSE has been solved. 
It was due to parameter PYBIND11_INSTALL which is set to OFF as default after configuring BUILD_PYTHON parameter in cmake.
So we need to set the parameter to ON and rebuild it.
