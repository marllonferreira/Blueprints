# Blueprints



### Modelos de Blueprints 


Importando Blueprints para o Home Assistant
Se você vir este emblema de importação, clique nele:

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmarllonferreira%2FBlueprints%2Fblob%2Fmain%2Fmulti_click_button.yaml)

Para importar um Blueprint manualmente:

Visite o tópico do blueprint que você deseja importar
Copie o URL da barra de endereço do navegador
Vá para Home Assistant → Configuração → Automações e cenas → Blueprints e clique no botão “Importar Blueprint” no canto inferior direito.
Cole a URL do tópico do blueprint e clique em “Visualizar Blueprint”
Clique em “Importar Blueprint”



## Sumário

- [Botão Multi Clique](#Botão Multi Clique)
- [Instalação](#instalação)



## Projeto de Monitoramento de Nível de Caixa D'Água

This is a Brazilian project to monitor water tank level.

Este é um projeto que desenvolvi para monitorar o nível da caixa d'água do meu
prédio. Trata-se de um projeto particular, que está sendo divulgado para ajudar a
quem precisa de algo similar. Não pretendo prover suporte técnico, mas poderei
esclarecer algumas dúvidas. Aceitarei eventuais PRs, desde que sirvam para mim, a
fim de não modificar o projeto desenvolvido para o condomínio.

Eu vou manter esse projeto em português para o caso de outra pessoa necessitar
fazer manutenção no sistema do meu prédio (assim eu poderei viajar e até mesmo
me mudar).

### Botão Multi Clique

O projeto faz a medição da caixa d'água inferior (subsolo) e da caixa superior
(cobertura). Há 03 LEDs para cada caixa que indicam os volumes de água: 80%, 50%
e 30%. O circuito principal fica localizado na casa das bombas, montado em uma
caixa de projeto eletrônico, e possui 06 LEDs (03 para a caixa inferior e 03 para
a caixa superior). Uma outra caixa, localizada na portaria do prédio, possui 06
LEDs que indicam as mesmas condições e também um buzzer, que emite sons
diferentes para situações diferentes. Essa caixa da portaria também possui um
push button, utilizado para reiniciar remotamente o Arduino, caso seja
necessário. Em cada caixa d'água, há um sensor que mede a profundidade da água.

### instalação

O projeto faz a medição da caixa d'água inferior (subsolo) e da caixa superior
(cobertura). Há 03 LEDs para cada caixa que indicam os volumes de água: 80%, 50%
e 30%. O circuito principal fica localizado na casa das bombas, montado em uma
caixa de projeto eletrônico, e possui 06 LEDs (03 para a caixa inferior e 03 para
a caixa superior). Uma outra caixa, localizada na portaria do prédio, possui 06
LEDs que indicam as mesmas condições e também um buzzer, que emite sons
diferentes para situações diferentes. Essa caixa da portaria também possui um
push button, utilizado para reiniciar remotamente o Arduino, caso seja
necessário. Em cada caixa d'água, há um sensor que mede a profundidade da água.


