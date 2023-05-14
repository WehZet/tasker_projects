Working Time Tracker is a simple Tasker scene for tracking the working time with the possibility to additionally track pause times. After recording it sends the data to Google Sheets.

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
