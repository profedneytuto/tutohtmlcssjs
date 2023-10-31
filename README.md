# [tutorial] Aprenda a Criar e Publicar Páginas Web sem Baixar Nada! 🚀

Olá pessoal, eu sou o professor Edney Rossi, dou aulas em escolas públicas e particulares, e muitas vezes não é permitido “instalar programas”,  sim absurdo,  eu sei, mas é a realidade, contornando este impedimento passei a utilizar ferramentas online,  e hoje vou  mostrar como criar e publicar uma página usando HTML, CSS e JavaScript, tudo sem precisar baixar nada para o seu computador. É isso mesmo, vamos usar apenas o seu navegador web e ferramentas online como Visual Studio Code Web e o GitHub Pages. Preparados? Vamos nessa!

## Passo 1: Criando uma conta no GitHub

Primeiro, vamos criar uma conta no GitHub ( se você ainda não tiver), que será o nosso repositório de código. Siga estes passos:
Acesse GitHub e clique em "Sign up".
Insira seu e-mail e clique em "Continue".
Crie uma senha forte com letras maiúsculas, minúsculas, números e um caractere especial.
Escolha um nome de usuário único que o identificará no GitHub.
Complete o teste para verificar se você não é um robô.
Verifique seu e-mail para receber o código de confirmação e clique no link.
Você acaba de criar uma conta no GitHub!

## Passo 2: Criando um Repositório

Agora, vamos criar um repositório onde você vai hospedar seus arquivos da página web:
No painel de controle do GitHub, clique em "Create repository".
Dê um nome ao seu repositório, por exemplo, "MeuSiteHTML".
Certifique-se de que ele seja público.
Marque a opção "Add a README file" para criar um arquivo README no repositório.
Clique em "Create repository".

## Passo 3: Configurando o Visual Studio Code Web

Agora, vamos usar o Visual Studio Code Web, que roda diretamente no seu navegador. Siga esses passos:
Pesquise "Visual Studio Code Web" na barra de busca.
Abra o Visual Studio Code Web e faça login com a sua conta do GitHub.
Clique em "Open Remote Repository" e cole o endereço do seu repositório recém-criado.

## Passo 4: Criando sua Página Web

Agora é hora de criar a sua página web. Vamos seguir os passos:
Clique no seu repositório no Visual Studio Code Web.
Clique no botão "+", escolha "New file" e dê o nome "index.html".
Cole o seguinte código HTML:

    <!DOCTYPE html>
    <html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Criando página WEB sem baixar nada</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <h1>Criando página WEB sem baixar nada</h1>
        <button onclick="myFunction()">Não aperte este botão</button>
        <!--Coloque o link para o arquivo JS depois do botão-->
        <script src="script.js"></script>
    </body>
    </html>



Clique em "Commit" para salvar as alterações.

## Passo 5: Adicionando Estilos com CSS

Vamos adicionar um estilo simples à nossa página. Siga esses passos:
Clique no seu repositório no Visual Studio Code Web.
Clique no botão "+", escolha "New file" e dê o nome "style.css".
Cole o seguinte código CSS no arquivo:

body{
    background-color: burlywood;
}




Clique em "Commit" para salvar as alterações.

## Passo 6: Adicionando JavaScript

Agora, vamos adicionar JavaScript para exibir um alerta quando o botão for clicado:
Clique no seu repositório no Visual Studio Code Web.
Clique no botão "+", escolha "New file" e dê o nome "script.js".
Cole o seguinte código JavaScript:

function myFunction() {
    alert("Sim eu sou uma janela chata JavaScript");
  }




Clique em "Commit" para salvar as alterações.

## Passo 7: Publicando sua Página Web

Agora que tudo está pronto, vamos publicar a sua página web. Siga esses passos:
Vá para as configurações do seu repositório.
No menu à esquerda, clique em "Pages".
Escolha a branch onde estão seus arquivos (provavelmente será a branch "main").
Clique em "Save".
Agora, aguarde alguns minutos até que a página seja publicada. Depois, você poderá acessá-la usando o link que aparecerá na seção "Pages" das configurações do seu repositório.
E é isso! Você acabou de criar e publicar sua página web sem precisar baixar nada. Agora, você pode compartilhar o link com outras pessoas e mostrar seu trabalho ao mundo. Divirta-se criando! 😎🌐🚀

Este Tutorial em vídeo: https://youtu.be/IQCEUfungAo?si=CRrbjalXOk0Z2sWK
Repositório deste Tutorial: https://github.com/profedney/tutohtmlcssjs 
Página deste tutorial: https://profedney.github.io/tutohtmlcssjs/ 

O que achou do tutorial? Foi útil? te ajudou de alguma forma? sugestões para o próximo tutorial?
