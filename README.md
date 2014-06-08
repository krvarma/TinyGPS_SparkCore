**TinyGPS** - a small GPS library for Arduino providing basic NMEA parsing Based on work by and "distance_to" and "course_to" courtesy of Maarten Lamers. Suggestion to add satellites(), course_to(), and cardinal(), by Matt Monson. Precision improvements suggested by Wayne Holder.
Copyright (C) 2008-2013 Mikal Hart
All rights reserved.

--- *Adapted by Krishnaraj Varma for Spark Code* ---

A MediaTek MT3329 GPS receiver is used in this example application. The sample simply publishes the GPS location every 15 minutes. The HMTL page uses Google Map API to display Spark Core location on a Map. You should replace the tag deviceid and accesstoken with actual values.

**Wiring**

 1. GPS Vcc to 3.3V
 2. GPS GND to GND 
 3. GPS Tx to Rx 
 4. GPS Rx to Tx
 
**Screenshot**

![enter image description here][1]

![enter image description here][2]


  [1]: https://raw.githubusercontent.com/krvarma/TinyGPS_SparkCore/master/IMG_0087.JPG
  [2]: https://raw.githubusercontent.com/krvarma/TinyGPS_SparkCore/master/IMG_0088.JPG