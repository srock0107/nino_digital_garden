---
{"dg-publish":true,"permalink":"//note/","tags":"gardenEntry","dgHomeLink":true,"dgPassFrontmatter":false}
---

# 第一章 系统仿真概述

## 系统包含的要素

-   **实体**：组成系统的具体对象或单元。
    

-   **属性**：实体的特性。
    

-   **活动**：指对象随着时间的推移而发生的状态的变化
    

-   **环境**：表示系统所处的界面状况，包括影响系统但不受系
    

## 系统状态

存在于系统内部的实体、属性、活动组成的整体。系统状态的变化构成**系统的动态****。**

## 系统的类型

1.  **静态** **系统**：相对不变的系统。
    

**动态**  **系统**：系统状态随时变化的系统

2.  **确定** **系统**：系统的状态和参数确定（但可能变化）的系统。
    

**随机** **系 统**：系统的状态和参数随机变化的系统

3.  **连续** **系统**：系统的状态随时间连续变化的系统。如运动系统中位置和速度的改变。
    
       **离散** **系统**：系统的状态随时间离散变化的系统。如生产系统中的产品、人员、设备的数量
    

**混合** **系统**：系统中既有连续成分，又包含离散成分。

## 系统分类

1.  **线性** **系统与** **非线性** **系统**
    

2.  **时不变**  **系统和****时变****系统**
    

3.  **线性时不变****系统**
    

## 系统研究的类型

**系统分析；系统设计；系统预测**

## 系统研究方法

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=ZjhjMGEwYWRmMzFlYzZjNzU4Y2M3ZDYyYzZlNmVjOGRfaWpkNWVzT0lMbFhDaktEM0NuNWVuMENXaGw0Q0wybTBfVG9rZW46Ym94Y25zclkwWHh6Zk92WDlrclpzWmZlUVNoXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

## 系统模型

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=NmY1MDY1MDI1Mzc4NWVlYzIyMTU0Nzc1NTlmY2ZjZDVfd29XT0xPbjJtY040Mzd3ZGxiNWdvQkd0bnkwdWJ0V01fVG9rZW46Ym94Y25VUVh4ek9nNUR0elRTTGZ0WldKUmZiXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

## 系统模型分类

1.  **物理模型：**根据实际系统，利用实物建立起来的模型。与实际系统具有相似的物理性质。
    

2.  **数学模型：**抽象数学方程描述系统内部物理变量之间的关系模型。与实际系统具有相似的数学描述和关系。
    

3.  **混合-半实物模型**
    

## 仿真的概念

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=MTk4NzNhZjJkZGQ5ZDBjMTZmYmVmMjg4M2ZkZGI0NzBfaWdrVXpyQWVUa2ZtcVZZUzJONmZvTlRFNlZIeUZnUHVfVG9rZW46Ym94Y25HRDhOd00zUUI5bVppS1RGeHFFMFFjXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

## 仿真的理论基础-相似理论

建立在相似理论、控制理论和计算机技术的基础上

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=NWRmYmU3MGQwMGU3ZWI1YzEwNDk2ZGMwMTVmNTQwOGRfYXdqYnRwazJoalNuWlFpdU9ETU5CSDExa3d0VTlXQ0xfVG9rZW46Ym94Y25Gb0NMSTllV1pLb3lOTW9PcTF0c3NOXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=MzliNzUzMzE1OWYzNDdlZmY0OGUzNmI0MmVmYmM2MjBfMWZjMG5IZGpyS2p3S0ZDSW1TOGpMZEhVdXMxRmhWMFNfVG9rZW46Ym94Y25PODJSRjViQWJkclo4OHFFUlVqQVJjXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

## 仿真系统

是指实现仿真任务的软件和设备。包括仿真设备，参与仿真操作的人员、部分被仿真系统组件。

## 仿真技术

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=Nzg5MjhhY2E4YzNhYTQ2NWIyNTg3MGU1OWQ5MjdkMWJfbVZ2NWVvOExkYjYxckpHUDI2MHZ0ZTN6ZGZHT09UNThfVG9rZW46Ym94Y25DR0lkcHRhOW41UnFTRkN5dXFoa2FkXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

## 仿真的意义和必要性

1.  **优化设计**：在系统实现之前通过改变仿真模型结构和调整参数优化系统设计对系统（或部分系统）进行性能评价
    

