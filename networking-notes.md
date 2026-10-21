# Networking Notes

## IP Address
What it is : Unique labels (within its network) assigned to every device connected to a network

Real example: Writing ipconfig you will get your private ip address that is 192.168.x.x, the range 192.168 is shared by a lot of networks 

## MAC Address
What it is : MAC address is the media access control that is placed by the manufacturer, its used to identify hardware devices on a LAN, it belongs to datalink layer 2 it doesnt change by itself when changing networks but it can be faked in a software which attackers use it's called MAC spoofing

Real example: Connecting to a public cafe network wont change the mac address, and you can check it by using the command ipconfig /all will show it called physical address

## Ports
What they are: Ports are numbers that tell the computer which program the data is for. If the ip address is the building the port is the room

Real example: When I have my browser and Spotify open at the same time, data for both arrives at my ip address. My laptop uses ports to know which data goes to which app. Websites usually use port 443

## The OSI Model
My memory trick: All People Seem To Need Data Processing

| # | Layer | What it does  | Real example |
|---|-------|------------------------|--------------|
| 7 | Application | What you interact with or the program you use |  Whatsapp, Chrome browser |
| 6 | Presentation | Translates, formatting the data and securing it so both sides understand it  |  Encryption |
| 5 | Session | It opens, manages, then terminates the connection |  Video call staying connected from beginning to end|
| 4 | Transport | Splits data into pieces and uses ports to deliver them to the right app | TCP and UDP |
| 3 | Network | Finding the best path for data to pass across different networks. |  IP address |
| 2 | Data Link | Moving data across your network from your device to router. |  MAC address |
| 1 | Physical | Transmits data over radio frequency for example. |  radio waves or ethernet cables |
