# AdSmart_AB_Test

## **PROBLEM**

* Given that the  Smart Ad company is based on the principle of voluntary participation which is proven to increase brand engagement ,
  an additional service called Brand Impact Optimiser (BIO), a lightweight questionnaire, is served with every campaign to determine 
  the impact of the creative, the ad they design, on various upper funnel metrics.
* That said the  tasks is to design a reliable hypothesis testing  algorithm for the BIO service and to determine whether a recent advertising
  campaign resulted in a significant    lift in brand awareness.
* The users that were presented with the questionnaire above were chosen according to the following rule:
     Control: users who have been shown a dummy ad
     Exposed:  users who have been shown a creative, an online interactive ad, with the SmartAd brand.
     
     
## **METHOD**
 ### **A/B TESTING**
   * From the problem definition,we determine whether there was a significant lift in brand awareness difference between the two groups.
      We use the below approaches:
       *Metric Choice:
           Invariante metrics-Used this to ensure that the esperiemnt (the way we presented a change to a part of the population )is not inherently 
             wrong. eg number of users in both groups
       *Evaluation metrics-metrics we expect to change and are relevant to the goals we aim to achieve eg (brand awareness)
**Hypothesis testing for A/B testing**
  * We use hypothesis testing to test the two hypotheses:   
       *Null Hypothesis :There is no difference in brand awareness between the exposed and control  groups in the current case.*
       *Alternative Hypothesis:There is a difference in brand awareness between the exposed and       control groups in the current case.*
       
### **MACHINE LEARNING**
 * We will carry out 3 types of classification analysis to predict whether a user responds yes to brand awareness,namely:
        Logistic Regression
        Decison Trees 
        XGboost
     We will then compare the different classification models to assess the best performing one(s).
     
## RESULTS
   * We used A/B testing to determine that there was a significant difference in brand awareness between the groups.
   * Those who were exposed to a creative ad had more probability of being able to remember the brand
   * Consequently,using Machine learning we determined the best features which contribute to users having more awareness on a certain brand.
   
   
## REFERENCES
[Statistical Significance](Statistical Significance in A/B Testing – a Complete Guide)
[A/B Test with Python](A/B test with Python) 
[Refresher on A/B testing](A Refresher on A/B Testing)
[A/B Testing Statistics](A/B Testing Statistics: An Easy-to-Understand Guide)
[Sequential A?B workflow and advantages over Classic Experiment](Sequential A/B Testing: Workflow and Advantages over Classic Experiments)
