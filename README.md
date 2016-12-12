
# Project Report 

Project 3 of CS5331-004: Visualization and Visual Analytics - Fall 2016 

<h2>Study of Genes and Its Imapct on Cancer types<h2>

 -Link to Demo: http://myweb.ttu.edu/videshpa/
 
 -Youtube video: https://youtu.be/AViFyIenAz0

 <b> 
This project is mainly based on the Research of Cancer Studies. In this  project, the main criteria is to understand the research work going on and also  need to overlay experimental data (from cancer studies) on top of a protein network. 
      The main source of the data has been acquired form http://www.cbioportal.org/. 
We as a Team have not only considered the above website but also go beyond the expectations and gathered data from different publications pertaining to Research on Cancer and its intensity .

### Data Pre-Processing 
The API(Application Program Interface) is requested from the Javascript code written and obtain the relavant data.The data mainly consists of different Case Studies on a particular Gene . The details of it is as shown below ..</b>
     
![1](https://cloud.githubusercontent.com/assets/22176809/21091973/2e02886c-c00f-11e6-9382-8df74e687150.JPG)



<b>The Requested data from the Cbioportal needs to be proccessed and filtered according to the requirement. In this Project our Main aim or motive is to show the Male and Female ratio based on a Gene. </b>

![2](https://cloud.githubusercontent.com/assets/22176809/21092033/9e6ae482-c00f-11e6-9fa6-68f1d8225a6e.JPG)
      
 <b> The data is in the form of Array of Objects which consits of Male Count and the Female count with respect to each Cancer type for each Gene Clicked by the user .</b>
  
![3](https://cloud.githubusercontent.com/assets/22176809/21092051/bb2c9020-c00f-11e6-831f-a0e108c5cb7d.JPG)
  
 <b> The Requirment is enhanced by sorting down the male and female count . The Legend shown are Male and Female . The user Clicks on the Male Legend to sort the data based on the Male count. When the user clicks on the female count the data is sorted based on the Female count . The motive of this requirement is to mainly understand the the effect of each Gene on a cancer tye based on the Gender . </b>
  ###Rendering the data 
  ![4](https://cloud.githubusercontent.com/assets/22176809/21092049/bb2bc50a-c00f-11e6-93ad-60e8f34ef1df.JPG)
  
  Sorting the Cancers based on its impact on Males
  
  ![male sort](https://cloud.githubusercontent.com/assets/22176809/21092048/bb2ba0de-c00f-11e6-9778-dd230911093a.JPG)
  
  Sorting the Cancers based on its impact on Females
  
  ![female sort](https://cloud.githubusercontent.com/assets/22176809/21092052/bb2cbcf8-c00f-11e6-9f41-00722375bcb2.JPG)
  
  <b>The Requirment is further enhanced by showing the intensity of each Gene on a Particular Cancer type . This mainly helps the user understand the effect of each Gene on a Cancer type . The data obtained for this requirment has been obtained from the publications in the http://www.proteinatlas.org/ . The CSV data obtained is from reliable sources since the data is from the authorized publications .
  The CSV Data shows exactly how the gene is affecting a particular cancer type . The CSV data has been synchronized dynamically with the data obtained by the Cbioportal website to visualize it better. <b>

High Intensity

![high intensity](https://cloud.githubusercontent.com/assets/22176809/21092047/bb2b95e4-c00f-11e6-873e-0c0ecde6a76d.JPG)

Medium Intensity

![medium intennsity](https://cloud.githubusercontent.com/assets/22176809/21092053/bb3a7d84-c00f-11e6-8385-88392215b315.JPG)
  
Low Intensity

![low intensity](https://cloud.githubusercontent.com/assets/22176809/21092050/bb2c4c64-c00f-11e6-85d2-f6b295a23521.JPG)


 <b> The Next Requirement is to show exactly what the Cancer Gene Looks like . The best possible way to do that is to show the user on how the Gene looks liks and its structure . The images have been obtained from the relaible sources and the image is rendered based on the request of the user . Although an user who does not have any knwoledge about the study of cancer may find it hard to understand the structure of the data , but along with the visuzalized data it becomes easier for the user to corelate between the data and the gene and get some basic knowledge of it  .. </b>
  
  Here is the Screen shot which show s a particular Gene along with its effect and the Gender impact of that Gene. 
  
 <b> The Project shows the data in the form of Bar Graph which makes it quite easy for any type of the user to read and understand the data. Results have shown that Bar graph is the best way to visualize the data which makes it quite easy for any lay man to understand it well. </b>
  
## Future Work  
  
  <b>1)The  image retrieved can be animated further using cola.js library.<br/>
  2)The visiualization used even though efficient ,can be further enhanced .<br/>
  3) Use of Three.js Library to visually improve the appearnace and animate it. </b>
  

  
# Weekly Report 

## Week 1 (11/18/2016 - 11/21/2016) 

Meeting 18/11/2016<br>
--Discussed basic idea about the project. Distributed various tasks among the group members. 

###<dl>Arun Kumar Jagerkal </dl>
      1)Study of Web API.(done)
      2)Connecting and Retrieving Information related to different Proteins from the cBioPortal Database.(done and showed sample data)


###<dl>Vinay Arvind Deshpande </dl>
      1)Setting up GitHub Repository.(done)
      2)Research on different proteins  which includes all the information related to cancer studies  .(found protienalias website) 


###<dl>Bhavya Batra </dl>
      1)Research on cBioPortal website of all the proteins (done)
      2)Analyze what information can be rendered efficiently.  (done and discussed ideas with the professor). 

## Week 2 (11/21/2016 - 11/28/2016) 

Meeting 21/11/2016<br>
###<dl>Arun Kumar Jagerkal </dl>
      1)Need to get the statistical information when passed as a query.(done)
      2)Mutation rates based on gender. (done)
      3)Connecting and Retrieving Information related to different Proteins from the cBioPortal Database.(done) 


###<dl>Vinay Arvind Deshpande </dl>
      1)Research on proteinalias website for Web API to get protein data.(done)
      2)Work on the data to get different cancer types based on protiens(done) . 


###<dl>Bhavya Batra </dl>
      1)Research on how to visualize the data. (done)
      2)Fetch protein based images for different types of cancers.(Found the RestAPI) (Working with Arun and Vinay ) 
      
## Week 3 (11/28/2016 - 11/05/2016) 

Meeting 21/11/2016<br>
###<dl>Arun Kumar Jagerkal </dl>
      1)Need to get the statistical information when passed as a query.
      2)Mutation rates based on gender. 
      3)Connecting and Retrieving Information related to different Proteins from the cBioPortal Database.
      4)Implementation of the above requrement.


###<dl>Vinay Arvind Deshpande </dl>
      1)Research on proteinalias website for Web API to get protein data.
      2)Implementation of the above requrement.


###<dl>Bhavya Batra </dl>
      1)Research on how to visualize the data. 
      2)Fetch protein based images for different types of cancers.
      3)Implementation of the above requrement.


  
