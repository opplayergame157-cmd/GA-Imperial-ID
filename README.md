# GA Imperial ID

Projeto Android inicial para o GA Imperial ID, com visual preto/vermelho e autenticação pelo diálogo biométrico do Android.

## Como compilar na nuvem

1. Envie o conteúdo desta pasta para a raiz do repositório GitHub `GA-Imperial-ID`, preservando os caminhos.
2. Faça commit dos arquivos na branch `main` (ou `master`).
3. Abra **Actions** e selecione **Build GA Imperial ID**. Também é possível compilar automaticamente após um push.
4. Abra a execução concluída e baixe o artefato `GA-Imperial-ID-debug-apk`.
5. Dentro do artefato estará `app-debug.apk`.

## Importante

- Esta é uma versão inicial de demonstração; o painel mostrado é local e não protege dados de servidor.
- A biometria é validada pelo sistema Android, não por código que lê ou armazena impressões digitais.
- O APK é de depuração, não uma versão assinada para distribuição pública.
- É necessário ter uma biometria ou credencial de bloqueio de tela configurada no aparelho para que o sistema permita autenticação.
