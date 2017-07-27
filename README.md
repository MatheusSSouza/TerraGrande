# TerraGrande  Unreal 4.15.3

### Para editar o projeto é preciso [instalar o git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)  
###### É possível __abrir__ o projeto fazendo o [download do zip](https://github.com/MatheusSSouza/TerraGrande/archive/master.zip)  
### Alterações feitas no master serão revertidas  
### Após a instalação é preciso identificar o usuário  
`git config --global user.email *Seu Usuario*`  
`git config --global user.email *Seu Email*`  
### Para evitar erros durante o upload do projeto, execute o seguinte comando  
`git config http.postBuffer 52428800000`  
  

### Copiar o projeto  
* Execute o gitBash ou CMD  
* Acesse o diretório onde deseja salvar o projeto  
`cd Desktop/`  
* Copie os arquivos do repositório online usando o comando  
`git clone https://github.com/MatheusSSouza/TerraGrande.git`  


### Criar uma versão  
##### É importante fazer uma versão do projeto para cada funcionalidade que será feita  

* Execute o gitBash ou CMD  
* Acesse a pasta do projeto  
`cd Desktop/TerraGrande`  
* Acesse a versão principal usando o comando  
`git checkout master`  
* Crie e acesse a versão *Teste_IA_Gorila* usando o comando  
`git checkout -b "Teste_IA_Gorila"`  
* Para mudar de versão use   
`git checkout *Nome da versão*`  
A versão principal se chama *master*  


### Salvar alterações  

* Execute o gitBash ou CMD  
* Acesse a pasta do projeto  
`cd Desktop/TerraGrande`  
* Abra a versão que foi editada  
`git checkout "Teste_IA_Gorila"`  
* Agrupe todas suas mudanças usado o comando  
`git add -A`  
* Descreva as alterações  
`git commit -m "Descasca a banana"`  


### Upload das alterações  

* Acesse a pasta do projeto  
`cd Desktop/TerraGrande`  
* Abra a versão que deseja mandar para o repositório online  
`git checkout "Teste_IA_Gorila"`  
* Se a versão nunca tiver sido carregada, crie ela no repositório online com o comando  
`git push --set-upstream origin "Teste_IA_Gorila"`  
* Se a versão já existe no repositório online, carregue as alterações com o comando  
`git push`  

  
### [Documentação completa](https://git-scm.com/docs)  
