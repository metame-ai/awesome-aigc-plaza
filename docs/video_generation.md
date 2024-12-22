# Video Generation

- [Video Generation](#video-generation) 
  - [Survey](#survey)
  - [Generation](#generation)
  - [Animation](#animation)
  - [Evaluation](#evaluation)
  - [Detection](#detection)
  - [Alignment](#alignment)
  - [Auto Regressive](#auto-regressive)
  - [Editting](#editting)
  - [Datasets](#datasets)
  - [Toolkits](#toolkits)
  - [Tutorials](#tutorials)
  - [Blog](#blog)
  - [Products](#products)
  - [Misc](#misc)


## Survey


## Generation

- **LinGen: Towards High-Resolution Minute-Length Text-to-Video Generation
  with Linear Computational Complexity**, `arXiv, 2412.09856`, [arxiv](http://arxiv.org/abs/2412.09856v1), [pdf](http://arxiv.org/pdf/2412.09856v1.pdf), cication: [**-1**](None) 

	 *Hongjie Wang, Chih-Yao Ma, Yen-Cheng Liu, ..., Niraj K. Jha, Xiaoliang Dai* · ([lineargen.github](https://lineargen.github.io/))
- 🌟 [**FastVideo**](https://github.com/hao-ai-lab/FastVideo) - hao-ai-lab ![Star](https://img.shields.io/github/stars/hao-ai-lab/FastVideo.svg?style=social&label=Star)

	 · ([huggingface](https://huggingface.co/FastVideo/FastHunyuan)) · ([huggingface](https://huggingface.co/FastVideo/FastMochi-diffusers)) · ([𝕏](https://x.com/haoailab/status/1869119459249758680))
- 🌟 **STIV: Scalable Text and Image Conditioned Video Generation**, `arXiv, 2412.07730`, [arxiv](http://arxiv.org/abs/2412.07730v1), [pdf](http://arxiv.org/pdf/2412.07730v1.pdf), cication: [**-1**](None) 

	 *Zongyu Lin, Wei Liu, Chen Chen, ..., Kai-Wei Chang, Yinfei Yang*
- **Mobile Video Diffusion**, `arXiv, 2412.07583`, [arxiv](http://arxiv.org/abs/2412.07583v1), [pdf](http://arxiv.org/pdf/2412.07583v1.pdf), cication: [**-1**](None) 

	 *Haitam Ben Yahia, Denis Korzhenkov, Ioannis Lelekas, ..., Amir Ghodrati, Amirhossein Habibian* · ([qualcomm-ai-research.github](https://qualcomm-ai-research.github.io/mobile-video-diffusion/))
- 🌟 **SynCamMaster: Synchronizing Multi-Camera Video Generation from Diverse 
  Viewpoints**, `arXiv, 2412.07760`, [arxiv](http://arxiv.org/abs/2412.07760v1), [pdf](http://arxiv.org/pdf/2412.07760v1.pdf), cication: [**-1**](None) 

	 *Jianhong Bai, Menghan Xia, Xintao Wang, ..., Pengfei Wan, Di Zhang* · ([jianhongbai.github](https://jianhongbai.github.io/SynCamMaster/))
- **GenMAC: Compositional Text-to-Video Generation with Multi-Agent 
  Collaboration**, `arXiv, 2412.04440`, [arxiv](http://arxiv.org/abs/2412.04440v1), [pdf](http://arxiv.org/pdf/2412.04440v1.pdf), cication: [**-1**](None) 

	 *Kaiyi Huang, Yukun Huang, Xuefei Ning, ..., Yu Wang, Xihui Liu* · ([karine-h.github](https://karine-h.github.io/GenMAC/)) · ([arxiv](https://arxiv.org/pdf/2412.04440))
- [Genie 2: A large-scale foundation world model](https://deepmind.google/discover/blog/genie-2-a-large-scale-foundation-world-model/) 

	 · ([𝕏](https://x.com/GoogleDeepMind/status/1864367798132039836))
- **Mimir: Improving Video Diffusion Models for Precise Text Understanding**, `arXiv, 2412.03085`, [arxiv](http://arxiv.org/abs/2412.03085v1), [pdf](http://arxiv.org/pdf/2412.03085v1.pdf), cication: [**-1**](None) 

	 *Shuai Tan, Biao Gong, Yutong Feng, ..., Jingdong Chen, Ming Yang* · ([lucaria-academy.github](https://lucaria-academy.github.io/Mimir/))
- **Open-Sora Plan: Open-Source Large Video Generation Model**, `arXiv, 2412.00131`, [arxiv](http://arxiv.org/abs/2412.00131v1), [pdf](http://arxiv.org/pdf/2412.00131v1.pdf), cication: [**-1**](None) 

	 *Bin Lin, Yunyang Ge, Xinhua Cheng, ..., Yonghong Tian, Li Yuan* · ([Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan) - PKU-YuanGroup) ![Star](https://img.shields.io/github/stars/PKU-YuanGroup/Open-Sora-Plan.svg?style=social&label=Star)
- 🌟 **VideoGen-of-Thought: A Collaborative Framework for Multi-Shot Video 
  Generation**, `arXiv, 2412.02259`, [arxiv](http://arxiv.org/abs/2412.02259v1), [pdf](http://arxiv.org/pdf/2412.02259v1.pdf), cication: [**-1**](None) 

	 *Mingzhe Zheng, Yongqi Xu, Haojian Huang, ..., Harry Yang, Ser-Nam Lim* · ([cheliosoops.github](https://cheliosoops.github.io/VGoT))
- [**HunyuanVideo**](https://github.com/Tencent/HunyuanVideo) - Tencent ![Star](https://img.shields.io/github/stars/Tencent/HunyuanVideo.svg?style=social&label=Star) 

	 *A Systematic Framework For Large Video Generation Model Training* · ([HunyuanVideo](https://github.com/Tencent/HunyuanVideo/blob/main/assets/hunyuanvideo.pdf) - Tencent) ![Star](https://img.shields.io/github/stars/Tencent/HunyuanVideo.svg?style=social&label=Star)
- **Spatiotemporal Skip Guidance for Enhanced Video Diffusion Sampling**, `arXiv, 2411.18664`, [arxiv](http://arxiv.org/abs/2411.18664v1), [pdf](http://arxiv.org/pdf/2411.18664v1.pdf), cication: [**-1**](None) 

	 *Junha Hyung, Kinam Kim, Susung Hong, ..., Min-Jung Kim, Jaegul Choo* · ([junhahyung.github](https://junhahyung.github.io/STGuidance/)) · ([STGuidance](https://github.com/junhahyung/STGuidance) - junhahyung) ![Star](https://img.shields.io/github/stars/junhahyung/STGuidance.svg?style=social&label=Star)
- **Timestep Embedding Tells: It's Time to Cache for Video Diffusion Model**, `arXiv, 2411.19108`, [arxiv](http://arxiv.org/abs/2411.19108v1), [pdf](http://arxiv.org/pdf/2411.19108v1.pdf), cication: [**-1**](None) 

	 *Feng Liu, Shiwei Zhang, Xiaofeng Wang, ..., Qixiang Ye, Fang Wan* · ([liewfeng.github](https://liewfeng.github.io/TeaCache/)) · ([TeaCache](https://github.com/LiewFeng/TeaCache) - LiewFeng) ![Star](https://img.shields.io/github/stars/LiewFeng/TeaCache.svg?style=social&label=Star)
- **VideoRepair: Improving Text-to-Video Generation via Misalignment 
  Evaluation and Localized Refinement**, `arXiv, 2411.15115`, [arxiv](http://arxiv.org/abs/2411.15115v1), [pdf](http://arxiv.org/pdf/2411.15115v1.pdf), cication: [**-1**](None) 

	 *Daeun Lee, Jaehong Yoon, Jaemin Cho, ..., Mohit Bansal* · ([video-repair.github](https://video-repair.github.io/))
- **DreamRunner: Fine-Grained Storytelling Video Generation with 
  Retrieval-Augmented Motion Adaptation**, `arXiv, 2411.16657`, [arxiv](http://arxiv.org/abs/2411.16657v1), [pdf](http://arxiv.org/pdf/2411.16657v1.pdf), cication: [**-1**](None) 

	 *Zun Wang, Jialu Li, Han Lin, ..., Jaehong Yoon, Mohit Bansal* · ([dreamrunner-story2video.github](https://dreamrunner-story2video.github.io/))
- **AnchorCrafter: Animate CyberAnchors Saling Your Products via 
  Human-Object Interacting Video Generation**, `arXiv, 2411.17383`, [arxiv](http://arxiv.org/abs/2411.17383v1), [pdf](http://arxiv.org/pdf/2411.17383v1.pdf), cication: [**-1**](None) 

	 *Ziyi Xu, Ziyao Huang, Juan Cao, ..., Jintao Li, Fan Tang* · ([cangcz.github](https://cangcz.github.io/Anchor-Crafter/))
- 🌟 **Identity-Preserving Text-to-Video Generation by Frequency Decomposition**, `arXiv, 2411.17440`, [arxiv](http://arxiv.org/abs/2411.17440v1), [pdf](http://arxiv.org/pdf/2411.17440v1.pdf), cication: [**-1**](None) 

	 *Shenghai Yuan, Jinfa Huang, Xianyi He, ..., Jiebo Luo, Li Yuan* · ([arxiv](https://arxiv.org/abs/2411.17440)) · ([pku-yuangroup.github](https://pku-yuangroup.github.io/ConsisID/)) · ([ConsisID](https://github.com/PKU-YuanGroup/ConsisID) - PKU-YuanGroup) ![Star](https://img.shields.io/github/stars/PKU-YuanGroup/ConsisID.svg?style=social&label=Star)
- [**LTX-Video**](https://github.com/Lightricks/LTX-Video) - Lightricks ![Star](https://img.shields.io/github/stars/Lightricks/LTX-Video.svg?style=social&label=Star) 

	 · ([huggingface](https://huggingface.co/Lightricks/LTX-Video)) · ([𝕏](https://x.com/ltxstudio/status/1859964100203430280?s=46))
- [Pyramid Flow, a training-efficient Autoregressive Video Generation method based on Flow Matching.](https://huggingface.co/rain1011/pyramid-flow-miniflux)  🤗 

	 · ([pyramid-flow.github](https://pyramid-flow.github.io/)) · ([Pyramid-Flow](https://github.com/jy0205/Pyramid-Flow) - jy0205) ![Star](https://img.shields.io/github/stars/jy0205/Pyramid-Flow.svg?style=social&label=Star)
- 🌟 **Generative World Explorer**, `arXiv, 2411.11844`, [arxiv](http://arxiv.org/abs/2411.11844v2), [pdf](http://arxiv.org/pdf/2411.11844v2.pdf), cication: [**-1**](None) 

	 *Taiming Lu, Tianmin Shu, Alan Yuille, ..., Daniel Khashabi, Jieneng Chen* · ([generative-world-explorer.github](https://generative-world-explorer.github.io/)) · ([𝕏](https://x.com/jieneng_chen/status/1858754157697790210)) · ([youtube](https://www.youtube.com/watch?v=_1YMpI-oHWU&ab_channel=JienengChen))
- [The Matrix        Infinite-Horizon World Generation with Real-Time Interaction](https://thematrix1999.github.io/) 

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247760141&idx=4&sn=f6e815d57fcb6df68d7dfa2e9e7fedb0&chksm=e991229bca440619bccda5fdddf49c2ce501162db94bd203cdf32666ad56fc4318f5b1b0d8e7&scene=0&xtrack=1))
- [**lucid-v1**](https://github.com/SonicCodes/lucid-v1) - SonicCodes ![Star](https://img.shields.io/github/stars/SonicCodes/lucid-v1.svg?style=social&label=Star) 
- **Motion Control for Enhanced Complex Action Video Generation**, `arXiv, 2411.08328`, [arxiv](http://arxiv.org/abs/2411.08328v1), [pdf](http://arxiv.org/pdf/2411.08328v1.pdf), cication: [**-1**](None) 

	 *Qiang Zhou, Shaofeng Zhang, Nianzu Yang, ..., Ye Qian, Hao Li* · ([mvideo-v1.github](https://mvideo-v1.github.io/))
- **GameGen-X: Interactive Open-world Game Video Generation**, `arXiv, 2411.00769`, [arxiv](http://arxiv.org/abs/2411.00769v1), [pdf](http://arxiv.org/pdf/2411.00769v1.pdf), cication: [**-1**](None) 

	 *Haoxuan Che, Xuanhua He, Quande Liu, ..., Cheng Jin, Hao Chen* · ([GameGen-X](https://github.com/GameGen-X/GameGen-X) - GameGen-X) ![Star](https://img.shields.io/github/stars/GameGen-X/GameGen-X.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s/hAcDciiJ5oRB-9bIsYEt5w))
- **Adaptive Caching for Faster Video Generation with Diffusion Transformers**, `arXiv, 2411.02397`, [arxiv](http://arxiv.org/abs/2411.02397v2), [pdf](http://arxiv.org/pdf/2411.02397v2.pdf), cication: [**-1**](None) 

	 *Kumara Kahatapitiya, Haozhe Liu, Sen He, ..., Michael S. Ryoo, Tian Xie* · ([adacache-dit.github](https://adacache-dit.github.io/)) · ([AdaCache](https://github.com/AdaCache-DiT/AdaCache) - AdaCache-DiT) ![Star](https://img.shields.io/github/stars/AdaCache-DiT/AdaCache.svg?style=social&label=Star)
- [CogVideoX is an open-source video generation model originating from Qingying.](https://huggingface.co/THUDM/CogVideoX1.5-5B-SAT)  🤗 

	 · ([CogVideo](https://github.com/THUDM/CogVideo) - THUDM) ![Star](https://img.shields.io/github/stars/THUDM/CogVideo.svg?style=social&label=Star)
- **DimensionX: Create Any 3D and 4D Scenes from a Single Image with 
  Controllable Video Diffusion**, `arXiv, 2411.04928`, [arxiv](http://arxiv.org/abs/2411.04928v1), [pdf](http://arxiv.org/pdf/2411.04928v1.pdf), cication: [**-1**](None) 

	 *Wenqiang Sun, Shuo Chen, Fangfu Liu, ..., Jun Zhang, Yikai Wang* · ([chenshuo20.github](https://chenshuo20.github.io/DimensionX/)) · ([DimensionX](https://github.com/wenqsun/DimensionX) - wenqsun) ![Star](https://img.shields.io/github/stars/wenqsun/DimensionX.svg?style=social&label=Star)
- **Enhancing Motion in Text-to-Video Generation with Decomposed Encoding 
  and Conditioning**, `arXiv, 2410.24219`, [arxiv](http://arxiv.org/abs/2410.24219v1), [pdf](http://arxiv.org/pdf/2410.24219v1.pdf), cication: [**-1**](None)

	 *Penghui Ruan, Pichao Wang, Divya Saxena, ..., Jiannong Cao, Yuhui Shi* · ([pr-ryan.github](https://pr-ryan.github.io/DEMO-project/)) · ([DEMO](https://github.com/PR-Ryan/DEMO) - PR-Ryan) ![Star](https://img.shields.io/github/stars/PR-Ryan/DEMO.svg?style=social&label=Star)
- **FasterCache: Training-Free Video Diffusion Model Acceleration with High 
  Quality**, `arXiv, 2410.19355`, [arxiv](http://arxiv.org/abs/2410.19355v1), [pdf](http://arxiv.org/pdf/2410.19355v1.pdf), cication: [**-1**](None)

	 *Zhengyao Lv, Chenyang Si, Junhao Song, ..., Ziwei Liu, Kwan-Yee K. Wong* · ([FasterCache](https://github.com/Vchitect/FasterCache) - Vchitect) ![Star](https://img.shields.io/github/stars/Vchitect/FasterCache.svg?style=social&label=Star)
- **MarDini: Masked Autoregressive Diffusion for Video Generation at Scale**, `arXiv, 2410.20280`, [arxiv](http://arxiv.org/abs/2410.20280v1), [pdf](http://arxiv.org/pdf/2410.20280v1.pdf), cication: [**-1**](None) 

	 *Haozhe Liu, Shikun Liu, Zijian Zhou, ..., Jürgen Schmidhuber, Juan-Manuel Pérez-Rúa* · ([mardini-vidgen.github](https://mardini-vidgen.github.io/)- [Multi-Style Video Generation with Enhanced Effects](https://x.com/DigestDiff93383/status/1851175936944640384))
- **ARLON: Boosting Diffusion Transformers with Autoregressive Models for 
  Long Video Generation**, `arXiv, 2410.20502`, [arxiv](http://arxiv.org/abs/2410.20502v1), [pdf](http://arxiv.org/pdf/2410.20502v1.pdf), cication: [**-1**](None)

	 *Zongyi Li, Shujie Hu, Shujie Liu, ..., Hefei Ling, Furu Wei* · ([aka](http://aka.ms/arlon))
- **WorldSimBench: Towards Video Generation Models as World Simulators**, `arXiv, 2410.18072`, [arxiv](http://arxiv.org/abs/2410.18072v1), [pdf](http://arxiv.org/pdf/2410.18072v1.pdf), cication: [**-1**](None) 

	 *Yiran Qin, Zhelun Shi, Jiwen Yu, ..., Wanli Ouyang, Ruimao Zhang*

	 · ([iranqin.github](https://iranqin.github.io/WorldSimBench.github.io))
- [**Allegro**](https://github.com/rhymes-ai/Allegro) - rhymes-ai ![Star](https://img.shields.io/github/stars/rhymes-ai/Allegro.svg?style=social&label=Star) 
- [Allegro: Advanced Video Generation Model](https://huggingface.co/blog/RhymesAI/allegro)  🤗 
- [Open-Sora Plan](https://huggingface.co/LanguageBind/Open-Sora-Plan-v1.3.0)  🤗 
- [Introducing Mochi 1 preview. A new SOTA in open-source video generation. Apache 2.0.](https://x.com/genmoai/status/1848762405779574990)  𝕏 

	 · ([genmo](https://www.genmo.ai/play)) · ([models](https://github.com/genmoai/models) - genmoai) ![Star](https://img.shields.io/github/stars/genmoai/models.svg?style=social&label=Star)
- **Movie Gen: A Cast of Media Foundation Models**, `arXiv, 2410.13720`, [arxiv](http://arxiv.org/abs/2410.13720v1), [pdf](http://arxiv.org/pdf/2410.13720v1.pdf), cication: [**-1**](None) 

	 *Adam Polyak, Amit Zohar, Andrew Brown, ..., Vladan Petrovic, Yuming Du* · ([ai.meta](https://ai.meta.com/blog/movie-gen-media-foundation-models-generative-ai-video/))
- **VidPanos: Generative Panoramic Videos from Casual Panning Videos**, `arXiv, 2410.13832`, [arxiv](http://arxiv.org/abs/2410.13832v1), [pdf](http://arxiv.org/pdf/2410.13832v1.pdf), cication: [**-1**](None) 

	 *Jingwei Ma, Erika Lu, Roni Paiss, ..., Michael Rubinstein, Forrester Cole* · ([vidpanos.github](https://vidpanos.github.io/))

## Animation

- [An image-to-video model by CreateAI.](https://huggingface.co/IamCreateAI/Ruyi-Mini-7B)  🤗

	 · ([Ruyi-Models](https://github.com/IamCreateAI/Ruyi-Models) - IamCreateAI) ![Star](https://img.shields.io/github/stars/IamCreateAI/Ruyi-Models.svg?style=social&label=Star)
- **DreamDance: Animating Human Images by Enriching 3D Geometry Cues from 2D 
  Poses**, `arXiv, 2412.00397`, [arxiv](http://arxiv.org/abs/2412.00397v1), [pdf](http://arxiv.org/pdf/2412.00397v1.pdf), cication: [**-1**](None) 

	 *Yatian Pang, Bin Zhu, Bin Lin, ..., Harry Yang, Li Yuan*
- 🌟 **StableAnimator: High-Quality Identity-Preserving Human Image Animation**, `arXiv, 2411.17697`, [arxiv](http://arxiv.org/abs/2411.17697v2), [pdf](http://arxiv.org/pdf/2411.17697v2.pdf), cication: [**-1**](None) 

	 *Shuyuan Tu, Zhen Xing, Xintong Han, ..., Chong Luo, Zuxuan Wu* · ([StableAnimator](https://github.com/Francis-Rings/StableAnimator?tab=readme-ov-file) - Francis-Rings) ![Star](https://img.shields.io/github/stars/Francis-Rings/StableAnimator.svg?style=social&label=Star)
- **Trajectory Attention for Fine-grained Video Motion Control**, `arXiv, 2411.19324`, [arxiv](http://arxiv.org/abs/2411.19324v1), [pdf](http://arxiv.org/pdf/2411.19324v1.pdf), cication: [**-1**](None) 

	 *Zeqi Xiao, Wenqi Ouyang, Yifan Zhou, ..., Jianlou Si, Xingang Pan*
- **AnimateAnything: Consistent and Controllable Animation for Video 
  Generation**, `arXiv, 2411.10836`, [arxiv](http://arxiv.org/abs/2411.10836v1), [pdf](http://arxiv.org/pdf/2411.10836v1.pdf), cication: [**-1**](None) 

	 *Guojun Lei, Chi Wang, Hong Li, ..., Yikai Wang, Weiwei Xu* · ([yu-shaonian.github](https://yu-shaonian.github.io/Animate_Anything/))
- **FlipSketch: Flipping Static Drawings to Text-Guided Sketch Animations**, `arXiv, 2411.10818`, [arxiv](http://arxiv.org/abs/2411.10818v1), [pdf](http://arxiv.org/pdf/2411.10818v1.pdf), cication: [**-1**](None) 

	 *Hmrishav Bandyopadhyay, Yi-Zhe Song* · ([hmrishavbandy.github](https://hmrishavbandy.github.io/flipsketch-web/))
- [**EasyAnimate**](https://github.com/aigc-apps/EasyAnimate) - aigc-apps ![Star](https://img.shields.io/github/stars/aigc-apps/EasyAnimate.svg?style=social&label=Star) 
- **SG-I2V: Self-Guided Trajectory Control in Image-to-Video Generation**, `arXiv, 2411.04989`, [arxiv](http://arxiv.org/abs/2411.04989v1), [pdf](http://arxiv.org/pdf/2411.04989v1.pdf), cication: [**-1**](None) 

	 *Koichi Namekata, Sherwin Bahmani, Ziyi Wu, ..., Igor Gilitschenski, David B. Lindell* · ([kmcode1.github](https://kmcode1.github.io/Projects/SG-I2V/))
- **HelloMeme: Integrating Spatial Knitting Attentions to Embed High-Level 
  and Fidelity-Rich Conditions in Diffusion Models**, `arXiv, 2410.22901`, [arxiv](http://arxiv.org/abs/2410.22901v1), [pdf](http://arxiv.org/pdf/2410.22901v1.pdf), cication: [**-1**](None) 

	 *Shengkai Zhang, Nianhong Jiao, Tian Li, ..., Boya Niu, Jun Gao* · ([HelloMeme](https://github.com/HelloVision/HelloMeme) - HelloVision) ![Star](https://img.shields.io/github/stars/HelloVision/HelloMeme.svg?style=social&label=Star) · ([songkey.github](https://songkey.github.io/hellomeme/))
- **CamI2V: Camera-Controlled Image-to-Video Diffusion Model**, `arXiv, 2410.15957`, [arxiv](http://arxiv.org/abs/2410.15957v2), [pdf](http://arxiv.org/pdf/2410.15957v2.pdf), cication: [**-1**](None) 

	 *Guangcong Zheng, Teng Li, Rui Jiang, ..., Tao Wu, Xi Li* · ([zgctroy.github](https://zgctroy.github.io/CamI2V)) · ([CamI2V](https://github.com/ZGCTroy/CamI2V) - ZGCTroy) ![Star](https://img.shields.io/github/stars/ZGCTroy/CamI2V.svg?style=social&label=Star)
- [FrameBridge: Improving Image-to-Video  Generation with Bridge Models](https://framebridge-demo.github.io/) 
- **Animate-X: Universal Character Image Animation with Enhanced Motion 
  Representation**, `arXiv, 2410.10306`, [arxiv](http://arxiv.org/abs/2410.10306v1), [pdf](http://arxiv.org/pdf/2410.10306v1.pdf), cication: [**-1**](None)

	 *Shuai Tan, Biao Gong, Xiang Wang, ..., Jingdong Chen, Ming Yang* · ([lucaria-academy.github](https://lucaria-academy.github.io/Animate-X/))
- **DreamVideo-2: Zero-Shot Subject-Driven Video Customization with Precise 
  Motion Control**, `arXiv, 2410.13830`, [arxiv](http://arxiv.org/abs/2410.13830v1), [pdf](http://arxiv.org/pdf/2410.13830v1.pdf), cication: [**-1**](None)

	 *Yujie Wei, Shiwei Zhang, Hangjie Yuan, ..., Yingya Zhang, Hongming Shan* · ([dreamvideo2.github](https://dreamvideo2.github.io/))

## Evaluation

- 🌟 **Evaluation Agent: Efficient and Promptable Evaluation Framework for
  Visual Generative Models**, `arXiv, 2412.09645`, [arxiv](http://arxiv.org/abs/2412.09645v2), [pdf](http://arxiv.org/pdf/2412.09645v2.pdf), cication: [**-1**](None) 

	 *Fan Zhang, Shulin Tian, Ziqi Huang, ..., Yu Qiao, Ziwei Liu*
- **VBench++: Comprehensive and Versatile Benchmark Suite for Video 
  Generative Models**, `arXiv, 2411.13503`, [arxiv](http://arxiv.org/abs/2411.13503v1), [pdf](http://arxiv.org/pdf/2411.13503v1.pdf), cication: [**-1**](None) 

	 *Ziqi Huang, Fan Zhang, Xiaojie Xu, ..., Yu Qiao, Ziwei Liu* · ([huggingface](https://huggingface.co/spaces/Vchitect/VBench_Leaderboard))
- **How Far is Video Generation from World Model: A Physical Law Perspective**, `arXiv, 2411.02385`, [arxiv](http://arxiv.org/abs/2411.02385v1), [pdf](http://arxiv.org/pdf/2411.02385v1.pdf), cication: [**-1**](None) 

	 *Bingyi Kang, Yang Yue, Rui Lu, ..., Gao Huang, Jiashi Feng* · ([phyworld.github](https://phyworld.github.io/))
- [Artificial Analysis Video Generation Arena Leaderboard](https://artificialanalysis.ai/text-to-video/arena?tab=Leaderboard) 

## Detection

- **Video Seal: Open and Efficient Video Watermarking**, `arXiv, 2412.09492`, [arxiv](http://arxiv.org/abs/2412.09492v1), [pdf](http://arxiv.org/pdf/2412.09492v1.pdf), cication: [**-1**](None) 

	 *Pierre Fernandez, Hady Elsahar, I. Zeki Yalniz, ..., Alexandre Mourachko* · ([videoseal](https://github.com/facebookresearch/videoseal) - facebookresearch) ![Star](https://img.shields.io/github/stars/facebookresearch/videoseal.svg?style=social&label=Star)

## Alignment

- **LiFT: Leveraging Human Feedback for Text-to-Video Model Alignment**, `arXiv, 2412.04814`, [arxiv](http://arxiv.org/abs/2412.04814v1), [pdf](http://arxiv.org/pdf/2412.04814v1.pdf), cication: [**-1**](None) 

	 *Yibin Wang, Zhiyu Tan, Junyan Wang, ..., Cheng Jin, Hao Li* · ([codegoat24.github](https://codegoat24.github.io/LiFT)) · ([LiFT](https://github.com/CodeGoat24/LiFT) - CodeGoat24) ![Star](https://img.shields.io/github/stars/CodeGoat24/LiFT.svg?style=social&label=Star)

## Auto Regressive

- **From Slow Bidirectional to Fast Causal Video Generators**, `arXiv, 2412.07772`, [arxiv](http://arxiv.org/abs/2412.07772v1), [pdf](http://arxiv.org/pdf/2412.07772v1.pdf), cication: [**-1**](None) 

	 *Tianwei Yin, Qiang Zhang, Richard Zhang, ..., Eli Shechtman, Xun Huang* · ([causvid.github](https://causvid.github.io/))
- **Progressive Autoregressive Video Diffusion Models**, `arXiv, 2410.08151`, [arxiv](http://arxiv.org/abs/2410.08151v1), [pdf](http://arxiv.org/pdf/2410.08151v1.pdf), cication: [**-1**](None) 

	 *Desai Xie, Zhan Xu, Yicong Hong, ..., Arie Kaufman, Yang Zhou*

	 · ([desaixie.github](https://desaixie.github.io/pa-vdm/))

## Editting

- **MoViE: Mobile Diffusion for Video Editing**, `arXiv, 2412.06578`, [arxiv](http://arxiv.org/abs/2412.06578v1), [pdf](http://arxiv.org/pdf/2412.06578v1.pdf), cication: [**-1**](None) 

	 *Adil Karjauv, Noor Fathima, Ioannis Lelekas, ..., Amir Ghodrati, Amirhossein Habibian*
- **DIVE: Taming DINO for Subject-Driven Video Editing**, `arXiv, 2412.03347`, [arxiv](http://arxiv.org/abs/2412.03347v1), [pdf](http://arxiv.org/pdf/2412.03347v1.pdf), cication: [**-1**](None) 

	 *Yi Huang, Wei Xiong, He Zhang, ..., Mingfu Yan, Shifeng Chen* · ([dino-video-editing.github](https://dino-video-editing.github.io/))
- **MyTimeMachine: Personalized Facial Age Transformation**, `arXiv, 2411.14521`, [arxiv](http://arxiv.org/abs/2411.14521v1), [pdf](http://arxiv.org/pdf/2411.14521v1.pdf), cication: [**-1**](None) 

	 *Luchao Qi, Jiaye Wu, Bang Gong, ..., David W. Jacobs, Roni Sengupta* · ([mytimemachine.github](https://mytimemachine.github.io/))
- 🌟 [Generative Omnimatte            Learning to Decompose Video into Layers](https://gen-omnimatte.github.io/) 

	 · ([𝕏](https://x.com/jbhuang0604/status/1861490177912471965))
- **StableV2V: Stablizing Shape Consistency in Video-to-Video Editing**, `arXiv, 2411.11045`, [arxiv](http://arxiv.org/abs/2411.11045v1), [pdf](http://arxiv.org/pdf/2411.11045v1.pdf), cication: [**-1**](None) 

	 *Chang Liu, Rui Li, Kaidong Zhang, ..., Yunwei Lan, Dong Liu*
- [Fashion-VDM: Video Diffusion Model for Virtual Try-On](https://johannakarras.github.io/Fashion-VDM/) 
- **AutoVFX: Physically Realistic Video Editing from Natural Language 
  Instructions**, `arXiv, 2411.02394`, [arxiv](http://arxiv.org/abs/2411.02394v1), [pdf](http://arxiv.org/pdf/2411.02394v1.pdf), cication: [**-1**](None) 

	 *Hao-Yu Hsu, Zhi-Hao Lin, Albert Zhai, ..., Hongchi Xia, Shenlong Wang* · ([haoyuhsu.github](https://haoyuhsu.github.io/autovfx-website/)) · ([autovfx](https://github.com/haoyuhsu/autovfx) - haoyuhsu) ![Star](https://img.shields.io/github/stars/haoyuhsu/autovfx.svg?style=social&label=Star)
- 🌟 **ReCapture: Generative Video Camera Controls for User-Provided Videos 
  using Masked Video Fine-Tuning**, `arXiv, 2411.05003`, [arxiv](http://arxiv.org/abs/2411.05003v1), [pdf](http://arxiv.org/pdf/2411.05003v1.pdf), cication: [**-1**](None) 

	 *David Junhao Zhang, Roni Paiss, Shiran Zada, ..., Neal Wadhwa, Nataniel Ruiz* · ([generative-video-camera-controls.github](https://generative-video-camera-controls.github.io/))
- **Fashion-VDM: Video Diffusion Model for Virtual Try-On**, `arXiv, 2411.00225`, [arxiv](http://arxiv.org/abs/2411.00225v2), [pdf](http://arxiv.org/pdf/2411.00225v2.pdf), cication: [**-1**](None) 

	 *Johanna Karras, Yingwei Li, Nan Liu, ..., Chris Lee, Ira Kemelmacher-Shlizerman* · ([johannakarras.github](https://johannakarras.github.io/Fashion-VDM/)) · ([arxiv](https://arxiv.org/abs/2411.00225))
- [**InvokeAI**](https://github.com/invoke-ai/InvokeAI) - invoke-ai ![Star](https://img.shields.io/github/stars/invoke-ai/InvokeAI.svg?style=social&label=Star) 
- [**ComfyUI-MochiEdit**](https://github.com/logtd/ComfyUI-MochiEdit) - logtd ![Star](https://img.shields.io/github/stars/logtd/ComfyUI-MochiEdit.svg?style=social&label=Star) 
- **Framer: Interactive Frame Interpolation**, `arXiv, 2410.18978`, [arxiv](http://arxiv.org/abs/2410.18978v1), [pdf](http://arxiv.org/pdf/2410.18978v1.pdf), cication: [**-1**](None) 

	 *Wen Wang, Qiuyu Wang, Kecheng Zheng, ..., Yujun Shen, Chunhua Shen*

## Datasets

- **InstanceCap: Improving Text-to-Video Generation via Instance-aware
  Structured Caption**, `arXiv, 2412.09283`, [arxiv](http://arxiv.org/abs/2412.09283v1), [pdf](http://arxiv.org/pdf/2412.09283v1.pdf), cication: [**-1**](None) 

	 *Tiehan Fan, Kepan Nan, Rui Xie, ..., Jian Yang, Ying Tai* · ([InstanceCap](https://github.com/NJU-PCALab/InstanceCap) - NJU-PCALab) ![Star](https://img.shields.io/github/stars/NJU-PCALab/InstanceCap.svg?style=social&label=Star) · ([arxiv](https://arxiv.org/abs/2412.09283))
- **EgoVid-5M: A Large-Scale Video-Action Dataset for Egocentric Video 
  Generation**, `arXiv, 2411.08380`, [arxiv](http://arxiv.org/abs/2411.08380v1), [pdf](http://arxiv.org/pdf/2411.08380v1.pdf), cication: [**-1**](None) 

	 *Xiaofeng Wang, Kang Zhao, Feng Liu, ..., Yingya Zhang, Xingang Wang* · ([egovid.github](https://egovid.github.io/))
- **TIP-I2V: A Million-Scale Real Text and Image Prompt Dataset for 
  Image-to-Video Generation**, `arXiv, 2411.04709`, [arxiv](http://arxiv.org/abs/2411.04709v1), [pdf](http://arxiv.org/pdf/2411.04709v1.pdf), cication: [**-1**](None) 

	 *Wenhao Wang, Yi Yang* · ([tip-i2v.github.io](https://tip-i2v.github.io.))

## Toolkits

- [**cogvideox-factory**](https://github.com/a-r-r-o-w/cogvideox-factory) - a-r-r-o-w ![Star](https://img.shields.io/github/stars/a-r-r-o-w/cogvideox-factory.svg?style=social&label=Star) 

## Tutorials


## Blog


## Products

- [State-of-the-art video and image generation with Veo 2 and Imagen 3](https://blog.google/technology/google-labs/video-image-generation-update-december-2024/) 
- [Sora System Card](https://openai.com/index/sora-system-card/) 
- [Introducing Wonder Animation:  New AI solution for animated films, powered by cutting-edge Video to 3D Scene technology](https://adsknews.autodesk.com/en/news/autodesk-launches-wonder-animation-video-to-3d-scene-technology/) 

	 · ([reddit](https://www.reddit.com/r/singularity/comments/1gfrmvt/wonder_animation_transform_any_video_into_a_3d/))
- [Advanced Camera Control' feature for its AI video generation model](https://x.com/adcock_brett/status/1853120761369608517)  𝕏 
- [Runway introduced Act-One, a new AI system that generates expressive character animations from a single video and image.](https://x.com/adcock_brett/status/1850569033776496696)  𝕏 
- [Haiper launched version 2 of its video generation platform](https://x.com/adcock_brett/status/1850569170892546282)  𝕏 

## Misc

- [Install CogVideoX: Text-to-Video and Image-to-Video (ComfyUI)](https://www.stablediffusiontutorials.com/2024/08/cogvideox.html) 
- [**ComfyUI-CogVideoXWrapper**](https://github.com/kijai/ComfyUI-CogVideoXWrapper) - kijai ![Star](https://img.shields.io/github/stars/kijai/ComfyUI-CogVideoXWrapper.svg?style=social&label=Star) 
- [optimized support for Genmo’s latest model and can run it fast on a GPU like 4090](https://x.com/ComfyUI/status/1853838184012251317)  𝕏 

	 · ([blog.comfy](https://blog.comfy.org/mochi-1/))
- [**ComfyUI-MochiWrapper**](https://github.com/kijai/ComfyUI-MochiWrapper) - kijai ![Star](https://img.shields.io/github/stars/kijai/ComfyUI-MochiWrapper.svg?style=social&label=Star) 