# AWSTest-Android
Testing AWS + SNS integration for Android

* Official setup docs: http://docs.aws.amazon.com/mobile/sdkforandroid/developerguide/setup.html
* AWS SDK to use as dependency in project is: https://github.com/aws/aws-sdk-android

Dependency for SNS can be added to gradle as: `compile 'com.amazonaws:aws-android-sdk-SNS:2.2.+'`

----

Some hardcoded values needed for setup in Android project:

* Cognito Identity Pool: `eu-west-1:ce293d64-dad2-493e-a09e-881c822484c4`

* Application ARN: `arn:aws:sns:eu-west-1:618717458389:app/GCM/AWSTest_Android`

* Region: `Regions.EU_WEST_1`
