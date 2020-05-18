# QuickApp
As close to a single file iOS app as you can get. 

## Usage
1. Copy `QuickApp.xcodeproj` to a new directory.
2. Open project, add a new Swift or ObjC file with a class named `MainViewController` or `TestViewController`
    - if you don't want a `UINavigationController` name your class `RootViewController`
3. Change the Product Name (aka Display Name) in the Project properties (optional)
    - change the Team and BundleID if you want to run on a device.
4. Build and Run.

## Renaming project.
if you rename the file `QuickApp.xcodeproj` you will need to update the file references for `Info.plist`, `Main.m`, and `Launch.storyboard`. 




