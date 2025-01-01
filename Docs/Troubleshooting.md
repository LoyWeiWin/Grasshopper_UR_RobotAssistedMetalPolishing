# Troubleshooting Guide

## Common Issues and Solutions

### 1. Issues Related to Plugins
- **Problem:** Plugins cannot be installed on the workstation.
- **Solution:**
  1. Plugins downloaded from FoodForRhino need to be "unblocked."
  2. Instructions:
     - Right-click on the zip file (downloaded from FoodForRhino).  
       <img src="https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/Assets/Images/IMG_PluginIssue_HowTo.png" alt="Access File Properties" title="Access File Properties" width="400">  
     - Ensure the "Unblock" checkbox is ticked in the file properties.  
       <img src="https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/Assets/Images/IMG_PluginIssue_HowTo_01.png" alt="Unblock File" title="Unblock File" width="400">

### 2. Issues Related to RobotMesh
- **Problem:** The robot input is "missing."
- **Solution:**
  - Install the robot configuration file (provided via the appropriate link) into your workstation's document folder.
  - Restart Rhino and Grasshopper to apply the changes.

### 3. Issues Related to the Communication Channel
- **Problem:** Cannot communicate or send commands to the physical robot.
- **Solution:**
  - Verify that the physical robot and workstation are connected to the same network. Use the "ping" command to test the connection (refer to documentation link X).
- **Alternative Solution:**
  - Connect the physical robot and workstation directly using an Ethernet cable. Then, establish a static IP address through the robot's teach pendant.
