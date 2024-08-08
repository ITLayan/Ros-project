I used ROS online by( https://app.theconstruct.ai/login/) I went to My Rosjects, then I created new Rosjects ,then I chose the old copy (Noetic) after that, I clicked Run to open the online, I opened the shell window and code editor window.
Step 1 : I went to the source directory to install the package inside it 

<img width="467" alt="f1" src="https://github.com/user-attachments/assets/eb84f57b-90e5-4a85-be4f-44172f73401c">

Step 2: I installed the dependencies using this command (rosdep install --from-paths src --ignore-src -r -y), and I chose ROS copy (noetic distro). Then I built the package using the (catkin_make) command.

<img width="463" alt="f2" src="https://github.com/user-attachments/assets/3bb59070-17a0-498c-a911-88a8149a8665">

Step 3: Controlling the robot arm by joint_state_publisher, command( roslaunch robot_arm_pkg check_motors.launch),to open the window for controlling the robot arm.

<img width="481" alt="f3" src="https://github.com/user-attachments/assets/145e6510-b883-4a78-bf74-2ffcd813f49d">

Step 4: As you see here The simulation shows the robot arm and how you can move it! 

<img width="479" alt="f4" src="https://github.com/user-attachments/assets/34292ae4-17f3-42f2-94c8-012c23027d77">

<img width="474" alt="f5" src="https://github.com/user-attachments/assets/17d7122a-9148-4ae0-a309-2e496079c82a">

