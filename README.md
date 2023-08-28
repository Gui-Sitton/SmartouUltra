# SmartouUltra



Mobile operator Megaline is dissatisfied with the fact that many of its customers are using old plans. They want to develop a model that can analyze customer behavior and recommend one of Megaline's newer plans: Smart or Ultra.
You have access to behavioral data from subscribers who have already switched to the new plans. For this classification task, you need to develop a model that will choose the right plan. As you have already carried out the data pre-processing stage, you can go straight to creating the model.
Develop a model with the highest possible accuracy. In this project, the limit for accuracy is 0.75. Check the accuracy using the test data set.

**Data description**

Each observation in the dataset contains monthly behavioral information about a user. The information given is as follows:
* сalls - number of calls
* minutes - total call duration in minutes
* messages - number of text messages
* mb_used - Internet traffic used in MB
* is_ultra - plan for the current month (Ultra - 1, Smart - 0)

**Conclusion**

I believe that the model that stood out the most was RandomForestClassifier because it confirmed expectations, with the highest accuracy of almost 80%, its speed was in fact the lowest but I believe that this is not an impediment because its high accuracy makes it worthwhile. I also chose this model because of the method it works with, and I think it's ideal for this situation.
