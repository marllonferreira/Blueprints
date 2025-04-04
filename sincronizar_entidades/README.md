## Blueprint: Sincronizar entidades


### **Descrição:**

Este blueprint para Home Assistant Automation permite sincronizar o estado ligado/desligado entre duas entidades. Ao alterar o estado de uma das entidades (para "on" ou "off"), a outra entidade será automaticamente alterada para o mesmo estado.

**Entradas:**

O blueprint solicita a seleção de duas entidades para sincronização:

* **Primeira entidade:** Selecione a primeira entidade (switch, luz ou script).
* **Segunda entidade:** Selecione a segunda entidade (switch, luz ou script).

**Como Funciona:**

A automação é acionada quando o estado de qualquer uma das entidades selecionadas muda para "on" ou "off". Uma condição verifica se os estados das duas entidades são diferentes e se a mudança de estado não foi iniciada por esta própria automação (para evitar loops infinitos). Se essas condições forem atendidas, a automação altera o estado da outra entidade para corresponder ao estado da entidade que disparou a automação.


# **Como Usar:**

### Metodo 1

Importando Blueprints para o Home Assistant
Se você vir este emblema de importação, clique nele:

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmarllonferreira%2FBlueprints%2Fblob%2Fmain%2Fsincronizar_entidades%2Fsincronizar_entidades.yaml)

### Metodo 2

Para importar um Blueprint manualmente:

Visite o tópico do blueprint que você deseja importar
Copie o URL da barra de endereço do navegador
Vá para Home Assistant → Configuração → Automações e cenas → Blueprints e clique no botão “Importar Blueprint” no canto inferior direito.
Cole a URL do tópico do blueprint e clique em “Visualizar Blueprint”
Clique em “Importar Blueprint”