# OS-X-Dell-XPS420-Clover
Files needed for installing Mac OSX on Dell XPS 420

## Hardware Spec
- BIOS: Dell XPS 420 System BIOS, A07
- MB: Intel X38 Express (ICH9R)
- CPU: Intel Core 2 Quad Q6600 @ 2.39GHz
- GPU: ATI Radeon 2600 Pro (GFX should be replaced with supported card)
- Memory: 4x 2G DDR2-800
- Storage: 500GB SATA HDD
- LAN: Intel 825xx Gigabit Platform LAN
- Audio: Sigmatel STAC9227 C-Major HD Audio

## BIOS Settings
To enter the BIOS setup, press F2 while booting at the Dell loading screen.

- Under “Drives -> SATA Operation”, set the SATA mode to “RAID On”.
- Under “Onboard Devices -> Integrated NIC”, select “On”.
- Under “Onboard Devices -> Integrated Audio”, select “On”.
- Both Windows SideShow, i.e. the small screen on the case, and the Dell Media Accelerator, will not work with OSX. Therefore, unless you will also be booting Windows, you may set both “Miniview Display” and “Media Accelerator” to “Off”.
- Under “Video -> Primary Video”, select “PEG”.
- Under “Power Management -> Suspend Mode”, select “S3”.

## Installation

### Prepare USB Stick
To be continued.