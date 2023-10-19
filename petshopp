<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CachorroLoko - Seu Petshop de Confiança</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background-color: #f7f7f7;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            background-color: #00aa00;
            text-align: center;
            padding: 20px 0;
        }

        header h1 {
            font-size: 48px;
            color: #fff;
            text-shadow: 2px 2px 4px #000;
            margin: 0;
        }

        .content {
            display: flex;
            flex: 1;
        }

        #sidebar {
            width: 250px;
            background-color: #333;
            padding: 20px 0;
            text-align: center;
            color: #fff;
        }

        #sidebar a {
            color: #fff;
            text-decoration: none;
            display: block;
            margin: 10px 0;
            font-size: 20px;
            transition: background-color 0.3s;
        }

        #sidebar a:hover {
            background-color: #00aa00;
        }

        .services {
            flex: 1;
            padding: 40px;
        }

        .services h2 {
            font-size: 36px;
            color: #333;
            margin: 0;
        }

        .service-description {
            font-size: 20px;
            color: #555;
            margin-top: 20px;
        }

        .service-description p {
            display: none;
        }

        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>CachorroLoko</h1>
    </header>

    <div class="content">
        <div id="sidebar">
            <a href="javascript:void(0);" onclick="showService('banho')">Banho</a>
            <a href="javascript:void(0);" onclick="showService('tosa')">Tosa</a>
            <a href="javascript:void(0);" onclick="showService('levatraz')">Sistema Leva e Traz</a>
            <a href="javascript:void(0);" onclick="showService('vacina')">Vacinação</a>
            <a href="javascript:void(0);" onclick="showService('vermifugacao')">Vermifugação</a>
            <a href="javascript:void(0);" onclick="showService('atendimento')">Atendimento Veterinário</a>
            <a href="javascript:void(0);" onclick="showService('hospedagem')">Hospedagem</a>
        </div>

        <div class="services">
            <h2>Nossos Serviços</h2>
            <div class="service-description">
              <img src="./img/cachorro.JPG" alt="Uma imagem de um cachorro">


                <p id="banho">
                    <strong>Banho:</strong> Em nosso serviço de banho, oferecemos um tratamento de spa completo para o seu pet. Usamos produtos naturais e hipoalergênicos, garantindo que seu animal de estimação saia não apenas limpo, mas também relaxado e revigorado. Nossos banhistas especializados sabem como proporcionar uma experiência de bem-estar para o seu pet, deixando-o com um pelo brilhante e cheiroso.
                </p>
                <p id="tosa">
                    <strong>Tosa:</strong> Nossos groomers são verdadeiros artistas quando se trata de tosar. Eles não apenas deixarão seu pet com um visual incrível, mas também garantirão que o corte seja adequado para a raça e as necessidades individuais. Seu pet sairá daqui não apenas parecendo incrível, mas também se sentindo mais leve e confortável.
                </p>
                <p id="levatraz">
                    <strong>Sistema Leva e Traz:</strong> Oferecemos um serviço de busca e entrega que torna a vida mais fácil para você e seu pet. Basta agendar, e nossa equipe irá buscar seu animal de estimação em casa, levá-lo para nossos serviços e trazê-lo de volta após o tratamento. O conforto e a comodidade são nossas prioridades, permitindo que você economize tempo e esforço.
                </p>
                <p id="vacina">
                    <strong>Vacinação:</strong> A saúde do seu pet é nossa prioridade. Nossos veterinários experientes fornecerão vacinas essenciais e preventivas para garantir que seu amigo peludo esteja protegido contra doenças. Nossa clínica de vacinação é segura e acolhedora, e nossos profissionais de saúde animal estão comprometidos em manter seu pet saudável e feliz.
                </p>
                <p id="vermifugacao">
                    <strong>Vermifugação:</strong> A vermifugação regular é crucial para manter seu pet livre de parasitas internos. Utilizamos produtos seguros e eficazes para garantir que seu animal de estimação esteja protegido contra vermes. Um pet saudável é um pet feliz, e estamos aqui para ajudar a manter seu amigo peludo saudável e vibrante.
                </p>
                <p id="atendimento">
                    <strong>Atendimento Veterinário:</strong> Nossos veterinários dedicados estão disponíveis para oferecer cuidados abrangentes ao seu pet. De consultas de rotina a tratamentos específicos, estamos comprometidos em manter a saúde e o bem-estar do seu amigo peludo. Conte conosco para fornecer atendimento de alta qualidade e personalizado.
                </p>
                <p id="hospedagem">
                    <strong>Hospedagem:</strong> Quando você precisa viajar, confie-nos o cuidado do seu pet. Nossa hospedagem oferece aconchego e segurança, com quartos limpos e confortáveis para seu amigo de quatro patas. Nossa equipe amorosa garante que seu pet se sinta em casa, com cuidados 24 horas por dia, garantindo que você possa viajar tranquilamente.
                </p>
            </div>
        </div>
    </div>

    <footer>
       <p>&copy; CachorroLoko 2023 - Todos os direitos reservados - Filipe Motta - RA: 320100474
    </footer>

    <script>
        function showService(service) {
            var serviceDescriptions = document.querySelectorAll('.service-description p');
            for (var i = 0; i < serviceDescriptions.length; i++) {
                serviceDescriptions[i].style.display = 'none';
            }
            document.getElementById(service).style.display = 'block';
        }
    </script>
</body>
</html>
