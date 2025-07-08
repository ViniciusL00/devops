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
