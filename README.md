# firebase_practice

##expo init => android, ios (X)
  expo eject
  packge name : com.example.MyProject

##Debug signing certificate SHA-1 get
cd android && ./gradlew signingReport

Uuntu/Mac
  keytool -list -v -keystore ~/.android/debug.keystore -alias androiddebugkey -storepass android -keypass android

firebase upload
