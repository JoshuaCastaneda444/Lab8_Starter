# Lab8-Starter

Name: Joshua Castaneda
GitHub Page: 

# Graceful Degradation

Service workers seem to be a direct application of the ideas behind graceful degradation. For example, if we start with a working app that uses the network, then with service workers, we can enable the page to not be dependent in the high level technologies like the network which might not be reliable on older devices. We accomplish by having the service worker cache resources when loaded from the network in order to be able to use them when the network fails. As a result, the webpage will be able to work on devices with more unreliable networks and so we increase reliability since even for faster and more reliable devices, we reduce the dependence of our site on something we can't control, the user's network, and degrade our dependence on "max technology" gracefully. 

# Progressive Web App

![Progressive Web App Screenshot](pwa.png)