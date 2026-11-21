# Gerar o APK usando somente o celular

Este projeto pode ser compilado na nuvem pelo GitHub Actions, sem instalar Android Studio no celular.

1. No navegador, entre em https://github.com e crie/acesse sua conta.
2. Crie um repositório novo (por exemplo, `mc1h-android`). Deixe-o privado se preferir.
3. Extraia este ZIP no celular com o ZArchiver.
4. Envie os arquivos e pastas que estão dentro de `mc1h-freefire-android` para a raiz do repositório. Inclua também a pasta oculta `.github` e seu arquivo `workflows/build-apk.yml`.
5. No GitHub, abra a aba **Actions**, selecione **Build Android APK** e toque em **Run workflow**.
6. Aguarde a execução terminar com sucesso. Abra a execução concluída e baixe o artefato **mc1h-debug-apk**.
7. Extraia o artefato baixado; dentro dele estará o APK de depuração.

Observações:
- A compilação ocorre nos servidores do GitHub; não é feita pelo ZArchiver.
- Não compartilhe o APK nem instale arquivos enviados por desconhecidos.
- O app é um painel independente de treinamento/configuração; não altera o Free Fire nem automatiza ações dentro do jogo.
