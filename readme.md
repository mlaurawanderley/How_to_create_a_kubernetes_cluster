# How to create a kubernetes cluster
&nbsp;
#### Confira aqui algumas opções para subir um cluster kubernetes de maneira gratuita, com opções de serviços gerenciados ou localmente. 
&nbsp;
## Lista de opções gratuitas para serviços gerenciados do Kubernetes
&nbsp;
* **Google Cloud Platform (GKE)**
    
    **Descrição:** Crédito de $300 que pode ser usado por um período de 3 meses a partir da criação da conta. Não há restrição quanto aos recursos e ao número de nós para a criação de um cluster.
	
	**Requisitos:** Um cartão de crédito é necessário para se inscrever, mas você não será cobrado se o seu crédito acabar.
	
	**Link:** https://cloud.google.com/free/


* **Microsoft Azure (AKS)**

    **Descrição:** Crédito de $200 que pode ser usado por um período de 30 dias a partir da criação da conta. No entanto, o Azure Kubernetes Service é gratuito para cargas de trabalho de IA e ML que se enquadram na lista de recursos sempre gratuitos.
	
	**Requisitos:** Um cartão de crédito é necessário para se inscrever, mas você não será cobrado se o seu crédito acabar.
	
	**Link:** https://azure.microsoft.com/en-us/free/

* **IBM Cloud**

    **Descrição:** Cluster Kubernetes de nó de trabalhador único junto com registro de contêiner, como outros provedores de nuvem. Isso é mais que suficiente para um iniciante experimentar os conceitos do Kubernetes. O cluster gratuito expira após 30 dias.
    
    **Link:** https://www.ibm.com/cloud/free/

* **Linode (LKE)**

    **Descrição:** Crédito de LKE $ 100 por um período de 2 meses a partir da criação da conta para usar a infraestrutura e os serviços da Linode.
    
    **Requisitos:** Um cartão de crédito é necessário para se inscrever, mas você não será cobrado se o seu crédito acabar.
    
    **Link:** https://www.linode.com/lp/brand-free-credit

* **Alibaba Cloud**

    **Descrição:** Crédito de $300 que pode ser usado por um período de 12 meses a partir da criação da conta. Eles também fornecem Kubernetes na lista de recursos sempre gratuitos.
    
    **Link:** https://www.alibabacloud.com/

* **Redhat OpenShift**

    **Descrição:** PaaS de nó único sobre Kubernetes. Pode ser usado por um período de teste de 60 dias em sua conta RedHat.
    
    **Link:** https://www.openshift.com/try
    
* **CodeFresh**

    **Descrição:** Aproveita o Google Cloud Platform, oferece crédito de US$ 500 para experimentar o Kubernetes.
    
    **Link:** https://codefresh.io/google-cloud/
    
* **Civo Cloud**

    **Descrição:** Crédito de US$ 250 por um período de um mês a partir da criação da conta para usar os kubernetes e serviços do Civo.
   
    **Requisitos:** Um cartão de crédito é necessário para se inscrever, mas você não será cobrado se o seu crédito acabar.
   
    **Link:** https://www.civo.com/signup
    
* **Okteto Cloud**

    **Descrição:** Serviço Kubernetes gerenciado projetado para desenvolvedores. As contas de desenvolvedor gratuitas vêm com 8 GB de RAM, 4 CPUs e 5 GB de espaço em disco. Os aplicativos dormem após 24 horas de inatividade. Você tem acesso a um único namespace.
    
    **Requisitos:** Uma conta Github é necessária para se inscrever.
    
    **Link:** https://cloud.okteto.com/

* **Huawei Cloud**

    **Descrição:** Registre-se e ganhe 1500 horas de teste grátis. Até 10 Gb disponíveis para baixar e armazenar imagens de contêiner docker (sempre gratuito)
    
    **Requisitos:** É necessário um cartão de crédito para se inscrever
    
    **Link:** https://reg.huaweicloud.com/registerui/register.html/
    
* **DigitalOcean**

    **Descrição:** A DigitalOcean oferece 100$ de crédito de teste pelos primeiros 60 dias. Isso requer uma referência de usuários existentes ou use o URL abaixo, que é o URL de referência oficial.
    
    **Requisitos:** É necessário um cartão de crédito para se inscrever
    
    **Link:** https://m.do.co/c/8cce85e94a19

