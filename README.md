# IP-Based Pinball Streaming-Platform
## A budget-friendly portable pinball streaming platform designed to provide professional-quality multi-camera tournament coverage using commodity networking hardware and Android smartphones.

This project was built to solve a specific problem:

Professional wireless video systems capable of supporting
multiple cameras often cost between **$2,000 and $3,000** to implement.

By combining readily-available consumer networking equipment, Android smartphones,
and open-source software, I was able to create a reliable, high quality
multi-camera production platform for a fraction of the cost.


## Design Requirements

The system must:

- Support 3 simultaneous cameras
- Operate without venue Ethernet
- Use existing venue WiFi when available
- Deploy in under 15 minutes
- Remain portable
- Operate from battery power
- Cost substantially less than commercial HDMI solutions


## Engineering Decisions

**Why not wireless HDMI?** 

Commercial wireless HDMI solutions were considered. While devices such as Accsoon's CineView line of HDMI transceivers do offer better image quality, the cost savings of an IP-based video streaming solution makes the project extremely accessible to individuals wishing to broadcast pinball events on a budget. The used smartphone market is saturated with devices capable of capturing 1080p/60fps video which can be had for as little as $40. HDMI solutions also require physical cabling from each receiver to the streaming computer, adding more time for setup and requiring much more consideration in the placement of equipment. With an IP-based wireless solution, the streaming computer does not require any actual physical connection to the rest of the system (although I recommend having the streaming computer connected to the router directly via ethernet for the best performance).


## Hardware Requirements

Camera frame/rig (insert link to materials/instructions)

**Network Equipment**

Router - GL.iNet Beryl AX  
Access Point - TP-Link EAP225  
WiFi Bridge - Ubiquiti NanoStation loco M5  
Cat5e/6 cables

**Cameras**

3x Android smartphone with a 1080p/60fps camera and a 5Ghz WiFi radio. Samsung Galaxy S9 or newer, Motorola Moto G phones are excellent choices and can be bought for as low as $40 on eBay.

**Streaming Computer**

Any modern Windows or Apple laptop (or even desktop) computer is suitable for the setup. I am personally using a Macbook M1 Pro as my streaming computer and it performs extremely well. If you wish to use Windows, I would recommend a laptop or compact desktop with a dedicated graphics card. Having a physical ethernet port is also recommended. This can be achieved using a USB to Ethernet adapter as well.
