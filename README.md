<h1 align="center">Máquina Virtual Azure</h1>

## Criando a VM

Em `Máquinas virtuais` no Azure, podemos criar uma instância de VM, preenchendo:

- Nome da máquina virtual
- Região (região padrão recomendada)
- Opções de disponibilidade
- Tipo de segurança (tipo de segurança padrão recomendada)
- Imagem (Windows Server 2022 Datacenter: Azure Edition - x64 Gen2, [recomendada pela Microsoft](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal))

>[!NOTE]
>Caso queira [criar uma VM com várias zonas de disponibilidade](https://learn.microsoft.com/pt-br/azure/virtual-machines/create-portal-availability-zone), a Microsoft disponibiliza uma página dedicada só para isso.
><br>
>Isso irá depender da forma de disponibilidade da qual é desejada, dependendo das necessidades do usuário.

Agora precisamos de uma conta de administrador.

Em `Conta de administrador`, preenchemos:

- Username
- Senha
- Confirmação da senha

Agora temos que selecionar as portas de entrada da nossa VM.

Em `Regras de porta de entrada`, selecione:

- Portas de entrada pública: Permitir portas selecionadas
- Selecione a porta RDP (3389) e HTTP (80)

***

O restante das opções podem conter seus valores padrões, para finalizar, clique no botão "Examinar + criar".

>[!IMPORTANT]
>Depois de a máquina ser examinada, podemos ver as configurações da nossa VM.

Depois de validado, podemos criar a máquina.

# Documentações oficiais:
[Início Rápido: Criar uma máquina virtual do Windows no Portal do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)

[Criar máquinas virtuais em uma zona de disponibilidade usando o portal do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/create-portal-availability-zone)

[Quais são os requisitos de senha ao criar uma VM?](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/faq#quais-s-o-os-requisitos-de-senha-ao-criar-uma-vm-)
