# Self-Driving-Cars-Using-Keras

## Demo
<img src="https://github.com/saireddyavs/Self-Driving-Cars-Using-Keras/blob/master/Demo.gif"/>



## Dataset
- Approximately 45,500 images, 2.3GB. One of the original datasets made by [SullyChen](https://github.com/SullyChen/) in 2017. Data was recorded around Rancho Palos Verdes and San Pedro California.
- 25 minutes = 25{min} x 60{1 min = 60 sec} x 30{fps} = 45,000 images ~ 2.3 GB
- [You Can Download Dataset from Here](https://drive.google.com/file/d/0B-KJCaaF7elleG1RbzVPZWV4Tlk/view?usp=sharing)
- How the data was recorded by SullyChen can is explained in one his medium articles. [link to SullyChen medium article](https://medium.com/@sullyfchen/how-a-high-school-junior-made-a-self-driving-car-705fa9b6e860)
- You can see how the images are recorded from this [Video](https://www.youtube.com/watch?v=nzKzee-Mhnc&feature=youtu.be).




## Description
- self_driving_using_keras.ipynb file contains 4 different Architectures trained on the data for 100 epochs and selected the 2 best models that converge loss faster.
- Best_Model_1.ipynb , Best_Model_2.ipynb contains the model trained for 1000 epochs.
- Best_Model_1 and Best_Model_2 files contains **CSV**,**Excel**,**Json** files of history object showing loss on epoch  1-1000. The Output **Model** is also saved in it.
-run_model_one and run_model_two are **Python** files for running the model on dataset.


## Some-Results

  **Got Best Results Using Nvidia's Architecture. It is used in Best_Model_1**



  *These are the Results after 1000 epochs.*

- ### Best_Model_1

  | | val_loss | loss|
  | --- | --- | --- |
  |min |	0.155158 |	0.006902|
  |max |	0.314412 	|0.264360|
  |mean |	0.175964 |	0.011505|

- ### Best_Model_2
| | val_loss | loss|
| --- | --- | --- |
|min| 	0.170120 |	0.009587|
|max |	0.822659 |	0.292208|
|mean |	0.316213 |	0.014819|





### Other Larger Datasets you can train on
- [ Udacity:](https://medium.com/udacity/open-sourcing-223gb-of-mountain-view-driving-data-f6b5593fbfa5)
70 minutes of data ~ 223GB
Format: Image, latitude, longitude, gear, brake, throttle, steering angles and speed<br>
-  [Udacity Dataset:](https://github.com/udacity/self-driving-car/tree/master/datasets) Dataset ranging from 40 to 183 GB in different conditions
-  [Comma.ai Dataset ](https://github.com/commaai/research)[80 GB Uncompressed]
- [Apollo Dataset](http://data.apollo.auto/?locale=en-us&lang=en) with different environment data of road

### Credits & Inspired By
-  SullyChen [github page](https://github.com/SullyChen/Autopilot-TensorFlow)
- cyanamous [github page](https://github.com/cyanamous/Self-Driving-Car-)
-  Research paper: [End to End Learning for Self-Driving Cars by Nvidia.](https://arxiv.org/pdf/1604.07316.pdf)
-  Nvidia blogs:
  -  https://devblogs.nvidia.com/deep-learning-self-driving-cars/
  -  https://devblogs.nvidia.com/explaining-deep-learning-self-driving-car/
- https://mc.ai/self-driving-car-on-indian-roads/

- http://on-demand.gputechconf.com/gtc/2018/presentation/s8748-simulate-and-validate-your-dnn-inference-with-catia-before-adas-industrial-deployment.pdf

- https://www.ctolib.com/amp/cyanamous-Self-Driving-Car-.html
