# Activity-assistant
Activity-assistant is a platform that streamlines the process of collecting Activities of Daily Living. Selected devices from Home Asisstant and persons are tracked and dumped into .csv files. Using an android app or Home Assistant input_select/input_booleans, device readings are labeled with the inhabitants current activities. Furthermore activity-assistant (will) support the deployment of trained models running predictions in real-time. A homeassistant integration (will) offers users a way to automate things based on activity predictions.

## Alpha version 
Notice that this is still an alpha release, meaning you will inevitably run into bugs. If there are problems, please open an issue because otherwise I will not notice. I am still a student, therefore there will be times where a fix takes longer because I am busy learning. 

## Features
For now you can collect data and generate useful statistics and visualizations. Although I build a proof of concept showing real-time prediction within Home Assistant, the prototype doesn't scale for general models. I am working on providing a generic interface for deploying models, a secure runtime environment as well as a proper Home Assistant component in the future.

## Audience
This Addon, at its current state, is intended for machine learning practitioners or developers to get started in this field. If this does not apply to you, the visualization may provide insights in your interaction with your smart home.
