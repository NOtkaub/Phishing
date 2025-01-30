Phishing com Kali Linux:

1. Abrindo o SEToolkit no Kali Linux
O primeiro passo é abrir o SEToolkit no terminal e aceitar os termos de uso.

2. Selecionando a Opção de Ataque
Dentro do menu principal, escolhe-se a opção Social-Engineering Attacks, que contém várias técnicas de engenharia social.

3. Escolhendo "Website Attack Vectors"
Esta opção permite realizar ataques baseados em sites, incluindo a clonagem de páginas para capturar credenciais.

4. Selecionando "Credential Harvester Attack Method"
O método Credential Harvester captura credenciais de login inseridas em páginas falsas.

5. Escolhendo "Site Cloner"
O SEToolkit oferece três formas de ataque: templates prontos, clonagem de site e importação personalizada. A opção Site Cloner é escolhida para copiar um site real.

6. Definição do Endereço IP
É necessário fornecer o IP da máquina Kali, que pode ser obtido com ifconfig ou ip a. Esse IP será o endereço onde a página falsa ficará hospedada.

7. Escolha do Site a Ser Clonado
Após fornecer o IP, o usuário deve indicar a URL do site a ser clonado. O SET baixa e reproduz a página de login indicada.

8. Início da Captura de Credenciais
Com a página falsa hospedada, qualquer usuário que acessá-la e inserir suas credenciais terá seus dados capturados. O SET exibirá as informações no terminal.

9. Tornando a Página Acessível a Vítimas
Se o atacante e a vítima estiverem na mesma rede, basta compartilhar o endereço http://[IP-do-Kali]. Para ataques externos, serviços como ngrok podem ser utilizados para expor a página na internet.

10. Finalizando o Ataque
Para encerrar o ataque, basta pressionar Ctrl + C no terminal, encerrando o servidor do SEToolkit.

![Captura de tela 2025-01-30 170158](https://github.com/user-attachments/assets/cae63589-0f10-444d-9344-0be2ad9fe24e)

