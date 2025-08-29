# U3D_body
本仓库旨在研究通过单目摄像头生成3D骨骼点, 并驱动Unity3D模型, 在可交互的网页上展示。

## 技术路径
### 3D骨骼点
* RTMPose3D
* MotionBERT

### 通信(骨骼点模型->U3D)
* UDP/TCP Socket

### U3D
#### Mesh
免费Mesh下载网站: [mixamo](https://www.mixamo.com)获取fbx格式模型;

在Unity下方的Project中Asserts文件夹里新建Models路径, 将fbx文件复制进去;

<img width="1512" height="885" alt="image" src="https://github.com/user-attachments/assets/26bcadf8-5fd7-4134-bd31-0ace5671171b" width="100"/>

在Assert路径下新建C#脚本 `SimplePosePlayer.cs`
<img width="831" height="652" alt="image" src="https://github.com/user-attachments/assets/0227866b-d30e-446a-9905-47517fa15ed3" />


