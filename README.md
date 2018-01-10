# puppy-pic-sms
Send a link to a random dog picture to a phone number daily, via AWS Lambda and SNS.

##Parameters

PhoneNumber is the phone number you'd like to receive the picture. Specify in E.164 format (e.g. +12223334444).
Hour is the hour (in UTC time) at which you'd like to send the daily message. Specify as an integer 0-23.