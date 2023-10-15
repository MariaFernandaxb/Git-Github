# Git-Github
Um pouco sobre Git e GitHub 

![kMCMR25Vh](https://github.com/Nandabdev/Git-Github/assets/132234392/48107e70-1d6b-4651-80a5-9f497b440678)

(Créditos img: Via Google)

# Um pouco sobre Git e GitHub: 


# Git 
 É um sistema de versionamento de código amplamente distribuído e adotado. 

Criado por Linus Torvalds em 2005, é usado para rastrear as alterações no código-fonte de um projeto de software ao longo do tempo.

Com o Git, os desenvolvedores podem trabalhar em seus próprios ramos (cópias separadas do código-fonte), mesclar suas alterações e controlar o histórico de todas as alterações.

O Git opera localmente em um computador, permitindo que os desenvolvedores façam commits, branches e merges sem depender de uma conexão com a Internet ou um servidor remoto.

# GitHub 
 É uma plataforma de hospedagem de código-fonte que utiliza o Git como sistema de controle de versão subjacente. 

Ele permite que os desenvolvedores armazenem, colaborem e compartilhem projetos de software publicamente ou de forma privada. Muito utilizada também como portfólio para programadores.

O GitHub fornece recursos adicionais, como controle de acesso, rastreamento de problemas, integração contínua e a capacidade de colaborar facilmente com outros desenvolvedores em um projeto.

Os desenvolvedores podem enviar (push) seus repositórios Git locais para o GitHub, tornando-o acessível a outros colaboradores e mantendo uma cópia de backup do projeto na nuvem.

## Resumo

Git é o sistema de controle de versão que permite rastrear e gerenciar as mudanças em um código-fonte, enquanto o GitHub é uma plataforma online que permite hospedar, colaborar e gerenciar projetos de software que usam o Git como sistema de controle de versão. Existem outras alternativas ao GitHub, como o GitLab e o Bitbucket, que oferecem funcionalidades semelhantes.

## Principais comandos e códigos : 

# Git 

 git init 
 ---
 Inicia um repositório. 

 git clone <link_do_repositorio_existente>
 ---
Clona um repositório já existente no GitHub

 git add <nome_do_arquivo> 
 ---
 Adicionar arquivos para serem rastreados 

 git commit -m "Mensagem de commit"
 ---
 Confirma as mudanças no repositório e permite
 uma mensagem descritiva.

 git checkout <nome_do_branch>
 ---
 Troca entre branchs ou restaura arquivos
 da área de trabalho

 git merge <nome_do_branch>
 ---
 Mescla informações de um branch e outro. 

 git push origin <nome_do_branch>
 ---
 Envia alterações para o repositório remoto (GitHub)

 git config --global user.name "Seu Nome"
 ---
 git config --global user.email "seu@email.com"
 ---
 Define configurações globais de usuário para o 
 Git (nome de usuário e email):

# GitHub

 - Para criar um novo repositório no GitHub é usado comando do GIT para subir(push) o arquivos.

 Passo a passo: 

 No seu GitHub clique em "NEW" para criar novo repositório. 

 - Coloque um nome pro seu repositório.
 - Pode usar o arquivo como README para adicionar uma longa descrição. 

Após vai aparacer os seguintes comandos: 
 

 git init 
 ---
 Inicia um repositório. 
 
 git add . 
 ---
 Adicionar o seu repositório. 
 ou 
 git add README.md  
 ---
 Adicionar o seu repositório ao README

 git commit -m "primeiro commit" 
 ---
 Confirma as mudanças no repositório e permite
 uma mensagem descritiva

 git branch -M main 
 --- 
 Equivalente ao tronco da sua árvore, ou seja,
  é a parte principal do seu projeto

  git remote add origin 
  ---
  https://github.com/SEUGITHUB/NOMEDABRANCH.git
  
  Adicionar um origin para o repositório 

 git push - sua origem principal
 ---
 Envia alterações para o repositório remoto (GitHub)
 



## Conclusão

- Estes são alguns dos comandos e ações mais comuns no Git e no GitHub. Existem muitos outros comandos e recursos disponíveis, dependendo das suas necessidades específicas de desenvolvimento e colaboração. Certifique-se de estar familiarizado com a documentação do Git e do GitHub para explorar todos os recursos.

  - documentação:
 
  https://git-scm.com/docs/git/pt_BR
  
  https://docs.github.com/pt
