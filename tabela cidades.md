<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ATIVIDADE PRÁTICA DE ACESSO API</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 20px;
            color: #333;
        }
        h1 {
            color: #4CAF50;
            text-align: center;
        }
        .info {
            text-align: center;
            margin: 20px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        th, td {
            padding: 12px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        tr:hover {
            background-color: #f5f5f5;
        }
        .message {
            text-align: center;
            margin-top: 20px;
            color: #ff5722;
            display: none;
        }
    </style>
</head>
<body>

<h1>ATIVIDADE PRÁTICA DE ACESSO API</h1>

<div class="info">
    <p><strong>Nome completo:</strong> Marcelo Faffe Ribeiro Grillo</p>
    <p><strong>RA:</strong> 12623112780</p>
</div>

<table>
    <tr>
        <th>ID</th>
        <th>Nome</th>
    </tr>
    <tr>
        <td>1101450</td>
        <td>Parecis</td>
    </tr>
    <tr>
        <td>1715507</td>
        <td>Oliveira de Fátima</td>
    </tr>
    <tr>
        <td>3150000</td>
        <td>Pescador</td>
    </tr>
    <tr>
        <td>3159506</td>
        <td>Santa Rita do Itueto</td>
    </tr>
    <tr>
        <td>5003157</td>
        <td>Coronel Sapucaia</td>
    </tr>
</table>

<div class="message" id="message"></div>

<script>
    // Função para mostrar uma mensagem após um certo tempo
    function showMessage() {
        const messageDiv = document.getElementById('message');
        messageDiv.textContent = "Tabela carregada com sucesso!";
        messageDiv.style.display = 'block';
        setTimeout(() => {
            messageDiv.style.display = 'none';
        }, 3000);
    }

    // Chamar a função para mostrar a mensagem
    window.onload = showMessage;
</script>

</body>
</html>
