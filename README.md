# Testes


Aqui temos o prototipo do livro que deve conter o conteudo da disciplina de testes ministrada pelo professor Marcelo d'Amorim com demos, atividades hands-on e tutorias

Este livro e construido com o suporte do [Jupyter Books](https://jupyterbook.org)

### Para contribuir

Faca o download do repositorio e instale as dependencias 

`pip3 install -r requirements.txt` 


#### Como este livro esta organizado?
Alguns arquivos e diretorios sao responsaveis pela organizao do livro, sao eles:
- `_config.yml` contem informacoes sobre titulo, autores e logo
- `_toc.yml` e a tabela de conteudo dos livros (table of contents), nela esta a estrurua de capitulos e secoes
- `/capitulos/` contem os diretorios numeros respectivamente com cada capitulo
- `/capitulos/numero_do_capitulo` contem um arquivo `conteudo.md` que tem as informacoes iniciais do capitulo
- `/capitulos/numero_do_capitulo/secao` contem arquivos com conteudo de cada secao

#### Como gerar arquivos html?
Simplesmente rode o script `build_book` e abra o arquivo html no path indicado

```
./build_book
```

abrir o arquivo `index.html` para ter acesso a pagina atualizada

#### Como adicionar arquivos .ipynb?
acesse o `jupyter notebook`, depois das modificacoes inseridas, exporte o arquivo `.ipynb` e adicione dentro da secao desejada

