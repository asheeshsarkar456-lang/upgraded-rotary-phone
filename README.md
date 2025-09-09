<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: linear-gradient(135deg, #6e8efb, #a777e3);
            color: white;
            padding: 20px 0;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 24px;
            font-weight: bold;
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin-left: 25px;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
        }
        
        .nav-links a:hover {
            color: #ffdd59;
        }
        
        .hero {
            text-align: center;
            padding: 80px 0;
            background: white;
            margin: 30px 0;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        
        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
            color: #333;
        }
        
        .hero p {
            font-size: 20px;
            color: #666;
            max-width: 700px;
            margin: 0 auto;
        }
        
        .btn {
            display: inline-block;
            background: #6e8efb;
            color: white;
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            margin-top: 30px;
            transition: all 0.3s ease;
        }
        
        .btn:hover {
            background: #5a7dfa;
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(106, 142, 251, 0.3);
        }
        
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin: 60px 0;
        }
        
        .feature {
            flex: 0 0 calc(33.333% - 20px);
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            margin-bottom: 30px;
            text-align: center;
        }
        
        .feature h3 {
            font-size: 22px;
            margin: 20px 0;
            color: #333;
        }
        
        .feature-icon {
            font-size: 40px;
            color: #6e8efb;
        }
        
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 30px 0;
            margin-top: 60px;
        }
        
        @media (max-width: 768px) {
            .feature {
                flex: 0 0 100%;
            }
            
            .nav-links {
                display: none;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo">MyWebsite</div>
                <ul class="nav-links">
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Portfolio</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <div class="container">
        <section class="hero">
            <h1>Welcome to My Website</h1>
            <p>This is a simple example of how to create a website using HTML and CSS. You can modify this code to create your own website.</p>
            <a href="#" class="btn">Get Started</a>
        </section>
        
        <section class="features">
            <div class="feature">
                <div class="feature-icon">💻</div>
                <h3>Responsive Design</h3>
                <p>This website looks great on all devices, from desktops to mobile phones.</p>
            </div>
            <div class="feature">
                <div class="feature-icon">🎨</div>
                <h3>Modern UI</h3>
                <p>Clean and modern user interface with beautiful colors and typography.</p>
            </div>
            <div class="feature">
                <div class="feature-icon">⚡</div>
                <h3>Fast Loading</h3>
                <p>Optimized for performance and fast loading times.</p>
            </div>
        </section>
    </div>
    
    <footer>
        <div class="container">
            <p>&copy; 2023 My Website. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
