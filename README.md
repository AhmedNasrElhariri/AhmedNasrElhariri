<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahmed - Full Stack Developer</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            margin: 0;
            padding: 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            min-height: 100vh;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        h1 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 10px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .subtitle {
            text-align: center;
            font-size: 1.2em;
            color: #666;
            margin-bottom: 30px;
            line-height: 1.6;
        }
        
        .experience-badge {
            display: inline-block;
            background: linear-gradient(45deg, #ff6b6b, #ee5a24);
            color: white;
            padding: 8px 16px;
            border-radius: 20px;
            font-weight: bold;
            font-size: 0.9em;
            margin: 5px;
            box-shadow: 0 4px 15px rgba(255,107,107,0.3);
        }
        
        .section {
            margin: 30px 0;
        }
        
        .section h3 {
            font-size: 1.5em;
            margin-bottom: 20px;
            color: #333;
            border-bottom: 3px solid #667eea;
            padding-bottom: 10px;
            display: inline-block;
        }
        
        .connect-links {
            display: flex;
            gap: 15px;
            align-items: center;
            flex-wrap: wrap;
        }
        
        .connect-links a {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 10px 15px;
            background: #f8f9fa;
            border-radius: 10px;
            text-decoration: none;
            color: #333;
            transition: all 0.3s ease;
            border: 2px solid transparent;
        }
        
        .connect-links a:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
            border-color: #667eea;
        }
        
        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .tech-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
            background: #f8f9fa;
            border-radius: 15px;
            transition: all 0.3s ease;
            border: 2px solid transparent;
        }
        
        .tech-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            border-color: #667eea;
        }
        
        .tech-item img {
            width: 50px;
            height: 50px;
            margin-bottom: 10px;
        }
        
        .tech-name {
            font-weight: 600;
            font-size: 0.9em;
            text-align: center;
        }
        
        .experience-years {
            font-size: 0.8em;
            color: #666;
            margin-top: 5px;
        }
        
        @media (max-width: 768px) {
            .container {
                margin: 10px;
                padding: 20px;
            }
            
            h1 {
                font-size: 2em;
            }
            
            .tech-grid {
                grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
                gap: 15px;
            }
            
            .connect-links {
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hi! I'm Ahmed 👋</h1>
        <p class="subtitle">
            A passionate full stack developer with <strong>5+ years of experience</strong><br>
            Specialized in building modern web applications and scalable solutions
        </p>
        
        <div class="section">
            <div style="text-align: center; margin: 20px 0;">
                <span class="experience-badge">5+ Years React & Next.js</span>
                <span class="experience-badge">5+ Years Node.js</span>
                <span class="experience-badge">5+ Years Laravel</span>
                <span class="experience-badge">5+ Years JavaScript</span>
            </div>
        </div>

        <div class="section">
            <h3>Connect with me:</h3>
            <div class="connect-links">
                <a href="https://www.linkedin.com/in/ahmed-nasr-elhariri-software-engineer-full-stack-developer/" target="_blank">
                    <img src="https://cdn-icons-png.flaticon.com/512/1384/1384014.png" width="25" height="25" alt="LinkedIn"/>
                    LinkedIn
                </a>
                <a href="mailto:ahmednasr.fci97@gmail.com" target="_blank">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Gmail_icon_%282020%29.svg/2560px-Gmail_icon_%282020%29.svg.png" height="25" alt="Gmail"/>
                    Email Me
                </a>
            </div>
        </div>

        <div class="section">
            <h3>Languages and Tools:</h3>
            <div class="tech-grid">
                <div class="tech-item">
                    <img src="https://camo.githubusercontent.com/27d0b117da00485c56d69aef0fa310a3f8a07abecc8aa15fa38c8b78526c60ac/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f72656163742f72656163742d6f726967696e616c2e737667" alt="React"/>
                    <div class="tech-name">React</div>
                    <div class="experience-years">5+ years</div>
                </div>
                
                <div class="tech-item">
                    <img src="https://camo.githubusercontent.com/92ec9eb7eeab7db4f5919e3205918918c42e6772562afb4112a2909c1aaaa875/68747470733a2f2f6173736574732e76657263656c2e636f6d2f696d6167652f75706c6f61642f76313630373535343338352f7265706f7369746f726965732f6e6578742d6a732f6e6578742d6c6f676f2e706e67" alt="Next.js"/>
                    <div class="tech-name">Next.js</div>
                    <div class="experience-years">5+ years</div>
                </div>
                
                <div class="tech-item">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/590px-Node.js_logo.svg.png" alt="Node.js"/>
                    <div class="tech-name">Node.js</div>
                    <div class="experience-years">5+ years</div>
                </div>
                
                <div class="tech-item">
                    <img src="https://camo.githubusercontent.com/442c452cb73752bb1914ce03fce2017056d651a2099696b8594ddf5ccc74825e/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6a6176617363726970742f6a6176617363726970742d6f726967696e616c2e737667" alt="JavaScript"/>
                    <div class="tech-name">JavaScript</div>
                    <div class="experience-years">5+ years</div>
                </div>
                
                <div class="tech-item">
                    <img src="https://laravel.com/img/logomark.min.svg" alt="Laravel"/>
                    <div class="tech-name">Laravel</div>
                    <div class="experience-years">5+ years</div>
                </div>
                
                <div class="tech-item">
                    <img src="https://cdn.shopify.com/s/files/1/0277/3329/5197/files/GraphQL-logo.png?height=628&pad_color=ffffff&v=1663253428&width=1200" alt="GraphQL"/>
                    <div class="tech-name">GraphQL</div>
                    <div class="experience-years">3+ years</div>
                </div>
                
                <div class="tech-item">
                    <img src="https://cdn.icon-icons.com/icons2/2415/PNG/512/postgresql_original_wordmark_logo_icon_146392.png" alt="PostgreSQL"/>
                    <div class="tech-name">PostgreSQL</div>
                    <div class="experience-years">4+ years</div>
                </div>
                
                <div class="tech-item">
                    <img src="https://angular.io/assets/images/logos/angularjs/AngularJS-Shield.svg" alt="Angular"/>
                    <div class="tech-name">Angular</div>
                    <div class="experience-years">3+ years</div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
