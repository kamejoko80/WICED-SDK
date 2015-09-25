
## Red Bear Duo

The Red Bear Duo contains a ST32F205 MCU and AP6212A WiFi+Bluetooth combo module. The MCU has 1MB Flash and 128KB RAM, running at 120MHz. The wireless combo module built with BCM43438 A1 chip that works at 2.4GHz in frequency.

![image](images/RBDuo.png)

## WICED SDK

To use the board with WICED SDK 3.3.1:

1. Download Broadcom WICED-SDK-3.3.1 from:

   - http://community.broadcom.com/docs/DOC-2312

2. Unzip WICED-SDK-3.3.1 to your local file-system

3. Download and copy the files in this add-on package to the WICED-SDK-3.3.1 you just unzip and replace the original files

##  RBLink (Programmer) 

![image](images/RBLink.png)

The programmer is based on STLink:

1. For Windows, go to ST official website to download and install the STLink driver:

   - http://www.st.com/web/en/catalog/tools/PF260219

2. No driver is required for OSX and Linux

3. Open the command line terminal and change the working directory to WICED-SDK-3.3.1>

4. Type in "make rbl.rgb-RB_Duo JTAG=RBLINK download run" and press the Enter on the keyboard to begin build the project that under the folder "WICED-SDK-3.3.1\apps\rbl\rgb". More details about make usage please refer to the Makefile which under "WICED-SDK-3.3.1\"

* Remember to short the JTMS D7 and JTCK D6 jumpers (as the photo shows) before burning firmware to the board.

* RBLink supports drag and drop programming, we will provide instructions for that soon.
