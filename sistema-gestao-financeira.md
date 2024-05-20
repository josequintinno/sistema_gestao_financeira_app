## Sistema de Gestão Financeira - SISGESFIN

#### Configurar Ambiente de Desenvolvimento (MacOS)

- &#9745; Instalar o JDK (v17)
    - Criar variáveis de ambiente

- &#9745; Instalar o Node Version Manager (NVM)
    - Criar arquivo _zshrc_
        > touch .zshrc

- &#9745; Instalar o NodeJS (v20)

- &#9745; Instalar _Android Studio Code_
    - Configurar SDK

- &#9745; Cordova (Android)

    Adicionar Plataforma Android
    > cordova add platform android    

- &#9745; Cordova (IOS)

    - Antes de construir o projeto deve-se executar esse comando

    ```java
    sudo xcode-select -s /Applications/Xcode.app/Contents/Developer
    ```

    - Construir o projeto

    ```java
    cordova add platform ios
    ```

    - Gerar executável

    ```java
    cordova build ios
    ```