# Comandos para o Git

## Criar novo Repositório
- git init 

## Verificar estados dos arquivos/diretórios
- git status

## Adicionar Arquivo/Diretório
### Adicionar um arquivo em específico
- git add meu_arquivo.txt
### Adicionar um diretório em específico
- git add meu_diretorio
### Adicionar todos os arquivos/diretórios
- git add .
### Adicionar um arquivo que esta listado no .gitignore (geral ou do repositório)
- git add -f arquivo_no_gitignore.txt

## Comitar arquivo/diretório
### Comitar um arquivo
- git commit meu_arquivo.txt
### Comitar vários arquivosComitar vários arquivos
- git commit meu_arquivo.txt meu_outro_arquivo.txt
### Comitar informando mensagem
- git commit meuarquivo.txt -m "minha mensagem de commit"

## Remover arquivo/diretório
### Remover Arquivo
- git rm meu_arquivo.txt
#### Remover diretório
- git rm -r diretorio
