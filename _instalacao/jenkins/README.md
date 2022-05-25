# ADJ - Aplication Deploy Jenkins

## Objetivo desse tutorial
- Realizar download do Jenkins
- Realizar a instalação do Jenkins no Windows
- Realizar as primeiras configurações de acesso.

## Checklist

### Passo: Download

Para realizar o download do Jenkins acesse o link abaixo:

https://www.jenkins.io/download/

Depois selecione a opção **Windows** para que o download seja iniciado.

![Download Jenkins](/assets/images/Jenkins/jenkins_download_win.png)


### Passo: Instalação

Após a realização do download execute o Jenkins e siga os passos abaixo.

- Na tela inicial da instalação clique em **"Next"** para prosseguir.

![jenkins_instalacao_01](/assets/images/Jenkins/instalacao/jenkins_instalacao_01.png)

- Na tela seguinte clique em **"Next"** para prosseguir.

![jenkins_instalacao_02](/assets/images/Jenkins/instalacao/jenkins_instalacao_02.png)

- Na tela seguinte em *"Logon Type"* selecione a opção **Run service as LocalSystem** e clique em **"Next"** para prosseguir.

![jenkins_instalacao_03](/assets/images/Jenkins/instalacao/jenkins_instalacao_03.png)

#### **OBS:** Como a execução do Jenkins será local não é preciso informar o usuário e senha de domínio.

- Na tela seguinte clique no botão **"Test Port"** para verificar se a porta informada ( 8080 ), está disponível para ser utilizada na sua máquina.

![jenkins_instalacao_04](/assets/images/Jenkins/instalacao/jenkins_instalacao_04.png)

- Logo depois de testar a disponibilidade da porta, clique em **"Next"** para prosseguir.

![jenkins_instalacao_05](/assets/images/Jenkins/instalacao/jenkins_instalacao_05.png)

### **ATENÇÃO:** é recomendado que você tenha instalado em sua máquina o Java JDK 11

- Na tela seguinte informe o caminho da pasta onde está instalado o Java JDK 11 e clique em **"Next"** para prosseguir.

![jenkins_instalacao_06](/assets/images/Jenkins/instalacao/jenkins_instalacao_06.png)

- Na tela seguinte não precisa realizar nenhuma alteração, basta clicar em **"Next"** para prosseguir.

![jenkins_instalacao_07](/assets/images/Jenkins/instalacao/jenkins_instalacao_07.png)

- Na tela seguinte clique em **"Install"** para que seja realizado a instalação do Jenkins.

![jenkins_instalacao_08](/assets/images/Jenkins/instalacao/jenkins_instalacao_08.png)

- Na tela seguinte clique em **"Finish"** para concluir a instalação.

![jenkins_instalacao_finish](/assets/images/Jenkins/instalacao/jenkins_instalacao_finish.png)


### Passo: Configurações

- Nesse passo iremos realizar o primeiro acesso ao Jenkins.

### **ATENÇÃO:** Antes de abrir o Jenkins abra o gerenciador de serviços da sua máquina e confirme se o serviço do Jenkins está em execução.

![jenkins_config_servicos](/assets/images/Jenkins/configuracao/jenkins_config_servicos.png)

 - Depois de ter conferido se o serviço estava em execução abra o seu navegador de digite o seguinte.

> localhost:8080

logo de inicio o Jenkins vai pedir uma senha de administrador, para pegar essa senha até a pasta indicada pelo próprio Jenkins, conforme a imagem.

![jenkins_config_pass_admin](/assets/images/Jenkins/configuracao/jenkins_config_pass_admin.png)

Depois que colocar a senha clique em **"Continue"**.

- Na tela seguinte clique na opção **"Install suggested plugins"**.

![jenkins_config_customize](/assets/images/Jenkins/configuracao/jenkins_config_customize.png)

- Na tela seguinte o Jenkins ira começar a realizar as configurações iniciais. Aguarde o processo concluir.

![jenkins_config_getting_started](/assets/images/Jenkins/configuracao/jenkins_config_getting_started.png)

- Na tela seguinte cadastre os dados de acesso do adiministrador que usará para fazer login no Jenkins. Depois clique no botão **"Save and Continue"**

![jenkins_config_create_admin](/assets/images/Jenkins/configuracao/jenkins_config_create_admin.png)

- Na tela seguinte confirme se a URL do Jenkins está correta e clique no botão **"Save and Finish"**.

![jenkins_config_finish](/assets/images/Jenkins/configuracao/jenkins_config_finish.png)

- Agora basta clicar no botão **"Start Using Jenkins"** e você será encaminhado para a página de Dashboard.

![jenkins_config_start_jenkins](/assets/images/Jenkins/configuracao/jenkins_config_start_jenkins.png)

![jenkins_config_dashboard](/assets/images/Jenkins/configuracao//jenkins_config_dashboard.png)

## PARABÉNS!

![parabéns!](/assets/images/Jenkins/parabens.png)

Você acaba de instalar e configurar o Jenkins na sua máquina local, agora é começar a fazer testes de deploy.

- Quero muito saber seu feedback
    - O que achou do tutorial ?
    - Teria alguma dica para acrescentar ?