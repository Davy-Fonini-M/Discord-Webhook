GitHub New File Notification

🔔 Notificação Automática de Novos Arquivos no GitHub

Este projeto automatiza notificações para o Discord, alertando toda vez que um novo arquivo é adicionado ao repositório do GitHub. A integração é feita por meio de um webhook do Discord, tornando a comunicação eficiente e instantânea.

🚀 Funcionalidades

Monitora automaticamente o repositório e detecta novos arquivos.
Envia notificações para um canal do Discord configurado com webhook.
Fácil de configurar e personalizar conforme a necessidade.
📋 Pré-requisitos

Para utilizar este projeto, você precisará de:

Webhook do Discord: Crie um webhook em um canal desejado no Discord.
Acesso ao repositório GitHub: Certifique-se de ter permissões adequadas.
🛠️ Configuração

Clone este repositório:
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
Configure o Webhook do Discord:
Atualize o arquivo de configuração com a URL do webhook.
Exemplo de configuração no arquivo .env:

DISCORD_WEBHOOK_URL=https://discord.com/api/webhooks/...
Execute o script:
python monitor.py  
⚙️ Como Funciona

O script verifica periodicamente o repositório em busca de novos arquivos. Caso encontre algum, ele envia uma mensagem no canal do Discord com detalhes sobre o novo arquivo adicionado.

🧩 Possíveis Personalizações

Filtros: Notificar apenas arquivos de determinados tipos (ex: .md, .png).
Formato da Notificação: Personalizar a mensagem enviada ao Discord.
Intervalo de Monitoramento: Ajustar o tempo entre as verificações.
🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

📜 Licença

Este projeto está licenciado sob a licença MIT.

🌐 Conecte-se

Se você gostou deste projeto, não se esqueça de deixar uma estrela ⭐ no repositório!
