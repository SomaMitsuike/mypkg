# ロボットシステム学　課題2 
ROS 

# 内容  
ロボットシステム学の講義で作成したコードを書き換えてcount_upで出力される値を3倍にして出力するthird.pyを作成した 

# 実演動画  
https://www.youtube.com/watch?v=WEmmnT3hbbA 
# インストール・実行方法  
    $ cd ~/catkin_ws/src  
    $ git clone https://github.com/SomaMitsuike/mypkg.git   
    $ cd catkin_ws  
    $ catkin_make 
    $ cd src/mypkg/scripts/   
    $ roscore & 
    $ rosrun mypkg count.py & 
    $ rosrun mypkg third.py & 
    $ rostopic echo /count_up    

別のタブで  
   
    $ cd catkin_ws/src/mypkg/scripts/ 
    $ rostopic echo /third  
# 参考  
https://www.youtube.com/watch?v=PL85Pw_zQH0&t=3481s

# ライセンス 
[BSD 3-Clause License](https://github.com/SomaMitsuike/mypkg/blob/main/COPYING)
