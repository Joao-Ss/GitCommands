# GitCommands
Este repositório contém uma lista detalhada e organizada dos principais comandos do Git Bash, explicando suas funções de forma simplificada. <br>
Ideal para iniciantes e para quem deseja ter uma referência rápida sobre versionamento de código com Git. 

# ⚡ Comandos básicos:

```bash
## Iniciar um repositório Git na pasta atual.
git init

## Mostrar o diretório atual.
pwd

## Baixar um repositório remoto para o seu computador.
git clone <Link-Repositório>

## Mostrar o status dos arquivos no repositório.
git status

## Adicionar um arquivo específico para o controle do Git.
git add <arquivo>

## Adicionar todos os arquivos modificados ao controle do Git.
git add . 

## Salvar as mudanças com uma mensagem descritiva.
git commit -m "mensagem"
```

# 📤 Enviando e recebendo alterações:

```bash
## Enviar as mudanças para o repositório remoto.
git push origin <branch>

## Baixar as últimas alterações do repositório remoto.
git pull origin <branch>

## Definir a branch como padrão para push.
git push -u origin <branch>

## Baixar as atualizações do repositório remoto, mas sem aplicá-las.
git fetch
```

# 🔄 Trabalhando com branches:

```bash
## Listar as branches existentes.
git branch

## Criar uma nova branch.
git branch <nome>

## Mudar para a branch especificada.
git checkout <branch>

## Criar e muda para uma nova branch.
git checkout -b <branch>

## Juntar uma branch ao código atual.
git merge <branch>

## Deletar uma branch.
git branch -d <branch>

## Deletar uma branch, mesmo que não tenha sido mesclada.
git branch -D <branch>
```

# 🌍 Trabalhando com repositórios remotos

```bash
## Adicionar um repositório remoto.
git remote add origin <URL>

## Listar os repositórios remotos configurados.
git remote -v

## Remover um repositório remoto.
git remote remove origin
```