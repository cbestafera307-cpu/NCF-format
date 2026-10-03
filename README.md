# NCF — Directory Name Content File

NCF é um formato de arquivo para representar diretórios, nomes de arquivos, conteúdos e extensões.

## Formato

Exemplo de uma linha NCF:

    "ncf-repo/","Test.txt","Test",".txt"

## Estrutura

| Campo | Descrição | Exemplo |
|---|---|---|
| Directory | Caminho do diretório | `ncf-repo/` |
| Name | Nome do arquivo | `Test.txt` |
| Content | Conteúdo do arquivo | `Test` |
| File | Extensão do arquivo | `.txt` |

## Exemplo

    "ncf-repo/","Test.txt","Olá, mundo!",".txt"
    "ncf-repo/","Main.c","#include <stdio.h>",".c"
    "ncf-repo/","index.html","<h1>Olá!</h1>",".html"

## Objetivo

O NCF foi criado para armazenar informações sobre diretórios e arquivos em um formato simples e legível.

## Especificações

- Extensão: `.ncf`
- Nome completo: Directory Name Content File
- Formato: Texto simples
- Campos: Directory, Name, Content e File

## Status

Em desenvolvimento.
