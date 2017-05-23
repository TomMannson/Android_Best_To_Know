# Android_Best_To_Know

Adb Shell Hints

Dump data from system service
adb shell dumpsys {system-name} > {output-file}

DumP OF SERVICE {system-name}
DUMP OF SERVICE alarm:
DUMP OF SERVICE clipboard:
DUMP OF SERVICE permission:
DUMP OF SERVICE search:
DUMP OF SERVICE sensor:
DUMP OF SERVICE simphonebook:
DUMP OF SERVICE statusbar:
DUMP OF SERVICE telephony.registry:
DUMP OF SERVICE throttle:
DUMP OF SERVICE usagestats:
DUMP OF SERVICE vibrator:
DUMP OF SERVICE window:
more....
http://stackoverflow.com/questions/11201659/whats-the-android-adb-shell-dumpsys-tool-and-what-are-its-benefits

Android Framework Problems

Drawable - android 5+
Paths with hardware accelerate
Serialization problem
Fragment BackStack



String plurals

Problem:
<plurals name="plural_remaining">
        <item quantity="zero">Today</item>
        <item quantity="one">Tommorow</item>
        <item quantity="other">%d Days Remaining</item>
  </plurals>
  
  Zero not workng instade uses other
  
  Solution:
  Code is 
  
  
  
