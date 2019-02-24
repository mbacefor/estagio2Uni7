# Autenticação na Aplicação:

Essa funcionalidade é responsável pela autenticação e cadastro usuário.

### Cenários dessa funcionalidade:

+ Logar na Aplicação:
    - Nesse cenário o usuário previamente cadastrado loga na aplicação com seu login(email) e senha.
+ Cadastrar Novo Usuário
    - Nesse cenário o usuário ainda não esta cadastrado na aplicação e quer se cadastrar.
+ Validar e-mail usuário
    - Nesse cenário o usuário fez o seu primeiro cadastro ou alterou o e-mail, nesse caso precisa validar seu e-mail.
+ Editar Usuário
    - Esse cenário permite o usuário alterar os seus dados cadastrais e sua senha.

### Regras dessa funcionalidade:
+ Unicidade de e-mail
    - Não pode ter o mesmo email cadastrado para outro usuário.
+ Senha criptograda
    - A senha do usuário deve ser criptografada.
+ Tamanho da senha
    - O tamanho mínimo da senha deve ser 6 caracteres alfanuméricos
