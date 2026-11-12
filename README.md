# Xui Naxx · Atualizações

Canal público das melhorias da interface Xui Naxx em português brasileiro.

O pacote inclui o tema azul, os ajustes de navegação e reprodução, o importador com categorias e URL, a tradução e a associação automática de canais ao EPG.

Uma instalação NAXX com o atualizador configurado consulta `latest.json`, confere o tamanho e o SHA-256 do pacote e de cada arquivo e aplica os arquivos com backup. O endereço do pacote no manifesto é fixado no commit que o publicou, para que o download corresponda à versão anunciada.

Este canal contém a atualização da interface. O núcleo XUI, as credenciais, os bancos de dados e os instaladores de cada instalação ficam sob responsabilidade de seus mantenedores.

## Arquivos do canal

- `latest.json`: versão disponível, data de publicação, endereço imutável do pacote e hashes de integridade.
- `naxx-frontend.zip`: arquivos personalizados da atualização, dentro de `payload/`.

No painel com o atualizador já instalado, abra **Atualizações** para verificar a versão e acompanhar o resultado. A ativação inicial do serviço de atualização é feita localmente pelo administrador da instalação.

## Edição 1.14.2

Inclui nove paletas do menu superior, seleção de todo o catálogo nos buquês, organização simplificada de canais, filmes, séries e rádios e ajustes de português.

O manifesto identifica esta edição com `version: "1.14.2"` e `release_version: "1.14.2"`. O ZIP contém exatamente 19 arquivos próprios, validados por tamanho e SHA-256. A base compatível continua sendo XUI 1.5.12.

Os arquivos de terceiros mantêm seus termos e direitos.
