# Router Monitor

Display with ESP8266 and SPI LCD

<img src="./images/routermonitor.jpg" width="200" alt="routermonitor" />
[NetData](https://github.com/netdata/netdata)

## Introduction

This mini TV project utilizes the ESP8266 module combined with a 1.54-inch SPI LCD screen to display data metrics. The data is sourced from [NetData](https://github.com/netdata/netdata) on a router, showcasing details about CPU, memory, and network usage in real-time.
| ![routermonitor](./images/routermonitor.png) | ![pikaqiu](./images/pikaqiu.png)  | 



## Features

- **Compact Design**: Perfect for desktop setups.
- **Real-time Data Monitoring**: Instantly displays router metrics including CPU, memory, and network.
- **Wireless**: Leverages the WiFi capabilities of the ESP8266.

## Prerequisites

- Hardware:
  - ESP8266 Module
  - SPI LCD screen
- Software:
  - [NetData](https://github.com/netdata/netdata) installed on the router
  - PlatformIO (for ESP8266 programming)

## Setup & Installation

1. **Hardware Setup**: Connect the ESP8266 to the 1.54" SPI LCD as per the [schematics](https://oshwhub.com/Q21182889/esp-xiao-dian-shi) provided.
2. **Software Installation**: 
   - Flash the ESP8266 with the provided firmware using the VSCode IDE.
   - Ensure [NetData](https://github.com/netdata/netdata) is correctly set up and running on your router.

## Usage

1. Power on the mini TV.
2. Connect the ESP8266 to your WiFi network
3. The device should now start displaying the data metrics.

## Compile

### 1. CH340 Driver Download
#### 1.1 Download & install Driver Here
https://www.wch.cn/downloads/category/67.html?feature=USB%E8%BD%AC%E4%B8%B2%E5%8F%A3&product_name=CH340


### 2. Dev Environment
1. Install Visual Studio Code
2. Install PlatformIO Extenion
![](images/platformIO.png)
1. Clone, Open Folder

### 3. Logic
- main.ino Main Logic
- NetData.h Netdata Interface


## Contributing

We welcome contributions! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the GPL License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Thanks to [NetData](https://github.com/netdata/netdata) for their comprehensive data collection tools.
- Shout out to the ESP8266 community for their resources and support.
- **This project is forked from the [routermonitor](https://gitee.com/dannylsl/routermonitor) project.**

