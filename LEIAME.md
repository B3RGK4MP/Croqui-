# Croqui de Rede – gerar o APK

Você não precisa instalar nada no computador. O GitHub compila o APK de graça.

1. Crie uma conta em github.com e um repositório novo (ex.: `croqui-rede`).
2. Envie todo o conteúdo desta pasta para o repositório (Add file > Upload files).
   Se a pasta `.github` não subir, use Add file > Create new file, digite o nome
   `.github/workflows/apk.yml` e cole o conteúdo do arquivo de mesmo nome.
3. Abra a aba **Actions** > **Gerar APK** > **Run workflow**. Leva uns 5 a 10 minutos.
4. Ao terminar, abra a execução e baixe **croqui-apk** (um .zip com o `app-debug.apk`).
5. Passe o APK para o celular/tablet e instale (permita "fontes desconhecidas").

Funciona 100% offline. Os desenhos ficam salvos no aparelho.
O botão PDF abre a tela de impressão do Android: escolha **Salvar como PDF**.

Observação: este APK é de teste (debug), bom para distribuir internamente.
Para publicar na Play Store é preciso gerar uma versão assinada (release).
