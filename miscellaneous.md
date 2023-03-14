# Miscellaneous

### User IDs
- UID 0 - root
- UID 1-99 - reservado para system users
- UID 100+ - standard users
- UID 65534 - reservado para o user nobody

### Rodar em background
Utiliza o & no final do comando
Ex: sleep 5 &

### Executar vários comandos ao mesmo tempo
Utilizar ;
Ex: mkdir teste/ ; cd teste/ ; touch file.txt

### Redirecionar
Utilizar > ou >>
| Comando | Descrição |
| --- | --- |
| cat file.txt > file2.txt | Redireciona a saída de file para file2 |
 cat file.txt >> file2.txt | Realiza um append no file2 |

 ### Executar um comando na saída de outro comando
 Utiliza o |
 Ex: cat file.txt | grep Hello