# Pesquisa-Ts

# README.md
## O que é o README
Um arquivo README.md é um arquivo de texto formatado em Markdown, frequentemente usado para fornecer documentação e informações sobre um projeto de software, repositório de código, ou qualquer tipo de projeto que seja hospedado em um sistema de controle de versão como o Git. O README.md é frequentemente o primeiro arquivo que os usuários e desenvolvedores verão quando acessarem um repositório no GitHub, GitLab, Bitbucket ou qualquer outra plataforma semelhante.


# Comando git
## O que é?
O Git é um sistema de controle de versão distribuído amplamente utilizado para rastrear alterações em projetos de software. Ele permite que várias pessoas trabalhem em um projeto simultaneamente, mantendo um histórico completo de todas as alterações feitas ao longo do tempo.
Este documento fornece uma visão geral dos comandos Git mais comuns que você usará ao trabalhar com o Git.
## Configuração do Comando
Antes de começar a usar o Git, é importante configurá-lo com suas informações pessoais. Isso é necessário para que o Git saiba quem está fazendo as alterações em um repositório.
```sh
    git config --global user.name "Seu Nome"
    git config --global user.email "seu@email.com"
```
## Inicialização de um Repositório
Para começar a rastrear as alterações em um projeto, você pode inicializar um repositório Git em um diretório específico. Isso criará um repositório vazio onde você pode começar a adicionar seus arquivos.
```sh
    git init
```
## Clonagem de um Repositório
Se você deseja colaborar com um projeto existente, pode clonar um repositório Git para obter uma cópia local em sua máquina.
```sh
    git clone URL_do_Repositório
```
## Upload para GitHub
Para subir os arquivos para o GitHub basta usar os comandos:
- Source Control > Adicione os arquivos para a pasta Alterações Preparadas > Confirmar