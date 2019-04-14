# Online Chat using Firebase with Flutter

Small app using firebase functionality to authenticate, storage data and storage media files, using some plugins to implement this methods.

## Dependencies of the project

These dependencies have to be on pubspec.yaml on flutter project.

 cloud_firestore: ^0.8.2+3
 google_sign_in: ^3.2.4
 firebase_auth: ^0.6.2+1
 firebase_storage: ^1.0.4
 image_picker: ^0.4.12+1

## Some observations

→ In the graddle of application (app level) the multiDexEnabled have to be set "true", because if not, will get some error because some incompatibility with version of firebase_storage plugin.

→ Two themes options, dependenting of the platform, will be showed they respective theme.

→ Image picker working only on camera.

## Some pictures of the app

<div>

<img style="float: right;" src="https://user-images.githubusercontent.com/44711197/56100173-daa3bc80-5eeb-11e9-96c5-da44e015099e.png" width="290"/>

<img style="float: right;" src="https://user-images.githubusercontent.com/44711197/56099963-0aea5b80-5eea-11e9-9296-206259604518.png" width="290"/>

<img style="float: right;" src="https://user-images.githubusercontent.com/44711197/56100136-bb0c9400-5eeb-11e9-8b67-46115ba01585.png" width="290"/>



</div>


