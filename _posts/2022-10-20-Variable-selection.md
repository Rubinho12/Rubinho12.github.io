## __Variable selection__  

* ## What is variable selection in statistics or analysis?  

  A huge part of statisticians and analysts work is to build statistical models. Models are often built to represent or follow the data they are working with.
  Two goals of the model building is to make inference or prediction, depending on the task at hand. In order to arrive at the final goal which is either
  inference or prediction using a final appropriate model, variables or features that will be part of that model is a very important step.  
  With that being said, variable selection is, just briefly, the art or I would say the task of selecting relevant explanatory variables that will be supervised 
  by the outcome feature, in case of a parametric model.  
  
 * ## How would you plan to determine variables to use in a regression model?  

    In building a regression model, one has to keep in mind that the simpler the model, the better. We, first have to make sure that the number of obseravtions
    in our data is more than the candidates of available features, in order to avoid the *curse of dimensionality*. If p < n , then we will run a multicollinearity
    test to check wich variables are higly correlated with each other. If , for, instance two variables are higly correlated, then we do not
    necessarily need both of them in our model, just one or the average of the two. In case, there is not a presence a collinearity among the features, we
    will check by hypothesis testing, which variables are significant in explaining or predicting the response variable. Insignificant features are often dropped
    from the model, since they are considered redundant, not adding anything to the dependent variable.  
    
 * ## Is your technique of selecting variables in a regression model, mentioned above, optimal?  

    No, far from it. Those techniques are widely used, but are not the best. Any debutant would apply those techniques blindy without asking the good questions.
    That is excatly what I would have done too, but not now, after some few research on the variable selection topic. Think about it, we can drop an insignificant
    variable from the model, that will turn out to correctly explain the dependant variable. 
    
 * ## So, tell us. What variable selection techniques do you prefer and why, based on your research?  

    There are multiple variables selection methods such as the forward, backward, stepwise, and best subset selection. Other penalizing methods such as the Ridge 
    and LASSO regressions are often also used to make the choice between which features will enter a model. While those methods are used a lot, they are not 
    necessarely the best techniques in choosing variables.  
    Other selection criterias, like AIC, BIC, Cp, Adjusted R-squared, the minimun test error, etc... allow us to select the best subset among various models, and I 
    would prefer them over the stepwise selections, but still , we can do better. 
    My favorite technique of selecting features is the *enhanced variable selection*. In this method, we tend to find the best combination of the original variables 
    to include in the model. This method identifies a subset that consist of the original features and data-mined features.  
    
 * ## Tell us a little bit more about the enhanced variable selection (EVS) method.

    Consider a regression equation that has some independent variables that are not symmetric, or can't predict the response variable with their original shape.
    We will build a model that is not powerful in prediction. The enhanced variable selection transforms and re-expresses the variables in order to increase their
    predictive power. Dividing  two variables or taking the natural log of certain variables is some examples of that transformation.  
    We all know that the normal distribution is very important is statistics. EVs, by transforming the variables may change their shapes into a more symmetric 
    distribution, which will provide accurate estimates for means, variances, correlations; and also facilitate the interpretation of the variables. All these, as 
    we may have noticed, are not considered by the common variable selection method.  
    EVS has the ability to straighten non-linear relationships. In regression a linear relation betwen the dependent and independent variables is one of the important
    assumptions that we look for. Not only between the response and explanatory features, but among the independent variables themselves, linearity is desired, since
    it provides an ease of interpretation. 
    There is more to this method, but I will stop here  and hopefully I have convinced you as why the EVS is my preferred variable selection techniques. Combining this 
    method to the selection criteria method, and the hypothesis one and whatnot mentioned earlier will ensure us of building a 'good' model.  
    
  * ## Some final words?  

      The simpler , the better. Analysts have to keep parsimony in mind when building models. Also, don't naively use just any technique to select your features
     because you have the ability to do so. A lot of variable selection methods have their weaknesses. Do some data mining, understand your variables, do some 
     transformations, stress the variables, stretch them, don't just leave them in their original shape. It is lots of work, but *it is hard to keep things simple*,
     as Sir Richard Branson said.
     
