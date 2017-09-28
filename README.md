# Ionic Cancham iOS/Android App

This is an hybrid app made with Ionic w/ Angular for the CANCHAM so their event attendants can know about it, their events and communicate between them.

## Requirements

* [NodeJS](https://nodejs.org/en/download/) >= 6.11.3
* Npm (Included with NodeJS) >= 3.10.10

## Getting Started

1. First clone the project:

```bash
git clone https://github.com/arturoaviles/ionic-cancham.git
```

2. Go inside the directory:

```bash
cd ionic-cancham/
```

3. Download dependencies:

```bash
npm install -g ionic cordova 
```

4. Run Locally (Web Browser):

```bash
ionic serve
```

## Run in your device

Each device needs its own configuration:

* Ionic View App (Reccomended Option)
* iOS
* Android
* Simulator iOS/Android

### Ionic View (Reccomended Option)

1. Create an [Ionic Pro Account](http://ionicframework.com/). 

2. Download the Ionic View app from the Appstore/Playstore to your device.

3. Go inside the project directory:

```bash
cd ionic-cancham/
```

4. Sign up in the [Ionic Framework](https://ionicframework.com/) website. 

5. Login to your account from the terminal:

```bash
ionic login
```

6. Link your app to Ionic Pro:

```bash
ionic link
```

> It's is going to ask you to generate a ssh key. Create it.

> It's also going to ask you to enter a name for your new app or select an already made one.

7. Push the app to Ionic Pro: 

```bash
git push ionic master
```

8. In your web browser go to Ionic Pro website and login with your Ionic Pro account.

9. Select your app in the Ionic Pro dashboard.

10. Go to "Channels" and create one (Example: Alpha, Beta, Mkt, Testers).

11. Go to "Builds" and hit deploy.

12. Open the app in your device, login into your account and select the project.

### iOS

1. Go inside the project directory:

```bash
cd ionic-cancham/
```

2. Install/Update Xcode:

```bash
xcode-select --install
```

3. Install the iOS npm module:

```bash
sudo npm install -g ios-deploy
```

4. Install Ionic iOS platform

```bash
ionic platform add ios
```

5. Build the iOS Cordova for Ionic:

```bash
ionic cordova build ios
```

7. Run the project for iOS

```bash
ionic cordova run ios
```

With Live Reload:

```bash
ionic cordova run ios -l
```

### Android

1. Go inside the project directory:

```bash
cd ionic-cancham/
```

2. Install Ionic Android platform

```bash
ionic cordova platform add android
```

3. Run the project for Android

```bash
ionic cordova run android
```

With Live Reload:

```bash
ionic cordova run android -l
```


### Simulator iOS/Android

1. Build the project for iOS

```bash
ionic cordova build ios
ionic cordova emulate ios
```


## Adding new stuff

If you would like to add a:

* component
* directive
* page
* pipe 
* provider
* tabs

Run the command:

```bash
ionic generate
```

## Deploy to the Appstore

1. Sign up for an [Apple Developer Account]()

## Deploy to the Playstore

1. Sign up for a [Google Developer Account]()

## License

Copyright © 2017 CANCHAM. All rights reserved.
