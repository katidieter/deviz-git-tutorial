# DEVIZ TUTORIAL 
 
## Git na prática

Fala Deviz, esse tutorial faz parte do material que preparamos com os princiapais comandos para acompanhar a série de vídeos [Deviz na prática sobre o Git e GitHub](https://www.youtube.com/watch?v=8T9joR3LMPg&t=1156s). Aqui você vai aprender como criar branches, fazer o seu primeiro commit, como clonar e atualizar o repositório, criar um pull request e fazer merge com o main.


## Instalando o GIT e Node

* [Link com download do Git](https://git-scm.com/downloads)
* [Link com download do NodeJs](https://nodejs.org/en/download/) - Sugerido para rodar a aplicação do tutorial mas não obrigatório para o entendimento do tutorial sobre Git.

## Principais comandos

### Clonar respositório

* Crie um pasta no seu computador local

* Através do seu terminal shell favorito execute o comando `git clone git@github.com:katidieter/deviz-git-tutorial.git`

Dica: você pode clonar repositórios utilizando uma conexão HTTPS, comumente utilizada para navegação web segura. Entretanto, quando trabalhamos com git executamos muitos comandos diretamente via shell script, então é altamente recomendado que façamos o clone utilizando a URL SSH. [Mas para isso você vai precisar adicionar uma chave SSH](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)


### Trabalhando com branches

* Para criar uma branch local `git branch nome_da_branch`

* Para navegar para outra branch `git checkout nome_da_branch`

* Para criar uma branch local e já navegar até ela `git checkout -b nome_da_branch`

### Adicionando/alterando arquivos

Todos os arquivos criados/alterados precisam ser selecionados para serem sincronizados com o repositório remoto. \n
Para isso nós adicionamos ele à uma área chamada de stage e somente então, poderá ser feito o commit com a descrição da alteração para depois realizar a sincronização de fato.

* Para adicionar todos os arquivos novos/alterados a zona de stage `git add .`, ou `git add caminho_do_arquivo` para adicionar um arquivo em específico.

* `git commit -m "descrição do commit"` para de fato dar o commit no repositório

Dica: para verificar qual a atual situação da sua branch local, execute `git status`

### Sincronizando o repositório

* Após o commit as alterações precisam ser enviadas ao repositório remoto: `git push`

* Para manter o seu repositório local atualizado com as alterações de outres colaboradores `git pull`


## Gran finale

Existem muitas outras funcionalidades do Git e do Github que podem ser exploradas para facilitar o trabalho colaborativo, porém estes comandos são os mais utilizados no dia-a-dia e já são uma baita mão na roda.

Pra quem quer conhecer um pouco mais, a gente recomenda dar uma olhada na [documentação do Git](https://git-scm.com/doc), pois qualquer dúvida que apareça pode ser respondida por lá na explicação.

**Não esqueçam de deixar o like e se inscrever no [canal do Youtube](https://www.youtube.com/channel/UCFO7Z4vLTosTutrK77zAaLg)**
