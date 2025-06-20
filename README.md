# Automate-linux-desktop ⚙️
### Script que realiza automações para instalação de apps via APT, DNF, Flatpak e Gext  

*`install.sh` para baixar apps necessários*  
*`/dash-to-panel-matt-configs` para configurar a extensão dash-to-panel de forma manual ou automática*  

---

🔧 Funcionalidades do script

- Instala aplicativos e utilitários populares essenciais no dia a dia

- Prepara o sistema com ferramentas para melhorar a compatibilidade com jogos

- Adiciona extensão para abrir o menu de apps com a tecla Super

- Adiciona área de ícones para mostrar apps em segundo plano na barra superior

- Adiciona barra inferior centralizada com menu 'iniciar', opção de fixar apps favoritos e ocultação automática quando sobreposta

- Configura atalhos `Super + D` para minimizar e maximizar tudo e `Ctrl + Alt + T` para abrir terminal

<br>

### Menu com apps baixados após execução do script:  
![Menu com apps baixaddos após execução script](img/apps.png)  

<br>

### Pré-visualização ao passar o mouse (extensão):  
![Pré-visualização mínima ao passar o mouse (extensão)](img/mini-preview.png)  

<br>

### Barra se esconde ao ser sobreposta (extensão):  
![Barra se esconde ao ser sobreposta (extensão)](img/sobreposição-barra.png)  

<br>

### Baldur's gate 3 rodando no Fedora 42 com GE-Proton10-3 + Vulkan:  
![Baldur's gate 3 rodando no Fedora 42 com GE-Proton10-3 + Vulkan](img/BD3-Fedora.png)  

<br>

### Ícones de apps em segundo plano (extensão):  
![Ícones de apps em segundo plano (extensão)](img/apps-segundo-plano.png)  

<br>

---

### 📋 Lista de aplicativos com as descrições curtas para ajudar na identificação:  

---

### 🎮 Games & Runners

| Aplicativo                    | Descrição                                                                 |
|------------------------------|---------------------------------------------------------------------------|
| `ProtonPlus`                 | Interface gráfica para gerenciar e instalar versões do Proton personalizadas.|
| `ProtonUp-Qt`                | Gerenciador gráfico para instalar Proton GE, Wine GE e similares.         |
| `steam-rom-manager`          | Adiciona ROMs de consoles à Steam com arte personalizada.                 |
| `SGDBoop`                    | Aplica imagens personalizadas da SteamGridDB à sua biblioteca Steam.      |
| `Bottles`                    | Gerenciador de ambientes Wine para rodar apps e jogos de Windows no Linux.|
| `HeroicGamesLauncher`        | Launcher alternativo para Epic Games Store e GOG.                         |
| `Sunshine`                   | Host para streaming de jogos via Moonlight (como NVIDIA GameStream).      |
| `Lutris`                     | Plataforma que gerencia jogos de várias fontes (Steam, Windows, emuladores)|

---

### 🧰 Utilitários & Sistema

| Aplicativo                    | Descrição                                                                 |
|------------------------------|---------------------------------------------------------------------------|
| `ExtensionManager`           | Interface gráfica para gerenciar extensões do GNOME.                      |
| `Flatseal`                   | Gerenciador de permissões de apps Flatpak.                                |
| `LibreMenuEditor`            | Editor de menus de aplicativos do sistema.                                |
| `Fragments`                  | Cliente de torrent simples e moderno.                                     |
| `Boxes`                      | Aplicativo de máquinas virtuais do GNOME.                                 |
| `LocalSend`                  | Envia arquivos entre dispositivos na mesma rede local.                    |
| `ranger`                     | Gerenciador de arquivos no terminal com navegação em árvore.              |
| `speedtest-cli`              | Ferramenta de linha de comando para testar a velocidade da internet.      |
| `btop`                       | Monitor de sistema interativo com visual moderno no terminal.             |
| `gnome-tweaks`               | Ferramenta para ajustar configurações avançadas do GNOME.                 |
| `gnome-extensions-cli`       | Gerencia extensões do GNOME via terminal.                                 |
| `start-overlay-in-application-view` | Extensão para transformar tecla Super de workspaces para menu de apps.|
| `msttcore-fonts-installer`   | Instala fontes TrueType da Microsoft (como Arial e Times).                |
| `Google Chrome`              | Navegador web popular do Google                                           |
| `SaveDesktop`                | Faz backup e restaura o layout do desktop, painéis e personalizações.     |
| `Brave`                      | Navegador rápido, com foco em privacidade e bloqueio de anúncios.         |
| `Librewolf`                  | Navegador focado em privacidade baseado no firefox                        |
| `Thunderbird`                | Cliente de e-mails completo, com suporte a múltiplas contas e calendário. |
| `Cryptomator`                | Criptografia de arquivos locais para manter no dispositivo ou enviar para nuvem.|
| `PowerISO`                   | Manipulação de arquivos ISO, criação e extração de imagens de disco.      |
| `qBittorrent`                | Cliente de torrent leve e sem anúncios, com interface simples.            |
| `clipboard-indicator`        | Extensão que adiciona um gerenciador de clipboard na bandeja (tray)       |
| `Birdtray`                   | Extensão para deixar cliente de e-mails Thunderbird minimizado em 2 plano |
| `Gedit`                      | Editor de texto simples - estilo bloco de notas                           |

---

### 🎨 Edição de Imagem

| Aplicativo                    | Descrição                                                                 |
|------------------------------|---------------------------------------------------------------------------|
| `GIMP`                       | Editor de imagens avançado, similar ao Photoshop.                         |
| `Krita`                      | Aplicativo para pintura digital e ilustração.                             |
| `Inkscape`                   | Editor de gráficos vetoriais para logotipos, ilustrações etc              |

---

### 📺 Mídia

| Aplicativo                    | Descrição                                                                 |
|------------------------------|---------------------------------------------------------------------------|
| `Celluloid`                  | Reprodutor de vídeo baseado em MPV.                                       |
| `TubeConverter`              | Baixa vídeos ou áudios do YouTube e similares.                            |
| `OBS Studio`                 | Gravação de tela e transmissões ao vivo.                                  |
| `Spotify`                    | Cliente de música via streaming.                                          |
| `Discord`                    | Chat de voz/texto para comunidades e jogos.                               |
| `Zapzap`                     | Cliente moderno e leve para WhatsApp Web.                                 |

---

### 💻 Desenvolvimento

| Aplicativo                    | Descrição                                                                 |
|------------------------------|---------------------------------------------------------------------------|
| `Visual Studio Code`         | Editor de código (para desenvolvimento em geral).                         |
| `Docker`                     | Plataforma para criação e gerenciamento de containers.                    |
| `Docker Compose`             | Ferramenta para definir e gerenciar multi-containers com Docker.          |

---

### 📌 Observações

A maioria os aplicativos listados acima foram instalados via Flathub:  
```bash
flatpak install flathub <nome-do-aplicativo>
```

### 🎮 Rodar jogos da Steam (Windows) no Linux:
Para jogar títulos da Steam disponíveis apenas para Windows (ou macOS) no Linux, use o ProtonUp-Qt ou ProtonPlus para baixar o GE-Proton na versão mais atual (recomandado)  
Depois, na Steam, vá até o jogo desejado → clique na engrenagem → Propriedades → Compatibilidade → marque a opção para forçar compatibilidade e escolha o GE-Proton instalado.


