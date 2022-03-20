 # A Low-cost Real-time Human Activity Recognition System Based on Wearable Sensor and the Supervised Learning Algorithms 
	

### ** Abstract **
Human Activity Recognition system plays an important role in many application, including the healthcare field. This implementation uses machine learning algorithms based on the data from the accelerometer gives good recognition results. Therefore, designing low-cost, high recognition rate and real-time system is necessary.


### ** Dataset Information **
* The public dataset: 
[WISDM] (https://www.cis.fordham.edu/wisdm/dataset.php) collected data from a smartphone in front pants leg pocket with sampling frequency of 20 Hz. Dataset was collected from 29 participants performing 6 activities.

* Our recorded data: Our waist-worn device got data from accelerometer with sampling frequency of 50 Hz  and transfered data to a smartphone with Android operating system. A group of 16 volunteers (14 students and 2 older adults) conducted data recording for 4 activities. 
  

### ** Method **
First, dataset was collected from our proposed device in three axes Ax, Ay, Az. Then, we conducted windowing step, divided data stream into small segment and deployed sliding window. In each segment, statistical features extraction created vector carrying behavioral information. Last, the features selected would be trained to build classification model to classify behaviors.


### ** Table results **
| Evaluation Method   | Public dataset | Private dataset |
| :------------: | :------------: | :-------------: |
| Accuracy    | 95.3% | 99.2% |
| Sensitivity  | 94% | 98.5% |




