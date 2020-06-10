# box_utils
build box_utils under windows. Used in maskrcnn, RRPN, and other rotation rpn networks

cd path/box_utils

python setup.py build_ext --inplace

cd path/box_utils/cython_utils

python setup.py build_ext --inplace

Important Info：

for different cuda version

modify the 43~68 lines in setup.py

library_dirs=['C:\\Program Files\\NVIDIA GPU Computing Toolkit\\CUDA\\v9.0\\lib\\x64'],

according to your cuda version.

It has been tested success in cuda 9, and cuda 10. For other versions, it has not been tested. 
