# Testes


Aqui temos o protótipo do livro que deve conter o conteúdo da disciplina de testes ministrada pelo professor Marcelo d'Amorim com demos, atividades hands-on e tutorias

Este livro e construido com o suporte do [Jupyter Books](https://jupyterbook.org)

### Para contribuir

Faça o download do [repositório](https://github.com/edenalsant/book) e instale as dependências 

`pip3 install -r requirements.txt` 


#### Como este livro está organizado?
Alguns arquivos e diretóorios são responsáveis pela organização do livro, são eles:
- `_config.yml` contem informações sobre título, autores e logo
- `_toc.yml` e a tabela de conteúdo do livro (table of contents), nela está a estrutura de capítulos e seções
- `/capitulos/` contem os diretórios nomeados respectivamente com o número de cada capítulo
- `/capitulos/numero_do_capitulo` contem um arquivo `conteudo.md` que tem as informações iniciais do capítulo
- `/capitulos/numero_do_capitulo/secao` contem arquivos com conteúdo de cada seção

#### Como gerar arquivos html?
a pasta `_build` contem os arquivos responsáveis pela geração das páginas html. Para que as modificações sejam devidamente aplicadas, voce deve apagar a pasta `_build `e rodar os seguintes comandos, considerando que você esta no diretório do livro

```
cd ..
jupyter-book build book/
```

abrir o arquivo `index.html` para ter acesso a página atualizada

#### Como adicionar arquivos .ipynb?
acesse o `jupyter notebook`, depois das modificações inseridas, exporte o arquivo `.ipynb` e adicione dentro da seção desejada
