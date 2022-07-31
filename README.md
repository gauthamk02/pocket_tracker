# Pocket Tracker

This is our project for Hackathon [Hack@Arch](https://hackatarch.devfolio.co/) 2021, Conducted by GECT.

---

## Description
Pocket tracker is a money management app for every common man's usage.
The main goal of the app is to help you to efficiently keep track of your expenses.
The app has a very intuitive and easy to understand User Interface.
Upon opening the app, the user has to click a photo of his receipt. Our app's algorithm will extract the total amount from the receipt and ask the user to tag it with a label like grocery, medical, food, fuel, apparel etc.
The app shows a donut pie chart to the user to show him how much money he has spent category wise and will also give an alert when the budget is about to be over.
Additionally, the app also has a page for recent bills, where the user can view his past bills, along with the timestamp and its label, saving the user from the hassle of misplacing the receipt.
## Our team's vision towards this App
The long term vision of our team towards this project is to make the money management easy for a common man.
Initially we had a lot of ideas for this project, but due to the stipulated time frame, we applied only the main ideas as of now. Our future ideas are : -
enabling the app to read the user's bank transaction history by reading his/her bank sms, and storing this data in our app, extending it not only to paper receipts but also digital purchases
automate the process of entering the category of the transaction by using ML models to identify the category of purchase.



## Tech stack
<p align="center">
<img src="https://i.imgur.com/I6FNCiK.png" width="80"></img>
<img src="https://i.imgur.com/QEzASqR.png" width="80"></img>
<img src="https://www.gameartguppy.com/wp-content/uploads/2019/04/mascot_firebase-logo.png" width="80"></img>
</p>

---

## Screenshots
<img src="assets/preview/1.jpeg"
     alt="Markdown Monster icon"
     style=" margin: 30px; height: 500px;" />
<img src="assets/preview/2.jpeg"
     alt="Markdown Monster icon"
     style=" margin: 30px;height: 500px;" />
<img src="assets/preview/3.jpeg"
     alt="Markdown Monster icon"
     style=" margin: 30px;height: 500px;" />
<img src="assets/preview/4.jpeg"
     alt="Markdown Monster icon"
     style=" margin: 30px;height: 500px;" />
<img src="assets/preview/5.jpeg"
     alt="Markdown Monster icon"
     style=" margin: 30px;height: 500px;" />
<!-- <img src="assets/preview/2.jpeg"
     alt="Markdown Monster icon"
     style="float: right; margin: 10px;" /> -->

### Checkout  Devfolio Submissions: [Pocket Tracker](https://devfolio.co/projects/pocket-tracker-1ade)

## Instructions to run the app in your device locally

Before running the app in your device you need to set up Firebase backend.
 
<ol>
  <li>Clone the repository in your system</li>

  <li>Open a terminal window and navigate to the project directory</li>
  <li>Run 'flutter pub get' in the terminal window to get all packages used in the project</li>
  <li>Follow the steps in <b>Setting up Firebase</b> to set up the Firebase backend and Firebase SDKs.</li>
  <li>Open a simulator / connect your device physically to your device as per availability and preference</li>
  <li>Type 'flutter run' in the terminal window</li> 
</ol>

### Setting up Firebase:
<ol markdown=1>
  <li>Go to <a href="https://console.firebase.google.com/">Firebase Console</a> and create a new project.</li>
  <li>In the project console click on the Android logo to create configuration for Android.</li>
  <li>Follow the instructions on the page to add the package name ( which is `com.example.pocket_tracker` for the current version), saving the configuration file and adding Firebase SDKs to the project (The lines for adding Firebase SDKs are already present in the project and need to updated only if the version is outdated)</li>
  <li>The app uses Firestore Database, Authentication and storage services from Firebase. They need to be configured first before using the App. 
  
  <ul>
    <li>Click on Firestore Database from the Build dropdown in console page of the project and click on 'Create Database' button. After that select start in test mode and select the location of database before pressing the create button. Go to Rules tab and ensure permission line for read, write is set to `allow read, write: if true;`.</li>
    <li>Click on Authentication from the dropdown and select Email/Password to enable it.</li>
    <li>Select Storage from the dropdown and go to Rules tab and ensure permission line for read, write is set to `allow read, write: if true;`.</li>
  </ul>
  </li>
</ol>
