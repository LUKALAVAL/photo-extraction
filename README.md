# photo-extraction

This project was developped for the PRAT course. The file `report.pdf` explains the project in detail.

Unzip the folders `data.zip` and `output.zip`. Make sure the project has the following structure :


> data/ \
____full_set/ \
_______... \
____test_set/ \
________bb_groundtruth_non_empty.csv \
_______bb_groundtruth.csv \
_______... \
____ark
\
\
output/ \
____full_set/ \
____global/ \
_______extraction/ \
__________... \
_______segmentation.csv \
____test_set/ \
_______global/ \
__________draft/ \
_____________... \
__________extraction/ \
_____________... \
__________segmentation.csv \
_______local/ \
__________draft/ \
_____________... \
__________extraction/ \
_____________... \
__________segmentation.csv
\
 \
detections.csv \
global_method.ipynb \
local_method.ipynb \
README.md \
report.pdf \
some_visuals.ipynb \
utils.ipynb