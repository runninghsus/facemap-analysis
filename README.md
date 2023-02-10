# Analyze facemap output

### requirements
``` commandline
pip install notebook h5py tqdm matplotlib numpy pandas tkinter
```

### run notebook
```commandline
cd facemap-analysis/notebooks
jupyter notebook notebooks
```

This code will
* split each keypoint into individual csv file
* organize by (frame, keypoint name, x, y, likelihood)
* compute euclidean distance 
* plot the distance change/frame, organized by keypoint