# :checkered_flag: PicBox

Um serviço de armazenamento de imagens online. Usuários podem criar contas para armazenar imagens. Imagens armazenadas podem ser compartilhadas através de links. As imagens possuem títulos, e imagens compartilhadas através de links podem vir acompanhadas de caixas de comentários, caso o usuário que as compartilhou habilite essa função.

## :technologist: Membros da equipe

495915 - Augusto Vasconcellos. Ciências da Computação.

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

Usuário logado: tem acesso à sua própria galeria de imagens. Pode adicionar e remover imagens. Pode criar links para compartilhar imagens na galeria com outros usuários logados ou não-logados. Pode comentar em caixas de comentários em imagens compartilhadas.

Usuário não-logado: pode acessar imagens dentro do serviço através de links de compartilhamento gerados por usuários logados.

Administrador: caso uma imagem compartilhada por um usuário logado seja reportada como inapropriada por usuários logados ou não-logados, o administrador é notificado e pode, dependendo do seu julgamento, removê-la do site e, em casos piores, remover o usuário que as postou. O administrador pode também remover comentários dentro das caixas de comentários.

## :spiral_calendar: Entidades ou tabelas do sistema

Imagem: contém a string do título, um autor, uma lista de comentários, e a imagem em sí.

Comentário: contém a string do texto e um autor.

Report: contém a string da razão do report e a imagem sendo reportada.

## :triangular_flag_on_post:	 Principais funcionalidades da aplicação

Armazenar imagens: o usuário logado pode armazenar suas imagens em sua conta no site. Imagens podem ser adicionadas ou removidas da conta.

Compartilhar imagens: o usuário logado pode gerar links para que certas imagens armazenadas em sua conta possam ser acessadas por usuários logados e não-logados.

Reportar imagens: usuários logados e não logados podem enviar um report para os administradores, notificando-os sobre imagens inapropriadas compartilhadas por outros usuários.

----

:warning::warning::warning: As informações a seguir devem ser enviadas juntamente com a versão final do projeto. :warning::warning::warning:


----

## :desktop_computer: Tecnologias e frameworks utilizados

**Frontend:**

Lista as tecnologias, frameworks e bibliotecas utilizados.

**Backend:**

Lista as tecnologias, frameworks e bibliotecas utilizados.


## :shipit: Operações implementadas para cada entidade da aplicação


| Entidade| Criação | Leitura | Atualização | Remoção |
| --- | --- | --- | --- | --- |
| Entidade 1 | X |  X  |  | X |
| Entidade 2 | X |    |  X | X |
| Entidade 3 | X |    |  |  |

> Lembre-se que é necessário implementar o CRUD de pelo menos duas entidades.

## :neckbeard: Rotas da API REST utilizadas

| Método HTTP | URL |
| --- | --- |
| GET | api/entidade1/|
| POST | api/entidade2 |
