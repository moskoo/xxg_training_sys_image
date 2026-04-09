**镜像名称**：【西小瓜炼丹炉】全量微调训练(kohya_ss)/Lora训练(ai-toolkit)/千问中文打标(qwen-caption)/joy3英文打标(joycaption_webui)  
**版本**：v1.2.0  
**更新日期**：2026-03-31  
**适用场景**：AIGC模型全量微调、LoRA训练、中英文批量数据标注，<font style="color:rgb(36, 41, 47);">支持训练：Chroma\Flex.1\Flex.2\FLUX.1\FLUX.2\HiDream\Lumina2\OmniGen2\Qwen-lmage\Qwen-lmage-Edit\SD 1.5\SDXL\Z-lmage\Z-lmage Turbo\FLUX.1-Kontext-dev\Wan 2.1 \Wan 2.2</font>

**一、镜像核心工具介绍**  
本镜像集成了多种高效AI工具，覆盖模型训练全流程及数据标注需求，提供一站式解决方案，大幅简化环境部署与使用流程。主要工具包括：

**1. 全量微调/LoRA训练工具**

+ **kohya_ss**：
    - **视频教程**：http://

**2. LoRA训练工具**

+ **ai-toolkit**：
    - **视频教程**：http://

**3. 批量数据标注工具**

+ **qwen-caption（XXG千问中文批量打标工具）**：
    - **视频教程**：http://
+ **joycaption 3（英文批量打标工具）**：
    - **视频教程**：http://

**二、使用指南**

1. **使用镜像**：
    1. 仙宫云：[https://www.xiangongyun.com/image/detail/e2de596e-17cb-40d1-866b-c1c15fa8ca61?r=3BVV7A](https://www.xiangongyun.com/image/detail/e2de596e-17cb-40d1-866b-c1c15fa8ca61?r=3BVV7A)
2. **目录结构**：

```plain
root/
├── ai-toolkit/        # ai-toolkit LoRA训练工具目录
├── Desktop/           # 桌面
├── kohya_ss/          # kohya_ss 全量微调/LoRA训练工具目录
├── llava/             # joycaption 英文批量打标工具目录
├── miniconda3/        # conda目录
├── models/            # 模型存放目录
├── quick/,quick-1/..  # 快捷方式（勿动）
├── qwen-caption       # XXG千问中文批量打标工具目录
└── other...           # 云系统文件
```

**三、注意事项**

1. 训练大模型时，请确保磁盘空间充足（建议≥500GB）。
2. 修改配置前备份原始文件，避免误操作导致数据丢失。
3. 工具版本手动更新链接：
    - **kohya_ss**: [https://github.com/bmaltais/kohya_ss](https://github.com/bmaltais/kohya_ss)
    - **joycaption_webui**: [https://github.com/AdamShuo/joycaption_webui](https://github.com/AdamShuo/joycaption_webui)
    - **qwen-caption：**[https://github.com/moskoo/qwen-caption](https://github.com/moskoo/qwen-caption)
    - **ai-toolkit: **[https://github.com/ostris/ai-toolkit](https://github.com/ostris/ai-toolkit)

**四、联系与支持**  
如有问题或功能建议，请联系wechat：

[二维码]

**--- 版权声明 ---**  
本镜像仅用于合法学习与研究用途，禁止违法违规使用。工具开源协议详见各组件官方说明。

---



