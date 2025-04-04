# Blueprints Home Assistant - PT-BR




Bem-vindo ao repositório de Blueprints para o Home Assistant em português do Brasil! Aqui você encontrará uma coleção de automações pré-configuradas para facilitar a sua vida com o Home Assistant.

**O que são Blueprints?**

Blueprints são modelos de automação e scripts que você pode importar facilmente para o seu Home Assistant. Eles permitem que você crie automações complexas com apenas alguns cliques, sem a necessidade de escrever código YAML.

**Como usar os Blueprints deste repositório:**

1.  **Navegue pelas pastas:** Os Blueprints estão organizados em pastas por categoria (por exemplo, `automações`, `notificações`, `segurança`, etc.) ou por tipo de dispositivo.
2.  **Escolha o Blueprint desejado:** Clique no arquivo `.yaml` do Blueprint que você quer usar.
3.  **Copie o conteúdo:** Clique no botão "Raw" para visualizar o conteúdo do arquivo e copie todo o código YAML.
4.  **Importe para o Home Assistant:**
    * No seu Home Assistant, vá para "Configurações" > "Automações e Cenas" > "Blueprints".
    * Clique no botão "+ Adicionar Blueprint".
    * Cole o código YAML copiado na janela.
    * Clique em "Salvar Blueprint".
5.  **Crie uma automação:** Depois de importar o Blueprint, você poderá criar uma nova automação baseada nele, configurando as entidades e opções desejadas.


### **Blueprints Disponiveis**
- Cada projeto possui sua própria pasta com os seguintes arquivos:
  - [Multiclique](./multi_click_button/README.md) : defini varias ações p/ um botão dependendo de quantos cliques rápidos você der nele.
  - [Paralelo virtual](./paralelo_virtual/README.md) : Controla simultaneamente um grupo de luzes/interruptores.
  - [sincronizar entidades](./sincronizar_entidades/README.md) : Mantém duas entidades (luz, interruptor ou script) com o mesmo estado (ligado/desligado).
