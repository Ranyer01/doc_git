# Documentação Git
Documentação do git para ajudar nos comandos

Se atentar no nome do arquivo: ver pontuação, letras.

### Ele inicia o arquivo ".git/" para controlar a pasta.
````
git test
````
### Ele é responsável por validar os arquivos modificados dentro do projeto.
````
git status
````
##### - Vermelho: mostra os arquivos modificados ou excluídos.
##### - Verde: mostra os arquivos que foram adicionados pelo "git add", que estão preparados para serem comitados.

### Ele é resposável por colocar o arquivo modificado em uma área segura.
````
git add
````
### Ele é resposável por criar uma nova versão do projeto com as referências do criador.
````
git commit -m "<texto_da_modificação>"
````

### Cria uma nova branch/ramo
````
git checkout -b <nome _da_branch>
````
### Ele adiciona branch atual de outra branch.
````
git checkout <nome _da_branch>
````
### Baixa o projeto do repositório.
````
git clone <url>: 
````
### Ele envia alteração para o repositório.
````
git push
````
### Ele puxa as alterações do repositório.
````
git pull
````
### ERROS:
````
git config --global user.name "<seu_nome>"
````
````
git config --global user.email "<seu_email>"
````
##### Apagando as credenciais, gerenciamento de credenciais.
````
Erro 403
````
