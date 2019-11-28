# Trung Trinh - Blog for Smart Mirror Project

# Week 12 (Nov 26/28): 
# Presentation made
# Raspberry Pi 3 fully booted up
# Raspberry Pi 3 working with speaker

# Week 11 (Nov 19/21) 
# Case installation for speaker circuit 
# Speaker fully constructed and functional with speaker, amplifier and cases
# [Speaker fully finished](https://github.com/Trung28899/SmartMirror/blob/master/documentation/Speaker.jpg)
# Ordered Raspberry Pi 3 for the project to work with speaker
<img src="https://github.com/Trung28899/SmartMirror/blob/master/documentation/RaspberryPi.jpg" alt="Raspberry Pi" height="242" width="242">

# Week 10 (Nov 12/14): PCB power up
# Received full package of speaker circuit (PCB, electrical components, speaker hat)
# [IMAGE LINK](https://github.com/Trung28899/SmartMirror/blob/master/documentation/PCB%20with%20components.jpg)

# Soldered speaker circuit
# [Soldered Circuit Front](https://github.com/Trung28899/SmartMirror/blob/master/documentation/PCB%20soldered%201.jpg)
# [Soldered Circuit Back](https://github.com/Trung28899/SmartMirror/blob/master/documentation/PCB%20soldered%202.jpg)
# Speaker working with laptop and phone devices

# Week 9 Hardware (Nov. 5/7): PCB soldered
# Still unable to connect to Raspberry PI, Here are steps taken for setting up OS for PI:
# +, Step 1: Downloaded Raspbian Lite from  https://www.raspberrypi.org/downloads/raspbian/

# +, Step 2: Download and Install Bonjour Printer Service and Win32Disk (following the video: https://www.youtube.com/watch?v=xj3MPmJhAPU)

# +, Step 3: Using Win32Disk, Write Raspbian Lite image to Sd card using Win32Disk

# +, Step 4: Change the files as following in the root file
# -> Open config.txt: add dtoverlay=dwc2 at the end of the file
# -> Open cmdline.txt add modules-load=dwc2,g_ether at the end of the file
# -> Add file ssh  (Following https://www.youtube.com/watch?v=xj3MPmJhAPU )

# +, Step 5: Connect raspberry Pi zero to laptop
# -> Put micro sd card in Pi zero (tried with two sd card)
# -> Connect through usb cable
# -> In Device Manager should see other devices like minute 3:09 in this video https://www.youtube.com/watch?v=HSSpQDs4lfU
# => but I didn’t see it


# More details: 
# +, connect Pi without microSd card > see other device in device manager without green light on the Pi > not an usb cable problem
# +, connect Pi with microsd card > doesn’t see other device in device manager with green light on the Pi > Pi able to read microSd
# +, Loaded same way on 2 different microSd cards > same issue > not a memory card issue
# +, Got help from teamate who got Raspbery Pi zero set up and running > stil not able to connect Pi

# NEXT MOVE REGARDING CONNECTING TO RASPBERRY PI: 
# +, Order a new raspbery Pi zero and reinstall
# +, Ask for help from Mr.Kelly from next door lab

# ORDERED PCB BOARD AND COMPONENTS FROM AMAZON.CA COMING ON 14TH NOVEMBER
# [IMAGE LINK](https://github.com/Trung28899/SmartMirror/blob/master/documentation/Order.png)

# Week 8 Hardware (Oct. 29/31)
# Working on installing OS for Raspberry PI
# Wasn't able to set up OS for Raspberry PI
# Builded circuit on Breadboard

# Week 7(Oct 15/17): Breadboard and PCB designed
# [Breadboard Design Image](https://github.com/Trung28899/SmartMirror/blob/master/documentation/Final%20Design.png)
# [PCB Image](https://github.com/Trung28899/SmartMirror/blob/master/documentation/PCB%20back.jpg)
# [Sketch Image]
# [Fritzing File](https://github.com/Trung28899/SmartMirror/blob/master/documentation/Sketch.fzz)

# Week 5 (Oct. 1/3): Parts Ordered
# [Proof of Purchase Adapter, Speaker](https://github.com/Trung28899/SmartMirror/blob/master/documentation/Amplifier%20and%20Power%20Adapter.pdf)
# [Proof of Purchase Amplifier Module](https://github.com/Trung28899/SmartMirror/blob/master/documentation/Amplifier%20Board%20Module.pdf)

# Week 4 (Sept. 24/26): Budget Due
# [Budget](https://github.com/Trung28899/SmartMirror/blob/master/documentation/PartsForSmartMirror.xlsx)

# Week 3 (Sept 17/19): Schedule Due
# [Schedule](https://github.com/Trung28899/SmartMirror/blob/master/documentation/CENG317-schedule.mpp)

# Week 2 (Sept 10/12): Proposal Due
# [Proposal](https://github.com/Trung28899/SmartMirror/blob/master/documentation/CENG-317-Proposal-Official.xlsx)

# Week 1 (Sept 3/5): Project Selection
