# Automação de Inscrição em Vagas da NerdIn

Este script python tem o objetivo de auxiliar na candidatura em vagas de emprego disponiveis no site [NerdIn](https://nerdin.com.br/)

## Como Usar

### Dependências

Instale as dependências presentes no arquivo `.toml`

### Run

A utilização é bem simples... Basta ir no site acima citado e fazer uma pesquisa aplicando os filtros desejados, clique em `pesquisar` e copie o link do resultado da pesquisa.

Eis um exemplo do link quando a palavra pesquisada foi `python`.

https://nerdin.com.br/vagas?CodigoCidade=0&CodigoVaga=&PalavraChave=python&CodigoEmpresa=0

Esse link deve ser posto na variável `url` do notebook de nome `main`.

Em `basic_data` devem ser preenchido as informacoes pessoas para que o script preencha dentro de cada vaga.

Sempre que o formulario encontrar alguma resposta nao respondida ele ira pausar o programa.

Voce deve inserir o dado e pressionar enter no programa pra que ele continue.