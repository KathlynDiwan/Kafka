# Ponderada Kafka S2M8

Esse documento foi criado com o intuito de conseguir responder de forma clara o autoestudo ponderado de programação da semana 02. O autoestudo em questão exigia a criação d eum docker-compose com todos os parâmetros de um kafka e seus gerenciadores e um exemplo de produção e consumo de mensagem local.

Os serviços utilizados nessa atividade, são amplamente recomendadas em arquiteturas de dados distribuídas. O "Kafka", serve como uma plataforma de streaming distribuída de código aberto, projetada para lidar com o processamento em tempo real de grandes volumes de dados de maneira escalável, confiável e tolerante a falhas. Já o "Zookeeper" serve como um sistema de auxilio ao Kafka que mantem a consistência em sistemas distribuídos, como cluster de servidores, sistemas de gerenciamento de configuração e sistemas de alta disponibilidade. 


Steps para execução: 
- Primeiro de tudo, você deve iniciar com o comando `docker-compose up`
- Depois disso, iniciar dois terminais distintos, um que servirá como reciver, e um como sender. 
- As mensagens serão enviadas do produtor para o consumidor em questão.
- E para finalizar você deve colocar o comando  `docker-compose down`.
- Você conseguirá ver a troca de mensagens. 
