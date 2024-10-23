# Classification and Regression on AIRBNB data

    The main files of this repository are hosted in "notebooks" folder if you want to take a look at the analysis and results obtained.

In this repository we will apply some Machine Learning to **classify/perform regression** on an Airbnb dataset which contains rooms that were available to rent in Madrid, Spain. 

The attributes of this dataset are: 
* room_type
* price
* latitude 
* altitude
* minimum nights
* total reviews  
* availability
* calculated_host_listings_count
  
<br>

We will **classify** ```room_type``` based on the other attributes. Also, we will use ```price``` as the **dependent variable** and the other ones as **independent** while performing **regression**.

The Machine Learning Models we will apply are:

* Naives Bayes
* K-Nearest Neighbors (KNN) 
* Decision Trees
* Support Vector Machines (SVM)
  * Classifier:
    * LinearSVC 
    * LinearSVC with RBF Kernel
  * Regression:
    * LinearSVR
    * LinearSVR with RBF Kernel

## Preprocessing

Some of the tasks we will do in preprocessing are:

* **Distribution analysis**
  
![Alt text](images/image-1.png)

* **Correlation Matrix**

 ![Alt text](images/image-2.png)

* **Box and whisker plot**

![Alt text](images/image-3.png)

* **Scale values (StandardScaler)**
* **Trasform Pipeline (for scaling)**
* **Removing attributes**



