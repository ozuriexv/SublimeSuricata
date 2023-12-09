# Sublime Suricata

![Alt text](/showcase.png)

Basic Suricata syntax highlighter for Sublime Text (tested on Sublime Text 4).

Now built with a custom color scheme instead of just a highlighter based on existing color schemes.

Includes all features from the Suricata-7.0.0rc1 branch.

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
