<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professora Deblyane Ribeiro Correia - Aulas Particulares</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #f4f7f6;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .card {
            background-color: #ffffff;
            border-radius: 12px;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            width: 100%;
            overflow: hidden;
            text-align: center;
        }

        .card-header {
            background-color: #007bff;
            color: white;
            padding: 30px 20px 20px 20px;
        }

        .profile-pic {
            max-width: 90px; 
            aspect-ratio: 1 / 1;
            border-radius: 15px;
            margin: 20px auto 0 auto;
            border: 4px solid #ffffff; 
            object-fit: cover;
            display: block;
        }
        
        .card-header h1 {
            margin: 0;
            font-size: 1.8em;
            color: white;
        }

        .card-header h2 {
            margin: 5px 0 0 0;
            font-size: 1.1em;
            font-weight: 400;
            color: #e6f2ff;
        }

        .card-body {
            padding: 25px;
        }

        .card-body p {
            font-size: 1.1em;
            color: #555;
            line-height: 1.6;
            margin-bottom: 25px;
        }

        .info-list {
            list-style-type: none;
            padding: 0;
            margin: 0 0 30px 0;
            text-align: left;
        }

        .info-list li {
            position: relative;
            padding-left: 30px;
            margin-bottom: 12px;
            font-size: 1.05em;
        }

        .info-list li::before {
            content: '✓';
            color: #28a745;
            font-weight: 700;
            position: absolute;
            left: 0;
            top: 0;
        }

        .whatsapp-button {
            display: block;
            width: 100%;
            padding: 18px;
            background-color: #25D366;
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            font-weight: 700;
            border-radius: 8px;
            box-sizing: border-box;
            transition: background-color 0.2s;
        }

        .whatsapp-button:hover {
            background-color: #1EAE50;
        }
    </style>
</head>
<body>

    <div class="card">
        
        <div class="card-header">
            <h1>Professora Deblyane Ribeiro Correia </h1>
            <h2>Especialista em Apoio Pedagógico Personalizado para o Desenvolvimento Infantil
</h2>
            <img src="https://uploads.onecompiler.io/43s363kb2/4437nswsn/Captura%20de%20tela%202025-10-30%20175353.png" alt="Foto de perfil da Professora Ana Costa" class="profile-pic">
        </div>
        
        <div class="card-body">
            <p>
                Com mais de 10 anos de experiência, ajudo alunos a alcançarem a nota máxima na redação do ENEM e vestibulares.
            </p>

            <ul class="info-list">
                <li>Aulas de Gramática Aplicada</li>
                <li>Correção Detalhada de Redação</li>
                <li>Preparo para ENEM e Vestibulares</li>
                <li>Aulas online e presenciais</li>
            </ul>

            <a href="#" id="whatsapp-link" class="whatsapp-button" target="_blank">
                Entre em Contato
            </a>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            
            const seuNumeroWhatsApp = "553499508646"; 
            
            const suaMensagem = "Olá, Professora Deblyane! Vi seu site e gostaria de mais informações sobre as aulas.";

            const mensagemCodificada = encodeURIComponent(suaMensagem);
            
            const urlWhatsApp = `https://wa.me/${seuNumeroWhatsApp}?text=${mensagemCodificada}`;
            
            document.getElementById('whatsapp-link').href = urlWhatsApp;
        });
    </script>

</body>
</html>
