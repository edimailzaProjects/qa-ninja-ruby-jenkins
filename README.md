# qa-ninja-ruby-jenkins
Repositório do projeto Kabug com Cucumber Capybara e Ruby - em 27/03/2021

##Como executar o projeto

*Importante ter o ruby instalado (versão 2.7.2 ou superior)

### Instalar o Bundler
'
gem install bundler
'

### Instalar as dependências do Ruby (projeto)
'
bundle install
'

### Executar localmente (minha máquina)
'
bundle exec cucumber
'

### Executar no servidor de CI gerando (gerando reports JSON)
'
bundle exec cucumber -p ci
'
