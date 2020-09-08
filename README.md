## Welcome to Cloint Vision's Face Recognition based Employee Attendance System

<img src="https://1.bp.blogspot.com/-6PReDvLHoKI/X1Wqasj7ySI/AAAAAAAAAQs/Jx2vYKipYkQ4ezCcpQWS2B4pIHrqV12OgCLcBGAsYHQ/s320/Cloint_GIF.gif">

## Live Application : https://cloint-vision.appspot.com

## This project is already deployed on our Google App Engine. 
## End Users (Non Developers): Steps to use this application on your computer:

# 1. Please visit the web application using Google Chrome and give required permissions for Camera
Latest Version: https://cloint-vision.appspot.com

# 2. Once your face appears on your monitor screen, enter your name and hit 'Register This Face' blue button.
Wait till you see 'Registered ! Please add some more photos with different poses' and click OK.
You can add few more (5 is better) photos of yours, with different poses. This is a one time activity. In any time, if you wish wish to delete all registered/stored faces, just hit 'Clear Database'.

# 3. You may refresh the page and see your name listed as 'List of Registered Employees in your Organization' at the bottom of the page in table

# 4. You may now click on 'Start Taking Attendance'.
Please wait, while required JavaScript libraries are loaded.. And you can hear the application wishing you via voice command.

# 5. You may also visit, old Versions:
1) https://cloint-vision.appspot.com/index-v1.html
2) https://cloint-vision.appspot.com/index-v2.html
3) https://cloint-vision.appspot.com/index-v3.html

## Note:
1) All the photos are stored locally in your browser as 128 bit encodings
2) No facial data is stored on any server. Its just stored in your own browser. Please hit 'Ctrl+Shift+I' on Chrome browser to take yourself to 'Chrome DevTools' and go to 'Applications' tab. Expand, 'IndexedDB' and you can see all the face encodings's numerical values.. thats it !!!
3) Only Name and arrival-time gets stored in the Google Spreadsheet
4) If the application gets struck, at any time, just hit F5 or refresh the page !


## For Developers / Contributors Reference:

# 1. Download (latest) NodeJS:
https://nodejs.org/en/download/

# 2. Clone this repository
git clone https://github.com/ClointFusion/Cloint-Vision.git

# 3. Open Command Promt and Go to that folder
Ex: cd <..\..\> cv-app

# 4. Enter this command to install nodeJs dependencies
npm install

# 5. Run locally 
npm start

# 6. Browse to http://localhost:8080/

# 7. Deploy to your App Engine

    gcloud app deploy

    [appengine tutorial]: https://cloud.google.com/appengine/docs/standard/nodejs/quickstart

# This project is developed using face-api.js libraries:
https://github.com/justadudewhohacks/face-api.js#running-the-examples

# For more information, please drop me an email: 
mayur@cloint.com

## We love your Contributions:
Please submit a Pull request