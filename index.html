<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login API</title>
</head>
<body>
    <h1>Login na API</h1>
    
    <!-- Formulário simples para email e senha -->
    <form id="loginForm">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>
        
        <label for="password">Senha:</label>
        <input type="password" id="password" name="password" required><br><br>
        
        <button type="submit">Login</button>
    </form>

    <p id="message"></p> <!-- Para exibir mensagens de erro ou sucesso -->

    <script>
        // Seleciona o formulário e adiciona o evento de 'submit'
        document.getElementById('loginForm').addEventListener('submit', async function(event) {
            event.preventDefault(); // Previne o comportamento padrão de envio de formulário

            // Coleta os valores de email e senha do formulário
            const email = document.getElementById('email').value;
            const password = document.getElementById('password').value;

            try {
                // Faz a requisição POST para o endpoint de login
                const response = await fetch('https://sua-api.com/api/login', {
                    method: 'POST',
                    headers: {
                        'Content-Type': 'application/json'
                    },
                    body: JSON.stringify({
                        email: email,
                        password: password
                    })
                });

                const data = await response.json();

                if (response.ok) {
                    // Exibe o token recebido no console e em uma mensagem
                    console.log('Token recebido:', data.token);
                    document.getElementById('message').innerText = 'Login realizado com sucesso! Token: ' + data.token;
                    
                    // Salva o token no localStorage (opcional)
                    localStorage.setItem('token', data.token);
                } else {
                    // Exibe a mensagem de erro
                    document.getElementById('message').innerText = 'Erro no login: ' + data.message;
                }
            } catch (error) {
                console.error('Erro na requisição:', error);
                document.getElementById('message').innerText = 'Erro na requisição: ' + error.message;
            }
        });
    </script>

</body>
</html>
