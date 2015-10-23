# WaOC
Workflow automatizado para OpenCode
--------------------

**WaOC** é um sistema que automatiza os processos no **desenvolvimento** de lojas **OpenCode**.

##Download:

O WaOC está disponivel em duas versões:

- [Ruby](https://github.com/WaOC/WaOC-Ruby)
- [Shell](https://github.com/WaOC/WaOC-Shell)

## Funções

Veja abaixo uma lista com todas as funções disponíveis, elas irão agilizar o processo de trabalho com o OpenCode.

### **Install**
- Instala a GEM do OpenCode e o Gulp, deixando o ambiente configurado rapidamente.
``` shell
  waoc install
```

### **Edit**
- Edita uma loja. Com as informações que são passadas no comando, a loja é configurada e baixada em segundos.
``` shell
  waoc edit {{STORE_ID}} {{API_KEY}} {{API_PASSWORD}} {{THEME_ID}}
```

### **Work**
- Inicia o OpenCode e o Gulp para a loja passada no comando, assim, rapidamente é possivel editar um tema.
``` shell
  waoc work {{STORE_ID}}
```

### **Stop**
- Para o OpenCode e o Gulp de todas as lojas.
``` shell
  waoc stop
```
