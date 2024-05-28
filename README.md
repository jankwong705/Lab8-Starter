# Lab8-Starter

## Jan Kwong, Ethan Shih, Michael Pena

## How are graceful degradation and service workers related? 
Graceful degradation focuses on implementing full functionality of an app first, then developing fallbacks to address lower levels. Service workers, listening in the background, store the data from requests to the internet. They are related to graceful degradation because it is a method to ensure the usability of the app despite the lack of internet. We first implement all the functions in JavaScript, then use service workers to address the situation where internet is not available. This is a form of graceful degradation.

## Link to GitHub Pages:
https://jankwong705.github.io/Lab8-Starter/