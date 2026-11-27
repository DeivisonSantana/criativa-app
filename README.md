# Criativa para Windows, Mac e Linux

App de desktop da [Criativa](https://jogos.criativa.live), o hub de jogos para lives do TikTok. Este repositório guarda só os instaladores e o arquivo de atualização de cada versão.

Baixe a versão mais nova em [Releases](https://github.com/lmardark/criativa-app/releases/latest) e, depois de instalar, entre com a sua conta da Criativa (precisa de passe ativo).

## Windows

1. Baixe o arquivo `Criativa_..._x64-setup.exe`.
2. Abra o arquivo. Enquanto o app não tem certificado, o Windows mostra "O Windows protegeu o computador":
   1. clique em **Mais informações**;
   2. clique em **Executar assim mesmo**.
3. O instalador não pede administrador: instala só para o seu usuário.

## Mac (Apple Silicon: M1 em diante)

1. Baixe o arquivo `Criativa_..._aarch64.dmg`, abra e arraste a Criativa para a pasta Aplicativos.
2. Na primeira vez, o Mac bloqueia o app, porque ele ainda não tem a assinatura da Apple:
   1. abra **Ajustes do Sistema > Privacidade e Segurança**;
   2. desça até a mensagem sobre a Criativa e clique em **Abrir Mesmo Assim**.
3. Mac com processador Intel ainda não tem versão.

## Linux (x86_64)

- **AppImage** (se atualiza sozinho):
  1. baixe o `Criativa_..._amd64.AppImage`;
  2. dê permissão de execução (`chmod +x Criativa_*.AppImage`);
  3. abra.
- **Debian e Ubuntu:** baixe o `Criativa_..._amd64.deb` e instale com `sudo apt install ./Criativa_*.deb`. Essa versão não se atualiza sozinha: baixe a nova a cada versão.

## Como funciona

- O app abre o hub da Criativa e fica no ícone perto do relógio (no Mac, na barra de menus) quando você fecha a janela.
- Os links dos jogos no OBS e no TikTok LIVE Studio são os mesmos de sempre.
- Cada conta usa o app em um PC por vez.
- O app se atualiza sozinho ao abrir (no Linux, só o AppImage).
