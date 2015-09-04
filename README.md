#How to add custom fonts to a React Native app in Xcode

*Create a new group Fonts within your Xcode project
*Drag and drop fonts from Finder to the Fonts group you just created, and check your project name in Add to targets list
Expand your project name folder within the main directory in your project and open Info.plist
Add Fonts provided by application as a new key
Add a new item named after the full font name with extension under Fonts provided by application for each font you've added to the fonts folder
Run Shift + Command + K to clean last build
Then Command + B to start a new build
And finally Command + R to run the application
If you still see the error Unrecognized font family restart your react packager.
