# How to Download the App Sample
## Prerequisites
To make installations easier, download [Chocolatey](https://chocolatey.org/) (windows) or [Homebrew](https://brew.sh/) (macOS)
  - Install Nodejs (v12 or above)
  `choco install -y nodejs.install`
  - Install Python (v2 or above)
  `choco install -y python2`
  - Install jdk8
  `choco install -y jdk8`
  - Install React Native CLI
  `npm install -g react-native-cli`
  - Install Yarn
  `choco install yarn`
  - Download [AndroidStudio](https://developer.android.com/studio/index.html) and make sure you setup your environment to be able to run an app on Android Emulator
  
## Clone this Repo
  - Go to Code -> Clone (copy the http:// address)
  - Open a powershell (windows) or a terminal (macOS) and go to the directory where you want to clone this code
  - Type: `git clone [use the http address you just copied from GitHub]`
  - You now should have a local copy of the app
  
## Get the App Running
  - Go to the app directory: `cd PropertyFinder`
  - Start your Android emulator runnning SDK 23 is it isn't running
  - Run the following command in a terminal:
  `react-native run-android`
  - You should have now the app running in your Android Emulator!
