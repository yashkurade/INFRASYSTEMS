## Acronyms:
- PTZ - Pan Zoom Tilt
- NVR - Network Video Recorder
- DVR - Digital Video Recorder
- PoE - Power over Ethernet
- BNC - Bayonet Neill–Concelma
- ONVIF - Open Network Video Interface Forum
## Theory:
### IP vs Analog Cameras
- Definitions & Basic Differences
	- An analog camera is a traditional type of CCTV camera found in video security applications in many different industries. 
	- Analog cameras record images and transfer them for analysis and storage via wired connections, such as through a coaxial cable, to a recording device. 
	- They require a separate wired power supply.

	- IP cameras record images in a similar way, but they send data to a networked video recorder via the Internet or a local or wide area network (LAN or WAN). 
	- Unlike traditional cameras, an IP camera can take its power from the network using power‑over‑Ethernet (PoE) technology.

- Resolution & Image Quality
	- Analog camera technology is evolving with high‑definition (HD), now capable of up to 4‑ or 5‑megapixel resolution. 
	- However, that represents the high end of the range. Analog CCTV cameras do not offer the high resolution video footage that IP network cameras do.

	- IP cameras offer higher resolution across the range, with models offering 1.3 to 5 megapixels.

- Bandwidth & Transmission
	- IP cameras such as IP dome or bullet security cameras offer better quality, higher‑resolution images than analog camera CCTV versions. 
	- However, that increases the bandwidth and storage requirements because file sizes are larger.

