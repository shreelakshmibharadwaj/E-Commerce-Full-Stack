# How to Setup & Run this Project


### Install NodeJs (Ignore If Already Installed)

1.  Visit the official Node.js website i.e) https://nodejs.org/en/download/
2.  Download the Node.js installer 
3.  Run the installer 
4.  Follow the prompts in the installer 

### -First Run Backend then Frontend & Admin-

## Steps To Setup Backend Of The Project

1.  Open Project Folder In VS Code 
2.  Open Integrated Terminal

    * Right Click on 'backend' > Select "Open In Integrated Terminal"
3.  Type "npm install" and press Enter and Wait for Installation to be completed (requires Internet)
4.  Setup Cloudinary for file storage.

    * Create account and login to: https://cloudinary.com/ 
    * The go to Dashboard
    * Copy and paste the Cloud Name, API Key, And Secret Key in the backend/.env file: 
5.  Setup The MongoDB

    * a. Open this link - [LINK](https://mongodb.com/cloud/atlas/register) 
    * b. After that Sign Up on the website.
    * c. Click on New Project Option 
    * d. After Creating Project go to Database Section & Build a database
    * e. Select M0 & Your Region & Create Database 
    * f. Setup Username & Password & Create User 

        * Users will be given the read and write to any database privilege by default. 
        * You can update these permissions and/or create additional users later. 
        * Ensure these credentials are different to your MongoDB Cloud username and password.
    * g. Now Click on Finish & Close.
    * h. Whitelist IP 0.0.0.0 & Click on Add Entry
    * i. Now Click on Connect.
    * j. Now Select Compass Option.

        * Explore, modify, and visualize your data with MongoDB's GUI
    * k. And Copy the Connection String 

        * Replace <password> with the password for the greatstack user, 
        * When entering your password, make sure that any special characters are URL encoded.
    * l. And Paste It in the backend / .env file and replace the <password> with the password you set previously in 4.F & save changes.
6.  Setup Stripe (Optional) -

    * a. create a stripe account from [here](https://stripe.com/).
    * b. After creating account get the Stripe Secret Key from dashboard.
    * c. Paste the Secret Key in backend/.env file and save file.
7.  Setup Razorpay(Optional) -

    * a. create a razorpay account from [here](https://razorpay.com/) 
    * b. After creating account get the Razorpay Secret Key & Razorpay Key ID from dashboard.
    * c. Paste the Secret Key in backend/.env file and save file.
8.  To Run Backend use npm run server command in Integrated Terminal. 

    * ***Before Running Frontend or Admin Projects make sure Backend is Running in the background terminal*** 

## Steps To Run Frontend of The Project

1.  Right Click on 'frontend' folder > Select "Open In Integrated Terminal".
2.  Type "npm install" and press Enter and Wait for Installation to be completed (requires Internet).
3.  After that type "npm run dev" in terminal.
4.  Now you will see the '[http://localhost:5173](http://localhost:5173)' link in that terminal. Open that link in the browser. 

## Steps To Run Admin Panel of The Project

1.  Right Click on 'admin' folder > Select "Open In Integrated Terminal" .
2.  Type "npm install" and press Enter and Wait for Installation to be completed (requires Internet).
3.  After that type "npm run dev" in terminal.
4.  Now you will see the '[http://localhost:5174](http://localhost:5174)' link in that terminal. Open that link in the browser.



