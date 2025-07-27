## Acronyms:
- ACS - Access Control System
- DAC - Discretionary Access Control
- MAC - Mandatory Access Control
- RBAC -  Role-Based Access Control
- REX - Request to Exit
- OSDP - Open Supervised Device Protocol

## Theory:
### Access Control
- An Access Control System (ACS) is an electronic system that regulates the entry of individuals or vehicles into a protected area through authentication and authorization processes at designated access points
- Its main goal is to prevent unauthorized access and ensure the safety and security of people and assets within the controlled area

### Types of Access Control
1. Discretionary Access Control (DAC)
	- Discretionary access control is a decentralized access control policy that allows subjects to control access to objects
	- Discretionary access control means that once the end user has access to a location or a digital system, they're able to grant the same privileges to any other person at their own personal discretion.
	- ![Pasted image 20250624100440.png](Media/Pasted%20image%2020250624100440.png)

2. Mandatory Access Control (MAC)
	- Mandatory access control (MAC) is a security strategy that restricts the ability individual resource owners have to grant or deny access to resource objects
	- MAC criteria are defined by the system administrator and cannot be altered by end users
	- MAC is a system where access is determined by a central authority based on predefined security policies. Its rigid, non‑discretionary structure makes it ideal for securing highly sensitive information
	- ![Pasted image 20250624100902.png](Media/Pasted%20image%2020250624100902.png)

3. Role-Based Access Control (RBAC)
	- Role-based access control (RBAC) restricts network access based on a person's role within an organization
	- RBAC is an access control model that grants permissions to specific roles within a school or department, rather than to individual users
	- ![Pasted image 20250624101336.png](Media/Pasted%20image%2020250624101336.png)

4. Rule-Based Access Control
	- Rule-based access control (RuBAC) is an access control system that allows user access to network resources according to pre-defined rules
	- Rule-based access control regulates access to resources, where access is granted or denied based on pre-defined rules. These rules are created by an administrator
	- ![Pasted image 20250624101448.png](Media/Pasted%20image%2020250624101448.png)

###  Components of an ACS
- Door or Entrance: 
	- The physical barrier that controls access to a protected area. It’s the entry point where individuals interact with the system to gain access.
- Electrified Door Hardware: 
	- A device that receives signals from the Access Control System to lock and unlock doors.
- Card/Biometric Reader: 
	- A device that reads credentials (key cards, fobs, mobile devices) presented by individuals seeking access. It communicates with the control panel to verify identity and access permissions.
- Door Contact: 
	- A sensor that detects whether the door is open or closed. It sends a signal to the control panel, ensuring security before granting access and monitoring for unauthorized attempts to open the door.
- Request to Exit (REX): 
	- A device that allows authorized individuals to exit a controlled area without using a credential. It typically consists of a button or sensor that unlocks the door temporarily for egress.
![Pasted image 20250624101721.png](Media/Pasted%20image%2020250624101721.png)

### Authentication vs Authorization
| **Aspect**                 | **Authentication**                                          | **Authorization**                                        |
| -------------------------- | ----------------------------------------------------------- | -------------------------------------------------------- |
| **Definition**             | “Verifies that someone is who they say they are.”           | “Determines what that person can do or access.”          |
| **Purpose**                | To confirm identity                                         | To grant access rights                                   |
| **Process Type**           | Identity verification                                       | Permission validation                                    |
| **Occurs When?**           | First – always before authorization                         | After successful authentication                          |
| **Based On**               | Credentials: passwords, PINs, biometrics, etc.              | Policies, roles, permissions                             |
| **Examples**               | Logging in with username/password                           | Allowing user to view or edit certain files              |
| **System Concerned With**  | “You are who you say you are”                               | “You’re allowed to do what you're trying to do”          |
| **Can They Happen Alone?** | No – authentication is always required before authorization | No – authorization is meaningless without authentication |
| **Key Difference**         | Proves _who_ you are                                        | Grants _what_ you can do                                 |

