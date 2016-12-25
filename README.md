# SwitchCaseGenerator
An Xcode Source Editor Extension that generates a swift switch case statement based on selected enum cases

![Generate switch example](https://github.com/timaktimak/SwitchCaseGenerator/blob/master/Assets/Example.gif)

## Installation

1. Clone or download the repo
2. Open ``SwitchCaseGenerator.xcodeproj``
3. Enable target signing for both the Application and the Source Code Extension using your own developer ID
4. Select the application target and then Product > Archive
5. Export the archive as a macOS App
6. Run the app, then quit (Don't delete the app, put it in a convenient folder)
7. Go to System Preferences -> Extensions -> Xcode Source Editor and make sure the extension is enabled
8. The menu-item should now be available from Xcode's Editor menu
