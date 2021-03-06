

# Get Started
**Hardware**

Biometric Scanner: [Digital Persona U.are.U 4500](https://www.lazada.com.ph/products/digital-persona-uareu-4500-fingerprint-scanner-uru4500-with-sdk-i121429233-s126283958.html?ef_id=Cj0KCQiA0ZHwBRCRARIsAK0Tr-q4VYad3021bHyyeUZ4WbWyHYcmt3K1P4kgf07ZtK1f0mBv-SyXZ4caAvxFEALw_wcB:G:s&s_kwcid=AL!3151!3!244365264139!!!u!293946777986!&exlaz=d_1:mm_150050845_51350205_2010350205::12:1032129542!52512091404!!!pla-293946777986!c!293946777986!126283958!135210741!244365264139)

**Installation**

Download the  [Files](https://drive.google.com/open?id=1l8VP_tSVcN8cU29vXhbSwLitMxlqHAzD) and install the following on your computer.

 - `Digital-Persona-SDK-master/SDK/Setup.exe`  - so you can use your biometric hardware to your desktop application when trying to register a fingerprint and logging-in through the event.
 - `mysql-connector-net-8.0.13.msi` I used this to connect my Desktop Application to mysql database.
 - `ams.sql` - create a mysql database name it '*ams*' then import this.



# Usage

**Create a student(Website)**
![Navi](https://github.com/kuyapete/Biometric-Ticketing-System/blob/master/AMS%20Images/Create%20Student.png)
**Create a event(Website)**
![Create Event](https://github.com/kuyapete/Biometric-Ticketing-System/blob/master/AMS%20Images/Create%20Event.png)
**Register Fingerprint to a Student(DesktopAdmin)**

Click on *Fingerprint Enrollment*

![enter image description here](https://github.com/kuyapete/Biometric-Ticketing-System/blob/master/AMS%20Images/Register%20Fingerprint.png)

Then Scan your Finger.

![enter image description here](https://github.com/kuyapete/Biometric-Ticketing-System/blob/master/AMS%20Images/Scan%20Fingerprint%20Register.png)

Input Student ID of the student you want to enroll of the fingerprint then Click on *Save Fingerprint Template*

**Run DesktopClient**

You must open this depending on what time and date of the event you have created. It will not logged if the time you open this it out of bound on the time you input on the event. Then you can start scanning fingerprint so they can enter on your event.

![enter image description here](https://github.com/kuyapete/Biometric-Ticketing-System/blob/master/AMS%20Images/Scan%20Fingerprint%20on%20event.png)


# Additional

 - Edit students Information
 - Edit Event Information
 - Print Attendance Report of Students who attended the Event
 - View a events attended on a specific Students
 - Realtime Logging on a Event
