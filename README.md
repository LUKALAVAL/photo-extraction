# photo-extraction

This project was developped for the PRAT course. The file `report.pdf` explains the project in detail.

Unzip the folders `data.zip` and `output.zip`. Make sure the project has the following structure :


> data/ \
&ensp; full_set/ \
&ensp;&ensp; ... \
&ensp; test_set/ \
&ensp;&ensp; bb_groundtruth_non_empty.csv \
&ensp;&ensp; bb_groundtruth.csv \
&ensp;&ensp; ... \
&ensp; ark
\
\
output/ \
&ensp; full_set/ \
&ensp; global/ \
&ensp;&ensp; extraction/ \
&ensp;&ensp;&ensp; ... \
&ensp;&ensp; segmentation.csv \
&ensp; test_set/ \
&ensp;&ensp; global/ \
&ensp;&ensp;&ensp; draft/ \
&ensp;&ensp;&ensp;&ensp; ... \
&ensp;&ensp;&ensp; extraction/ \
&ensp;&ensp;&ensp;&ensp; ... \
&ensp;&ensp;&ensp; segmentation.csv \
&ensp;&ensp; local/ \
&ensp;&ensp;&ensp; draft/ \
&ensp;&ensp;&ensp;&ensp; ... \
&ensp;&ensp;&ensp; extraction/ \
&ensp;&ensp;&ensp;&ensp; ... \
&ensp;&ensp;&ensp; segmentation.csv
\
 \
detections.csv \
global_method.ipynb \
local_method.ipynb \
README.md \
report.pdf \
some_visuals.ipynb \
utils.ipynb