# 🚀 Módulo 1: Introdução a DevOps

## 🤝 1. A Filosofia DevOps

- Une **Desenvolvimento (Dev)** e **Operações (Ops)** em uma única mentalidade.
- Prioriza:
  - **Integração Contínua (CI)**
  - **Entrega Contínua (CD)**
  - **Colaboração constante entre os times**
- Automatiza processos para **acelerar entregas** e **reduzir erros**.
- Visa melhorar a **qualidade, velocidade e confiabilidade** do software. 🏗️💡

---

## 🐧 2. Primeiros Passos com Linux

- Aprendi comandos essenciais do terminal:
  - `ls`, `cd`, `pwd`, `cp`, `mv`, `rm`...
- Naveguei pelo **sistema de arquivos Linux** (estrutura em árvore).
- Gerenciei:
  - **Permissões de arquivos**
  - **Usuários e grupos**
  - **Processos ativos** com `ps`, `top`, `kill`, etc.
- Mexi com serviços e demonstrei noções básicas de administração. 👨‍💻🔧

---

## 🤖 3. ShellScript: Automatizando Tudo!

- Escrevi **scripts** para automatizar tarefas rotineiras.
- Usei:
  - **Variáveis**
  - **Condicionais (`if`, `else`)**
  - **Loops (`for`, `while`)**
- Manipulei arquivos e usei comandos dentro dos scripts.
- Ferramenta poderosa pra economizar tempo e padronizar processos. ⏱️📜

---

## 🌐 4. Instalar e Monitorar um Servidor Web

- Instalei servidores como **Apache** e **Nginx**.
- Configurei para servir:
  - **Páginas estáticas (HTML)**
  - **Páginas dinâmicas (com backend)**
- Monitorei:
  - **Logs** com `tail -f`
  - **Status** com `systemctl`, `service`, etc.
- Foquei em manter o servidor **estável e seguro**. 🔒🌍

---

## ⏰ 5. Agendamento com `cron`

- Usei o `crontab` para agendar tarefas automaticamente.
- Aprendi a sintaxe:
  ```bash
  * * * * * comando
  ```
- Defini **frequência e horários** das execuções.
- Consultei histórico e status das execuções programadas. 🕐📆

---

# 🧠 Preparando o Ambiente DevOps

## 🖥️ 1. Oracle VirtualBox

- Instalei o **VirtualBox** para rodar sistemas virtualizados.
- Entendi como criar, ligar, desligar e gerenciar VMs. 🖲️💽

## 🐧 2. Ubuntu Server LTS

- Baixei a **ISO oficial do Ubuntu Server LTS**.
- Ideal para simular **ambientes reais de produção**.
- Seguro, estável e muito usado em servidores. 📡🛠️

---

## 🧩 Resumo

💡 **Base sólida pronta** pra brincar, testar e ferrar tudo sem medo! Ambiente virtualizado = liberdade total + aprendizado garantido.

---

# 🧠 Usando Linux no Windows com WSL

## ✅ O que é o WSL?

- **Windows Subsystem for Linux**: roda distros Linux **dentro do Windows**.
- Sem VM, sem dual boot. Leve, rápido e direto no terminal do Windows. ⚡

## 🛠️ Instalando o Ubuntu via PowerShell

```powershell
wsl --install
```

- Ativa o WSL 2 e instala Ubuntu.
- Pode escolher outras distros com:

```powershell
wsl --list --online
```

---

## 🐧 Usando o Ubuntu no WSL

- Acesse pelo menu Iniciar com `wsl` ou `ubuntu`.
- Roda comandos Linux normalmente: `ls`, `cd`, `nano`, `apt`, etc.
- Ambiente perfeito para DevOps, scripts, Git, Docker e mais. 💻🐚

---

## 💡 Vantagens do WSL

- Rápido e leve ⚙️
- Integra com os arquivos do Windows (`/mnt/c/...`)
- Ideal para testes e estudos sem VM.

---

# 🧠 Distros Linux Mais Comuns

## 🧱 Debian

- 🔐 Estável e confiável.
- Suporte a várias arquiteturas.
- Base para várias distros (ex: Ubuntu).

## 🟣 Ubuntu

- 👶 Fácil pra iniciantes.
- Baseado no Debian.
- Tem versão Desktop, Server, IoT.
- Amplo suporte da comunidade.

## 🍃 Linux Mint

- 🖥️ Foco em usabilidade desktop.
- Interface tradicional (ótima transição do Windows).
- Baseado no Ubuntu.

