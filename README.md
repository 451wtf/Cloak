# 🦸 Cloak OS **→** 451.wtf's OS based on our Silhouette Kernel
CloakOS is an OS made by 451.wtf which are F(L)OSS and Privacy enthusiasts for people who:
- want to try something new.
- want an OS which is easy to use.
- want an OS where Updates don't brick the System.
- want an OS which is noob-proof.
- want an OS easy on resources.

The OS and our Kernel are both written in Zig, for learning purposes and to make the internet a more private place.

> [!CAUTION]
> Nothing here mentioned is applicable to the OS as of August 21st 2025.
> This OS is NOT functional. Our main focus is the [Silhouette Kernel](https://codeberg.org/451/Silhouette)

## Focus
**→** Privacy » No tracking, no telemetry. Block domains, IPs or Ports for Apps or the complete OS and easily configure the Firewall. Sandbox apps natively with one click. <br/>
**→** Usability » Install, uninstall and update Software easily using our App Store or CLI Tool. <br/>
**→** Design » We try to make everything as modern as possible, from the Developer API to the Userland of Cloak. <br/>
**→** Built-in Software » DeadDrop is our own Chat App made for extreme privacy, Arc is our own IDE with a focus on Privacy, Usability and Simplicity. Both can be uninstalled. <br/>

Note: None of the above mentioned software exists yet. Usage examples will be provided once the software is available.

## Planned Features
- [ ] Developer API
- [ ] Domain, IP and Port blocking.
- [ ] Firewall GUI
- [ ] Settings GUI
- [ ] App Store
- [ ] DeadDrop
- [ ] Arc

## System Requirements (Goals)
- 250mb RAM
- 800mb Space on HDD/SSD

## Install
1. Download the ISO from our Release
2.
    - Move it to an [Ventoy](https://ventory.net/) USB Drive (Recommended)
    - Flash it to an USB Drive
3. Boot to the USB Drive

## Developer API
We want that Developers have an easy way to create applications for Cloak OS.
From TUIs (Terminal/Text User Interfaces) to GUIs (Graphical User Interfaces), the API will allow easy creation of Software with a nice IO API.

## Contribute
Requirements: <br/>
**→** Zig 0.14.1 <br/>
**→** x86_64 (64 Bit) AMD/Intel CPU. <br/>
**→** Qemu, CMake, Git <br/>


**1. Preferred Way** <br/>
Join our [Discord Server](https://discord.gg/Knm3aHMmkW) and apply to join us to work on Cloak and/or Silhouette.

**2. One-Time Contributions (or two, three, ... times)** <br/>
Create a Pull Request.

**3. Clone and Run the OS** <br/>
```bash
git clone https://codeberg.org/451/Cloak.git
cd Cloak
make run-x86_64
```

## License
The Kernel and the OS are both Licensed under GPLv3 ONLY. [See our license](LICENSE)