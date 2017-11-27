.. role:: strike
   :class: strike

Roadmap
#######

As listas de tarefas descritas nesta página estão desatualizadas.
Todas as tarefas, bugs, lançamentos agendados são agora acompanhados no github:

    https://github.com/croogo/croogo/milestones

2.0.x
-----

- :strike:`Totalmente adaptado à Plugin: O Croogo pode se tornar um conjunto de plugins e um aplicativo minimalista que simplesmente instala o plugin padrão definido para fácil instalação.` **(shama, real34, rchavik)**
- Adicionado namespaces
- PSR-0 a PSR-1 Compat
- Usa composer.json ao invés de Config/plugin.json para extenses
- Oferece uma API RESTful para o core, para permitir fácil integração com aplicações de terceiros (pode ser uma aplicação iPhone também)
- Permite administradores atualizar o Croogo pelo painel admin (HTTP download, ou basedo no Git?)
- :strike:`Granular ACL` **(rchavik)**
- [Plugin] Conteúdos: Node est caindo fora, criando um plugin Contents. 

1.5.2
-----
- Versão estável
- Atualizações da Documentação

1.5.1
-----
- :strike:`
- :strike:`Ordenação e apresentação de ativação do plugin na lista de plugins`
- :strike:`Helpers para criar UI components, por exemplo: tabs, accordion, panels.  Principalmente para /admin` **(aymeric e real34 - occitech)**
- :strike:`Trocar Email Component por CakeEmail e mover para o models`
- :strike:`Mover as funcionalidades de NodesController para o model`

1.5.0
-----

- Plugin download/finder via shell (o CPM - uma ideia de gerenciador de pacotes)
- :strike:`Tema padrão: usar Twitter Bootstrap` (tema padrão não será alterado)
- :strike:`Tema Admin: usar Twitter Bootstrap aqui também?` **(aymeric and real34 - occitech)**
- Indicador de Preview de nodes, mostrar nodes plublicados que tem a flag preview setada pelo admin.
- :strike:`Definir InnoDb como storage engine padrão para o mysql`
- :strike:`Migration plugin (cakedc) pode ser utilizado para instalação, e plugins. Criar e atualizar as tabelas entre versões, configurar os dados padrão/básicos [http://croogo.lighthouseapp.com/projects/32818/tickets/258]` **(aymeric and real34 - occitech)**
- :strike:`Tornar o File Manager um plugin, adicionar maior segurança às pastas` **(shama)**
- :strike:`Tornar o Blocks um plugin` **(shama)**
- :strike:`Tornar o Taxonomy um plugin` **(shama)**
- :strike:`Mover a funcionalidade CommentsController::add() para a model`
- :strike:`Mover a funcionalidade AttachmentsController::admin_add para a model`
- :strike:`Mover funcionalidades do CroogoComponent para uma Lib`
- :strike:`Tornar o User um plugin` **(rchavik)**
- Permitir a integração de Autenticação de terceiros, por exemplo: twitter oauth, facebook, ldap,
- :strike:`Trocar Config/settings.yml por Config/settings.json, remover spyc do Vendor` **(rchavik)**
