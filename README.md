# Sign-with-SHA-1-Key-on-Android-Studio-
How to sign your project on Android Studio 


STEPS:

=>Open your project in android studio and open terminal

=>Type this code 

                       debug.keystore
                       
                       
=>After that automaticly open the new file and  you will see all encrypted data on this file

=>Save that this file on the your project files and file name like debug.keystore

=>After that go to C:\Program Files\Android\Android Studio\jre\bin, open the terminal and  write this code


                  .\keytool -list -v -keystore YOUR_ANDROID_FILE_PATH\debug.keystore -alias androiddebugkey -storepass android -keypass android

Note: YOUR_ANDROID_FILE_PATH => This your project path we want that this path because we save debug.keystore file on this path!



=>After that you will see your uniqe SHA-1 fingerprint on your project!








