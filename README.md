# Xui Naxx · Atualizações

Canal público das melhorias da interface Xui Naxx em português brasileiro.

O pacote inclui o tema azul, os ajustes de navegação e reprodução, o importador com categorias e URL, a tradução e a associação automática de canais ao EPG.

Uma instalação NAXX com o atualizador configurado consulta `latest.json`, confere o tamanho e o SHA-256 do pacote e de cada arquivo e aplica os arquivos com backup. O endereço do pacote no manifesto é fixado no commit que o publicou, para que o download corresponda à versão anunciada.

Este canal contém a atualização da interface. O núcleo XUI, as credenciais, os bancos de dados e os instaladores de cada instalação ficam sob responsabilidade de seus mantenedores.

## Arquivos do canal

- `latest.json`: versão disponível, data de publicação, endereço imutável do pacote e hashes de integridade.
- `naxx-frontend.zip`: arquivos personalizados da atualização, dentro de `payload/`.

No painel com o atualizador já instalado, abra **Atualizações** para verificar a versão e acompanhar o resultado. A ativação inicial do serviço de atualização é feita localmente pelo administrador da instalação.

## Edição 1.5.14.1

Inclui **NAXX Automático**, que analisa as fontes de um canal cadastrado e escolhe um modo de baixa latência compatível ao salvar. A ativação é por canal; atualizar o pacote preserva as configurações existentes. Consulte [uso e limites](https://github.com/victorbrum33/Xui-Naxx/blob/main/NAXX-AUTOMATICO.md).

O manifesto mantém `version: "1.5.14"` para serviços legados e identifica a edição completa em `release_version: "1.5.14.1"`. Serviços novos reconhecem os quatro componentes; o hash permite que os antigos instalem o mesmo pacote.

Os arquivos de terceiros mantêm seus termos e direitos. A edição NAXX 1.5.14.1 identifica as melhorias da interface e usa a base compatível XUI 1.5.12.
