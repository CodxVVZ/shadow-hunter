# Caçador de Sombras — projeto Android

Este projeto empacota os arquivos web do jogo dentro de um app Android usando WebView. Os recursos são incluídos no APK, então o jogo não depende do GitHub Pages para abrir.

## Gerar APK gratuitamente pelo GitHub Actions

1. Crie um repositório novo no GitHub (público ou privado) chamado `shadow-hunter-apk`.
2. Envie todos os arquivos e pastas deste projeto para a raiz do repositório, preservando a pasta `.github/workflows`.
3. Abra a aba **Actions**. Se necessário, habilite workflows.
4. Selecione **Build Shadow Hunter APK** e toque em **Run workflow**, ou faça um commit na branch `main` para iniciar automaticamente.
5. Quando terminar com sucesso, abra a execução e baixe o artefato `shadow-hunter-debug-apk`.
6. Extraia o ZIP baixado; dentro estará `app-debug.apk`. Transfira para o Android e instale.

Este é um APK de teste (`debug`), não um pacote pronto para publicar na Google Play. O GitHub Actions compila o APK nos servidores do GitHub; não é necessário instalar o Android SDK no Termux.