## 🎩 Fedora

- 🧪 Foco em inovação.
- Atualizações frequentes.
- Ideal pra quem curte o "estado-da-arte" do Linux.

---

### 📝 Comparativo Final

| Distro  | Foco Principal        |
|---------|------------------------|
| Debian  | Estabilidade 🧱        |
| Ubuntu  | Facilidade de uso 🟣   |
| Mint    | Usabilidade desktop 🍃 |
| Fedora  | Inovação 🎩            |

---

# 📚 Fundamentos de Sistemas e Linux

## 💻 1. O que é um Sistema Operacional?

- **Gerencia recursos**: memória, CPU, disco, dispositivos...
- Intermediário entre o **hardware** e o **usuário**.
- Sem ele, o PC seria só um peso de papel caro. 💀🧠

---

## 🐧 2. Conhecendo as Distros

- Cada distro tem um público/uso específico.
  - **Servidor**: Ubuntu Server, Debian
  - **Desktop**: Mint, Ubuntu Desktop
  - **Testes/novidades**: Fedora

---

## 🧪 3. Criando Máquinas Virtuais

- Usei o **VirtualBox** pra criar ambientes de teste.
- Instalei o **Ubuntu Server**.
- Ambiente isolado, ideal pra praticar e aprender sem medo. 🔬🧱

---

## 🔐 4. Acesso remoto com SSH

- **SSH (Secure Shell)**: login remoto seguro em servidores.
- Comando básico:

```bash
ssh usuario@ip_do_servidor
```

- Totalmente criptografado. Fundamental pra administração remota. 🔐🌐

---

## 📌 Resumo Final

✅ O que aprendi:
- O papel do sistema operacional
- As principais distros Linux
- Como configurar ambientes virtuais com segurança
- A usar SSH para gerenciar servidores remotamente

---

# 🐧 Módulo 2: Explorando o Linux Server

## 🔄 Verificando Atualizações

- O Linux não força atualizações como o Windows. Você escolhe o que atualizar! 🧠
- Para verificar atualizações disponíveis:
  ```bash
  sudo apt update
  ```
- Esse comando exige senha e mostra quais pacotes podem ser atualizados.
- Para ver quais são atualizáveis:
  ```bash
  apt list --upgradable
  ```

---

## 🛠️ Descobrindo Comandos com `help`

- Use `help` ou `comando --help` para ver como um comando funciona.
  ```bash
  ls --help
  ```
- Shell CLI executa apenas comandos seguros e pré-configurados no sistema.

---

## 📁 Navegando e Gerenciando Diretórios

### 📍 Onde estou?
```bash
pwd
```
- Exibe o caminho atual no sistema.

### 📂 Listar arquivos e ocultos:
```bash
ls      # lista arquivos
ls -a   # inclui arquivos ocultos (começam com ".")
```

### 📁 Criar novo diretório:
```bash
mkdir nome_do_diretorio
```

### 🚶 Navegar entre diretórios:
```bash
cd nome_do_diretorio    # entra na pasta
cd                      # volta pra home
```

### 🧠 Dica: use as setas ↑ ↓ para navegar pelos comandos anteriores.

---

## 📝 Criando e Manipulando Arquivos

### 🆕 Criar arquivos vazios:
```bash
touch nome.txt
```

### 🖊️ Adicionar conteúdo com `cat`:
```bash
cat > nome.txt
```
- Digite o conteúdo e finalize com `Ctrl + D`.

### 👀 Ver conteúdo do arquivo:
```bash
cat nome.txt
```

### 🔊 Usar `echo` para mensagens:
```bash
echo "Hello world"
```

### ➕ Adicionar com `echo`:
```bash
echo "Novo conteúdo" > nome.txt  # sobrescreve
```

---

## ✍️ Editor de Texto `nano`

- Editor nativo do Linux CLI.
- Instalar:
  ```bash
  sudo apt-get install nano
  ```

- Usar:
  ```bash
  nano nome_do_arquivo.txt
  ```

- Finalizar:
  - `Ctrl + X` para sair
  - `Y` para salvar
  - Digite o nome do arquivo

---

## 📦 Compactar e Mover Arquivos

### 📦 Compactar arquivos com `tar`:
```bash
tar -czf compactado.tar.gz arquivo1.txt arquivo2.txt
```

### 🚚 Mover com `mv`:
```bash
mv compactado.tar.gz /caminho/do/destino
```

