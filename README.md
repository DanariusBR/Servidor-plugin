# 💻 Servidor Único - Plugin All-in-One

Este plugin foi desenvolvido para consolidar todos os principais sistemas de grandes redes (como MushMC ou KaizenMC) em um **único servidor** de Minecraft (1.8.8), maximizando a eficiência e simplificando o gerenciamento.



---

## ✨ Recursos e Funcionalidades

O plugin Servidor Único integra os seguintes módulos:

### 1. 🌐 Sistema de Lobby
* **Hub Central:** Um único ponto de encontro para todos os jogadores.
* **Seleção Rápida:** Um Compass (Bússola) para acesso rápido aos minigames através de uma GUI customizada.
* **Comando de Retorno:** Comando `/lobby` para voltar ao hub de qualquer lugar.

### 2. 🕹️ Minigames Integrados
Todos os jogos rodam simultaneamente e de forma isolada dentro do mesmo servidor, usando um sistema de Arena e Filas (Queue):
* **BedWars**
* **SkyWars**
* **TheBridge**
* **MurderMystery**

### 3. 👤 Perfil & Conta
* **Comando `/perfil` ou `/conta`:** Acesso a estatísticas (kills, wins, derrotas), configurações pessoais e cosméticos.
* **Economia Única:** Um sistema de coins (moedas) que é compartilhado entre todos os minigames.

### 4. 💎 Cosméticos e Personalização
Sistema avançado de personalização que pode ser gerenciado por meio da GUI do `/perfil`:
* **Cosméticos:** Suporte para Chapéus, Auras, Partículas (Trilhas) e Efeitos Especiais.
* **Tags de Chat:** Sistema customizável de prefixos no chat.
    > Exemplo: `/tag` mostra suas tags disponíveis: `&aSuas tags&f: &{cor}&f, &{cor}&f.`
* **Medalhas:** Exibição de conquistas especiais ao lado do nome.
    > Exemplo: `/medal` ou `/medalha` mostra: `&aSuas medalhas&f: &{cor}&f, &{cor}&f.`

### 5. ⚔️ Sistema de Clãs
* **Comando `/clan`:** Criação, convite, expulsão e gestão de membros.
* **Estatísticas do Clã:** Kills e Wins acumuladas pelo grupo.
* **Tag no Chat:** Exibição da tag do clã no chat e/ou Scoreboard.

---

## ⚙️ Especificações Técnicas

* **Versão do Minecraft:** **1.8.8**
* **Versão do Java:** **Java 8**
* **Plataforma Recomendada:** PaperSpigot ou Spigot 1.8.8.

## 🚀 Instalação

1.  Baixe o arquivo `ServidorUnico-v1.0.jar`.
2.  Coloque-o na pasta `plugins/` do seu servidor 1.8.8.
3.  Inicie e depois pare o servidor para que os arquivos de configuração sejam gerados (pasta `plugins/ServidorUnico`).
4.  Configure os mapas, mensagens e permissões nos arquivos `.yml`.
5.  Inicie o servidor e divirta-se!

## 📜 Comandos

| Comando | Descrição | Permissão Padrão |
| :--- | :--- | :--- |
| `/perfil` | Abre o menu de conta e personalização. | `servidor.player` |
| `/tag` | Abre o menu para selecionar tags. | `servidor.player` |
| `/medal` | Abre o menu para exibir medalhas. | `servidor.player` |
| `/clan [sub]` | Comandos principais para o gerenciamento de clãs. | `servidor.player` |
| `/setlobby` | Define o ponto de spawn principal do Lobby. | `servidor.admin` |
| `/servidorunico reload` | Recarrega as configurações do plugin. | `servidor.admin` |

---

