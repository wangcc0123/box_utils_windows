# box_utils
build box_utils under windows. Used in maskrcnn, RRPN, and other rotation rpn networks

success under cuda 8.  other version need to be tested.

cd path/box_utils
python setup.py build_ext --inplace

cd path/box_utils/cython_utils
python setup.py build_ext --inplace
