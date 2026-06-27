# Palha Italiana - Site de Divulgação

Este é um site estático simples para divulgar e vender Palha Italiana. Ele foi criado para ser publicado gratuitamente com GitHub Pages.

## Como usar

1. Coloque as fotos reais na pasta `images/`.
2. Atualize os nomes dos arquivos em `index.html` se necessário.
3. Substitua o número do WhatsApp e o perfil do Instagram pelos seus dados reais.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub, por exemplo `palha-italiana`.
2. Faça commit destes arquivos e envie para o GitHub:
   ```bash
   git init
   git add .
   git commit -m "Site inicial de Palha Italiana"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/palha-italiana.git
   git push -u origin main
   ```
3. No GitHub, vá em `Settings` > `Pages`.
4. Defina a fonte como `Branch: main` e `Folder: / (root)`.
5. Salve. O site ficará disponível em `https://SEU_USUARIO.github.io/palha-italiana/`.

## Personalizar

- Edite `index.html` para mudar textos, sabores e contatos.
- Edite `styles.css` para ajustar cores e layout.
- Adicione ou substitua imagens na pasta `images/`.
