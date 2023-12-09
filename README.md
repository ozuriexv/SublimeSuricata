# Sublime Suricata

![Alt text](/showcase.png)

Basic Suricata syntax highlighter for Sublime Text (tested on Sublime Text 4).

Now built with a custom color scheme instead of just a highlighter based on existing color schemes.

Accounts for all of the following in Suricata-7.0.0rc1:
- Meta keywords
- IP keywords
- TCP keywords
- UDP keywords
- ICMP keywords
- Payload keywords
- Transformation keywords
- Prefiltering keywords
- Flow keywords
- HTTP keywords
- File keywords
- DNS keywords
- SSL/TLS keywords
- SSH keywords
- JA3 keywords
- Modbus keywords
- DCERPC keywords
- DHCP keywords
- DNP3 keywords
- ENIP/CIP keywords
- FTP/FTP-DATA keywords
- Kerberos keywords
- SMB keywords
- SNMP keywords
- Base64 keywords
- SIP keywords
- RFB keywords
- MQTT keywords
- IKE keywords
- HTTP2 keywords
- Quic keywords
- Xbits keywords
- Thresholding keywords
- IP reputation keywords
- App-layer-event

# Warning/Error highlighting
Experimental idea - this syntax highlighter will point out some warnings/errors (warnings being rule styling that does not conform with Emerging Threats styling, errors being bad logic).  Currently there are only 2 scenarios (as I said, experimental, if this is annoying it will be scrapped):
- WARNING: Double spaces, highlighted with yellow background
- ERROR: Double sticky buffer, highlighted with red background

![Alt text](/double_buffer.png)

# Getting it working
- Save the Suricata folder in your 'Packages' folder
  - Windows: 'C:\Users\\%user%\AppData\Roaming\Sublime Text 3\Packages'
  - Mac: $HOME/Library/Application Support/Sublime Text/Packages
  - Linux: $home/.config/sublime-text-3/Packages
- Open Sublime Text
- View > Syntax > Suricata
- Set your color scheme to 'Suricata'
