# BonjourWebrtc
Server-less or No Server or Zero Conf Webrtc for iOS. Bonjour Networking abstracted as MultiPeerConnectivity framework in iOS is used for webrtc signalling. Refer to [my blog](https://mobilitysolutionsexpert.wordpress.com/) for more details

## Instruction
	1.	Install app on 2 iOS devices, preferably with iOS 8 and above
	2.	Peers will be listed with their device name
	3.	Tap on a peer
	4.	 Incoming call notification will be sent to that peer
	5.	 If peer accepts, webrtc connection will be established.


## Screenshots
**Peer Listing Screen**

![Alt text](/../screenshot/screenshot/peerScreen.PNG?raw=true "Peers Screen") 

**Video Screen**

![Alt text](/../screenshot/screenshot/videochat.PNG?raw=true "Video Screen")

## License

MIT

##To Say Hi
[Me](https://in.linkedin.com/in/dhilipr)

[My blog](https://mobilitysolutionsexpert.wordpress.com/)

#Gene's edit 1 Feb 2017  
*When opening in a newer version of XCode, asks if we would like to convert to Swift 3. Say Later/Later  
*Go to Build Settings->Swift Compiler - Version->Use Legacy Swift Language Version and set to YES  
*In BonjourServiceManager.swift, change Line 99 from:
invitationHandler: ((Bool, MCSession))   
To:
invitationHandler: (Bool, MCSession?) 
  
