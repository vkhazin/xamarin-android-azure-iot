# xamarin-android-azure-iot

## Requirements

* Build a simple Xamarin application with one screen
* The app should display application version in a read-only fashion
* The app should have a multiline text box with a `Send` button next to it
* When the `Send` button is selected the application will send a message along with app version number to Azure Message Queue
* Azure Serverless function to read a message from the queue and to print the message to Azure Logs

## Deliverables

* Xamarin application
* Instructions in a form of readme.md how to deploy to an Android device
* Automated setup of Azure IoT Hub
* Ability to push a new version of the xamarin app without Android user ***intervention***
* Ability to click a button on the xamarin app to send a text to Azure Message Queue
* Azure logs displaying the message and the app version sent from the app
* A demo and a walk through on updating the version of xamarin app, building, deploying to Android device, and sending message

## How to submit work

* Fork this repository
* Create a separate folder for Xamarin App, Azure IoT automation, and Azure function
* Commit code to your own repository
* Submit a pull request back to this repository
