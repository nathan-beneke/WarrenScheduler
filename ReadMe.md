<center>
	<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.1fTmJYEvdd8nf7Ufb5uG1AHaHa%26pid%3DApi&f=1" height=250>
	<h1> Camp Warren Scheduler</h1>
</center>
Table of contents

* [Welcome](#Welcome)
* Getting Started
* Formatting Data
* [Troubleshooting](#Troubleshooting)
***
### Welcome
Hello there and welcome to the Camp Warren camper scheduler. 
This program exists to help you, the program coordinator, create schedules for camp in a fraction of the regular time. In the creation of this program we are hoping that you can spend more time writing the staff schedule and making the office run smoothly and less time figuring out how to fit kids into activities. Below you'll find hopefully all you'll need to know to get the program up and running but as always, if you have any questions or problems reach out to Cole Polyak at colepolyak@gmail.com or through Facebook messenger. 
Have a wonderful summer and good luck!

### Getting Started
To download the scheduler, download the jar file in this repository by first clicking on the file:
![GitHub Repo](https://i.imgur.com/B9pTTcW.jpg)
And then selecting the download option.
![Github Repo](https://i.imgur.com/E51cH9A.jpg)
After the download has completed, find the Jar file on your computer. Double click to run. A dialog will appear guiding you through selecting the file with the input data and choosing how many iterations you would prefer.

**IMPORTANT:** Ensure that the Excel data file is **closed** before running the program. In order for the program to read and write to the file, it must be closed.

After selecting the file, and clicking okay, the program will run. Currently, the program takes roughly 60 seconds. When it has finished a dialog will appear: 
![Finished screen](https://i.imgur.com/sgfCBk0.jpg)
Then you're all set!
***
### Formatting Data
The program uses the XSSF library, meaning only Excel files from 2008 or newer can be used. In this repository you will also find the Excel sheet detailing the format the program expects campers in. 
![Excel Sheet](https://i.imgur.com/2OBX1id.jpg)
Each camper should appear in this format. 

Adding or altering activities is also simple. Activities are formatted as follows:
![Excel Sheet](https://i.imgur.com/A4XFCT1.jpg)Each column represents if the activity is offered that period. The final column, "Variable?", tells the program that which period that activity appears can be changed for the sake of finding a better schedule. 

**Emphasis** has to be handled slightly different currently. If you want an activity with only emphasis kids in that activity, you have to add the following to the activity sheet and the camper sheet:
![](https://i.imgur.com/3mo4xCl.jpg)
![](https://i.imgur.com/C4ETCXs.jpg)This way the program will schedule only emphasis kids in those activities. 
***
### Troubleshooting
If for some reason you get weird errors, try the following:
* Ensure there are no junk lines in the Excel file, including random space lines.
* Ensure that each camper has six activities and that the names are spelled correctly given the activities listed on the activities page. 
* Ensure that the sheet is **closed** so that the program can read and write to it. 
* Shoot Cole an email at colepolyak@gmail.com
