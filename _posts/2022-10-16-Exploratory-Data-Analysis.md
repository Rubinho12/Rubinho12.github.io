## Exploratory Data Analysis  

* ## What is Exploratory Data Analysis?  

     Exploratory Data Analysis, often abbreviated as EDA, is an approach used by data analysts and data scientists to analyze and 
     investigate data sets in order to  summarize their main characteristics , often employing data vizualization methods. EDA has been 
     promoted by an American mathematician named **John Tukey** since 1970.  
     
 * ## What strategy is used in performing EDA?  
 
      First, before performing an EDA, a good analyst should start by exploring the data and try to understand the data at a high level.
      After exploring the data, he/she can start with the EDA. Note, that there are multiple important steps in performing an EDA, however, 
      we will only talk about the five most important ones today; which are :  

      * Check for missing values in the data  
        
      * Provide basic descriptions of the sample and features of the data  
        
      * Identify the shape of the data  
      
      * Identify significant correlations  
      
      * Spot outliers in the dataset.  
      
 * ## What is the overall goal when doing an Exploratory Data Analysis?  
 
      The main goal of an EDA is to help look at the data before making any assumptions. It can help identify obvious errors, as well as 
      better understand patterns within the data , detect outliers or anomalous events, and find interesting relations among the variables.
      EDA is essential for seeing what the data can tell us beyond the formal modeling. It helps us maximize insight into the data set, uncover
      underlying structure, extract important variables, test underlying assumptions, develop parsimonious models , and determine optimal factor 
      settings.  
      
  * ## What methods do you think are important? 
  
       Graphical methods remain ones of the best methods used in EDA. It is often done by plotting the raw data such as data traces, histograms, 
       probability plots (PDFs for discrete features and PMFs for continous features), lag plots, etc.. Also, some simple statistics plots like box plots,
       mean and standard deviation plots are useful in seeing patterns in the data.  
       Furthermore, some techniques like PCA, K-means clustering, Multidimensional scaling , can be used to explore the data.  
       
   * ## What things do you try to look for?  

        That is a great question. We are looking for patterns, anomalies, and understand what the data might be hiding. For example, plotting
        the boxplot is a great way to identify outliers in the data. The probability plots, for instance, help us understand the shape of the features.
        They tell us about skewness, whether the feature is heterogenous, etc... If a feature is heavily skewed, then the data scientist knows not to 
        use the mean as a measure of central tendency.  
        K-means clustering helps us group similar data points into clusters. PCA is a dimension reduction technique which is useful in reducing the number
        of features in our data.  
        There is much more to it , but yes, this is a short overview of what we can do with EDA.  
        
   * ## Do you have any advice for a new data analyst or scientist who might think that EDA is not useful but rather a waste of time?
   
        Well, I don't think anyone who is serious about making data science or data analysis as his/her career wil think of EDA as a waste of 
        time. EDA is usually the first step of dealing with data. Even if a raw data is given to a machine learning engineer, the first thing
        he/she will do is to get some insight into the data, before building any model. So to any new analyst, do not skip EDA. It helps us avoid 
        lots of erronous assumptions , results, and decisions; helps us determine how to best manipulate data sources to get the desired answers. 
        Stakeholders, thanks to EDA, can confirm if they are asking the right questions.
