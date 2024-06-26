# ROS-Final-Project

這個專案是我們在ROS（機器人操作系統）課程中的實作練習，旨在深入了解和掌握ROS的基本概念、架構和應用。我們通過完成一系列任務，學習了如何使用ROS開發和測試機器人應用。

## 安裝與使用指南

按照以下步驟進行即可：

1. 下載.zip檔並解壓縮
2. 將整包資源放入此路徑：
   \\wsl.localhost\Ubuntu-20.04\home\user\catkin_ws\src
3. 開啟Ubuntu的命令行
4. cd至catkin_ws目錄：
   cd ~/catkin_ws
5. 執行catkin_make：
   catkin_make
6. 啟動Gazebo模擬環境：
   roslaunch final_project_description gazebo.launch
7. 在模擬環境中隨意增加障礙物
8. 啟動鍵盤控制節點：
   rosrun teleop_twist_keyboard teleop_twist_keyboard.py
9. 啟動RViz：
   roslaunch final_project_description display.launch
10. 在RViz中進行以下步驟：
    - Add -> By topic -> LaserScan -> OK -> Topic -> /scan

恭喜你，完成以上步驟就可以開始遊玩囉~
