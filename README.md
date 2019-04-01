## Google Home Number Generator
Simple Google Assistant app that lets users to store a number in a database.

Implemented functionality:
- Asking for current number
- Setting number to a given value (or random)
- Guessing number
- Signing up for notifications
- Invoking push notifications (for mobile devices) - User gets a push notification every time his/hers number changes
- Invoking TTS notifications on Google Home (just on devices with local access though as Google Assistant apps on Google Home do not support push notifications)

App speaks in the following languages:
- Polish `pl_PL`
- English `en_US`

##### Running server
1. Installing depedencies `npm install`
2. Deploying server `firebase deploy` (or `firebase serve` to run server locally)

##### Brief info about deploying the whole app
In order to get the app working you need
to link the project with Firebase and Dialogflow with all the corresponding intents, link Firebase webhook to Dialogflow and generate account credentials for push notifications from Google API Console.

##### Used technologies
- NodeJS
- Firebase
- Cloud Firestore
- Dialogflow
- JWT
