# git clean
- vai remover permanentemente os arquivos não adicionados a um commit ou a staged area

## git clean <file> -n
- -n serve para ver o que irá fazer ou o que irá deletar nesse caso
### Ex 
git clean -f trash.txt -n
(resposta) Would be remove trash.txt


## git clean -f
- Irá forçar a remoção do arquivo (não rastreado) para sempre sem chance de recuperálo 

### Ex
- git clean -f trash.txt