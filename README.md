Laboratório Azure - Máquina Virtual ☁️

Este repositório contém anotações, resumos e dicas sobre o processo de criação e configuração de uma Máquina Virtual (VM) utilizando a plataforma Microsoft Azure.

📚 Objetivos do Laboratório

Praticar a criação e configuração de uma VM na Azure;

Documentar de forma clara o processo realizado;

Utilizar o GitHub como ferramenta de apoio para compartilhar e versionar esse material técnico.

🛠️ Passo a Passo: Criando uma VM na Azure

1. Acesso à Azure

Link: https://portal.azure.com

É necessário ter uma conta da Microsoft (pode usar créditos educacionais se disponíveis).

2. Criar um novo recurso

Vá em "Recursos" > "Criar um recurso" > "Máquina Virtual".

3. Configurações básicas

Nome da VM: lab-vm

Região: Escolha a mais próxima (Ex: Brazil South)

Imagem: Ubuntu 20.04 LTS ou Windows Server

Tamanho: B1s (gratuito para contas elegíveis)

Usuário e senha/SSH: Crie um acesso seguro

4. Disco

Tipo SSD padrão

5. Rede

Criar nova rede virtual ou usar a padrão

Permitir portas necessárias (por exemplo: RDP para Windows, SSH para Linux)

6. Revisar + Criar

Verifique se tudo está correto e clique em "Criar"

💻 Acessando a VM

Linux: ssh usuario@ip_da_vm

Windows: Usar o cliente de RDP

🧠 Dicas Úteis

Use Resource Groups para organizar seus recursos;

Configure regras de firewall corretamente para acesso seguro;

Lembre-se de desligar ou excluir a VM após o uso para evitar cobranças;

Monitore sua VM usando Azure Monitor.

📝 Recursos e Anotações Adicionais

Documentação oficial da Azure - Máquinas Virtuais

Azure para Estudantes

Comandos úteis para Linux/Windows na VM