### Access Modes
|**Mode**|**Description**|**Pros**|**Cons**|
|---|---|---|---|
|**Card-Based**|Uses RFID/proximity cards or keyfobs with readers|Simple, low-cost, widely used|Cards can be lost, cloned, or stolen|
|**Biometric-Based**|Uses unique human traits like fingerprint, iris, or face recognition|High security, can't be shared or stolen|Can fail in poor lighting or due to physical changes|
|**Mobile-Based**|Uses smartphones (Bluetooth, NFC, QR) as credentials|Convenient, easy to manage remotely|Requires smartphones, dependent on app/network availability|

### Access Levels & Scheduling
- Access Levels
	- Different access control system levels can be set for different users, meaning that employees can access sensitive areas of a building only when they have the proper authorization
	- Enhanced physical security: modern access systems enable you to manage visitors and set access groups and schedules for different user groups like full-time employees, contractors, and vendors
	- There are five types of database access levels:
		- **Read-only:** The user can only view data in the database. He or she cannot update, insert, or delete data.
		- **Select:** The user can select data from the database. He or she cannot update, insert, delete, or alter data.
		- **Update:** The user can update data in the database, and they cannot select data.
		- **Insert:** The user can insert data into the database. He or his cannot select data.
		- **Delete:** The user can delete data from the database.
	
- Scheduling / Timed Access
	- Restrict access to certain times of day or specific days of the week, aligning with business hours and employee schedules
	- automatic locking during non-operational hours enhances security, while precise timing allows for scheduling access, granting temporary access, and maintaining audit trails

### Integration with Other Systems
1. Fire Alarm Integration
2. CCTV Integration
3. BMS Integration
4. Unified Control Platforms (C•CURE 9000)

### Wiring & Network Topologies
- RS‑485 (Serial Controllers)
	- RS‑485 standard allows long cable runs, up to 4000 feet (1200 m)
	- The maximum number of devices on an RS‑485 line is limited to 32, which means that the host can frequently request status updates … display events almost in real time
	- RS‑485 does not allow Star‑type wiring unless splitters are used
- Daisy‑Chain (Bus) Topology
	- A daisy chain is a wiring scheme in which multiple devices are wired together in sequence 
	- Daisy chains may be used for … digital data
	- Any particular daisy chain forms one of two network topologies: Linear topology … or Ring topology … often called a ‘daisy chain loop'
- OSDP with RS‑485 / Daisy‑Chain
	- OSDP has a concept called ‘multi‑drop’ that allows devices to daisy chain directly from the controller to the reader and then to a secondary reader and so on. This reduces … number of individual cable runs
	- OSDP uses RS‑485 wiring. … Key features include long‑distance transmission and multi‑drop

### Types of Doors and Lock Mechanisms
| **Lock Type**               | **Description**                                                                                                                                                                                                      | **Pros**                                                                                                | **Cons / Notes**                                                                                                     | Images                               |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- | ------------------------------------ |
| **Magnetic Lock (Maglock)** | “Magnetic locks … use magnetic attraction produced from electric currents to securely shut a door. … Maglocks consist of two components: an electromagnet … and a metal plate.”                                      | “Highly durable and reliable, easy to install and provide a strong level of protection.”                | “Require constant power to operate … in a power outage … unlocks when power is lost.”                                | ![Pasted image 20250624162447.png](Media/Pasted%20image%2020250624162447.png) |
| **Electric Strike**         | “Electric strikes are electromechanical door locking devices … controlled by solenoids … locked by default and unlock when powered.”                                                                                 | “Affordable … compatible with existing lock bolts … can be fail-safe or fail-secure.”                   | “Requires precise installation … may need to modify the door frame.”                                                 | ![Pasted image 20250624162133.png](Media/Pasted%20image%2020250624162133.png) |
| **Mortise Lock**            | “A mortise lock … requires a pocket — the mortise — to be cut into the edge of the door … embedded into the door.”                                                                                                   | “Strong, durable … widely installed in industrial, commercial … and upmarket residential construction.” | “Difficult to install, rekey and repair … not compatible with narrow doors.”                                         | ![Pasted image 20250624161958.png](Media/Pasted%20image%2020250624161958.png) |
| **Cylindrical / Deadbolt**  | **Deadbolt**: “A deadbolt … is a lock morticed into a wooden door … bolt is thrown into the door frame … more resistant to forced entry.” **Cylindrical**: common – installed through the door with a knob or lever. | **Deadbolt**: “Resistant to forced entry.” **Cylindrical**: “Easy to rekey … quick installation.”       | **Deadbolt**: “Double cylinder … can prevent exit in fire.” **Cylindrical**: “Weaker durability … prone to picking.” | ![Pasted image 20250624162234.png](Media/Pasted%20image%2020250624162234.png) |
| **Push Bar / Panic Bar**    | “Push bar … a long metal bar … When pushed, it releases the latch and allows the door to be opened.”                                                                                                                 | “Allows easy and quick exit in case of emergency. Mandated for emergency exits.”                        | —                                                                                                                    | ![Pasted image 20250624162414.png](Media/Pasted%20image%2020250624162414.png) |

