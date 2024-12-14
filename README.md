# Recriando o arquivo HTML corrigido
html_code = """
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Site oficial da [Nome da Empresa] - Especializada em Publicidade e Criação de Conteúdo.">
    <title>[Nome da Empresa] - Publicidade e Criação de Conteúdo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background: linear-gradient(to right, #333, #555);
            color: #fff;
            padding: 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        header img {
            height: 50px;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 10px;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-size: 16px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
            animation: fadeIn 1s ease-in-out;
        }
        .cta {
            background: #007BFF;
            color: white;
            padding: 10px 20px;
            text-align: center;
            margin: 20px auto;
            display: block;
            width: max-content;
            text-decoration: none;
            border-radius: 5px;
        }
        .cta:hover {
            background: #0056b3;
        }
        .services img, .portfolio img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 10px 0;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        footer a {
            color: #fff;
            margin: 0 10px;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
        form input, form textarea, form button {
            display: block;
            width: 100%;
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            background: #007BFF;
            color: white;
            border: none;
        }
        form button:hover {
            background: #0056b3;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logotipo da [Nome da Empresa]">
        <div>
            <h1>[Nome da Empresa]</h1>
            <p>Transformando ideias em resultados</p>
        </div>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#sobre">Sobre Nós</a>
        <a href="#servicos">Serviços</a>
        <a href="#portfolio">Portfólio</a>
        <a href="#contato">Contato</a>
    </nav>

    <section id="home">
        <h2>Bem-vindo à [Nome da Empresa]</h2>
        <p>Somos especialistas em publicidade e criação de conteúdo que conecta marcas ao seu público.</p>
        <a href="#servicos" class="cta">Conheça nossos serviços</a>
    </section>

    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Com anos de experiência no mercado, ajudamos empresas a se destacarem através de estratégias criativas e personalizadas. Nossa missão é trazer resultados reais para nossos clientes.</p>
    </section>

    <section id="servicos" class="services">
        <h2>Serviços</h2>
        <ul>
            <li>
                <img src="service1.jpg" alt="Criação de conteúdo para redes sociais">
                Criação de conteúdo para redes sociais
            </li>
            <li>
                <img src="service2.jpg" alt="Estratégias de marketing digital">
                Estratégias de marketing digital
            </li>
            <li>
                <img src="service3.jpg" alt="Design gráfico e identidade visual">
                Design gráfico e identidade visual
            </li>
            <li>
                <img src="service4.jpg" alt="Campanhas publicitárias">
                Campanhas publicitárias
            </li>
        </ul>
    </section>

    <section id="portfolio" class="portfolio">
        <h2>Portfólio</h2>
        <p>Confira alguns dos nossos projetos mais recentes:</p>
        <ul>
            <li>
                <img src="portfolio1.jpg" alt="Campanha 'Inovando com Criatividade'">
                Campanha "Inovando com Criatividade" para [Cliente]
            </li>
            <li>
                <img src="portfolio2.jpg" alt="Gestão de redes sociais">
                Gestão de redes sociais para [Cliente]
            </li>
            <li>
                <img src="portfolio3.jpg" alt="Design e branding">
                Design e branding para [Cliente]
            </li>
        </ul>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <p>Quer saber como podemos ajudar a sua marca? Entre em contato conosco:</p>
        <form>
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mensagem:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit" class="cta">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 [Nome da Empresa]. Todos os direitos reservados.</p>
        <a href="#">Termos de Uso</a>
        <a href="#">Política de Privacidade</a>
        <a href="#">Redes Sociais</a>
    </footer>
</body>
</html>
"""

# Salvando o arquivo HTML corrigido
file_path = "/mnt/data/site_empresa_publicidade.html"
with open(file_path, "w", encoding="utf-8") as file:
    file.write(html_code)

file_path
git add .
git commit -m "Adiciona arquivos do site"
git push origin main
![469834146_1156620339369244_1694713365185281126_n](https://github.com/user-attachments/assets/1ee438ff-e1a3-4300-84c5-3473cc2bd800)
![DALL·E-2024-12-14-14 56](https://github.com/user-attachments/assets/d9b1fd69-3ef5-429c-a322-3ff423078a31)
