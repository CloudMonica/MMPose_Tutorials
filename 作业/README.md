### **题目：基于RTMPose的耳朵穴位关键点检测**

### **背景**：

根据中医的“倒置胎儿”学说，耳朵的穴位反映了人体全身脏器的健康，耳穴按摩可以缓解失眠多梦、内分泌失调等疾病。耳朵面积较小，但穴位密集，涉及耳舟、耳轮、三角窝、耳甲艇、对耳轮等三维轮廓，普通人难以精准定位耳朵穴位。

### **任务**

- 1.Labelme标注关键点检测数据集
- 2.划分训练集和测试集
- 3.Labelme标注转MS COCO格式
- 4.使用MMDetection算法库，训练RTMDet耳朵目标检测算法，提交测试集评估指标
- 5.使用MMPose算法库，训练RTMPose耳朵关键点检测算法，提交测试集评估指标
- 6.用自己耳朵的图像预测，将预测结果保存
- 7.用自己耳朵的视频预测，将预测结果保存

**【4-7任务完成提交】**  
提交测试集评估指标（不能低于baseline指标的50%）  
并使用训练的模型对自己的数据进行预测并保存呈现结果（可采用notebook或者输出图片和视频的形式呈现）。

**【参考提交方法和格式】**  
【提交链接】[issue 24 comment](https://github.com/open-mmlab/OpenMMLabCamp/issues/24#issuecomment-1425167107)  
【作业目录】[2.Basic_mmdet3.x_V2](https://github.com/chg0901/openmmlab-hong/tree/main/2.Basic_mmdet3.x_V2)

_PS：任务1,2,3，示例代码作者子豪兄已经提供_

**目标检测Baseline模型（RTMDet-tiny）**  
[![image](https://user-images.githubusercontent.com/8240984/242793955-378e8592-abed-4f6b-a955-531a0db6a3f6.png)](https://user-images.githubusercontent.com/8240984/242793955-378e8592-abed-4f6b-a955-531a0db6a3f6.png)

**关键点检测Baseline模型（RTMPose-s）**  
[![image](https://user-images.githubusercontent.com/8240984/242793993-2af4dd12-db79-4b3f-b8a4-b75607855825.png)](https://user-images.githubusercontent.com/8240984/242793993-2af4dd12-db79-4b3f-b8a4-b75607855825.png)

### **数据集**

耳朵穴位关键点检测数据集，MS COCO格式，划分好了训练集和测试集，并写好了样例config配置文件  
链接: [https://pan.baidu.com/s/1swTLpArj7XEDXW4d0lo7Mg](https://pan.baidu.com/s/1swTLpArj7XEDXW4d0lo7Mg) 提取码: 741p  
标注人：张子豪、田文博  
[![image](https://user-images.githubusercontent.com/8240984/242794021-82bc4ee2-ca64-4959-9461-9a12ba244b5e.png)](https://user-images.githubusercontent.com/8240984/242794021-82bc4ee2-ca64-4959-9461-9a12ba244b5e.png)