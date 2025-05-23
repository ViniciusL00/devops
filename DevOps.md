# 🚀 Revisão de Aula: Introdução a DevOps

## O que você vai aprender

### 1. 🤝 Compreender a abordagem DevOps
- Entender a filosofia que une Desenvolvimento (Dev) e Operações (Ops)
- Focar em integração contínua, entrega contínua e colaboração entre times
- Automatizar para acelerar entregas e aumentar qualidade

### 2. 🐧 Explorar o Linux
- Conhecer comandos básicos do terminal
- Navegar pelo sistema de arquivos
- Gerenciar permissões e usuários
- Entender processos e gerenciamento de serviços

### 3. 🤖 Automatizar Processos com ShellScript
- Escrever scripts para automatizar tarefas repetitivas
- Usar variáveis, loops e condicionais no Shell
- Manipular arquivos e comandos do sistema via script

### 4. 🌐 Instalar e Monitorar um Servidor Web
- Instalar servidores web (ex: Apache, Nginx)
- Configurar o servidor para servir páginas estáticas/dinâmicas
- Monitorar logs e status do servidor para garantir estabilidade

### 5. ⏰ Agendar Execução de Tarefas
- Usar `cron` para agendar scripts e comandos
- Configurar horários e frequência de execução
- Verificar histórico e status das tarefas agendadas

---

**Dica do dia:**  
DevOps não é só ferramentas, é mindset. Aprenda a pensar em automação, colaboração e feedback constante. Só assim você vai virar fera.

---

# 🧠 Revisão de Aula: Preparando o Ambiente DevOps

## ✅ O que aprendi

### 🖥️ 1. Instalar a Virtual Machine
- Baixei e instalei o **Oracle VirtualBox** (💾)
- Entendi como criar e gerenciar VMs

### 🐧 2. Baixar o Ubuntu Server LTS
- Baixei a imagem ISO do **Ubuntu Server LTS** 📥
- Pronto para simular ambientes reais de servidor

---

**Nota rápida:**  
Essa estrutura com VirtualBox + Ubuntu Server é a base pra testar comandos Linux, ShellScript e simular servidores reais. 🛠️

# 🧠 Revisão de Aula: Configurando Ambiente Linux Virtual

## ✅ O que aprendi

### 🐧 1. Baixar o Ubuntu Server 24.04.2 LTS
- Baixei a versão mais recente e estável do Ubuntu Server  
- Ideal para treinar comandos Linux e ambiente de servidor

### 🧰 2. Configurar o Oracle VirtualBox
- Ajustei as configurações da VM (RAM, disco, rede)  
- Aprendi a preparar o ambiente virtual para rodar o Linux

### 💻 3. Criar uma Máquina Virtual Linux
- Instalei o Ubuntu Server dentro da VM  
- Sistema operacional funcionando 100% de forma isolada

---

### 🧩 **Resumo**
Aprendi a **criar e configurar um ambiente Linux virtual** usando o VirtualBox + Ubuntu Server. Agora tenho uma base segura pra treinar sem medo de quebrar nada! 🔧🔥

---

# 🧠 Revisão de Aula: Usar Ubuntu no Windows 11 (sem VM)

## ✅ O que é WSL?
WSL (Windows Subsystem for Linux) permite rodar distribuições Linux como o Ubuntu **diretamente no Windows**, sem precisar de máquina virtual ou dual boot. É leve, rápido e nativo! ⚡🐧

---

## 🛠️ Como instalar o Ubuntu via PowerShell

### 1. 🚀 Ativar o WSL
Abra o **PowerShell como administrador** e digite:

```powershell
wsl --install
```

> Isso instala o WSL 2 e baixa o Ubuntu automaticamente. Caso peça pra reiniciar, faça isso.

### 2. 📥 Instalar o Ubuntu manualmente (caso precise)

Se quiser instalar outra versão específica:

```powershell
wsl --install -d Ubuntu
```

Você também pode escolher outra distro com:

```powershell
wsl --list --online
```

---

## 🐧 Usar o Ubuntu

Depois da instalação:

- Digite `wsl` ou `ubuntu` no menu Iniciar
- Use o terminal normalmente como em qualquer Linux
- Pode rodar comandos como `ls`, `cd`, `apt update`, `nano`, `bash`, etc.

---

## 💡 Vantagens do WSL

- Sem precisar de VM = menos peso na máquina 💨
- Integração com arquivos do Windows (`/mnt/c/Users/SeuNome`)
- Perfeito pra testar ShellScript, Git, Docker e ferramentas DevOps

---

# 🧠 Revisão Compacta: Distros Linux Mais Comuns

Conheça as distribuições Linux mais populares e suas principais características 👇

---

## 🧱 Debian
- 🔒 **Estável e confiável**: uma das distros mais antigas do mundo Linux
- 💻 Suporte a várias arquiteturas (servidores, desktops, embarcados)
- 🧰 Base para várias outras distros (inclusive o Ubuntu)

---

## 🟣 Ubuntu
- 🙌 **Fácil de usar**: ideal pra quem está começando no Linux
- 🧬 Derivado do Debian
- 💻 Versões para desktop, servidores e IoT
- 🔄 Atualizações regulares e vasto suporte da comunidade

---

## 🍃 Linux Mint
- 🖥️ Foco em notebooks e desktops
- 👵 Interface tradicional e amigável (ótimo pra quem vem do Windows)
- 🔧 Baseado no Ubuntu (herda estabilidade e compatibilidade)

---

## 🎩 Fedora
- 🧪 **Inovação com estabilidade**: foco em tecnologias mais recentes
- 💻 Usado em desktops, servidores, nuvem e IoT
- 🔁 Atualizações frequentes, ideal pra quem quer estar na vanguarda

---

### 📝 Resumo Final
Cada distro tem um foco:
- **Debian** = estabilidade
- **Ubuntu** = facilidade de uso
- **Mint** = usabilidade em desktop
- **Fedora** = inovação e tecnologias novas

---

# 📚 Revisão Geral: Fundamentos de Sistemas e Linux

## ✅ O que aprendi

### 💻 1. Papel do Sistema Operacional
- O **sistema operacional** é o cérebro entre o hardware e o usuário.
- Ele **gerencia os recursos** da máquina (CPU, memória, disco, dispositivos).
- Sem ele, o hardware seria só um monte de metal inútil. 🧠⚙️

---

### 🐧 2. Distribuições Linux
- Existem **várias distros** Linux, cada uma com um foco diferente.
- A escolha da distro depende do **caso de uso**:
  - Servidores? Vai de Debian ou Ubuntu Server.
  - Estudo e uso pessoal? Mint ou Ubuntu Desktop.
  - Gosta de novidade? Fedora tá na área!

---

### 🧪 3. Instalar SO em Máquina Virtual
- Com o **Oracle VirtualBox**, dá pra criar um ambiente isolado e seguro.
- Instalei o **Ubuntu Server** como exemplo.
- Ideal pra **testes, estudos e experimentações**, sem risco de ferrar o PC real. 🧯💻

---

### 🔐 4. Acesso remoto com SSH
- **SSH (Secure Shell)** permite acessar outro computador/servidor pela rede.
- Usado pra **administrar servidores** de forma segura.
- Comandos básicos:
  ```bash
  ssh usuario@ip_do_servidor
  ```
- Prático, rápido e criptografado. 🛡️🔌

---

### 📌 Resumo Final
- O que é um sistema operacional
- Que existem várias distros Linux com usos específicos
- Como criar um ambiente de testes com VM
- E como acessar servidores de verdade com SSH
