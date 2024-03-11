# teleoperations
Step 1: Learn how the gamepad work

 Connect USB adapter to PC

 Go to https://html5gamepad.com

 Check the INDEX of Gamepad. Here the INDEX is 0 (ZERO) in your case might be different so check the index

 The gamepad included supports two working modes. One is PC/PS3/Android mode and another is Xbox 360 mode

 [Note] To switch between PC/PS3/Android mode and the Xbox 360 mode, you can long-press the HOME button for about 7s. In Xbox mode, the left joystick is mapped to axes[0] and axes[1], right joystick is mapped to 
axes[2] and axes[3]. This mode is exactly what the NVIDIA examples use.We recommend you to set your gamepad to this mode when you use it. Otherwise, you need to modify the codes.

Step 2: Run the test gamepad

 Access JetBot by going to https://<jetbot_ip_address>:8888, navigate to ~/Notebooks/teleoperation

 Open teleoperation.ipynb file and following notebook.

 Modify the index as per the controller

Step 3: Connect gamepad controller to the robot motors

 Modify axes values if required, here we use axes[0] and axes[1] and try with axes[1] and axes[1] also. Modify the axes as per requirements

Step 4: Create and display image widgets

Step 5: Create camera instance

Step 6: Connect camera to image widgets

Step 7: Snapshots with gamepad buttons

After running this cell you can see the snapshot folder is created
[Note] You can change the controllers to change the button for the snapshots.Here controller.buttons[6] and controller.buttons[7] both B6 and B7 used to click snapshot
