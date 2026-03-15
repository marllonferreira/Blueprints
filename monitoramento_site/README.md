# Monitoramento Inteligente de Site (Ping)

Este Blueprint permite monitorar a disponibilidade de um site ou dispositivo IP de forma inteligente, evitando notificações desnecessárias por quedas momentâneas de rede.

## 🚀 Funcionalidades
- **Intervalo Personalizado:** Configure checagens a cada 6h, 12h ou o intervalo que preferir (via Time Pattern).
- **Lógica de Reteste:** Se a primeira checagem falhar, o sistema aguarda 2 minutos e tenta novamente. Ele faz isso até 3 vezes antes de considerar o site oficialmente "Offline".
- **Notificação Flexível:** Permite definir o título, a mensagem e para qual dispositivo a notificação será enviada.

## 📋 Requisitos
1. Ter a integração [Ping (ICMP)](https://www.home-assistant.io/integrations/ping) configurada no Home Assistant.
2. **Importante:** Nas configurações da integração Ping, desative a opção "Ativar atualizações automáticas" para que este Blueprint controle o momento exato do ping.

## 🛠️ Instalação
Clique no botão abaixo para importar este Blueprint para sua instância do Home Assistant:

[![Importar Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/marllonferreira/Blueprints/blob/main/monitoramento_site/monitoramento_site_inteligente.yaml)
---
*Nota: Certifique-se de que o caminho no link acima (`monitoramento_site/blueprint.yaml`) corresponde exatamente à estrutura de pastas que você criar no seu GitHub.*