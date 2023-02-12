# Minimal Documentation
I am working on a real documentation which will be linked later. So stay tuned.


## Guide
- Follow the onboarding and configure stuff
- Check if the IP address (CAVE not domain name) is set up correctly in the config!!!
- Connect the android app to the platform by navigating to /person/x and scanning the qrcode
- Start an experiment and document your activites with the app
- Finish the experiment and export your data 
- Use [pyadlml](https://github.com/tcsvn/pyadlml/) to load your data 
- Train your models, evaluate and repeat

## FAQ
- I can't connect my smartphone
    - Is the IP and PORT set correctly? Check the addon configuration and the config in Activity Assistant.
- Can I connect to the AA from the internet?
    - Yes, in principle with Port forwarding enabled this is possible. However, this it NOT recommended. I did not develop the addon with security concerns in mind.
- I want to enter the dangerzone
    - Activity Assistant exposes a browseable REST API udner domain:8000/api most of 
      the important values can be set directly
## Known Issues
- Changing the port from 8000 to sth. other does not work!
- Everything is slow or 504/502 timeout errors
    - The dashboard requires a lot of ram. Machines that have not enough ram may use 
      iswap file. Home Assistant sometimes allocates a to smal swap file, thus the application crashes. To increase your swap file follow: https://community.home-assistant.io/t/how-to-increase-the-swap-file-size-on-home-assistant-os/272226/46 
    - Buy a better machine ;)
- Plots do not show anything or crash after starting an experiment
    - Record at least a few activites and device events and then the correct content should be displayed
    - Waiting or reloading is your friend. Sometimes the imported libraries do crash unexpectedly.
- Logger can not connect to Activity Assistant or other issues
    - You have to use the IP address and not a domain name such as homeassistant.local since
      android phones do not use local dnss 
- Dashboard error message with dpd_component could not resolve demo or dependencies
    - Just reload again and again