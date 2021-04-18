# firebase_practice
Application made with React Native


### expo init => android, ios (X)
    expo eject
    packge name : com.example.MyProject

### Debug signing certificate SHA-1 get
    cd android && ./gradlew signingReport
    Uuntu/Mac
    keytool -list -v -keystore ~/.android/debug.keystore -alias androiddebugkey -storepass android -keypass       android

firebase upload

### react-native run android (x)
     Android studio > Preferences(cmd+,) > Build, Execution, Deployment > Compiler > Command-line Options > -- warning-mode=all --stacktrace add


## Result

* android emulator

![initial](https://user-images.githubusercontent.com/61046271/115129660-ee2a1680-a022-11eb-8560-4eee3247a08a.png)

* firebase - cloud messaging

![initial](https://user-images.githubusercontent.com/61046271/115129664-f1bd9d80-a022-11eb-8bcf-28cfb25751e7.png)

