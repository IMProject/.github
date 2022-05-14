This project is created as an ecosystem to help other Embedded projects to save some time for developing Bootloader and application for Flashing.\
\
[IMBootloader](https://github.com/IMProject/IMBootloader) is a bootloader with different features:
- accepts <b>signed</b> Firmware
- enters in bootloader over FLASH segment
- enters in bootloader over RAM segment
- enters in bootloader with button
- copy and run Firmware from RAM
- it is  <b>self updatable </b>
- <b>CRC32</b> protected communication with IMFlasher
- capable of enabling <b>read protection</b> (RDP)
- capable of disabling read protection (RDP)
- generates 32 bytes long <b>unique board id</b>
- informs IMFlasher with  <b>GIT branch/hash/tag info</b>
- carry  <b>manufacturer id</b> for integration with a system
- carry <b>product type</b> data for integration with a system \


[IMFlasher](https://github.com/IMProject/IMFlasher) is a Qt application for flashing firmware by using a PC. \
[IMLedBlink](https://github.com/IMProject/IMLedBlink) is a simple example that serves as a showcase of project capabilities.


### Project Architecture
![IMProject_architecture drawio](https://user-images.githubusercontent.com/10188706/166161827-8685d38a-fb8c-4b8a-bcd6-eb103b810c17.png)
