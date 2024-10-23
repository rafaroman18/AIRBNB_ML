# Classification and Regression on AIRBNB data

# Introduction 

In this repository we will apply some Machine Learning to **classify/perform regression** on an Airbnb dataset which contains rooms that were available to rent in Madrid, Spain. 

# Models

The Machine Learning Models we will apply are:

* Naives Bayes
* K-Nearest Neighbors (KNN) 
* Decision Trees
* Support Vector Machines (SVM)
  * Classifier:
    * LinearSVC 
    * SVC with RBF Kernel
  * Regression:
    * LinearSVR
    * SVR with RBF Kernel

# Dataset

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

Also, we will be using jupyter notebooks during the process to **analyse the data, visualize the results and explain each section** all in the same file. We will be performing Bayes, KNN and Decision Trees in the first file and SVM in the second

# Preprocessing

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

# Results

The results, analysis and explanation are available in each notebook.