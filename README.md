mobile-backend-starter-android-client-with-AndroidStudio
========================================================

This project is an Android native client sample for Mobile Backend Starter
that works with AndroidStudio.

Disclaimer: This is not an official Google Product.

## Products
- [App Engine][1]
- [Android][2]

## Language
- [Java][3]

## APIs
- [Google Cloud Endpoints][4]
- [Google Cloud Endpoints Backend Source][5]

## IDE
- [Android Studio][6]

## Setup Instructions
These instruction list only the key steps.
For detailed setup instructions and documentation visit the [Google App Engine developer site] (https://developers.google.com/cloud/samples/mbs).

1. Make sure you have the Android SDK with Google APIs level 15 or above installed.

2. Import the project into Android Studio (File -> Import Project).

3. Update the value of `PROJECT_ID` in
   `mobile-backend-starter-android-client-core/src/main/java/com/google/cloud/backend/core/Consts.java` to the app_id of your
   deployed Mobile Backend[5]. Make sure that your Mobile Backend is configured
   with OPEN mode. Also update your `PROJECT_NUMBER` and `WEB_CLIENT_ID` with the values from your console project.

4. Run the application.

[1]: https://developers.google.com/appengine
[2]: http://developer.android.com/index.html
[3]: http://java.com/en/
[4]: https://developers.google.com/appengine/docs/java/endpoints/
[5]: https://github.com/GoogleCloudPlatform/solutions-mobile-backend-starter-java
[6]: http://developer.android.com/sdk/installing/studio.html

