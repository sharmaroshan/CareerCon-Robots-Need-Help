# CareerCon-Robots-Need-Help-
It is Data Science and Machine Learning Competition Hosted by Kaggle where we have to perform multi-class classification on the labels, a  very good amount of feature engineering, data preprocessing, data visualizations and modelling is done on the data set to get a good accuracy using random forest and xg boost classifier

CareerCon 2019 is upon us!

CareerCon is a digital event all about landing your first data science job — and registration is now open! Ahead of the event, we have a fun competition to get you started. See below for a unique challenge and opportunity to share your resume with select CareerCon sponsors. Read more about CareerCon 2019 here.

“CareerCon”

___________________________________

# The Competition

Robots are smart… by design. To fully understand and properly navigate a task, however, they need input about their environment.

In this competition, you’ll help robots recognize the floor surface they’re standing on using data collected from Inertial Measurement Units (IMU sensors).

We’ve collected IMU sensor data while driving a small mobile robot over different floor surfaces on the university premises. The task is to predict which one of the nine floor types (carpet, tiles, concrete) the robot is on using sensor data such as acceleration and velocity. Succeed and you'll help improve the navigation of robots without assistance across many different surfaces, so they won’t fall down on the job.

Special thanks for making this competition possible:
The data for this competition has been collected by Heikki Huttunen and Francesco Lomio from the Department of Signal Processing and Damoon Mohamadi, Kaan Celikbilek, Pedram Ghazi and Reza Ghabcheloo from the Department of Automation and Mechanical Engineering both from Tampere University, Finland. We at Kaggle would like thank them all for kindly donating the data that has made this competition possible!

# Dataset

X_[train/test].csv - the input data, covering 10 sensor channels and 128 measurements per time series plus three ID columns:

-row_id: The ID for this row.

-series_id: ID number for the measurement series. Foreign key to y_train/sample_submission.

-measurement_number: Measurement number within the series.

The orientation channels encode the current angles how the robot is oriented as a quaternion (see Wikipedia). Angular velocity describes the angle and speed of motion, and linear acceleration components describe how the speed is changing at different times. The 10 sensor channels are:

orientation_X

orientation_Y

orientation_Z

orientation_W

angular_velocity_X

angular_velocity_Y

angular_velocity_Z

linear_acceleration_X

linear_acceleration_Y

linear_acceleration_Z

y_train.csv - the surfaces for training set.

-series_id: ID number for the measurement series.

-group_id: ID number for all of the measurements taken in a recording session. Provided for the training set only, to enable more cross validation strategies.

-surface: the target for this competition.

sample_submission.csv - a sample submission file in the correct format.
