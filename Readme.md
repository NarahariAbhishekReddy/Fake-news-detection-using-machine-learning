<!Doctype html>
<html>
<body>

<h1> Python/Deep Learning - Fraudulent News Detection </h1>


<hr size="1" noshade>


<h2> Overview </h2>

<p> In recent years, we came to know that fake news or articles is a big threat to the society as they make people believe what is not true and making them mislead with the false information which might affect not only economically but also individually. For instance, as we researched online, one of the economically well-developed countries have lost billions due to outspread of false information. This is just an instance that result in greater economic impact but there are many more incidents happened because of fake news circulation. Therefore, we find this as a potential problem to address and provide a solution in understanding what we learn in daily life is real or fake.  </p>

<p> Our major objective is to discriminate the fake news among a set of news articles and determine the articles that contain misleading information. In order to achieve our goal, we would make use of machine learning algorithms that provide an approach to the best solution possible.  <p>


<h3> Datasets </h3>

<p> All the datasets we used in this project is from public domain, Kaggle (www.kaggle.com) </p>

<p> Dataset 1 </p>
 
<p> Dataset 2 </p>
 

<p> Dataset 3 </p>
 

<p> Dataset 4 </p>

 

<p> The final dataset contains only 2 columns and in the label column, 1 represent true and 0 represent false/fake</p>
 

<hr size="1" noshade>

<h4> Data Preprocessing </h4>

<p> - Remove all unwanted columns. </p>
<p> - Remove missing value records. </p>
<p> - Remove extra information - could be some special characters. </p>
<p> - Removing the numbers, urls from the text. </p>

<h5> Machine Learning models, Building and Training </h5>

<h3> Machine Learning model we think are best suitable for the problem chosen </h3>

<p> Naive Bayes(Multinomial and Bernoulli) </p>
<p> Logistic Regression Classifier </p>
<p> Random Forest </p>
<p> Decision Tree </p>

<p> we have used the aforementioned classifiers to perform the prediction and classify the result when fake news detection. Using pipeline, we assemble several operations that cross-validate together with different parameters. </p>

<p> Upon fitting the model, we compared the accuracy score among all the classifiers and also the confusion matrix </p>

<p> We observe Logistic Regression has returned with highest accuracy score - 94.71%. Therefore, we saved the model with model.plk </p>

<p> This is the webpage which accepts the content/news/text from the user and upon clicking on submit button, our model performs the classification on the provided text into either True or Fake.
 </p>

 

<p> As seen in the above screenshot, we have provided some text and our model predicted it as True news. </p>
 

<p> As seen in the above screenshot, we have provided some text and our model predicted it as Fake news </p>






</body>
</html>
