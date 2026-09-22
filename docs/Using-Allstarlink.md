# Using Allstarlink with VK2RNS

## Why Allstarlink

Allstarlink (ASL) is a Radio over IP (ROIP) solution based on the open source software PBX Asterisk.

It is an alternative to other ROIP solutions such as Echolink and IRLP in that is designed for use with analog FM radios and repeaters and is not directly comparable to ther varios digital modes such as DMR, D-Star etc.

The reason Allstarlink was chosen as the primary ROIP technology for use a the HADARC club 2M repeater VK2RNS was it is open source, has superior audio quality due to a wide choice of codecs and has less rigid network requirements / limitations.

Allstarlink also has basic compatibility with Echolink and can participate in the Echoloink network.

## VK2RNS Allstarlink Network Design

A simple implementation of Allstarlink just requires a connected computer running Allstarlink software, an internet connection and a sound card interface to a radio / repeater.

A limitation of the internet connection at the Storey Park location is that the service is over the mobile network which uses CGNAT. This essentially means it is not possible to receive incoming connections via the internet. It is possible to make outgoing connections.

The solution to this problem has been to implement an Allstarlink node on a cloud hosted linux server. This server has a public IP address and can receive incoming connections as well as make outgoing connections.

The ASL node at Storey Park has a permanent connection which it establishes outbound the the cloud server. Users on the internet connect to the cloud server so the audio is effectively linked through to Storey Park.

## Connecting to VK2RNS

The cloud server has the primary node number for VK2RNS which is 57272. The on-site node at Storey Park is node number 564022.

**Generally users just connect to node 57272.**

The cloud server is also connected to the Echolink network as VK2RNS-R or Echolink node number 611366.

## Using Apps to Access Allstarlink

### Linux

[AllStarLink V3](https://www.allstarlink.org/)

[Hamvoip - Asterisk Allstar on the Raspberry Pi 2/3/4](https://hamvoip.org/)

### macOS

[Transceive](https://islandmagic.co/transceive)

### Windows

[AllStar Web Transceiver - Microsoft Store](https://apps.microsoft.com/detail/9nk9jn5kcq1d?hl=en-GB&gl=AU)

[QSO One - Free client for AllStarLink, EchoLink, IAX Direct, DMR, System Fusion, and M17](https://qso1.net)

### iOS

[RepeaterPhone](https://repeaterphone.com/)

[nostar/DroidStar](https://github.com/nostar/DroidStar)

### Android
[AllStar Web Transceiver for Android — WT, Direct IAX2, and Node Mode](https://github.com/TerryClaiborne/AllStarWebTransceiver-Android)

[QSO One - Free client for AllStarLink, EchoLink, IAX Direct, DMR, System Fusion, and M17](https://qso1.net)
