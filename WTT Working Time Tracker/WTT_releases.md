[Taskernet-Link](https://taskernet.com/shares/?user=AS35m8ks8HbsdHFuQd8IQwuQOnRpbi3s1kNACT0seG%2Ftrt9xPGrDRmNw71%2BgbKj6vg1mISfy&id=Project%3AWorking+Time+Tracker)

Working Time Tracker is a simple Tasker scene for tracking the working time with the possibility to additionally track pause times. After recording it sends the data to Google Sheets.

## v0.3.3
02.07.2023<br/>
1) bugfix: Error if using EndAt function. (element Visibility was not able to change because the Scene is not opened at this point anymore)

## v0.3.2
01.07.2023<br/>
1) fixed a problem where begin an pause-begin times were set to a new time because of restarting phone etc. --> Added a stop action at the beginning of the tasks which are setting the begin and pause-begin times
2) all variables will now be resetted after using the "End At" function

## v0.3.1
15.05.2023<br/>
1) fixed failure where "now" will be set as end time even when choosing end time by user
2) setting Pause to 0 before uploading and notification for correct showing
3) fixed problem where pause times where rounded up

## v0.3.0
14.05.2023<br/>
1) Added button to change the start time
2) Added button to choose the end time manuall
3) Added button to change the pause time
4) Added button to add comment
5) Added a notification after ending the working day with the stats

## v0.2.1
12.05.2023<br/>
1) corrected flow of reset variable when resetting
2) if pause is active, it is not anymore possible to end working via NFC resetting

## v0.2
30.04.2023<br/>
1) first running and useable version
2) Scene:
- Start/Stop working Time
- Start/Stop Pause
- Reset and descard all current Tracking
3) Uploads all data to a Google Sheet after tracking

## v0.1
29.04.2023<br/>
1) first draft<br/>
Stores times (begin, pause_begin, pause_end, end) one after the other into Task variables and then pushes them into a Google sheet
