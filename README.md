# Apex Unified Logging #

<a href="https://githubsfdeploy.herokuapp.com?owner=rsoesemann&repo=apex-unified-logging">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/src/main/webapp/resources/img/deploy.png">
</a>

Logging framework based on Salesfore Platform Events to overcome the limitations of `System.debug` logging.

## Features: ##
 - Provides unified view of logs over transaction boundaries (a.k.a. execution contexts)
 - Groups Logs of the same Batch
 - UI only shows the logs produced by current user
 - Autodetection of Code Location 
 - Nice UI using a Lightning Utility Bar 
 - Activated using user-level custom settings
 
## Screenshots: ##

<img width="861" alt="lightning_experience___salesforce" src="https://user-images.githubusercontent.com/8180281/51323033-616d0880-1a67-11e9-887c-4c51f0b0cd69.png">

<img width="1166" alt="developer_console" src="https://user-images.githubusercontent.com/8180281/51323046-69c54380-1a67-11e9-9999-29d4697d4b82.png">

<img width="649" alt="custom_settings___salesforce" src="https://user-images.githubusercontent.com/8180281/51323040-6762e980-1a67-11e9-886a-159905a035db.png">

## Kudos to: ##

I was standing on the shoulders of those giants when building this

- [Advanced Logging with Platform Events](https://www.youtube.com/watch?v=yYeurYnasVc) by @afawcett
- [Ein Versuch über einen Protokoll-Service](https://shoreforce.herokuapp.com/ein-versuch-uber-einen-protokoll-service/) by @szandor72
- [Build an Instant Notification App](https://trailhead.salesforce.com/en/content/learn/projects/workshop-platform-events) 
