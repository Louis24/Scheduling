# Scheduling
Step 1:首先以第一时段的客流量作为原点，以此求的剩余时刻与其对应斜率
Step 2:根据斜率以及发车班次求的每时段的班次配数
Step 3:根据班次配数进而求得每时段的发车间隔
Step 4:根据给定运营时间段评判发车间隔的合理性不合理返回Step 3否则返回Step 5
Step 5: 输出发车时间表
![image](https://user-images.githubusercontent.com/18719360/131454979-9da1077c-f7b9-4cad-842a-b0b5dbeb253b.png)
![320线路](https://user-images.githubusercontent.com/18719360/131455014-2790beea-a086-4204-9d1d-3fdb0ab1a390.png)
![393线路](https://user-images.githubusercontent.com/18719360/131455019-8407e410-73c8-4b9f-84f3-f957c235f269.png)
