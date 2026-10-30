# Cybersecurity Lab Setup

## Student Details

- Name: Etinosa Osahon
- Project: Week 1 - Project Module 1
- Topic: VirtualBox and Kali Linux Lab Setup

## Lab Configuration

I configured a cybersecurity testing lab using Oracle VirtualBox and Kali Linux.

- VirtualBox NAT Network: `10.0.0.0/24`
- Kali Linux static IP address: `10.0.0.2/24`
- Default gateway: `10.0.0.1`
- Internet access: verified successfully
- Shared Clipboard: enabled
- Drag and Drop: enabled
- Shared Downloads folder: enabled
- VirtualBox snapshot: created after completion

## Configuration Steps

1. Configured a NAT Network in VirtualBox using the `10.0.0.0/24` subnet.
2. Connected the Kali Linux VM to the NAT Network.
3. Configured Kali Linux with the static IP address `10.0.0.2/24`.
4. Verified the gateway and internet connection using ping tests.
5. Enabled shared clipboard and drag-and-drop between Linux Mint and Kali.
6. Added the Linux Mint Downloads folder as a shared folder.
7. Created a VirtualBox snapshot of the completed lab.

## Verification

The Kali Linux VM successfully received the required static IP address and connected to the internet. Both IP-address and domain-name ping tests completed with 0% packet loss.

## Evidence Screenshots

The required configuration screenshots are included in this repository:

- NAT Network configuration
- Kali VM NAT Network settings
- Clipboard and Drag-and-Drop settings
- Shared Downloads folder settings
- Kali IP address and internet test
- Completed VirtualBox snapshot