### 🧹 Mover múltiplos arquivos compactando-os antes = mais agilidade!

---

## ❌ Deletar Arquivos e Diretórios

### 🗑️ Remover arquivos:
```bash
rm nome.txt
```

### 🗑️ Remover diretório vazio:
```bash
rmdir pasta_vazia
```

### 🧨 Remover diretório com conteúdo:
```bash
rm -r pasta_com_arquivos
```

> ⚠️ Use com cuidado! Arquivos excluídos **não vão pra lixeira**!

---

## 🌳 Estrutura de Diretórios Linux

- Sistema baseado em **estrutura hierárquica** (como uma árvore).
- Cada diretório/pasta organiza melhor os dados e logs.
- Facilita manutenção, acesso e segurança de aplicações.

---

# 🐚 Módulo 3: Shell Scripting no Linux

Este módulo ensina como **automatizar tarefas** no Linux utilizando **scripts em Bash**. Aprendemos a criar, editar, executar scripts, além de usar condicionais, variáveis, compactação e passagem de parâmetros.

---

## 🚀 Automatização com Scripts

### 🧠 O que é um script?
- Um **roteiro de comandos** que executa automaticamente tarefas no terminal
- Usa a linguagem **Bash**, comum no Linux

### 🛠️ Vantagem
- Automatiza processos repetitivos como backups
- Agiliza a rotina de administração de sistemas

---

## 📦 Criando Script de Backup

```bash
#!/bin/bash

diretorio_backup="/home/vinic/devops"
nome_arquivo="backup_$(date +%Y%m%d_%H%M%S).tar.gz"

tar -czf "$nome_arquivo" "$diretorio_backup"
echo "Backup concluído em $nome_arquivo"
```

### 💡 Etapas
1. `#!/bin/bash`: define o interpretador
2. Variáveis armazenam diretório e nome do backup
3. `tar -czf`: compacta os arquivos
4. `echo`: informa sucesso

### ✅ Execução
```bash
chmod +x backup.sh
bash backup.sh
```

---

## 🔁 Condicionais (if/elif/else)

### ✅ Sintaxe:
```bash
if [ condição ]; then
    comandos
elif [ outra condição ]; then
    comandos
else
    comandos
fi
```

### 🔍 Exemplos de Testes:

- Strings iguais: `[ "$a" = "$b" ]`
- Strings diferentes: `[ "$a" != "$b" ]`
- Números iguais: `[ "$a" -eq "$b" ]`
- Maior/Menor: `[ "$a" -gt "$b" ]`, `[ "$a" -lt "$b" ]`
- Arquivo existe: `[ -e "/caminho/arquivo" ]`

> ⚠️ Sempre use espaços entre colchetes e variáveis!

---

## 📂 Script para Compactar Arquivos com Parâmetros

### 🎯 Objetivo
Permitir que a pessoa usuária escolha:
- Nome do arquivo de saída
- Quais arquivos devem ser compactados

### 📜 Script:
```bash
#!/bin/bash

if [ "$#" -lt 2 ]; then
    echo "O programa, $0 requer nome do arquivo e arquivos a serem compactados"
    exit 1
fi

arquivo_saida="$1"
arquivos=("${@:2}")

tar -czf "$arquivo_saida" "${arquivos[@]}"
echo "Compactado com sucesso em $arquivo_saida"
```

### ⚙️ Execução
```bash
chmod +x compactador
./compactador saida.tar.gz /home/vinic/devops
```

---

## 📥 Passagem de Parâmetros

### 📌 Conceito
- Argumentos passados na execução do script
- `$1`, `$2`, ..., `$@`: representam os parâmetros

### 🧪 Exemplo:
```bash
#!/bin/bash

if [ $# -ne 2 ]; then
  echo "Erro! Nao foram fornecidos dois argumentos"
  exit 1
fi

arg1=$1
arg2=$2

echo "O primeiro argumento é: $arg1"
echo "O segundo argumento é: $arg2"
```

---

## 🧠 Resumo Final

✅ Automatizar tarefas com scripts Bash  
✅ Usar condicionais com `if`, `elif`, `else`  
✅ Passar parâmetros para tornar scripts reutilizáveis  
✅ Compactar arquivos usando `tar` via script  
✅ Organizar backups com timestamp automático

---

📌 **Dica prática:** sempre teste scripts em ambientes seguros antes de rodar em servidores de produção. Um erro num `rm -rf` pode ser catastrófico! ☠️💻