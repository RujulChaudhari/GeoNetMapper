# Tutorial: Network Scanning and Mapping with GeoIP and Wireshark

## Introduction

Welcome to this step-by-step tutorial on using GeoIP with Wireshark to analyze network traffic and visualize connections on a map. This tutorial is designed for beginners with zero experience in network analysis.

## Prerequisites

Before you begin, make sure you have the following installed:

- [Wireshark](https://www.wireshark.org/)
- [Python](https://www.python.org/)
- [GeoIP Database](https://dev.maxmind.com/geoip/geoip2/geolite2/) (for IP to location mapping)

## Step 1: Install Wireshark

Download and install Wireshark from the official website: [Wireshark Download](https://www.wireshark.org/download.html).

## Step 2: Capture Network Traffic

1. Open Wireshark and select the network interface you want to monitor.
2. Click on the "Start" button to begin capturing network traffic.

## Step 3: Analyze Captured Data

1. Let Wireshark capture data for a reasonable amount of time.
2. Stop the capture and analyze the captured packets.

## Step 4: Export IP Addresses

1. Export the list of IP addresses from Wireshark.
2. Save the list to a text file.

## Step 5: Install GeoIP Python Library

Install the `geoip2` Python library for IP to location mapping:

```bash
pip install geoip2
