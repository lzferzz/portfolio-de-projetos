<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meus Projetos p5.js</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 40px 0;
        }
        
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #ED225D; /* Cor do p5.js */
        }
        
        header p {
            font-size: 1.2rem;
            color: #586069;
        }
        
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        
        .portfolio-item {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        
        .portfolio-item:hover {
            transform: translateY(-5px);
        }
        
        .portfolio-content {
            padding: 20px;
        }
        
        .portfolio-content h3 {
            margin-bottom: 10px;
            color: #ED225D; /* Cor do p5.js */
        }
        
        .portfolio-content p {
            color: #586069;
            margin-bottom: 15px;
        }
        
        .btn {
            display: inline-block;
            background: #ED225D;
            color: white;
            padding: 8px 16px;
            border-radius: 4px;
            text-decoration: none;
            font-weight: 600;
            transition: background 0.3s ease;
        }
        
        .btn:hover {
            background: #C2185B;
        }
        
        footer {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            color: #586069;
        }
        
        @media (max-width: 768px) {
            .portfolio-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Meus Projetos p5.js</h1>
            <p>Confira abaixo meus projetos criados com p5.js</p>
        </header>
        
        <main>
            <div class="portfolio-grid">
                <!-- Projeto 1 -->
                <div class="portfolio-item">
                    <div class="portfolio-content">
                        <h3>Projeto 1</h3>
                        <p>Descrição breve do projeto. O que ele faz, conceitos utilizados e objetivo.</p>
                        <a https://editor.p5js.org/00001228804564sp/full/vptfSag9V" class="btn" target="_blank">Ver Projeto</a>
                    </div>
                </div>
                
                <!-- Projeto 2 -->
                <div class="portfolio-item">
                    <div class="portfolio-content">
                        <h3>Projeto 2</h3>
                        <p>Descrição breve do projeto. O que ele faz, conceitos utilizados e objetivo.</p>
                        <a https://editor.p5js.org/00001228804564sp/full/vptfSag9V" class="btn" target="_blank">Ver Projeto</a>
                    </div>
                </div>
                
                <!-- Projeto 3 -->
                <div class="portfolio-item">
                    <div class="portfolio-content">
                        <h3>Projeto 3</h3>
                        <p>Descrição breve do projeto. O que ele faz, conceitos utilizados e objetivo.</p>
                        <a https://editor.p5js.org/00001228804564sp/full/h7S0ufes4" class="btn" target="_blank">Ver Projeto</a>
                    </div>
                </div>
                
                <!-- Template para novos projetos -->
                <!--
                <div class="portfolio-item">
                    <div class="portfolio-content">
                        <h3>Nome do Projeto</h3>
                        <p>Descrição do projeto.</p>
                        <a https://editor.p5js.org/00001228804564sp/full/h7S0ufes4" class="btn" target="_blank">Ver Projeto</a>
                    </div>
                </div>
                -->
            </div>
        </main>
        
        <footer>
            <p>© <span id="year"></span> Meus Projetos p5.js. Todos os direitos reservados.</p>
        </footer>
    </div>
    
    <script>
        // Atualiza o ano no footer automaticamente
        document.getElementById('year').textContent = new Date().getFullYear();
    </script>
</body>
</html>
