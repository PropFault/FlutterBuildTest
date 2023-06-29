# FlutterBuildTest

## Asset Replacement
Each client must have a .zip file in the asset folder

Naming scheme: {client_id}.zip
e.g.: Client id = itb -> assets/itb.zip


### Zip file structure

The zip file must contain two folders:

android
ios


files found in android_assets/res get merged into /android/app/src/main/res
files found in ios_assets get merged into /ios/Runner/Assets.xcassets
android/play_store_512.png gets used for play store deployment


Example: overriding app icon

android/mipmap-hdpi/ic_launcher.png
android/mipmap-mdpi/ic_launcher.png
android/mipmap-xhdpi/ic_launcher.png
android/mipmap-xxhdpi/ic_launcher.png
android/mipmap-xxxhdpi/ic_launcher.png

ios/AppIcon.appiconset/Icon-App-20x20@1x.png
ios/AppIcon.appiconset/Icon-App-20x20@2x.png
ios/AppIcon.appiconset/Icon-App-20x20@3x.png
ios/AppIcon.appiconset/Icon-App-29x29@1x.png
ios/AppIcon.appiconset/Icon-App-29x29@2x.png
ios/AppIcon.appiconset/Icon-App-29x29@3x.png
ios/AppIcon.appiconset/Icon-App-40x40@1x.png
ios/AppIcon.appiconset/Icon-App-40x40@2x.png
ios/AppIcon.appiconset/Icon-App-40x40@3x.png
ios/AppIcon.appiconset/Icon-App-60x60@1x.png
ios/AppIcon.appiconset/Icon-App-60x60@2x.png
ios/AppIcon.appiconset/Icon-App-60x60@3x.png
ios/AppIcon.appiconset/Icon-App-76x76@1x.png
ios/AppIcon.appiconset/Icon-App-76x76@2x.png
ios/AppIcon.appiconset/Icon-App-76x76@3x.png
ios/AppIcon.appiconset/Icon-App-83.5x83.5@2x.png
ios/AppIcon.appiconset/Icon-App-1024x1024@1x.png


