# WaOC
Workflow automation OpenCode
--------------------

WaOC é um sistema que automatiza os processos no desenvolvimento de lojas OpenCode.

##Download:

O WaOC está disponivel em duas versões:

- [Ruby](https://github.com/WaOC/WaOC-Ruby)
- [Shell](https://github.com/WaOC/WaOC-Shell)

## Funções

Veja abaixo uma lista com todas as funções disponíveis, elas irão agilizar o processo de trabalho com o OpenCode.

#### **Install**
``` shell
  waoc install
```

- Instala a GEM do OpenCode e o Gulp, deixando o ambiente configurado rapidamente.

#### **Edit**
``` shell
  waoc edit {{STORE_ID}} {{API_KEY}} {{API_PASSWORD}} {{THEME_ID}}
```

- Edita uma loja. Com as informações que são passadas no comando, a loja é configurada e baixada em segundos.

#### **Work**
``` shell
  waoc work {{STORE_ID}}
```
- Inicia o OpenCode e o Gulp para a loja passada no comando, assim, rapidamente é possivel editar um tema.

#### **Stop**
``` shell
  waoc stop
```
- Para o OpenCode e o Gulp de todas as lojas.
