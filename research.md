<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Research-Insight Lab</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            color: #333;
        }
        
        .container {
            max-width: 1280px;
            margin: 0 auto;
        }
        
        .breadcrumb {
            margin-bottom: 20px;
            color: #666;
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
            flex: 0 0 54%;
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
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="breadcrumb">
            Home &raquo; Research
        </div>
        
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
