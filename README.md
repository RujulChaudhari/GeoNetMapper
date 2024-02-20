# Tutorial: Network Scanning and Mapping with GeoIP and Wireshark

## Introduction

Welcome to this step-by-step tutorial on using GeoIP with Wireshark to analyze network traffic and visualize connections on a map. This tutorial is designed for beginners with zero experience in network analysis.

## Prerequisites

Before you begin, make sure you have the following installed:

- [Wireshark](https://www.wireshark.org/)
- [GeoLite Database](https://dev.maxmind.com/geoip/geoip2/geolite2/) (for IP to location mapping)

## Step 1: Install Wireshark

Download and install Wireshark from the official website: [Wireshark Download](https://www.wireshark.org/download.html).

## Step 2: Install GeoLite Databases
1. Go to [GeoIP](https://dev.maxmind.com/geoip/geoip2/geolite2/) to download the databases.
2. You need the GeoLite-ASN, GeoLite-City, and GeoLite-Country databases.

## Step 3: Configure GeoLite in WireShark

1. Start WireShark, go to the "Edit" tab and go to the Preferences menu.
2. There you want to click on "Name Resolution". You will see "MaxMind Databases Directories" at the bottom.
3. Click on the "edit" button next to it. And select the directory where you installed the GeoLite databases.

## Step 4: Scanning the Network

1. Once GeoLite has been added to WireShark. Go ahead and run a scan.
2. Once you have enough data. Go ahead and stop the scan.
3. Here you will see multiple Ips listed. If you click on anyone of them and select the "Ipv4" option. You will see towards the botton that the GeoLite data associated with the ips.

## Step 5: Mapping the Ips out on the web browser.

1. In Wireshark, click on the "Statistics" menu and select "Endpoints"
2. Here on the left-hand side you will see a "Map" optin. Go ahead and select it and hit "Open in browser".
3. This will give you a visual of where each connection is coming from to your netowrk.




# Enjoy!
