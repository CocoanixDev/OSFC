# Open Source Fan Controller

# What is it?
OSFC is a Arduino Based Device Designed To Test And Validate PWM ARGB Fans.

# What Do I Need To Assemble It
You will need:
• 1x Breadboard
• 1x Arduino Uno Or Nano
• 1x PWM Fan Header
• 1x aRGB 3-Pin Header
• 1x LM7805 5V Regulator
• 1x DC Jack Female Connector
• Some Wires
• A Computer

Schematics You Can Find In This Repo.               

# How does it operate?
OSFC Uses Special Firmware "OSFC-OS" That Allows Communication With Controller Using Arduino's Serial Monitor Or Recomended OSFC Companion App For Windows. (OSFC Is Not Compatible With Mac Or Linux, If You Are On These Platforms You Will Need To Use Arduino IDE)

OSFC-OS Sends And Recieves A PWM Signal That Allows You To Control And See The Speed Of Your Fan. Also aRGB Signal Is Fully Customizable From The App! You Can Set Individual Diodes And Validate The LEDs Properties.

The LM7805 Steps Down The Voltage From 12v to 5v For Arduino And ARGB Header Power Needs. The Clean 12v Goes Straight To The PWM Header.
