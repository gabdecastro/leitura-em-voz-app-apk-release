# Guia de Instalação do APK no Android (App Leitura em Voz)

Este guia explica como instalar o APK gerado no seu dispositivo Android. Certifique-se de seguir os passos abaixo cuidadosamente para garantir uma instalação bem-sucedida.

## Passo 1: Escolha o APK correto
O build gerou vários APKs otimizados para diferentes arquiteturas de CPU. Escolha o arquivo APK correspondente à arquitetura do seu dispositivo:

- **app-arm64-v8a-release.apk**: Para dispositivos com arquitetura ARM de 64 bits.
- **app-armeabi-v7a-release.apk**: Para dispositivos com arquitetura ARM de 32 bits.
- **app-x86_64-release.apk**: Para dispositivos com arquitetura x86 de 64 bits.

Se não souber a arquitetura do seu dispositivo, geralmente a versão **ARM64** é a mais comum em dispositivos modernos.

## Passo 2: Habilitar a Instalação de Apps de Fontes Desconhecidas
1. Abra as configurações do seu dispositivo Android.
2. Navegue até **Segurança** ou **Privacidade** (o nome pode variar dependendo do fabricante).
3. Ative a opção **Permitir a instalação de apps de fontes desconhecidas**.

> **Nota**: Em versões mais recentes do Android, você precisará permitir essa configuração para o app que está gerenciando o arquivo APK, como o gerenciador de arquivos ou navegador usado para baixá-lo.

## Passo 3: Transferir o APK para o Dispositivo
Caso o APK esteja no seu computador, siga um dos métodos abaixo para transferi-lo para o dispositivo Android:

- **Via cabo USB**:
  1. Conecte o dispositivo ao computador com um cabo USB.
  2. Transfira o arquivo APK para a pasta desejada no dispositivo.

- **Via serviços de armazenamento na nuvem**:
  1. Faça upload do APK para um serviço como Google Drive, Dropbox, ou OneDrive.
  2. Acesse o serviço no dispositivo e faça o download do arquivo.

## Passo 4: Instalar o APK
1. Abra o gerenciador de arquivos no dispositivo Android.
2. Navegue até o local onde o APK foi salvo.
3. Toque no arquivo APK para iniciar a instalação.
4. Caso solicitado, conceda permissões e confirme a instalação.

> **Dica**: Se aparecer uma mensagem de bloqueio de segurança, volte para o **Passo 2** e certifique-se de ter habilitado a instalação de apps de fontes desconhecidas.

## Passo 5: Concluir a Instalação
Aguarde até que o processo de instalação seja concluído. Após isso, você poderá abrir o aplicativo diretamente ou encontrá-lo na gaveta de apps do seu dispositivo.

---

## Resolução de Problemas
- **Erro de arquitetura incompatível**: Certifique-se de que escolheu o APK correto para a arquitetura do seu dispositivo.
- **Instalação bloqueada**: Verifique as configurações de segurança do dispositivo e habilite a instalação de fontes desconhecidas.
- **App não abre após instalação**: Verifique se você baixou a versão correta (release) e tente reinstalar o APK.

