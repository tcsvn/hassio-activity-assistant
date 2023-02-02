# Activity Assistant
Activities of Daily living (ADLs) such as eating, working, sleeping and Smart Home device readings are recorded by inhabitants. Predicting resident activity from the device event stream enables a variety of
applications. Activity Assistant is a platform that streamlines the data collection process. Multiple devices or subjects are tracked using an additional [Android](https://github.com/tcsvn/activity-assistant-logger) or the Home Assistants companion app. Furthermore, Activity Assistant (will) support the deployment of trained models and running ADL predictions in real-time. A (future) Home Assistant integration offers users a novel activity based abstraction to automate their homes upon.


## Alpha version 
Notice, this is still an alpha release and therefore flagged as experimental. Be prepared to inevitably run into bugs. If you are  stuck check out the FAQ for workarounds or please open an issue on github. 

## Features
For now you can collect data and generate useful statistics and visualizations. Although I once build a proof of concept running real-time prediction in my personal setup with Home Assistant, the prototype does not scale for general models. I am working on providing a generic interface for deploying models, a secure runtime environment as well as a proper Home Assistant component in the future.

## Audience
This Addon, at its current state, is intended for machine learning practitioners or developers providing an friction-less starting point for collecting data. If you are just a person enjoying unfinished software and cool data-visualization, the plots may provide you with insights about daily interactions with your Smart Home.