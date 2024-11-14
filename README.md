# lex
FERRAMENTA DE ANÁLISE LÉXICA
> Copyright (c) 2024, Augusto Damasceno.  
> All rights reserved.   
> SPDX-License-Identifier: BSD-2-Clause  
>
> Contact  
> [augustodamasceno@protonmail.com](mailto:augustodamasceno@protonmail.com)


# Abstract

Este repositório é uma adaptação do laboratório 14 do material do professor 
Judson Santiago ([JudsonSS](https://github.com/JudsonSS)) 
disponível em https://github.com/JudsonSS/Compiladores/tree/2e1b81ba859e18e938ea149d1cef2edea04dde36/Labs/Lab14/Sample.
A modificação inclui:
* palavra-chave while
* operadores relacionais para serem os mesmo de C++
* Permitir que o caractere sublinhado em qualquer parte de um identificador
* Incluir um padrão para o token STRING. O padrão consiste em um sinal de aspas
("), qualquer cadeia de caracteres e aspas no final. Porém, se o sinal de aspas
aparecer na cadeia, ele tera que ser precedido por uma barra invertida (\) e,
similarmente, uma barra invertida na cadeia precisa ser representada por duas
barras. O valor léxico e a cadeia sem as aspas e sem as barras usadas como
caracteres especiais.

# Utilização

## Compile

```bash
make
```

## Livre Utilização

```bash
make
```

## Redirecione input de um arquivo

```bash
./sample < test.txt
```

## Apresentação

* https://youtu.be/sJgc_fba3tE

# Licença

A licença do repositório base, fornecido pelo professor Judson Santiago, é a MIT License. 
Para este repositório modificado, foi adotada a licença BSD 2-Clause, que é compatível com a licença MIT. 
Essa compatibilidade permite o uso e a redistribuição do código original em projetos sob ambas as licenças, 
mantendo a liberdade para uso, modificação e redistribuição com algumas condições, 
principalmente em relação à atribuição e isenção de responsabilidade.
