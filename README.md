cat > README.md << 'EOF'
<!DOCTYPE html>
<html>
<head>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 40px 20px;
            line-height: 1.6;
        }
        .container { max-width: 1200px; margin: 0 auto; }
        .header { text-align: center; color: white; margin-bottom: 60px; }
        .avatar { width: 140px; height: 140px; border-radius: 50%; border: 4px solid rgba(255,255,255,0.3); margin: 0 auto 20px; display: block; }
        h1 { font-size: 3.5rem; font-weight: 700; margin-bottom: 8px; letter-spacing: -1px; }
        .subtitle { font-size: 1.4rem; font-weight: 400; opacity: 0.95; margin-bottom: 12px; }
        .tagline { font-size: 1.1rem; opacity: 0.85; max-width: 600px; margin: 0 auto; }
        
        .section { background: rgba(255,255,255,0.95); border-radius: 24px; padding: 40px; margin-bottom: 32px; box-shadow: 0 25px 50px -12px rgba(0,0,0,0.15); backdrop-filter: blur(10px); }
        .section h2 { font-size: 1.8rem; font-weight: 600; color: #2d3748; margin-bottom: 28px; display: flex; align-items: center; gap: 12px; }
        .section h2::before { content: ''; width: 4px; height: 24px; background: linear-gradient(135deg, #667eea, #764ba2); border-radius: 2px; }
        
        .tech-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 16px; margin-top: 24px; }
        .tech-badge { padding: 12px 20px; border-radius: 50px; text-align: center; font-weight: 500; font-size: 0.9rem; transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1); backdrop-filter: blur(10px); border: 1px solid rgba(255,255,255,0.2); }
        .tech-badge:hover { transform: translateY(-4px); box-shadow: 0 20px 40px -10px rgba(0,0,0,0.2); }
        
        .stats-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 24px; }
        .graph-container { background: rgba(255,255,255,0.1); border-radius: 20px; padding: 20px; backdrop-filter: blur(20px); border: 1px solid rgba(255,255,255,0.2); }
        
        .connect-grid { display: flex; justify-content: center; gap: 16px; flex-wrap: wrap; margin-top: 24px; }
        .connect-btn { padding: 14px 28px; border-radius: 50px; font-weight: 600; text-decoration: none; transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1); border: 2px solid rgba(255,255,255,0.3); backdrop-filter: blur(10px); }
        .connect-btn:hover { transform: translateY(-2px); box-shadow: 0 20px 40px -10px rgba(0,0,0,0.3); border-color: rgba(255,255,255,0.5); }
        
        .footer { text-align: center; color: rgba(255,255,255,0.9); font-size: 0.95rem; margin-top: 40px; }
        @keyframes fadeInUp { from { opacity: 0; transform: translateY(30px); } to { opacity: 1; transform: translateY(0); } }
        .section { animation: fadeInUp 0.8s cubic-bezier(0.4, 0, 0.2, 1) forwards; }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="https://avatars.githubusercontent.com/u/178491093?s=400&u=54809017fc5993a4448a1a1ecb1eb4dda2c315fa&v=4" class="avatar" alt="Altaf" />
            <h1>Altaf Hussain</h1>
            <div class="subtitle">Full-Stack Developer</div>
            <div class="tagline">Building scalable SaaS products with clean UI & high performance</div>
            <div style="margin-top: 24px; font-size: 1.1rem;">📍 Himachal Pradesh, India</div>
        </div>
        
        <div class="section">
            <h2>📊 Contribution Activity</h2>
            <div style="background: linear-gradient(90deg, #f0f9ff, #e0f2fe); border-radius: 16px; padding: 24px; text-align: center;">
                <div style="font-size: 1.4rem; font-weight: 600; color: #1e40af; margin-bottom: 16px;">75+ Commits in 2025</div>
                <img src="https://ghchart.rshah.org/4CAF50:FFEB3B:FF5722:9C27B0:2196F3/code-with-altaf" style="border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.1);" />
            </div>
        </div>
        
        <div class="section">
            <h2>🛠️ Tech Stack</h2>
            <div class="tech-grid">
                <div class="tech-badge" style="background: linear-gradient(135deg, #20232a, #282c34); color: #61DAFB;">React</div>
                <div class="tech-badge" style="background: linear-gradient(135deg, #000, #111); color: white;">Next.js</div>
                <div class="tech-badge" style="background: linear-gradient(135deg, #007acc, #005a9e); color: white;">TypeScript</div>
                <div class="tech-badge" style="background: linear-gradient(135deg, #43853d, #2f5a2b); color: white;">Node.js</div>
                <div class="tech-badge" style="background: linear-gradient(135deg, #4ea94b, #3a8c38); color: white;">MongoDB</div>
                <div class="tech-badge" style="background: linear-gradient(135deg, #316192, #244a74); color: white;">PostgreSQL</div>
                <div class="tech-badge" style="background: linear-gradient(135deg, #38b2ac, #2c8b88); color: white;">Tailwind</div>
                <div class="tech-badge" style="background: linear-gradient(135deg, #3987c5, #2b6a9e); color: white;">Prisma</div>
            </div>
        </div>
        
        <div class="section">
            <h2>📈 GitHub Stats</h2>
            <div class="stats-grid">
                <div class="graph-container">
                    <img src="https://github-readme-stats.vercel.app/api?username=code-with-altaf&show_icons=true&theme=transparent&hide_border=true&bg_color=ffffff00&title_color=2d3748&icon_color=667eea&text_color=4a5568" width="100%"/>
                </div>
                <div class="graph-container">
                    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=code-with-altaf&layout=compact&theme=transparent&hide_border=true&bg_color=ffffff00" width="100%"/>
                </div>
            </div>
            <div class="stats-grid" style="margin-top: 20px;">
                <div class="graph-container">
                    <img src="https://github-readme-streak-stats.herokuapp.com/?user=code-with-altaf&theme=transparent&hide_border=true&background=ffffff00" width="100%"/>
                </div>
                <div class="graph-container">
                    <img src="https://github-profile-trophy.vercel.app/?username=code-with-altaf&theme=dracula&no-frame=true&no-bg=true" width="100%"/>
                </div>
            </div>
        </div>
        
        <div class="section">
            <h2>🌐 Let's Connect</h2>
            <div class="connect-grid">
                <a href="https://adowise.in" class="connect-btn" style="background: linear-gradient(135deg, #1e90ff, #0066cc); color: white;">Portfolio</a>
                <a href="https://linkedin.com/in/reachmohdaltaf" class="connect-btn" style="background: linear-gradient(135deg, #0077b5, #005582); color: white;">LinkedIn</a>
                <a href="mailto:reachmohdaltaf@gmail.com" class="connect-btn" style="background: linear-gradient(135deg, #d14836, #a83226); color: white;">Email</a>
            </div>
            <div style="text-align: center; margin-top: 24px; color: #4a5568; font-weight: 500;">
                📫 reachmohdaltaf@gmail.com | 📱 +91 7876637551
            </div>
        </div>
    </div>
</body>
</html>
EOF
