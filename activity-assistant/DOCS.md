# Minimal Documentation
I am working on a real documentation which will be linked later. So stay tuned.


## Guide
- Configure activities and devices
- Check if the IP addresse (not domain name) was set up correctly in the config!!!
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
- Everything is slow or 504/502 timeout errors
    - The dashboard requires a lot of ram. Machines that have not enough ram may use the 
      swap file. If the swap file is to small, the application crashes. To increase your 
      swap file follow: https://community.home-assistant.io/t/how-to-increase-the-swap-file-size-on-home-assistant-os/272226/46 
    - Buy a better machine ;)
- Plots do not show anything or crash after starting an experiment
    - Record at least a few activites and device events and then the correct content should be displayed
- Logger can not connect to Activity Assistant or other issues
    - You have to use the IP address and not a domain name such as homeassistant.local since
      android phones do not use local dnss 

- Dashboard error message with dpd_component could not resolve demo or dependencies
    - Just reload again and again