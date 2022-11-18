# Activity Assistant
Activities of Daily living (ADLs) such as eating, working, sleeping and Smart Home device readings are recorded by its inhabitants. The projects aim is to predict inhabitants activities from device recordings. Activity Assistant is a platform that streamlines the process of data collection. Multiple devices and subjects may be tracked using an additional Android or the Home Assistants companion app. Furthermore, Activity Assistant (will) support the deployment of trained models and running predictions in real-time. A (future) Home Assistant integration offers user a novel activity-based abstraction to automate their homes upon.


## Alpha version 
Notice that this is still an alpha release, meaning you will inevitably run into bugs. If there are problems, please open an issue because otherwise I will not notice. I am still a student, therefore there will be times where a fix takes longer because I am busy learning. 

## Features
For now you can collect data and generate useful statistics and visualizations. Although I build a proof of concept showing real-time prediction within Home Assistant, the prototype doesn't scale for general models. I am working on providing a generic interface for deploying models, a secure runtime environment as well as a proper Home Assistant component in the future.

## Audience
This Addon, at its current state, is intended for machine learning practitioners or developers providing an friction-less starting point for collecting data. If you are just a person enjoying unfinished software and cool data-visualization, the plots may provide you with insights in your daily interaction with your Smart Home.