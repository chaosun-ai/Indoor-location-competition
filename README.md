# Indoor-location-competition
Indoor Location &amp; Navigation code

There are 3 notebooks in this repo.


1. **'notebook-1-position-with-xgboost-lightgbm.ipynb'** used xgboost/lightgbm to generate a location prediction baseline.

2. **'notebook-2-generate-extra-grid-points.ipynb'** generated grid points in the hallway by generating masks for each of the floor plan.

3. **'notebook-3-positioning-using-imu.ipynb'** used the IMU sensor data to calculate the relative movement. It also used the outputs from notebook 1 and notebook 2 to improve the result.
