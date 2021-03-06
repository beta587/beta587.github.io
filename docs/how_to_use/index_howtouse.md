---
layout: page
title: How to Use
permalink: /tutorial/
nav_order: 3
has_children: false

---
- [How to use Search Exam software](#how-to-use-search-exam-software)
    - [Opening the software for the very first time](#opening-the-software-for-the-very-first-time)
    - [Takes time to load initially](#takes-time-to-load-initially)
  - [Input questions](#input-questions)
    - [Taking care of format](#taking-care-of-format)
    - [Taking care of limitations](#taking-care-of-limitations)
    - [Entering GPS Coordinates for location of exam center](#entering-gps-coordinates-for-location-of-exam-center)
  - [Finally - The dates screen](#finally---the-dates-screen)
    - [Notes](#notes)
    - [Subscription](#subscription)

# How to use Search Exam software

Please download the software as explained in the [download](../download) section.
### Opening the software for the very first time
On Windows, when you open the program for the very first time, you may see a warning blue screen. If you see this screen, click on <span style="color:orange">More Info</span> and then click on <span style="color:orange">Run Anyway</span>.
<!-- <span style="color:orange">More Info</span>  and then click on <span style="color:orange">Run Anyway</span>. -->

<!-- ![winProtectedScreen](images/windows_defender_smartscreen.png) -->
On Mac, when you open the program for the very first time, you may see a warning that this app can not be opened. If you see this warning, please cancel it. Then <span style="color:orange">Right click</span> the software (the searchExam file), choose <span style="color:orange">Open</span> from the menu, and then click <span style="color:orange">Open</span> in the dialog that appears.
### Takes time to load initially
Once you open the software, it takes a few minutes to load initially. It is actually working in the background even if it may appear stuck. Please be patient till you see the **welcome screen** like this.
(If you can't read the image, right click on it and open it in new tab).

![welScreen](images/welcome_screen_blue.png)
## Input questions

Software will ask you to input some parameters like start date, end date, location of exam center etc. This is similar to how you select the start date, end date and location on the website.

However, you use the mouse on the website, but here you have to write the inputs with keyboard and press the enter key.

### Taking care of format
While entering inputs, please take special care of the format . For example, **dates** should be entered in YYYY-MM-DD format like 2022-12-31. For some questions like **Refresh Interval**, you only have to write digits, no alphabets. (Refresh Interval means how regularly should the software refresh the website and check for new dates).

### Taking care of limitations
While entering inputs, please take care of the limitations. For example, there is a question about how long this program should run continuously. Its maximum limit is 30 for plus subscription plan (which means you have to start the software again after a month - During those 30 days it will regularly check the dates for you without your interference).

### Entering GPS Coordinates for location of exam center

To select the location of exam center, you can **not** simply write the city name. 

You would need to input the GPS coordinates of the exam center for which you want to find the available dates.

For example, if you want to see the dates for exam center in  Gurugram, India, you should input <span style="color:orange">28.421080, 77.043670</span>

It is fairly easy to find GPS coordinates of any location using [Google maps](https://www.google.com/maps){:target="_blank"}. 

- Search your desired exam center on google maps.
- Right click on the location and you will see the coordinates for that location.
- Click on the coordinates and it will be copied.
- Then paste it into Search Exam software when it asks to input GPS coordinates. 
- For example, for Prometric center near Kolkata, India, you should enter  <span style="color:orange">22.575710, 88.435663</span>

![kolkata_center](images/kolkata_center.png)

## Finally - The dates screen

After entering all the inputs correctly, you will see the available dates like this:

![dates_screen](images/dates_screen_black.png)

This screen will show an alert in red color (and play alarm) for all available dates when the software refreshes the website for the first time.
In the subsequent refresh cycles, you will only get alerts for the new dates (new dates are the dates that did not appear in the previous refresh cycle). List of available dates will still be shown.

Time interval between each refresh cycle depends on what you input at the start of the program.

Refresh cycle number is shown below in the screen, and also the time when the last successful refresh happened.

### Notes

You need to keep the computer active (not sleep/shutdown etc.) in order for this program to keep running.

All dates/times used in this program are in [UTC timezone](https://www.google.com/search?q=utc+time+zone){:target="_blank"}.

### Subscription
If you like the program and want to renew/upgrade the subscription, please [contact us](../contact/) via email.
