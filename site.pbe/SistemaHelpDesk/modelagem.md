Sistema Help Desk

Usuário
-id_usuario
-nome
-email
-senha

Técnico
-id_tecnico
-nome
-email
-senha
-especialidade

Chamado
-id_chamado
-titulo
-descricao
-categoria
-data_abertura
-id_usuario
-id_tecnico

Relacionamento 
-Um usuário pode abrir vários chamados.
-Um técnico pode atender vários chamados.
-Cada chamado pertence a um usuário e pode ser atribuído a um técnico.