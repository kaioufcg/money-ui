# MoneyUi
Projeto front-end para aprendizagem do framework Angular.

Esse projeto foi gerado com [Angular CLI](https://github.com/angular/angular-cli) versão 8.3.2.
Configurado com o Angular routing e o formatador de estilo Sass.

## Servidor de desenvolvimento

Execute `ng serve` para iniciar o servidor de desenvolvimento. Navegue para `http://localhost:4200/`. A aplicação irá recarregar automaticamente se você alterar alguma coisa nos arquivos.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
## Extensões

#### Git Flow

Fluxo do git no projeto.

O projeto segue utilizando os nomes padrões das branchs.
Branch name for production releases is [master].
Branch name for "next release" development is [develop].

Para suporte das branchs, segue-se os prefixos de nomes padrões.
Branch prefixe name for feature branches is [feature/].
Branch prefixe name for bugfix branches is [bugfix/].
Branch prefixe name for release branches is [release/].
Branch prefixe name for hotfix branches is [hotfix/].
Branch prefixe name for support branches is [support/].

#### Criar uma nova funcionalidade utilize o comando abaixo.
git flow feature start name_feature

#### Gitflow e Pull Requests
Antes de fechar a feature, consulte seus colegas, depois de fazer pull request 
para a branch [develop], e os adicione como reviewers.
Se estiver tudo correto, faça o merge na branch [develop].
Remova a branch da feature.
Depois é só fazer checkout e pull da branch [develop] 
e fazer git branch -D nome_feature para remover a branch local.

Outra opção é, termine a implementação e os 'commits'.
Faça push para o repositório remoto, consulte seus colegas, depois de fazer pull request 
para a branch [develop], e os adicione como reviewers. Faça o merge na branch [develop]
e depois utilize o comando abaixo
git flow feature finish name_feature
Executado o comando você estará na 'branch' [develop]. 
Só que vai existir um commit do pull request. 

#### Criar uma nova release utilize o comando abaixo.
git flow release star name_release
Executado o comando você estará na nova branch 
baseada na branch [develop].

Terminado os ajustes e os 'commits', utilize o comando abaixo.
git flow release finish name_release
Executado o comando você estará na tela de merge.
Adicione uma mensagem e salve com :wq
Após isso, você vai cair em outra tela, a tela da mensagem da 'tag' (Nova versão da aplicação).
Adicione uma mensagem e salve com :wq
Executado os comandos, você vai estar na branch [master].

#### Criar uma 'branch' para correção de erro urgente em produção.
git flow hotfix start name_hotfix
Executado o comando você estará na nova branch 
baseada na branch [master].

Terminado a correção, utilize o comando abaixo.
git flow hotfix finish name_hotfix
Executado o comando a tela de merge com a brach [master] será apresentada.
Adicione uma mensagem e salve com :wq
Salvo, a tela da 'tag'(Nova versão da aplicação) será apresentada.
Adicione o nome para a tag e salve com :wq
Salvo, a tela de merge com a brach [develop] será apresentada.
Adicione uma mensagem e salve com :wq
Executado os comandos, você vai estar na branch [develop].





