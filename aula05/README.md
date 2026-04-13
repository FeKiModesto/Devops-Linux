#  Aula 05 - Azure CLI (Prática)

Nesta aula foi realizada a prática de comandos do Azure CLI utilizando uma máquina virtual Linux.

O objetivo foi compreender como gerenciar recursos na nuvem através de linha de comando.

---

## Objetivo da aula

- Praticar o uso do Azure CLI
- Entender comandos básicos de gerenciamento de recursos
- Simular operações em ambiente cloud

---

##  Estrutura criada

- Pasta `aula05`
- Arquivo `comandos_azure.txt`

---

##  Comandos praticados

- az version
- az account show
- az group list -o table 
- az vm list -o table
- az resource list -o table 

---

## Exemplos de comandos Azure CLI

```bash
az group create --name rg-aula05 --location southafricanorth
az vm create --name vm-devops --image Ubuntu2204
az vm list
az resource list
