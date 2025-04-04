# Blueprint: Botão Multiclique


Este Blueprint para Home Assistant permite configurar ações que serão executadas com base no número de cliques em um botão (ou no número de vezes que um interruptor é ligado/desligado) dentro de um período de tempo definido.

## Funcionalidades Principais:

* **Ações Multiclique:** Defina diferentes ações para diferentes números de cliques em um único botão.
* **Suporte a Múltiplas Entidades:** Funciona com entidades dos tipos `button`, `input_button` e `switch`.
* **Contagem de Cliques em Interruptores:** Cada mudança de estado de um interruptor (ligar ou desligar) é contada como um clique.
* **Número de Cliques Configurável:** Defina o número exato de cliques necessários para acionar as ações (de 1 a 100).
* **Tempo Limite entre Cliques:** Configure o tempo máximo permitido entre cada clique consecutivo.
* **Condições de Ação Opcionais:** Adicione condições que precisam ser atendidas antes que as ações sejam executadas.
* **Ações Personalizáveis:** Defina as ações que serão executadas quando o número de cliques for atingido e as condições (se houver) forem verdadeiras.

## Parâmetros de Entrada:

* **`button_entity` (Entidade do Botão):**
    * Selecione a entidade do botão, interruptor ou botão virtual que você deseja usar.
    * Tipos de entidades suportados: `button`, `input_button`, `switch`.
* **`number_of_clicks` (Quantos cliques?):**
    * Defina o número de cliques necessários para que a ação seja executada.
    * Valor padrão: 2
    * Permite selecionar de 1 a 100 cliques usando um controle deslizante.
* **`time_between_clicks` (Tempo entre cliques):**
    * Defina o tempo máximo permitido entre dois cliques consecutivos.
    * Permite configurar a duração com precisão em milissegundos.
* **`action_conditions` (Condição de ação):**
    * (Opcional) Defina condições que devem ser verdadeiras antes que as ações sejam executadas.
* **`actions` (Ações):**
    * Defina as ações que serão executadas quando o botão for pressionado o número de vezes definido (e as condições forem atendidas).

## Como Funciona (Resumo):

1.  A automação é acionada por qualquer mudança de estado da entidade de botão selecionada.
2.  Ela então espera um número específico de cliques subsequentes dentro do intervalo de tempo definido.
3.  Se o número correto de cliques for detectado dentro do tempo limite, a automação verifica as condições de ação (se houver).
4.  Se as condições forem atendidas (ou não houver condições), as ações definidas pelo usuário são executadas.

## Exemplo de Uso:

Imagine que você tem um botão inteligente:

* **Um clique:** Acende a luz da sala com 30% de brilho.
* **Dois cliques rápidos:** Acende a luz da sala com 100% de brilho.
* **Três cliques rápidos:** Desliga a luz da sala.

Este Blueprint permite configurar essa lógica facilmente no seu Home Assistant.



### Botão_Multi_Clique

Importando Blueprints para o Home Assistant
Se você vir este emblema de importação, clique nele:


[![Para importar um blueprint diretamente, abra o seu Home Assistant e a janela de importação de Blueprints será aberta com o blueprint específico já preenchido, pronto para você salvar e usar.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmarllonferreira%2FBlueprints%2Fblob%2Fmain%2Fmulti_click_button%2Fmulti_click_button.yaml)

Para importar um Blueprint manualmente:

Visite o tópico do blueprint que você deseja importar
Copie o URL da barra de endereço do navegador
Vá para Home Assistant → Configuração → Automações e cenas → Blueprints e clique no botão “Importar Blueprint” no canto inferior direito.
Cole a URL do tópico do blueprint e clique em “Visualizar Blueprint”
Clique em “Importar Blueprint”
