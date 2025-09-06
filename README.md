# Criando uma VM no Azure

---

## 1. Acessar o Serviço de Máquinas Virtuais
Primeiro, acesse o **portal do Azure**.  
Na barra de pesquisa na parte superior, digite **"Máquinas virtuais"** e selecione o serviço correspondente nos resultados.

---

## 2. Iniciar a Criação de uma Nova VM
Na tela de **Máquinas Virtuais**, procure pelo botão **"Criar"** no canto superior esquerdo e clique nele.  
Em seguida, selecione **"Máquina virtual"** no menu suspenso para começar a configurar a sua nova VM.

---

## 3. Configuração Básica da VM
Nesta etapa, você vai definir as informações essenciais para a sua VM:

- **Assinatura**: Escolha a sua assinatura do Azure.  
- **Grupo de recursos**: Um grupo de recursos é um contêiner que organiza os recursos do Azure.  
  - Você pode selecionar um existente ou criar um novo.  
  - Para este exemplo, crie um novo chamado **VMTeste**.  
- **Nome da máquina virtual**: Dê um nome único, como **VMTestes**.  
- **Região**: Escolha a região onde a VM será hospedada.  
  - Boa prática: selecionar a região mais próxima para reduzir a latência.  
  - Exemplo: **Brasil Sul**.  
- **Opções de disponibilidade**: Para a maioria dos testes, deixe como **"Sem redundância de infraestrutura"**.  
- **Tipo de segurança**: Selecione **"Padrão"**.  
- **Imagem**: Escolha o sistema operacional da VM.  
  - Exemplos: Windows Server, Ubuntu, Red Hat.  
  - Neste guia: **Ubuntu Server 22.04 LTS**.  
- **Tamanho**: Define poder de processamento e memória.  
  - Para testes: **Standard B1s** (1 vCPU, 1 GiB RAM).  
- **Tipo de autenticação**: Escolha a forma de acesso.  
  - Recomendo **Senha** para começar.  
  - Defina um **usuário** e uma **senha** fáceis de lembrar.

---

## 4. Configurar Discos e Rede
Clique em **"Avançar: Discos >"** e depois em **"Avançar: Rede >"** para aceitar as configurações padrão, a menos que tenha necessidades específicas.  
Para uma VM de teste, as opções padrão geralmente funcionam bem.

---

## 5. Revisar e Criar
Na tela **"Revisar + criar"**, revise todas as configurações.  
O Azure fará a validação automática da configuração.  

Se estiver tudo certo, clique em **"Criar"**.  

O Azure levará alguns minutos para implantar a sua VM.  
Após a conclusão, você receberá uma notificação e poderá acessar a sua nova máquina virtual.

---
