# Wireless-Attacks

## What is a Wireless Attack?
**Definition**:
A wireless attack targets Wi-Fi, Bluetooth, NFC, RFID, or other wireless communication technologies to steal data, gain unauthorized access, disrupt services, or compromise devices.
Wireless networks are more vulnerable than wired networks because signals are broadcast in open air, making interception easier.

## Key Idea:
If it’s over the air, it’s open to interception unless encrypted & secured.

## Wireless Attack Categories (Deep Explanation)

**Category**	**Description**	**Example Attacks**	**Impact**	**Mitigation**

 ### Eavesdropping / Packet Sniffing	
**Description** Capturing unencrypted wireless traffic.
**Example Attacks** Wireshark sniffing open Wi-Fi packets.
**Impact** Data theft, credential capture.	
**Mitigation**Use WPA3/WPA2 encryption, disable open Wi-Fi.

### Rogue Access Point (Rogue AP)
**Description** An unauthorized AP set up to mimic a real network.
**Example Attacks** Fake Wi-Fi at a coffee shop.	
**Impact** Credential theft, MITM attacks.
**Mitigation**Monitor for rogue APs, wireless intrusion detection systems (WIDS).

### Evil Twin
**Description** A type of rogue AP that clones SSID & appearance of a legitimate network.
**Example Attacks** “Free_Airport_WiFi” mimicking the real airport Wi-Fi.
**Impact**Data interception, phishing.	
**Mitigation**Use VPN, verify SSID, mutual authentication (802.1X).

### Jamming / DoS	
**Description** Overloading wireless frequencies to disrupt communication.	
**Example Attacks** RF jammer blocking 2.4GHz Wi-Fi.
**Impact**Service outage.
**Mitigation**Use directional antennas, change channels, detect source.

### Deauthentication Attack
**Description** Sending forged deauth frames to disconnect clients from Wi-Fi.
**Example Attacks** Kicking devices off WPA2 network to force handshake capture.	
**Impact**Session hijacking, credential cracking.
WPA3 Protected Management Frames (PMF).

### Replay Attack
**Description** Capturing wireless data packets and replaying them to trick devices.	
**Example Attacks** Resending captured RFID access card signals.	
**Impact**Unauthorized access.	
**Mitigation**Use nonces/timestamps, encryption.

### Bluejacking
**Description** Sending unsolicited messages over Bluetooth.
**Example Attacks** Spam messages to nearby phones.
**Impact**Annoyance, phishing.	
**Mitigation**Disable Bluetooth when not in use, set to hidden.

 ### Bluesnarfing
**Description** Unauthorized access to Bluetooth-enabled device.	
**Example Attacks** Stealing contacts/files via Bluetooth.	
**Impact**Data theft.
**Mitigation**Use Bluetooth security mode, pair only with trusted devices.

### RFID/NFC Skimming
**Description** Reading RFID/NFC signals without permission.	
**Example Attacks** Skimming contactless credit cards.
**Impact**Financial theft.	
RFID-blocking wallets, strong encryption.

### War Driving	
**Description** Searching for open/weak Wi-Fi while driving around.	
**Example Attacks** Mapping Wi-Fi hotspots with GPS.
**Impact**Finding networks to exploit.
**Mitigation**Disable SSID broadcast, use WPA3/WPA2.

### Password Cracking (Wireless)
**Description** Capturing WPA2 handshake & brute-forcing passphrase.	
**Example Attacks** Aircrack-ng on captured handshake.	
**Impact**Network breach.
**Mitigation**Strong complex passwords, WPA3.

## Security+ Key Points
Wireless is vulnerable because anyone in range can attempt to connect or capture traffic.

Encryption & authentication are the main defenses.

802.1X, WPA3, and VPNs are critical in modern defenses.
