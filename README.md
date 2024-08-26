# Guia de Configuração do Git

Este guia fornece instruções passo a passo para configurar o Git em diferentes sistemas operacionais e ferramentas. Ele cobre configurações para Windows, Linux, GitHub Desktop e outras formas de configuração.

## Índice

1. [Configuração do Git no Windows](#configuração-do-git-no-windows)
2. [Configuração do Git no Linux](#configuração-do-git-no-linux)
3. [Configuração do GitHub Desktop](#configuração-do-github-desktop)
4. [Configuração do Git na Linha de Comando do GitHub](#configuração-do-git-na-linha-de-comando-do-github)
5. [Referências](#referências)

## Configuração do Git no Windows

### 1. Instalar o Git

1. **Baixe o Git**: Acesse [o site oficial do Git](https://git-scm.com/download/win) e baixe o instalador para Windows.
2. **Execute o Instalador**: Clique duas vezes no arquivo baixado para iniciar a instalação.
3. **Siga as Instruções**: Aceite as configurações padrão ou ajuste conforme necessário. Certifique-se de que a opção para adicionar o Git ao PATH esteja selecionada.

### 2. Configurar o Git

Abra o Git Bash (instalado com o Git) e configure seu nome e e-mail:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```
### 2. Configurar o Git

```bash
git config --global --list
```

### Para distribuições baseadas em Red Hat (como Fedora), use:

```bash
sudo dnf install git
```

# Guia de Configuração do Git

Este guia fornece instruções passo a passo para configurar o Git em diferentes sistemas operacionais e ferramentas. Ele cobre configurações para Windows, Linux, GitHub Desktop e outras formas de configuração.

## Índice

1. [Configuração do Git no Windows](#configuração-do-git-no-windows)
2. [Configuração do Git no Linux](#configuração-do-git-no-linux)
3. [Configuração do GitHub Desktop](#configuração-do-github-desktop)
4. [Configuração do Git na Linha de Comando do GitHub](#configuração-do-git-na-linha-de-comando-do-github)
5. [Referências](#referências)

## Configuração do Git no Windows

### 1. Instalar o Git

1. **Baixe o Git**: Acesse [o site oficial do Git](https://git-scm.com/download/win) e baixe o instalador para Windows.
2. **Execute o Instalador**: Clique duas vezes no arquivo baixado para iniciar a instalação.
3. **Siga as Instruções**: Aceite as configurações padrão ou ajuste conforme necessário. Certifique-se de que a opção para adicionar o Git ao PATH esteja selecionada.

### 2. Configurar o Git

Abra o Git Bash (instalado com o Git) e configure seu nome e e-mail:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
