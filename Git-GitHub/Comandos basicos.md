# Comandos básicos para utilização do Git e Git Hub

## Configurar SSH e Token

- criar as senhas na pasta - ssh-keygen -t ed25519 -c [email](mailto:email)
- Navegar para a pasta que criou - cd /c/Users/Gabriel/.ssh/
- Verificar a chave - cat "chave.pub"
- Após colar lá no githup nas configurações
- Configurar a chave privada - eval $(ssh-agent -s)
- Seleciona a chave e coloca a senha - ssh-add "chave"

## Iniciando o Git e criando um commit

- Iniciar repositório git - git init
- Adicionar as alterações - git add
- Salvar as alterações - git commit -m “”
- Mostra qual o estado das alterações - git status
- Vincular ao repositório remoto - git remote add origin
- Empurrar para o repositório remoto - git push origin master
- Puxar as alterações do repositório remoto - git pull origin master