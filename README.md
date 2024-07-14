# Roma.com
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人网页</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        section#main {
            padding: 20px;
            background: #fff;
            margin: 20px 0;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 30px 0;
            margin-top: 20px;
        }
        .profile-pic {
            float: left;
            width: 150px;
            height: 150px;
            margin-right: 20px;
            border-radius: 50%;
        }
        .clearfix::after {
            content: "";
            clear: both;
            display: table;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>我的个人网页</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">关于我</a></li>
                    <li><a href="#skills">技能特长</a></li>
                    <li><a href="#experience">工作经验</a></li>
                    <li><a href="#projects">项目展示</a></li>
                    <li><a href="#education">教育背景</a></li>
                    <li><a href="#contact">联系信息</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="main" class="container">
        <section id="about">
            <h2>关于我</h2>
            <img src="profile-pic.jpg">
            <p>你好！我是蔡金云,一位中医名家，喜欢学习新技术并将其应用到实际项目中。</p>
        </section>

        <section id="skills" class="clearfix">
            <h2>技能特长</h2>
            <ul>
                <li>编程语言：HTML, CSS, JavaScript, Python</li>
                <li>框架和库：React, Vue, Django</li>
                <li>工具：Git, Docker, Webpack</li>
            </ul>
        </section>

        <section id="experience">
            <h2>工作经验</h2>
            <h3>某科技公司</h3>
            <p>软件开发工程师 | 2018 - 2021</p>
            <ul>
                <li>负责前端开发，使用React和Redux</li>
                <li>参与后端开发，使用Django框架</li>
                <li>维护和优化现有系统</li>
            </ul>
        </section>

        <section id="projects">
            <h2>项目展示</h2>
            <h3>个人博客</h3>
            <p>一个使用React和Node.js开发的个人博客网站。</p>
            <h3>电商平台</h3>
            <p>参与开发一个基于Django的电商平台，主要负责前端和部分后端开发。</p>
        </section>

        <section id="education">
            <h2>教育背景</h2>
            <h3>某大学</h3>
            <p>计算机科学与技术 | 本科 | 2014 - 2018</p>
        </section>

        <section id="contact">
            <h2>联系信息</h2>
            <p>邮箱: viesjeck@gmail.com</p>
            <p>电话: 123-456-7890</p>
        </section>
    </section>

    <footer>
        <p>版权所有 &copy; 2024</p>
    </footer>
</body>
</html>
