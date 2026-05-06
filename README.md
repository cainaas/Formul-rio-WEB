# Formula-rio-WEB
Criação de tela de formulário WEB para envio de informações.


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Avaliação Prática 3 - Formulário Interativo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <main class="container">
        <form id="contactForm" novalidate>
            <h2>Cadastro de Aluno</h2>
            
            <div class="input-group">
                <label for="fullname">Nome Completo</label>
                <input type="text" id="fullname" placeholder="Digite seu nome completo">
                <span class="error-message" id="nameError">O nome deve ter pelo menos 3 caracteres.</span>
            </div>

            <div class="input-group">
                <label for="email">E-mail</label>
                <input type="email" id="email" placeholder="seu@email.com">
                <span class="error-message" id="emailError">Insira um e-mail válido.</span>
            </div>

            <button type="submit" id="submitBtn">Enviar Dados</button>
            <div id="successMessage" class="success-box">✅ Formulário enviado com sucesso!</div>
        </form>
    </main>
    <script src="script.js"></script>
</body>
</html>
