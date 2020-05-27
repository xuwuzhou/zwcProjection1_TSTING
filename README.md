# zwcProjection1_TSTING
4.12测试报告 点云的畸变矫正代码可能出现了问题，轨迹漂移很大并且距离远远长于实际的路程

5.27报告 未进行测试 参照https://github.com/Jinqiang/demo_lidar 改写loam的建图模块代码

接下来的方向是修改视觉里程计，在viso2原本订阅image图像的基础上，将图像特征和三维点云匹配获得一个深度值，然后lm迭代收敛获得转移矩阵
