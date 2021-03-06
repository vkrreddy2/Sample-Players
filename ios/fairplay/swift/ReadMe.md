# About iOS FPS Client

iOS FPS Client is a simple iOS app that illustrates how to implement and install an AVAssetResourceLoader delegate that will handle FairPlay Streaming key requests.

For additional information about AVAssetResourceLoader, see the AVAssetResourceLoader Class Reference:
https://developer.apple.com/library/ios/documentation/AVFoundation/Reference/AVAssetResourceLoader_Class/

To learn more about FairPlay Streaming, see the FairPlay Streaming Guide document.

## Requirements

Hardware -- Fairplay playback will not work on emulators

## Code adaptation required

Modify the defaultCertURL and the playListURL near the top of  PlayerViewController.swift to test playback
of a single asset quickly.

To run on hardware you will need to modify the xcode project to provide a valid signing idenity and application profile.   See the signing section of the profile

### Build

iOS 9 SDK, Xcode Version 8 or greater

### Runtime

iOS 9 SDK
iPhone, iPad

Copyright (C) 2015 Apple Inc. All rights reserved.
