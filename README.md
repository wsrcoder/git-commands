# git-commands
Reune informações de comandos e resolução de problemas relacionados ao GitHub


### 1- Substituir um usuário Git por outro no Windows <h2>

Caso já exista um usuario do github na maquina e é necessário substituir por outro e ao trocar você tem erros. Siga os seguintes passos:

* Abra o menu de pesquisas do windows e procure por 'Gerenciador de Crdenciais'

![excluir credenciais do github - 01](https://user-images.githubusercontent.com/105994806/170886929-00097839-259e-43a0-bb63-d5290033c8c3.jpg)

Escolha a opção 'Credencias Genéricas' e procure a correspondente ao GitHub

![excluir credenciais do github - 02](https://user-images.githubusercontent.com/105994806/170887008-4772fa3e-eab1-474c-a509-172101335985.jpg)

  
  Após a exclusão do usuário existente você deve redefinir as configurações de usuário do git:
  
  git config --global user.name "usuario"
  git config --global user.email "usuario@email.com"