- Cabling & Power
	- Analog cameras require separate cabling for power and connectivity. 
	- If the camera also provides audio feeds or incorporates pan, tilt and zoom functionality, each function will require separate dedicated cabling.

	- IP cameras can connect to a LAN or WAN via twisted‑pair Ethernet or coaxial cable to transmit images. 
	- They can also source power from the same network using a [PoE system](https://www.cisco.com/site/us/en/learn/topics/networking/what-is-power-over-ethernet.html) over twisted‑pair Ethernet cabling.

- Intelligence & Features
	- IP cameras such as PTZ IP security cameras have the edge here because they can be programmed to respond to specific events. They are sometimes described as ‘cameras with a brain’
	- IP cameras support resolutions that far exceed the 1080p standard, providing much clearer and more detailed images. 
	- Additionally, many IP cameras come with built‑in features such as motion detection, night vision, and on‑board analytics.

### Types of Cameras
| **Type**    | **Features**                                  | **Advantages**                                    | **Disadvantages**                           | Images                               |
| ----------- | --------------------------------------------- | ------------------------------------------------- | ------------------------------------------- | ------------------------------------ |
| **Dome**    | Dome-shaped, wide-angle lens, discreet design | Tamper-resistant, blends in, indoor-friendly      | Limited range, not ideal for zoom or pan    | ![Pasted image 20250623101852.png](Media/Pasted%20image%2020250623101852.png) |
| **Bullet**  | Cylindrical, visible deterrent, fixed lens    | Long-range, weatherproof, outdoor use             | More noticeable, can be vandalized          | ![Pasted image 20250623101903.png](Media/Pasted%20image%2020250623101903.png) |
| **PTZ**     | Remote pan, tilt, zoom, motorized             | Full coverage, controllable, efficient monitoring | Expensive, moving parts wear out            | ![Pasted image 20250623101912.png](Media/Pasted%20image%2020250623101912.png) |
| **Turret**  | Ball-and-socket mount, compact                | Adjustable, less prone to IR reflection (no dome) | Still somewhat exposed, limited zoom        | ![Pasted image 20250623101919.png](Media/Pasted%20image%2020250623101919.png) |
| **Fisheye** | Ultra-wide-angle (180°–360°), panoramic view  | Single cam covers wide area, fewer blind spots    | Distorted image, lower detail in wide areas | ![Pasted image 20250623101926.png](Media/Pasted%20image%2020250623101926.png) |
### NVR vs DVR
- What It Means
	- A DVR converts analog footage into a digital format, while an NVR typically only works with digital footage
	- Network video recorder (NVR) is a specialized computer system that records video to a disk drive … connects to cameras through a network … NVRs differ … as an NVR's input is from a network rather than a direct connection 
	- Video on a DVR is encoded and processed at the DVR, while video on an NVR is encoded and processed at the camera, then streamed to the NVR

- Cabling & Power
	- In a DVR system, the recorder doesn’t provide power to the cameras. Each camera connection will need a splitter
	- NVR systems use standard Ethernet cables … Ethernet cable powers the camera using Power over Ethernet (PoE)… only needs one cable running to capture video, audio, and power

- Image & Quality
	- Video quality is better on NVR … as Ethernet cables carry audio, all cameras with microphones could record audio to the NVR.
	- A DVR converts analog video via the coax cable directly to the recorder … analog signal results in a lower quality image compared to NVR systems.

- Flexibility & Scalability
	- DVR security systems are less flexible … can only use wired security cameras. … routing coaxial cable can be more difficult in tight situations.
	- NVR systems are inherently more flexible … cameras don’t necessarily have to be physically connected directly to the recorder. … could feasibly have cameras all over the world on the same network.

### Cabling & Power (PoE vs Separate Lines)
- PoE:
	- Power over Ethernet describes any of several standards or ad hoc systems (a temporary type of LAN where multiple devices can use it simultaneously) that pass electric power along with data on twisted‑pair Ethernet cabling. 
	- This allows a single cable to provide both a data connection and enough electricity to power networked devices such as IP cameras.

- Analog cameras require separate cabling for power and connectivity. 
- Electrical security camera cables and connectors are used to supply power and connectivity is via coaxial cable or twisted‑pair cabling. 
- If the camera also provides audio feeds or incorporates pan, tilt and zoom functionality, each function will require separate dedicated cabling.

- IP cameras such as panoramic IP security cameras only require a single cable for all of those functions. 
- They can connect to a LAN or WAN via twisted‑pair Ethernet or coaxial cable to transmit images. 
- They can also source power from the same network using a PoE system over twisted‑pair Ethernet cabling.

- BNC (Bayonet Neill–Concelma) connector uses coaxial cable for transmission. The limitation of its distance is 300 m. 
- PoE uses Ethernet for data transmission. It can transmit data up to 100 m, but this can be expanded. You can install repeaters to increase the distance up to 500 m.

### Coverage Planning & Camera Placement
| **Aspect**               | **Details / Best Practices**                                                       |
| ------------------------ | ---------------------------------------------------------------------------------- |
| **Objective**            | Maximize area coverage, reduce blind spots, enhance deterrence                     |
| **Planning Step**        | Start with a site map: entry points, valuables, traffic zones, blind spots         |
| **Mounting Height**      | 8–10 ft (ideal for visibility + tamper resistance)                                 |
| **Lighting Strategy**    | Place lighting above camera; avoid direct glare/backlight                          |
| **Common Patterns**      | - Back-to-Back- Corner-to-Corner- Inside Corner- Mid Wall (least preferred)        |
| **Choke Point Coverage** | Doorways, entrances, hallways — for clear facial/ID shots                          |
| **High-Risk Areas**      | Entrances, cash counters, parking lots, restricted areas                           |
| **Blind Spot Handling**  | Use overlapping coverage or secondary cams; avoid isolated views                   |
| **Camera Angle**         | Adjust for field-of-view, remove obstructions, match intended coverage width/depth |
- **Common Patterns**
1.  Mid Wall Pattern
![Pasted image 20250623104321.png](Media/Pasted%20image%2020250623104321.png)2. Back-to-Back Pattern
![Pasted image 20250623104346.png](Media/Pasted%20image%2020250623104346.png)3. Secret Service Pattern
![Pasted image 20250623104537.png](Media/Pasted%20image%2020250623104537.png)4. Corner-to-Corner
![Pasted image 20250623104546.png](Media/Pasted%20image%2020250623104546.png)5. Inside Corner
![Pasted image 20250623104600.png](Media/Pasted%20image%2020250623104600.png)
### Resolution & Frame Rate
- Resolution refers to the number of pixels in each frame of video. The higher the resolution, the more detail you capture.
- Resolution is measured in pixels. Then pixels are grouped into categories such as 2 megapixel, 4 megapixel, 5 megapixel and 8 megapixel
	- 1080p: 2 MP (1920 × 1080); 
	- 2K: 4 MP (2560 × 1440); 
	- 4K: 8 MP (3840 × 2160)
- Frame rate is measured in frames per second (FPS) and determines how smooth your footage looks
	- 15 FPS – Basic security footage
	- 20–25 FPS – Standard smooth video
	- 30 FPS – High‑quality motion
- Bitrate
	- **Bitrate** controls the amount of data the camera sends to the NVR per second. 
	- It directly affects image quality, especially in motion-heavy scenes.
		-  Low: 512–1024 kbps (grainy or pixelated, low bandwidth)
		- Medium: 2048–4096 kbps (standard clarity)
		- High: 8192–16384 kbps (great quality, higher storage use)

### ONVIF Standard
- ONVIF stands for Open Network Video Interface Forum. Its aim is to provide a standard for the interface between different IP-based physical security devices.
- These standardized ONVIF specifications are like a common language that all devices can use to communicate
- The end user benefits from this interoperability because they are no longer tied to a single brand for everything to work
- ONVIF is the CCTV and video surveillance industries voluntary data format that standardizes IP camera signals so different brands of equipment can communicate with each other
- Video security systems use Profiles D, G, M, S, and T, while access control systems use Profiles A, C, D, and M
- ONVIF is a security standard, whereas RTSP — a key element of video and audio streaming — is a protocol
- Limitations
	- Many other features may or may not operate depending on the combination of brands 
	- Motion activated recordings, remote alerts, two-way audio, digital image adjustments, and AI features may or may not work 
	- ONVIF is voluntary and each manufacturer develops their own features unique to their equipment

### Storage Calculation
- To accurately calculate storage requirements, you need to consider three variables:
	1. resolution
	2. frame rate
	3. compression
- Storage calculation = number of cameras × recording hours per day × bit rate (based on resolution/FPS/compression) × number of days of retention.
- For example, a 4 MP camera recording at 15 fps with H.264 compression may generate around 4 GB per day
- Using newer compression standards such as H.265 instead of H.264 can reduce storage usage by up to 50% at identical image quality.
## References:
- https://www.pelco.com/blog/analog-vs-ip
- https://www.secureredact.ai/articles/analog-vs-digital-security-cameras
- https://www.avigilon.com/blog/types-of-cctv-cameras
- https://info.verkada.com/compare/dvr-vs-nvr/
- https://en.wikipedia.org/wiki/Network_video_recorder
- https://blog.swann.com/dvr-vs-nvr-whats-the-difference/
- https://www.backstreet-surveillance.com/security-cameras-made-simple-a-diy-guide/security-camera-locations.html
- https://montavue.com/blogs/news/understanding-bitrate-frame-rate-and-resolution-in-security-cameras
- https://www.pelco.com/blog/onvif-guide