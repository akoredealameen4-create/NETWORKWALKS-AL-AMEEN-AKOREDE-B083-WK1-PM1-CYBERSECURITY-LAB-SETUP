# NETWORKWALKS-AL-AMEEN-AKOREDE-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP
# Week 1 Project: Kali Linux and Windows Network Setup

## Project Overview

This project documents my Week 1 lab, where I configured Kali Linux and Windows to communicate over a virtual network. The aim was to understand how virtual machines connect, how to check their network settings, and how to test communication between them in both directions.

I connected Kali Linux and Windows to the same virtual network, checked the network configuration on each machine, and tested the connection from Windows to Kali and from Kali to Windows.

## Project Objectives

The objectives of this project were to configure the network settings for Kali Linux and Windows, identify the network adapter used by each machine, and test whether they could communicate with each other. I also documented the challenges I encountered and what I learned while troubleshooting the network configuration.

## Lab Environment

I used VirtualBox to run Kali Linux and Windows. Both machines were connected to the same virtual network, which allowed me to test communication between them.

## Network Configuration

I configured the network settings for both virtual machines and checked that each was connected to the intended virtual network. During this process, I had some challenges configuring the network. I reviewed the adapter and network settings, made the necessary adjustments, and learned how the configuration affects communication between the machines.

## Connectivity Testing

I tested connectivity from Windows to Kali Linux using the `ping` command. The test was successful, and Windows received replies from Kali.

I then tested connectivity from Kali Linux to Windows using `ping`. This test was also successful, and Kali received replies from Windows.

Both machines were able to communicate with each other in both directions.

## Challenges and Troubleshooting

The main challenge I faced was configuring the network settings for Kali Linux and Windows. I needed to make sure both machines were connected to the correct virtual network and that their settings allowed them to communicate.

Working through this challenge helped me understand how virtual network adapters and network configuration affect connectivity. I checked the settings, made adjustments, and tested the connection again until communication worked successfully in both directions.

## What I Learned

This lab taught me how to configure virtual machine network settings and check network connectivity between Kali Linux and Windows. I learned that both machines need to be connected to the appropriate virtual network for them to communicate. I also learned that troubleshooting and testing each direction helped me identify and resolve the configuration issue.

## Conclusion

I successfully configured Kali Linux and Windows to communicate over a virtual network. The Windows-to-Kali test and the Kali-to-Windows test were both successful. Although configuring the network settings was challenging, troubleshooting the setup helped me understand virtual machine networking better.

## Safety

All testing in this project was performed between my own machines in my virtual lab. I will only test systems and networks that I own or have permission to use.