2.  **节约实验成本**：系统模型成本低于实际系统，且模型可重复使用，输入和环境条件可设置。
    

3.  **故障诊断**：通过仿真故障重演，判断产生原因。
    

4.  **避免危险**
    

5.  **假设预测系统性能**：通过仿真条件设置，预测系统特性和外部作用对系统的影响。
    

6.  **训练操作人员**
    

7.  **为管理和技术决策提供依据**
    

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=OThjZDNhMTk1NWVjZDYyNDlhOGM5YjZkNTY4NmVkNjdfeXFiNDN6TDJrQzZLMkZJM2RHaXVpWDQyTmZ2SHRBWmFfVG9rZW46Ym94Y243b2I1WVZrQTg5WmFqcTZ1bW5NVkxkXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=MzJlN2NmYzQ2OWI0YmFkYmViMjZkMjhlOWYzYTMwMDJfaXMybVZLSTNac3h3RHFiQ0U1S1VrQUtmczhieXFwR2hfVG9rZW46Ym94Y241Mk45YVhOTGJmYkxFNnZFcThFNkZnXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

仿真技术是几乎所有高科技产业的关键技术

## 系统仿真分类

**系统仿真定义：**以系统的 数学模型 为基础，采用数学模型代替实际系统，以 计算机 为主要工具，对系统进行试验和研究的一种方法。

**物理仿真**

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=ZDU5MjQxMGNlOTU3Nzk0N2EyYmI0OTczMWUwOWM3MzhfUGExWFBhbDN3ZEFNWllGZGplb2E0VmNtbW5PU2lFdWZfVG9rZW46Ym94Y25ta2hwelQ3TFZYY0ljVXVEdFlnbGpoXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

**数学仿真**

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=YjMxMGExYzUwODRiOTk4ZTg1YzAyNmQxMjI5NGU4YmVfVk1FM1FBdm5xa0RzNEd6ZGdjTjNJQ3FHbDRwN0RXNjVfVG9rZW46Ym94Y25IYVdYSFdJS0RMbm1lYUZHcXprYXVmXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

**人在回路中仿真**

  

  

  

  

**半实物仿真**

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=ODNiNTFlMTYwZjcwMzBjMzNlZWM2ODgwNGRiMDY3NDhfY2lTZVQxS216OU9OUEpWSmxUcmpuWlg4UHBYZnBXVk1fVG9rZW46Ym94Y25PVUFHejI1VllRSElyeEtGZEtpMUZkXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=YTlhMThmYTFmZWU3MWY0YjVjMTU5MGYyYTBhMGRkZTNfZ1FWS3d0cTh0aDQ0OUZDR2xuaUZMcjllMm5NQWgzaHNfVG9rZW46Ym94Y24yN21PaVZMTE1YYWtiNVZDQjJ0a0NoXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

## 系统仿真的分类

**按照系统模型与实际系统的时间关系划分：**实时仿真、超实时仿真、慢实时仿真

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=NGU2YzQwOTMyNzI5NjkyYmVmNmYwNGFlYjYzM2U1MmZfT0JjM1hYYm41NE1PVHlKc1RjNkxrZTJnb3ZEWFRpUzFfVG9rZW46Ym94Y25rNDNFSmthU3NWS1BUNURnWEUwUXliXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

**按照系统随时间变化的状态划分：**连续系统仿真、离散事件仿真

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=MzNkMDkxM2Y4MmZmNGZkZDc4MTcyZjMzYjMzZGUwYTNfQU01RGxIc3BRSUFFcTJObzVhWEJ4MExHVWY3VkVucnZfVG9rZW46Ym94Y25xbWt1dHpKNnVyUTdSVHBXckpwUTFnXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

## 系统仿真的特征-要素与基本活动

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=YTQ2ZjVmYTE1ZGFkNjdlYTQ0MjNjZTQwODc4YmRlMjBfV3dOQjRzN0NyTUhHa2I0VXpoMVNFZmRKeVZFNGhIQTlfVG9rZW46Ym94Y25SZ0ZZemN6U1d4UVplZG9KalR0cUdiXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

基于系统状态和特征建立数学模型，功能仿真关注信号信号级关注幅度，或者相位

仿真是基于模型的实验，实验要运行的平台载体：通用计算机或者嵌入式或者运算平台

