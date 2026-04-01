#  Aula 01 - Comandos básicos Linux

Esta aula teve como objetivo praticar comandos básicos do sistema operacional Linux utilizando uma máquina virtual na Azure.

Foi desenvolvida uma simulação de sistema bancário para organizar dados de clientes, transações e logs.

---

##  Estrutura criada

Dentro da pasta `dimdim_bank`, foram criados os seguintes diretórios:

###  clientes
- cliente_001.txt
- cliente_002.txt
- cliente_003.txt

###  transacoes
- transacoes-jan.tsx
- transacoes-fev.tsx

###  logs
- sistema_dimdim.log
- acesso_usuarios.log
- transacoes_api.log
- erro_sistema.log

###  relatorios

###  backup

---

## Etapas realizadas no projeto

###  Criação da estrutura de diretórios

###  Criação de arquivos de clientes

- cd clientes
- touch cliente_001.txt cliente_002.txt cliente_003.txt

### Inserção de dados nos clientes

- echo "Cliente 1 - João" > cliente_001.txt
- echo "Cliente 2 - Maria" > cliente_002.txt
- echo "Cliente 3 - Pedro" > cliente_003.txt

###  Criação de arquivos de transações

- cd ../transacoes
- touch transacoes-jan.tsx transacoes-fev.tsx

###  Inserção de dados nas transações

- echo "Transferência João -> Maria" > transacoes-jan.tsx
- echo "Depósito Pedro" >> transacoes-jan.tsx

###  Criação dos logs

- cd ../logs
- touch sistema_dimdim.log acesso_usuarios.log transacoes_api.log erro_sistema.log

###  Visualização de arquivos

Exemplos de comandos utilizados para visualizar dados:

- cat cliente_001.txt
- tail transacoes-jan.tsx

---

###  Comandos utilizados

-mkdir
-cd
-ls
-pwd
-touch
-echo
-cat
-cp
-mv
-rm
-tail

---

###  Objetivo da atividade

Praticar a criação e organização de arquivos e diretórios no Linux, além de manipular dados via terminal.

### Autor

Felipe Kirschner Modesto
	
```bash
mkdir dimdim_bank
cd dimdim_bank
mkdir clientes transacoes logs relatorios backup
