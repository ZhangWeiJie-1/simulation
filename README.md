# simulation
<img width="1307" height="1004" alt="截图 2026-07-25 18-41-01" src="https://github.com/user-attachments/assets/f4bd6af6-16eb-402e-acb5-e28086735575" />
imu标红，要用到robot_state_publisher;joint_state_publisher
<img width="1307" height="1004" alt="截图 2026-07-25 18-59-52" src="https://github.com/user-attachments/assets/b7d8ecb8-196f-4abe-93bd-5e8311cf38ce" />
launch之所以能启动，是因为把命令行集成了
<img width="1307" height="1352" alt="截图 2026-07-25 22-07-34" src="https://github.com/user-attachments/assets/c1773ed6-623d-41f0-b259-1861ff22b413" />
必须先humble@humble-VirtualBox:~/chapt6/chapt6_ws$ xacro /home/humble/chapt6/chapt6_ws/install/fishbot_description/share/fishbot_description/urdf/fishbot/fishbot.urdf.xacro
再humble@humble-VirtualBox:~/chapt6/chapt6_ws$ ros2 launch fishbot_description display_robot.launch.py model:=/home/humble/chapt6/chapt6_ws/install/fishbot_description/share/fishbot_description/urdf/fishbot/fishbot.urdf.xacro
