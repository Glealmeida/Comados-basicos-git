# Comandos básicos Git

### Para listar os arquivos que estão no diretório:

```
dir- Windows     ls-Linux
```

### Navegar entre as pastas:

```
cd
```

### Limpar tela:

```
cls -Windows   clear-Linux
```

### Criar pasta:

```
mkdir
```

### Criar arquivo:

```
echo
```

### Deletar diretório:

```
del/rmdir
```

### Criando um repositório local

#### No diretório ou pasta que deseja versionar:

```
git init
```

### Para ver o estado dos arquivos no Git:

```
git status
```

### Adicionando arquivos ao Git:

```
git add * (todos os arquivos de uma só vez) ou
```

```
git add nome_do_arquivo (adiciona um arquivo por vez)
```

### Depois de Adicionado o arquivo é preciso fazer o commit  para que o Git possa fazer as modificações:

```
git commit -m 'comentário sobre seus arquivos aqui'
```

### Atualizando commit de arquivo modificado:

```
git commit -am 'digite sua mensagem aqui'
```

### Ligando seu repositório local a sua nuvem:

```
git remote add origin link_para_o_repositório_do_seu_projeto
```

### Enviando as alterações:

* Pela Primeira vez:

  ```
  git push -u origin master
  ```

* Nas outras vezes, só precisa fazer:

```
git push
```

### Copiando um repositório:

```
git clone link_para_o_repositório_que_deseja_copiar
```

### 