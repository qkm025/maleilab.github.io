<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Insight Lab</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0 auto;
            padding: 20px;
            color: #333;
            max-width: 1300px;
        }

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
            font-size: 2.4em;
            font-weight: bold;
            color: #47975d;
            text-decoration: none;
            font-family: "HeadLineA", "SimHei", "Heiti TC", "Arial Black", sans-serif;
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
        .content-section {
            margin-bottom: 30px;
        }
        .float-container {
            overflow: hidden;
            margin: 10px 0;
        }
        .float-left {
            float: left;
            margin-right: 20px;
        }
        h1 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        h2 {
            color: #34495e;
        }
        h3 {
            color: #2c3e50;
            margin-top: 25px;
        }
        a {
            color: #2c3e50;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
            color: #3498db;
        }
        .publication-item {
            margin-bottom: 15px;
        }
        .float-container img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .profile-image {
            width: 240px;
        }
        
        .image-group {
            float: left;
            margin-right: 20px;
            display: flex;
            gap: 10px;
        }
        
        .image-group img {
            display: block;
            margin-bottom: 0;
            border-radius: 5px;
        }
        
        .image-large {
            width: 390px;
        }
        
        .image-small {
            width: 240px;
        }
        
        .image-cell-research {
            width: 640px;
            float: left;
            margin-right: 20px;
        }
        
        .xinhua-link {
            display: inline-block;
            padding: 10px 20px;
            background-color: #f8f9fa;
            border: 2px solid #47975d;
            border-radius: 8px;
            color: #47975d;
            font-weight: 500;
            transition: all 0.3s ease;
            margin: 5px;
            line-height: 30px;
        }
        .xinhua-link:hover {
            background-color: #47975d;
            color: white;
            text-decoration: none;
            transform: translateY(-2px);
        }
        
        .media-links {
            margin: 15px 0;
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        @media (max-width: 768px) {
            .navbar {
                flex-direction: column;
                gap: 15px;
            }
            .navbar .nav-links {
                flex-direction: column;
                gap: 5px;
                width: 100%;
            }
            .navbar .nav-links a {
                display: block;
                text-align: center;
                margin: 5px 0;
            }

            .float-left {
                float: none;
                margin-right: 0;
                margin-bottom: 15px;
            }
            .image-group {
                float: none;
                margin-right: 0;
                margin-bottom: 15px;
                flex-direction: column;
            }
            
            .image-group img {
                width: 100%;
                max-width: 100%;
            }
            
            .image-cell-research {
                width: 100%;
                float: none;
                margin-right: 0;
                margin-bottom: 15px;
            }
            
            .media-links {
                flex-direction: column;
            }
        }
    </style>
</head>

<body>
    <nav class="navbar">
        <a href="/" class="logo">Insight Lab</a>
        <ul class="nav-links">
            <li><a href="/">Home</a></li>
            <li><a href="members">Members</a></li>
            <li><a href="research">Research</a></li>
            <li><a href="fulllist">Publications</a></li>
        </ul>
    </nav>

    <div class="content-section">
        <div class="float-container">
            <img src="images/home/47915613.jpg" alt="马雷" class="float-left profile-image">
            <div>
                <h1>马雷</h1>
                <p><strong>北京大学国家生物医学成像科学中心 研究员（PI）、博士生导师</strong></p>
                <p><strong>北京市杰出青年</strong></p>
                <p><strong><a href="https://mp.weixin.qq.com/s/o9HHS7PkMGN8eQ6bg6KK4w?scene=2">2025-2026 博古睿学者</a></strong></p>
                <p><strong>北京智源人工智能研究院 智源学者</strong></p>
                <p><strong>国家重大科技基础设施- "多模态跨尺度生物医学成像设施" 装置四负责人</strong></p>
                <p>邮箱：<a href="mailto:lei.ma@pku.edu.cn">lei.ma@pku.edu.cn</a></p>
                <p>地址：北京市海淀区颐和园路5号北京大学王克桢楼209</p>
            </div>
        </div>
    </div>

    <div class="content-section">
        <h1>Short Bio</h1>
        <p>马雷博士的研究方向为人工智能与数字生命。共计发表学术论文近70篇。近三年以第一或通讯在Nature Computational Science(2024、封面文章)、Cell Research(2024、封面文章）、National Science Review（2025）、MIA（2024）、Nature Communications(2023)、ACM/IEEE汇刊等国际期刊及CVPR、NIPS、ECCV等人工智能会议发表32篇论文，代表工作包括数据驱动秀丽线虫"天宝"、精细神经元动力学快速求解算法、SCN神经元集群时间编码模型、神经形态相机等。承担"科技创新2030"重大项目课题（2022）、北京市科技计划（2023）、北京市杰出青年科学基金（2024）、北京市非共识项目（第一批、2025）等多个重要项目。</p>
        <p><strong>课题组尚有26年硕士起点博士名额，有意者联系<a href="mailto:lei.ma@pku.edu.cn">lei.ma@pku.edu.cn</a></strong></p>
    </div>

    <div class="content-section">
        <h1>Research</h1>
        
        <h3>1. Nature Computational Science 期刊封面 - 国际首个秀丽线虫闭环仿真模型</h3>
        <div class="float-container">
            <div class="image-group">
                <img src="images/home/57934934.jpg" alt="Nature Computational Science期刊封面" class="image-large">
                <img src="images/home/57934770.png" alt="Nature Computational Science期刊封面" class="image-small">
            </div>
            
            <div>
                <p>秀丽线虫是生命科学研究的重要模式动物之一，常被用于研究神经系统的工作机制。当前脑科学研究侧重解析神经系统的局部工作机制，如何整合大脑不同层级的细节，进而构建完整的生物体仿真一直是领域内的重大挑战。</p>
                <p>马雷团队首次实现了线虫神经网络模型与身体环境模型的闭环交互仿真，完整模拟了秀丽线虫的大脑、身体与环境的动态相互作用（Nature Computational Science 2024，12月封面文章，编辑推荐，期刊同期发表Research Briefing 报道）。</p>
            </div>
        </div>

        <h3>2. Cell Research 期刊封面 - 脑解码：SCN神经元集群时间编码模型</h3>
        <div class="float-container">
            <img src="images/home/57932339.png" alt="Cell Research期刊封面" class="image-cell-research">
            <div>
                <p>视交叉上核（Suprachiasmatic Nucleus, SCN）是哺乳动物昼夜节律的中枢，现有研究主要聚焦于个体神经元的分子节律机制，系统层面如何编码时间仍然未解。马雷与合作者结合新型高速双视角双光子显微镜成像技术和机器学习技术，提出了SCN群体决策与空间模块化特征表示的新概念，为生物钟的系统设计提供了全新视角（Cell Research (2024)）。</p>
            </div>
        </div>
    </div>

    <div class="content-section">
        <h1>Selected Publications <a href="fulllist">[Full List]</a></h1>
        <p>(# Equal Contribution, *Corresponding Author)</p>
        
        <div class="publication-item">
            <p><strong>1. An initiative on digital nephrology: the Kidney Imageomics Project.</strong></p>
            <p>Fangxu Zhou, Zehua Li, Haifeng Li, Yao Lu, Linjia Cheng, Ying Zhang, Zichen Wang, Jing Nie, Heping Cheng, Bin Dong*, Lei Ma*, Li Yang*</p>
            <p><em>National Science Review</em></p>
        </div>
        
        <div class="media-links">
            <a href="https://xhnewsapi.xinhuaxmt.com/share/news_pc?id=1059512391118848&showType=3001&utdId=null&version=4.0.7&twoShare=1&uuid=9530-453f-ec50-b6b7-d8d2" target="_blank" class="xinhua-link">Xinhua News - 2025年3月</a>
            <a href="https://h.xinhuaxmt.com/vh512/share/12443882?d=134fec8" target="_blank" class="xinhua-link">新华社 - 2025年3月</a>
        </div>
        
        <div class="publication-item">
            <p><strong>2. An integrative data-driven model simulating C. elegans brain, body and environment interactions.</strong></p>
            <p>Mengdi Zhao, Ning Wang, Xinrui Jiang, Xiaoyang Ma, Haixin Ma, Gan He, Kai Du, Lei Ma* & Tiejun Huang.</p>
            <p><em>Nature Computational Science</em></p>
        </div>
        
        <div class="media-links">
            <a href="https://h.xinhuaxmt.com/vh512/share/12341233?d=134db4c" target="_blank" class="xinhua-link">新华社 - 新华视点 - 2024年12月</a>
            <a href="https://tv.cctv.com/2023/01/21/VIDEEG17Lt1mLKlDsrkqbGWG230121.shtml?spm=C55924871139.PT8hUEEDkoTi.0.0" target="_blank" class="xinhua-link">CCTV 9</a>
            <a href="https://h.xinhuaxmt.com/vh512/share/10845612" target="_blank" class="xinhua-link">新华社</a>
            <a href="https://h.xinhuaxmt.com/vh512/share/10845254" target="_blank" class="xinhua-link">新华社</a>
        </div>
        
        <div class="media-links">
            <a href="https://tv.cctv.com/2025/03/01/VIDEBHUUetmfDfV1fG5N1ZXJ250301.shtml?spm=C53156045404.PKXC0xLPAnP9.0.0" target="_blank" class="xinhua-link">CCTV - 新闻直播间 - 2025年3月 - 大模型"智"在何方，数字线虫"天宝" 开启生物智能新范式</a>
        </div>
        
        <div class="publication-item">
            <p><strong>3. System-level time computation and representation in the suprachiasmatic nucleus revealed by large-scale calcium imaging and machine learning.</strong></p>
            <p>Zichen Wang, Jing Yu, Muyue Zhai, Zehua Wang, Kaiwen Sheng, Yu Zhu, Tianyu Wang, Mianzhi Liu, Lu Wang, Miao Yan, Jue Zhang, Ying Xu, Xianhua Wang, Lei Ma*, Wei Hu* & Heping Cheng*.</p>
            <p><em>Cell Research</em></p>
        </div>
        
        <div class="media-links">
            <a href="https://h.xinhuaxmt.com/vh512/share/10845254" target="_blank" class="xinhua-link">新华社</a>
            <a href="http://www.bj.xinhuanet.com/20240418/e84ab548d7dd4bacb928489e4c04d6a2/c.html" target="_blank" class="xinhua-link">新华社</a>
        </div>
        
        <div class="publication-item">
            <p><strong>4. A GPU-based computational framework that bridges Neuron simulation and Artificial Intelligence</strong></p>
            <p>Yichen Zhang#, Gan He#, Lei Ma#, Xiaofei Liu, JJ Johannes Hjorth, Alexander Kozlov, Yutao He, Shenjian Zhang, Jeanette Hellgren Kotaleski, Yonghong Tian, Sten Grillner, Kai Du, Tiejun Huang.</p>
            <p><em>Nature Communications</em></p>
        </div>
        
        <div class="publication-item">
            <p><strong>5. Embedded prompt tuning: Towards enhanced calibration of pretrained models for medical images</strong></p>
            <p>Wenqiang Zu#, Shenghao Xie#, Qing Zhao#, Guoqi Li, Lei Ma*</p>
            <p><em>Medical Image Analysis</em></p>
        </div>
    </div>

    <div class="content-section">
        <h1>Opportunities</h1>
        
        <h3>1. 研究生</h3>
        <p>我们正在积极寻找优秀的学生加入我们的课题组，研究领域包括但不限于：计算生物学、人工智能、计算机图形学、计算机视觉。</p>
        <p>课题组尚有26年硕士起点博士名额，有意者联系<a href="mailto:lei.ma@pku.edu.cn">lei.ma@pku.edu.cn</a></p>
        
        <h3>2. 博士后研究员</h3>
        <p>我们正在招聘 数字生命/生物医学大模型/软件开发 方向的博士后研究员，有意者可联系<a href="mailto:lei.ma@pku.edu.cn">lei.ma@pku.edu.cn</a>或者<a href="mailto:jie.sun@pku.edu.cn">jie.sun@pku.edu.cn</a></p>
        <p>具体招聘信息参考链接：<a href="#">北京大学未来技术学院马雷课题组招聘博士后</a></p>
    </div>

    <div class="content-section">
        <p><strong>联系方式：</strong></p>
        <p>邮箱：<a href="mailto:lei.ma@pku.edu.cn">lei.ma@pku.edu.cn</a></p>
        <p>地址：北京市海淀区颐和园路5号北京大学王克桢楼209</p>
    </div>
</body>
</html>
