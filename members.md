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
    </style>
</head>

<body>
    <nav class="navbar">
        <a href="/" class="logo">Insight Lab</a>
        <ul class="nav-links">
            <li><a href="#">Home</a></li>
            <li><a href="members">Members</a></li>
            <li><a href="research">Research</a></li>
            <li><a href="fulllist">Publications</a></li>
        </ul>
    </nav>
    
    <div class="current-page-indicator">
        <h2><a href="#">Home</a> &raquo; Research</h2>
    </div>
</body>
