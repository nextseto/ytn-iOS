![image](https://github.com/nextseto/Players-iOS/blob/master/assets/banner.png)

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/nextseto/Players-iOS/master/LICENSE)

Players is an iOS application written in Swift that communicates with a custom backend `Players-Cloud` to get video information and metadata from Youtube.

## Screenshots

![image](https://github.com/nextseto/Players-iOS/blob/master/assets/iphoneX-screenshot.png)
![image](https://github.com/nextseto/Players-iOS/blob/master/assets/ipad-screenshot.png)

## Purpose

#### Introduction

I love watching videos in my spare time. Whether its watching TV shows on my TiVo or online via Youtube/Twitch. When I got my iPod Touch in 2009, I religiously used the built in Youtube app to watch Gaming Let's Plays and other content. When Apple removed the Youtube app in iOS 6, I tried to find alternatives, however, as time went on these Youtube-app-alternatives got bloated and I eventually got frustrated. I spent more time closing the built in popup ads and "Rate me!" dialogues than actually enjoying the purpose of the app; watching my favorite youtube channels.

I was just so fed up with other apps that I took it upon myself to make something to satisfy my hunger of watching great content on Youtube.

#### Development Requirements

- Swift: Apple's latest/modern programming language

- Core Data/UserDefaults: Stores data for subscriptions and cached videos

- UICollectionView: This type of view paradigm is ideal to present/layout video details

- iPhone / iPad Support: Be able to support all iOS devices

#### Roadmap

I started working on this in 2014 and I've been slowly working on it to improve its performance and reliability on both the front/back-end. With the front-end, I had to update the source to conform to the changes to the Swift language. With the back-end, I had to try different packages and Javascript techniques to shave milliseconds off the processing/response time.

- [ ] Time Stamps in Videos
- [ ] Detecting and opening links for Channel URLs
- [ ] Full details for cached content
- [ ] Add Placeholders for empty View Controllers
- [ ] Non-Hacky Background Content Playback (custom playback)
- [ ] Now Playing Screen Implementation: Lock Screen & Control Center (custom playback since `AVPlayerViewController` limits certain customizations)
- [ ] Details for Channels
- [ ] More Options for Searching Videos
- [ ] Support iCloud Sync for Backing Up Subscriptions
- [ ] Support Playlists
- [ ] Twitch-App Style In-App Background Video
- [ ] Support additional Youtube categories: Trending, Private, etc
- [ ] Support additional video provides: Twitch, etc 

#### :)

It's been a long road, but it is finally done. I'm proud of what is currently on GitHub.

Thank you to everyone who has helped me and this project along the way. (Friends, family, reddit testers!!)

## Requirements

- 10.13+ High Sierra
- iOS 11+
- Xcode 9.2+ (with Swift 4 support)

## License

All source code in Players-iOS is released under the MIT license. See LICENSE for details.
