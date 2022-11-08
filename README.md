# cartao
 
> Projeto para trabalhar com HTML e CSS de forma inicial. O objetivo é criar um cartão virtual cartão com as informações de contato. referencia https://linktr.ee/s/discover/share-content/


todo arquivo html deve ter o nome .html, exemplo:
index.html

HTML - Hyper Text Markup Language

### HTML ---> conteúdo
```
<destacado>TEXTO</destacado>
<comando></comando>
<comando> --> <tag>

***ALT + SHIFT + F** --> Organiza o código automaticamente

h1, h2, h3, h4, h5, h6, são titulos

<p></p> --> paragrafo
<br> --> quebrar linha
<img srf="foto.jpg"> ---> imagem
<a href="https://sp.senac.br">Senac</a> --> Link
```

CSS ---> ESTILO/FORMATAÇÃO
JS ----> INTERAÇÃO

<!DOCTYPE html>   é a versao do html
<html lang="en">  é o idioma "pt-br"
<head>  é o nome la nas abas
    <meta charset="UTF-8"> é o conjunto alfabético pra pagina 
    <meta http-equiv="X-UA-Compatible" content="IE=edge">       é a configuração de compatibilidade do internet explorer para o edge
    <meta name="viewport" content="width=, initial-scale=1.0">  é a escala adaptada para despositivos como celular etc
    <title>Document</title>
</head>
<body>
    <h1>Francesco C. Lanzoni</h1>
    <h2>Desenvolvedor</h2>
    <h3></h3>

</body>
</html>

## Criando o CSS
> CSS -> Cascading Style sheet (Folha de estilo em cascata). O CSS é o modo pelo qual iremos formatar (estilizar) o nosso conteúdo (HTML).

Existem formas de estilizar o conteúdo:

1. inline - formatação é feita diretamente no elemento HTML
2. na página - a formatação é feita dentro de uma seção `<style>`
3. **arquivo externo** - criamos um arquivo exclusivo para formatação (.CSS)

A escolha do elemento HTML que será formatado, se dá através de seletores. Seletores são criados à partir de 3 possibilidades: Tag, classe(.) e identificação (ID) é #

Por exemplo: imagine que queremos modificar o fundo do site para a cor laranja e a cor da letra para amarelo, podemos montar um seletor da seguinte forma:
```css
body{
    background-color: orange;
    color: yellow;
}
```
Explicação:
- body --> seletor (onde será formatado)
- backgorund-color --> propriedade (o que será formatado)
- orange --> valor (como será formatado)

Design:
- tipografia
- cores
- grid
- espaçamento
- gestalt
- contraste
<a href="https://https://www.youtube.com/c/Chiefofdesign"></a> --> Link


