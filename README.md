# Watch4-complicatedMedium
WearOS version of m fitbit complicatedMeduim watchface; a bespoke wearOS watchface that displays time, day, date, step count, hr and estimated distance traveled.

A few things to note:
Simple was designed for and with Samsung Galaxy watch4 on wearOS 3.2. 
That doesn't stop you from trying it out on other wearables running API level28 and higher but please be advised. 

- Navigation/Info  
  - tap on the minute to go to your alarms  
  - tap on the day/date to go to your calendar   
  - the arc (circle) you see is essentially a countdown/up timer for the day. it updates every minute for a compromise between accuracy and battery saving.  
  - AOD is available!

- Limitations   
  - distance is entirely estimated and is based off a fixed average 30" stride length. It does not account for faster gait/pace nor running. This is intentional and as a result of the limitations of the software and platform used to make this. It is also locked to miles for now. However, I am looking into making a companion app that lets you input your own gait and preferred unit of measurement. Stay tuned.    
  - HR updates every 10 mins (when still) regardless of watch defined settings. My apologies.   
  - in order to accommodate a comma at the appropriate places for step counting, a known byproduct is a leading zero and a comma below 999 steps. Again, this is due to a limitation of the platform and I'll be keeping an eye out for latest releases to rectify this. Step goal is locked to 15,000 steps.  