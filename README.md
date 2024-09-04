# Portify - Um gerenciador de portfólios!

### documentação da nossa API: https://github.com/Kenzie-Academy-Brasil-Developers/kenzie-portify-api
#### AVISO: A api ela é desligada automaticamente todas vezes que não está sendo usada. A cada primeiro acesso, pode demorar alguns segundos para funcionar, até que a api seja ligada novamente.
### link do figma: https://www.figma.com/design/jbjSioh3CEosnxplORzCxm/portify?node-id=0-1&node-type=CANVAS

## Instruções
Vamos começar com as rotas públicas, aquelas que não exigem autenticação:

### Tela de cadastro:
--> Os usuários devem ser capazes de se cadastrar, fornecendo os seguintes campos: nome, e-mail, senha e confirmação de senha.

--> Ao cadastrar um usuário, a senha precisa atender aos seguintes requisitos:

- Deve conter pelo menos uma letra maiúscula;
- Deve conter pelo menos uma letra minúscula;
- Deve conter pelo menos um caractere especial;
- Deve conter pelo menos um número;
- Deve ter no mínimo 8 caracteres.
- A aplicação deve validar se a senha digitada coincide com a confirmação de senha.

### Tela de login:
--> Deve ser possível fazer login informando o e-mail e a senha cadastrados.

--> Após o login ser concluído com sucesso, o usuário deve ser redirecionado para a tela de administração.
### Tela autenticada:
--> Na tela autenticada, o usuário deve ser capaz de
- Criar e editar seu próprio perfil;
- Criar, editar e deletar seus projetos.

## Requisitos técnicos
Embora seja um projeto que oferece mais liberdade em relação ao conteúdo, é importante atender a alguns requisitos técnicos.
É necessário que o sistema faça uso da ContextAPI.
Além disso, é permitido utilizar uma biblioteca de estilo/componente (caso seja consentimento do grupo), como tailwind, stitches, radix, chakra UI ou Styled-Components.
Gostaríamos de ressaltar que este projeto tem como objetivo o trabalho em grupo, mas também explorar novas tecnologias e, embora o uso do SASS seja permitido, seria bastante interessante ver o grupo se arriscando e experimentando outras bibliotecas mencionadas acima.
