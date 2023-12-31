# Criando e Hospedando um Site no GitHub Pages

https://eduardo1985s.github.io/site-template/

Este repositório contém as instruções e os recursos necessários para criar um site simples e hospedá-lo no GitHub Pages. Siga os passos abaixo para começar:

## Passo 1: Crie o Seu Site

1. Escolha um tema ou tópico para o seu site. Pode ser um portfólio pessoal, um blog, um site de projeto, ou qualquer coisa que você desejar.

2. Crie um arquivo HTML para cada página do seu site. Você deve ter pelo menos três páginas: `index.html`, `sobre.html` e `contato.html`. Personalize o conteúdo de acordo com o seu tema.

3. Use folhas de estilo CSS (em um arquivo separado ou incorporado) para estilizar o seu site. Você pode adicionar imagens, fontes e outros recursos para tornar o seu site mais atraente.

## Passo 2: Faça o Upload para o GitHub

1. Crie uma conta no GitHub se você ainda não tiver uma.

2. Crie um novo repositório no GitHub, dando-lhe um nome descritivo, como "meu-site".

3. No seu computador, instale o Git se ainda não o fez e configure a sua identidade usando os comandos:
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu-email@example.com"
```

4. No seu terminal, navegue até o diretório onde estão os arquivos do seu site e execute os seguintes comandos:

```bash
git init
git add .
git commit -m "Primeiro commit: Adicionando paginas..."
git branch -M main
git remote add origin https://github.com/Eduardo1985S/site-template.git
git push -u origin main
```

# Ative o GitHub Pages
No repositório do GitHub, vá para a aba "Settings" (Configurações).

Role para baixo até encontrar a seção "GitHub Pages".

No menu suspenso "Source" (Origem), selecione "main branch" para usar a branch principal como fonte.

Clique em "Save" (Salvar).

Aguarde alguns minutos para que o GitHub Pages seja ativado.

Após a ativação, você encontrará o link para o seu site no formato: https://seu-usuario.github.io/meu-site.
