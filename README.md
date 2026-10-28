# Leandro TV OS - Launcher & Smart Hub Pro
**Desenvolvido exclusivamente por Leandro Corrêa**

Este projeto é um Launcher completo e moderno desenvolvido para **TV TCL 55" OLED com Google TV** e **Xiaomi Mi TV Stick / Mi Box**, oferecendo máxima fluidez, interface D-Pad otimizada para controle remoto, economia de painel OLED (Pure Black), e central de ferramentas em tempo real.

---

## 🌟 Principais Recursos

1. **Design OLED Pure Black**:
   - Fundo `#000000` absoluto que desliga os pixels da sua TV OLED TCL, garantindo contraste infinito, menor consumo de energia e proteção contra burn-in.
2. **Navegação 100% por Controle Remoto (D-Pad)**:
   - Suporte nativo às setas do controle (Cima, Baixo, Esquerda, Direita, Botão OK e Voltar).
3. **Painel de Informações Úteis na Inicialização**:
   - Relógio digital grande com data completa em português.
   - Previsão do tempo (Temperatura, Sensação, Umidade, Vento e previsão dos próximos dias).
   - Manchetes e notícias atualizadas automaticamente a cada 10 segundos.
   - Monitor de Hardware da TV: Uso de memória RAM, armazenamento livre e temperatura interna.
   - Monitor de Rede: Endereço IP local, DNS, qualidade do sinal e ping (latência).
4. **Central de Aplicativos**:
   - Acesso rápido aos principais apps (YouTube, Netflix, Prime Video, Disney+, Max, Globoplay, Spotify, Plex, SmartTube, etc.).
5. **Ferramentas Exclusivas**:
   - 🚀 **Otimizador / Limpar RAM**: Encerra processos em segundo plano com 1 clique para evitar travamentos no Mi Stick.
   - ⚡ **Teste de Velocidade de Conexão**: Medidor integrado de velocidade e ping.
   - ⏱️ **Sleep Timer (Temporizador)**: Desligamento automático em 15, 30, 60, 90 ou 120 minutos.
   - 🔌 **Seletor de Entradas HDMI**: Alternância rápida entre HDMI 1 (Console), HDMI 2 (eARC Soundbar) e HDMI 3.
   - 🌙 **Modo Cinema OLED**: Ajuste rápido de atenuação de luz para ambientes escuros.
6. **Área Sobre o Aplicativo**:
   - Tela dedicada destacando: **"Criado por Leandro Corrêa"**, versão 1.0.0 Pro, especificações técnicas e agradecimentos.

---

## 🚀 Como Gerar o APK Automaticamente (Sem precisar de PC potente)

Você tem 2 formas muito fáceis de ter o arquivo `.apk` pronto para instalar na TV:

### Opção 1: Via GitHub Actions (Gratuito e em 2 minutos)
1. Crie uma conta gratuita no [GitHub](https://github.com) se ainda não tiver.
2. Crie um novo repositório chamado `leandro-tv-launcher`.
3. Envie (upload) todos os arquivos desta pasta para o repositório.
4. O GitHub detectará automaticamente o arquivo `.github/workflows/build-apk.yml`.
5. Vá na aba **Actions** no seu GitHub: ele compilará o `.apk` nos servidores do Google/GitHub e liberará o download direto do `Leandro-TV-Launcher-v1.0.0-Debug.apk`!

### Opção 2: Via Android Studio no Computador
1. Abra o **Android Studio**.
2. Clique em **File > Open** e selecione a pasta descompactada deste projeto.
3. Aguarde o Gradle sincronizar e clique no menu **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. O arquivo `.apk` estará pronto na pasta `app/build/outputs/apk/debug/`.

---

## 📺 Como Instalar o APK na sua TCL 55 OLED e no Xiaomi Mi Stick

1. **Na sua TV ou Mi Stick**:
   - Abra a Google Play Store na TV.
   - Instale o aplicativo gratuito **Downloader by AFTVnews** ou **Send Files to TV (SFTTV)**.
2. **Transferir o APK**:
   - Se usar o **Downloader**: hospede o APK no seu Google Drive / Dropbox ou envie um link direto e digite no Downloader.
   - Se preferir via Pen Drive (na TCL OLED): copie o `.apk` para um pen drive USB, espete na TV e abra com o app File Commander.
3. **Ativar Fontes Desconhecidas**:
   - Nas configurações da TV, vá em **Privacidade / Segurança > Instalar apps desconhecidos** e dê permissão para o Downloader ou Gerenciador de Arquivos.
4. **Instalar**:
   - Clique no arquivo `.apk` e selecione **Instalar**.
5. **Definir como Launcher Padrão**:
   - Pressione o botão Home no controle remoto e selecione **Leandro TV Launcher** > **Sempre**.

---

## 🌐 Como Usar Imediatamente no Navegador da TV (Sem precisar de APK)
Se quiser usar o painel imediatamente na TV hoje mesmo:
1. Abra o navegador da TV (**TV Bro**, **JioPages** ou **Puffin TV**).
2. Abra o arquivo `leandro_tv_launcher.html` ou hospede no seu servidor / GitHub Pages.
3. Pressione a tecla de navegação do controle remoto: ele funciona com 100% de suporte ao D-Pad!
