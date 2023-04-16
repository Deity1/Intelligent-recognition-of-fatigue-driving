# 题目名称
 基于端云算力协同的疲劳驾驶智能识别  
# 作品需求
 利用端侧算力单元与云上算力中心协同，让车能够更准确更迅速的检测疲劳/分神驾驶，及时提醒司机，减少交通事故。  
 结合与协同端云算力，研发端云算力协同应用系统，让疲劳/分神检测更迅速  。
**提交形式：** **PPT 作品方案介绍+作品代码，PPT 方案中提供相关的举证演示视频及截图等材料  **

# 开发环境
赛题偏向于硬件开发：所以可能会比较的难，大家一起克服一下哈（基本上都是没有基础），涉及到的内容主要有环境搭建，代码的编写和调试，烧录，测试（部分是可以直接从华为云的gitee上直接clone用的）等等
**OpenHarmony开发板，摄像头，小车**（不知道学校有没有相应设施）
MindStudio
开发语言：python
大部分学习资料可以在华为云开发平台当中找到（可以稍微去了解一下大概的一些流程）。
[环境搭建视频](https://www.bilibili.com/video/BV1Mq4y1a79b/?spm_id_from=333.880.my_history.page.click)
[可参考博客](https://blog.csdn.net/weixin_42800966/article/details/122587832?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-0-122587832-blog-109120924.235^v29^pc_relevant_default_base&spm=1001.2101.3001.4242.1&utm_relevant_index=3)
[华为官方环境搭建视频](https://connect.huaweicloud.com/courses/learn/course-v1:HuaweiX+CBUCNXA023+Self-paced/about)

# 题目思考
[什么是算力网络](https://info.support.huawei.com/info-finder/encyclopedia/zh/%E7%AE%97%E5%8A%9B%E7%BD%91%E7%BB%9C.html)
端侧算力，指的是终端，即PC、手机、智慧电视，甚至是家庭的机顶盒、智能水电表等一切具备联网和计算能力的设备。物联网时代，将会有海量终端接入到网络中，汇集这些社会闲散设备的存量算力，就是算力共享。也就是从这个意义上来说，算力是泛在的。
算力网络的核心思想是通过新型网络技术将地理分布的算力中心节点连接起来，**动态实时感知算力资源状态，进而统筹分配和调度计算任务，传输数据，构成全局范围内感知、分配、调度算力的网络（核心难题）**，在此基础上汇聚和共享算力、数据、应用资源。
疲劳驾驶智能识别 ：

1. 可以通过人脸识别模块，根据记录的视频信息，根据**视频片段**的人物反应出来的一些特征来做出一个精神状态指标的得分（多分类），如果得分低于标准值则判断为疲劳驾驶（要去找到疲劳的一些特征，如:打哈欠之类的）**核心思考的方向**
2. 根据车辆的行驶情况来做出判断，车辆出现异常的左右浮动（驾驶员无法集中注意力控制方向盘...）
# 队伍地址
[加入队伍](https://competition.huaweicloud.com/information/1000041855/myteam)：队名：菜菜捞捞
