# Apple & Salesforce Pre-TDX Challenge!

## Table of Contents

1. [Prerequisites](#pre)
1. [Source Control Setup](#download)
1. [Challenge Requirements](#requirements)
1. [Challenge Validation](#validation)
1. [Additional Resources](#resources)

## Prerequisites <a name="pre"></a>

In order to complete this challenge you'll need:

1. A working installation of Git.
2. An Apple Computer with xCode 10.1 (or higher) installed.
3. If you want to install the sample app on a physical iOS device, you'll need an Apple Developer Account.
4. A Salesforce developer edition org (Signup at [developer.salesforce.com](https://developer.salesforce.com/signup))

## Source Control Setup <a name="download"></a>

This project makes use of [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules), in addition to Xcode build dependencies to incorporate the SDK. This means you must not only clone _this_ repository, but the submodule repositories as well. If you have not yet cloned this repository, this clone command will clone not only this repo, but the submodules as well.

```console
git clone --recurse-submodules https://github.com/trailheadapps/MobileSDK-Starter.git
```

If you've already cloned this repository, please initialize the submodules using this command

```console
git submodule update --init --recursive
```

## Challenge Requirements <a name="requirements"></a>

To complete this challenge, you need to develop an application using Swift 5 and the Salesforce Mobile SDK for iOS. Your application must have the following features:

- Utilize Biometric authentication via the Salesforce Mobile SDK for iOS
- Has a tab based navigation user interface that can display
  - Accounts by name retrieved from Salesforce
  - Allows users to select a specific account and see a list of all contacts related to that account.
  - Allows users to select a specific contact and see the contact's name, address, phone number and email address as well as any attached files.
- Allows the user to take a photograph, and upload it to Salesforce as an attachment related to a specific Contact.

## Challenge Validation <a name="validation"></a>

You must present your application on either a iPhone or the iOS Simulator to booth officials before the close of TrailheadX'19.

## Additional Resources <a name="resources"></a>

For more information on the Salesforce Mobile SDK for iOS check out these resources:

1. [Salesforce Mobile SDK Basics](https://trailhead.salesforce.com/en/content/learn/modules/mobile_sdk_introduction)
2. [Native iOS Trailhead Module](https://trailhead.salesforce.com/en/content/learn/modules/mobile_sdk_native_ios)
3. [Get Started with iOS App Development](https://trailhead.salesforce.com/en/content/learn/trails/start-ios-appdev)
4. [Swift Essentials](https://trailhead.salesforce.com/en/content/learn/modules/swift-essentials)
