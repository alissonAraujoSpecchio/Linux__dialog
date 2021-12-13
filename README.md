# Linux__dialog
How to use dialog application in linux



```
sudo apt install dialog
```

menu example:
```
dialog --menu "teste" 20 80 15 Teste1 Item1 Teste2 Item2 Teste3 Item3
```

Radio example:
```
dialog --radiolist 'Choose AGW Inteface' 20 80 15 Teste1 '' on Teste2 '' off --stdout
```
