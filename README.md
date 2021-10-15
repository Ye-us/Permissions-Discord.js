#### Permissions Discord.js.

```javascript
var permissions = new Map();

permissions.set(/CREATE_INSTANT_INVITE/g, 'Criar um Convite');
permissions.set(/KICK_MEMBERS/g, 'Expulsar Membros');
permissions.set(/BAN_MEMBERS/g, 'Banir Membros');
permissions.set(/ADMINISTRATOR/g, 'Administrador');
permissions.set(/MANAGE_CHANNELS/g, 'Gerenciar Canais');
permissions.set(/MANAGE_GUILD/g, 'Gerenciar Servidor');
permissions.set(/ADD_REACTIONS/g, 'Adicionar Reações');
permissions.set(/VIEW_AUDIT_LOG/g, 'Ver o Registro de Auditoria');
permissions.set(/PRIORITY_SPEAKER/g, 'Voz Prioritária');
permissions.set(/STREAM/g, 'Vídeo');
permissions.set(/VIEW_CHANNEL/g, 'Ver Canal');
permissions.set(/SEND_MESSAGES/g, 'Enviar Mensagens');
permissions.set(/SEND_TTS_MESSAGES/g, 'Enviar Mensagens de Voz');
permissions.set(/MANAGE_MESSAGES/g, 'Gerenciar Mensagens');
permissions.set(/EMBED_LINKS/g, 'Inserir Links');
permissions.set(/ATTACH_FILES/g, 'Anexar Arquivos');
permissions.set(/READ_MESSAGE_HISTORY/g, 'Ver Histórico de Mensagens');
permissions.set(/MENTION_EVERYONE/g, 'Mencionar Everyone');
permissions.set(/USE_EXTERNAL_EMOJIS/g, 'Usar Emojis Externos');
permissions.set(/VIEW_GUILD_INSIGHTS/g, 'Ver Análises do Servidor');
permissions.set(/CONNECT/g, 'Conectar');
permissions.set(/SPEAK/g, 'Falar');
permissions.set(/MUTE_MEMBERS/g, 'Silenciar Membros');
permissions.set(/DEAFEN_MEMBERS/g, 'Ensurdecer Membros');
permissions.set(/MOVE_MEMBERS/g, 'Mover Membros');
permissions.set(/CHANGE_NICKNAME/g, 'Alterar Apelido');
permissions.set(/MANAGE_NICKNAMES/g, 'Gerenciar Apelidos');
permissions.set(/MANAGE_ROLES/g, 'Gerenciar Cargos');
permissions.set(/MANAGE_WEBHOOKS/g, 'Gerenciar WebHooks');
permissions.set(/MANAGE_EMOJIS/g, 'Gerenciar Emojis');

module.exports = permissions;
```
