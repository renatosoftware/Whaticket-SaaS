# WhaTicket Saas</br>
Com Kanban e Modo Noturno</br>
Está é uma versão exclusiva licencas.digital by launcher, e conta com modo noturno e módulo kanban. </br>
Funcionando com Baileys 6.5.0 - Setembro de 2023 </br>
</br> Atualizado referencias para a bilioteca @WhiskeySockets/Baileys</br>
Modificado AnyWASocket, WALegacySocket, LegacyAuthenticationCreds</br>
Corrigio Bot repete Menu</br>

Atualizações Fontend:</br>
Adicionado Tema Escuro</br>
Adicionado Módulo Kanban

Adicionado conexões Insta e Facebook - Em Revisão (Biblioteca desatualizada 9/13, meta 16)
</br> Adicionado Lista de Tarefas (Função que usa o cache do navegador)

Tipo de Chatbot = Somente Texto <br> Removido as opções depreciadas, Listas e Botões.

Não é necessário estar com celular ativo e conectado a internet para receber mensagens.
Respostas Rápidas > OK </br>
Envio de mídia > OK </br>
Agendamento de mensagens > OK </br>
Importar contatos do telefone > OK </br>
Exportar lista de contatos .csv > OK </br>
Envio de campanhas > OK </br>
Download e Importação de Lista de Contatos em Campanhas > OK </br>
Criar contatos de campanha direto no painel > Não testado </br>
CallBack GerenciaNet via Insomnia > OK </br>
Midia no Chat > Não testado</br>
Escutar Audios > Não testado </br>
Localização Fixa > Não testado - Não funciona em tempo real, mesmo na api oficial</br>

Planos Futuros:</br>
Atualização de Material UI 4 para MUI 5</br>
Correção de Webhook Facebook (Messenger e Direct)</br>

Em Observação:</br>
Tickets de Admin são fechados automaticamente na avaliação</br>
(verificar se corrigiu) Tickets de usuários recebem a nota e só fecham e enviam disparo da mensagem de encerramento quando clica novamente em resolver.</br>
Ao modificar gerenciamento de horários limpe as configurações anteriores primeiro.

Personalizações:</br>

** Alterar Cor Primária: (#007aff)</br>
/frontend/src/config.json</br>
/frontend/src/App.js</br>
/frontend/src/layout/index.js
/frontend\src\pages\Chat\ChatMessages.js

** Cores do Chat Interno:</br>
frontend\src\pages\Chat\ChatList.js</br>

** Cores da Lista de Tarefas</br>
/frontend/src/pages/ToDoList/index.js

** Popover de Anuncios / Chat Interno </br>
/frontend/src/components/AnnouncementsPopover/index.js</br>
/frontend/src/pages/Chat/ChatPopover.js

** Logo e LogoLogin:</br>
/frontend/src/assets

** Icone e Favicon:</br>
/frontend/public

** Comando para rebuild, caminho absoluto /home/deploy/"nome"/
  
cd /frontend
npm run build

URL WEBHOOK META:

```bash
https://api.seudominio.com.br/webhook/fb
