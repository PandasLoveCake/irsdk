# irsdk
Copy of the IRacing SDK from the members website (2024.06.01)


From the Iracing website (https://forums.iracing.com/discussion/62/iracing-sdk/p1)

The iRacing SDK or IRSDK is an api that allows you to query information about your car and the state of the current race straight from the iRacing sim client. This uses a memory mapped file to push out data to as many clients as want to connect. It is only in action when you are in a race session (or watching a replay) and can only tell you info about the current session.

The original iRacing SDK forum is still available, there is lots of good info there on how this grew over time. And you can still access the original iRacing API's and development discussion forum for information on user developed api's.

This api is based on C/C++ but all source code is provided and it can easily be ported to any language that can access a memory mapped file in windows.

For accessing data from the website see this forum post:

https://forums.iracing.com/discussion/15068/general-availability-of-data-api

History:
2021/05/21 - Maintenance update, added message support for control over video recording and screenshots.
2024/03/04 - New rain defines, new .ibt irsdkDiskWriter class.
2024/03/06 - New rain defines
2024/03/18 - New tire compound change enum
