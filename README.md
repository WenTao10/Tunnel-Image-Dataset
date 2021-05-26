# Tunnel-Image-Dataset
The tunnel image dataset aims to train a deep network to estimate vanishing points in the forward direction of the tunnel. In this dataset, each image has a unique camera rotation angle, and the label file stores the image name and vanishing point.

- The dataset is divided into real data and virtual data. The real dataset contains 2312 images covering 300 different tunnel sections, while the virtual dataset contains 9600
- images with camera pitch and pan angles within [-40,0] and [-40,40], respectively.
- The training set accounts for 70%, and the test set accounts for 30%.
- These images are available in RGB format and 1920x1080 resolution.
- The average camera height is about 6m.
