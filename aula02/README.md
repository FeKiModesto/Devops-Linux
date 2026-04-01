#  Aula 02 - Manipulação de arquivos e processos

Nesta aula foram realizados exercícios voltados à manipulação de arquivos, busca de informações e monitoramento de processos no Linux.

---

##  Estrutura criada

###  arquivos
- usuarios.txt
- dados_sistema.txt

###  logs
- acessos.log
- erros.log

###  backup
- cópia dos arquivos.txt

---

## Etapas realizadas

###  Criação de arquivos

### Inserção de dados
- echo "Usuario: Joao" > usuarios.txt
- echo "Erro: falha de conexão" > erros.log

###  Busca de informações
- grep "Maria" usuarios.txt
- grep "Erro" erros.log

####  Análise de dados
- wc -l usuarios.txt
- wc -w usuarios.txt

### Processos do sistema
- ps
- top

###  Backup de arquivos
- mkdir backup
- cp *.txt backup/

###  Visualização
- cat usuarios.txt
- tail erros.log

###  Comandos utilizados
- touch
- echo
- grep
- wc
- ps
- top
- cp
- cat
- tail

---

###  Objetivo da atividade
Praticar manipulação de arquivos, busca de informações e monitoramento de processos no ambiente Linux.

---

###  Autor

Felipe Kirschner Modesto

```bash
touch usuarios.txt acessos.log erros.log dados_sistema.txt
