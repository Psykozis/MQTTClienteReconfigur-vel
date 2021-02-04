# MQTTClienteReconfigurável

Marlon Soares Sigales 04-02-2021

Neste esboço de firmware criamos uma página para escrever as configurações iniciais da nodemcu, como um cliente mqtt, dados de rede iniciais, ou qualquer outra aplicação.

Um ponto de acesso é criado na nodemcu com nome configura_node, sem senha, neste uma página é acessada por meio do endereço 192.168.4.1 para configurar inicialmente informações, no exemplo são informações referentes a rede que ela irá se conectar, broker MQTT, porta, id de cliente e rota de tópicos que ela irá escrever/ler, estes dados são gravados na EEprom ao enviar. 
Após enviado, ou cancelado, ou no decorrer de 4.5 minutos a rede é desfeita e a aplicação principal executada. 

Futura aplicação será incluir este esboço no projeto pubsub_mqtt_MULTITOPIC. 

O projeto está sendo realizado utilizando a IDE do Arduino.

Cópias podem ser feitas em partes ou integralmente desde que referenciando este projeto.
Copies can be made in part or in full as long as referencing this project. 
