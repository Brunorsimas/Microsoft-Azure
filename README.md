# Microsoft-Azure

## ☁️ O que é uma Máquina Virtual no Azure?

Uma máquina virtual (VM) no Azure permite executar um sistema operacional e aplicativos em uma infraestrutura de nuvem, sem precisar investir em hardware físico. É possível escolher o sistema operacional, configurar recursos e realizar o gerenciamento completo do ambiente.

---

## 📋 Pré-requisitos

- Conta ativa no [Microsoft Azure](https://azure.microsoft.com/pt-br/free/)  
  > 🆓 É possível utilizar uma conta gratuita com crédito inicial.

---

## 🛠️ Passo a Passo para Criar sua Máquina Virtual (via Portal)

### 1. Acesse o Portal do Azure
- Acesse: [https://portal.azure.com](https://portal.azure.com)

### 2. Localize o Serviço de Máquinas Virtuais
- No menu esquerdo, clique em **“Máquinas virtuais”**.  
- Ou use a barra de pesquisa no topo digitando **"Máquinas virtuais"**.

### 3. Crie uma Nova Máquina Virtual
- Clique em **“+ Criar”** e selecione **“Máquina virtual”**.

### 4. Preencha as Informações Básicas
- **Assinatura:** Selecione sua assinatura ativa.  
- **Grupo de Recursos:** Crie um novo ou selecione um existente.  
- **Nome da Máquina Virtual:** Defina um nome único.  
- **Região:** Escolha a localização (ex.: East US, Brazil South).  
- **Disponibilidade:** (Opcional) Se deseja alta disponibilidade.  
- **Imagem:** Selecione o sistema operacional (ex.: Windows Server 2022, Windows 10, etc.).  
- **Tamanho:** Clique em **“Alterar tamanho”** para escolher a configuração de CPU/RAM.  
- **Usuário e Senha:** Configure credenciais de acesso.

### 5. Configure as Regras de Porta
- Permitir acesso remoto via **RDP (porta 3389)**.  
- Se necessário, habilite outras portas (HTTP, HTTPS, etc.).

### 6. Configurações Avançadas (Opcional)
- **Discos:** Escolha entre SSD, HDD ou Premium SSD.  
- **Rede:** Configure rede virtual, sub-rede, IP público e grupo de segurança.  
- **Gerenciamento:** Configure backup, monitoramento e identidade.  
- **Tags:** Adicione tags para organização e gerenciamento de custos.

### 7. Validação e Criação
- Clique em **“Revisar + criar”**.  
- Valide as configurações.  
- Clique em **“Criar”** para iniciar a implantação da VM.

---

## 💻 Acessando a Máquina Virtual

Após a implantação:

1. No painel da VM, clique em **“Conectar”**.  
2. Selecione **“RDP”** (Área de Trabalho Remota).  
3. Baixe o arquivo `.rdp` e abra em seu computador.  
4. Insira o **usuário e senha** configurados durante a criação.

---

## 🛑 Gerenciando Custos

- Para evitar cobranças, **pare** ou **exclua** a VM quando não estiver em uso:  
  - No painel da VM, clique em **“Parar”** para desligar temporariamente.  
  - Ou clique em **“Excluir”** para remover completamente a VM e os recursos associados.

---

## 📚 Referências

- [Documentação Oficial — Azure Virtual Machines](https://learn.microsoft.com/pt-br/azure/virtual-machines/)  
- [Guia Rápido — Criar VM no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)  
- [Portal do Azure](https://portal.azure.com)
  
