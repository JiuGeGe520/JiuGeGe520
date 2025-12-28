<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>九戈戈的 GitHub 主页</title>
    <style>
        /* 基础样式重置 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background-color: #0D1117;
            color: #E5E7EB;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            padding: 20px;
        }
        /* 容器样式 */
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        /* 标题样式 */
        .header {
            text-align: center;
            margin: 40px 0 60px;
        }
        .title {
            font-size: 2.5rem;
            font-weight: 700;
            color: #FFFFFF;
            margin-bottom: 12px;
            letter-spacing: -0.5px;
        }
        .subtitle {
            font-size: 1.1rem;
            color: #9CA3AF;
            font-weight: 400;
        }
        /* 徽章容器 */
        .badges {
            display: flex;
            justify-content: center;
            gap: 12px;
            flex-wrap: wrap;
            margin: 0 0 50px;
        }
        /* 卡片样式 */
        .card {
            background-color: #161B22;
            border-radius: 16px;
            padding: 28px;
            margin-bottom: 30px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
        }
        .card-title {
            font-size: 1.4rem;
            color: #818CF8;
            margin-bottom: 20px;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        /* 关于我样式 */
        .about-content {
            line-height: 2.2;
            font-size: 1rem;
            color: #E5E7EB;
        }
        .about-quote {
            margin-top: 20px;
            color: #9CA3AF;
            font-style: italic;
            padding-left: 8px;
            border-left: 2px solid #4F46E5;
        }
        /* 技术栈样式 */
        .tech-stack {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 24px;
        }
        .tech-group {
            text-align: center;
        }
        .tech-group-title {
            color: #60A5FA;
            font-weight: 600;
            margin-bottom: 12px;
            font-size: 1rem;
        }
        .tech-badges {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            justify-content: center;
        }
        /* 社交链接样式 */
        .social-links {
            display: flex;
            justify-content: center;
            gap: 16px;
            flex-wrap: wrap;
        }
        /* 底部样式 */
        .footer {
            text-align: center;
            margin: 60px 0 40px;
            color: #9CA3AF;
            font-size: 0.9rem;
        }
        .footer-hr {
            width: 80%;
            margin: 0 auto 20px;
            border: none;
            border-top: 1px solid #30363D;
        }
        /* 响应式调整 */
        @media (max-width: 600px) {
            .title {
                font-size: 2rem;
            }
            .card {
                padding: 20px;
            }
            .tech-stack {
                grid-template-columns: 1fr;
            }
            .social-links {
                gap: 12px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- 头部信息 -->
        <div class="header">
            <h1 class="title">嘿，你好！👋 我是 JiuGeGe520 | 九戈戈</h1>
            <p class="subtitle">天汪科技总负责人 · 技术领袖 · 持续学习的开发者</p>
        </div>

        <!-- 数据徽章 -->
        <div class="badges">
            <a href="https://github.com/JiuGeGe520" style="text-decoration: none;">
                <img src="https://img.shields.io/badge/Profile%20Views-∞-4F46E5?style=flat-square" alt="个人资料浏览">
            </a>
            <a href="https://github.com/JiuGeGe520?tab=followers" style="text-decoration: none;">
                <img src="https://img.shields.io/github/followers/JiuGeGe520?label=Followers&color=10B981&style=flat-square" alt="追随者">
            </a>
            <a href="https://github.com/JiuGeGe520" style="text-decoration: none;">
                <img src="https://img.shields.io/badge/Contributions-22-3B82F6?style=flat-square" alt="贡献">
            </a>
        </div>

        <!-- 关于我卡片 -->
        <div class="card">
            <h2 class="card-title">✨ 关于我</h2>
            <div class="about-content">
                🎓 大学生 / 开发者<br>
                🏢 创建并运营 天汪科技<br>
                🌐 专注于 高质量网站 / 软件系统 / 私有化部署<br>
                ⚙️ 熟悉服务器运维（Nginx / 宝塔 / Docker）<br>
                🎨 追求 极致 UI / UX 与细节体验
                <div class="about-quote">代码不仅是工具，更是艺术。</div>
            </div>
        </div>

        <!-- 技术栈卡片 -->
        <div class="card">
            <h2 class="card-title">🚀 技术栈</h2>
            <div class="tech-stack">
                <!-- 前端 -->
                <div class="tech-group">
                    <p class="tech-group-title">🌐 前端</p>
                    <div class="tech-badges">
                        <img src="https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JS">
                        <img src="https://img.shields.io/badge/TS-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TS">
                        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
                        <img src="https://img.shields.io/badge/HTML/CSS-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML/CSS">
                    </div>
                </div>
                <!-- 后端 -->
                <div class="tech-group">
                    <p class="tech-group-title">🧠 后端</p>
                    <div class="tech-badges">
                        <img src="https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white" alt="Node.js">
                        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
                    </div>
                </div>
                <!-- 运维&工具 -->
                <div class="tech-group">
                    <p class="tech-group-title">🛠 运维&工具</p>
                    <div class="tech-badges">
                        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
                        <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx">
                        <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
                    </div>
                </div>
            </div>
        </div>

        <!-- 社交链接卡片 -->
        <div class="card">
            <h2 class="card-title">🌐 找到我</h2>
            <div class="social-links">
                <a href="https://github.com/JiuGeGe520" style="text-decoration: none;">
                    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
                </a>
                <a href="https://jiugg.fun" style="text-decoration: none;">
                    <img src="https://img.shields.io/badge/个人网站-4F46E5?style=for-the-badge&logo=globe&logoColor=white" alt="个人网站">
                </a>
                <a href="https://blog.jiugg.fun/" style="text-decoration: none;">
                    <img src="https://img.shields.io/badge/我的博客-FF6B6B?style=for-the-badge&logo=blogger&logoColor=white" alt="我的博客">
                </a>
                <a href="https://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=naiwenzhu123@qq.com" style="text-decoration: none;">
                    <img src="https://img.shields.io/badge/QQ邮箱-D14836?style=for-the-badge&logo=qq&logoColor=white" alt="QQ邮箱">
                </a>
            </div>
        </div>

        <!-- 底部信息 -->
        <div class="footer">
            <hr class="footer-hr">
            <p>📍 立足广东 · 天汪科技总负责人<br>⭐️ Made with ❤️ by 九戈戈（JiuGeGe520）</p>
        </div>
    </div>
</body>
</html>
