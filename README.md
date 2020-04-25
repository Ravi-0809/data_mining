## Mining Patterns in Higher Education Enrollment Data

### Introduction

----

This repository contains the work done for the research project of the Data Mining (CS F415) course in BITS Pilani, Hyderabad Campus. This aim of this project was to mine patterns in higher education enrollment data in India for the year of 2015. The abstract for the paper can be found below in this README file.

This repository also serves as a general purpose way of dealing with sparse, and a combination highly dimensional categorical data with census(ratio) data.

The repository contains the following structure:

1. **code** - Contains jupyter notebooks for the mentioned tasks
   1. *apriori*
   2. *classification*
   3. *clustering*
   4. *plots*
   5. *preprocessing*
2. **data**
   1. *student_enrollment.csv* - original dataset
   2. *basic_college_info.csv* - extra dataset merged with original
   3. *final_enc_dataset.csv* - merged dataset
   4. *merged_preprocessed.csv* - merged+preprocessed dataset
3. **demo** - contains the video demo for the final presentation 
4. **latex_report** - contains the Latex code base for the final report/paper
5. **reports** - contains a list of all reports throughout the project
6. **plots** - folder containing the plots generated for use in the paper

All the plots used for data visualization can be found using the plots jupyter notebook. The plots inside the folder are a small subset of all the generated plots.

### Abstract for the paper

----

```The  aim  of  this  paper  is  to  find  patterns,  relation-ships  and  draw  insights  from  enrollment  statistics  of  higher eduction in India. The data contains census of the population of each college, split by caste, gender and religion, and also contains details  about  the  enrolled  courses.  This  paper  details  the  use  of three  techniques  to  identity  patterns  in  this  dataset  -  Frequent pattern  mining  using  Apriori  rule,  Clustering  using  K-means and Classification using logistic regression and a neural network approach.  The  paper  details  the  complete  process  followed  in completing  the  data  mining  tasks  by  describing  the  problem,the  data  selection,pre-processing,  visualization,  and  the  mining tasks.  The  resulting  patterns  and  relationships  are  presented  at the  end  of  the  paper  comparing  the  results  from  each  of  the three mining techniques while also detailing the advantages and disadvantages of using the three techniques on this dataset which can be generalized to a high dimensional categorical data along with  highly  sparse  ratio  data  (census).```