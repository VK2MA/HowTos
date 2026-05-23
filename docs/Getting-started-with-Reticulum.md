# Getting Started with Reticulum
## Installing and Configuring an LXMF (Messaging) client

In this example we will be installing the [Reticulum MeshChatX](https://meshchatx.com) app that is available for Mac, Linux and Windows.

Go to [Reticulum MeshChatX](https://meshchatx.com) then download and install the most recent version of the app for your operating system.

Run the program and go to the **Interfaces** section.

Click on **+ Add Interface** and configure it as follows:

**Name:** `HADARC Hub`

**Type:** `TCP Client`

**Target Host:** `hub.hadarc.org.au`

**Target Port:** `4242`

Click on **Add interface**

![Add TCP Interface](assets/Interface_add_TCP.png)

Click on **Restart Now**

![Restart](assets/Inetrface_add_restart2.png)

## Start Messaging

Go to the **Messages** section

Click on **Compose**

Enter the address of the **HADARC LXMF Group** which is `0f24f850aa7cf536a557fac3621bd06e`

Type `/join` in the **Send a Message** box and click **Send**

You will get a notification you have joined the messaging group.

You can now send messages to the group.

## Browse a Micron Page on the Nomad Network

Go to the **Nomad Network** section

Click on **Open a Nomadnet URL**

Enter `429572a04001a8023bf4c2518e34f95b:/page/index.mu`

Follow the links on the Home Page, similar to using a web browser

## Add an RF interface
This is where Reticulum starts to make sense for Amateurs, using RF to carry the data.

The simplest place to start is to use an RNode. These use common Microcontroller dev boards with LoRa radios in the ISM band.

I have had good results with the Heltec Wireless Stick Lite which can easily be purchased online.

We are using the following settings for LoRa

## What's Next

Reticulum is more than a messaging system, it's a complete network stack supporting just about anything that runs over networks. This includes things like file transfers and even real time traffic such as voice and video.

Probably the most interesting aspect for Amateur Radio enthusiasts is the ability of Reticulum to work over low speed radio links.

To that end a number of HADARC members are setting up LoRa radios around the Hornsby area. If you are interested in participating please follow this guide and send a message to the **HADARC LXMF Group** asking how to set up an RNode and where the existing RNodes are located

Read more at [https://reticulum.network](https://reticulum.network)
