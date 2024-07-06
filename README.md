### Template

```markdown
Land Page Bootcamp Nexa - Fundamentos de IA Generativa e Claude 3

## 📒 Descrição
Land Page para prospeção de clientes para o  Bootcamp Nexa - Fundamentos de IA Generativa e Claude 3

## 🤖 Tecnologias Utilizadas
ChatGPT

## 🧐 Processo de Criação
Solicitei ao ChatGPT para que criasse uma página HTML com a intenção de que as pessoas interessadas pudessem se inscrever.

Orientei o ChatGPT basicamente para que incluísse o nome do Bootcamp e que o mesmo fosse chamativo e vendedor.

Solicitei também que desse ênfase nos seguintes pontos:

Aprendizado: Enfatizar a qualidade do ensino e os diferenciais do Bootcamp.
Mentoria Especializada: Destacar a experiência e qualificação dos mentores.
Projetos Práticos: Ressaltar a importância da prática para o aprendizado e a relevância dos projetos para o mercado de trabalho


## 🚀 Resultados
Com a ferramenta, consegui criar uma página HTML clean, intuitiva e de fácil uso, mesmo sem ter experiência em programação. Em apenas alguns minutos, consegui estruturar a página, adicionar conteúdo e formatar o texto.

## 💭 Reflexão (Opcional)
Foi divertido e desafiador ao mesmo tempo, não sabia nada de código apenas sabia as perguntas que queria.
```
# Código HMTL criado pelo ChatGpt

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bootcamp Nexa - Fundamentos de IA Generativa e Claude 3</title>
  <style>
    /* Estilos CSS */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    main {
      padding: 40px;
    }
    .hero {
      text-align: center;
      margin-bottom: 40px;
    }
    .features {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-bottom: 40px;
    }
    .features div {
      width: 300px;
      margin: 20px;
      text-align: center;
    }
    .cta {
      text-align: center;
      margin-bottom: 40px;
    }
    .cta button {
      background-color: #333;
      color: #fff;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bootcamp Nexa - Fundamentos de IA Generativa e Claude 3</h1>
  </header>
  <main>
    <div class="hero">
      <h2>Domine os Fundamentos da IA Generativa e Claude 3</h2>
      <p>Aprenda as técnicas mais avançadas em IA Generativa e explore as possibilidades do Claude 3.</p>
    </div>
    <div class="features">
      <div>
        <h3>Aprendizado Personalizado</h3>
        <p>Conteúdo adaptado às suas necessidades e nível de conhecimento.</p>
      </div>
      <div>
        <h3>Mentoria Especializada</h3>
        <p>Acompanhamento de experts em IA Generativa e Claude 3.</p>
      </div>
      <div>
        <h3>Projetos Práticos</h3>
        <p>Desenvolva projetos reais e aplique o que aprendeu.</p>
      </div>
    </div>
    <div class="cta">
      <h2>Inscreva-se agora!</h2>
      <button onclick="redirectToRegistration()">Quero me inscrever</button>
    </div>
  </main>
  <script>
    function redirectToRegistration() {
      // Redirecionar o usuário para a página de inscrição
      window.location.href = "https://www.example.com/registro";
    }
  </script>
</body>
</html>