* **Kubernautic**

    **Descrição:** Rancher compartilhado ou dedicado como serviço para gerenciar e executar kubernetes no local ou como um serviço sem nuvem.
    
    **Preços:** Sempre Gratuito/Teste Gratuito/Pago Disponível . O plano gratuito para sempre inclui um único usuário, painel de rancheiro compartilhado, namespaces spot, 1CPU, 1Gi Mem. Enquanto o plano de avaliação gratuita inclui 2 usuários, painel de rancheiro compartilhado, namespaces com estado, 2CPU, 2Gi Mem, armazenamento de 10 GB.
    
    **Link:** https://kubernautic.com/

* **Plataforma de Nuvem Freebernetes (FCP)**

    **Descrição:** Cluster Kubernetes de curta duração para fins educacionais. Funciona em um modelo de crowdfunding, portanto, outros limites podem mudar ao longo do tempo. Restrições iniciais: 6h TTL, 2CPU, 4Gi Mem, 10Gi PV, IPv6 externo para plano de controle/trabalhadores.
    
    **Requisitos:** É necessário um e-mail válido.

    **Link:** https://try-fcp.org/
    
* **KraudCloudName**

    **Descrição:** Clusters kubernetes gratuitos com 32 GB de RAM durante a fase beta de 6 meses.
    
    **Requisitos:** Uma conta do Github é necessária para se inscrever e receber um convite.

    **Link:** https://kraudcloud.com/

&nbsp;
___

## Lista de opções gratuitas para rodar o Kubernetes localmente.
&nbsp;
* **Minikube**

    **Descrição:** Minikube é um kubernetes local, tudo o que você precisa é de um contêiner Docker (ou similarmente compatível) ou um ambiente de máquina virtual.

    **Requisitos:** Min 2 CPUs, 2 GB de memória, e 20 GB de espaço em disco livres e um gerenciador de container, como Docker, Hyper-V, KVM...
    
    **Link:** https://minikube.sigs.k8s.io/docs/start/ 

* **Kind**

    **Descrição:** Kind é uma ferramenta para executar clusters locais do Kubernetes usando “nós” de contêiner do Docker. Kind foi projetado principalmente para testar o próprio Kubernetes, mas pode ser usado para desenvolvimento local ou CI.
    
    **Requisitos:** Se você tiver go ( 1.17+ ) e o docker instalado go install sigs.k8s.io/kind@v0.17.0 && kind create cluster é tudo o que você precisa!
    
    **Link:** https://kind.sigs.k8s.io/docs/user/quick-start/
    

* **K3s**

    **Descrição:** K3s é uma versão reduzida do Kubernetes desenvolvida pela Rancher Labs. O K3s é ideal para executar cargas de trabalho de produção em locais remotos com recursos limitados ou em dispositivos IoT
    
    **Requisitos:** Min 1 CPU, 512Mb de memória, por otimizar todos os processos do cluster kubernetes em um processo único, utiliza de pouquíssimos recursos computacionais. 
    
    **Link:** https://docs.k3s.io/quick-start
    
* **Microk8s**

    **Descrição:** MicroK8s é um Kubernetes extremamente leve e rápido. O MicroK8s é ótimo para desenvolvimento, prototipagem e teste. Use-o numa VM como um k8s pequeno, barato e confiável para CI/CD. É também o Kubernetes de melhor nível de produção.

    **Requisitos:** Recomendado 4GB de memória, e pelo menos 20 GB de espaço em disco livres.
    
    **Link:** https://docs.k3s.io/quick-start

&nbsp;
___
### Tip bônus
&nbsp;
Para interagir com o cluster kubernetes é preciso utilizar a ferramenta Kubectl, você pode instalar através desse link:
https://kubernetes.io/docs/tasks/tools/

As operações mais comuns podem ser realizadas com os comandos abaixo:

* **kubectl get** - listar recursos
* **kubectl describe** - mostrar informações detalhadas sobre um recurso
* **kubectl logs** - mostrar os logs de um container em um Pod
* **kubectl exec** - executar um comando dentro de um contêiner em um Pod

Para maiores informações e referências acesse: https://kubernetes.io/docs/reference/kubectl/

