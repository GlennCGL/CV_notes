# CV_notes

## Performance & Model ZOO


|          Network          | Input Size |      Loss & Label       | total vis acc | total pos acc |   macc   |  param  |                           model                             |
| :-----------------------: | :--------: | :---------------------: | :-----------: | :-----------: | :------: | :-----: |:----------------------------------------------------------: |
|        ResNet-50 sb       |   96*96    |     SCE & radius 2      |     80.6      |     78.1      |   972.7  |  129.8  |[Link](ftp://10.10.17.21/lustre/caoguoliang/workspace/Learn_201905/3D/pytorch-keypoint/experiments/Model_ZOO/res50_sb_9696/) |
|       ResNet-50 FPN       |   96*96    | SCE & radius 0, 0, 1, 2 |     80.8      |     78.3      |  1326.0  |  117.7  |[Link](ftp://10.10.17.21/lustre/caoguoliang/workspace/Learn_201905/3D/pytorch-keypoint/experiments/Model_ZOO/res50_fpn_9696) |
|        ResNet-18 sb       |   96*96    |     SCE & radius 2      |     80.6      |     77.2      |   519.0  |   58.7  |[Link](ftp://10.10.17.21/lustre/caoguoliang/workspace/Learn_201905/3D/pytorch-keypoint/experiments/Model_ZOO/res18_sb_9696/) |
|       ResNet-18 FPN       |   96*96    | SCE & radius 0, 0, 1, 2 |     80.7      |     77.6      |   848.6  |   55.8  |[Link](ftp://10.10.17.21/lustre/caoguoliang/workspace/Learn_201905/3D/pytorch-keypoint/experiments/Model_ZOO/res18_fpn_9696/) |
|          Dnet4 sb         |   96*96    |     SCE & radius 2      |     75.8      |     74.3      |   828.1  |   14.7  |[Link](ftp://10.10.17.21/lustre/caoguoliang/workspace/Learn_201905/3D/pytorch-keypoint/experiments/Model_ZOO/dnet4_sb_9696/) |
|         Dnet4 FPN         |   96*96    | SCE & radius 0, 0, 1, 2 |     80.2      |     76.4      |  2130.9  |   13.3  |[Link](ftp://10.10.17.21/lustre/caoguoliang/workspace/Learn_201905/3D/pytorch-keypoint/experiments/Model_ZOO/dnet4_fpn_9696/) |
|        ResNet-50 sb       |  256*256   |     SCE & radius 2      |     80.5      |     78.6      |  6917.2  |  129.8  |[Link](ftp://10.10.17.21/lustre/caoguoliang/workspace/Learn_201905/3D/pytorch-keypoint/experiments/Model_ZOO/res50_sb_256256/) |
|       ResNet-50 FPN       |  256*256   | SCE & radius 0, 0, 1, 2 |     80.3      |     79.4      |  9429.3  |  117.7  |[Link](ftp://10.10.17.21/lustre/caoguoliang/workspace/Learn_201905/3D/pytorch-keypoint/experiments/Model_ZOO/res50_fpn_256256/) |
|        ResNet-18 sb       |  256*256   |     SCE & radius 2      |     78.9      |     78.6      |  3690.4  |   58.7  |[Link](ftp://10.10.17.21/lustre/caoguoliang/workspace/Learn_201905/3D/pytorch-keypoint/experiments/Model_ZOO/res18_sb_256256/) |
|       ResNet-18 FPN       |  256*256   | SCE & radius 0, 0, 1, 2 |     ----      |     ----      |  ------  |  -----  |[Link](ftp://10.10.17.21/lustre/caoguoliang/workspace/Learn_201905/3D/pytorch-keypoint/experiments/Model_ZOO/res18_fpn_256256/) |
