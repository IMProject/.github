## About
This project is created as an ecosystem to help other Embedded projects to save some time for developing Bootloaders and applications for Flashing.

## Discord
Join to project's <b>Discord</b> group:
https://discord.gg/r53FEqvz73

## Repositories
[IMBootloader](https://github.com/IMProject/IMBootloader) is a bootloader with different features written in **C** following the **MISRA C 2012** guidelines:
- accepts <b>signed</b> Firmware
- it is <b>secure</b>. It uses encrypted communication for firmware and bootloader update
- it can copy and run Firmware directly from the RAM
- it is  <b>self updatable </b>
- enters in bootloader over FLASH segment
- enters in bootloader over RAM segment
- enters in bootloader with button
- <b>CRC32</b> protected communication with IMFlasher
- capable of enabling <b>read protection</b> (RDP)
- capable of disabling read protection (RDP)
- generates 32 bytes long <b>unique board id</b>
- informs IMFlasher with  <b>GIT branch/hash/tag info</b>
- carry  <b>manufacturer id</b> for integration with a system
- carry <b>product type</b> data for integration with a system
- running Firmware from external FLASH over QSPI (paid version)


[IMFlasher](https://github.com/IMProject/IMFlasher) is a Qt application for flashing firmware or a new bootloader by using a PC. \
- multiplatform application
- auto detect IMBootloder over USB
- download files from [improject.imtech.hr](https://improject.imtech.hr) server

[IMLedBlink](https://github.com/IMProject/IMLedBlink) is a simple example that serves as a showcase of project capabilities. \
[IMUtility](https://github.com/IMProject/IMUtility) A Safety-Critical Utility Code written in C (Queue, CRC, data serialization/deserialization, base64...) 


### Architecture
![IMProject_architecture drawio](https://user-images.githubusercontent.com/10188706/166161827-8685d38a-fb8c-4b8a-bcd6-eb103b810c17.png)
