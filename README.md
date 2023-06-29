# FlutterBuildTest

## Asset Replacement
Each client must have a .zip file in the asset folder

Naming scheme: {client_id}.zip
e.g.: Client id = itb -> assets/itb.zip


### Zip file structure

The zip file must contain two folders:

android_assets 
ios_assets


files found in android_assets get merged into /android/app/src/main/res
files found in ios_assets get merged into /ios/Runner/Assets.xcassets


Example: overriding app icon

android_assets/mipmap-hdpi/ic_launcher.png
android_assets/mipmap-mdpi/ic_launcher.png
android_assets/mipmap-xhdpi/ic_launcher.png
android_assets/mipmap-xxhdpi/ic_launcher.png
android_assets/mipmap-xxxhdpi/ic_launcher.png

ios_assets/AppIcon.appiconset/Icon-App-20x20@1x.png
ios_assets/AppIcon.appiconset/Icon-App-20x20@2x.png
ios_assets/AppIcon.appiconset/Icon-App-20x20@3x.png
ios_assets/AppIcon.appiconset/Icon-App-29x29@1x.png
ios_assets/AppIcon.appiconset/Icon-App-29x29@2x.png
ios_assets/AppIcon.appiconset/Icon-App-29x29@3x.png
ios_assets/AppIcon.appiconset/Icon-App-40x40@1x.png
ios_assets/AppIcon.appiconset/Icon-App-40x40@2x.png
ios_assets/AppIcon.appiconset/Icon-App-40x40@3x.png
ios_assets/AppIcon.appiconset/Icon-App-60x60@1x.png
ios_assets/AppIcon.appiconset/Icon-App-60x60@2x.png
ios_assets/AppIcon.appiconset/Icon-App-60x60@3x.png
ios_assets/AppIcon.appiconset/Icon-App-76x76@1x.png
ios_assets/AppIcon.appiconset/Icon-App-76x76@2x.png
ios_assets/AppIcon.appiconset/Icon-App-76x76@3x.png
ios_assets/AppIcon.appiconset/Icon-App-83.5x83.5@2x.png
ios_assets/AppIcon.appiconset/Icon-App-1024x1024@1x.png


