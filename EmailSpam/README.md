Here is a link to my Web App :
https://email spam by gaurav.herokuapp.com/






We have to create a Machine Learning Model that can Classify the Spam and Ham(Not Spam) Emails. 

Model Building
This consists of three major parts:
• Vectorizing the Data: We separate each of the
transformed text into a list of words. This can be
done with Count Vectorizer or TFIDF Vectorizer . In
this Project I have used the TFIDF vectorizer as it
gave me better results.
• Splitting the Data Set: Now as we Split the Data set
into Test Set and Train Set.
• Training the Data Set: Now we have to choose a
suitable Algorithm to train our Data Set. Since this is
a Classification problem we can use Logistic
Regression to Implement the Model. But I checked
with other Models as well to get the best results and
recorded their Accuracy and Precision.


Creating Web App for the Model
Now as we Created the model I made a Web App for
the same using Streamlit Library in Python.
Firstly, we have to pickle our model. Pickling the
model helps to serialize the model to create a . pkl file
which can be used to implement the model in other
place. Here I used Scikit Library to pickle my model
and used the . pkl file to create a web interface using
streamlit and to finish things up Deployed the web
app using Heroku .

