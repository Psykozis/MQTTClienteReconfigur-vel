# MQTTClienteReconfigurável

Marlon Soares Sigales 04-02-2021

Neste esboço de firmware criamos uma página para escrever as configurações iniciais da nodemcu como um cliente mqtt, ou qualquer outra aplicação.
Um ponto de acesso é criado na nodemcu com nome configura_node sem senha para configurar inicialmente informações referentes a rede que ela irá se conectar, broker MQTT, porta, id e rota de tópicos que ela irá escrever/ler e gravando na EEprom, após feito, ou cancelado, ou passado 4.5 minutos a rede é desfeita e a aplicação principal executada. 
Futura aplicação será incluir este esboço no projeto pubsub_mqtt_MULTITOPIC. 

Cópias podem ser feitas em partes ou integralmente desde que referenciando este projeto.
Copies can be made in part or in full as long as referencing this project. 
