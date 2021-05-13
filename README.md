# CoVacK
A software to reveal the truth of Vaccine availability in your location by OTP

CoVacK  alias COWIN + Hack

Its a commandline tool to help ManKind to know the truth

In this CORONA Era ,the chaos of Vaccine Notification and its actual availability is a **?**

I have made a simple attempt to let you know about the fact whether Vaccine is available anytime in a given location or not.

  Problem is that Common people are in Suspicion whether Vaccines are really available and if yes then when.

Concept is simple that you will receive an OTP to mobile numbers you define about the PIN codes you define.

Just open the "CoVacK.txt file and change according to your wish except the formatting"

Mobile Number:=XXXXXXXXXX  // Here you can put as many mobile numbers to whom you want to notify about vaccine availability at given PIN codes. Use semicolon to separate mobile numbers
Ex.
   Mobile Number:=9966332255;8855223366;6699335522 
   
PIN Code:=XXXXXXXXX  // Here you can put as many PIN codes at which vaccine availability is desired. Use semicolon to separate PIN Codes
Ex.
   PIN Code:=889955;445566;112233
   
Age Limit:=18  // Just put the age either 18 or 45 about which you needs Notification, use 0 if you want Notification for both age group.
Consecutive OTP:=5  // If some availability is there for some time ,then you will receive OTP five times every 180 seconds.
Seat Limit for OTP:=12  //This is the lower limit of available vaccines above which you want Notofication.
Refresh Interval:=2   // This is the update/refresh interval i.e how often this program enquire server(https://www.cowin.gov.in) for data .
