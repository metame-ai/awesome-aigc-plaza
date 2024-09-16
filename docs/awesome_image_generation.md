# Awesome Image Generation

- [Awesome Image Generation](#awesome-image-generation)
	- [Survey](#survey)
	- [Generation](#generation)
	- [Control Generation](#control-generation)
	- [Efficiency](#efficiency)
	- [Editting](#editting)
	- [Architecture](#architecture)
	- [DiT](#dit)
	- [Text Rendering](#text-rendering)
	- [Personlazation](#personlazation)
	- [Super Resolution](#super-resolution)
	- [Try-On](#try-on)
	- [Projects](#projects)
	- [Optimization](#optimization)
	- [Toolkits](#toolkits)
	- [Evaluation](#evaluation)
	- [Products](#products)
	- [Tutorials](#tutorials)


## Survey
- **A Survey of Multimodal-Guided Image Editing with Text-to-Image Diffusion
  Models**, `arXiv, 2406.14555`, [arxiv](http://arxiv.org/abs/2406.14555v1), [pdf](http://arxiv.org/pdf/2406.14555v1.pdf), cication: [**-1**](None)

	 *Xincheng Shuai, Henghui Ding, Xingjun Ma, Rongcheng Tu, Yu-Gang Jiang, Dacheng Tao* · ([awesome-image-editing](https://github.com/xinchengshuai/awesome-image-editing) - xinchengshuai) ![Star](https://img.shields.io/github/stars/xinchengshuai/awesome-image-editing.svg?style=social&label=Star)
- **A Survey on Personalized Content Synthesis with Diffusion Models**, `arXiv, 2405.05538`, [arxiv](http://arxiv.org/abs/2405.05538v1), [pdf](http://arxiv.org/pdf/2405.05538v1.pdf), cication: [**-1**](None)

	 *Xulu Zhang, Xiao-Yong Wei, Wengyu Zhang, Jinlin Wu, Zhaoxiang Zhang, Zhen Lei, Qing Li*
- **Evaluating Text to Image Synthesis: Survey and Taxonomy of Image Quality
  Metrics**, `arXiv, 2403.11821`, [arxiv](http://arxiv.org/abs/2403.11821v1), [pdf](http://arxiv.org/pdf/2403.11821v1.pdf), cication: [**-1**](None)

	 *Sebastian Hartwig, Dominik Engel, Leon Sick, Hannah Kniesel, Tristan Payer, Poonam, Timo Ropinski*
- **Controllable Generation with Text-to-Image Diffusion Models: A Survey**, `arXiv, 2403.04279`, [arxiv](http://arxiv.org/abs/2403.04279v1), [pdf](http://arxiv.org/pdf/2403.04279v1.pdf), cication: [**-1**](None)

	 *Pu Cao, Feng Zhou, Qing Song, Lu Yang* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652456111&idx=4&sn=339d003cda8189697856b7e03d19618c)) · ([Awesome-Controllable-T2I-Diffusion-Models](https://github.com/PRIV-Creation/Awesome-Controllable-T2I-Diffusion-Models) - PRIV-Creation) ![Star](https://img.shields.io/github/stars/PRIV-Creation/Awesome-Controllable-T2I-Diffusion-Models.svg?style=social&label=Star)

## Tokenization
- **Language Model Beats Diffusion -- Tokenizer is Key to Visual Generation**, `arXiv, 2310.05737`, [arxiv](http://arxiv.org/abs/2310.05737v3), [pdf](http://arxiv.org/pdf/2310.05737v3.pdf), cication: [**41**](https://scholar.google.com/scholar?cites=10816486597646660868&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Lijun Yu, José Lezama, Nitesh B. Gundavarapu, Luca Versari, Kihyuk Sohn, David Minnen, Yong Cheng, Vighnesh Birodkar, Agrim Gupta, Xiuye Gu* · ([Open-MAGVIT2](https://github.com/TencentARC/Open-MAGVIT2?tab=readme-ov-file) - TencentARC) ![Star](https://img.shields.io/github/stars/TencentARC/Open-MAGVIT2.svg?style=social&label=Star)

## Generation
- **JPEG-LM: LLMs as Image Generators with Canonical Codec Representations**, `arXiv, 2408.08459`, [arxiv](http://arxiv.org/abs/2408.08459v1), [pdf](http://arxiv.org/pdf/2408.08459v1.pdf), cication: [**-1**](None)

	 *Xiaochuang Han, Marjan Ghazvininejad, Pang Wei Koh, Yulia Tsvetkov*
- **Imagen 3**, `arXiv, 2408.07009`, [arxiv](http://arxiv.org/abs/2408.07009v1), [pdf](http://arxiv.org/pdf/2408.07009v1.pdf), cication: [**-1**](None)

	 *Imagen-Team-Google, :, Jason Baldridge, Jakob Bauer, Mukul Bhutani, Nicole Brichtova, Andrew Bunner, Kelvin Chan, Yichang Chen, Sander Dieleman*
- **Stretching Each Dollar: Diffusion Training from Scratch on a
  Micro-Budget**, `arXiv, 2407.15811`, [arxiv](http://arxiv.org/abs/2407.15811v1), [pdf](http://arxiv.org/pdf/2407.15811v1.pdf), cication: [**-1**](None)

	 *Vikash Sehwag, Xianghao Kong, Jingtao Li, Michael Spranger, Lingjuan Lyu*
- **Lumina-mGPT: Illuminate Flexible Photorealistic Text-to-Image Generation
  with Multimodal Generative Pretraining**, `arXiv, 2408.02657`, [arxiv](http://arxiv.org/abs/2408.02657v1), [pdf](http://arxiv.org/pdf/2408.02657v1.pdf), cication: [**-1**](None)

	 *Dongyang Liu, Shitian Zhao, Le Zhuo, Weifeng Lin, Yu Qiao, Hongsheng Li, Peng Gao* · ([Lumina-mGPT](https://github.com/Alpha-VLLM/Lumina-mGPT) - Alpha-VLLM) ![Star](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-mGPT.svg?style=social&label=Star)
- [**flux**](https://github.com/black-forest-labs/flux) - black-forest-labs ![Star](https://img.shields.io/github/stars/black-forest-labs/flux.svg?style=social&label=Star)

	 *Official inference repo for FLUX.1 models*
- **Wavelets Are All You Need for Autoregressive Image Generation**, `arXiv, 2406.19997`, [arxiv](http://arxiv.org/abs/2406.19997v1), [pdf](http://arxiv.org/pdf/2406.19997v1.pdf), cication: [**-1**](None)

	 *Wael Mattar, Idan Levy, Nir Sharon, Shai Dekel*
- [**Kolors**](https://github.com/Kwai-Kolors/Kolors?tab=readme-ov-file) - Kwai-Kolors ![Star](https://img.shields.io/github/stars/Kwai-Kolors/Kolors.svg?style=social&label=Star)

	 *Kolors Team*
- **Exploring the Role of Large Language Models in Prompt Encoding for
  Diffusion Models**, `arXiv, 2406.11831`, [arxiv](http://arxiv.org/abs/2406.11831v2), [pdf](http://arxiv.org/pdf/2406.11831v2.pdf), cication: [**-1**](None)

	 *Bingqi Ma, Zhuofan Zong, Guanglu Song, Hongsheng Li, Yu Liu*
- **Autoregressive Image Generation without Vector Quantization**, `arXiv, 2406.11838`, [arxiv](http://arxiv.org/abs/2406.11838v1), [pdf](http://arxiv.org/pdf/2406.11838v1.pdf), cication: [**-1**](None)

	 *Tianhong Li, Yonglong Tian, He Li, Mingyang Deng, Kaiming He*
- **An Image is Worth 32 Tokens for Reconstruction and Generation**, `arXiv, 2406.07550`, [arxiv](http://arxiv.org/abs/2406.07550v1), [pdf](http://arxiv.org/pdf/2406.07550v1.pdf), cication: [**-1**](None)

	 *Qihang Yu, Mark Weber, Xueqing Deng, Xiaohui Shen, Daniel Cremers, Liang-Chieh Chen* · ([yucornetto.github](https://yucornetto.github.io/projects/titok.html))

	 · ([1d-tokenizer](https://github.com/bytedance/1d-tokenizer) - bytedance) ![Star](https://img.shields.io/github/stars/bytedance/1d-tokenizer.svg?style=social&label=Star)
- **Unified Text-to-Image Generation and Retrieval**, `arXiv, 2406.05814`, [arxiv](http://arxiv.org/abs/2406.05814v1), [pdf](http://arxiv.org/pdf/2406.05814v1.pdf), cication: [**-1**](None)

	 *Leigang Qu, Haochuan Li, Tan Wang, Wenjie Wang, Yongqi Li, Liqiang Nie, Tat-Seng Chua*
- **Autoregressive Model Beats Diffusion: Llama for Scalable Image
  Generation**, `arXiv, 2406.06525`, [arxiv](http://arxiv.org/abs/2406.06525v1), [pdf](http://arxiv.org/pdf/2406.06525v1.pdf), cication: [**-1**](None)

	 *Peize Sun, Yi Jiang, Shoufa Chen, Shilong Zhang, Bingyue Peng, Ping Luo, Zehuan Yuan* · ([LlamaGen](https://github.com/FoundationVision/LlamaGen) - FoundationVision) ![Star](https://img.shields.io/github/stars/FoundationVision/LlamaGen.svg?style=social&label=Star)
- **Greedy Growing Enables High-Resolution Pixel-Based Diffusion Models**, `arXiv, 2405.16759`, [arxiv](http://arxiv.org/abs/2405.16759v1), [pdf](http://arxiv.org/pdf/2405.16759v1.pdf), cication: [**-1**](None)

	 *Cristina N. Vasconcelos, Abdullah Rashwan Austin Waters, Trevor Walker, Keyang Xu, Jimmy Yan, Rui Qian, Shixin Luo, Zarana Parekh, Andrew Bunner, Hongliang Fei*
- **Hunyuan-DiT: A Powerful Multi-Resolution Diffusion Transformer with
  Fine-Grained Chinese Understanding**, `arXiv, 2405.08748`, [arxiv](http://arxiv.org/abs/2405.08748v1), [pdf](http://arxiv.org/pdf/2405.08748v1.pdf), cication: [**-1**](None)

	 *Zhimin Li, Jianwei Zhang, Qin Lin, Jiangfeng Xiong, Yanxin Long, Xinchi Deng, Yingfang Zhang, Xingchao Liu, Minbin Huang, Zedong Xiao*
	- github.com/Tencent/HunyuanDiT
- **CoMat: Aligning Text-to-Image Diffusion Model with Image-to-Text Concept
  Matching**, `arXiv, 2404.03653`, [arxiv](http://arxiv.org/abs/2404.03653v1), [pdf](http://arxiv.org/pdf/2404.03653v1.pdf), cication: [**-1**](None)

	 *Dongzhi Jiang, Guanglu Song, Xiaoshi Wu, Renrui Zhang, Dazhong Shen, Zhuofan Zong, Yu Liu, Hongsheng Li* · ([CoMat](https://github.com/CaraJ7/CoMat) - CaraJ7) ![Star](https://img.shields.io/github/stars/CaraJ7/CoMat.svg?style=social&label=Star)
- **Visual Autoregressive Modeling: Scalable Image Generation via Next-Scale
  Prediction**, `arXiv, 2404.02905`, [arxiv](http://arxiv.org/abs/2404.02905v1), [pdf](http://arxiv.org/pdf/2404.02905v1.pdf), cication: [**-1**](None)

	 *Keyu Tian, Yi Jiang, Zehuan Yuan, Bingyue Peng, Liwei Wang* · ([VAR](https://github.com/FoundationVision/VAR) - FoundationVision) ![Star](https://img.shields.io/github/stars/FoundationVision/VAR.svg?style=social&label=Star)
- **Scaling Rectified Flow Transformers for High-Resolution Image Synthesis**, `arXiv, 2403.03206`, [arxiv](http://arxiv.org/abs/2403.03206v1), [pdf](http://arxiv.org/pdf/2403.03206v1.pdf), cication: [**-1**](None)

	 *Patrick Esser, Sumith Kulal, Andreas Blattmann, Rahim Entezari, Jonas Müller, Harry Saini, Yam Levi, Dominik Lorenz, Axel Sauer, Frederic Boesel*
	- `This work enhances rectified flow models for high-resolution text-to-image synthesis by improving noise sampling and introducing a novel transformer-based architecture that enhances text comprehension and image quality, showing better performance through extensive evaluation and human preference ratings.`

	 · ([stability](https://stability.ai/news/stable-diffusion-3-research-paper)) · ([huggingface](https://huggingface.co/stabilityai/stable-diffusion-3-medium)) · ([huggingface](https://huggingface.co/blog/sd3))
- **CosmicMan: A Text-to-Image Foundation Model for Humans**, `arXiv, 2404.01294`, [arxiv](http://arxiv.org/abs/2404.01294v1), [pdf](http://arxiv.org/pdf/2404.01294v1.pdf), cication: [**-1**](None)

	 *Shikai Li, Jianglin Fu, Kaiyuan Liu, Wentao Wang, Kwan-Yee Lin, Wayne Wu* · ([CosmicMan](https://github.com/cosmicman-cvpr2024/CosmicMan/blob/main) - cosmicman-cvpr2024) ![Star](https://img.shields.io/github/stars/cosmicman-cvpr2024/CosmicMan.svg?style=social&label=Star) · ([cosmicman-cvpr2024.github](https://cosmicman-cvpr2024.github.io/))
- **ELLA: Equip Diffusion Models with LLM for Enhanced Semantic Alignment**, `arXiv, 2403.05135`, [arxiv](http://arxiv.org/abs/2403.05135v1), [pdf](http://arxiv.org/pdf/2403.05135v1.pdf), cication: [**-1**](None)

	 *Xiwei Hu, Rui Wang, Yixiao Fang, Bin Fu, Pei Cheng, Gang Yu*

	 · ([ELLA](https://github.com/TencentQQGYLab/ELLA) - TencentQQGYLab) ![Star](https://img.shields.io/github/stars/TencentQQGYLab/ELLA.svg?style=social&label=Star)
- **CogView3: Finer and Faster Text-to-Image Generation via Relay Diffusion**, `arXiv, 2403.05121`, [arxiv](http://arxiv.org/abs/2403.05121v1), [pdf](http://arxiv.org/pdf/2403.05121v1.pdf), cication: [**-1**](None)

	 *Wendi Zheng, Jiayan Teng, Zhuoyi Yang, Weihan Wang, Jidong Chen, Xiaotao Gu, Yuxiao Dong, Ming Ding, Jie Tang*

## Control Generation
- **One-Shot Diffusion Mimicker for Handwritten Text Generation**, `arXiv, 2409.04004`, [arxiv](http://arxiv.org/abs/2409.04004v2), [pdf](http://arxiv.org/pdf/2409.04004v2.pdf), cication: [**-1**](None)

	 *Gang Dai, Yifan Zhang, Quhui Ke, Qiangya Guo, Shuangping Huang* · ([one-dm](https://github.com/dailenson/one-dm) - dailenson) ![Star](https://img.shields.io/github/stars/dailenson/one-dm.svg?style=social&label=Star)
- [**style-tokenizer**](https://github.com/alipay/style-tokenizer/blob/master) - alipay ![Star](https://img.shields.io/github/stars/alipay/style-tokenizer.svg?style=social&label=Star)
- **IFAdapter: Instance Feature Control for Grounded Text-to-Image
  Generation**, `arXiv, 2409.08240`, [arxiv](http://arxiv.org/abs/2409.08240v1), [pdf](http://arxiv.org/pdf/2409.08240v1.pdf), cication: [**-1**](None)

	 *Yinwei Wu, Xianpan Zhou, Bing Ma, Xuefeng Su, Kai Ma, Xinchao Wang*
- **CSGO: Content-Style Composition in Text-to-Image Generation**, `arXiv, 2408.16766`, [arxiv](http://arxiv.org/abs/2408.16766v2), [pdf](http://arxiv.org/pdf/2408.16766v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=15536153885122697551&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Peng Xing, Haofan Wang, Yanpeng Sun, Qixun Wang, Xu Bai, Hao Ai, Renyuan Huang, Zechao Li* · ([csgo-gen.github](https://csgo-gen.github.io/)) · ([CSGO](https://github.com/instantX-research/CSGO) - instantX-research) ![Star](https://img.shields.io/github/stars/instantX-research/CSGO.svg?style=social&label=Star)
- **Draw Like an Artist: Complex Scene Generation with Diffusion Model via
  Composition, Painting, and Retouching**, `arXiv, 2408.13858`, [arxiv](http://arxiv.org/abs/2408.13858v1), [pdf](http://arxiv.org/pdf/2408.13858v1.pdf), cication: [**-1**](None)

	 *Minghao Liu, Le Zhang, Yingjie Tian, Xiaochao Qu, Luoqi Liu, Ting Liu*
- **What Do You Want? User-centric Prompt Generation for Text-to-image
  Synthesis via Multi-turn Guidance**, `arXiv, 2408.12910`, [arxiv](http://arxiv.org/abs/2408.12910v1), [pdf](http://arxiv.org/pdf/2408.12910v1.pdf), cication: [**-1**](None)

	 *Yilun Liu, Minggui He, Feiyu Yao, Yuhe Ji, Shimin Tao, Jingzhou Du, Duan Li, Jian Gao, Li Zhang, Hao Yang*
- **MUSES: 3D-Controllable Image Generation via Multi-Modal Agent
  Collaboration**, `arXiv, 2408.10605`, [arxiv](http://arxiv.org/abs/2408.10605v2), [pdf](http://arxiv.org/pdf/2408.10605v2.pdf), cication: [**-1**](None)

	 *Yanbo Ding, Shaobin Zhuang, Kunchang Li, Zhengrong Yue, Yu Qiao, Yali Wang*
- **Generative Photomontage**, `arXiv, 2408.07116`, [arxiv](http://arxiv.org/abs/2408.07116v2), [pdf](http://arxiv.org/pdf/2408.07116v2.pdf), cication: [**-1**](None)

	 *Sean J. Liu, Nupur Kumari, Ariel Shamir, Jun-Yan Zhu* · ([lseancs.github](https://lseancs.github.io/generativephotomontage/))
- **TraDiffusion: Trajectory-Based Training-Free Image Generation**, `arXiv, 2408.09739`, [arxiv](http://arxiv.org/abs/2408.09739v1), [pdf](http://arxiv.org/pdf/2408.09739v1.pdf), cication: [**-1**](None)

	 *Mingrui Wu, Oucheng Huang, Jiayi Ji, Jiale Li, Xinyue Cai, Huafeng Kuang, Jianzhuang Liu, Xiaoshuai Sun, Rongrong Ji* · ([TraDiffusion](https://github.com/och-mac/TraDiffusion) - och-mac) ![Star](https://img.shields.io/github/stars/och-mac/TraDiffusion.svg?style=social&label=Star)
- **ControlNeXt: Powerful and Efficient Control for Image and Video
  Generation**, `arXiv, 2408.06070`, [arxiv](http://arxiv.org/abs/2408.06070v1), [pdf](http://arxiv.org/pdf/2408.06070v1.pdf), cication: [**-1**](None)

	 *Bohao Peng, Jian Wang, Yuechen Zhang, Wenbo Li, Ming-Chang Yang, Jiaya Jia* · ([ControlNeXt](https://github.com/dvlab-research/ControlNeXt) - dvlab-research) ![Star](https://img.shields.io/github/stars/dvlab-research/ControlNeXt.svg?style=social&label=Star) · ([pbihao.github](https://pbihao.github.io/projects/controlnext/index.html))
- **Sketch2Scene: Automatic Generation of Interactive 3D Game Scenes from
  User's Casual Sketches**, `arXiv, 2408.04567`, [arxiv](http://arxiv.org/abs/2408.04567v1), [pdf](http://arxiv.org/pdf/2408.04567v1.pdf), cication: [**-1**](None)

	 *Yongzhi Xu, Yonhon Ng, Yifu Wang, Inkyu Sa, Yunfei Duan, Yang Li, Pan Ji, Hongdong Li* · ([xrvisionlabs.github](https://xrvisionlabs.github.io/Sketch2Scene/))
- **ReCorD: Reasoning and Correcting Diffusion for HOI Generation**, `arXiv, 2407.17911`, [arxiv](http://arxiv.org/abs/2407.17911v1), [pdf](http://arxiv.org/pdf/2407.17911v1.pdf), cication: [**-1**](None)

	 *Jian-Yu Jiang-Lin, Kang-Yang Huang, Ling Lo, Yi-Ning Huang, Terence Lin, Jhih-Ciang Wu, Hong-Han Shuai, Wen-Huang Cheng*
- [**ControlNetPlus**](https://github.com/xinsir6/ControlNetPlus) - xinsir6 ![Star](https://img.shields.io/github/stars/xinsir6/ControlNetPlus.svg?style=social&label=Star)

	 *ControlNet++: All-in-one ControlNet for image generations and editing!* · ([huggingface](https://huggingface.co/xinsir/controlnet-union-sdxl-1.0))
- **Ada-adapter:Fast Few-shot Style Personlization of Diffusion Model with
  Pre-trained Image Encoder**, `arXiv, 2407.05552`, [arxiv](http://arxiv.org/abs/2407.05552v1), [pdf](http://arxiv.org/pdf/2407.05552v1.pdf), cication: [**-1**](None)

	 *Jia Liu, Changlin Li, Qirui Sun, Jiahui Ming, Chen Fang, Jue Wang, Bing Zeng, Shuaicheng Liu*
- **Sketch-Guided Scene Image Generation**, `arXiv, 2407.06469`, [arxiv](http://arxiv.org/abs/2407.06469v1), [pdf](http://arxiv.org/pdf/2407.06469v1.pdf), cication: [**-1**](None)

	 *Tianyu Zhang, Xiaoxuan Xie, Xusheng Du, Haoran Xie*
- **SEED-Story: Multimodal Long Story Generation with Large Language Model**, `arXiv, 2407.08683`, [arxiv](http://arxiv.org/abs/2407.08683v1), [pdf](http://arxiv.org/pdf/2407.08683v1.pdf), cication: [**-1**](None)

	 *Shuai Yang, Yuying Ge, Yang Li, Yukang Chen, Yixiao Ge, Ying Shan, Yingcong Chen* · ([SEED-Story](https://github.com/TencentARC/SEED-Story) - TencentARC) ![Star](https://img.shields.io/github/stars/TencentARC/SEED-Story.svg?style=social&label=Star)
- **Magic Insert: Style-Aware Drag-and-Drop**, `arXiv, 2407.02489`, [arxiv](http://arxiv.org/abs/2407.02489v1), [pdf](http://arxiv.org/pdf/2407.02489v1.pdf), cication: [**-1**](None)

	 *Nataniel Ruiz, Yuanzhen Li, Neal Wadhwa, Yael Pritch, Michael Rubinstein, David E. Jacobs, Shlomi Fruchter*
- **InstantStyle-Plus: Style Transfer with Content-Preserving in
  Text-to-Image Generation**, `arXiv, 2407.00788`, [arxiv](http://arxiv.org/abs/2407.00788v1), [pdf](http://arxiv.org/pdf/2407.00788v1.pdf), cication: [**-1**](None)

	 *Haofan Wang, Peng Xing, Renyuan Huang, Hao Ai, Qixun Wang, Xu Bai*
- **AnyControl: Create Your Artwork with Versatile Control on Text-to-Image
  Generation**, `arXiv, 2406.18958`, [arxiv](http://arxiv.org/abs/2406.18958v2), [pdf](http://arxiv.org/pdf/2406.18958v2.pdf), cication: [**-1**](None)

	 *Yanan Sun, Yanchen Liu, Yinhao Tang, Wenjie Pei, Kai Chen*

	 · ([any-control.github](https://any-control.github.io/)) · ([AnyControl](https://github.com/open-mmlab/AnyControl) - open-mmlab) ![Star](https://img.shields.io/github/stars/open-mmlab/AnyControl.svg?style=social&label=Star)
- **Stylebreeder: Exploring and Democratizing Artistic Styles through
  Text-to-Image Models**, `arXiv, 2406.14599`, [arxiv](http://arxiv.org/abs/2406.14599v1), [pdf](http://arxiv.org/pdf/2406.14599v1.pdf), cication: [**-1**](None)

	 *Matthew Zheng, Enis Simsar, Hidir Yesiltepe, Federico Tombari, Joel Simon, Pinar Yanardag* · ([stylebreeder.github](https://stylebreeder.github.io/))
	- 
- **Make It Count: Text-to-Image Generation with an Accurate Number of
  Objects**, `arXiv, 2406.10210`, [arxiv](http://arxiv.org/abs/2406.10210v1), [pdf](http://arxiv.org/pdf/2406.10210v1.pdf), cication: [**-1**](None)

	 *Lital Binyamin, Yoad Tewel, Hilit Segev, Eran Hirsch, Royi Rassin, Gal Chechik*
- **EMMA: Your Text-to-Image Diffusion Model Can Secretly Accept Multi-Modal
  Prompts**, `arXiv, 2406.09162`, [arxiv](http://arxiv.org/abs/2406.09162v1), [pdf](http://arxiv.org/pdf/2406.09162v1.pdf), cication: [**-1**](None)

	 *Yucheng Han, Rui Wang, Chi Zhang, Juntao Hu, Pei Cheng, Bin Fu, Hanwang Zhang*
- **Kaleido Diffusion: Improving Conditional Diffusion Models with
  Autoregressive Latent Modeling**, `arXiv, 2405.21048`, [arxiv](http://arxiv.org/abs/2405.21048v1), [pdf](http://arxiv.org/pdf/2405.21048v1.pdf), cication: [**-1**](None)

	 *Jiatao Gu, Ying Shen, Shuangfei Zhai, Yizhe Zhang, Navdeep Jaitly, Joshua M. Susskind*
- [**Omost**](https://github.com/lllyasviel/Omost) - lllyasviel ![Star](https://img.shields.io/github/stars/lllyasviel/Omost.svg?style=social&label=Star)

	 *Your image is almost there!*
- **Kaleido Diffusion: Improving Conditional Diffusion Models with
  Autoregressive Latent Modeling**, `arXiv, 2405.21048`, [arxiv](http://arxiv.org/abs/2405.21048v1), [pdf](http://arxiv.org/pdf/2405.21048v1.pdf), cication: [**-1**](None)

	 *Jiatao Gu, Ying Shen, Shuangfei Zhai, Yizhe Zhang, Navdeep Jaitly, Joshua M. Susskind*
- **Compositional Text-to-Image Generation with Dense Blob Representations**, `arXiv, 2405.08246`, [arxiv](http://arxiv.org/abs/2405.08246v1), [pdf](http://arxiv.org/pdf/2405.08246v1.pdf), cication: [**-1**](None)

	 *Weili Nie, Sifei Liu, Morteza Mardani, Chao Liu, Benjamin Eckart, Arash Vahdat* · ([blobgen-2d.github](https://blobgen-2d.github.io))
- [**IC-Light**](https://github.com/lllyasviel/IC-Light) - lllyasviel ![Star](https://img.shields.io/github/stars/lllyasviel/IC-Light.svg?style=social&label=Star)

	 *More relighting!* · ([huggingface](https://huggingface.co/spaces/lllyasviel/IC-Light))
- [**MistoLine**](https://github.com/TheMistoAI/MistoLine) - TheMistoAI ![Star](https://img.shields.io/github/stars/TheMistoAI/MistoLine.svg?style=social&label=Star)

	 *A Versatile and Robust SDXL-ControlNet Model for Adaptable Line Art Conditioning* · ([huggingface](https://huggingface.co/TheMistoAI/MistoLine))
- **From Parts to Whole: A Unified Reference Framework for Controllable
  Human Image Generation**, `arXiv, 2404.15267`, [arxiv](http://arxiv.org/abs/2404.15267v1), [pdf](http://arxiv.org/pdf/2404.15267v1.pdf), cication: [**-1**](None)

	 *Zehuan Huang, Hongxing Fan, Lipeng Wang, Lu Sheng* · ([huanngzh.github](https://huanngzh.github.io/Parts2Whole/)) · ([Parts2Whole](https://github.com/huanngzh/Parts2Whole) - huanngzh) ![Star](https://img.shields.io/github/stars/huanngzh/Parts2Whole.svg?style=social&label=Star)
- **Graphic Design with Large Multimodal Model**, `arXiv, 2404.14368`, [arxiv](http://arxiv.org/abs/2404.14368v1), [pdf](http://arxiv.org/pdf/2404.14368v1.pdf), cication: [**-1**](None)

	 *Yutao Cheng, Zhao Zhang, Maoke Yang, Hui Nie, Chunyuan Li, Xinglong Wu, Jie Shao* · ([graphist](https://github.com/graphic-design-ai/graphist) - graphic-design-ai) ![Star](https://img.shields.io/github/stars/graphic-design-ai/graphist.svg?style=social&label=Star)
- **Ctrl-Adapter: An Efficient and Versatile Framework for Adapting Diverse
  Controls to Any Diffusion Model**, `arXiv, 2404.09967`, [arxiv](http://arxiv.org/abs/2404.09967v1), [pdf](http://arxiv.org/pdf/2404.09967v1.pdf), cication: [**-1**](None)

	 *Han Lin, Jaemin Cho, Abhay Zala, Mohit Bansal*
- **ControlNet++: Improving Conditional Controls with Efficient Consistency
  Feedback**, `arXiv, 2404.07987`, [arxiv](http://arxiv.org/abs/2404.07987v1), [pdf](http://arxiv.org/pdf/2404.07987v1.pdf), cication: [**-1**](None)

	 *Ming Li, Taojiannan Yang, Huafeng Kuang, Jie Wu, Zhaoning Wang, Xuefeng Xiao, Chen Chen* · ([liming-ai.github](https://liming-ai.github.io/ControlNet_Plus_Plus/))
- **HairFastGAN: Realistic and Robust Hair Transfer with a Fast
  Encoder-Based Approach**, `arXiv, 2404.01094`, [arxiv](http://arxiv.org/abs/2404.01094v1), [pdf](http://arxiv.org/pdf/2404.01094v1.pdf), cication: [**-1**](None)

	 *Maxim Nikolaev, Mikhail Kuznetsov, Dmitry Vetrov, Aibek Alanov* · ([HairFastGAN](https://github.com/AIRI-Institute/HairFastGAN?tab=readme-ov-file) - AIRI-Institute) ![Star](https://img.shields.io/github/stars/AIRI-Institute/HairFastGAN.svg?style=social&label=Star)
- **Self-Rectifying Diffusion Sampling with Perturbed-Attention Guidance**, `arXiv, 2403.17377`, [arxiv](http://arxiv.org/abs/2403.17377v1), [pdf](http://arxiv.org/pdf/2403.17377v1.pdf), cication: [**-1**](None)

	 *Donghoon Ahn, Hyoungwon Cho, Jaewon Min, Wooseok Jang, Jungwoo Kim, SeonHwa Kim, Hyun Hee Park, Kyong Hwan Jin, Seungryong Kim* · ([ku-cvlab.github](https://ku-cvlab.github.io/Perturbed-Attention-Guidance/))
- **Condition-Aware Neural Network for Controlled Image Generation**, `arXiv, 2404.01143`, [arxiv](http://arxiv.org/abs/2404.01143v1), [pdf](http://arxiv.org/pdf/2404.01143v1.pdf), cication: [**-1**](None)

	 *Han Cai, Muyang Li, Zhuoyang Zhang, Qinsheng Zhang, Ming-Yu Liu, Song Han*
- **Getting it Right: Improving Spatial Consistency in Text-to-Image Models**, `arXiv, 2404.01197`, [arxiv](http://arxiv.org/abs/2404.01197v1), [pdf](http://arxiv.org/pdf/2404.01197v1.pdf), cication: [**-1**](None)

	 *Agneet Chatterjee, Gabriela Ben Melech Stan, Estelle Aflalo, Sayak Paul, Dhruba Ghosh, Tejas Gokhale, Ludwig Schmidt, Hannaneh Hajishirzi, Vasudev Lal, Chitta Baral* · ([huggingface](https://huggingface.co/SPRIGHT-T2I/spright-t2i-sd2)) · ([spright-t2i.github](https://t.co/xanpTfKhzY))
- **Relation Rectification in Diffusion Model**, `arXiv, 2403.20249`, [arxiv](http://arxiv.org/abs/2403.20249v1), [pdf](http://arxiv.org/pdf/2403.20249v1.pdf), cication: [**-1**](None)

	 *Yinwei Wu, Xingyi Yang, Xinchao Wang* · ([RRNet](https://github.com/WUyinwei-hah/RRNet) - WUyinwei-hah) ![Star](https://img.shields.io/github/stars/WUyinwei-hah/RRNet.svg?style=social&label=Star) · ([wuyinwei-hah.github](https://wuyinwei-hah.github.io/rrnet.github.io/))
- **BrushNet: A Plug-and-Play Image Inpainting Model with Decomposed
  Dual-Branch Diffusion**, `arXiv, 2403.06976`, [arxiv](http://arxiv.org/abs/2403.06976v1), [pdf](http://arxiv.org/pdf/2403.06976v1.pdf), cication: [**-1**](None)

	 *Xuan Ju, Xian Liu, Xintao Wang, Yuxuan Bian, Ying Shan, Qiang Xu* · ([BrushNet](https://github.com/TencentARC/BrushNet) - TencentARC) ![Star](https://img.shields.io/github/stars/TencentARC/BrushNet.svg?style=social&label=Star)
- **Implicit Style-Content Separation using B-LoRA**, `arXiv, 2403.14572`, [arxiv](http://arxiv.org/abs/2403.14572v1), [pdf](http://arxiv.org/pdf/2403.14572v1.pdf), cication: [**-1**](None)

	 *Yarden Frenkel, Yael Vinker, Ariel Shamir, Daniel Cohen-Or* · ([B-LoRA](https://github.com/yardenfren1996/B-LoRA) - yardenfren1996) ![Star](https://img.shields.io/github/stars/yardenfren1996/B-LoRA.svg?style=social&label=Star) · ([b-lora.github](https://b-lora.github.io/B-LoRA/))
- **Be Yourself: Bounded Attention for Multi-Subject Text-to-Image
  Generation**, `arXiv, 2403.16990`, [arxiv](http://arxiv.org/abs/2403.16990v1), [pdf](http://arxiv.org/pdf/2403.16990v1.pdf), cication: [**-1**](None)

	 *Omer Dahary, Or Patashnik, Kfir Aberman, Daniel Cohen-Or*
- **LightIt: Illumination Modeling and Control for Diffusion Models**, `arXiv, 2403.10615`, [arxiv](http://arxiv.org/abs/2403.10615v1), [pdf](http://arxiv.org/pdf/2403.10615v1.pdf), cication: [**-1**](None)

	 *Peter Kocsis, Julien Philip, Kalyan Sunkavalli, Matthias Nießner, Yannick Hold-Geoffroy*
- **StreamMultiDiffusion: Real-Time Interactive Generation with Region-Based
  Semantic Control**, `arXiv, 2403.09055`, [arxiv](http://arxiv.org/abs/2403.09055v1), [pdf](http://arxiv.org/pdf/2403.09055v1.pdf), cication: [**-1**](None)

	 *Jaerin Lee, Daniel Sungho Jung, Kanggeon Lee, Kyoung Mu Lee*

	 · ([StreamMultiDiffusion](https://github.com/ironjr/StreamMultiDiffusion) - ironjr) ![Star](https://img.shields.io/github/stars/ironjr/StreamMultiDiffusion.svg?style=social&label=Star)

	 · ([huggingface](https://huggingface.co/spaces/ironjr/SemanticPalette))
- **FaceChain-SuDe: Building Derived Class to Inherit Category Attributes
  for One-shot Subject-Driven Generation**, `arXiv, 2403.06775`, [arxiv](http://arxiv.org/abs/2403.06775v1), [pdf](http://arxiv.org/pdf/2403.06775v1.pdf), cication: [**-1**](None)

	 *Pengchong Qiao, Lei Shang, Chang Liu, Baigui Sun, Xiangyang Ji, Jie Chen*

	 · ([facechain](https://github.com/modelscope/facechain) - modelscope) ![Star](https://img.shields.io/github/stars/modelscope/facechain.svg?style=social&label=Star)
- **MIGC: Multi-Instance Generation Controller for Text-to-Image Synthesis**, `arXiv, 2402.05408`, [arxiv](http://arxiv.org/abs/2402.05408v2), [pdf](http://arxiv.org/pdf/2402.05408v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=6982678976661726233&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Dewei Zhou, You Li, Fan Ma, Xiaoting Zhang, Yi Yang* · ([MIGC](https://github.com/limuloo/MIGC) - limuloo) ![Star](https://img.shields.io/github/stars/limuloo/MIGC.svg?style=social&label=Star)
- **UniHDA: A Unified and Versatile Framework for Multi-Modal Hybrid Domain
  Adaptation**, `arXiv, 2401.12596`, [arxiv](http://arxiv.org/abs/2401.12596v2), [pdf](http://arxiv.org/pdf/2401.12596v2.pdf), cication: [**-1**](None)

	 *Hengjia Li, Yang Liu, Yuqi Lin, Zhanwei Zhang, Yibo Zhao, weihang Pan, Tu Zheng, Zheng Yang, Yuchun Jiang, Boxi Wu*

	 · ([echopluto.github](https://echopluto.github.io/UniHDA-project/))

## Efficiency
- **VQ4DiT: Efficient Post-Training Vector Quantization for Diffusion
  Transformers**, `arXiv, 2408.17131`, [arxiv](http://arxiv.org/abs/2408.17131v1), [pdf](http://arxiv.org/pdf/2408.17131v1.pdf), cication: [**-1**](None)

	 *Juncan Deng, Shuaiting Li, Zeyu Wang, Hong Gu, Kedong Xu, Kejie Huang*
- **Accurate Compression of Text-to-Image Diffusion Models via Vector
  Quantization**, `arXiv, 2409.00492`, [arxiv](http://arxiv.org/abs/2409.00492v1), [pdf](http://arxiv.org/pdf/2409.00492v1.pdf), cication: [**-1**](None)

	 *Vage Egiazarian, Denis Kuznedelev, Anton Voronov, Ruslan Svirschevski, Michael Goin, Daniil Pavlov, Dan Alistarh, Dmitry Baranchuk* · ([yandex-research.github](https://yandex-research.github.io/vqdm/))
- **SwiftBrush v2: Make Your One-step Diffusion Model Better Than Its
  Teacher**, `arXiv, 2408.14176`, [arxiv](http://arxiv.org/abs/2408.14176v2), [pdf](http://arxiv.org/pdf/2408.14176v2.pdf), cication: [**-1**](None)

	 *Trung Dao, Thuan Hoang Nguyen, Thanh Le, Duc Vu, Khoi Nguyen, Cuong Pham, Anh Tran* · ([swiftbrushv2.github](https://swiftbrushv2.github.io/)) · ([vinairesearch.github](https://vinairesearch.github.io/SwiftBrush/))
- **AsyncDiff: Parallelizing Diffusion Models by Asynchronous Denoising**, `arXiv, 2406.06911`, [arxiv](http://arxiv.org/abs/2406.06911v1), [pdf](http://arxiv.org/pdf/2406.06911v1.pdf), cication: [**-1**](None)

	 *Zigeng Chen, Xinyin Ma, Gongfan Fang, Zhenxiong Tan, Xinchao Wang* · ([AsyncDiff](https://github.com/czg1225/AsyncDiff) - czg1225) ![Star](https://img.shields.io/github/stars/czg1225/AsyncDiff.svg?style=social&label=Star)
- **MLCM: Multistep Consistency Distillation of Latent Diffusion Model**, `arXiv, 2406.05768`, [arxiv](http://arxiv.org/abs/2406.05768v3), [pdf](http://arxiv.org/pdf/2406.05768v3.pdf), cication: [**-1**](None)

	 *Qingsong Xie, Zhenyi Liao, Chen chen, Zhijie Deng, Shixiang Tang, Haonan Lu*
- [**sdxl-flash**](https://huggingface.co/sd-community/sdxl-flash) - sd-community 🤗
- **Phased Consistency Model**, `arXiv, 2405.18407`, [arxiv](http://arxiv.org/abs/2405.18407v1), [pdf](http://arxiv.org/pdf/2405.18407v1.pdf), cication: [**-1**](None)

	 *Fu-Yun Wang, Zhaoyang Huang, Alexander William Bergman, Dazhong Shen, Peng Gao, Michael Lingelbach, Keqiang Sun, Weikang Bian, Guanglu Song, Yu Liu* · ([g-u-n.github](https://g-u-n.github.io/projects/pcm/)) · ([Phased-Consistency-Model](https://github.com/G-U-N/Phased-Consistency-Model) - G-U-N) ![Star](https://img.shields.io/github/stars/G-U-N/Phased-Consistency-Model.svg?style=social&label=Star)
- **EM Distillation for One-step Diffusion Models**, `arXiv, 2405.16852`, [arxiv](http://arxiv.org/abs/2405.16852v1), [pdf](http://arxiv.org/pdf/2405.16852v1.pdf), cication: [**-1**](None)

	 *Sirui Xie, Zhisheng Xiao, Diederik P Kingma, Tingbo Hou, Ying Nian Wu, Kevin Patrick Murphy, Tim Salimans, Ben Poole, Ruiqi Gao*
- **DiM: Diffusion Mamba for Efficient High-Resolution Image Synthesis**, `arXiv, 2405.14224`, [arxiv](http://arxiv.org/abs/2405.14224v1), [pdf](http://arxiv.org/pdf/2405.14224v1.pdf), cication: [**-1**](None)

	 *Yao Teng, Yue Wu, Han Shi, Xuefei Ning, Guohao Dai, Yu Wang, Zhenguo Li, Xihui Liu*
- **Improved Distribution Matching Distillation for Fast Image Synthesis**, `arXiv, 2405.14867`, [arxiv](http://arxiv.org/abs/2405.14867v1), [pdf](http://arxiv.org/pdf/2405.14867v1.pdf), cication: [**-1**](None)

	 *Tianwei Yin, Michaël Gharbi, Taesung Park, Richard Zhang, Eli Shechtman, Fredo Durand, William T. Freeman*
- **LiteVAE: Lightweight and Efficient Variational Autoencoders for Latent
  Diffusion Models**, `arXiv, 2405.14477`, [arxiv](http://arxiv.org/abs/2405.14477v1), [pdf](http://arxiv.org/pdf/2405.14477v1.pdf), cication: [**-1**](None)

	 *Seyedmorteza Sadat, Jakob Buhmann, Derek Bradley, Otmar Hilliges, Romann M. Weber*
- **Imagine Flash: Accelerating Emu Diffusion Models with Backward
  Distillation**, `arXiv, 2405.05224`, [arxiv](http://arxiv.org/abs/2405.05224v1), [pdf](http://arxiv.org/pdf/2405.05224v1.pdf), cication: [**-1**](None)

	 *Jonas Kohler, Albert Pumarola, Edgar Schönfeld, Artsiom Sanakoyeu, Roshan Sumbaly, Peter Vajda, Ali Thabet*
- **PixArt-Σ: Weak-to-Strong Training of Diffusion Transformer for 4K
  Text-to-Image Generation**, `arXiv, 2403.04692`, [arxiv](http://arxiv.org/abs/2403.04692v2), [pdf](http://arxiv.org/pdf/2403.04692v2.pdf), cication: [**-1**](None)

	 *Junsong Chen, Chongjian Ge, Enze Xie, Yue Wu, Lewei Yao, Xiaozhe Ren, Zhongdao Wang, Ping Luo, Huchuan Lu, Zhenguo Li* · ([PixArt-sigma](https://github.com/PixArt-alpha/PixArt-sigma) - PixArt-alpha) ![Star](https://img.shields.io/github/stars/PixArt-alpha/PixArt-sigma.svg?style=social&label=Star)
- **Align Your Steps: Optimizing Sampling Schedules in Diffusion Models**, `arXiv, 2404.14507`, [arxiv](http://arxiv.org/abs/2404.14507v1), [pdf](http://arxiv.org/pdf/2404.14507v1.pdf), cication: [**-1**](None)

	 *Amirmojtaba Sabour, Sanja Fidler, Karsten Kreis*
- [**piecewise-rectified-flow**](https://github.com/magic-research/piecewise-rectified-flow/tree/main) - magic-research ![Star](https://img.shields.io/github/stars/magic-research/piecewise-rectified-flow.svg?style=social&label=Star)
- **Bigger is not Always Better: Scaling Properties of Latent Diffusion
  Models**, `arXiv, 2404.01367`, [arxiv](http://arxiv.org/abs/2404.01367v1), [pdf](http://arxiv.org/pdf/2404.01367v1.pdf), cication: [**-1**](None)

	 *Kangfu Mei, Zhengzhong Tu, Mauricio Delbracio, Hossein Talebi, Vishal M. Patel, Peyman Milanfar* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-04-22-2))
- [Hyper-SD: Trajectory Segmented Consistency Model for Efficient Image Synthesis](https://hyper-sd.github.io/)

	 · ([hyper-sd.github](https://hyper-sd.github.io/))
- **EdgeFusion: On-Device Text-to-Image Generation**, `arXiv, 2404.11925`, [arxiv](http://arxiv.org/abs/2404.11925v1), [pdf](http://arxiv.org/pdf/2404.11925v1.pdf), cication: [**-1**](None)

	 *Thibault Castells, Hyoung-Kyu Song, Tairen Piao, Shinkook Choi, Bo-Kyeong Kim, Hanyoung Yim, Changgwun Lee, Jae Gon Kim, Tae-Ho Kim*
- **Applying Guidance in a Limited Interval Improves Sample and Distribution
  Quality in Diffusion Models**, `arXiv, 2404.07724`, [arxiv](http://arxiv.org/abs/2404.07724v1), [pdf](http://arxiv.org/pdf/2404.07724v1.pdf), cication: [**-1**](None)

	 *Tuomas Kynkäänniemi, Miika Aittala, Tero Karras, Samuli Laine, Timo Aila, Jaakko Lehtinen*
- **BinaryDM: Towards Accurate Binarization of Diffusion Model**, `arXiv, 2404.05662`, [arxiv](http://arxiv.org/abs/2404.05662v1), [pdf](http://arxiv.org/pdf/2404.05662v1.pdf), cication: [**-1**](None)

	 *Xingyu Zheng, Haotong Qin, Xudong Ma, Mingyuan Zhang, Haojie Hao, Jiakai Wang, Zixiang Zhao, Jinyang Guo, Xianglong Liu* · ([BinaryDM](https://github.com/Xingyu-Zheng/BinaryDM) - Xingyu-Zheng) ![Star](https://img.shields.io/github/stars/Xingyu-Zheng/BinaryDM.svg?style=social&label=Star)
- **Cross-Attention Makes Inference Cumbersome in Text-to-Image Diffusion
  Models**, `arXiv, 2404.02747`, [arxiv](http://arxiv.org/abs/2404.02747v1), [pdf](http://arxiv.org/pdf/2404.02747v1.pdf), cication: [**-1**](None)

	 *Wentian Zhang, Haozhe Liu, Jinheng Xie, Francesco Faccio, Mike Zheng Shou, Jürgen Schmidhuber* · ([t-gate](https://github.com/haozheliu-st/t-gate) - haozheliu-st) ![Star](https://img.shields.io/github/stars/haozheliu-st/t-gate.svg?style=social&label=Star)
- **SDXS: Real-Time One-Step Latent Diffusion Models with Image Conditions**, `arXiv, 2403.16627`, [arxiv](http://arxiv.org/abs/2403.16627v1), [pdf](http://arxiv.org/pdf/2403.16627v1.pdf), cication: [**-1**](None)

	 *Yuda Song, Zehao Sun, Xuanwu Yin*
- **Fast High-Resolution Image Synthesis with Latent Adversarial Diffusion
  Distillation**, `arXiv, 2403.12015`, [arxiv](http://arxiv.org/abs/2403.12015v1), [pdf](http://arxiv.org/pdf/2403.12015v1.pdf), cication: [**-1**](None)

	 *Axel Sauer, Frederic Boesel, Tim Dockhorn, Andreas Blattmann, Patrick Esser, Robin Rombach*
- **Multistep Consistency Models**, `arXiv, 2403.06807`, [arxiv](http://arxiv.org/abs/2403.06807v1), [pdf](http://arxiv.org/pdf/2403.06807v1.pdf), cication: [**-1**](None)

	 *Jonathan Heek, Emiel Hoogeboom, Tim Salimans*
- **SDXL-Lightning: Progressive Adversarial Diffusion Distillation**, `arXiv, 2402.13929`, [arxiv](http://arxiv.org/abs/2402.13929v3), [pdf](http://arxiv.org/pdf/2402.13929v3.pdf), cication: [**14**](https://scholar.google.com/scholar?cites=15402790534057305106&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shanchuan Lin, Anran Wang, Xiao Yang* · ([huggingface](https://huggingface.co/ByteDance/SDXL-Lightning))

## Editting
- **Guide-and-Rescale: Self-Guidance Mechanism for Effective Tuning-Free
  Real Image Editing**, `arXiv, 2409.01322`, [arxiv](http://arxiv.org/abs/2409.01322v2), [pdf](http://arxiv.org/pdf/2409.01322v2.pdf), cication: [**-1**](None)

	 *Vadim Titov, Madina Khalmatova, Alexandra Ivanova, Dmitry Vetrov, Aibek Alanov* · ([Guide-and-Rescale](https://github.com/FusionBrainLab/Guide-and-Rescale) - FusionBrainLab) ![Star](https://img.shields.io/github/stars/FusionBrainLab/Guide-and-Rescale.svg?style=social&label=Star)
- **TurboEdit: Instant text-based image editing**, `arXiv, 2408.08332`, [arxiv](http://arxiv.org/abs/2408.08332v1), [pdf](http://arxiv.org/pdf/2408.08332v1.pdf), cication: [**-1**](None)

	 *Zongze Wu, Nicholas Kolkin, Jonathan Brandt, Richard Zhang, Eli Shechtman* · ([betterze.github](https://betterze.github.io/TurboEdit/))
- **TurboEdit: Text-Based Image Editing Using Few-Step Diffusion Models**, `arXiv, 2408.00735`, [arxiv](http://arxiv.org/abs/2408.00735v1), [pdf](http://arxiv.org/pdf/2408.00735v1.pdf), cication: [**-1**](None)

	 *Gilad Deutch, Rinon Gal, Daniel Garibi, Or Patashnik, Daniel Cohen-Or* · ([turboedit-paper.github](https://turboedit-paper.github.io/))
- **Diffree: Text-Guided Shape Free Object Inpainting with Diffusion Model**, `arXiv, 2407.16982`, [arxiv](http://arxiv.org/abs/2407.16982v1), [pdf](http://arxiv.org/pdf/2407.16982v1.pdf), cication: [**-1**](None)

	 *Lirui Zhao, Tianshuo Yang, Wenqi Shao, Yuxin Zhang, Yu Qiao, Ping Luo, Kaipeng Zhang, Rongrong Ji* · ([opengvlab.github](https://opengvlab.github.io/Diffree/))
- **UltraEdit: Instruction-based Fine-Grained Image Editing at Scale**, `arXiv, 2407.05282`, [arxiv](http://arxiv.org/abs/2407.05282v1), [pdf](http://arxiv.org/pdf/2407.05282v1.pdf), cication: [**-1**](None)

	 *Haozhe Zhao, Xiaojian Ma, Liang Chen, Shuzheng Si, Rujie Wu, Kaikai An, Peiyu Yu, Minjia Zhang, Qing Li, Baobao Chang*

	 · ([ultra-editing.github](https://ultra-editing.github.io/))
- **A Survey of Multimodal-Guided Image Editing with Text-to-Image Diffusion
  Models**, `arXiv, 2406.14555`, [arxiv](http://arxiv.org/abs/2406.14555v1), [pdf](http://arxiv.org/pdf/2406.14555v1.pdf), cication: [**-1**](None)

	 *Xincheng Shuai, Henghui Ding, Xingjun Ma, Rongcheng Tu, Yu-Gang Jiang, Dacheng Tao* · ([awesome-image-editing](https://github.com/xinchengshuai/awesome-image-editing) - xinchengshuai) ![Star](https://img.shields.io/github/stars/xinchengshuai/awesome-image-editing.svg?style=social&label=Star)
- **Invertible Consistency Distillation for Text-Guided Image Editing in
  Around 7 Steps**, `arXiv, 2406.14539`, [arxiv](http://arxiv.org/abs/2406.14539v1), [pdf](http://arxiv.org/pdf/2406.14539v1.pdf), cication: [**-1**](None)

	 *Nikita Starodubcev, Mikhail Khoroshikh, Artem Babenko, Dmitry Baranchuk*
- **The Devil is in the Details: StyleFeatureEditor for Detail-Rich StyleGAN
  Inversion and High Quality Image Editing**, `CVPR, 2024`, [arxiv](http://arxiv.org/abs/2406.10601v1), [pdf](http://arxiv.org/pdf/2406.10601v1.pdf), cication: [**-1**](None)

	 *Denis Bobkov, Vadim Titov, Aibek Alanov, Dmitry Vetrov* · ([stylefeatureeditor](https://github.com/airi-institute/stylefeatureeditor) - airi-institute) ![Star](https://img.shields.io/github/stars/airi-institute/stylefeatureeditor.svg?style=social&label=Star)
- **Zero-shot Image Editing with Reference Imitation**, `arXiv, 2406.07547`, [arxiv](http://arxiv.org/abs/2406.07547v1), [pdf](http://arxiv.org/pdf/2406.07547v1.pdf), cication: [**-1**](None)

	 *Xi Chen, Yutong Feng, Mengting Chen, Yiyang Wang, Shilong Zhang, Yu Liu, Yujun Shen, Hengshuang Zhao*
- **Attention-Driven Training-Free Efficiency Enhancement of Diffusion
  Models**, `arXiv, 2405.05252`, [arxiv](http://arxiv.org/abs/2405.05252v1), [pdf](http://arxiv.org/pdf/2405.05252v1.pdf), cication: [**-1**](None)

	 *Hongjie Wang, Difan Liu, Yan Kang, Yijun Li, Zhe Lin, Niraj K. Jha, Yuchen Liu* · ([atedm.github](https://atedm.github.io/))
- [**ZeST**](https://huggingface.co/spaces/fffiloni/ZeST) - fffiloni 🤗
- **Customizing Text-to-Image Models with a Single Image Pair**, `arXiv, 2405.01536`, [arxiv](http://arxiv.org/abs/2405.01536v1), [pdf](http://arxiv.org/pdf/2405.01536v1.pdf), cication: [**-1**](None)

	 *Maxwell Jones, Sheng-Yu Wang, Nupur Kumari, David Bau, Jun-Yan Zhu*
- **Paint by Inpaint: Learning to Add Image Objects by Removing Them First**, `arXiv, 2404.18212`, [arxiv](http://arxiv.org/abs/2404.18212v1), [pdf](http://arxiv.org/pdf/2404.18212v1.pdf), cication: [**-1**](None)

	 *Navve Wasserman, Noam Rotstein, Roy Ganz, Ron Kimmel* · ([rotsteinnoam.github](https://rotsteinnoam.github.io/Paint-by-Inpaint/))
- **Editable Image Elements for Controllable Synthesis**, `arXiv, 2404.16029`, [arxiv](http://arxiv.org/abs/2404.16029v1), [pdf](http://arxiv.org/pdf/2404.16029v1.pdf), cication: [**-1**](None)

	 *Jiteng Mu, Michaël Gharbi, Richard Zhang, Eli Shechtman, Nuno Vasconcelos, Xiaolong Wang, Taesung Park* · ([jitengmu.github](https://jitengmu.github.io/Editable_Image_Elements/))
- **StyleBooth: Image Style Editing with Multimodal Instruction**, `arXiv, 2404.12154`, [arxiv](http://arxiv.org/abs/2404.12154v1), [pdf](http://arxiv.org/pdf/2404.12154v1.pdf), cication: [**-1**](None)

	 *Zhen Han, Chaojie Mao, Zeyinzi Jiang, Yulin Pan, Jingfeng Zhang* · ([ali-vilab.github](https://ali-vilab.github.io/stylebooth-page/)) · ([scepter](https://github.com/modelscope/scepter) - modelscope) ![Star](https://img.shields.io/github/stars/modelscope/scepter.svg?style=social&label=Star)
- **HQ-Edit: A High-Quality Dataset for Instruction-based Image Editing**, `arXiv, 2404.09990`, [arxiv](http://arxiv.org/abs/2404.09990v1), [pdf](http://arxiv.org/pdf/2404.09990v1.pdf), cication: [**-1**](None)

	 *Mude Hui, Siwei Yang, Bingchen Zhao, Yichun Shi, Heng Wang, Peng Wang, Yuyin Zhou, Cihang Xie*

	 · ([thefllood.github](https://thefllood.github.io/HQEdit_web))
- [sandner.art | Cosine-Continuous Stable Diffusion XL (CosXL) on StableSwarmUI](https://sandner.art/cosine-continuous-stable-diffusion-xl-cosxl-on-stableswarmui)

	 · ([huggingface](https://huggingface.co/stabilityai/cosxl/tree/main))
- **SwapAnything: Enabling Arbitrary Object Swapping in Personalized Visual
  Editing**, `arXiv, 2404.05717`, [arxiv](http://arxiv.org/abs/2404.05717v1), [pdf](http://arxiv.org/pdf/2404.05717v1.pdf), cication: [**-1**](None)

	 *Jing Gu, Yilin Wang, Nanxuan Zhao, Wei Xiong, Qing Liu, Zhifei Zhang, He Zhang, Jianming Zhang, HyunJoon Jung, Xin Eric Wang*
- **InstantStyle: Free Lunch towards Style-Preserving in Text-to-Image
  Generation**, `arXiv, 2404.02733`, [arxiv](http://arxiv.org/abs/2404.02733v1), [pdf](http://arxiv.org/pdf/2404.02733v1.pdf), cication: [**-1**](None)

	 *Haofan Wang, Qixun Wang, Xu Bai, Zekui Qin, Anthony Chen* · ([instantstyle](https://github.com/instantstyle/instantstyle?tab=readme-ov-file) - instantstyle) ![Star](https://img.shields.io/github/stars/instantstyle/instantstyle.svg?style=social&label=Star)
- **Learning Inclusion Matching for Animation Paint Bucket Colorization**, `arXiv, 2403.18342`, [arxiv](http://arxiv.org/abs/2403.18342v1), [pdf](http://arxiv.org/pdf/2403.18342v1.pdf), cication: [**-1**](None)

	 *Yuekun Dai, Shangchen Zhou, Qinyue Li, Chongyi Li, Chen Change Loy* · ([BasicPBC](https://github.com/ykdai/BasicPBC) - ykdai) ![Star](https://img.shields.io/github/stars/ykdai/BasicPBC.svg?style=social&label=Star)
- **FlexEdit: Flexible and Controllable Diffusion-based Object-centric Image
  Editing**, `arXiv, 2403.18605`, [arxiv](http://arxiv.org/abs/2403.18605v1), [pdf](http://arxiv.org/pdf/2403.18605v1.pdf), cication: [**-1**](None)

	 *Trong-Tung Nguyen, Duc-Anh Nguyen, Anh Tran, Cuong Pham* · ([flex-edit.github](https://flex-edit.github.io/))
- **ObjectDrop: Bootstrapping Counterfactuals for Photorealistic Object
  Removal and Insertion**, `arXiv, 2403.18818`, [arxiv](http://arxiv.org/abs/2403.18818v1), [pdf](http://arxiv.org/pdf/2403.18818v1.pdf), cication: [**-1**](None)

	 *Daniel Winter, Matan Cohen, Shlomi Fruchter, Yael Pritch, Alex Rav-Acha, Yedid Hoshen*
- **ReNoise: Real Image Inversion Through Iterative Noising**, `arXiv, 2403.14602`, [arxiv](http://arxiv.org/abs/2403.14602v1), [pdf](http://arxiv.org/pdf/2403.14602v1.pdf), cication: [**-1**](None)

	 *Daniel Garibi, Or Patashnik, Andrey Voynov, Hadar Averbuch-Elor, Daniel Cohen-Or*
- **Magic Fixup: Streamlining Photo Editing by Watching Dynamic Videos**, `arXiv, 2403.13044`, [arxiv](http://arxiv.org/abs/2403.13044v1), [pdf](http://arxiv.org/pdf/2403.13044v1.pdf), cication: [**-1**](None)

	 *Hadi Alzayer, Zhihao Xia, Xuaner Zhang, Eli Shechtman, Jia-Bin Huang, Michael Gharbi*
- **One-Step Image Translation with Text-to-Image Models**, `arXiv, 2403.12036`, [arxiv](http://arxiv.org/abs/2403.12036v1), [pdf](http://arxiv.org/pdf/2403.12036v1.pdf), cication: [**-1**](None)

	 *Gaurav Parmar, Taesung Park, Srinivasa Narasimhan, Jun-Yan Zhu* · ([img2img-turbo](https://github.com/GaParmar/img2img-turbo) - GaParmar) ![Star](https://img.shields.io/github/stars/GaParmar/img2img-turbo.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/spaces/gparmar/img2img-turbo-sketch))
- **One-Dimensional Adapter to Rule Them All: Concepts, Diffusion Models and
  Erasing Applications**, `arXiv, 2312.16145`, [arxiv](http://arxiv.org/abs/2312.16145v2), [pdf](http://arxiv.org/pdf/2312.16145v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=1848795327329358939&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Mengyao Lyu, Yuhong Yang, Haiwen Hong, Hui Chen, Xuan Jin, Yuan He, Hui Xue, Jungong Han, Guiguang Ding*

	 · ([SPM](https://github.com/Con6924/SPM) - Con6924) ![Star](https://img.shields.io/github/stars/Con6924/SPM.svg?style=social&label=Star) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-03-13))

## Architecture
- **MARS: Mixture of Auto-Regressive Models for Fine-grained Text-to-image
  Synthesis**, `arXiv, 2407.07614`, [arxiv](http://arxiv.org/abs/2407.07614v2), [pdf](http://arxiv.org/pdf/2407.07614v2.pdf), cication: [**-1**](None)

	 *Wanggui He, Siming Fu, Mushui Liu, Xierui Wang, Wenyi Xiao, Fangxun Shu, Yi Wang, Lei Zhang, Zhelun Yu, Haoyuan Li*
- **YaART: Yet Another ART Rendering Technology**, `arXiv, 2404.05666`, [arxiv](http://arxiv.org/abs/2404.05666v1), [pdf](http://arxiv.org/pdf/2404.05666v1.pdf), cication: [**-1**](None)

	 *Sergey Kastryulin, Artem Konev, Alexander Shishenya, Eugene Lyapustin, Artem Khurshudov, Alexander Tselousov, Nikita Vinokurov, Denis Kuznedelev, Alexander Markovich, Grigoriy Livshits*
- **Diffusion-RWKV: Scaling RWKV-Like Architectures for Diffusion Models**, `arXiv, 2404.04478`, [arxiv](http://arxiv.org/abs/2404.04478v1), [pdf](http://arxiv.org/pdf/2404.04478v1.pdf), cication: [**-1**](None)

	 *Zhengcong Fei, Mingyuan Fan, Changqian Yu, Debang Li, Junshi Huang*
- **ZigMa: Zigzag Mamba Diffusion Model**, `arXiv, 2403.13802`, [arxiv](http://arxiv.org/abs/2403.13802v1), [pdf](http://arxiv.org/pdf/2403.13802v1.pdf), cication: [**-1**](None)

	 *Vincent Tao Hu, Stefan Andreas Baumann, Ming Gui, Olga Grebenkova, Pingchuan Ma, Johannes Fischer, Bjorn Ommer*
- **Text-Driven Image Editing via Learnable Regions**, `CVPR, 2024`, [arxiv](http://arxiv.org/abs/2311.16432v2), [pdf](http://arxiv.org/pdf/2311.16432v2.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=8294621472607914145&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yuanze Lin, Yi-Wen Chen, Yi-Hsuan Tsai, Lu Jiang, Ming-Hsuan Yang* · ([Learnable_Regions](https://github.com/yuanze-lin/Learnable_Regions) - yuanze-lin) ![Star](https://img.shields.io/github/stars/yuanze-lin/Learnable_Regions.svg?style=social&label=Star)
- **The Missing U for Efficient Diffusion Models**, `arXiv, 2310.20092`, [arxiv](http://arxiv.org/abs/2310.20092v4), [pdf](http://arxiv.org/pdf/2310.20092v4.pdf), cication: [**-1**](None)

	 *Sergio Calvo-Ordonez, Chun-Wun Cheng, Jiahao Huang, Lipei Zhang, Guang Yang, Carola-Bibiane Schonlieb, Angelica I Aviles-Rivero* · ([reddit](https://www.reddit.com/r/MachineLearning/comments/1bzfns4/r_the_missing_u_for_efficient_diffusion_models/?utm_source=ainews&utm_medium=email&utm_campaign=ainews-gemini-pro-and-gpt4t-vision-go-ga-on-the))

## DiT
- **Qihoo-T2X: An Efficiency-Focused Diffusion Transformer via Proxy Tokens
  for Text-to-Any-Task**, `arXiv, 2409.04005`, [arxiv](http://arxiv.org/abs/2409.04005v1), [pdf](http://arxiv.org/pdf/2409.04005v1.pdf), cication: [**-1**](None)

	 *Jing Wang, Ao Ma, Jiasong Feng, Dawei Leng, Yuhui Yin, Xiaodan Liang* · ([Qihoo-T2X](https://github.com/360CVGroup/Qihoo-T2X) - 360CVGroup) ![Star](https://img.shields.io/github/stars/360CVGroup/Qihoo-T2X.svg?style=social&label=Star)
- **Scaling Diffusion Transformers to 16 Billion Parameters**, `arXiv, 2407.11633`, [arxiv](http://arxiv.org/abs/2407.11633v1), [pdf](http://arxiv.org/pdf/2407.11633v1.pdf), cication: [**-1**](None)

	 *Zhengcong Fei, Mingyuan Fan, Changqian Yu, Debang Li, Junshi Huang* · ([dit-moe](https://github.com/feizc/dit-moe) - feizc) ![Star](https://img.shields.io/github/stars/feizc/dit-moe.svg?style=social&label=Star)
- [**opendit**](https://github.com/nus-hpc-ai-lab/opendit) - nus-hpc-ai-lab ![Star](https://img.shields.io/github/stars/nus-hpc-ai-lab/opendit.svg?style=social&label=Star)

	 *OpenDiT: An Easy, Fast and Memory-Efficient System for DiT Training and Inference*
- **DiTFastAttn: Attention Compression for Diffusion Transformer Models**, `arXiv, 2406.08552`, [arxiv](http://arxiv.org/abs/2406.08552v1), [pdf](http://arxiv.org/pdf/2406.08552v1.pdf), cication: [**-1**](None)

	 *Zhihang Yuan, Pu Lu, Hanling Zhang, Xuefei Ning, Linfeng Zhang, Tianchen Zhao, Shengen Yan, Guohao Dai, Yu Wang*
- **MDTv2: Masked Diffusion Transformer is a Strong Image Synthesizer**, `ICCV, 2023`, [arxiv](http://arxiv.org/abs/2303.14389v2), [pdf](http://arxiv.org/pdf/2303.14389v2.pdf), cication: [**36**](https://scholar.google.com/scholar?cites=265826374435029950&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shanghua Gao, Pan Zhou, Ming-Ming Cheng, Shuicheng Yan* · ([MDT](https://github.com/sail-sg/MDT) - sail-sg) ![Star](https://img.shields.io/github/stars/sail-sg/MDT.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652454525&idx=3&sn=fdd95d9f3de58caa7ad0c8bfbe07f548))
	 
## Text Rendering
- **Glyph-ByT5-v2: A Strong Aesthetic Baseline for Accurate Multilingual
  Visual Text Rendering**, `arXiv, 2406.10208`, [arxiv](http://arxiv.org/abs/2406.10208v1), [pdf](http://arxiv.org/pdf/2406.10208v1.pdf), cication: [**-1**](None)

	 *Zeyu Liu, Weicong Liang, Yiming Zhao, Bohan Chen, Ji Li, Yuhui Yuan*
- **TextCraftor: Your Text Encoder Can be Image Quality Controller**, `arXiv, 2403.18978`, [arxiv](http://arxiv.org/abs/2403.18978v1), [pdf](http://arxiv.org/pdf/2403.18978v1.pdf), cication: [**-1**](None)

	 *Yanyu Li, Xian Liu, Anil Kag, Ju Hu, Yerlan Idelbayev, Dhritiman Sagar, Yanzhi Wang, Sergey Tulyakov, Jian Ren*
- **Glyph-ByT5: A Customized Text Encoder for Accurate Visual Text Rendering**, `arXiv, 2403.09622`, [arxiv](http://arxiv.org/abs/2403.09622v1), [pdf](http://arxiv.org/pdf/2403.09622v1.pdf), cication: [**-1**](None)

	 *Zeyu Liu, Weicong Liang, Zhanhao Liang, Chong Luo, Ji Li, Gao Huang, Yuhui Yuan*

## Personlazation
- **TextBoost: Towards One-Shot Personalization of Text-to-Image Models via
  Fine-tuning Text Encoder**, `arXiv, 2409.08248`, [arxiv](http://arxiv.org/abs/2409.08248v1), [pdf](http://arxiv.org/pdf/2409.08248v1.pdf), cication: [**-1**](None)

	 *NaHyeon Park, Kunhee Kim, Hyunjung Shim* · ([textboost.github](https://textboost.github.io/)) · ([textboost](https://github.com/nahyeonkaty/textboost) - nahyeonkaty) ![Star](https://img.shields.io/github/stars/nahyeonkaty/textboost.svg?style=social&label=Star)
- **CoRe: Context-Regularized Text Embedding Learning for Text-to-Image
  Personalization**, `arXiv, 2408.15914`, [arxiv](http://arxiv.org/abs/2408.15914v1), [pdf](http://arxiv.org/pdf/2408.15914v1.pdf), cication: [**-1**](None)

	 *Feize Wu, Yun Pang, Junyi Zhang, Lianyu Pang, Jian Yin, Baoquan Zhao, Qing Li, Xudong Mao*
- [**comfyui-instantId-faceswap**](https://github.com/nosiu/comfyui-instantId-faceswap) - nosiu ![Star](https://img.shields.io/github/stars/nosiu/comfyui-instantId-faceswap.svg?style=social&label=Star)

	 *Implementation of faceswap based on InstantID for ComfyUI.*
- **MagicID: Flexible ID Fidelity Generation System**, `arXiv, 2408.09248`, [arxiv](http://arxiv.org/abs/2408.09248v2), [pdf](http://arxiv.org/pdf/2408.09248v2.pdf), cication: [**-1**](None)

	 *Zhaoli Deng, Wen Liu, Fanyi Wang, Junkang Zhang, Fan Chen, Meng Zhang, Wendong Zhang, Zhenpeng Mi*
- **MagicFace: Training-free Universal-Style Human Image Customized
  Synthesis**, `arXiv, 2408.07433`, [arxiv](http://arxiv.org/abs/2408.07433v3), [pdf](http://arxiv.org/pdf/2408.07433v3.pdf), cication: [**-1**](None)

	 *Yibin Wang, Weizhong Zhang, Cheng Jin* · ([codegoat24.github](https://codegoat24.github.io/MagicFace/)) · ([MagicFace](https://github.com/CodeGoat24/MagicFace) - CodeGoat24) ![Star](https://img.shields.io/github/stars/CodeGoat24/MagicFace.svg?style=social&label=Star)
- **UniPortrait: A Unified Framework for Identity-Preserving Single- and
  Multi-Human Image Personalization**, `arXiv, 2408.05939`, [arxiv](http://arxiv.org/abs/2408.05939v1), [pdf](http://arxiv.org/pdf/2408.05939v1.pdf), cication: [**-1**](None)

	 *Junjie He, Yifeng Geng, Liefeng Bo* · ([UniPortrait](https://github.com/junjiehe96/UniPortrait) - junjiehe96) ![Star](https://img.shields.io/github/stars/junjiehe96/UniPortrait.svg?style=social&label=Star)
- **IPAdapter-Instruct: Resolving Ambiguity in Image-based Conditioning
  using Instruct Prompts**, `arXiv, 2408.03209`, [arxiv](http://arxiv.org/abs/2408.03209v1), [pdf](http://arxiv.org/pdf/2408.03209v1.pdf), cication: [**-1**](None)

	 *Ciara Rowles, Shimon Vainer, Dante De Nigris, Slava Elizarov, Konstantin Kutsy, Simon Donné* · ([unity-research.github](https://unity-research.github.io/IP-Adapter-Instruct.github.io/)) · ([IP-Adapter-Instruct](https://github.com/unity-research/IP-Adapter-Instruct) - unity-research) ![Star](https://img.shields.io/github/stars/unity-research/IP-Adapter-Instruct.svg?style=social&label=Star)
- **ViPer: Visual Personalization of Generative Models via Individual
  Preference Learning**, `arXiv, 2407.17365`, [arxiv](http://arxiv.org/abs/2407.17365v1), [pdf](http://arxiv.org/pdf/2407.17365v1.pdf), cication: [**-1**](None)

	 *Sogand Salehi, Mahdi Shafiei, Teresa Yeo, Roman Bachmann, Amir Zamir* · ([ViPer](https://github.com/EPFL-VILAB/ViPer) - EPFL-VILAB) ![Star](https://img.shields.io/github/stars/EPFL-VILAB/ViPer.svg?style=social&label=Star) · ([viper.epfl](https://viper.epfl.ch/))
- **Stable-Hair: Real-World Hair Transfer via Diffusion Model**, `arXiv, 2407.14078`, [arxiv](http://arxiv.org/abs/2407.14078v1), [pdf](http://arxiv.org/pdf/2407.14078v1.pdf), cication: [**-1**](None)

	 *Yuxuan Zhang, Qing Zhang, Yiren Song, Jiaming Liu* · ([Stable-Hair](https://github.com/Xiaojiu-z/Stable-Hair?tab=readme-ov-file) - Xiaojiu-z) ![Star](https://img.shields.io/github/stars/Xiaojiu-z/Stable-Hair.svg?style=social&label=Star)
- [Imagine yourself: Tuning-Free Personalized Image Generation](https://ai.meta.com/research/publications/imagine-yourself-tuning-free-personalized-image-generation/)
- **AutoStudio: Crafting Consistent Subjects in Multi-turn Interactive Image
  Generation**, `arXiv, 2406.01388`, [arxiv](http://arxiv.org/abs/2406.01388v2), [pdf](http://arxiv.org/pdf/2406.01388v2.pdf), cication: [**-1**](None)

	 *Junhao Cheng, Xi Lu, Hanhui Li, Khun Loun Zai, Baiqiao Yin, Yuhao Cheng, Yiqiang Yan, Xiaodan Liang* · ([AutoStudio](https://github.com/donahowe/AutoStudio?tab=readme-ov-file) - donahowe) ![Star](https://img.shields.io/github/stars/donahowe/AutoStudio.svg?style=social&label=Star)
- **MS-Diffusion: Multi-subject Zero-shot Image Personalization with Layout
  Guidance**, `arXiv, 2406.07209`, [arxiv](http://arxiv.org/abs/2406.07209v1), [pdf](http://arxiv.org/pdf/2406.07209v1.pdf), cication: [**-1**](None)

	 *X. Wang, Siming Fu, Qihan Huang, Wanggui He, Hao Jiang* · ([MS-Diffusion](https://github.com/MS-Diffusion/MS-Diffusion?tab=readme-ov-file) - MS-Diffusion) ![Star](https://img.shields.io/github/stars/MS-Diffusion/MS-Diffusion.svg?style=social&label=Star)
- **Personalized Residuals for Concept-Driven Text-to-Image Generation**, `arXiv, 2405.12978`, [arxiv](http://arxiv.org/abs/2405.12978v1), [pdf](http://arxiv.org/pdf/2405.12978v1.pdf), cication: [**-1**](None)

	 *Cusuh Ham, Matthew Fisher, James Hays, Nicholas Kolkin, Yuchen Liu, Richard Zhang, Tobias Hinz* · ([cusuh.github](https://cusuh.github.io/personalized-residuals/))
- **Face Adapter for Pre-Trained Diffusion Models with Fine-Grained ID and
  Attribute Control**, `arXiv, 2405.12970`, [arxiv](http://arxiv.org/abs/2405.12970v1), [pdf](http://arxiv.org/pdf/2405.12970v1.pdf), cication: [**-1**](None)

	 *Yue Han, Junwei Zhu, Keke He, Xu Chen, Yanhao Ge, Wei Li, Xiangtai Li, Jiangning Zhang, Chengjie Wang, Yong Liu*
- [**omni-zero**](https://github.com/okaris/omni-zero) - okaris ![Star](https://img.shields.io/github/stars/okaris/omni-zero.svg?style=social&label=Star)

	 *A diffusers pipeline for zero shot stylised portrait creation*
- **InstantFamily: Masked Attention for Zero-shot Multi-ID Image Generation**, `arXiv, 2404.19427`, [arxiv](http://arxiv.org/abs/2404.19427v1), [pdf](http://arxiv.org/pdf/2404.19427v1.pdf), cication: [**-1**](None)

	 *Chanran Kim, Jeongin Lee, Shichang Joung, Bongmo Kim, Yeul-Min Baek*
- **CharacterFactory: Sampling Consistent Characters with GANs for Diffusion
  Models**, `arXiv, 2404.15677`, [arxiv](http://arxiv.org/abs/2404.15677v1), [pdf](http://arxiv.org/pdf/2404.15677v1.pdf), cication: [**-1**](None)

	 *Qinghe Wang, Baolu Li, Xiaomin Li, Bing Cao, Liqian Ma, Huchuan Lu, Xu Jia* · ([CharacterFactory](https://github.com/qinghew/CharacterFactory) - qinghew) ![Star](https://img.shields.io/github/stars/qinghew/CharacterFactory.svg?style=social&label=Star) · ([qinghew.github](https://qinghew.github.io/CharacterFactory/))
- **ConsistentID: Portrait Generation with Multimodal Fine-Grained Identity
  Preserving**, `arXiv, 2404.16771`, [arxiv](http://arxiv.org/abs/2404.16771v1), [pdf](http://arxiv.org/pdf/2404.16771v1.pdf), cication: [**-1**](None)

	 *Jiehui Huang, Xiao Dong, Wenhui Song, Hanhui Li, Jun Zhou, Yuhao Cheng, Shutao Liao, Long Chen, Yiqiang Yan, Shengcai Liao* · ([ssugarwh.github](https://ssugarwh.github.io/consistentid.github.io/))
- **PuLID: Pure and Lightning ID Customization via Contrastive Alignment**, `arXiv, 2404.16022`, [arxiv](http://arxiv.org/abs/2404.16022v1), [pdf](http://arxiv.org/pdf/2404.16022v1.pdf), cication: [**-1**](None)

	 *Zinan Guo, Yanze Wu, Zhuowei Chen, Lang Chen, Qian He* · ([PuLID](https://github.com/ToTheBeginning/PuLID) - ToTheBeginning) ![Star](https://img.shields.io/github/stars/ToTheBeginning/PuLID.svg?style=social&label=Star)
- **ID-Aligner: Enhancing Identity-Preserving Text-to-Image Generation with
  Reward Feedback Learning**, `arXiv, 2404.15449`, [arxiv](http://arxiv.org/abs/2404.15449v1), [pdf](http://arxiv.org/pdf/2404.15449v1.pdf), cication: [**-1**](None)

	 *Weifeng Chen, Jiacheng Zhang, Jie Wu, Hefeng Wu, Xuefeng Xiao, Liang Lin*
- **MultiBooth: Towards Generating All Your Concepts in an Image from Text**, `arXiv, 2404.14239`, [arxiv](http://arxiv.org/abs/2404.14239v1), [pdf](http://arxiv.org/pdf/2404.14239v1.pdf), cication: [**-1**](None)

	 *Chenyang Zhu, Kai Li, Yue Ma, Chunming He, Li Xiu* · ([multibooth.github](https://multibooth.github.io/))
- **MoA: Mixture-of-Attention for Subject-Context Disentanglement in
  Personalized Image Generation**, `arXiv, 2404.11565`, [arxiv](http://arxiv.org/abs/2404.11565v1), [pdf](http://arxiv.org/pdf/2404.11565v1.pdf), cication: [**-1**](None)

	 *Kuan-Chieh, Wang, Daniil Ostashev, Yuwei Fang, Sergey Tulyakov, Kfir Aberman* · ([snap-research.github](https://snap-research.github.io/mixture-of-attention/))
- **MoMA: Multimodal LLM Adapter for Fast Personalized Image Generation**, `arXiv, 2404.05674`, [arxiv](http://arxiv.org/abs/2404.05674v1), [pdf](http://arxiv.org/pdf/2404.05674v1.pdf), cication: [**-1**](None)

	 *Kunpeng Song, Yizhe Zhu, Bingchen Liu, Qing Yan, Ahmed Elgammal, Xiao Yang*
- [**face-to-all**](https://huggingface.co/spaces/multimodalart/face-to-all) - multimodalart 🤗
- **Arc2Face: A Foundation Model of Human Faces**, `arXiv, 2403.11641`, [arxiv](http://arxiv.org/abs/2403.11641v1), [pdf](http://arxiv.org/pdf/2403.11641v1.pdf), cication: [**-1**](None)

	 *Foivos Paraperas Papantoniou, Alexandros Lattas, Stylianos Moschoglou, Jiankang Deng, Bernhard Kainz, Stefanos Zafeiriou* · ([arc2face.github](https://arc2face.github.io/)) · ([Arc2Face](https://github.com/foivospar/Arc2Face) - foivospar) ![Star](https://img.shields.io/github/stars/foivospar/Arc2Face.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/spaces/FoivosPar/Arc2Face))
- **FlashFace: Human Image Personalization with High-fidelity Identity
  Preservation**, `arXiv, 2403.17008`, [arxiv](http://arxiv.org/abs/2403.17008v1), [pdf](http://arxiv.org/pdf/2403.17008v1.pdf), cication: [**-1**](None)

	 *Shilong Zhang, Lianghua Huang, Xi Chen, Yifei Zhang, Zhi-Fan Wu, Yutong Feng, Wei Wang, Yujun Shen, Yu Liu, Ping Luo*

	 · ([jshilong.github](https://jshilong.github.io/flashface-page))
- **OMG: Occlusion-friendly Personalized Multi-concept Generation in
  Diffusion Models**, `arXiv, 2403.10983`, [arxiv](http://arxiv.org/abs/2403.10983v1), [pdf](http://arxiv.org/pdf/2403.10983v1.pdf), cication: [**-1**](None)

	 *Zhe Kong, Yong Zhang, Tianyu Yang, Tao Wang, Kaihao Zhang, Bizhu Wu, Guanying Chen, Wei Liu, Wenhan Luo* · ([omg](https://github.com/kongzhecn/omg) - kongzhecn) ![Star](https://img.shields.io/github/stars/kongzhecn/omg.svg?style=social&label=Star)
- **IDAdapter: Learning Mixed Features for Tuning-Free Personalization of
  Text-to-Image Models**, `arXiv, 2403.13535`, [arxiv](http://arxiv.org/abs/2403.13535v1), [pdf](http://arxiv.org/pdf/2403.13535v1.pdf), cication: [**-1**](None)

	 *Siying Cui, Jiankang Deng, Jia Guo, Xiang An, Yongle Zhao, Xinyu Wei, Ziyong Feng*
- **Infinite-ID: Identity-preserved Personalization via ID-semantics
  Decoupling Paradigm**, `arXiv, 2403.11781`, [arxiv](http://arxiv.org/abs/2403.11781v1), [pdf](http://arxiv.org/pdf/2403.11781v1.pdf), cication: [**-1**](None)

	 *Yi Wu, Ziqiang Li, Heliang Zheng, Chaoyue Wang, Bin Li*
- **SSR-Encoder: Encoding Selective Subject Representation for
  Subject-Driven Generation**, `arXiv, 2312.16272`, [arxiv](http://arxiv.org/abs/2312.16272v2), [pdf](http://arxiv.org/pdf/2312.16272v2.pdf), cication: [**-1**](None)

	 *Yuxuan Zhang, Yiren Song, Jiaming Liu, Rui Wang, Jinpeng Yu, Hao Tang, Huaxia Li, Xu Tang, Yao Hu, Han Pan* · ([SSR_Encoder](https://github.com/Xiaojiu-z/SSR_Encoder) - Xiaojiu-z) ![Star](https://img.shields.io/github/stars/Xiaojiu-z/SSR_Encoder.svg?style=social&label=Star)

## Super Resolutions
- **Retinexformer: One-stage Retinex-based Transformer for Low-light Image
  Enhancement**, `ICCV, 2023`, [arxiv](http://arxiv.org/abs/2303.06705v3), [pdf](http://arxiv.org/pdf/2303.06705v3.pdf), cication: [**126**](https://scholar.google.com/scholar?cites=14225312754574154631&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yuanhao Cai, Hao Bian, Jing Lin, Haoqian Wang, Radu Timofte, Yulun Zhang* · ([retinexformer](https://github.com/caiyuanhao1998/retinexformer) - caiyuanhao1998) ![Star](https://img.shields.io/github/stars/caiyuanhao1998/retinexformer.svg?style=social&label=Star)
- **LinFusion: 1 GPU, 1 Minute, 16K Image**, `arXiv, 2409.02097`, [arxiv](http://arxiv.org/abs/2409.02097v2), [pdf](http://arxiv.org/pdf/2409.02097v2.pdf), cication: [**-1**](None)

	 *Songhua Liu, Weihao Yu, Zhenxiong Tan, Xinchao Wang* · ([LinFusion](https://github.com/Huage001/LinFusion) - Huage001) ![Star](https://img.shields.io/github/stars/Huage001/LinFusion.svg?style=social&label=Star) · ([lv-linfusion.github](https://lv-linfusion.github.io/))
- [**aura-sr**](https://github.com/fal-ai/aura-sr) - fal-ai ![Star](https://img.shields.io/github/stars/fal-ai/aura-sr.svg?style=social&label=Star)

	 *AuraSR: GAN-based Super-Resolution for real-world*
- [[2408.11001] MegaFusion: Extend Diffusion Models towards Higher-resolution Image Generation without Further Tuning](https://arxiv.org/abs/2408.11001/)

	 · ([haoningwu3639.github](https://haoningwu3639.github.io/MegaFusion/)) · ([MegaFusion](https://github.com/ShaochengShen/MegaFusion/) - ShaochengShen) ![Star](https://img.shields.io/github/stars/ShaochengShen/MegaFusion.svg?style=social&label=Star)
- **Kalman-Inspired Feature Propagation for Video Face Super-Resolution**, `arXiv, 2408.05205`, [arxiv](http://arxiv.org/abs/2408.05205v1), [pdf](http://arxiv.org/pdf/2408.05205v1.pdf), cication: [**-1**](None)

	 *Ruicheng Feng, Chongyi Li, Chen Change Loy* · ([jnjaby.github](https://jnjaby.github.io/projects/KEEP/))
- **Arbitrary-Scale Video Super-Resolution with Structural and Textural
  Priors**, `arXiv, 2407.09919`, [arxiv](http://arxiv.org/abs/2407.09919v1), [pdf](http://arxiv.org/pdf/2407.09919v1.pdf), cication: [**-1**](None)

	 *Wei Shang, Dongwei Ren, Wanying Zhang, Yuming Fang, Wangmeng Zuo, Kede Ma* · ([st-avsr](https://github.com/shangwei5/st-avsr) - shangwei5) ![Star](https://img.shields.io/github/stars/shangwei5/st-avsr.svg?style=social&label=Star)
- [Tile controlnet + Tiled diffusion = very realistic upscaler workflow : r/StableDiffusion](https://www.reddit.com/r/StableDiffusion/comments/1e3v6jy/tile_controlnet_tiled_diffusion_very_realistic/)
- **UltraPixel: Advancing Ultra-High-Resolution Image Synthesis to New Peaks**, `arXiv, 2407.02158`, [arxiv](http://arxiv.org/abs/2407.02158v2), [pdf](http://arxiv.org/pdf/2407.02158v2.pdf), cication: [**-1**](None)

	 *Jingjing Ren, Wenbo Li, Haoyu Chen, Renjing Pei, Bin Shao, Yong Guo, Long Peng, Fenglong Song, Lei Zhu*

	 · ([jingjingrenabc.github](https://jingjingrenabc.github.io/ultrapixel/))
- **EvTexture: Event-driven Texture Enhancement for Video Super-Resolution**, `arXiv, 2406.13457`, [arxiv](http://arxiv.org/abs/2406.13457v1), [pdf](http://arxiv.org/pdf/2406.13457v1.pdf), cication: [**-1**](None)

	 *Dachun Kai, Jiayao Lu, Yueyi Zhang, Xiaoyan Sun*

	 · ([evtexture](https://github.com/dachunkai/evtexture) - dachunkai) ![Star](https://img.shields.io/github/stars/dachunkai/evtexture.svg?style=social&label=Star)
- **ResMaster: Mastering High-Resolution Image Generation via Structural and
  Fine-Grained Guidance**, `arXiv, 2406.16476`, [arxiv](http://arxiv.org/abs/2406.16476v1), [pdf](http://arxiv.org/pdf/2406.16476v1.pdf), cication: [**-1**](None)

	 *Shuwei Shi, Wenbo Li, Yuechen Zhang, Jingwen He, Biao Gong, Yinqiang Zheng* · ([ResMaster](https://github.com/Shuweis/ResMaster) - Shuweis) ![Star](https://img.shields.io/github/stars/Shuweis/ResMaster.svg?style=social&label=Star) · ([shuweis.github](https://shuweis.github.io/ResMaster/))
- [**AuraSR**](https://huggingface.co/fal-ai/AuraSR) - fal-ai 🤗
- **BeyondScene: Higher-Resolution Human-Centric Scene Generation With
  Pretrained Diffusion**, `arXiv, 2404.04544`, [arxiv](http://arxiv.org/abs/2404.04544v1), [pdf](http://arxiv.org/pdf/2404.04544v1.pdf), cication: [**-1**](None)

	 *Gwanghyun Kim, Hayeon Kim, Hoigi Seo, Dong Un Kang, Se Young Chun*
- [**upscayl**](https://github.com/upscayl/upscayl) - upscayl ![Star](https://img.shields.io/github/stars/upscayl/upscayl.svg?style=social&label=Star)

	 *🆙 Upscayl - Free and Open Source AI Image Upscaler for Linux, MacOS and Windows built with Linux-First philosophy.*
- **APISR: Anime Production Inspired Real-World Anime Super-Resolution**, `arXiv, 2403.01598`, [arxiv](http://arxiv.org/abs/2403.01598v1), [pdf](http://arxiv.org/pdf/2403.01598v1.pdf), cication: [**-1**](None)

	 *Boyang Wang, Fengyu Yang, Xihang Yu, Chao Zhang, Hanbin Zhao* · ([apisr](https://github.com/kiteretsu77/apisr) - kiteretsu77) ![Star](https://img.shields.io/github/stars/kiteretsu77/apisr.svg?style=social&label=Star)

## Try-On
- **Improving Virtual Try-On with Garment-focused Diffusion Models**, `arXiv, 2409.08258`, [arxiv](http://arxiv.org/abs/2409.08258v1), [pdf](http://arxiv.org/pdf/2409.08258v1.pdf), cication: [**-1**](None)

	 *Siqi Wan, Yehao Li, Jingwen Chen, Yingwei Pan, Ting Yao, Yang Cao, Tao Mei* · ([GarDiff](https://github.com/siqi0905/GarDiff/tree/master) - siqi0905) ![Star](https://img.shields.io/github/stars/siqi0905/GarDiff.svg?style=social&label=Star)
- **CatVTON: Concatenation Is All You Need for Virtual Try-On with Diffusion
  Models**, `arXiv, 2407.15886`, [arxiv](http://arxiv.org/abs/2407.15886v1), [pdf](http://arxiv.org/pdf/2407.15886v1.pdf), cication: [**-1**](None)

	 *Zheng Chong, Xiao Dong, Haoxiang Li, Shiyue Zhang, Wenqing Zhang, Xujie Zhang, Hanqing Zhao, Xiaodan Liang*

	 · ([catvton](https://github.com/zheng-chong/catvton) - zheng-chong) ![Star](https://img.shields.io/github/stars/zheng-chong/catvton.svg?style=social&label=Star)
- **OutfitAnyone: Ultra-high Quality Virtual Try-On for Any Clothing and Any
  Person**, `arXiv, 2407.16224`, [arxiv](http://arxiv.org/abs/2407.16224v1), [pdf](http://arxiv.org/pdf/2407.16224v1.pdf), cication: [**-1**](None)

	 *Ke Sun, Jian Cao, Qi Wang, Linrui Tian, Xindi Zhang, Lian Zhuo, Bang Zhang, Liefeng Bo, Wenbo Zhou, Weiming Zhang* · ([humanaigc.github](https://humanaigc.github.io/outfit-anyone/)) · ([OutfitAnyone](https://github.com/HumanAIGC/OutfitAnyone) - HumanAIGC) ![Star](https://img.shields.io/github/stars/HumanAIGC/OutfitAnyone.svg?style=social&label=Star)
- **IMAGDressing-v1: Customizable Virtual Dressing**, `arXiv, 2407.12705`, [arxiv](http://arxiv.org/abs/2407.12705v1), [pdf](http://arxiv.org/pdf/2407.12705v1.pdf), cication: [**-1**](None)

	 *Fei Shen, Xin Jiang, Xin He, Hu Ye, Cong Wang, Xiaoyu Du, Zechao Li, Jinghui Tang* · ([imagdressing](https://github.com/muzishen/imagdressing) - muzishen) ![Star](https://img.shields.io/github/stars/muzishen/imagdressing.svg?style=social&label=Star)
- **WildVidFit: Video Virtual Try-On in the Wild via Image-Based Controlled
  Diffusion Models**, `arXiv, 2407.10625`, [arxiv](http://arxiv.org/abs/2407.10625v1), [pdf](http://arxiv.org/pdf/2407.10625v1.pdf), cication: [**-1**](None)

	 *Zijian He, Peixin Chen, Guangrun Wang, Guanbin Li, Philip H. S. Torr, Liang Lin* · ([wildvidfit-project.github](http://wildvidfit-project.github.io/))
- **ViViD: Video Virtual Try-on using Diffusion Models**, `arXiv, 2405.11794`, [arxiv](http://arxiv.org/abs/2405.11794v1), [pdf](http://arxiv.org/pdf/2405.11794v1.pdf), cication: [**-1**](None)

	 *Zixun Fang, Wei Zhai, Aimin Su, Hongliang Song, Kai Zhu, Mao Wang, Yu Chen, Zhiheng Liu, Yang Cao, Zheng-Jun Zha* · ([becauseimbatman0.github](https://becauseimbatman0.github.io/ViViD)) · ([ViViD](https://github.com/BecauseImBatman0/ViViD) - BecauseImBatman0) ![Star](https://img.shields.io/github/stars/BecauseImBatman0/ViViD.svg?style=social&label=Star)
- **Improving Diffusion Models for Virtual Try-on**, `arXiv, 2403.05139`, [arxiv](http://arxiv.org/abs/2403.05139v2), [pdf](http://arxiv.org/pdf/2403.05139v2.pdf), cication: [**-1**](None)

	 *Yisol Choi, Sangkyung Kwak, Kyungmin Lee, Hyungwon Choi, Jinwoo Shin* · ([IDM-VTON](https://github.com/yisol/IDM-VTON) - yisol) ![Star](https://img.shields.io/github/stars/yisol/IDM-VTON.svg?style=social&label=Star)
- **Magic Clothing: Controllable Garment-Driven Image Synthesis**, `arXiv, 2404.09512`, [arxiv](http://arxiv.org/abs/2404.09512v1), [pdf](http://arxiv.org/pdf/2404.09512v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=9611620576309210958&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Weifeng Chen, Tao Gu, Yuhao Xu, Chengcai Chen* · ([MagicClothing](https://github.com/ShineChen1024/MagicClothing?tab=readme-ov-file) - ShineChen1024) ![Star](https://img.shields.io/github/stars/ShineChen1024/MagicClothing.svg?style=social&label=Star)
- **Wear-Any-Way: Manipulable Virtual Try-on via Sparse Correspondence
  Alignment**, `arXiv, 2403.12965`, [arxiv](http://arxiv.org/abs/2403.12965v1), [pdf](http://arxiv.org/pdf/2403.12965v1.pdf), cication: [**-1**](None)

	 *Mengting Chen, Xi Chen, Zhonghua Zhai, Chen Ju, Xuewen Hong, Jinsong Lan, Shuai Xiao*

---
- [**awesome-virtual-try-on**](https://github.com/minar09/awesome-virtual-try-on) - minar09 ![Star](https://img.shields.io/github/stars/minar09/awesome-virtual-try-on.svg?style=social&label=Star)

	 *A curated list of awesome research papers, projects, code, dataset, workshops etc. related to virtual try-on.*
- [CVPR 2024 Workshop: Virtual Try-On](https://vto-cvpr24.github.io/index.html)
- [基于Stable Diffusion的AIGC服饰穿搭实践-CSDN博客](https://blog.csdn.net/Taobaojishu/article/details/132632670)

## Projects
- [Site Unreachable](https://blog.novelai.net/image-generation-announcement-807b3cf0afec)

	 · ([huggingface](https://huggingface.co/NovelAI/nai-anime-v1-full))
- [Towards Pony Diffusion V7, going with the flow. | Civitai](https://civitai.com/articles/6309)
- [**PixArt-Sigma-900M**](https://huggingface.co/dataautogpt3/PixArt-Sigma-900M) - dataautogpt3 🤗
- [**littletinies**](https://huggingface.co/alvdansen/littletinies) - alvdansen 🤗
- [**AuraFlow**](https://huggingface.co/fal/AuraFlow) - fal 🤗

	 · ([blog.fal](https://blog.fal.ai/auraflow/))
- [**DiffSynth-Studio**](https://github.com/modelscope/DiffSynth-Studio?tab=readme-ov-file) - modelscope ![Star](https://img.shields.io/github/stars/modelscope/DiffSynth-Studio.svg?style=social&label=Star)

	 *Enjoy the magic of Diffusion models!*
- [**kivotos-xl-2.0**](https://huggingface.co/yodayo-ai/kivotos-xl-2.0) - yodayo-ai 🤗
- [**Fluently-XL-Final**](https://huggingface.co/fluently/Fluently-XL-Final) - fluently 🤗
- [**cosxl**](https://huggingface.co/spaces/multimodalart/cosxl) - multimodalart 🤗
- [Future of E-commerce?! Virtual clothing try-on agent - YouTube](https://www.youtube.com/watch?v=C94pTaKoLbU&ab_channel=AIJason)
- [**animagine-xl-3.0**](https://huggingface.co/cagliostrolab/animagine-xl-3.0) - cagliostrolab 🤗

	 · ([huggingface](https://huggingface.co/spaces/Linaqruf/animagine-xl))

## Optimization
- **RealisHuman: A Two-Stage Approach for Refining Malformed Human Parts in
  Generated Images**, `arXiv, 2409.03644`, [arxiv](http://arxiv.org/abs/2409.03644v1), [pdf](http://arxiv.org/pdf/2409.03644v1.pdf), cication: [**-1**](None)

	 *Benzhi Wang, Jingkai Zhou, Jingqi Bai, Yang Yang, Weihua Chen, Fan Wang, Zhen Lei* · ([RealisHuman](https://github.com/Wangbenzhi/RealisHuman) - Wangbenzhi) ![Star](https://img.shields.io/github/stars/Wangbenzhi/RealisHuman.svg?style=social&label=Star)
- **SaRA: High-Efficient Diffusion Model Fine-tuning with Progressive Sparse
  Low-Rank Adaptation**, `arXiv, 2409.06633`, [arxiv](http://arxiv.org/abs/2409.06633v1), [pdf](http://arxiv.org/pdf/2409.06633v1.pdf), cication: [**-1**](None)

	 *Teng Hu, Jiangning Zhang, Ran Yi, Hongrui Huang, Yabiao Wang, Lizhuang Ma* · ([sjtuplayer.github](https://sjtuplayer.github.io/projects/SaRA/))
- **HumanRefiner: Benchmarking Abnormal Human Generation and Refining with
  Coarse-to-fine Pose-Reversible Guidance**, `arXiv, 2407.06937`, [arxiv](http://arxiv.org/abs/2407.06937v1), [pdf](http://arxiv.org/pdf/2407.06937v1.pdf), cication: [**-1**](None)

	 *Guian Fang, Wenbiao Yan, Yuanfan Guo, Jianhua Han, Zutao Jiang, Hang Xu, Shengcai Liao, Xiaodan Liang* · ([HumanRefiner](https://github.com/Enderfga/HumanRefiner) - Enderfga) ![Star](https://img.shields.io/github/stars/Enderfga/HumanRefiner.svg?style=social&label=Star)
- **Diffusion Forcing: Next-token Prediction Meets Full-Sequence Diffusion**, `arXiv, 2407.01392`, [arxiv](http://arxiv.org/abs/2407.01392v3), [pdf](http://arxiv.org/pdf/2407.01392v3.pdf), cication: [**-1**](None)

	 *Boyuan Chen, Diego Marti Monso, Yilun Du, Max Simchowitz, Russ Tedrake, Vincent Sitzmann*

	 · ([diffusion-forcing](https://github.com/buoyancy99/diffusion-forcing) - buoyancy99) ![Star](https://img.shields.io/github/stars/buoyancy99/diffusion-forcing.svg?style=social&label=Star)
- **No Training, No Problem: Rethinking Classifier-Free Guidance for
  Diffusion Models**, `arXiv, 2407.02687`, [arxiv](http://arxiv.org/abs/2407.02687v1), [pdf](http://arxiv.org/pdf/2407.02687v1.pdf), cication: [**-1**](None)

	 *Seyedmorteza Sadat, Manuel Kansy, Otmar Hilliges, Romann M. Weber*

	 · ([twitter](https://twitter.com/Msadat97/status/1808780460912263418))
- **Aligning Diffusion Models with Noise-Conditioned Perception**, `arXiv, 2406.17636`, [arxiv](http://arxiv.org/abs/2406.17636v1), [pdf](http://arxiv.org/pdf/2406.17636v1.pdf), cication: [**-1**](None)

	 *Alexander Gambashidze, Anton Kulikov, Yuriy Sosnin, Ilya Makarov* · ([huggingface](https://huggingface.co/alexgambashidze/SDXL_NCP-DPO_v0.1))
- **Beyond Thumbs Up/Down: Untangling Challenges of Fine-Grained Feedback
  for Text-to-Image Generation**, `arXiv, 2406.16807`, [arxiv](http://arxiv.org/abs/2406.16807v1), [pdf](http://arxiv.org/pdf/2406.16807v1.pdf), cication: [**-1**](None)

	 *Katherine M. Collins, Najoung Kim, Yonatan Bitton, Verena Rieser, Shayegan Omidshafiei, Yushi Hu, Sherol Chen, Senjuti Dutta, Minsuk Chang, Kimin Lee*
- **Alleviating Distortion in Image Generation via Multi-Resolution
  Diffusion Models**, `arXiv, 2406.09416`, [arxiv](http://arxiv.org/abs/2406.09416v1), [pdf](http://arxiv.org/pdf/2406.09416v1.pdf), cication: [**-1**](None)

	 *Qihao Liu, Zhanpeng Zeng, Ju He, Qihang Yu, Xiaohui Shen, Liang-Chieh Chen* · ([qihao067.github](https://qihao067.github.io/projects/DiMR))
- **Margin-aware Preference Optimization for Aligning Diffusion Models
  without Reference**, `arXiv, 2406.06424`, [arxiv](http://arxiv.org/abs/2406.06424v1), [pdf](http://arxiv.org/pdf/2406.06424v1.pdf), cication: [**-1**](None)

	 *Jiwoo Hong, Sayak Paul, Noah Lee, Kashif Rasul, James Thorne, Jongheon Jeong*
- **Step-aware Preference Optimization: Aligning Preference with Denoising
  Performance at Each Step**, `arXiv, 2406.04314`, [arxiv](http://arxiv.org/abs/2406.04314v1), [pdf](http://arxiv.org/pdf/2406.04314v1.pdf), cication: [**-1**](None)

	 *Zhanhao Liang, Yuhui Yuan, Shuyang Gu, Bohan Chen, Tiankai Hang, Ji Li, Liang Zheng* · ([rockeycoss.github](https://rockeycoss.github.io/spo.github.io/))

	 · ([SPO](https://github.com/RockeyCoss/SPO) - RockeyCoss) ![Star](https://img.shields.io/github/stars/RockeyCoss/SPO.svg?style=social&label=Star)
- **Guiding a Diffusion Model with a Bad Version of Itself**, `arXiv, 2406.02507`, [arxiv](http://arxiv.org/abs/2406.02507v1), [pdf](http://arxiv.org/pdf/2406.02507v1.pdf), cication: [**-1**](None)

	 *Tero Karras, Miika Aittala, Tuomas Kynkäänniemi, Jaakko Lehtinen, Timo Aila, Samuli Laine*
- **Aligning Diffusion Models by Optimizing Human Utility**, `arXiv, 2404.04465`, [arxiv](http://arxiv.org/abs/2404.04465v1), [pdf](http://arxiv.org/pdf/2404.04465v1.pdf), cication: [**-1**](None)

	 *Shufan Li, Konstantinos Kallidromitis, Akash Gokul, Yusuke Kato, Kazuki Kozuka*
- **RL for Consistency Models: Faster Reward Guided Text-to-Image Generation**, `arXiv, 2404.03673`, [arxiv](http://arxiv.org/abs/2404.03673v1), [pdf](http://arxiv.org/pdf/2404.03673v1.pdf), cication: [**-1**](None)

	 *Owen Oertell, Jonathan D. Chang, Yiyi Zhang, Kianté Brantley, Wen Sun* · ([rlcm.owenoertell](https://rlcm.owenoertell.com))
- **On the Scalability of Diffusion-based Text-to-Image Generation**, `arXiv, 2404.02883`, [arxiv](http://arxiv.org/abs/2404.02883v1), [pdf](http://arxiv.org/pdf/2404.02883v1.pdf), cication: [**-1**](None)

	 *Hao Li, Yang Zou, Ying Wang, Orchid Majumder, Yusheng Xie, R. Manmatha, Ashwin Swaminathan, Zhuowen Tu, Stefano Ermon, Stefano Soatto*
- **Bigger is not Always Better: Scaling Properties of Latent Diffusion
  Models**, `arXiv, 2404.01367`, [arxiv](http://arxiv.org/abs/2404.01367v1), [pdf](http://arxiv.org/pdf/2404.01367v1.pdf), cication: [**-1**](None)

	 *Kangfu Mei, Zhengzhong Tu, Mauricio Delbracio, Hossein Talebi, Vishal M. Patel, Peyman Milanfar*
- **Improving Text-to-Image Consistency via Automatic Prompt Optimization**, `arXiv, 2403.17804`, [arxiv](http://arxiv.org/abs/2403.17804v1), [pdf](http://arxiv.org/pdf/2403.17804v1.pdf), cication: [**-1**](None)

	 *Oscar Mañas, Pietro Astolfi, Melissa Hall, Candace Ross, Jack Urbanek, Adina Williams, Aishwarya Agrawal, Adriana Romero-Soriano, Michal Drozdzal*
- **Analyzing and Improving the Training Dynamics of Diffusion Models**, `arXiv, 2312.02696`, [arxiv](http://arxiv.org/abs/2312.02696v2), [pdf](http://arxiv.org/pdf/2312.02696v2.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=3838550793208248689&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Tero Karras, Miika Aittala, Jaakko Lehtinen, Janne Hellsten, Timo Aila, Samuli Laine*

	 · ([edm2](https://github.com/nvlabs/edm2) - nvlabs) ![Star](https://img.shields.io/github/stars/nvlabs/edm2.svg?style=social&label=Star)
- **Rich Human Feedback for Text-to-Image Generation**, `CVPR, 2024`, [arxiv](http://arxiv.org/abs/2312.10240v2), [pdf](http://arxiv.org/pdf/2312.10240v2.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=9126507859941467026&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Youwei Liang, Junfeng He, Gang Li, Peizhao Li, Arseniy Klimovskiy, Nicholas Carolan, Jiao Sun, Jordi Pont-Tuset, Sarah Young, Feng Yang*

## Toolkits
- [**DiffusionKit**](https://github.com/argmaxinc/DiffusionKit) - argmaxinc ![Star](https://img.shields.io/github/stars/argmaxinc/DiffusionKit.svg?style=social&label=Star)

	 *On-device Inference of Diffusion Models for Apple Silicon*
- [**stable-diffusion-webui-forge**](https://github.com/lllyasviel/stable-diffusion-webui-forge/) - lllyasviel ![Star](https://img.shields.io/github/stars/lllyasviel/stable-diffusion-webui-forge.svg?style=social&label=Star)
- [**ai-toolkit**](https://github.com/ostris/ai-toolkit) - ostris ![Star](https://img.shields.io/github/stars/ostris/ai-toolkit.svg?style=social&label=Star)

	 *Various AI scripts. Mostly Stable Diffusion stuff.*
- [**SimpleTuner**](https://github.com/bghira/SimpleTuner) - bghira ![Star](https://img.shields.io/github/stars/bghira/SimpleTuner.svg?style=social&label=Star)

	 *A general fine-tuning kit geared toward Stable Diffusion 2.1, Stable Diffusion 3, DeepFloyd, and SDXL.*
- [stabilityai/cosxl at main](https://huggingface.co/stabilityai/cosxl/tree/main)
- [**Enhance-This-HiDiffusion-SDXL**](https://huggingface.co/spaces/radames/Enhance-This-HiDiffusion-SDXL) - radames 🤗
- [**d3pm**](https://github.com/cloneofsimo/d3pm) - cloneofsimo ![Star](https://img.shields.io/github/stars/cloneofsimo/d3pm.svg?style=social&label=Star)

	 *Minimal Implementation of a D3PM in pytorch*
- [**rembg-webapp-tutorial**](https://github.com/codediodeio/rembg-webapp-tutorial) - codediodeio ![Star](https://img.shields.io/github/stars/codediodeio/rembg-webapp-tutorial.svg?style=social&label=Star)

	 *a simple webapp with rembg*
- [**clarity-upscaler**](https://github.com/philz1337x/clarity-upscaler) - philz1337x ![Star](https://img.shields.io/github/stars/philz1337x/clarity-upscaler.svg?style=social&label=Star)

	 *Clarity-Upscaler: Reimagined image upscaling for everyone*

## Evaluation
- [**K-Sort-Arena**](https://huggingface.co/spaces/ksort/K-Sort-Arena) - ksort 🤗
- **MJ-Bench: Is Your Multimodal Reward Model Really a Good Judge for
  Text-to-Image Generation?**, `arXiv, 2407.04842`, [arxiv](http://arxiv.org/abs/2407.04842v1), [pdf](http://arxiv.org/pdf/2407.04842v1.pdf), cication: [**-1**](None)

	 *Zhaorun Chen, Yichao Du, Zichen Wen, Yiyang Zhou, Chenhang Cui, Zhenzhen Weng, Haoqin Tu, Chaoqi Wang, Zhengwei Tong, Qinglan Huang*

	 · ([MJ-Bench](https://github.com/MJ-Bench/MJ-Bench) - MJ-Bench) ![Star](https://img.shields.io/github/stars/MJ-Bench/MJ-Bench.svg?style=social&label=Star)
- **Fantastic Copyrighted Beasts and How (Not) to Generate Them**, `arXiv, 2406.14526`, [arxiv](http://arxiv.org/abs/2406.14526v1), [pdf](http://arxiv.org/pdf/2406.14526v1.pdf), cication: [**-1**](None)

	 *Luxi He, Yangsibo Huang, Weijia Shi, Tinghao Xie, Haotian Liu, Yue Wang, Luke Zettlemoyer, Chiyuan Zhang, Danqi Chen, Peter Henderson* · ([qbitai](https://www.qbitai.com/2024/06/158556.html))
- **DreamBench++: A Human-Aligned Benchmark for Personalized Image
  Generation**, `arXiv, 2406.16855`, [arxiv](http://arxiv.org/abs/2406.16855v1), [pdf](http://arxiv.org/pdf/2406.16855v1.pdf), cication: [**-1**](None)

	 *Yuang Peng, Yuxin Cui, Haomiao Tang, Zekun Qi, Runpei Dong, Jing Bai, Chunrui Han, Zheng Ge, Xiangyu Zhang, Shu-Tao Xia*
- **A-Bench: Are LMMs Masters at Evaluating AI-generated Images?**, `arXiv, 2406.03070`, [arxiv](http://arxiv.org/abs/2406.03070v1), [pdf](http://arxiv.org/pdf/2406.03070v1.pdf), cication: [**-1**](None)

	 *Zicheng Zhang, Haoning Wu, Chunyi Li, Yingjie Zhou, Wei Sun, Xiongkuo Min, Zijian Chen, Xiaohong Liu, Weisi Lin, Guangtao Zhai* · ([a-bench](https://github.com/q-future/a-bench) - q-future) ![Star](https://img.shields.io/github/stars/q-future/a-bench.svg?style=social&label=Star)
- [Launching the Artificial Analysis Text to Image Leaderboard & Arena](https://huggingface.co/blog/leaderboard-artificial-analysis2)
- **Revisiting Text-to-Image Evaluation with Gecko: On Metrics, Prompts, and
  Human Ratings**, `arXiv, 2404.16820`, [arxiv](http://arxiv.org/abs/2404.16820v1), [pdf](http://arxiv.org/pdf/2404.16820v1.pdf), cication: [**-1**](None)

	 *Olivia Wiles, Chuhan Zhang, Isabela Albuquerque, Ivana Kajić, Su Wang, Emanuele Bugliarello, Yasumasa Onoe, Chris Knutsen, Cyrus Rashtchian, Jordi Pont-Tuset*
- [Evaluating Text-to-Visual Generation with Image-to-Text Generation](https://linzhiqiu.github.io/papers/vqascore/)

	 · ([t2v_metrics](https://github.com/linzhiqiu/t2v_metrics) - linzhiqiu) ![Star](https://img.shields.io/github/stars/linzhiqiu/t2v_metrics.svg?style=social&label=Star)
- **Rethinking FID: Towards a Better Evaluation Metric for Image Generation**, `arXiv, 2401.09603`, [arxiv](http://arxiv.org/abs/2401.09603v2), [pdf](http://arxiv.org/pdf/2401.09603v2.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=13719089543049798984&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Sadeep Jayasumana, Srikumar Ramalingam, Andreas Veit, Daniel Glasner, Ayan Chakrabarti, Sanjiv Kumar* · ([google-research](https://github.com/google-research/google-research/tree/master/cmmd) - google-research) ![Star](https://img.shields.io/github/stars/google-research/google-research.svg?style=social&label=Star)
- **Measuring Style Similarity in Diffusion Models**, `arXiv, 2404.01292`, [arxiv](http://arxiv.org/abs/2404.01292v1), [pdf](http://arxiv.org/pdf/2404.01292v1.pdf), cication: [**-1**](None)

	 *Gowthami Somepalli, Anubhav Gupta, Kamal Gupta, Shramay Palta, Micah Goldblum, Jonas Geiping, Abhinav Shrivastava, Tom Goldstein* · ([CSD](https://github.com/learn2phoenix/CSD) - learn2phoenix) ![Star](https://img.shields.io/github/stars/learn2phoenix/CSD.svg?style=social&label=Star)

## Other
- **Interpreting the Weight Space of Customized Diffusion Models**, `arXiv, 2406.09413`, [arxiv](http://arxiv.org/abs/2406.09413v1), [pdf](http://arxiv.org/pdf/2406.09413v1.pdf), cication: [**-1**](None)

	 *Amil Dravid, Yossi Gandelsman, Kuan-Chieh Wang, Rameen Abdal, Gordon Wetzstein, Alexei A. Efros, Kfir Aberman*

## Chat Image
- **Teaching Text-to-Image Models to Communicate in Dialog**, `arXiv, 2309.15516`, [arxiv](http://arxiv.org/abs/2309.15516v2), [pdf](http://arxiv.org/pdf/2309.15516v2.pdf), cication: [**-1**](None)

	 *Xiaowen Sun, Jiazhan Feng, Yuxuan Wang, Yuxuan Lai, Xingyu Shen, Dongyan Zhao*

## Products
- [Rubbrband](https://www.rubbrband.com/roi)
- [RenderNet - Create AI images with Unmatched Control](https://rendernet.ai/?via=chase)

## Tutorials
- **Step-by-Step Diffusion: An Elementary Tutorial**, `arXiv, 2406.08929`, [arxiv](http://arxiv.org/abs/2406.08929v2), [pdf](http://arxiv.org/pdf/2406.08929v2.pdf), cication: [**-1**](None)

	 *Preetum Nakkiran, Arwen Bradley, Hattie Zhou, Madhu Advani*
- **Tutorial on Diffusion Models for Imaging and Vision**, `arXiv, 2403.18103`, [arxiv](http://arxiv.org/abs/2403.18103v1), [pdf](http://arxiv.org/pdf/2403.18103v1.pdf), cication: [**-1**](None)

	 *Stanley H. Chan*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-04-06-7))

## Autoregressive 
- **Open-MAGVIT2: An Open-Source Project Toward Democratizing
  Auto-regressive Visual Generation**, `arXiv, 2409.04410`, [arxiv](http://arxiv.org/abs/2409.04410v1), [pdf](http://arxiv.org/pdf/2409.04410v1.pdf), cication: [**-1**](None)

	 *Zhuoyan Luo, Fengyuan Shi, Yixiao Ge, Yujiu Yang, Limin Wang, Ying Shan* · ([Open-MAGVIT2](https://github.com/TencentARC/Open-MAGVIT2) - TencentARC) ![Star](https://img.shields.io/github/stars/TencentARC/Open-MAGVIT2.svg?style=social&label=Star)
- **Scalable Autoregressive Image Generation with Mamba**, `arXiv, 2408.12245`, [arxiv](http://arxiv.org/abs/2408.12245v1), [pdf](http://arxiv.org/pdf/2408.12245v1.pdf), cication: [**-1**](None)

	 *Haopeng Li, Jinyue Yang, Kexin Wang, Xuerui Qiu, Yuhong Chou, Xin Li, Guoqi Li* · ([AiM](https://github.com/hp-l33/AiM) - hp-l33) ![Star](https://img.shields.io/github/stars/hp-l33/AiM.svg?style=social&label=Star)
- **Show-o: One Single Transformer to Unify Multimodal Understanding and
  Generation**, `arXiv, 2408.12528`, [arxiv](http://arxiv.org/abs/2408.12528v2), [pdf](http://arxiv.org/pdf/2408.12528v2.pdf), cication: [**-1**](None)

	 *Jinheng Xie, Weijia Mao, Zechen Bai, David Junhao Zhang, Weihao Wang, Kevin Qinghong Lin, Yuchao Gu, Zhijie Chen, Zhenheng Yang, Mike Zheng Shou* · ([Show-o](https://github.com/showlab/Show-o) - showlab) ![Star](https://img.shields.io/github/stars/showlab/Show-o.svg?style=social&label=Star)
- **Transfusion: Predict the Next Token and Diffuse Images with One
  Multi-Modal Model**, `arXiv, 2408.11039`, [arxiv](http://arxiv.org/abs/2408.11039v1), [pdf](http://arxiv.org/pdf/2408.11039v1.pdf), cication: [**-1**](None)

	 *Chunting Zhou, Lili Yu, Arun Babu, Kushal Tirumala, Michihiro Yasunaga, Leonid Shamis, Jacob Kahn, Xuezhe Ma, Luke Zettlemoyer, Omer Levy*
- [**asymmetric_magvitv2**](https://github.com/bornfly-detachment/asymmetric_magvitv2) - bornfly-detachment ![Star](https://img.shields.io/github/stars/bornfly-detachment/asymmetric_magvitv2.svg?style=social&label=Star)

	 *In 2024, the strongest open-source implementation of asymmetric magvit\_v2 supports inference code but excludes VQVAE. It supports the joint encoding of images and videos, accommodating arbitrary video lengths and resolutions. It surpasses all open-source models in FID and FVD, with 4z and 16z models available on huggingface.*
- **Autoregressive Image Generation without Vector Quantization**, `arXiv, 2406.11838`, [arxiv](http://arxiv.org/abs/2406.11838v2), [pdf](http://arxiv.org/pdf/2406.11838v2.pdf), cication: [**-1**](None)

	 *Tianhong Li, Yonglong Tian, He Li, Mingyang Deng, Kaiming He* · ([mar](https://github.com/lth14/mar) - lth14) ![Star](https://img.shields.io/github/stars/lth14/mar.svg?style=social&label=Star)

## Detection
- **DeepSpeak Dataset v1.0**, `arXiv, 2408.05366`, [arxiv](http://arxiv.org/abs/2408.05366v2), [pdf](http://arxiv.org/pdf/2408.05366v2.pdf), cication: [**-1**](None)

	 *Sarah Barrington, Matyas Bohacek, Hany Farid*
- **DistilDIRE: A Small, Fast, Cheap and Lightweight Diffusion Synthesized
  Deepfake Detection**, `arXiv, 2406.00856`, [arxiv](http://arxiv.org/abs/2406.00856v1), [pdf](http://arxiv.org/pdf/2406.00856v1.pdf), cication: [**-1**](None)

	 *Yewon Lim, Changyeon Lee, Aerin Kim, Oren Etzioni* · ([DistilDIRE](https://github.com/miraflow/DistilDIRE) - miraflow) ![Star](https://img.shields.io/github/stars/miraflow/DistilDIRE.svg?style=social&label=Star)


## FLUX
- [**FLUX.1-dev**](https://huggingface.co/spaces/black-forest-labs/FLUX.1-dev) - black-forest-labs 🤗
- [Top 10 Prompts for Flux.1: Master the Art of AI - AI/ML Blog](https://aimlapi.com/blog/master-the-art-of-ai-top-10-prompts-for-flux-1-by-black-forests-labs)
- [Tips for Flux.1 Schnell: To avoid a "plasticky airbrushed face", do not use 4x-UltraSharp for upscaling realistic images, use 4xFaceUpDAT instead. : r/StableDiffusion](https://www.reddit.com/r/StableDiffusion/comments/1ev6ris/tips_for_flux1_schnell_to_avoid_a_plasticky/?utm_source=ainews&utm_medium=email&utm_campaign=ainews-the-dspy-roadmap)
- [**awesome-flux**](https://github.com/Eris2025/awesome-flux) - Eris2025 ![Star](https://img.shields.io/github/stars/Eris2025/awesome-flux.svg?style=social&label=Star)

	 *A curated list of awesome resources for FLUX, the state-of-the-art text-to-image model by Black Forest Labs.*
- [Announcing Black Forest Labs - Black Forest Labs](https://blackforestlabs.ai/announcing-black-forest-labs/)
- [**x-flux**](https://github.com/XLabs-AI/x-flux) - XLabs-AI ![Star](https://img.shields.io/github/stars/XLabs-AI/x-flux.svg?style=social&label=Star)

### Toolkits
- [**fluxgym**](https://github.com/cocktailpeanut/fluxgym) - cocktailpeanut ![Star](https://img.shields.io/github/stars/cocktailpeanut/fluxgym.svg?style=social&label=Star)

	 *Dead simple FLUX LoRA training UI with LOW VRAM support*

### Efficient 
- [**Realtime-FLUX**](https://huggingface.co/spaces/KingNish/Realtime-FLUX) - KingNish 🤗
- [Kijai/flux-fp8 at main](https://huggingface.co/Kijai/flux-fp8/tree/main)

### Loras
- [**FLUX.1-dev-LoRA-AntiBlur**](https://huggingface.co/Shakker-Labs/FLUX.1-dev-LoRA-AntiBlur) - Shakker-Labs 🤗
- [**AWPortrait-FL**](https://huggingface.co/Shakker-Labs/AWPortrait-FL) - Shakker-Labs 🤗
- [**FilmPortrait**](https://huggingface.co/Shakker-Labs/FilmPortrait) - Shakker-Labs 🤗
- [**flux-tarot-v1**](https://huggingface.co/multimodalart/flux-tarot-v1) - multimodalart 🤗
- [**flux-lora-collection**](https://huggingface.co/XLabs-AI/flux-lora-collection) - XLabs-AI 🤗
- [**Hyper-SD**](https://huggingface.co/ByteDance/Hyper-SD) - ByteDance 🤗
- [**Hyper-FLUX-8Steps-LoRA**](https://huggingface.co/spaces/ByteDance/Hyper-FLUX-8Steps-LoRA) - ByteDance 🤗
- [**FluxteusV1**](https://huggingface.co/dataautogpt3/FluxteusV1) - dataautogpt3 🤗
- [Flux_Realistic_v1](https://civitai.com/models/652009/fluxrealisticv1)
- [Realism Comparison v2 - Amateur Photography Lora [Flux Dev] : r/StableDiffusion](https://www.reddit.com/r/StableDiffusion/comments/1eywnv8/realism_comparison_v2_amateur_photography_lora)
- [Say goodbye to blurry backgrounds.. Anti-blur Flux Lora is here! : r/StableDiffusion](https://www.reddit.com/r/StableDiffusion/comments/1eyvzjv/say_goodbye_to_blurry_backgrounds_antiblur_flux)
- [running multiple Flux LoRAs at once. ](https://x.com/venturetwins/status/1825924552817520896)
- [**FLUX.1-schnell-training-adapter**](https://huggingface.co/ostris/FLUX.1-schnell-training-adapter) - ostris 🤗
- [Flux.1-Dev (v1+v2) Flux.1-Schnell BNB NF4](https://civitai.com/models/638187?modelVersionId=721627)
- [lllyasviel/flux1\_dev at main](https://huggingface.co/lllyasviel/flux1_dev/tree/main)
- [**flux_film_foto**](https://huggingface.co/alvdansen/flux_film_foto) - alvdansen 🤗
- [**flux-koda**](https://huggingface.co/alvdansen/flux-koda) - alvdansen 🤗
- [**frosting_lane_flux**](https://huggingface.co/alvdansen/frosting_lane_flux) - alvdansen 🤗
- [**FLUX.1-schnell-dev-merged**](https://huggingface.co/drbaph/FLUX.1-schnell-dev-merged) - drbaph 🤗
- [**OpenFLUX.1**](https://huggingface.co/ostris/OpenFLUX.1) - ostris 🤗
- [**FLUX.1-schnell-dev-merged-fp8-4step**](https://huggingface.co/drbaph/FLUX.1-schnell-dev-merged-fp8-4step) - drbaph 🤗

### Control Generation
- [**FLUX.1-dev-Controlnet-Inpainting-Alpha**](https://huggingface.co/alimama-creative/FLUX.1-dev-Controlnet-Inpainting-Alpha) - alimama-creative 🤗
- [**PuLID**](https://github.com/ToTheBeginning/PuLID) - ToTheBeginning ![Star](https://img.shields.io/github/stars/ToTheBeginning/PuLID.svg?style=social&label=Star)

	 *Official code for PuLID: Pure and Lightning ID Customization via Contrastive Alignment*
- [**SpeechCraft**](https://github.com/thuhcsi/SpeechCraft) - thuhcsi ![Star](https://img.shields.io/github/stars/thuhcsi/SpeechCraft.svg?style=social&label=Star)

	 *The official repository of SpeechCraft dataset, a large-scale expressive bilingual speech dataset with natural language descriptions.*
- [**flux-controlnet-canny-v3**](https://huggingface.co/XLabs-AI/flux-controlnet-canny-v3) - XLabs-AI 🤗

### Other
- [Flux Icon Maker! Ready to use Vector Outputs! : r/StableDiffusion](https://www.reddit.com/r/StableDiffusion/comments/1f9eyr7/flux_icon_maker_ready_to_use_vector_outputs)
- [Flux from @bfl_ml is now on RenderNet!](https://x.com/rendernet_ai/status/1833865069744083198)
- [FLUX is smarter than you! - and other surprising findings on making the model your own | Civitai](https://civitai.com/articles/6982)
- [AI in Filmmaking, X's txt2img (Flux.1 PRO), and FLUX Updates | This Week in AI Art 🎬](https://diffusiondigest.beehiiv.com/p/ai-filmmaking-xs-txt2img-flux1-pro-flux-updates-week-ai-art?_bhlid=1af336b16531cf042960800317583fa8ca7f70e3)
- [Stable Diffusion 3「精神续作」FLUX.1 源码深度前瞻解读](https://zhuanlan.zhihu.com/p/714150390)