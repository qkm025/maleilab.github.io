<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Publications-Insight Lab</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0 auto;
            padding: 20px;
            color: #333;
            max-width: 1300px;
        }

        /* 导航栏样式 */
        .navbar {
            background-color: white;
            padding: 15px 20px;
            border-radius: 8px;
            margin-bottom: 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .navbar .logo {
            font-size: 3em;
            font-weight: 500;
            color: #47975d;
            text-decoration: none;
            font-family: "HeadLineA", "Arial Black", sans-serif;
            letter-spacing: 0.5px;
            text-shadow: 1px 1px 1px rgba(0,0,0,0.1);
        }
        .navbar .nav-links {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            gap: 10px;
        }
        .navbar .nav-links a {
            display: inline-block;
            padding: 10px 20px;
            background-color: white;
            border: 2px solid #47975d;
            border-radius: 8px;
            color: #47975d;
            font-size: 1.15em;
            font-weight: 500;
            text-decoration: none;
            transition: all 0.3s ease;
            margin: 5px;
            line-height: 30px;
        }
        .navbar .nav-links a:hover {
            background-color: #47975d;
            color: white;
            text-decoration: none;
            transform: translateY(-2px);
        }
        
        /* 当前页面指示器样式 */
        .current-page-indicator {
            background-color: #f8f9fa;
            padding: 12px 20px;
            margin-bottom: 30px;
            border-radius: 8px;
            border-left: 4px solid #47975d;
        }
        .current-page-indicator h2 {
            color: #2c3e50;
            margin: 0;
            font-size: 1.2em;
            font-weight: 500;
        }
        .current-page-indicator a {
            color: #47975d;
            text-decoration: none;
        }
        .current-page-indicator a:hover {
            text-decoration: underline;
        }
        
        /* 出版物列表样式 */
        .publications-container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .year-section {
            margin-bottom: 40px;
        }
        
        .year-title {
            color: #2c3e50;
            border-bottom: 2px solid #47975d;
            padding-bottom: 10px;
            margin-bottom: 20px;
            font-size: 1.8em;
        }
        
        .publication-item {
            margin-bottom: 20px;
            padding: 15px;
            background-color: #f8f9fa;
            border-radius: 5px;
            border-left: 3px solid #47975d;
            transition: all 0.3s ease;
        }
        
        .publication-item:hover {
            background-color: #e9f5ec;
            transform: translateX(5px);
        }
        
        .publication-title {
            font-weight: bold;
            color: #2c3e50;
            margin-bottom: 8px;
        }
        
        .publication-authors {
            margin-bottom: 5px;
            color: #555;
        }
        
        .publication-venue {
            font-style: italic;
            color: #47975d;
        }
        
        @media (max-width: 768px) {
            .navbar {
                flex-direction: column;
                align-items: flex-start;
            }
            
            .navbar .nav-links {
                margin-top: 15px;
                flex-wrap: wrap;
            }
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <a href="/" class="logo">Insight Lab</a>
        <ul class="nav-links">
            <li><a href="https://qkm025.github.io/maleilab.github.io/">Home</a></li>
            <li><a href="members">Members</a></li>
            <li><a href="research">Research</a></li>
            <li><a href="fulllist">Publications</a></li>
        </ul>
    </nav>
    
    <div class="current-page-indicator">
        <h2><a href="https://qkm025.github.io/maleilab.github.io/">Home</a> &raquo; Publications</h2>
    </div>
    
<div class="publications-container">
    <!-- 2025年出版物 -->
    <div class="year-section">
        <h2 class="year-title">2025</h2>
        
        <h3>会议论文</h3>
        <div class="publication-item">
            <div class="publication-title">Splats in Splats: Robust and Effective 3D Steganography towards Gaussian Splatting.</div>
            <div class="publication-authors">Yijia Guo, Wenkai Huang, Yang Li, Gaolei Li, Hang Zhang, Liwen Hu, jianhua Li, Tiejun Huang, Lei Ma*</div>
            <div class="publication-venue">AAAI 2026</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Can Protective Watermarking Safeguard the Copyright of 3D Gaussian Splatting？</div>
            <div class="publication-authors">Wenkai Huang, Yijia Guo, Gaolei Li, Lei Ma*, Hang Zhang, Liwen Hu, Jiazheng Wang, Tiejun Huang, Jianhua Li</div>
            <div class="publication-venue">AAAI 2026</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">A Boundary-aware Cold-Diffusion Model for Electron Microscopy Segmentation.</div>
            <div class="publication-authors">Muge Qi, Ruohua Shi, Yu Cai, Liuyuan He, Wenyao Wang, Lei Ma*</div>
            <div class="publication-venue">MICAAI 2025</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">SpikeGS: Reconstruct 3D Scene Captured by a Fast-Moving Bio-Inspired Camera.</div>
            <div class="publication-authors">Yijia Guo, Liwen Hu, Yuanxi Bai, Jiawei Yao, Lei Ma*, Tiejun Huang</div>
            <div class="publication-venue">AAAI 2025</div>
        </div>
        
        <h3>期刊论文</h3>
        <div class="publication-item">
            <div class="publication-title">HCUC: Combining Holistic Consistency and Uniqueness for PET/CT Multi-modal Segmentation.</div>
            <div class="publication-authors">Yu Cai, Zhuo Yang, Lei Ma*</div>
            <div class="publication-venue">Computers in Biology and Medicine</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Cost-effective Instruction Learning for Pathology Vision and Language Analysis.</div>
            <div class="publication-authors">Kaitao Chen, Mianxin Liu, Fang Yan, Lei Ma, Xiaoming Shi, Lilong Wang, Xiaosong Wang, Lifeng Zhu, Zhe Wang, Mu Zhou & Shaoting Zhang*</div>
            <div class="publication-venue">Nature Computational Science</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Unifying the Electron Microscopy Multiverse through a Large-scale Foundation Model.</div>
            <div class="publication-authors">Liuyuan He, Ruohua Shi, Wenyao Wang, Yu Cai, Lei Ma*</div>
            <div class="publication-venue">bioRxiv 2025.04.13.648639</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Robust Indoor Person Re-Identification With Multimodal Training.</div>
            <div class="publication-authors">Can Su, Xinlei Xue, Lei Ma, Xiaolong Zhang, Wei Yan, Kaigui Bian*</div>
            <div class="publication-venue">IEEE Internet of Things Journal</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">From Slices to Volumes: A Scalable Pipeline for Developing General-Purpose Brain MRl Foundation Models.</div>
            <div class="publication-authors">Feng Su, Xiaoping Yi, Ye Cheng, Yongjie Ma, Wenqiang Zu, Qing Zhao, Gengdi Huang, Lei Ma*</div>
            <div class="publication-venue">medRxiv 2025.04.12.25325728</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Pre-trained Models Succeed in Medical Imaging with Representation Similarity Degradation.</div>
            <div class="publication-authors">Wenqiang Zu, Shenghao Xie, Hao Chen, Lei Ma*</div>
            <div class="publication-venue">arXiv preprint arXiv:2503.07958</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Keeping Representation Similarity in Finetuning for Medical Image Analysis.</div>
            <div class="publication-authors">Wenqiang Zu, Shenghao Xie, Hao Chen, Yiming Liang, Lei Ma*</div>
            <div class="publication-venue">arXiv preprint arXiv:2503.07399</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Aligning Instruction Tuning with Pre-training.</div>
            <div class="publication-authors">Yiming Liang, Tianyu Zheng, Xinrun Du, Ge Zhang, Jiaheng Liu, Xingwei Qu, Wenqiang Zu, Xingrun Xing, Chujie Zheng, Lei Ma, Wenhu Chen, Guoyin Wang, Zhaoxiang Zhang, Wenhao Huang, Xiang Yue, Jiajun Zhang</div>
            <div class="publication-venue">arXiv preprint arXiv:2501.09368</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">An initiative on digital nephrology: the Kidney Imageomics Project.</div>
            <div class="publication-authors">Fangxu Zhou, Zehua Li, Haifeng Li, Yao Lu, Linjia Cheng, Ying Zhang, Zichen Wang, Jing Nie, Heping Cheng, Bin Dong*, Lei Ma*, Li Yang*</div>
            <div class="publication-venue">National Science Review</div>
        </div>
    </div>
    
    <!-- 2024年出版物 -->
    <div class="year-section">
        <h2 class="year-title">2024</h2>
        
        <h3>会议论文</h3>
        <div class="publication-item">
            <div class="publication-title">PRTGS: Precomputed Radiance Transfer of Gaussian Splats for Real-Time High-Quality Relighting.</div>
            <div class="publication-authors">Yijia Guo, Yuanxi Bai, Liwen Hu, Guo Ziyi, Mianzhi Liu, Yu Cai, Tiejun Huang, Lei Ma*</div>
            <div class="publication-venue">ACM Int Conf Multimedia.(MM) 2024</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Learning to Robustly Reconstruct Dynamic Scenes from Low-light Spike Streams.</div>
            <div class="publication-authors">Liwen Hu, Ziluo Ding, Mianzhi Liu, Lei Ma*, Tiejun Huang</div>
            <div class="publication-venue">ECCV2024</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Correspondence-Free Non-Rigid Point Set Registration Using Unsupervised Clustering Analysis.</div>
            <div class="publication-authors">Mingyang Zhao, Jingen Jiang, Lei Ma*, Shiqing Xin, Gaofeng Meng, Dong-Ming Yan</div>
            <div class="publication-venue">CVPR 2024 Highlight</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">SCSim: A Realistic Spike Cameras Simulator.</div>
            <div class="publication-authors">Liwen Hu, Lei Ma*, Yijia Guo, Tiejun Huang</div>
            <div class="publication-venue">ICME 2024 (Oral)</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Spike-NeRF: Neural Radiance Field Based On Spike Camera.</div>
            <div class="publication-authors">Yijia Guo, Yuanxi Bai, Liwen Hu, Mianzhi Liu, Ziyi Guo, Lei Ma*</div>
            <div class="publication-venue">ICME 2024 (Oral)</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">ShapeMamba-EM: Fine-Tuning Foundation Model with Local Shape Descriptors and Mamba Blocks for 3D EM Image Segmentation.</div>
            <div class="publication-authors">Ruohua Shi, Qiufan Pang, Lei Ma, Lingyu Duan, Tiejun Huang & Tingting Jiang</div>
            <div class="publication-venue">MICCAI 2024</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Unsupervised Optical Flow Estimation with Dynamic Timing Representation for Spike Camera.</div>
            <div class="publication-authors">Lujie Xia, Ziluo Ding, Rui Zhao, Jiyuan Zhang, Lei Ma, Zhaofei Yu, Tiejun Huang, Ruiqin Xiong</div>
            <div class="publication-venue">NIPS 2024</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Med-UniC: Unifying Cross-Lingual Medical Vision-Language Pre-Training by Diminishing Bias.</div>
            <div class="publication-authors">Zhongwei Wan, Che Liu, Mi Zhang, Jie Fu, Benyou Wang, Sibo Cheng, Lei Ma, César Quilodrán-Casas, Rossella Arcucci</div>
            <div class="publication-venue">NIPS 2024</div>
        </div>
        
        <h3>期刊论文</h3>
        <div class="publication-item">
            <div class="publication-title">An integrative data-driven model simulating C. elegans brain, body and environment interactions.</div>
            <div class="publication-authors">Mengdi Zhao, Ning Wang, Xinrui Jiang, Xiaoyang Ma, Haixin Ma, Gan He, Kai Du, Lei Ma* & Tiejun Huang</div>
            <div class="publication-venue">Nature Computational Science</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">System-level time computation and representation in the suprachiasmatic nucleus revealed by large-scale calcium imaging and machine learning.</div>
            <div class="publication-authors">Zichen Wang, Jing Yu, Muyue Zhai, Zehua Wang, Kaiwen Sheng, Yu Zhu, Tianyu Wang, Mianzhi Liu, Lu Wang, Miao Yan, Jue Zhang, Ying Xu, Xianhua Wang, Lei Ma*, Wei Hu* & Heping Cheng*</div>
            <div class="publication-venue">Cell Research</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Embedded prompt tuning: Towards enhanced calibration of pretrained models for medical images.</div>
            <div class="publication-authors">Wenqiang Zu#, Shenghao Xie#, Qing Zhao#, Guoqi Li, Lei Ma*</div>
            <div class="publication-venue">Medical Image Analysis</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">A Bayesian Approach Toward Robust Multidimensional Ellipsoid-Specific Fitting.</div>
            <div class="publication-authors">Mingyang Zhao, Xiaohong Jia*, Lei Ma, Yuke Shi, Jingen Jiang, Qizhai Li, Dong-Ming Yan, and Tiejun Huang</div>
            <div class="publication-venue">IEEE Transactions on Pattern Analysis and Machine Intelligence</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Optimization-Based Pairwise Interaction Point Process (O-PIPP): A Precise and Universal Retinal Mosaic Modeling Approach.</div>
            <div class="publication-authors">Liuyuan He, Wenyao Wang, Lei Ma*, Tiejun Huang</div>
            <div class="publication-venue">Investigative Ophthalmology & Visual Science</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Coherent chord computation and cross ratio for accurate ellipse detection.</div>
            <div class="publication-authors">Mingyang Zhao, Xiaohong Jia∗, Lei Ma∗, Li-Ming Hu, Dong-Ming Yan</div>
            <div class="publication-venue">Pattern Recognition</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Light Flickering Guided Reflection Removal.</div>
            <div class="publication-authors">Yuchen Hong, Yakun Chang, Jinxiu Liang, Lei Ma*, Tiejun Huang & Boxin Shi</div>
            <div class="publication-venue">Int J Comput Vis.(IJCV) 2024</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Towards Unifying Understanding and Generation in the Era of Vision Foundation Models: A Survey from the Autoregression Perspective.</div>
            <div class="publication-authors">Shenghao Xie, Wenqiang Zu, Mingyang Zhao, Duo Su, Shilong Liu, Ruohua Shi, Guoqi Li, Shanghang Zhang, Lei Ma</div>
            <div class="publication-venue">arXiv preprint arXiv:2410.22217</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">PathoDuet: Foundation models for pathological slide analysis of H&E and IHC stains</div>
            <div class="publication-authors">Shengyi Hua, Fang Yan, Tianle Shen, Lei Ma, Xiaofan Zhang</div>
            <div class="publication-venue">Medical Image Analysis</div>
        </div>
    </div>
    
    <!-- 2023年出版物 -->
    <div class="year-section">
        <h2 class="year-title">2023</h2>
        
        <h3>会议论文</h3>
        <div class="publication-item">
            <div class="publication-title">Med-UniC: Unifying Cross-Lingual Medical Vision-Language Pre-Training by Diminishing Bias.</div>
            <div class="publication-authors">Zhongwei Wan, Che Liu, Mi Zhang, Jie Fu, Benyou Wang, Sibo Cheng, Lei Ma, César Quilodrán-Casas, Rossella Arcucci</div>
            <div class="publication-venue">NeurIPS 2023</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Unsupervised Optical Flow Estimation with Dynamic Timing Representation for Spike Camera.</div>
            <div class="publication-authors">Lujie Xia, Ziluo Ding, Rui Zhao, Jiyuan Zhang, Lei Ma, Zhaofei Yu, Tiejun Huang, Ruiqin Xiong</div>
            <div class="publication-venue">NeurIPS 2023</div>
        </div>
        
        <h3>期刊论文</h3>
        <div class="publication-item">
            <div class="publication-title">A GPU-based computational framework that bridges Neuron simulation and Artificial Intelligence.</div>
            <div class="publication-authors">Yichen Zhang#, Gan He#, Lei Ma#, Xiaofei Liu, JJ Johannes Hjorth, Alexander Kozlov, Yutao He, Shenjian Zhang, Jeanette Hellgren Kotaleski, Yonghong Tian, Sten Grillner, Kai Du, Tiejun Huang</div>
            <div class="publication-venue">Nature Communications</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Coherent chord computation and cross ratio for accurate ellipse detection.</div>
            <div class="publication-authors">Mingyang Zhao, Xiaohong Jia*, Lei Ma*, Li-Ming Hu, Dong-Ming Yan</div>
            <div class="publication-venue">Pattern Recognition</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Advanced prompting as a catalyst: Empowering large language models in the management of gastrointestinal cancers.</div>
            <div class="publication-authors">Jiajia Yuan, Peng Bao, Zifan Chen, etc., Lei Ma, Bin Dong</div>
            <div class="publication-venue">The Innovation Medicine</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Efficient Video Transformers via Spatial-Temporal Token Merging for Action Recognition.</div>
            <div class="publication-authors">Zhanzhou Feng, Jiamin Xu, Lei Ma, Shiliang Zhang</div>
            <div class="publication-venue">ACM Transactions on Multimedia Computing, Communications and Applications</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Accurate Registration of Cross-Modality Geometry via Consistent Clustering.</div>
            <div class="publication-authors">MingyangZhao, Xiaoshui Huang, Jingen Jiang, Luntian Mou, Dong-Ming Yan, Lei Ma*</div>
            <div class="publication-venue">IEEE Transactions on Visualization and Computer Graphics</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Algorithms for single machine scheduling problem with release dates and submodular penalties.</div>
            <div class="publication-authors">Xiaofei Liu, Man Xiao, Weidong Li, Yaoyu Zhu, Lei Ma*</div>
            <div class="publication-venue">Journal of Combinatorial Optimization</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">PS-Net: human perception-guided segmentation network for EM cell membrane.</div>
            <div class="publication-authors">Ruohua Shi, Keyan Bi, Kai Du, Lei Ma, Fang Fang, Lingyu Duan, Tingting Jiang*, Tiejun Huang</div>
            <div class="publication-venue">Bioinformatics</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Spike Camera Image Reconstruction Using Deep Spiking Neural Networks.</div>
            <div class="publication-authors">Rui Zhao, Ruiqin Xiong*, Jian Zhang, Zhaofei Yu, Shuyu Zhu, Lei Ma, Tiejun Huang</div>
            <div class="publication-venue">IEEE Transactions on Circuits and Systems for Video Technology</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Driver Emotion Recognition with a Hybrid Attentional Multimodal Fusion Framework.</div>
            <div class="publication-authors">Luntian Mou, Yiyuan Zhao, Chao Zhou, Bahareh Nakisa, Mohammad Naim Rastgoo, Lei Ma, Tiejun Huang, Baocai Yin, Ramesh Jain, Wen Gao</div>
            <div class="publication-venue">IEEE Transactions on Affective Computing</div>
        </div>
    </div>
    
    <!-- 2022年出版物 -->
    <div class="year-section">
        <h2 class="year-title">2022</h2>
        
        <h3>会议论文</h3>
        <div class="publication-item">
            <div class="publication-title">On-line Single Machine Scheduling with Release Dates and Submodular Rejection Penalties.</div>
            <div class="publication-authors">Xiaofei Liu, Yaoyu Zhu, Weidong Li, Lei Ma*</div>
            <div class="publication-venue">AAIM 2022</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Optical flow estimation for spiking camera.</div>
            <div class="publication-authors">Liwen Hu#, Rui Zhao#, Ziluo Ding, Lei Ma*, Boxin Shi, Ruiqin Xiong, and Tiejun Huang</div>
            <div class="publication-venue">CVPR 2022</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Modeling the Detection Capability of High-Speed Spiking Cameras.</div>
            <div class="publication-authors">Junwei Zhao; Zhaofei Yu*; Lei Ma*; Ziluo Ding; Shiliang Zhang; Yonghong Tian; Tiejun Huang</div>
            <div class="publication-venue">ICASSP 2022</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">SpikingSIM: a Bio-Inspired Spiking Simulator.</div>
            <div class="publication-authors">Junwei Zhao; Shiliang Zhang*; Lei Ma*; Zhaofei Yu; Tiejun Huang</div>
            <div class="publication-venue">ISCAS 2022</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Effect of arsenic trioxide on human ventricular myocytes: a model study.</div>
            <div class="publication-authors">Yacong Li, Jun Liu*, Runlan Wan, Lei Ma, Henggui Zhang*</div>
            <div class="publication-venue">BIBM 2022</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Effect of cell coupling between pacemaker cells on the biological pacemaker in cardiac tissue model.</div>
            <div class="publication-authors">Yacong Li, Qince Li, Kuanquan Wang, Lei Ma, Henggui Zhang*</div>
            <div class="publication-venue">BIBM 2022</div>
        </div>
        
        <h3>期刊论文</h3>
        <div class="publication-item">
            <div class="publication-title">GraphReg: Dynamical Point Cloud Registration with Geometry-aware Graph Signal Processing.</div>
            <div class="publication-authors">Mingyang Zhao, Lei Ma*, Xiaohong Jia, Dong-Ming Yan*, and Tiejun Huang</div>
            <div class="publication-venue">IEEE Transactions on Image Processing</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">A Theoretical Model Reveals Specialized Synaptic Depressions and Temporal Frequency Tuning in Retinal Parallel Channels.</div>
            <div class="publication-authors">Liuyuan He, Yutao He, Lei Ma*, Tiejun Huang</div>
            <div class="publication-venue">Front. Comput. Neurosci.</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Hybrid High Dynamic Range Imaging fusing Neuromorphic and Conventional Images.</div>
            <div class="publication-authors">Jin Han, Yixin Yang, Chu Zhou, Peiqi Duan, Lei Ma, Chao Xu, Tiejun Huang, Imari Sato, and Boxin Shi*</div>
            <div class="publication-venue">IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Quantization Framework for Fast Spiking Neural Networks.</div>
            <div class="publication-authors">Chen Li; Lei Ma; Steve Furber</div>
            <div class="publication-venue">Front. Neurosci.</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">In Silico Mechanisms of Arsenic Trioxide-Induced Cardiotoxicity.</div>
            <div class="publication-authors">Yacong Li, Runlan Wan, Jun Liu*, Weichao Liu*, Lei Ma, and Henggui Zhang*</div>
            <div class="publication-venue">Frontiers in Physiology</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">1000x Faster Camera and Machine Vision with Ordinary Devices.</div>
            <div class="publication-authors">Tiejun Huang; Yajing Zheng; Zhaofei Yu; Rui Chen; Yuan Li; Ruiqin Xiong; Lei Ma; Junwei Zhao; Siwei Dong; Lin Zhu; Jianing Li; Shanshan Jia; Yihua Fu; Boxin Shi; Si Wu; Yonghong Tian</div>
            <div class="publication-venue">Engineering</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">AMSA: Adaptive Multimodal Learning for Sentiment Analysis.</div>
            <div class="publication-authors">Jingyao Wang, Luntian Mou, Lei Ma, Tiejun Huang, Wen Gao</div>
            <div class="publication-venue">ACM Transactions on Multimedia Computing, Communications, and Applications</div>
        </div>
        
        <div class="publication-item">
            <div class="publication-title">Advances in spike vision.</div>
            <div class="publication-authors">Tiejun Huang, Zhaofei Yu, Yuan Li, Boxin Shi, Ruiqin Xiong, Lei Ma, Wei Wang</div>
            <div class="publication-venue">Journal of Image and Graphics</div>
        </div>
    </div>
</div>
</body>
</html>
