## To deploy the app to production, the dev team can follow these steps:

1.) Make sure the code is in a stable state and has been thoroughly tested on the target platforms.

2.) In the root of the project, use the command "npx cap build" to build the app for the target platforms 
(electron, ios, android etc)

3.) Use the command "npx cap copy" to copy the built files to the appropriate folder for each platform 
(for example, "electron/dist" for electron)

4.) Use the command "npx cap open" to open the project in the appropriate IDE for each platform 
(for example, Xcode for ios)

5.) In the IDE, use the appropriate method to sign the app and create the final build.

6.) Release the app to the desired app stores or distribute it as a standalone app.

Note: Steps 4-6 may vary depending on the specific platform you are targeting and the method you choose to distribute
 the app (e.g. App Store, Play Store, GitHub Releases, etc)

The dev team may also use the Github action configured earlier for building and releasing the app to automate these steps.
