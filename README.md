<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gradient Concentration</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        .header {
            height: 48px;
            position: relative;
            overflow: hidden;
        }
        .gradient {
            width: 100%;
            height: 100%;
            position: absolute;
            top: 0;
            left: 0;
            background: linear-gradient(to bottom, rgba(0,255,0,1) 0%, rgba(0,0,0,1) 100%);
        }
        .content {
            position: relative;
            text-align: center;
            color: white;
            padding-top: 5px; 
            z-index: 1; /* Adicionei z-index para garantir que o conteúdo fique acima do gradiente */
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="gradient"></div>
        <div class="content">
            <h1>Hi! I'm Samuel Gama 👋🏻</h1>
            <a href="https://samuelfox30.github.io/">
                <img src="https://img.shields.io/website-up-down-green-red/http/monip.org.svg" alt="Portifolio">
            </a>
            <br>
            <a href="https://linkedin.com/in/samuel-raposo-072ab7266">
                <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Linkedin">
            </a>
            <a href="https://api.whatsapp.com/send/?phone=5527992297504&text&type=phone_number&app_absent=0">
                <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Whatsapp">
            </a>
            <a href="https://www.instagram.com/samuel.rgama?utm_source=qr">
                <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
            </a>
        </div>
    </div>

    <div>
        <h3>STATUS</h3>
        <img src="https://github-readme-stats.vercel.app/api?username=samuelfox30&show_icons=true&theme=tokyonight" alt="Samuel's GitHub stats">
    </div>

    <div>
        <h3>HARD-SKILLS</h3>
        <!-- Adicione aqui suas hard-skills -->
    </div>
</body>
</html>
