# A-search-algorithm-A-star
A* search algorithm, finding path / graph traversal and path search algorithm
A*寻路算法， 用于遍历图，寻找最短路径

A* / A star search algorithm:
1. starting point and ending point
2. some obstacles scattered in the graph
3. distance function, calculate the distance from current status to the target point / (end point)
4. history recording, store the distance from the starting point (original point) to current status
5. distance table, store history distance and how much distance to the target
6. update your distance table every time when exploring to new points
7. converge to find the best route / path

A星寻路算法：
1. 设置起始点、目标点
2. 可能图中会有一些障碍物，要绕过去
3. 计算距离的函数，计算当前位置距离目标点的距离
4. 历史记录，记录起始点到当前位置的距离，——已经走了多远
5. 距离表，记录图上面的点，到目标点的距离
6. 当探索新的点的时候，更新表的数据
7. 收敛到最优路径

