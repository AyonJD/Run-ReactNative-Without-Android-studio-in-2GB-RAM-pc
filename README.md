
# Run React Native in custom Emulator without Android Studio or any Physical device in a 2GB RAM PC




## Installation

```bash
  1. npm install -g expo-cli (One time)
  2. npx create-expo-app ProjectName
  3. cd ProjectName
  4. npm start / expo start
```

    
## After That

- Install Memu Player (For low-end pc).

- Install Expo into Memu player.

- Right click on Memu player and “Open file location”.

- Open command prompt in that location and run, adb connect localhost:19000 (exp://192.168.0.101:19000, you will get this after the command npm start/expo start).

- Restart Memu player.

- In the first command prompt after the npm start press “a” for starting android emulator.

- Open Expo app into Memu player and click Enter URL manually.

- Paste  exp://192.168.0.101:19000 this from the first command prompt. You will get it after the npm start/expo start command.


## Thank You

Boom, you are using your Emulator not the Android Studio or any physical device. In this way ou can build Android app with a 2GB ram PC.

If you have any feedback, please reach out to us at ayonjodder177@gmail.com

