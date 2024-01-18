# Awesome-Reparameterize <br>[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
### This page's style is based on **[Awesome-Efficient-LLM](https://github.com/horseee/Awesome-Efficient-LLM/tree/main)**. Thank you for providing a great format. 

A curated list for Reparameterize:
  - [CNN](#cnn)
  - [Transformer/ViT](#Transformer/ViT)
  - [Quantization for Reparameterize](#Quantization-for-Reparameterize)
  - [Specific Domain](#specific-domain)
  - [Others](#Others)

####    

#### 🚀 Updates

#### 💮 Contributing

If you'd like to include your paper, or need to update any details such as conference information or code URLs, please feel free to submit a pull request. You can generate the required markdown format for each paper by filling in the information in `generate_item.py` and execute `python generate_item.py`. (or using `genetarte_markdown.ipynb`)  We warmly appreciate your contributions to this list. Alternatively, you can email me with the links to your paper and code, and I would add your paper to the list at my earliest convenience. 


## CNN
| Title & Authors | Introduction | Links |
|:----|  :----: | :---:|
|[![Star](https://img.shields.io/github/stars/FranxYao/FlanT5-CoT-Specialization.svg?style=social&label=Star)](https://github.com/FranxYao/FlanT5-CoT-Specialization)[![Publish](https://img.shields.io/badge/Conference-ICML'23-blue)]()<br>[Specializing Smaller Language Models towards Multi-Step Reasoning](https://arxiv.org/abs/2301.12726) <br> Yao Fu, Hao Peng, Litu Ou, Ashish Sabharwal, Tushar Khot |<img width="1002" alt="image" src="figures/ModelSpecialization.png"> |[Github](https://github.com/FranxYao/FlanT5-CoT-Specialization) <br> [Paper](https://arxiv.org/abs/2301.12726)|
|[![Star](https://img.shields.io/github/stars/DingXiaoH/RepVGG.svg?style=social&label=Star)](https://github.com/DingXiaoH/RepVGG) <br>[Repvgg: Making vgg-style convnets great again](https://arxiv.org/abs/2101.03697). <br> Ding, Xiaohan and Zhang, Xiangyu and Ma, Ningning and Han, Jungong and Ding, Guiguang and Sun, Jian.|<img width="1002" alt="image" src="figures/ModelSpecialization.png"> |[Paper](https://arxiv.org/abs/2101.03697)<br>[Github](https://github.com/DingXiaoH/RepVGG)|


|[![Star](https://img.shields.io/github/stars/microsoft/DeepSpeed-MII.svg?style=social&label=Star)](https://github.com/microsoft/DeepSpeed-MII) [DeepSpeed-FastGen: High-throughput Text Generation for LLMs via MII and DeepSpeed-Inference](https://arxiv.org/abs/2401.08671). Connor Holmes, Masahiro Tanaka, Michael Wyatt, Ammar Ahmad Awan, Jeff Rasley, Samyam Rajbhandari, Reza Yazdani Aminabadi, Heyang Qin, Arash Bakhtiari, Lev Kurilenko, Yuxiong He. [[Paper]](https://arxiv.org/abs/2401.08671)[[Github]](https://github.com/microsoft/DeepSpeed-MII)
<!--
|[![Star](https://img.shields.io/github/stars/FranxYao/FlanT5-CoT-Specialization.svg?style=social&label=Star)](https://github.com/FranxYao/FlanT5-CoT-Specialization)[![Publish](https://img.shields.io/badge/Conference-ICML'23-blue)]()<br>[Specializing Smaller Language Models towards Multi-Step Reasoning](https://arxiv.org/abs/2301.12726) <br> Yao Fu, Hao Peng, Litu Ou, Ashish Sabharwal, Tushar Khot |<img width="1002" alt="image" src="figures/ModelSpecialization.png"> |[Github](https://github.com/FranxYao/FlanT5-CoT-Specialization) <br> [Paper](https://arxiv.org/abs/2301.12726)|
|[![Star](https://img.shields.io/github/stars/siyuyuan/coscript.svg?style=social&label=Star)](https://github.com/siyuyuan/coscript)[![Publish](https://img.shields.io/badge/Conference-ACL'23%20Outstanding-blue)]()<br>[Distilling Script Knowledge from Large Language Models for Constrained Language Planning](https://arxiv.org/abs/2305.05252) <br> Siyu Yuan, Jiangjie Chen, Ziquan Fu, Xuyang Ge, Soham Shah, Charles Robert Jankowski, Yanghua Xiao, Deqing Yang |<img width="302" alt="image" src="figures/CoScript.png"> |[Github](https://github.com/siyuyuan/coscript) <br> [Paper](https://arxiv.org/abs/2305.05252)|
|[![Publish](https://img.shields.io/badge/Conference-ACL'23%20Outstanding-blue)]()<br>[SCOTT: Self-Consistent Chain-of-Thought Distillation](https://arxiv.org/abs/2305.01879) <br> Peifeng Wang, Zhengyang Wang, Zheng Li, Yifan Gao, Bing Yin, Xiang Ren |<img width="1002" alt="image" src="figures/SCOTT.png"> |[Paper](https://arxiv.org/abs/2305.01879)|
|[![Star](https://img.shields.io/github/stars/eric11eca/disco.svg?style=social&label=Star)](https://github.com/eric11eca/disco)[![Publish](https://img.shields.io/badge/Conference-ACL'23-blue)]()<br>[DISCO: Distilling Counterfactuals with Large Language Models](https://arxiv.org/abs/2212.10534) <br> Zeming Chen, Qiyue Gao, Antoine Bosselut, Ashish Sabharwal, Kyle Richardson |<img width="1002" alt="image" src="figures/disco.png"> |[Github](https://github.com/eric11eca/disco) <br> [Paper](https://arxiv.org/abs/2212.10534)|
|[![Star](https://img.shields.io/github/stars/allenai/i2d2.svg?style=social&label=Star)](https://github.com/allenai/i2d2)[![Publish](https://img.shields.io/badge/Conference-ACL'23-blue)]()<br>[I2D2: Inductive Knowledge Distillation with NeuroLogic and Self-Imitation](https://arxiv.org/abs/2212.09246) <br> Chandra Bhagavatula, Jena D. Hwang, Doug Downey, Ronan Le Bras, Ximing Lu, Lianhui Qin, Keisuke Sakaguchi, Swabha Swayamdipta, Peter West, Yejin Choi |<img width="1002" alt="image" src="https://i2d2.allen.ai/i2d2-fig1.png"> |[Github](https://github.com/allenai/i2d2) <br> [Paper](https://arxiv.org/abs/2212.09246) <br> [Project](https://i2d2.allen.ai/) |
|[![Star](https://img.shields.io/github/stars/allenai/cot_distillation.svg?style=social&label=Star)](https://github.com/allenai/cot_distillation)[![Publish](https://img.shields.io/badge/Conference-ACL'23-blue)]()<br>[Symbolic Chain-of-Thought Distillation: Small Models Can Also "Think" Step-by-Step](https://arxiv.org/abs/2306.14050) <br> Liunian Harold Li, Jack Hessel, Youngjae Yu, Xiang Ren, Kai-Wei Chang, Yejin Choi |<img width="202" alt="image" src="figures/SCoTD.png"> |[Github](https://github.com/allenai/cot_distillation) <br> [Paper](https://arxiv.org/abs/2306.14050)|
|[![Star](https://img.shields.io/github/stars/swarnaHub/ExplanationIntervention.svg?style=social&label=Star)](https://github.com/swarnaHub/ExplanationIntervention) [![Publish](https://img.shields.io/badge/Conference-NeurIPS'23-blue)]() <br>[Can Language Models Teach? Teacher Explanations Improve Student Performance via Theory of Mind](https://arxiv.org/abs/2306.09299) <br> Swarnadeep Saha, Peter Hase, and Mohit Bansal |<img width="302" alt="image" src="https://github.com/swarnaHub/ExplanationIntervention/blob/main/assets/main_fig.png"> |[Github](https://github.com/swarnaHub/ExplanationIntervention) <br> [Paper](https://arxiv.org/abs/2306.09299)|
|[![Publish](https://img.shields.io/badge/Conference-EMNLP'23-blue)]()<br>[Dialogue Chain-of-Thought Distillation for Commonsense-aware Conversational Agents](https://arxiv.org/abs/2310.09343) <br> Hyungjoo Chae, Yongho Song, Kai Tzu-iunn Ong, Taeyoon Kwon, Minjin Kim, Youngjae Yu, Dongha Lee, Dongyeop Kang, Jinyoung Yeo |<img width="1002" alt="image" src="figures/Doctor.png"> |[Paper](https://arxiv.org/abs/2310.09343)|
|[![Star](https://img.shields.io/github/stars/ServiceNow/PromptMix-EMNLP-2023.svg?style=social&label=Star)](https://github.com/ServiceNow/PromptMix-EMNLP-2023)[![Publish](https://img.shields.io/badge/Conference-EMNLP'23-blue)]()<br>[PromptMix: A Class Boundary Augmentation Method for Large Language Model Distillation](https://arxiv.org/abs/2310.14192) <br> Gaurav Sahu, Olga Vechtomova, Dzmitry Bahdanau, Issam H. Laradji |<img width="1002" alt="image" src="figures/PromptMix.png"> |[Github](https://github.com/ServiceNow/PromptMix-EMNLP-2023) <br> [Paper](https://arxiv.org/abs/2310.14192)|
|[![Star](https://img.shields.io/github/stars/Yiwei98/TDG.svg?style=social&label=Star)](https://github.com/Yiwei98/TDG)[![Publish](https://img.shields.io/badge/Conference-AAAI'24-blue)]()<br>[Turning Dust into Gold: Distilling Complex Reasoning Capabilities from LLMs by Leveraging Negative Data](https://arxiv.org/abs/2312.12832) <br> Yiwei Li, Peiwen Yuan, Shaoxiong Feng, Boyuan Pan, Bin Sun, Xinglin Wang, Heda Wang, Kan Li |<img width="1002" alt="image" src="https://github.com/Yiwei98/TDG/blob/main/img.png"> |[Github](https://github.com/Yiwei98/TDG) <br> [Paper](https://arxiv.org/abs/2312.12832)|
|[![Star](https://img.shields.io/github/stars/aitsc/GLMKD.svg?style=social&label=Star)](https://github.com/aitsc/GLMKD) [![Publish](https://img.shields.io/badge/Conference-ACL'23%20Industry%20Track-blue)]() <br>[GKD: A General Knowledge Distillation Framework for Large-scale Pre-trained Language Model](https://arxiv.org/abs/2306.06629) <br> Shicheng Tan, Weng Lam Tam, Yuanchun Wang, Wenwen Gong, Yang Yang, Hongyin Tang, Keqing He, Jiahao Liu, Jingang Wang, Shu Zhao, Peng Zhang, Jie Tang |<img width="1002" alt="image" src="figures/GKD.png"> |[Github](https://github.com/aitsc/GLMKD) <br> [Paper](https://arxiv.org/abs/2306.06629)|
|[![Star](https://img.shields.io/github/stars/google-research/distilling-step-by-step.svg?style=social&label=Star)](https://github.com/google-research/distilling-step-by-step) [![Publish](https://img.shields.io/badge/Conference-ACL'23%20Findings-blue)]() <br> [Distilling Step-by-Step! Outperforming Larger Language Models with Less Training Data and Smaller Model Sizes](https://arxiv.org/abs/2305.02301)    <br> Cheng-Yu Hsieh, Chun-Liang Li, Chih-Kuan Yeh, Hootan Nakhost, Yasuhisa Fujii, Alexander Ratner, Ranjay Krishna, Chen-Yu Lee, Tomas Pfister | <img width="2000" alt="image" src="figures/Distill_step_by_step.png">| [Github](https://github.com/google-research/distilling-step-by-step) <br> [Paper](https://arxiv.org/abs/2305.02301) |
|[![Publish](https://img.shields.io/badge/Conference-EMNLP'23%20Findings-blue)]()<br>[Retrieval-based Knowledge Transfer: An Effective Approach for Extreme Large Language Model Compression](https://arxiv.org/abs/2310.15594) <br> Jiduan Liu, Jiahao Liu, Qifan Wang, Jingang Wang, Xunliang Cai, Dongyan Zhao, Ran Lucien Wang, Rui Yan |<img width="1002" alt="image" src="figures/RetriKT.png"> |[Paper](https://arxiv.org/abs/2310.15594)|
|[![Star](https://img.shields.io/github/stars/stoyian/OCaTS.svg?style=social&label=Star)](https://github.com/stoyian/OCaTS)[![Publish](https://img.shields.io/badge/Conference-EMNLP'23%20Findings-blue)]()<br>[Cache me if you Can: an Online Cost-aware Teacher-Student framework to Reduce the Calls to Large Language Models](https://arxiv.org/abs/2310.13395) <br> Ilias Stogiannidis, Stavros Vassos, Prodromos Malakasiotis, Ion Androutsopoulos |<img width="252" alt="image" src="figures/OCaTS.png"> |[Github](https://github.com/stoyian/OCaTS) <br> [Paper](https://arxiv.org/abs/2310.13395)|
| [![Star](https://img.shields.io/github/stars/mbzuai-nlp/LaMini-LM.svg?style=social&label=Star)](https://github.com/mbzuai-nlp/LaMini-LM) <br> [LaMini-LM: A Diverse Herd of Distilled Models from Large-Scale Instructions](https://github.com/mbzuai-nlp/LaMini-LM) <br>Minghao Wu, Abdul Waheed, Chiyu Zhang, Muhammad Abdul-Mageed, Alham Fikri Aji | <img width="1002" alt="image" src="https://github.com/mbzuai-nlp/LaMini-LM/blob/main/images/lamini-pipeline.drawio.png"> | [Github](https://github.com/mbzuai-nlp/LaMini-LM) [paper](https://arxiv.org/abs/2304.14402) |
|[Knowledge Distillation of Large Language Models](https://arxiv.org/abs/2306.08543) <br> Yuxian Gu, Li Dong, Furu Wei, Minlie Huang |<img width="1002" alt="image" src="https://github.com/microsoft/LMOps/blob/main/minillm/figures/method.png"> |[Github](https://github.com/microsoft/LMOps/tree/main/minillm) <br> [Paper](https://arxiv.org/abs/2306.08543)|
|[Teaching Small Language Models to Reason](https://arxiv.org/abs/2212.08410) <br> Lucie Charlotte Magister, Jonathan Mallinson, Jakub Adamek, Eric Malmi, Aliaksei Severyn.  |<img width="202" alt="image" src="figures/Teach_Small_LM_COT.png"> |[Paper](https://arxiv.org/abs/2212.08410)|
| [![Star](https://img.shields.io/github/stars/ananyahjha93/llm-distill.svg?style=social&label=Star)](https://github.com/ananyahjha93/llm-distill) <br> [Large Language Model Distillation Doesn't Need a Teacher](https://arxiv.org/abs/2305.14864) <br> Ananya Harsh Jha, Dirk Groeneveld, Emma Strubell, Iz Beltagy </br> | <img width="2000" alt="image" src="figures/TeacherFreeLLM.png"> | [Github](https://github.com/ananyahjha93/llm-distill) [paper](https://arxiv.org/abs/2305.14864) |
| [The False Promise of Imitating Proprietary LLMs](https://arxiv.org/abs/2305.15717) <br> Arnav Gudibande, Eric Wallace, Charlie Snell, Xinyang Geng, Hao Liu, Pieter Abbeel, Sergey Levine, Dawn Song | <img width="400" alt="image" src="figures/FalsePromise.png"> | [Paper](https://arxiv.org/abs/2305.15717) |
|[![Star](https://img.shields.io/github/stars/jaehunjung1/impossible-distillation.svg?style=social&label=Star)](https://github.com/jaehunjung1/impossible-distillation) <br>[Impossible Distillation: from Low-Quality Model to High-Quality Dataset & Model for Summarization and Paraphrasing](https://arxiv.org/abs/2305.16635) <br> Jaehun Jung, Peter West, Liwei Jiang, Faeze Brahman, Ximing Lu, Jillian Fisher, Taylor Sorensen, Yejin Choi |<img width="1002" alt="image" src="figures/impossible_distillation.png"> |[Github](https://github.com/jaehunjung1/impossible-distillation) [paper](https://arxiv.org/abs/2305.16635) |
|[PaD: Program-aided Distillation Specializes Large Models in Reasoning](https://arxiv.org/abs/2305.13888) <br> Xuekai Zhu, Biqing Qi, Kaiyan Zhang, Xingwei Long, Bowen Zhou |<img width="402" alt="image" src="figures/PaD.png"> |[Paper](https://arxiv.org/abs/2305.13888)|
|[RLCD: Reinforcement Learning from Contrast Distillation for Language Model Alignment](https://arxiv.org/abs/2307.12950) <br> Kevin Yang, Dan Klein, Asli Celikyilmaz, Nanyun Peng, Yuandong Tian |<img width="302" alt="image" src="figures/RLCD.png"> |[Paper](https://arxiv.org/abs/2307.12950)|
|[Sci-CoT: Leveraging Large Language Models for Enhanced Knowledge Distillation in Small Models for Scientific QA](https://arxiv.org/abs/2308.04679) <br> Yuhan Ma, Haiqi Jiang, Chenyou Fan |<img width="302" alt="image" src="figures/Sci-COT.png"> |[Paper](https://arxiv.org/abs/2308.04679)|
|[![Star](https://img.shields.io/github/stars/universal-ner/universal-ner.svg?style=social&label=Star)](https://github.com/universal-ner/universal-ner)<br>[UniversalNER: Targeted Distillation from Large Language Models for Open Named Entity Recognition](https://arxiv.org/abs/2308.03279) <br> Wenxuan Zhou, Sheng Zhang, Yu Gu, Muhao Chen, Hoifung Poon |<img width="302" alt="image" src="figures/UniversalNER.png"> |[Github](https://github.com/universal-ner/universal-ner) <br> [Paper](https://arxiv.org/abs/2308.03279) <br> [Project](https://universal-ner.github.io) |
|[![Star](https://img.shields.io/github/stars/timinar/BabyLlama.svg?style=social&label=Star)](https://github.com/timinar/BabyLlama)<br>[Baby Llama: knowledge distillation from an ensemble of teachers trained on a small dataset with no performance penalty](https://arxiv.org/abs/2308.02019) <br> Inar Timiryasov, Jean-Loup Tastet |<img width="302" alt="image" src="figures/BabyLLaMA.png"> |[Github](https://github.com/timinar/BabyLlama) <br> [Paper](https://arxiv.org/abs/2308.02019) | [Model](https://huggingface.co/timinar/baby-llama-58m) |
|[DistillSpec: Improving Speculative Decoding via Knowledge Distillation](https://arxiv.org/abs/2310.08461) <br> Yongchao Zhou, Kaifeng Lyu, Ankit Singh Rawat, Aditya Krishna Menon, Afshin Rostamizadeh, Sanjiv Kumar, Jean-François Kagy, Rishabh Agarwal |<img width="1002" alt="image" src="figures/DistillSpec.png"> |[Paper](https://arxiv.org/abs/2310.08461)|
|[![Star](https://img.shields.io/github/stars/huggingface/alignment-handbook.svg?style=social&label=Star)](https://github.com/huggingface/alignment-handbook)<br>[Zephyr: Direct Distillation of LM Alignment](https://arxiv.org/abs/2310.16944) <br> Lewis Tunstall, Edward Beeching, Nathan Lambert, Nazneen Rajani, Kashif Rasul, Younes Belkada, Shengyi Huang, Leandro von Werra, Clémentine Fourrier, Nathan Habib, Nathan Sarrazin, Omar Sanseviero, Alexander M. Rush, Thomas Wolf |<img width="1002" alt="image" src="figures/zephyr.png"> |[Github](https://github.com/huggingface/alignment-handbook) <br> [Paper](https://arxiv.org/abs/2310.16944)|
|[![Star](https://img.shields.io/github/stars/GeneZC/MiniMA.svg?style=social&label=Star)](https://github.com/GeneZC/MiniMA)<br>[Towards the Law of Capacity Gap in Distilling Language Models](https://arxiv.org/abs/2311.07052) <br> Chen Zhang, Dawei Song, Zheyu Ye, Yan Gao |<img width="1002" alt="image" src="figures/MiniMA.png"> |[Github](https://github.com/GeneZC/MiniMA) <br> [Paper](https://arxiv.org/abs/2311.07052)|
|[Unlock the Power: Competitive Distillation for Multi-Modal Large Language Models](https://arxiv.org/abs/2311.08213) <br> Xinwei Li, Li Lin, Shuai Wang, Chen Qian |<img width="1002" alt="image" src="figures/CoMD.png"> |[Paper](https://arxiv.org/abs/2311.08213)|
|[Mixed Distillation Helps Smaller Language Model Better Reasoning](https://arxiv.org/abs/2312.10730) <br> Li Chenglin, Chen Qianglong, Wang Caiyu, Zhang Yin |<img width="1002" alt="image" src="figures/MixDistill.png"> |[Paper](https://arxiv.org/abs/2312.10730)|
|[Distilling Event Sequence Knowledge From Large Language Models](https://arxiv.org/abs/2401.07237) <br> Somin Wadhwa, Oktie Hassanzadeh, Debarun Bhattacharjya, Ken Barker, Jian Ni |<img width="1002" alt="image" src="figures/distill_event.png"> |[Paper](https://arxiv.org/abs/2401.07237)|
|[Knowledge Distillation for Closed-Source Language Models](https://arxiv.org/abs/2401.07013) <br> Hongzhan Chen, Xiaojun Quan, Hehong Chen, Ming Yan, Ji Zhang |<img width="1002" alt="image" src="figures/kd_close_source.png"> |[Paper](https://arxiv.org/abs/2401.07013)|

## Transformer/ViT
| Title & Authors | Introduction | Links |
|:----|  :----: | :---:|
|[![Star](https://img.shields.io/github/stars/FranxYao/FlanT5-CoT-Specialization.svg?style=social&label=Star)](https://github.com/FranxYao/FlanT5-CoT-Specialization)[![Publish](https://img.shields.io/badge/Conference-ICML'23-blue)]()<br>[Specializing Smaller Language Models towards Multi-Step Reasoning](https://arxiv.org/abs/2301.12726) <br> Yao Fu, Hao Peng, Litu Ou, Ashish Sabharwal, Tushar Khot |<img width="1002" alt="image" src="figures/ModelSpecialization.png"> |[Github](https://github.com/FranxYao/FlanT5-CoT-Specialization) <br> [Paper](https://arxiv.org/abs/2301.12726)|
|[![Star](https://img.shields.io/github/stars/siyuyuan/coscript.svg?style=social&label=Star)](https://github.com/siyuyuan/coscript)[![Publish](https://img.shields.io/badge/Conference-ACL'23%20Outstanding-blue)]()<br>[Distilling Script Knowledge from Large Language Models for Constrained Language Planning](https://arxiv.org/abs/2305.05252) <br> Siyu Yuan, Jiangjie Chen, Ziquan Fu, Xuyang Ge, Soham Shah, Charles Robert Jankowski, Yanghua Xiao, Deqing Yang |<img width="302" alt="image" src="figures/CoScript.png"> |[Github](https://github.com/siyuyuan/coscript) <br> [Paper](https://arxiv.org/abs/2305.05252)|
|[![Publish](https://img.shields.io/badge/Conference-ACL'23%20Outstanding-blue)]()<br>[SCOTT: Self-Consistent Chain-of-Thought Distillation](https://arxiv.org/abs/2305.01879) <br> Peifeng Wang, Zhengyang Wang, Zheng Li, Yifan Gao, Bing Yin, Xiang Ren |<img width="1002" alt="image" src="figures/SCOTT.png"> |[Paper](https://arxiv.org/abs/2305.01879)|
|[![Star](https://img.shields.io/github/stars/eric11eca/disco.svg?style=social&label=Star)](https://github.com/eric11eca/disco)[![Publish](https://img.shields.io/badge/Conference-ACL'23-blue)]()<br>[DISCO: Distilling Counterfactuals with Large Language Models](https://arxiv.org/abs/2212.10534) <br> Zeming Chen, Qiyue Gao, Antoine Bosselut, Ashish Sabharwal, Kyle Richardson |<img width="1002" alt="image" src="figures/disco.png"> |[Github](https://github.com/eric11eca/disco) <br> [Paper](https://arxiv.org/abs/2212.10534)|
|[![Star](https://img.shields.io/github/stars/allenai/i2d2.svg?style=social&label=Star)](https://github.com/allenai/i2d2)[![Publish](https://img.shields.io/badge/Conference-ACL'23-blue)]()<br>[I2D2: Inductive Knowledge Distillation with NeuroLogic and Self-Imitation](https://arxiv.org/abs/2212.09246) <br> Chandra Bhagavatula, Jena D. Hwang, Doug Downey, Ronan Le Bras, Ximing Lu, Lianhui Qin, Keisuke Sakaguchi, Swabha Swayamdipta, Peter West, Yejin Choi |<img width="1002" alt="image" src="https://i2d2.allen.ai/i2d2-fig1.png"> |[Github](https://github.com/allenai/i2d2) <br> [Paper](https://arxiv.org/abs/2212.09246) <br> [Project](https://i2d2.allen.ai/) |
|[![Star](https://img.shields.io/github/stars/allenai/cot_distillation.svg?style=social&label=Star)](https://github.com/allenai/cot_distillation)[![Publish](https://img.shields.io/badge/Conference-ACL'23-blue)]()<br>[Symbolic Chain-of-Thought Distillation: Small Models Can Also "Think" Step-by-Step](https://arxiv.org/abs/2306.14050) <br> Liunian Harold Li, Jack Hessel, Youngjae Yu, Xiang Ren, Kai-Wei Chang, Yejin Choi |<img width="202" alt="image" src="figures/SCoTD.png"> |[Github](https://github.com/allenai/cot_distillation) <br> [Paper](https://arxiv.org/abs/2306.14050)|
|[![Star](https://img.shields.io/github/stars/swarnaHub/ExplanationIntervention.svg?style=social&label=Star)](https://github.com/swarnaHub/ExplanationIntervention) [![Publish](https://img.shields.io/badge/Conference-NeurIPS'23-blue)]() <br>[Can Language Models Teach? Teacher Explanations Improve Student Performance via Theory of Mind](https://arxiv.org/abs/2306.09299) <br> Swarnadeep Saha, Peter Hase, and Mohit Bansal |<img width="302" alt="image" src="https://github.com/swarnaHub/ExplanationIntervention/blob/main/assets/main_fig.png"> |[Github](https://github.com/swarnaHub/ExplanationIntervention) <br> [Paper](https://arxiv.org/abs/2306.09299)|
|[![Publish](https://img.shields.io/badge/Conference-EMNLP'23-blue)]()<br>[Dialogue Chain-of-Thought Distillation for Commonsense-aware Conversational Agents](https://arxiv.org/abs/2310.09343) <br> Hyungjoo Chae, Yongho Song, Kai Tzu-iunn Ong, Taeyoon Kwon, Minjin Kim, Youngjae Yu, Dongha Lee, Dongyeop Kang, Jinyoung Yeo |<img width="1002" alt="image" src="figures/Doctor.png"> |[Paper](https://arxiv.org/abs/2310.09343)|
|[![Star](https://img.shields.io/github/stars/ServiceNow/PromptMix-EMNLP-2023.svg?style=social&label=Star)](https://github.com/ServiceNow/PromptMix-EMNLP-2023)[![Publish](https://img.shields.io/badge/Conference-EMNLP'23-blue)]()<br>[PromptMix: A Class Boundary Augmentation Method for Large Language Model Distillation](https://arxiv.org/abs/2310.14192) <br> Gaurav Sahu, Olga Vechtomova, Dzmitry Bahdanau, Issam H. Laradji |<img width="1002" alt="image" src="figures/PromptMix.png"> |[Github](https://github.com/ServiceNow/PromptMix-EMNLP-2023) <br> [Paper](https://arxiv.org/abs/2310.14192)|
|[![Star](https://img.shields.io/github/stars/Yiwei98/TDG.svg?style=social&label=Star)](https://github.com/Yiwei98/TDG)[![Publish](https://img.shields.io/badge/Conference-AAAI'24-blue)]()<br>[Turning Dust into Gold: Distilling Complex Reasoning Capabilities from LLMs by Leveraging Negative Data](https://arxiv.org/abs/2312.12832) <br> Yiwei Li, Peiwen Yuan, Shaoxiong Feng, Boyuan Pan, Bin Sun, Xinglin Wang, Heda Wang, Kan Li |<img width="1002" alt="image" src="https://github.com/Yiwei98/TDG/blob/main/img.png"> |[Github](https://github.com/Yiwei98/TDG) <br> [Paper](https://arxiv.org/abs/2312.12832)|
|[![Star](https://img.shields.io/github/stars/aitsc/GLMKD.svg?style=social&label=Star)](https://github.com/aitsc/GLMKD) [![Publish](https://img.shields.io/badge/Conference-ACL'23%20Industry%20Track-blue)]() <br>[GKD: A General Knowledge Distillation Framework for Large-scale Pre-trained Language Model](https://arxiv.org/abs/2306.06629) <br> Shicheng Tan, Weng Lam Tam, Yuanchun Wang, Wenwen Gong, Yang Yang, Hongyin Tang, Keqing He, Jiahao Liu, Jingang Wang, Shu Zhao, Peng Zhang, Jie Tang |<img width="1002" alt="image" src="figures/GKD.png"> |[Github](https://github.com/aitsc/GLMKD) <br> [Paper](https://arxiv.org/abs/2306.06629)|
|[![Star](https://img.shields.io/github/stars/google-research/distilling-step-by-step.svg?style=social&label=Star)](https://github.com/google-research/distilling-step-by-step) [![Publish](https://img.shields.io/badge/Conference-ACL'23%20Findings-blue)]() <br> [Distilling Step-by-Step! Outperforming Larger Language Models with Less Training Data and Smaller Model Sizes](https://arxiv.org/abs/2305.02301)    <br> Cheng-Yu Hsieh, Chun-Liang Li, Chih-Kuan Yeh, Hootan Nakhost, Yasuhisa Fujii, Alexander Ratner, Ranjay Krishna, Chen-Yu Lee, Tomas Pfister | <img width="2000" alt="image" src="figures/Distill_step_by_step.png">| [Github](https://github.com/google-research/distilling-step-by-step) <br> [Paper](https://arxiv.org/abs/2305.02301) |
|[![Publish](https://img.shields.io/badge/Conference-EMNLP'23%20Findings-blue)]()<br>[Retrieval-based Knowledge Transfer: An Effective Approach for Extreme Large Language Model Compression](https://arxiv.org/abs/2310.15594) <br> Jiduan Liu, Jiahao Liu, Qifan Wang, Jingang Wang, Xunliang Cai, Dongyan Zhao, Ran Lucien Wang, Rui Yan |<img width="1002" alt="image" src="figures/RetriKT.png"> |[Paper](https://arxiv.org/abs/2310.15594)|
|[![Star](https://img.shields.io/github/stars/stoyian/OCaTS.svg?style=social&label=Star)](https://github.com/stoyian/OCaTS)[![Publish](https://img.shields.io/badge/Conference-EMNLP'23%20Findings-blue)]()<br>[Cache me if you Can: an Online Cost-aware Teacher-Student framework to Reduce the Calls to Large Language Models](https://arxiv.org/abs/2310.13395) <br> Ilias Stogiannidis, Stavros Vassos, Prodromos Malakasiotis, Ion Androutsopoulos |<img width="252" alt="image" src="figures/OCaTS.png"> |[Github](https://github.com/stoyian/OCaTS) <br> [Paper](https://arxiv.org/abs/2310.13395)|
| [![Star](https://img.shields.io/github/stars/mbzuai-nlp/LaMini-LM.svg?style=social&label=Star)](https://github.com/mbzuai-nlp/LaMini-LM) <br> [LaMini-LM: A Diverse Herd of Distilled Models from Large-Scale Instructions](https://github.com/mbzuai-nlp/LaMini-LM) <br>Minghao Wu, Abdul Waheed, Chiyu Zhang, Muhammad Abdul-Mageed, Alham Fikri Aji | <img width="1002" alt="image" src="https://github.com/mbzuai-nlp/LaMini-LM/blob/main/images/lamini-pipeline.drawio.png"> | [Github](https://github.com/mbzuai-nlp/LaMini-LM) [paper](https://arxiv.org/abs/2304.14402) |
|[Knowledge Distillation of Large Language Models](https://arxiv.org/abs/2306.08543) <br> Yuxian Gu, Li Dong, Furu Wei, Minlie Huang |<img width="1002" alt="image" src="https://github.com/microsoft/LMOps/blob/main/minillm/figures/method.png"> |[Github](https://github.com/microsoft/LMOps/tree/main/minillm) <br> [Paper](https://arxiv.org/abs/2306.08543)|
|[Teaching Small Language Models to Reason](https://arxiv.org/abs/2212.08410) <br> Lucie Charlotte Magister, Jonathan Mallinson, Jakub Adamek, Eric Malmi, Aliaksei Severyn.  |<img width="202" alt="image" src="figures/Teach_Small_LM_COT.png"> |[Paper](https://arxiv.org/abs/2212.08410)|
| [![Star](https://img.shields.io/github/stars/ananyahjha93/llm-distill.svg?style=social&label=Star)](https://github.com/ananyahjha93/llm-distill) <br> [Large Language Model Distillation Doesn't Need a Teacher](https://arxiv.org/abs/2305.14864) <br> Ananya Harsh Jha, Dirk Groeneveld, Emma Strubell, Iz Beltagy </br> | <img width="2000" alt="image" src="figures/TeacherFreeLLM.png"> | [Github](https://github.com/ananyahjha93/llm-distill) [paper](https://arxiv.org/abs/2305.14864) |
| [The False Promise of Imitating Proprietary LLMs](https://arxiv.org/abs/2305.15717) <br> Arnav Gudibande, Eric Wallace, Charlie Snell, Xinyang Geng, Hao Liu, Pieter Abbeel, Sergey Levine, Dawn Song | <img width="400" alt="image" src="figures/FalsePromise.png"> | [Paper](https://arxiv.org/abs/2305.15717) |
|[![Star](https://img.shields.io/github/stars/jaehunjung1/impossible-distillation.svg?style=social&label=Star)](https://github.com/jaehunjung1/impossible-distillation) <br>[Impossible Distillation: from Low-Quality Model to High-Quality Dataset & Model for Summarization and Paraphrasing](https://arxiv.org/abs/2305.16635) <br> Jaehun Jung, Peter West, Liwei Jiang, Faeze Brahman, Ximing Lu, Jillian Fisher, Taylor Sorensen, Yejin Choi |<img width="1002" alt="image" src="figures/impossible_distillation.png"> |[Github](https://github.com/jaehunjung1/impossible-distillation) [paper](https://arxiv.org/abs/2305.16635) |
|[PaD: Program-aided Distillation Specializes Large Models in Reasoning](https://arxiv.org/abs/2305.13888) <br> Xuekai Zhu, Biqing Qi, Kaiyan Zhang, Xingwei Long, Bowen Zhou |<img width="402" alt="image" src="figures/PaD.png"> |[Paper](https://arxiv.org/abs/2305.13888)|
|[RLCD: Reinforcement Learning from Contrast Distillation for Language Model Alignment](https://arxiv.org/abs/2307.12950) <br> Kevin Yang, Dan Klein, Asli Celikyilmaz, Nanyun Peng, Yuandong Tian |<img width="302" alt="image" src="figures/RLCD.png"> |[Paper](https://arxiv.org/abs/2307.12950)|
|[Sci-CoT: Leveraging Large Language Models for Enhanced Knowledge Distillation in Small Models for Scientific QA](https://arxiv.org/abs/2308.04679) <br> Yuhan Ma, Haiqi Jiang, Chenyou Fan |<img width="302" alt="image" src="figures/Sci-COT.png"> |[Paper](https://arxiv.org/abs/2308.04679)|
|[![Star](https://img.shields.io/github/stars/universal-ner/universal-ner.svg?style=social&label=Star)](https://github.com/universal-ner/universal-ner)<br>[UniversalNER: Targeted Distillation from Large Language Models for Open Named Entity Recognition](https://arxiv.org/abs/2308.03279) <br> Wenxuan Zhou, Sheng Zhang, Yu Gu, Muhao Chen, Hoifung Poon |<img width="302" alt="image" src="figures/UniversalNER.png"> |[Github](https://github.com/universal-ner/universal-ner) <br> [Paper](https://arxiv.org/abs/2308.03279) <br> [Project](https://universal-ner.github.io) |
|[![Star](https://img.shields.io/github/stars/timinar/BabyLlama.svg?style=social&label=Star)](https://github.com/timinar/BabyLlama)<br>[Baby Llama: knowledge distillation from an ensemble of teachers trained on a small dataset with no performance penalty](https://arxiv.org/abs/2308.02019) <br> Inar Timiryasov, Jean-Loup Tastet |<img width="302" alt="image" src="figures/BabyLLaMA.png"> |[Github](https://github.com/timinar/BabyLlama) <br> [Paper](https://arxiv.org/abs/2308.02019) | [Model](https://huggingface.co/timinar/baby-llama-58m) |
|[DistillSpec: Improving Speculative Decoding via Knowledge Distillation](https://arxiv.org/abs/2310.08461) <br> Yongchao Zhou, Kaifeng Lyu, Ankit Singh Rawat, Aditya Krishna Menon, Afshin Rostamizadeh, Sanjiv Kumar, Jean-François Kagy, Rishabh Agarwal |<img width="1002" alt="image" src="figures/DistillSpec.png"> |[Paper](https://arxiv.org/abs/2310.08461)|
|[![Star](https://img.shields.io/github/stars/huggingface/alignment-handbook.svg?style=social&label=Star)](https://github.com/huggingface/alignment-handbook)<br>[Zephyr: Direct Distillation of LM Alignment](https://arxiv.org/abs/2310.16944) <br> Lewis Tunstall, Edward Beeching, Nathan Lambert, Nazneen Rajani, Kashif Rasul, Younes Belkada, Shengyi Huang, Leandro von Werra, Clémentine Fourrier, Nathan Habib, Nathan Sarrazin, Omar Sanseviero, Alexander M. Rush, Thomas Wolf |<img width="1002" alt="image" src="figures/zephyr.png"> |[Github](https://github.com/huggingface/alignment-handbook) <br> [Paper](https://arxiv.org/abs/2310.16944)|
|[![Star](https://img.shields.io/github/stars/GeneZC/MiniMA.svg?style=social&label=Star)](https://github.com/GeneZC/MiniMA)<br>[Towards the Law of Capacity Gap in Distilling Language Models](https://arxiv.org/abs/2311.07052) <br> Chen Zhang, Dawei Song, Zheyu Ye, Yan Gao |<img width="1002" alt="image" src="figures/MiniMA.png"> |[Github](https://github.com/GeneZC/MiniMA) <br> [Paper](https://arxiv.org/abs/2311.07052)|
|[Unlock the Power: Competitive Distillation for Multi-Modal Large Language Models](https://arxiv.org/abs/2311.08213) <br> Xinwei Li, Li Lin, Shuai Wang, Chen Qian |<img width="1002" alt="image" src="figures/CoMD.png"> |[Paper](https://arxiv.org/abs/2311.08213)|
|[Mixed Distillation Helps Smaller Language Model Better Reasoning](https://arxiv.org/abs/2312.10730) <br> Li Chenglin, Chen Qianglong, Wang Caiyu, Zhang Yin |<img width="1002" alt="image" src="figures/MixDistill.png"> |[Paper](https://arxiv.org/abs/2312.10730)|
|[Distilling Event Sequence Knowledge From Large Language Models](https://arxiv.org/abs/2401.07237) <br> Somin Wadhwa, Oktie Hassanzadeh, Debarun Bhattacharjya, Ken Barker, Jian Ni |<img width="1002" alt="image" src="figures/distill_event.png"> |[Paper](https://arxiv.org/abs/2401.07237)|
|[Knowledge Distillation for Closed-Source Language Models](https://arxiv.org/abs/2401.07013) <br> Hongzhan Chen, Xiaojun Quan, Hehong Chen, Ming Yan, Ji Zhang |<img width="1002" alt="image" src="figures/kd_close_source.png"> |[Paper](https://arxiv.org/abs/2401.07013)|
-->
