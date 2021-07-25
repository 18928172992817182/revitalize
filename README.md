# Revitalize

An app that integrates with the Google fit API and exposes a web interface to inspect the recorded data.

Hobby project used as a training exercise to explore new technologies.

## Getting it to run

We will be using flutter: https://flutter.dev/docs/get-started/install

The reason I am going for flutter is because despite Typescript adding convenience to javascript, it is still just javascript. Flutter uses Dart. Why should we explore Dart when we already have javascript? I simply got interested after having seen Lars Bak do a talk about the history of web browser performance and development for the future which you can find here https://www.youtube.com/watch?v=m4EB_k57g-I.

## Data 

Google Fit has a quite nice extensive API. It covers more than the actual Google fit app exposes. Which is odd but whatever. What is even cooler is that the Google Fit platform supports custom data points. 

So, lets just say I want to record how long I can hold my breath as part of the revitalization process. Then I can just add those data points and see how I improve my ability to hold my breath for freediving.

All our data points will live under the app's package name. However, do note that this data is only available for this app.

## Access

All access uses an OAuth 2.0 client ID generated from your Google account.