## 系统仿真的过程

  **系统定义**[确定仿真要求和仿真系统的边界与约束条件]**、数学建模**[效率、精度、资源的平衡]**、仿真建模、模型输入**[将仿真模型输入计算机，设定实验（仿真模型运行）条件并进行记录]**、模型实验、结果分析**[根据实验要求对实验结果进行分析，根据分析结果修正系统设计、数学模型和仿真模型，并进行新的仿真实验。]

## 系统仿真的特点

**优点**

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=NmYyNzZkYWRmY2VlNzRjMzYzNmQ0YzY5YWQ4NGRjMjlfalViWEJRMFpkM2RTbHlUVnZsaXNTcWVJTFVnQm5DSUhfVG9rZW46Ym94Y25VYXFmcUFDY2xUWTBwYTdaSkpENzRiXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

**缺点**

  

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=ZWE4M2M5MzM1MzQ5YjdmMTE5YWMzYjgxMTc5NGE1MjFfNnAzRENnZWxQbFJIN2owZHViTnBNVHh0cG5VZm1DRFVfVG9rZW46Ym94Y25QdHliOTlMRURiclltQ2ZnOVQ2TUVlXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

## 系统仿真应用领域和层次

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=NTI2NDY5NzM0ZDdmMDAyNTUxMjU2OTMxOWU1YWY4OWVfcGdsQTVzUnBYa1YxOXdDZDNDRGtFRTJoZlVVNXRONExfVG9rZW46Ym94Y25LZ3FkajJMN0JHMHVubW0wUkFwUjJ3XzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=ZjI2YjA4NDY3MWUzZmVlNjAwZWE2ZDk5YmRlNDA3YjZfdldzZkhvTG01UUpkMjdlbUQwSjVhS3NZdTdETVU5bHJfVG9rZW46Ym94Y253YTBnRzJHMDFXQmxYTHNTbDBJUEVmXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

## 系统仿真技术的发展主要方向

1.  面向对象的仿真方法
    

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=ZTY3MDNhM2M4NGQxYzVkM2M5MTZjODIzZTNjNDcxNWNfcjNtUWNvNUJreEM5azZzdWlucGdKeHVsY1NpQ3lCd3pfVG9rZW46Ym94Y25TWmxxbnlSY2QxM2hFOEZiUjNaV2o4XzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

2.  分布式交互仿真（DIS)
    

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=NGYyMzBkNWU4NDQ1NGYzODIyMzg4ZjA0YTU1NjY4ZWNfc2JVd2NBazlQS2dQWjc4WGRaMkNkZVJLbWFGRkt1eE9fVG9rZW46Ym94Y25SS2Y4cXBZSkJpczZmUUZDT3o0TzZjXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=ZDhlNWZiNjc1MTY5YjNhYjJkMTBiZDE0YjVjOGE5ZDVfZmlhd1dSNnFqemVTYkNINjlhQm1lVFFGQUQ4bW92NTVfVG9rZW46Ym94Y25NSTF3aHg4dnFkaGpWODRlQ0F2dVRnXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

3.  定性仿真
    

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=MjlkMTgzMjBlNzAwOWI4MWJlMzc3Nzg1YmEyOTk2NzFfN3RocWFqTW5lSXVqUDd5S2wzcTlWcWdvbmtGZjA0ZkZfVG9rZW46Ym94Y25yV3Y3ZnFqc2tCbnNlcEJkN25TWVZmXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

4.  可视化、多媒体和虚拟现实仿真
    

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=Mjg2MGRlODQzY2UxNzAzMjZhODQzYjdkY2QxYmI0ZWFfRVlDNU1uR0dyaXEwc2xkS3BveFVZN3FlbUJydDBla1JfVG9rZW46Ym94Y25jQkd5NzJKY2szZURXSVpaUktCVG9nXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)

![](https://uestc.feishu.cn/space/api/box/stream/download/asynccode/?code=YWI5NWIxMGMxODY1ODZiMGE4YjZhOWM5ZDFiYjU1ZjZfNnNBNHVzQkZQdzdXNDhjV09FeEo2TGxHVFVtcnhtR25fVG9rZW46Ym94Y25BZEFkdWtBMURHS2hsZmtiNFJFUmZoXzE2NjM3NzUxOTk6MTY2Mzc3ODc5OV9WNA)