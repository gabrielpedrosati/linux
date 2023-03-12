# Comandos
## Gerenciamento de Usuários e Grupos
**useradd**
```
- adiciona ou cria novos usuários
- -m - cria o usuário com o diretório /home/
```
**passwd**
```
- modifica a senha das contas dos usuários
```
**usermod**
```
- altera as configurações da conta do sistema de um usuário
```
**groups**
```
- mostra os grupos aos quais o usuário da sessão está incluído
```
**groupadd**
```
- cria novo grupo
```
**sudo**
```
- permite executar tarefas como administrador
```

## Diretórios
**cd**
```
- Navegar entre diretórios
- cd ~ - navega para a /home do usuário
- cd .. - sobe um nível no diretório
- cd - - volta para o diretório anterior
```
**pwd**
```
- Mostra diretório atual
```
**mkdir**
```
- Cria um ou mais diretórios
```
**rmdir**
```
- Remove diretório vazio
```

## Arquivos
**ls**
```
- Lista documentos e diretórios
- ls -a - mostra arquivos/diretórios ocultos
- ls -lh - mostra tamanho dos arquivos em human readable formats, como MB, GB e TB
```
**cat**
```
- combina, lista e escreve em arquivos
```
**cp**
```
- copia arquivos/diretórios para outro local
- cp file.txt /home/files
- cp -R /home/files /home/src - copia o diretório e subdiretórios
```
**mv**
```
- Move ou renomeia arquivos e diretórios
```
**rm**
```
- Apaga arquivos
- rm -r - apaga arquivos e diretórios recursivamente
```
**touch**
```
- cria um arquivo vazio
```
**grep**
```
- permite buscar padrões em textos usando expressões regulares
```

## Disco
**df**
```
- Mostra o espaço de disco utilizado
```
**du**
```
- mostra quanto de espaço um arquivo ou diretório ocupa
```