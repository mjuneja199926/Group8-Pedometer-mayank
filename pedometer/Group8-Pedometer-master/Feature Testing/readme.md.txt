Instructions for testing added features.

Average Steps Request
To test the new features for this request three functions of the app should be checked. This can be done by following the given below: -
1.	Download the .CSV file from our repository on GitHub and place it in your Android’s root folder.
2.	Clear the App Cache and Storage under app settings. 
3.	Import the data into the app using the Import/Restore Option under the setting tab.
4.	Compare the averages given by the app with the Expected Averages file present in our Update folder, if they are equal that would mean our app is working properly otherwise there is a problem.

The number displayed for each option should be as follows: 

All Time Excluding Today: 	5181
Last 7 Days Excluding Today:	5350
All Time Inlcuding Today: 	(41453 + steps taken today) / 9



Reset Button Request
To implement the request, user can perform a test case in which they take some steps and then press the reset button. If this erases the data for that trip that would imply the request works properly.
