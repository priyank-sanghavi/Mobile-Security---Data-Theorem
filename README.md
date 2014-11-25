Mobile-Security---Data-Theorem
==============================

Fall 2014 - Risk Analysis of iOS 8 sponsored by Data Theorem


Hello!


The Blitzkrieg code has an implementation of CustomKeyboard for iOS. It sends data on local server everytime the 
return key is pressed.
On the simulator, you can try it in the Photos app or any other app that takes an input.

For the data to be sent on the local server, you need to run the api.rb file in the command line.
Go to the folder that contains the file in terminal.
Type ./api.rb and it should start the local server. After this it will record all the keystrokes you make.
Can refer to this link. I had used this for a simple local server on Mac.
http://jamesonquave.com/blog/making-a-post-request-in-swift/#jumpSwift


The FitStore code is a sample code of using the HealthKit for iOS 8. Moreover, it copies the all the HealthKit data 
that can be accessed by the App to the PasteBoard. You can check it by running the app. 
Then open Notes (or any similar app) and paste there. You'll be able to see the data.


Thanks.
