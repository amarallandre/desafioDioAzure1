Laboratório Azure - Máquina Virtual ☁️

Este repositório contém anotações, resumos e dicas sobre o processo de criação e configuração de uma Máquina Virtual (VM) utilizando a plataforma Microsoft Azure.

📚 Objetivos do Laboratório

Praticar a criação e configuração de uma VM na Azure;

Documentar de forma clara o processo realizado;

Criando uma conta gratuita na Azure

🆓 Criando uma Conta Gratuita na Azure

Acesse:

Vá até o site oficial: https://azure.microsoft.com/pt-br/free

Clique em "Comece gratuitamente"

Você será redirecionado para fazer login com sua conta Microsoft (ou criar uma, se ainda não tiver).

Verificação de identidade:

Será necessário informar um número de telefone válido e um cartão de crédito (apenas para verificação, sem cobranças).

Plano Gratuito:
Você recebe R$ 1.000 em créditos por 30 dias

Após isso, pode continuar com os serviços gratuitos incluídos, como uso limitado de VMs, banco de dados, armazenamento, etc.

Plano para Estudantes (opcional):
Se for estudante, acesse: https://azure.microsoft.com/pt-br/free/students/

Não precisa de cartão de crédito.



Oferece créditos e serviços gratuitos voltados ao aprendizado.

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

