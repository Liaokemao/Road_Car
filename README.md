基于ROS1-Ubuntu20.04，vscode设计。
使用方法：
1.将road_vs文件夹放在主目录中
2.cd进入到road_vs工作空间下
3.执行catkin_make
4.若编译存在错误，证明缺少相关依赖，请确保ros相关依赖完整
5.编译成功后，执行source ./devel/setup.bash刷新工作空间
6.执行roslaunch base_control trytry.launch
7.另开终端窗口，rosnode list 查看当前节点状态
8.另开终端窗口,rostopic list 查看当前话题状态
9.另开终端窗口，rosparam list 查看参数服务器
10.另开终端窗口，rqt_graph 查看节点、话题关系图
