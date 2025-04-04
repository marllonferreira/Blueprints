# Paralelo Virtual

**Descrição:** Este Blueprint para Home Assistant permite criar um "paralelo virtual" entre múltiplos interruptores e/ou luzes. Ao ativar ou desativar qualquer um dos dispositivos selecionados, todos os outros dispositivos do grupo serão automaticamente sincronizados para o mesmo estado.

**Funcionalidade:**

* Quando o estado de um dos interruptores ou luzes selecionados mudar para `on`, todos os outros dispositivos do grupo também serão ligados.
* Da mesma forma, quando o estado de um dos dispositivos mudar para `off`, todos os outros serão desligados.
* Há um atraso de 2 segundos após a ação para permitir que os estados se estabilizem.

# **Como Usar:**

### Metodo 1

Importando Blueprints para o Home Assistant
Se você vir este emblema de importação, clique nele:

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmarllonferreira%2FBlueprints%2Fblob%2Fmain%2Fparalelo_virtual%2Fparalelo_virtual.yaml)

### Metodo 2

Para importar um Blueprint manualmente:

Visite o tópico do blueprint que você deseja importar
Copie o URL da barra de endereço do navegador
Vá para Home Assistant → Configuração → Automações e cenas → Blueprints e clique no botão “Importar Blueprint” no canto inferior direito.
Cole a URL do tópico do blueprint e clique em “Visualizar Blueprint”
Clique em “Importar Blueprint”