### Fail-Safe vs Fail-Secure Concepts
|**Feature**|**Fail-Safe**|**Fail-Secure**|
|---|---|---|
|**Power Loss Behavior**|Unlocks when power is lost _(requires power to stay locked)_|Stays locked when power is lost _(requires power to unlock)_|
|**Use Case**|Life safety routes, emergency exits (e.g., main doors, fire exits)|High-security zones (e.g., server rooms, data centers)|
|**Security Priority**|Prioritizes **safety** (easy exit in emergencies)|Prioritizes **security** (prevents unauthorized entry)|
|**Energy Usage**|High — needs continuous power to stay locked|Low — only uses power to unlock briefly|
|**Egress During Failure**|Always allows exit from inside|Always allows exit from inside|
|**Example Hardware**|Electromagnetic locks (maglocks)|Electric strikes, electric deadbolts|
|**Typical Door Location**|Exterior/public doors|IT closets, financial archives, control rooms|

### Common Protocols & Standards
- Wiegand
	-  It mostly refers to the technology used in card readers and sensors.
	- In the 1970s, German engineer John R Wiegand discovered that wires made of cobalt, iron and vanadium alloy switch polarity when run through strong magnetic fields.
	- The wiring in the Wiegand card adds on to the security as it makes the systems harder to duplicate.
	- 26-bit is also the industry standard format of opening encoding in regards to the access control systems.
	- The noteworthy thing is that Wiegand swipe cards are difficult to erase by magnetic fields. They are further durable as compared to the key cards as they do not have microchips. This is the major reason behind then being reliable and easy choices for equipping systems especially for swipe cards.

- OSDP (Open Supervised Device Protocol)
	-  It is an open standard protocol that provides advanced security features and enhanced functionality compared to older protocols like Wiegand.
	- OSDP offers bi-directional and secure communication with encryption, while Wiegand is an older, one-way protocol with no encryption and known vulnerabilities. OSDP uses a two-wire system for data, while Wiegand uses more wires. OSDP also provides supervision to monitor communication.
	- OSDP Profiles:
		- Basic
			- These devices are designed to replace Wiegand protocols and offer the added advantage of bidirectional communication.
		- Secure
			- Secure devices that meet the Basic profile and can handle encrypted messages using Secure Channel are essential in ensuring the safety and privacy of communication.
		- Smart Card
			- These devices transfer structured data units necessary for smart card operations.
		- Biometric
			- To read and match biometric templates.

## References:
- https://www.3sixtyintegrated.com/blog/2024/01/03/access-control-systems/
- https://www.avigilon.com/blog/access-control-models
- https://www.extnoc.com/learn/computer-security/access-level
- https://smartisystems.com/building-solutions/wiegand-what-is-it-and-how-does-it-work-with-access-control/
- https://www.lenels2.com/en/news/insights/What_is_OSDP.html
