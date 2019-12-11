## Waste Classifier

According to the World Bank, our global waste production from September 2018, is predicted to rise by 70 percent by 2050 unless we take urgent action. We human beings currently produce two billion tonnes of waste per year between 7.6 billion people. Population increase may be part of the problem, but it’s levels of consumption within developed countries, and their gross mismanagement of waste, that let to the environmental catastrophe.

What’s worse, until now, the most popular approach of managing the waste is still incineration. The bad part of this “efficient method” is that if the garbage is not well classified, it produces large amount of toxic gases around the incineration area, which potentially cause death to infants and other diseases to residents.

So, in order to protect the health of those who live near the garbage station, and to protect the environment, we came up with our waste classification app that can help us to restrict the emission of toxic gases by improving our garbage classification process.

### Introduction

Our app is called Waste Classifier, which is consist of two main parts with two human-AI interaction aspects, the Explainable AI and the AI feedback system. 

The first function of our app, also the main ability of our app is recognizing the object in a real-time frame, to see if the object is recyclable or organic. In this function, we introduced the Explainable AI concept. Users are allowed to look into each layer of the decision-making process, each of which contains a short description of why our model predict the result in certain manner. This idea helps the users to understand and to learn new knowledge of how to classify the disposal.

Another capability of our app is that it takes back the incorrect data, that the users report when they find out that the prediction of our model is clearly wrong. This feedback system allows us producers to look into where we did wrong, to consistently renew our database online, and to improve our AI model in order to provide more accurate predictions.

# How to
For you to use our project, you need to download all the files we have, and put them in the same directory. When you try to build our project in the Xcode, you might encounter a problem called "No such module as Firebase", or something similar. Then what you need to do, is to delete all the pod related file and the .xcworkspace file. Then you need to use terminal to install the pod by yourself. Remember not to delete the Podfile.

# Results
The final results are pretty satisfying. We are able to detect some of the daily disposals and to successfully classify them as recyclable or organic. However, the error could be large when the item we are detecting is not in our database. Since we are only using pre-tained model we found online, there should be more to be done on collecting more data.

# Future Work
For the future work, it definitly needs to use more models that show the properties of the disposal. For example, the brand of the disposal, and also the condition of the disposal, etc.

# You could find a demo video in the link below
http://
