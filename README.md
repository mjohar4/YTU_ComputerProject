3D LIDAR BASED ODOMETRY WITH CNN-RNN DEEP LEARNING NETWORK-SIMULATION

This project aims to make use of deep learning techniques to produce a model that
takes the readings data of a 3D LiDAR scanner as input and estimates as output the
change in two poses indicated by LiDAR scans in form of six values that represent the
change in 6DOF of a vehicle. A virtual environment is prepared to test the model. The
proposed method can be a replacement for position information of the wheel encoders
of GPS data when the data is absent.



The order of creating the files is:

1-read_kitti.ipynb
2-img_processing.ipynb
3-model_CNN_RNN_train.ipynb
4-odometry-estimation-test-result.ipynb

None of these files is required to run the others.
every file can be run separately.

But 2-img_processing.ipynb need to be provided with kitti dataset (80 GB)
3-model_CNN_RNN_train.ipynb and 4-odometry-estimation-test-result.ipynb have the code to download the dataset from Google Drive. It is preferable to run them on Google Colab or Kaggle.


Required Libraries:
Opencv
Open3d
PyTorch
Pandas

And other basic libraries.
