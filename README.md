# APRENDENDO LÓGICA
## COM PYTHON

#### Listas

```PYTHON
# DECLARANDO UMA LISTA VAZIA
lista = []

# DECLARANDO UMA LISTA COM VALORES
lista = ['valor 1', 'valor 2', 'valor 3']

# ACESSANDO OS DADOS DA LISTA 1 A 1
print lista[0] # valor 1
print lista[2] # valor 3

# ACESSANDO PARTES DA LISTA
print lista[:1] # ['valor 1']
print lista[1:3] # ['valor 2', 'valor 3']

# ACESSANDO TODOS OS ELEMENTOS DA LISTA DINAMICAMENTE
for valor in lista:
    print valor 
# valor 1 
# valor 2 
# valor 3

# ADICIONANDO ELEMENTOS À LISTA
lista.append('novo valor')
print lista # ['valor 1', 'valor 2', 'valor 3', 'novo valor']

# ALTERANDO ELEMENTOS DA LISTA
lista[0] = 'outro valor'
print lista # ['outro valor', 'valor 2', 'valor 3', 'novo valor']

# REMOVENDO ELEMENTOS DA LISTA
lista.remove('novo valor') # novo valor
print lista ['outro valor', 'valor 2', 'valor 3']

# RECUPERAR A POSIÇÃO PARA UM DETERMINADO VALOR NA LISTA
lista.index('valor 2') # 1
lista.index('outro valor') # 0
```
> Mais sobre listas [neste site](http://www.devfuria.com.br/python/listas/)