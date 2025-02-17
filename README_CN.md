# CodeFuse中文索引

<p align="center">
  <img src="assets/LOGO.png" width="50%" />
</p>


<div align="center">

[ **English** ](./README.md)|[ **HuggingFace** ](https://huggingface.co/codefuse-ai) | [ **魔搭社区** ](https://modelscope.cn/organization/codefuse-ai) | [ **WiseModel** ](https://www.wisemodel.cn/organization/codefuse-ai) | [ **产品主页** ](https://codefuse.alipay.com) 

</div>

## 关于本仓库

本仓库索引了CodeFuse项目的关键仓库、模型和演示例子. 

## 关于CodeFuse
CodeFuse的使命是开发专门设计用于支持整个软件开发生命周期的大型代码语言模型（Code LLMs），涵盖设计、需求、编码、测试、部署、运维等关键阶段。
我们致力于打造创新的解决方案，让软件开发者们在研发的过程中如丝般顺滑。下面是CodeFuse的整个框架。
<p align="center">
  <img src="https://github.com/codefuse-ai/.github/assets/82250814/9c8cd9f3-b1ca-43a1-9b0f-8f612b06753e" width="90%" />
</p>
<br/>

## CodeFuse仓库列表

我们按照上图软件生命周期的划分对仓库进行了组织. 
| 生命周期阶段               | 仓库名 | 仓库简介 | 
|:------------------------:|:-----------------:|:-------:|
| 项目Copilot     |    NA             |     NA  | 
| 数据Copilot        |[MFTCoder](https://github.com/codefuse-ai/MFTCoder) | CodeFuse独有的指令微调框架 |
|                     |[FastTransformer4CodeFuse](https://github.com/codefuse-ai/FasterTransformer4CodeFuse) | 推理引擎| 
|                     |[CodeFuse-Eval](https://github.com/codefuse-ai/codefuse-evaluation)|代码评估框架|   
| 测试和构建Copilot  |[TestAgent](https://github.com/codefuse-ai/Test-Agent) | TestGPT示例前端  |  
| 运维Copilot         |[DevOps-Eval](https://github.com/codefuse-ai/codefuse-devops-eval)|DevOps评测集和框架 |   
|                     |[DevOps-Model](https://github.com/codefuse-ai/CodeFuse-DevOps-Model) |DevOps模型列表介绍 |   
| 数据Copilot        |CodeFuse-Query (coming soon)| 程序语义分析引擎 | 
| 其他模块   |[ChatBot](https://github.com/codefuse-ai/codefuse-chatbot) |通用chatbot前端 | 
|                     |[CoCA](https://github.com/codefuse-ai/Collinear-Constrained-Attention)|共线约束注意力算法 | 
|                     |[Awesine-Code-LLM](https://github.com/codefuse-ai/Awesome-Code-LLM)|代码大模型survey主页 | 
|                     |你正在看的仓库 | CodeFuse通用介绍和索引 | 

## CodeFuse已发布模型索引

| ModelName               | Short Description | Modele Linls | 
|:------------------------:|:-----------------:|:-----------------:|
| CodeFuse-13B     | CodeFuse从0训练模型 | [HF](https://huggingface.co/codefuse-ai/CodeFuse-13B) ; [MS](https://modelscope.cn/models/codefuse-ai/CodeFuse-13B/summary)  | 
| CodeFuse-CodeLLaMA-34B    | 基于CodeLLaMA-34B微调的模型  | [HF](https://huggingface.co/codefuse-ai/CodeFuse-CodeLlama-34B) ; [MS](https://modelscope.cn/models/codefuse-ai/CodeFuse-CodeLlama-34B/summary)  | 
| ** CodeFuse-CodeLLaMA-34B-4bits |  34B模型的4bits量化版 |[HF](CodeFuse-CodeLlama-34B-4bits) ; [MS](https://modelscope.cn/models/codefuse-ai/CodeFuse-CodeLlama-34B-4bits/summary)  | 
| CodeFuse-StarCoder-15B    | 基于StarCoder-15B微调的模型 | [HF](https://huggingface.co/codefuse-ai/CodeFuse-StarCoder-15B) ; [MS](https://modelscope.cn/models/codefuse-ai/CodeFuse-StarCoder-15B/summary)  | 
| CodeFuse-Qwen-14B    | 基于Qwen-14B微调的模型    | [HF](https://huggingface.co/codefuse-ai/CodeFuse-QWen-14B) ; [MS](https://modelscope.cn/models/codefuse-ai/CodeFuse-QWen-14B/summary)  | 
| CodeFuse-CodeGeeX2-6B    | 基于CodeGeeX2-6B微调的模型           | [HF](https://huggingface.co/codefuse-ai/CodeFuse-CodeGeeX2-6B) ; [MS](https://modelscope.cn/models/codefuse-ai/CodeFuse-CodeGeeX2-6B/summary)  | 
| CodeFuse-DevOps-14B-Chat  | 在DevOps-14B上微调的模型          | [HF](https://huggingface.co/codefuse-ai/CodeFuse-DevOps-Model-14B-Chat) ; [MS](https://modelscope.cn/models/codefuse-ai/CodeFuse-DevOps-Model-14B-Chat/summary)  | 
| CodeFuse-DevOps-14B-Base    | 在Qwen-14B上加训DevOps相关数据的Base模型        | [HF](https://huggingface.co/codefuse-ai/CodeFuse-DevOps-Model-14B-Base) ; [MS](https://modelscope.cn/models/codefuse-ai/CodeFuse-DevOps-Model-14B-Base/summary)  | 
| CodeFuse-TestGPT-7B    | 基于CodeLLaMA-7B微调的用于测试的模型 | [HF](https://huggingface.co/codefuse-ai/CodeFuse-TestGPT-7B) ; [MS](https://modelscope.cn/models/codefuse-ai/TestGPT-7B/summary)  | 


## 演示

 - 视频Demo: 下面是中文版本, 英文版准备中
   https://user-images.githubusercontent.com/103973989/267514150-21012a5d-652d-4aea-bcea-582e67855ad7.mp4

 - 在线版本: 你可以在魔搭社区尝试我们的34B模型: [CodeFuse-CodeLlama34B-MFT-Demo](https://modelscope.cn/studios/codefuse-ai/CodeFuse-CodeLlama34B-MFT-Demo/summary)

![Online Demo Snapshot](assets/modelscope_demo2.png)

- 离线版本：你也可以安装[CodeFuse-Chatbot](https://github.com/codefuse-ai/codefuse-chatbot)在本地尝试我们的模型.

## 如何获得

- HF模型社区[**HuggingFace**](https://huggingface.co/codefuse-ai).
- 魔搭社区[**ModelScope**](https://modelscope.cn/organization/codefuse-ai).
- WiseModel社区[**WiseModel**](https://wisemodel.cn/organization/codefuse-ai).
- 对于自有或者自己感兴趣的模型，可以使用我们的[**MFTCoder**](https://github.com/codefuse-ai/MFTCoder)框架微调训练，它是一个支持多模型、多任务、多训练平台的微调框架.

## 参考文献
如果你觉得本项目对你有帮助，请引用下述论文:
```
@article{mftcoder2023,
      title={MFTCoder: Boosting Code LLMs with Multitask Fine-Tuning}, 
      author={Bingchang Liu and Chaoyu Chen and Cong Liao and Zi Gong and Huan Wang and Zhichao Lei and Ming Liang and Dajun Chen and Min Shen and Hailian Zhou and Hang Yu and Jianguo Li},
      year={2023},
      journal={arXiv preprint arXiv},
      archivePrefix={arXiv},
      eprint={2311.02303}
}

@misc{di2023codefuse13b,
      title={CodeFuse-13B: A Pretrained Multi-lingual Code Large Language Model}, 
      author={Peng Di and Jianguo Li and Hang Yu and Wei Jiang and Wenting Cai and Yang Cao and Chaoyu Chen and Dajun Chen and Hongwei Chen and Liang Chen and Gang Fan and Jie Gong and Zi Gong and Wen Hu and Tingting Guo and Zhichao Lei and Ting Li and Zheng Li and Ming Liang and Cong Liao and Bingchang Liu and Jiachen Liu and Zhiwei Liu and Shaojun Lu and Min Shen and Guangpei Wang and Huan Wang and Zhi Wang and Zhaogui Xu and Jiawei Yang and Qing Ye and Gehao Zhang and Yu Zhang and Zelin Zhao and Xunjin Zheng and Hailian Zhou and Lifu Zhu and Xianying Zhu},
      year={2023},
      eprint={2310.06266},
      archivePrefix={arXiv},
      primaryClass={cs.SE}
}
```
