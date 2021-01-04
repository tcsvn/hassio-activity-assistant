# Minimal Documentation
I am working on a real documentation which will be linked later. So stay tuned.


## Guide
- Configure activities and devices
- Connect the android app to the platform by navigating to a person and scanning the qrcode
- Start an experiment and document your activites with the app
- Finish the experiment and export your data 
- Use [pyadlml](https://github.com/tcsvn/pyadlml/) to load your data 
- Train your models, evaluate and repeat

## FAQ
- I can't connect my smartphone
    - Is the IP and PORT set correctly? Check the addon configuration and the config in activity-assistant.
- Can I connect to the server from the internet?
    - Yes, in principle with Port forwarding enbaled this is possible. However this is not the recommended way. It is totally fine to specify a local ip address and synchronize the activities now and then when you are within your local net

## Known Issues
- Changing the port from 8000 to sth. other does not work!