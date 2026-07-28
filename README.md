<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agência Tech Solutions</title>
    <link rel="stylesheet" href="FENIX.css">
    <link href="https://fonts.cdnfonts.com/css/modern-romance" rel="stylesheet">
</head>
<body>

    <nav class="topnav" id="topo">
        <div class="logo">TechSolutions</div>
        <button class="menu-toggle" id="btnMenu" aria-expanded="false">☰</button>
        <ul class="menu-links" id="menuLinks">
            <li><a href="#servicos">Serviços</a></li>
            <li><a href="#depoimentos">Depoimentos</a></li>
            <li><a href="#contato">Contato</a></li>
            <li><a href="#localizacao">Onde Estamos</a></li>
        </ul>
    </nav>

    <header id="servicos" class="carrossel-container">
        <div class="carrossel-slide ativa">
            <h1>Soluções em Nuvem</h1>
            <p>Escale sua infraestrutura com segurança.</p>
        </div>
        <div class="carrossel-slide">
            <h1>Desenvolvimento Web</h1>
            <p>Sistemas responsivos e de alta performance.</p>
        </div>
        <button class="btn-carrossel prev" onclick="mudarSlide(-1)">❮</button>
        <button class="btn-carrossel next" onclick="mudarSlide(1)">❯</button>
    </header>

    <main class="conteudo-principal">
        
        <section id="depoimentos" class="secao-pagina">
            <h2>O que nossos clientes dizem</h2>
            <div class="grid-cards">
                <article class="card">
                    <h3>Empresa Alpha</h3>
                    <p>"A migração do nosso banco de dados foi impecável. Zero tempo de inatividade."</p>
                </article>
                <article class="card">
                    <h3>Clinica Beta</h3>
                    <p>"O sistema construído sob medida revolucionou nosso atendimento."</p>
                </article>
                <article class="card">
                    <h3>Startup Gama</h3>
                    <p>"Consultoria de segurança que salvou nossa aplicação. Profissionais fantásticos."</p>
                </article>
            </div>
        </section>

<section id="sobre nós" class="secao-pagina">
            <h2>Quem somos?</h2>
            <div class=" sobreN">
                <article class="nós">
                    <h3>Sobre nós</h3>
                    <br>
                    <p>"A F.E.N.I.X é uma empresa focada em ajudar pessoas com dependência de nicotina e álcool que enfrentam dificuldades, sempre priorizando o bem-estar e a saúde mental. Também contamos com o apoio dos familiares durante toda a jornada, pois acreditamos que o suporte emocional é fundamental nesse processo.
O grupo não busca, necessariamente, acabar com o vício, mas sim reduzir o número de pessoas presas a esse problema. Sabemos que a superação depende de cada indivíduo, mas a F.E.N.I.X foi criada com o objetivo de apoiar, incentivar e mostrar que é possível superar desafios com acolhimento e motivação.
Nosso site foi desenvolvido de forma institucional para o curso de Multimídia, pois entendemos que esse é um tema relevante e importante de ser discutido."</p>
                </article>
                   <img src="alunos.jpg" alt="Sobre nós">
            </div>

       
    </section>

     </section>

<section id="arquivos" class="secao-pagina">
            <h2>Quem somos?</h2>
            <div class=" pdfs">
                <article class="livros">
                    <h3>livros</h3>
                    <br>
                    <p>compreendendo os vicios</p>
                </article>
                   <img src="arquivos/img_pdf2.jpg" alt="Sobre nós">
            </div>

<a href="arquivos/como superar um vicio.pdf" download class="botao">
    Baixar PDF
</a>

<a href="arquivos/manual.pdf" download class="botao">
    Baixar PDF
</a>

<a href="arquivos/manual.pdf" download class="botao">
    Baixar PDF
</a>

       
    </section>



        <section id="contato" class="secao-pagina secao-fundo-claro">
            <div class="container-formulario">
                <h2>Fale com um Especialista</h2>
                <p>Preencha os dados abaixo para detalhar sua necessidade.</p>
                
                <form id="formCadastro" class="form-cta">
                    <div class="grupo-campo">
                        <label for="nome">Nome Completo *</label>
                        <input type="text" id="nome" required placeholder="Ex: João Silva">
                    </div>
                    
                    <div class="grupo-campo">
                        <label for="email">E-mail Corporativo *</label>
                        <input type="email" id="email" required placeholder="Ex: joao@empresa.com">
                    </div>

                    <div class="grupo-campo">
                        <label for="assunto">Assunto Principal *</label>
                        <input type="text" id="assunto" required placeholder="Ex: Orçamento de Sistema, Dúvida Técnica">
                    </div>

                    <div class="grupo-campo">
                        <label for="mensagem">Breve descritivo do que precisa *</label>
                        <textarea id="mensagem" rows="4" required placeholder="Conte-nos brevemente sobre o seu projeto ou problema..."></textarea>
                    </div>
                    
                    <button type="submit" class="btn-enviar">Solicitar Atendimento 🚀</button>
                </form>
                <div id="mensagem-sucesso" class="feedback-sucesso"></div>
            </div>
        </section>

        <section id="localizacao" class="secao-pagina">
            <h2>Onde Estamos</h2>
            <p class="subtitulo-secao">Venha tomar um café conosco ou utilize a geolocalização para ver as coordenadas.</p>
            
            <div class="layout-localizacao">
                <div class="mapa-container">
                    <iframe 
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3714.471783515456!2d-48.9739446!3d-21.3121517!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMjHCsDE4JzQzLjciUyA0OMKwNTgnMjYuMiJX!5e0!3m2!1spt-BR!2sbr!4v1700000000000!5m2!1s0pt-BR!2sbr" 
                        allowfullscreen="" 
                        loading="lazy" 
                        referrerpolicy="no-referrer-when-downgrade">
                    </iframe>
                </div>

                <div class="gps-container">
                    <h3>Verificar Coordenadas</h3>
                    <p>Caso queira validar o sinal do seu dispositivo com nossa central, capture sua posição atual:</p>
                    <button id="btnLocalizacao" class="btn-acao">📍 Obter minhas coordenadas</button>
                    <p id="resultado-gps"></p>
                </div>
            </div>
        </section>
    </main>

    <footer class="rodape">
        <p>&copy; 2026 TechSolutions - Todos os direitos reservados.</p>
        <p>Desenvolvido para fins educacionais - Engenharia de Interface.</p>
    </footer>

    <button id="btnVoltarTopo" title="Voltar ao topo">⬆️</button>

  <div vw class="enabled">
    <div vw-access-button class="active"></div>
    <div vw-plugin-wrapper>
      <div class="vw-plugin-top-wrapper"></div>
    </div>
  </div>
  <script src="https://vlibras.gov.br/app/vlibras-plugin.js"></script>
  <script>
    new window.VLibras.Widget('https://vlibras.gov.br/app');
  </script>
<


    <script src="FENIX.js"></script>
</body>
</html>
