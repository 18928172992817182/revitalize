# Revitalize

An app that integrates with the Google fit API and exposes a web interface to inspect the recorded data.

Hobby project used as a training exercise to explore new technologies.

## Background

When my phone broke there was no way for me to interact with Google Fit. I found that annoying.

The reason I am going for Flutter is because despite Typescript adding convenience to javascript, it is still just javascript. Flutter uses Dart. Why should we explore Dart when we already have javascript? I simply got interested after having seen Lars Bak do a talk about the history of web browser performance and development for the future which you can find here https://www.youtube.com/watch?v=m4EB_k57g-I.

## Getting it to run

Follow the standard setup instruction from Flutter: https://flutter.dev/docs/get-started/install

I am using IntelliJ IDEA Ultimate but use any of the supported editors: https://flutter.dev/docs/get-started/editor

## Data 

Google Fit has a quite nice extensive API. It covers more than the actual Google fit app exposes. Which is odd but whatever. What is even cooler is that the Google Fit platform supports custom data points. 

So, lets just say I want to record how long I can hold my breath as part of the revitalization process. Then I can just add those data points and see how I improve my ability to hold my breath for freediving.

All our data points will live under the app's package name. However, do note that this data is only available for this app.

## Access

All access uses an OAuth 2.0 client ID generated from your Google account.

