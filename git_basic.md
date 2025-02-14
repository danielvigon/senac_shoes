`git config --global user.name "Seu Nome"` -> inclui a credencial do próprio nome
`git config --global user.email "seu_email@example.com"` -> inclui a credencial do próprio e-mail
`git init` -> inicializa o repositório local
`git status` -> Exibe se o arquivo projeto está adicionado ao repositório (cor vermelha = arquivo ou pasta fora do repositório local).
`git add nome_arquivo` -> Adiciona o arquivo ao repositório local.
`git add .` -> Adiciona todos arquivos criados ou alterados ao repositório local.
`git branch -M main` -> Altera o nome da brach pricipal de master para main.
`git commit -m "Mensagem de atualização"` -> Cria um commit para realizar um novo versionamento.
`git log` -> Lista todos commits realizados.
`git log --oneline --graph --decorate` -> Forma compacta para exibir os commits.
`git remote add origin https://github.com/danielvigon/senac_shoes.git` -> Sincroniza os dois repositórios (local e remoto).
`git push -u origin main` -> Envia as informações do repositório local para o repositório remoto.