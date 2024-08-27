# Chapter 2: Basic switch and end device configuration
## [2.1] Cisco IOS access
### [2.1.1] Operating systems
    - all end to end and network devices require an OS
    - kernel - part of the OS that directly interacts with the hardware
    - shell - portion that interfaces with applications and the user 

    | shell    | allows users to make specific requests to the kernel                       |
    |          | made through cli or GUI                                                    |
    | kernel   | communicates between hardware and software                                 |
    |          | manages how hardware resources are used to meet the software  requirements |
    | hardware | physical part of the computer                                              |


### [2.1.2] GUI
    an environment of graphical icons
    requires less knowledge of the underlying command structure that governs the OS
    does not provide all the capabilities of the CLI

    *OPERATING SYSTEMS ON ROUTERS ARE COMMONLY CALLED AS FIRMWARE

### [2.1.3] Purpose of an OS
    Cisco devices run on Cisco IOS

### [2.1.4] Access methods
    | Method             | Description                                                                                     |
    |--------------------|-------------------------------------------------------------------------------------------------|
    | Console            | Physical management port that provides out-of-band access to a Cisco device                     |
    |                    | requires dedicated software emulation tool and special cable                                    |
    |                    | device is configurable even if there are no networking devices configured (for initial configs) |
    |                    |                                                                                                 |
    | Secure Shell (SSH) | recommended for making remote CLI connections                                                   |
    |                    |                                                                                                 |
    | Telnet             | insecure SSH, does not encrypt                                                                  |
    |--------------------|-------------------------------------------------------------------------------------------------|
    * some devices may have an AUXILIARY PORT. There are used to establish remote connections over a telephone connection using a modem. Somewhat similar to console connection since it is out of band and does not require any networking device to be configured or available.
    * out-of-band - means dedicated channel for device maintenance purposes only

### [2.1.5] Terminal Emulation Programs
    Putty, TeraTerm, SecureCRT

## [2.2] IOS Navigation
### [2.2.1] Primary Command Modes
    Cisco IOS software seperates management access into two command modes:
        1. User EXEC mode 
            with the symbol ">"
            cannot change the configuration of the device in this mode but can execute basic monitoring commands
        2. Priveleged EXEC mode 
            with the symbol "#"
            can execute configuration commands to the device
            higher configuration modes can only be accessed through this mode

### [2.2.2] Configuration mode and subconfiguration modes
    To configure a device, a user must enter the GLOBAL CONFIGURATION MODE (global config mode)



