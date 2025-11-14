<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Research-Insight Lab</title>
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
            font-size: 2.5em;
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
            font-size: 18px;
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
            font-size: 1.4em;
            font-weight: 600;
        }
        .current-page-indicator a {
            color: #47975d;
            text-decoration: none;
        }
        .current-page-indicator a:hover {
            text-decoration: underline;
        }
        
        .container {
            max-width: 1280px;
            margin: 0 auto;
        }
        
        .research-section {
            margin-bottom: 50px;
        }
        
        .research-item {
            display: flex;
            margin-bottom: 40px;
            align-items: flex-start;
        }
        
        .research-image {
            flex: 0 0 50%;
            margin-right: 30px;
        }
        
        .research-image img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        
        .research-content {
            flex: 1;
        }
        
        .research-content h2 {
            margin-top: 0;
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        
        .introduction {
            background-color: #f8f9fa;
            padding: 20px;
            border-radius: 5px;
            margin-bottom: 40px;
            border-left: 4px solid #3498db;
        }
        
        @media (max-width: 768px) {
            .research-item {
                flex-direction: column;
            }
            
            .research-image {
                margin-right: 0;
                margin-bottom: 20px;
                flex: 0 0 auto;
            }
            
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
        <h2><a href="https://qkm025.github.io/maleilab.github.io/">Home</a> &raquo; Research</h2>
    </div>
    
    <div class="container">
        <div class="introduction">
            <p>The Computational Odyssey in Biological Exploration: Computational methods play a pivotal role in life science research. With advancing technology, we have amassed a wealth of biological data containing intricate information. However, traditional experiments struggle to unveil this complexity. Fortunately, computational methods introduce new possibilities. The application of intelligent algorithms enables the processing and analysis of high-throughput data, helping us uncover patterns and correlations within the data. Additionally, the use of visualization techniques makes life processes more intuitive, providing valuable insights for scientific research. Moreover, modeling and simulation can simulate biological systems at different scales, aiding in disease prediction, drug discovery, and mechanistic understanding. In summary, computation will deepen our comprehension of life and propel the advancement of life science research.</p>
        </div>
        
        <div class="research-section">
            <div class="research-item">
                <div class="research-image">
                    <img src="images/research/47919104.png" alt="Biomedical data realistic rendering" class="image-large">
                </div>
                <div class="research-content">
                    <h1>Biomedical data realistic rendering</h1>
                    <p>High-quality visualization can assist researchers in gaining deeper intuition and insights. We are dedicated to developing and offering world-leading cinematic computer graphics techniques to our collaborators for their research endeavors.</p>
                </div>
            </div>
            
            <div class="research-item">
                <div class="research-image">
                    <img src="images/research/47919102.png" alt="Biomedical image foundation model" class="image-large">
                </div>
                <div class="research-content">
                    <h1>Biomedical image foundation model</h1>
                    <p>In recent years, foundation models have revolutionized numerous research fields. This cutting-edge technology offers a promising approach to process, integrate, and comprehend vast amounts of biomedical images, thereby fostering the advancement of biomedical research.</p>
                </div>
            </div>
            
            <div class="research-item">
                <div class="research-image">
                    <img src="images/research/47919100.jpg" alt="Multimodal trans-scale biomedical image integration" class="image-large">
                </div>
                <div class="research-content">
                    <h1>Multimodal trans-scale biomedical image integration</h1>
                    <p>Accurately describing the temporal and spatial dynamics of life activities is crucial in biomedical research. This necessitates the integration of multimodal information and overcoming multi-scale barriers.</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
